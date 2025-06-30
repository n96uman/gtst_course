## Types of sql injection
1. IN-Band(classic):use the same channel to attack and gain information.
    1. Error: force the database to generate an error.
    2. Union: to marge two sql query to give one result.
2. Inferential(Blind):There is no transfer of data.
    1. Boolean: use Boolean repsonce.
    2. Time: 
3. Out-of-Band: use different channel to attack and gain info. maybe use http request to insert the sql injection.
## Finding sqli Vulnerabilities
1. Black box:
    - Map the application.
    - Fuzz the application.
2. White box:
    - Enable web server logging
    - Enable database logging
    - Map the application
## Exploit of sql  injection
## Union-Based sqli
- there are two rules
1. the number and the order of the columns must be the same in all queries.
2. the data type must be compatible.
## Exploiting
-  determine the columns using "order by ":
- Determining the number of columns required in an sql injection Union attack using "NULL values".
## How to prevent sqli vulnerabilities
1. primary defenses:
    - use of prepared statements(parametrized queries)
    - use of stored procedures (partial)
    - whitelist input validation (partial)
    - escaping All user supplied input (partial)
2. Additional Defenses:
    - Also : enforcing least privilege
    - Also : performing whitelist input validation as a secondary defense.