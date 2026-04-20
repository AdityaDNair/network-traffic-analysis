\# Nmap Scanning Basics



\## Overview



Nmap (Network Mapper) is a powerful open-source tool used for:

\- network discovery

\- port scanning

\- service enumeration

\- vulnerability identification



Cybersecurity professionals use Nmap during:

\- penetration testing

\- vulnerability assessments

\- network analysis

\- security audits



\---



\## What is Port Scanning?



Port scanning identifies:

\- open ports

\- running services

\- accessible hosts



Attackers and defenders both use scanning to understand network exposure.



\---



\## Basic Nmap Scan



Example:



```bash

nmap 192.168.1.1

```



This scans common ports on the target host.



\---



\## Common Port States



\### Open



A service is actively accepting connections.



\---



\### Closed



The port is reachable but no service is listening.



\---



\### Filtered



Traffic is blocked by a firewall or filtering device.



\---



\## Service Version Detection



Nmap can identify running services and versions.



Example:



```bash

nmap -sV 192.168.1.1

```



Useful for:

\- identifying outdated services

\- vulnerability analysis



\---



\## Operating System Detection



Nmap can estimate operating systems using:



```bash

nmap -O 192.168.1.1

```



\---



\## Common Scan Types



\### TCP Connect Scan



Uses full TCP connections.



```bash

nmap -sT target

```



\---



\### SYN Scan



Stealthier half-open scan.



```bash

nmap -sS target

```



\---



\### UDP Scan



Scans UDP services.



```bash

nmap -sU target

```



\---



\## Common Ports



| Service | Port |

|---|---|

| HTTP | 80 |

| HTTPS | 443 |

| SSH | 22 |

| DNS | 53 |

| RDP | 3389 |



\---



\## Nmap Scripting Engine (NSE)



NSE allows advanced scanning and automation.



Examples:

\- vulnerability detection

\- service enumeration

\- brute force testing



\---



\## Example NSE Scan



```bash

nmap --script vuln target

```



\---



\## Firewall Evasion



Attackers may attempt:

\- stealth scans

\- fragmented packets

\- timing adjustments



to bypass detection.



\---



\## Security Risks of Open Ports



Exposed services may lead to:

\- unauthorized access

\- brute force attacks

\- vulnerability exploitation



\---



\## Nmap in SOC Operations



SOC analysts may investigate:

\- scanning activity

\- reconnaissance attempts

\- suspicious network probes



\---



\## Ethical Usage



Nmap should only be used:

\- on authorized systems

\- within lab environments

\- during approved security testing



Unauthorized scanning may violate policies or laws.



\---



\## Importance in Cybersecurity



Nmap is essential for:

\- network visibility

\- attack surface assessment

\- vulnerability discovery

\- penetration testing



\---



\## Conclusion



Nmap is one of the most important cybersecurity tools for network discovery and security assessment. Understanding Nmap scanning techniques helps security professionals identify and secure exposed services.

