# libcli
Standalone command line interface (CLI) library from Quagga Routing Suite, GPL licensed


- Test on:
Ubuntu 18.04


- Build:
```scons```


- Example:
```sh
user@localhost:~/tmp/cli $ ./test_cli 

Hello, this is Quagga (version 1.2.2).
Copyright 1996-2005 Kunihiro Ishiguro, et al.

localhost> list
  show version
  list
  enable
  exit
  quit
  terminal length <0-512>
  terminal no length
  show daemons
  ping WORD
  ping ip WORD
  traceroute WORD
  traceroute ip WORD
  ping ipv6 WORD
  traceroute ipv6 WORD
  telnet WORD
  telnet WORD PORT
  ssh WORD
  show memory
  show work-queues
  show work-queues (zebra|ripd|ripngd|ospfd|ospf6d|bgpd|isisd)
  show thread cpu [FILTER]
  show logging
localhost> 
localhost> 
```

- References:


https://www.nongnu.org/quagga/docs/quagga.pdf

https://the-eye.eu/public/Books/IT%20Various/For.Dummies.Linux.Smart.Homes.For.Dummies.Aug.2006.pdf

http://tcpflag.blogspot.com/2010/03/using-quaggas-command-line.html

https://docs.cumulusnetworks.com/display/CL332/Configuring+Quagga

https://www.nongnu.org/quagga/docs/docs-multi/VTY-shell.html#VTY-shell


