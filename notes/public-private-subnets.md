\# Public and Private Subnets in AWS



\## Overview



Subnets are smaller network segments created within an AWS VPC. They help organize and isolate cloud resources based on networking and security requirements.



AWS commonly uses:

\- public subnets

\- private subnets



to separate internet-facing resources from internal systems.



\---



\## What is a Subnet?



A subnet is a portion of a VPC’s IP address range.



Each subnet exists within a specific Availability Zone and has:

\- its own route table

\- IP address range

\- network controls



\---



\## Public Subnets



A public subnet allows direct communication with the internet.



Resources in public subnets typically include:

\- web servers

\- load balancers

\- bastion hosts



\---



\## Internet Gateway Requirement



Public subnets require:

\- an Internet Gateway (IGW)

\- route table entries pointing to the IGW



Example route:



```text

0.0.0.0/0 → Internet Gateway

```



\---



\## Public IP Addresses



Instances inside public subnets often receive:

\- public IP addresses

\- Elastic IP addresses



These allow internet communication.



\---



\## Private Subnets



Private subnets do not allow direct inbound internet access.



Common resources:

\- databases

\- internal applications

\- backend services



\---



\## NAT Gateway Usage



Private subnets may use a NAT Gateway for outbound internet access.



This allows:

\- software updates

\- patch downloads

\- API communication



without exposing systems publicly.



\---



\## Security Benefits of Private Subnets



Private subnets improve security by:

\- reducing attack surface

\- isolating sensitive systems

\- restricting internet exposure



\---



\## Example Architecture



\### Public Subnet



Contains:

\- web servers

\- reverse proxies

\- load balancers



\### Private Subnet



Contains:

\- databases

\- internal APIs

\- application servers



\---



\## Route Tables



Route tables determine how traffic flows between:

\- subnets

\- the internet

\- VPNs

\- other VPCs



\---



\## Security Controls



Important controls include:

\- security groups

\- network ACLs

\- IAM permissions

\- VPC Flow Logs



\---



\## Monitoring and Logging



Security teams monitor:

\- subnet traffic

\- unauthorized access

\- exposed resources

\- suspicious outbound connections



Tools:

\- CloudTrail

\- VPC Flow Logs

\- GuardDuty



\---



\## Common Misconfigurations



Examples:

\- databases placed in public subnets

\- overly permissive routing

\- unrestricted inbound access



Such misconfigurations can lead to cloud security incidents.



\---



\## Best Practices



Recommended practices:

\- isolate sensitive systems

\- minimize public exposure

\- use least privilege networking

\- enable logging and monitoring



\---



\## Importance in Cloud Security



Subnet design is important for:

\- network segmentation

\- cloud security architecture

\- compliance

\- reducing attack surface



\---



\## Conclusion



Public and private subnets are essential components of AWS networking architecture. Proper subnet segmentation improves cloud security and helps protect critical resources from unauthorized access.

