\# Active Directory Basics



\## Overview



Active Directory (AD) is a directory service developed by Microsoft for managing users, computers, groups, policies, and authentication within Windows environments.



Active Directory is widely used in enterprise networks and is a major focus area in cybersecurity and SOC operations.



\---



\## Main Functions of Active Directory



AD helps organizations:

\- centralize authentication

\- manage users and devices

\- enforce security policies

\- control access to resources



\---



\## Domain



A domain is a centralized environment where users and systems are managed.



Examples:

\- company.local

\- enterprise.internal



All devices joined to the domain can authenticate using centralized credentials.



\---



\## Domain Controller (DC)



A Domain Controller is a server that manages:

\- authentication

\- authorization

\- directory services



The DC stores the Active Directory database.



\---



\## Organizational Units (OUs)



OUs are containers used to organize:

\- users

\- groups

\- computers



Example:

\- HR Department

\- IT Department

\- SOC Team



\---



\## Users and Groups



\### Users



Represent individual accounts used for authentication.



\---



\### Groups



Used to manage permissions efficiently.



Examples:

\- Domain Admins

\- IT Support

\- Security Analysts



\---



\## Authentication in Active Directory



AD commonly uses:

\- Kerberos

\- NTLM



for authentication processes.



\---



\## Kerberos Authentication



Kerberos is the primary authentication protocol in Active Directory.



Benefits:

\- mutual authentication

\- ticket-based authentication

\- reduced password transmission



\---



\## Group Policy (GPO)



Group Policy allows administrators to enforce configurations across systems.



Examples:

\- password policies

\- USB restrictions

\- software deployment



\---



\## Common Active Directory Attacks



Examples:

\- Pass-the-Hash

\- Kerberoasting

\- Password Spraying

\- Golden Ticket attacks



AD is frequently targeted during enterprise intrusions.



\---



\## Importance in SOC Operations



SOC analysts monitor:

\- failed logins

\- privilege escalation

\- suspicious PowerShell activity

\- abnormal account behavior



\---



\## Common Security Risks



Examples:

\- weak passwords

\- excessive admin privileges

\- disabled logging

\- outdated domain controllers



\---



\## Security Best Practices



Recommended practices:

\- enable MFA

\- enforce least privilege

\- monitor authentication logs

\- patch domain controllers

\- restrict administrative access



\---



\## Active Directory in Cybersecurity



AD knowledge is important for:

\- SOC analysis

\- threat hunting

\- incident response

\- penetration testing



Most enterprise environments rely heavily on Active Directory.



\---



\## Conclusion



Active Directory is a foundational component of enterprise identity management and security. Understanding AD architecture, authentication, and security risks is essential for cybersecurity professionals.

