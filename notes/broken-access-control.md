\# Broken Access Control



\## Overview



Broken Access Control occurs when applications fail to properly restrict user actions and resource access.



This vulnerability allows attackers to:

\- access unauthorized data

\- perform restricted actions

\- escalate privileges

\- manipulate application functionality



Broken Access Control is one of the most critical vulnerabilities in the OWASP Top 10.



\---



\## What is Access Control?



Access control determines:

\- who can access resources

\- what actions users can perform

\- what permissions are assigned



Access control protects sensitive systems and data from unauthorized use.



\---



\## Types of Access Control



\### Role-Based Access Control (RBAC)



Permissions are assigned based on user roles.



Example roles:

\- admin

\- user

\- analyst



\---



\### Attribute-Based Access Control (ABAC)



Access decisions are based on attributes such as:

\- department

\- device

\- location

\- time



\---



\### Discretionary Access Control (DAC)



Resource owners determine who can access resources.



\---



\## Common Broken Access Control Vulnerabilities



Examples:

\- accessing admin pages without authorization

\- modifying URLs to view other users’ data

\- privilege escalation

\- bypassing restrictions through API requests



\---



\## Insecure Direct Object References (IDOR)



IDOR vulnerabilities occur when attackers manipulate identifiers to access unauthorized resources.



Example:



```text

/user/1001

```



Changing the ID may expose another user’s data.



\---



\## Privilege Escalation



Attackers gain higher permissions than intended.



Examples:

\- normal users gaining admin access

\- modifying hidden parameters

\- abusing insecure APIs



\---



\## Forced Browsing



Attackers manually browse restricted directories or pages.



Examples:

\- /admin

\- /backup

\- /config



\---



\## API Access Control Issues



Modern applications often expose APIs with weak authorization checks.



Possible risks:

\- data exposure

\- unauthorized actions

\- account compromise



\---



\## Common Impacts



Broken access control may lead to:

\- sensitive data exposure

\- account takeover

\- unauthorized administrative access

\- data modification



\---



\## Detection Methods



Security analysts identify access control issues through:

\- penetration testing

\- API testing

\- authorization checks

\- manual application testing



Tools:

\- Burp Suite

\- Postman

\- OWASP ZAP



\---



\## Prevention Techniques



\### Enforce Server-Side Authorization



Applications should validate permissions on the server side.



\---



\### Use Least Privilege



Users should only receive necessary permissions.



\---



\### Deny by Default



Access should be denied unless explicitly allowed.



\---



\### Validate User Access



Applications should verify ownership of resources before granting access.



\---



\## Logging and Monitoring



Organizations should monitor:

\- unauthorized access attempts

\- privilege changes

\- unusual API requests

\- suspicious user behavior



\---



\## Importance in Cybersecurity



Broken access control vulnerabilities are highly dangerous because they directly affect authorization and sensitive data protection.



\---



\## Conclusion



Broken Access Control is a major web application security risk that can lead to unauthorized access and privilege escalation. Proper authorization validation and least privilege access are essential for secure applications.

