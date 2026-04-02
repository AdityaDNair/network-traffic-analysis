\# Common Types of Cyber Attacks



\## Overview



Cyber attacks are malicious attempts to compromise systems, networks, applications, or data. Attackers use different techniques to steal information, disrupt services, gain unauthorized access, or damage infrastructure.



Understanding common attack types is important for cybersecurity professionals and SOC analysts.



\---



\## Phishing Attacks



Phishing is a social engineering attack where attackers trick users into revealing sensitive information.



Common targets:

\- usernames

\- passwords

\- banking details

\- MFA codes



Attackers often use:

\- fake emails

\- fake login pages

\- malicious attachments



\---



\## Malware Attacks



Malware is malicious software designed to harm systems or steal data.



Types of malware include:

\- viruses

\- worms

\- trojans

\- spyware

\- ransomware



\---



\## Ransomware



Ransomware encrypts files and demands payment for decryption.



Common impacts:

\- data loss

\- operational disruption

\- financial damage



\---



\## Denial of Service (DoS)



A DoS attack attempts to overwhelm a system or service and make it unavailable.



\---



\## Distributed Denial of Service (DDoS)



DDoS attacks use multiple systems to flood a target with traffic.



Common targets:

\- websites

\- online services

\- DNS infrastructure



\---



\## SQL Injection (SQLi)



SQL Injection occurs when attackers insert malicious SQL commands into application inputs.



Possible impacts:

\- authentication bypass

\- database leakage

\- data modification



Example payload:



```sql

' OR '1'='1

```



\---



\## Cross Site Scripting (XSS)



XSS attacks inject malicious JavaScript into web applications.



Types:

\- Stored XSS

\- Reflected XSS

\- DOM-based XSS



Example payload:



```html

<script>alert('XSS')</script>

```



\---



\## Brute Force Attacks



Attackers repeatedly attempt passwords until successful authentication occurs.



Common targets:

\- SSH

\- RDP

\- web logins



\---



\## Credential Stuffing



Attackers use leaked username/password combinations from previous breaches.



\---



\## Man-in-the-Middle (MITM)



MITM attacks intercept communication between two parties.



Possible impacts:

\- credential theft

\- session hijacking

\- traffic manipulation



\---



\## Insider Threats



Insider threats come from individuals within the organization.



Examples:

\- malicious employees

\- careless users

\- compromised accounts



\---



\## Zero-Day Exploits



Zero-day vulnerabilities are security flaws unknown to vendors and unpatched at the time of exploitation.



These attacks are highly dangerous because no official fix exists initially.



\---



\## Social Engineering



Social engineering manipulates human behavior to gain unauthorized access.



Examples:

\- phishing

\- baiting

\- impersonation

\- tailgating



\---



\## Importance of Detection and Prevention



Organizations use:

\- firewalls

\- IDS/IPS

\- SIEM tools

\- EDR solutions

\- employee awareness training



to reduce attack risks.



\---



\## Conclusion



Understanding common cyber attacks helps security professionals identify threats, investigate incidents, and implement effective security controls to protect systems and data.

