\# Firewall Fundamentals



\## Overview



A firewall is a network security device or software that monitors and controls incoming and outgoing network traffic based on predefined security rules.



Firewalls are essential for:

\- network segmentation

\- access control

\- threat prevention

\- monitoring suspicious traffic



They are one of the most important components of cybersecurity infrastructure.



\---



\## How Firewalls Work



Firewalls inspect traffic and determine whether it should be:

\- allowed

\- blocked

\- logged



Filtering decisions are based on:

\- IP addresses

\- ports

\- protocols

\- applications



\---



\## Types of Firewalls



\### Packet Filtering Firewall



Filters traffic based on:

\- source IP

\- destination IP

\- port numbers



Basic but fast filtering method.



\---



\### Stateful Firewall



Tracks active network connections.



Benefits:

\- understands connection state

\- improves security

\- reduces unauthorized traffic



Most modern firewalls are stateful.



\---



\### Next-Generation Firewall (NGFW)



NGFWs provide advanced features such as:

\- deep packet inspection

\- intrusion prevention

\- application awareness

\- malware detection



\---



\## Common Firewall Rules



Examples:

\- allow HTTPS traffic on port 443

\- block Telnet traffic

\- restrict SSH access to trusted IPs



\---



\## Inbound vs Outbound Traffic



\### Inbound Traffic



Traffic entering the network.



Examples:

\- web traffic

\- remote access connections



\---



\### Outbound Traffic



Traffic leaving the network.



Examples:

\- internet browsing

\- cloud service communication



\---



\## Network Segmentation



Firewalls help isolate:

\- internal systems

\- servers

\- sensitive environments



Segmentation reduces attack spread during intrusions.



\---



\## Common Firewall Ports



| Service | Port |

|---|---|

| HTTP | 80 |

| HTTPS | 443 |

| SSH | 22 |

| RDP | 3389 |

| DNS | 53 |



\---



\## Firewall Logging



Firewalls generate logs for:

\- allowed connections

\- blocked traffic

\- suspicious activity

\- intrusion attempts



Logs are important for SOC monitoring and investigations.



\---



\## Common Firewall Attacks



Examples:

\- port scanning

\- firewall evasion

\- brute force attacks

\- DDoS attacks



Attackers often probe firewalls for exposed services.



\---



\## Importance in SOC Operations



SOC analysts monitor firewall logs to detect:

\- suspicious IP addresses

\- unusual traffic patterns

\- blocked attacks

\- unauthorized access attempts



\---



\## Firewall Best Practices



Recommended practices:

\- deny unnecessary traffic

\- restrict administrative access

\- monitor logs continuously

\- segment critical systems

\- update firewall firmware regularly



\---



\## Cloud Firewalls



Cloud environments use:

\- AWS Security Groups

\- Network ACLs

\- Azure NSGs



to enforce cloud network security.



\---



\## Importance in Cybersecurity



Firewalls are critical for:

\- perimeter defense

\- internal segmentation

\- threat detection

\- reducing attack surface



\---



\## Conclusion



Firewalls are fundamental security controls used to monitor and filter network traffic. Proper firewall configuration and monitoring are essential for protecting modern networks and cloud environments.

