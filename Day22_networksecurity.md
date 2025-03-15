## what is network Hacking?
 1. network spoofing 
  ## ping
    -c for count
    -s packet size
    1. fping : to fing multiple hosts simultanously.
    2. nping : allowing more advancd packet crafting and timing tests.
    3. hping : a more advanced tools that allow sending tcp , udp and icmp.

Traceroute 
    -T (tcp)
mtr google.com for dynamic.
Nestat short for (network statistics)
    display network connection.
    -l for listen ports
    -p for process.
SS (socket statistics)
- used to investigate sockets.
- it provide detailed information  about network connections , listening ports and more.
- it is often preferred over netstat for its faster performance and more detailed output.
- -t:tcp , u-:udp -l: listening -p:process n=number
## network sniffing
1. passive sniffing : you can see not change it work with hub.no more effective.
2. Active sniffing: you can alter it.
# WireShark
it is called protocol analyzer
Statistic -> protocol hierarchy 
## Filter commands
- ip.src == ipadders && ip.drs == ipadress
- ip.src eq ipadders && ip.drs eq ipadress

