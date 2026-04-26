\# MITRE ATT\&CK Framework Basics



\## Overview



The MITRE ATT\&CK Framework is a globally recognized knowledge base of attacker tactics, techniques, and procedures (TTPs) based on real-world cyber attacks.



Security teams use MITRE ATT\&CK for:

\- threat hunting

\- incident response

\- detection engineering

\- SOC operations

\- adversary emulation



\---



\## What is ATT\&CK?



ATT\&CK stands for:



```text

Adversarial Tactics, Techniques, and Common Knowledge

```



The framework organizes attacker behavior into categories that help defenders understand how attacks occur.



\---



\## Tactics vs Techniques



\### Tactics



Tactics represent the attacker’s objective.



Examples:

\- Initial Access

\- Persistence

\- Privilege Escalation

\- Credential Access



\---



\### Techniques



Techniques describe how attackers achieve those objectives.



Example:

\- phishing

\- PowerShell execution

\- credential dumping



\---



\## Common MITRE ATT\&CK Tactics



\### Initial Access



How attackers first enter an environment.



Examples:

\- phishing

\- exposed services

\- malicious attachments



\---



\### Execution



How attackers run malicious code.



Examples:

\- PowerShell

\- command-line execution

\- scripts



\---



\### Persistence



How attackers maintain long-term access.



Examples:

\- startup tasks

\- registry modifications

\- scheduled tasks



\---



\### Privilege Escalation



Attackers gain higher permissions.



Examples:

\- exploiting vulnerabilities

\- token manipulation

\- credential abuse



\---



\### Defense Evasion



Attackers avoid detection.



Examples:

\- disabling security tools

\- obfuscation

\- log deletion



\---



\### Credential Access



Attackers steal credentials.



Examples:

\- keylogging

\- LSASS dumping

\- password spraying



\---



\### Lateral Movement



Attackers move between systems.



Examples:

\- SMB abuse

\- RDP usage

\- remote services



\---



\### Exfiltration



Attackers steal sensitive data.



Examples:

\- cloud uploads

\- encrypted transfers

\- DNS tunneling



\---



\## ATT\&CK in SOC Operations



SOC analysts use ATT\&CK to:

\- classify attacker behavior

\- improve detection rules

\- investigate incidents

\- map alerts to techniques



\---



\## Threat Hunting with ATT\&CK



Threat hunters search for behaviors associated with known ATT\&CK techniques.



Example:

\- suspicious PowerShell execution

\- credential dumping activity

\- unusual remote access



\---



\## Detection Engineering



Security teams create SIEM detections mapped to ATT\&CK techniques.



Example:

\- alert on encoded PowerShell commands

\- detect suspicious scheduled tasks



\---



\## MITRE ATT\&CK and Threat Intelligence



Threat intelligence reports often reference ATT\&CK techniques to describe attacker behavior.



\---



\## Benefits of ATT\&CK



The framework helps organizations:

\- improve visibility

\- understand attacker behavior

\- strengthen detections

\- standardize investigations



\---



\## Common Security Tools Using ATT\&CK



Examples:

\- SIEM platforms

\- EDR solutions

\- threat hunting tools

\- security analytics platforms



\---



\## Importance in Cybersecurity



MITRE ATT\&CK is widely used across:

\- SOC operations

\- red teaming

\- blue teaming

\- threat intelligence

\- incident response



\---



\## Conclusion



The MITRE ATT\&CK Framework provides a structured way to understand attacker behavior and improve cybersecurity defenses. It is an essential framework for modern SOC and threat hunting operations.

