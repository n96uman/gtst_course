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
- SQL injection (SQLi) is a web security vulnerability that allows an attacker to interfere with the queries that an application makes to its database. This can allow an attacker to view data that they are not normally able to retrieve
## sql command
- to know the database version "select all from v$version".
- to list of table "Select * from information_schema.tables"
- for comment: "--" 
### Demo of sql injection
1. http request:https://insecure-website.com/products?category=Gifts'+OR+1=1--
2. change to sql: SELECT * FROM products WHERE category = 'Gifts' OR 1=1--' AND released = 1
## Detect sql injection

You can detect SQL injection manually using a systematic set of tests against every entry point in the application. To do this, you would typically submit:

- The single quote character `'` and look for errors or other anomalies.
- Some SQL-specific syntax that evaluates to the base (original) value of the entry point, and to a different value, and look for systematic differences in the application responses.
- Boolean conditions such as `OR 1=1` and `OR 1=2`, and look for differences in the application's responses.
- Payloads designed to trigger time delays when executed within a SQL query, and look for differences in the time taken to respond.
- OAST payloads designed to trigger an out-of-band network interaction when executed within a SQL query, and monitor any resulting interactions.
## sql injection example
1. Retrieving hidden data
2. subverting application logic
3. union attacks 
4. blind sql injection :Many instances of SQL injection are blind vulnerabilities. This means that the application does not return the results of the SQL query or the details of any database errors within its responses.
5. First-order sql injection: when the http request is directly change in to sql query.
6. Second-order injection: it is when http request is store for the future use.
- After you identify a SQL injection vulnerability, it's often useful to obtain information about the database.

# ## String concatenation

You can concatenate together multiple strings to make a single string.

|   |   |
|---|---|
|Oracle|`'foo'\|'bar'`|
|Microsoft|`'foo'+'bar'`|
|PostgreSQL|`'foo'\|'bar'`|
|MySQL|`'foo' 'bar'` [Note the space between the two strings]  <br>`CONCAT('foo','bar')`|

## ## Database version

You can query the database to determine its type and version. This information is useful when formulating more complicated attacks.

|   |   |
|---|---|
|Oracle|`SELECT banner FROM v$version   SELECT version FROM v$instance   `|
|Microsoft|`SELECT @@version`|
|PostgreSQL|`SELECT version()`|
|MySQL|`SELECT @@version`|

