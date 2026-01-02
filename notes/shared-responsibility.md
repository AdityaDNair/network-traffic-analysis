\# AWS Shared Responsibility Model



\## Overview



The AWS Shared Responsibility Model defines the security responsibilities shared between Amazon Web Services (AWS) and the customer.



AWS manages the security \*\*of\*\* the cloud, while customers are responsible for security \*\*in\*\* the cloud.



Understanding this model is important for cloud security, compliance, and risk management.



\---



\## Security of the Cloud



AWS is responsible for protecting the infrastructure that runs AWS services.



This includes:

\- physical data centers

\- networking infrastructure

\- hardware

\- virtualization layer

\- managed service infrastructure



AWS handles:

\- hardware maintenance

\- physical security

\- infrastructure patching

\- availability of cloud services



\---



\## Security in the Cloud



Customers are responsible for securing their own workloads and configurations.



This includes:

\- IAM permissions

\- operating systems

\- applications

\- data encryption

\- firewall configurations

\- security groups



Customers must properly configure their cloud resources to prevent security risks.



\---



\## Example Responsibilities



| AWS Responsibilities | Customer Responsibilities |

|---|---|

| Physical servers | User access management |

| Networking infrastructure | Application security |

| Storage hardware | Data encryption |

| Managed service availability | Operating system updates |

| Hypervisor security | Security group configuration |



\---



\## Responsibility Differences by Service Type



Responsibilities vary depending on the cloud service model.



\---



\## Infrastructure as a Service (IaaS)



Example:

\- Amazon EC2



Customer responsibilities:

\- OS patching

\- application security

\- firewall rules

\- account permissions



AWS responsibilities:

\- hardware

\- networking

\- virtualization



\---



\## Platform as a Service (PaaS)



Example:

\- AWS Elastic Beanstalk



AWS manages more infrastructure components while customers focus mainly on applications and data.



\---



\## Software as a Service (SaaS)



Example:

\- Gmail

\- Microsoft 365



The provider handles most infrastructure and platform security.



Customers mainly manage:

\- user accounts

\- access permissions

\- data usage



\---



\## Importance of IAM



Identity and Access Management (IAM) is a major customer responsibility.



Organizations should:

\- implement least privilege

\- use MFA

\- avoid root account usage

\- regularly audit permissions



\---



\## Logging and Monitoring



Customers should enable:

\- CloudTrail

\- CloudWatch

\- GuardDuty



to improve visibility and detect suspicious activity.



\---



\## Common Customer Misconfigurations



Examples:

\- public S3 buckets

\- overly permissive IAM policies

\- exposed EC2 instances

\- disabled logging



Many cloud breaches occur because of customer-side misconfigurations.



\---



\## Importance in Cloud Security



Understanding the shared responsibility model helps organizations:

\- improve compliance

\- secure cloud environments

\- reduce attack surface

\- manage cloud risks effectively



\---



\## Conclusion



The AWS Shared Responsibility Model is a foundational cloud security concept. Both AWS and customers have security responsibilities, and understanding these responsibilities is critical for securing cloud environments properly.

