\# Threat Hunting Basics



\## Overview



Threat hunting is the proactive process of searching for hidden threats and suspicious activity within an organization’s environment before automated security tools generate alerts.



Unlike reactive monitoring, threat hunting actively looks for:

\- attacker behavior

\- indicators of compromise

\- stealthy malware

\- unauthorized access



Threat hunting is an advanced SOC and blue-team activity.



\---



\## Goals of Threat Hunting



Threat hunters aim to:

\- detect hidden threats

\- identify attacker persistence

\- reduce dwell time

\- improve detection capabilities



\---



\## Threat Hunting Process



Common steps:

1\. Develop a hypothesis

2\. Collect data

3\. Analyze activity

4\. Investigate anomalies

5\. Document findings



\---



\## Sources of Threat Hunting Data



Examples:

\- SIEM logs

\- endpoint logs

\- Windows Event Logs

\- DNS logs

\- network traffic

\- CloudTrail logs



\---



\## Indicators of Compromise (IOCs)



Threat hunters search for:

\- malicious IP addresses

\- suspicious domains

\- malware hashes

\- unusual processes



\---



\## Indicators of Attack (IOAs)



IOAs focus on attacker behavior rather than known signatures.



Examples:

\- privilege escalation

\- PowerShell abuse

\- lateral movement

\- suspicious account activity



\---



\## Common Threat Hunting Techniques



Examples:

\- log analysis

\- behavioral analysis

\- anomaly detection

\- MITRE ATT\&CK mapping



\---



\## MITRE ATT\&CK Framework



Threat hunters often use MITRE ATT\&CK to identify:

\- attacker tactics

\- techniques

\- procedures (TTPs)



Examples:

\- credential dumping

\- persistence mechanisms

\- command execution



\---



\## Suspicious Behaviors to Investigate



Examples:

\- unusual login times

\- abnormal PowerShell usage

\- suspicious outbound traffic

\- disabled security tools



\---



\## Threat Hunting Tools



Common tools:

\- Splunk

\- Microsoft Sentinel

\- Elastic SIEM

\- CrowdStrike

\- Wireshark



\---



\## Endpoint Threat Hunting



Threat hunters analyze:

\- process creation

\- registry changes

\- persistence mechanisms

\- EDR alerts



\---



\## Network Threat Hunting



Analysts monitor:

\- DNS anomalies

\- unusual connections

\- data exfiltration attempts

\- beaconing behavior



\---



\## Importance in SOC Operations



Threat hunting helps organizations:

\- identify advanced threats

\- improve visibility

\- strengthen detections

\- reduce attacker dwell time



\---



\## Challenges in Threat Hunting



Common challenges:

\- large data volumes

\- false positives

\- limited visibility

\- advanced attacker techniques



\---



\## Security Best Practices



Recommended practices:

\- centralize logs

\- enable detailed auditing

\- monitor endpoints continuously

\- map detections to MITRE ATT\&CK



\---



\## Conclusion



Threat hunting is a proactive cybersecurity activity focused on identifying hidden threats and attacker behavior. Effective threat hunting improves organizational security visibility and strengthens incident detection capabilities.

