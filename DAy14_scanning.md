## ==Nmap==(network mapper): 
### live system Discovery 
1. ping sweep : uses ICMP protocol and it send echo request and wait echo reply.
     os 
     - window (32byte)
        - ttl: 108
    - linux 
        - ttl:64
2. when we use ping in nmap : nmap -sn IP (no port scan)
3. how do we identify all host on a network? - -
- nmap -sn  netwokaddresss - 255
- namp -sn netwoladdress/netwolbits(subnet mask) this will not work on virtual machines network.
- host discovery -Pn for nmap when the host reject any icmp protocol. : nmap -Pn ip.
### ports   nmap -p port 1, port 2 ip
1. open port : live system discovery.
2. nmap -sT IP for tcp scan  -sT(scan TCP)
