- it just simply using fake profile or hiding yourself.
- incognito: is just no history.
## proxy
1. forward proxy: forward client request to the internet.
    - provide ip address security.
    - example from a company.
2. Reverse proxy: to a company.
     - load balancing 
     - web acceleration
     - application firewall/WAF
3. transparent proxy: a proxy does not modify requests or responses.
4. Anonymous proxy: only for anonymous.
## proxy protocols 
- HTTP proxy:
    Handling http traffic
- Socks(socks5,socks4)
     - general proxy for ( http ,https ,smtp ,ftp)
### types of proxy chains
1. Dynamic chain: the way the proxy chain are list given.
    - if any of the server not working it will be skip.
    - if any of them serever that is not working
2. strict chain: if on of the proxy chain is not working it will stop working.
3. Round Robin chain:  it is like dynamic chain but if all are not working will again.
4. Random chain: the chain is random.
## TOR /the onion Routing /
- developed in military to gather information in anonymity.
- initial the name is "onion Routing".
- use RSA/Encryption/.
- It is slow.
- more than 7000 nodes they are volunteer.
- default 9050.
### 3 type of Node
1. entry node: the first relay
2. middle Relay: multiple intermediate relay
3. Exit Node: the last relay.
- ==torghost==: git clone it from the github.
## VPNs
- virtual private network.
- well secured.
- some vpn does not log some data.
![[Pasted image 20250712153326.png]]
### Type of VPN
1. SITE to SITE: to join company network over the internet.
    - allow multiple location  to communicate and act like local network.
2. Remote Access VPN: allow client to act as local network of other lan by creating virtual interface.
3. SSL VPN: done with our web browser. it on when you use like SSL/TLS protocols.
### types of vpn protocol
- every vpn use different encryption. but use similar protocols.
1. openVPN: it is open source.
2. IPSec/Ikev2: it create secure tunnel.
    - IKEv2: one of the fastest vpn.
3. WireGuard: new with good performace. use lower bandwith.
## OS for privacy
- Tails OS
- whonix os
- Qube Os
## Use Temporary Mail
- temp email for not expose your original email.
- https://temp-mail.org/
## True anonymity is hard
- operation security(opsec): is a process that identifies critical information to determine whether friendly actions can be observed by enemy intelligence.
- there is no solution for 100% anonymity.
## mac changer
- use command like macchanger.
1. sudo ifconfig wlan0 down
2. sudo macchanger -r wlan0 (random )
3. sudo macchanger -m mac_address for (manual change)
4. machcanger -s Wlan0.
5. sudo ifconfig wlan0 up
![[Pasted image 20250712163548.png]]
## WEb
-  Deep web: they aren't indexed.
- serface web:
- Dark web: illegal trade must use onion browser. it is intentional hide.