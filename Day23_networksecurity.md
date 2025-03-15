## Tshark like wireshark but with command line.
for filter -y 
Reading picaps file -r 
for capturing -w
for time -t 
to limit the capture -c
## TCPdump
for loop back
# What is ARP ?
# MAC flodding
most common network attacks.
it work by sending a lot of fake mac ports and over writing the reel users.
syntax : macof -i wlano -n 10 -d 192.168.0.4

## prevention
1. port security - limits the no of mac addresses connecting to a single port on the switch.
- command : switch port -security maximum 5
1. MAC filtering - limits the no of mac addresses to a certain extent.
# ARP Spoofing / ARP Cache poisoning 
demo
1. WE will get the mac of our gateway
2. we will get our linux machine mac
    a. arp -g
3. Enable ip forward
    a sudo sysctl net.ipv4.ip_forward=1
4. Disable Firewall
    sudo ufw disable 
5. Start the spoofing with arpspoof tools 
    a. Arpspoof -i interface -t target -r defaultgatewayip
NOTE:
- ip of attacker 
- ip victim
- getewap
### for advanced use better cap.
1. install bettercap 
2. start bettecap
3. scan the network 
    - net.probe on
    - netshow => to use the network 
4. Start arp spoofing 
    a. set arp.spoof.targets <ip>
    b. set arp apoof.fullduplex true
    c. arp.spoof on 
5. Enable forwarding and Disable Firewall
    a. sudo sysctl net.ipv4.ip_forward=1
    b. sudo ufw disable
6. start Mitm
    a. net.sniff on
    b. net sniff off
## prevention
1. Using static ARP table
2. Switch security 
3. Encryption 
## DNS spoofing 
using DNS cach poising 
we can use bettercap here to.  with 
HTST = http -> https


==protocol down grading attack==
oposite of hsts

#DOS and DDOS Attacks
DOs from one pc 
DDOs form more than one pc
TOOLS
1. solarWind security EVent manager (SEM)
2. MANAgeEngine log360
3. HULK
4. Tor's Hammer
5. slowloris
6. LOIC
7. XOIC
8. DDOSIM
9. RUDY
10. PyLoris

The most popular and effective is MEGAMedusa
prevention
we can use Cloudflare.