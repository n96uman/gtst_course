![[Pasted image 20250622104554.png]]
## Types of wireless tech
1. WI-FI(wireless Fidelity)
- use high speed internet network
2. Bluetooth
   - can work for 100 meter.
3. Zigbee
- low-power consumption mostly for iot.
4. NFC(Near Field communication)
    - it work for 4 cm. operate 13.56 mhz.
    - vulnerabilities : card cloning.
5. cellular Networks(3g,4g,5g)
    - data transfer in large distance.
## Wireless Hacking

   ### Radio signa; Encoders and Decoders
- Encoders: convert data into radio signal for transmission.
- Decoder: convert radio signals back into data.
### Wi-fi hacking

- wifi hacking is exploiting a wifi vulnerability and Gaining Acess to that network.
- when our wireless cards are converted in sniffing modes, They are called ==monitor mode==.
- when we use it to configure a AP on your laptop manually it is called ==managed mode==.
- for this we need a Wi-fi Antenna for our computer.
- SSID(service set identifier):it is the name of the Access point.
- BSSID(Basic Service Set identifier): Mac address of the Wireless AP Device.
- channel: small bands within frequency bands that used by our wireless.
- 2 ghz: 13 wi-fi  channel.
- 5 ghz : 45 wi-fi channel.
## Wireless encryption protocols
- WEP
- WPA
- WPA2
- WPA3
### WEP-wired Equivalent privacy.
- use RC4 stream cipher. 40 bit in hexadecimal. it uses one key.
- stope in 2004.
## WPA- wi-fi protected Access
- uses temporal key integrity protocol(tkip).
- wpa key is a pre-shared key(password) that you use to connect to wireless network.
- you can get the key from who ever runs the network.
## WPA2
- uses AES instead of RC4.
- vulnerable that called krack it uses clone.
## WPA3
- uses Device provisioning protocol(DDP).
- and uses GCMP-256 encryption.
## WLAN Recon
- to change in to monitor mood airmon-ng.
- to get information about the network we use airodump-ng.
# hacking Wlan
1. WPs Enabled
    - use  digit code to connect.
    - in linux we can use reaver.
2. handshake bruteforce.
    - four way handshake.
    - verify the the input password without sharing the real password.
    - kick someone out and sniff there handshake when they try re-conect.
    1. sniff the network:
        syntax: airdump-ng "'interface" -channel "channel" -w "filename"
    2. Deuth: kick out of wi-fi user
        syntax: aireplay-ng -o "size" -a "mac-target" "interface".
    3. capturing handshake
        - we gone use Aircrack.
        - we can use a wordlist from usr/share/wordlist/rockyou.txt
        - Syntax: aircrack "cap" -w "wordlist".
3.  WEP attack:
        - similar with the handshake but it bruteforce the encryption key.
4. evil-twin attack: 
    - clone the origin wifi
    a. Deauthentication
    b. Fake AP and 
    c. phishing
    ![[Pasted image 20250622131521.png]]
    - tools: airgeddon.sh.
    - to install :![[Pasted image 20250622131852.png]]
## Bluetooth hacking
- 2.4-2.485 GHZ.
- to use bluetooth we must install: 
- sudo apt install bluetooth bluez-tools rfkill blueman.
- hciconfig.
1. Bluejacking: sending message over bluetooth.

## SS7 Attack
- that attack on weakness of cellular.
- it illegal to do it.
## Mobile Security
### Android Architecture
- it based on linux kernel and it have c and c++.uses Dalvik virtual machine.
