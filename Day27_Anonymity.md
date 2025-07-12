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