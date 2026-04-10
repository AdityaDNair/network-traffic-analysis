\# SQL Injection (SQLi)



\## Overview



SQL Injection (SQLi) is a web application vulnerability that occurs when user input is improperly validated and executed as SQL commands by the backend database.



SQL Injection is one of the most dangerous web vulnerabilities because it can allow attackers to:

\- bypass authentication

\- access sensitive data

\- modify databases

\- execute administrative operations



\---



\## How SQL Injection Works



Applications often interact with databases using SQL queries.



Example vulnerable query:



```sql

SELECT \* FROM users

WHERE username='$user'

AND password='$pass';

```



If user input is not sanitized, attackers can inject malicious SQL code.



\---



\## Example Payload



```sql

' OR '1'='1

```



This payload can manipulate the query logic and potentially bypass authentication.



\---



\## Authentication Bypass Example



Original query:



```sql

SELECT \* FROM users

WHERE username='admin'

AND password='password';

```



Injected query:



```sql

SELECT \* FROM users

WHERE username='admin'

AND password='' OR '1'='1';

```



Because the condition is always true, access may be granted.



\---



\## Types of SQL Injection



\### 1. In-Band SQL Injection



The attacker receives results directly through the application.



Examples:

\- error-based SQLi

\- union-based SQLi



\---



\### 2. Blind SQL Injection



The application does not directly reveal database errors.



Attackers infer information through:

\- response behavior

\- timing differences



\---



\### 3. Out-of-Band SQL Injection



Data is exfiltrated using external communication channels.



\---



\## Common Impacts



SQL Injection can lead to:

\- credential theft

\- database dumping

\- unauthorized access

\- data modification

\- server compromise



\---



\## Detection Methods



Security analysts may identify SQLi through:

\- unusual database errors

\- suspicious input patterns

\- abnormal application responses

\- SIEM alerts



\---



\## Common Testing Payloads



Examples:



```sql

'

```



```sql

' OR '1'='1

```



```sql

UNION SELECT NULL,NULL--

```



\---



\## Prevention Techniques



\### Prepared Statements



Parameterized queries separate user input from SQL logic.



Example:



```python

cursor.execute("SELECT \* FROM users WHERE username = ?", (username,))

```



\---



\### Input Validation



Applications should validate and sanitize user input.



\---



\### Least Privilege Access



Database accounts should only have necessary permissions.



\---



\### Web Application Firewalls (WAF)



WAFs can help detect and block malicious SQL injection attempts.



\---



\## SQL Injection in Penetration Testing



Penetration testers commonly test:

\- login forms

\- search boxes

\- URL parameters

\- API requests



Tools used:

\- Burp Suite

\- SQLMap

\- OWASP ZAP



\---



\## Importance in Cybersecurity



SQL Injection remains a major security risk in web applications and is included in the OWASP Top 10.



Understanding SQLi is important for:

\- SOC analysts

\- penetration testers

\- developers

\- security engineers



\---



\## Conclusion



SQL Injection is a serious web application vulnerability that can compromise databases and sensitive information. Proper input handling, parameterized queries, and secure coding practices are essential defenses against SQLi attacks.

