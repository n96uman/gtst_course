- ==uri identifies==: (uniform resource identifier) a resource and differentiates it from others by using a name, location or both.
- ==url idnetifies==: (uniform resource locater) a web address or location of a unique resource.
- https://blog.bushpot.com/marketing
- scheme(protocol)//subdomain.secondleveldomain.top-level domain/subdirectory.
1. ==scheme==: the protocol used.
2. ==subdomain==: which section of the domain.
3. ==top-level domain==: specifiy the type of entity that the organization registers as.
    - Generic top-level domain(tld): gov.com.net
    - counry code top-level domain: et.ru..
4. ==second-level domain==: the name of the website.
5. ==subdirectory==: also known as subfolder ,helps people understand which particular section of a wabpage they are on.
- the apache web is found under /var/www/html
 - routes: check if it is route.
 ## DNS
 - resolves = change into ip address.
 ## HTTP request and response
 ### http header
 - are used to pass information between the clients and the server through the request and response header.
 - uses key value pair,clear text and case-insensitive.
 ### header type
 1. General header: a header that work for both.
     - cache header
 2. request header:
    - host,user-agent
 3. Response header: server and location
 4. Entity Header: tell more about the body of the resource.
     - content type and length.
## Request header
1. First line contains
    - GET/http/1.1
    - method/path/version
- use-agent : information about the browse user.
- curl: for simple http request.
## Response Header
http/2 200 ok
Date:
content-length
content-type
server
- hsts: it force the http to use https.
## http Request methods
1. GET: Request for resource from server
2. Post : submit data to the server 
3. Head: same as Get but does not return the body.
4. put: the data must be stored at the url supplied
5. Delete: Delete a resource.
6. Options: Return the http method support by the server.
7. connect: to make the proxy forward the connection.
## http parameters
-  each type server difference purpose 
1.  ==Query parameters==: append to the end of the url and are used to pass additional data to the server.
    - it used in "GET" request
    - to put the parameters we gone use "?" after that "&" is a parameter separator.
    - used most of the time for filtering.
2. ==path parameters==: it use for specific access of a resource and it will be part of the url.
3. ==body parameters==:mostly used for put,push to fetch data and it contain the data in http body.
## web attacks
## SSRF
- A vulnerability where an attacker tricks the server into making unintended requests to internal or exeternal systems.
## path Traversal 
- A vulnerability that allows attackers to access files and dir outside the intended scope of the web application.
## CSRF
- when the attacker tick unintended actions on a web application where they are authenticated.

## FFUF(Fuzz faster u fool)
- used to pentest it is used for directory, subdomains brut force
- ffuf -w wordlist -u url -h header
- we can find word list in : /usr/share/wordlists/fasttrack.txt
## WEb server
B. Nginx Server:
    - config file: etc/nginx/nginx.conf
    - log file: /var/log/nginx/access.log
c. python server:
    - python3 -m http.server portnumber
## API(application program interface)
- they are a web request to connect fronted and backend.
# roadmap 
![[Pasted image 20250615193436.png]]

![[Pasted image 20250615193516.png]]
