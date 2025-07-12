### Stealth Scan : nmap -sS 
- This scan we don't send the last ACK flag :
### UDP scann : NMAP -sU ip
### Xmas Scan : nmap i-sX
- first send FIN/PSH/URG
### operating system Detection
- nmap -O or -A
### banner Grabbing : -sV for version 
- it the  whetext or matadata n you connect with any port
### Scan speeds
- insane -T5 : sending packets insane fast and waits only 0.3 seconds for the response.
- Aggressive -T4 : sending packets very fast and wait only 1.25 second for the response.
- Normal -T3 : default 
- polite -T2 : these are the slowest timing.
- sneaky -T1
### nmap script engine(NSE) : nmap -sC 
- nmap --script --scriptname.nse ip
- namp -p  80 --script scriptname.nse  ssh* ip
- nmap is is capable of running some script on port and service.
- ==--script vuln== test if the port is vulnerable.
### nmap output 
- nmap can save out put using.
- -oG ->for Greppable format .
- -oX -> for xml format .
- -oN -> for normal saving formats.
### namp verbose
- display more information 
- nmap -v -little detial
- nmap -vv -more detail
- nmap -vvv -much more details
## nmap firewall Evasion
intrusion detection system (ids) the firewall detection system
1. ==Decoy scan==:nmap -D RND:5 or decoy1,decoy2
    - use decoy ip addresses to obscure the orgiin of a scan.
2. ==Fragment packets :== nmap -f -p21 [target ip]
    - send you scan by fragment.
3. ==mac address spoofing==: nmap -spoof -mac Apple/MAc_Address -Pn IP
4. ==source port manipulation==: nmap -g [port] -p 21 ip.
    - change destination port.