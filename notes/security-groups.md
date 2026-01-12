\# AWS Security Groups



\## Overview



AWS Security Groups act as virtual firewalls that control inbound and outbound traffic for AWS resources such as EC2 instances.



Security groups are a core part of AWS network security and help restrict unauthorized access to cloud resources.



\---



\## How Security Groups Work



Security groups evaluate traffic rules to determine whether network traffic should be allowed or denied.



They operate at the instance level and control:

\- inbound traffic

\- outbound traffic



\---



\## Stateful Firewall



Security groups are stateful.



This means:

\- if inbound traffic is allowed,

\- the response traffic is automatically allowed.



No separate outbound rule is required for response traffic.



\---



\## Inbound Rules



Inbound rules define what incoming traffic is permitted.



Example rules:

\- SSH (port 22)

\- HTTP (port 80)

\- HTTPS (port 443)



Example:



| Type | Port | Source |

|---|---|---|

| SSH | 22 | 192.168.1.10/32 |

| HTTP | 80 | 0.0.0.0/0 |



\---



\## Outbound Rules



Outbound rules define traffic leaving the resource.



Common outbound traffic:

\- internet access

\- software updates

\- API requests



\---



\## Common Protocols and Ports



| Service | Port |

|---|---|

| SSH | 22 |

| HTTP | 80 |

| HTTPS | 443 |

| RDP | 3389 |

| MySQL | 3306 |



\---



\## Security Group Best Practices



Recommended practices:

\- allow only necessary ports

\- restrict source IP ranges

\- avoid public SSH/RDP exposure

\- use least privilege access



\---



\## Restricting SSH Access



Instead of:



```text

0.0.0.0/0

```



Use:

\- corporate IP ranges

\- VPN networks

\- bastion hosts



to reduce attack exposure.



\---



\## Common Security Risks



Examples:

\- publicly exposed SSH ports

\- unrestricted RDP access

\- open database ports

\- overly permissive rules



Attackers commonly scan for exposed cloud services.



\---



\## Security Groups vs NACLs



| Security Groups | Network ACLs |

|---|---|

| Stateful | Stateless |

| Instance level | Subnet level |

| Allow rules only | Allow and deny rules |



\---



\## Monitoring and Logging



Security teams monitor:

\- unauthorized connection attempts

\- unusual traffic patterns

\- exposed services



Tools:

\- VPC Flow Logs

\- CloudTrail

\- GuardDuty



\---



\## Security Groups in SOC Operations



SOC analysts often investigate:

\- exposed cloud services

\- suspicious inbound traffic

\- brute force attempts

\- unauthorized access



\---



\## Importance in Cloud Security



Properly configured security groups help:

\- reduce attack surface

\- protect cloud workloads

\- prevent unauthorized access

\- improve cloud segmentation



\---



\## Conclusion



AWS Security Groups are an essential cloud security control used to restrict network access to AWS resources. Proper configuration and monitoring are critical for securing cloud environments.

