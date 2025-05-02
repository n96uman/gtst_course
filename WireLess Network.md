## types of wireless technology
- wifi , Bluetooth , Zigbee , NFC , Cellular Network , LpRa , infrared.
## WIFI (Wireless Fidelity)
- short and medium range
## Bluetooth
- short distance and work for 100 meters.
## Zigbee
- a low power consumption. for IOT.
## NFC (Near Field communication)
- 4 cm.
- operates 13.56 MHz.
- card cloning vulnerabilities.
## Cellular Network (3G,4G,5G)
- mobile for network.
## What is wireless Hacking
### Radio Signal Encoders and Decoders
- Encoders : converting to radio wave.
- Decoders: convert to signal wave.
### WI-FI(wireless Fidelity)
- Exploiting wifi vulnerability and Gaining Access to that network.
- AP(access point): transmit and accept wireless radio.
- wireless card: 
- moniter mode: for sniffing
- managed mode: configure AP on your laptop.
## WIFI term
- SSID/service set identifier/: wifi name
- BSSID/ Basic service set identifier: MAC Address of the wireless AP device.
## Wireless Encryption Protocol
- Wireless Encryption protocol are algorithms.
1. WEP- Wired Equivalent privacy:  uses RC4 cipher 40 bit key in hexadecimal and static key(the same key). stop at 2004.
2. WPA- WI-FI protected Access : uses TKIP(temporal key integrity protocol) encryption. which dynamically change the key of the user. you can get the password who ever connect to the wi-fi.
3. WPA2: they start use AES. vulnerability is clone the wi-fi(KRACK).
4. WPA3 uses Device provisioning protocol(DDP). and GCMP-256 encryption. in 2019.
## WLAN Recon
- to change manage mood to monitor mood use airmon-ng.
- sudo airmong-ng start wlan0.
- sudo airmong-ng wlan0.
![[Pasted image 20250418140226.png]]
## Hacking wi-fi
1. WPS Enable: tools reaver
2. Handshake Bruteforce(4-way handshake):  used on WPA/WPA 2.
    -  kick user from wi-fi.
    -  the user will try to reconnect using 4 way handshake.
    1. Sniffing to the network. use airodump-ng wlan0 --channel 4 -w geez
    2. Deauth(de authentication) : kick some one out.
        - aireplay-ng -0 100 -a mac_address wlan0
    3. Cracking : aircrack-ng geez -w rockyou.txt.
3. Evil-Twin Attack: using KRACK vul.
    - includes
    1. DEauth
    2. Fake AP and
    3. Phishing
    - airgeddon.sh from git.
    - ![[Pasted image 20250418151626.png]]
## Bluetooth HAcking
- 2.4 - 2.485 GHZ. we called it paiting.
- we can find the following information
    name.
- sudo apt install bluetooth bluez-tools rfkill blueman.
- hciconfig : to see the details.
- hcitools scan
### Bluetooth Attacks
1. Bluejacking: sending messages over bluetooth.
2. Bluesnarfing
3. BlueDucky
4. BlueBugger: 
## SS7 Attack
- SS(Signaling system)