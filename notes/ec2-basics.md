\# AWS EC2 Basics



\## Overview



Amazon Elastic Compute Cloud (EC2) is a cloud computing service provided by AWS that allows users to launch and manage virtual machines in the cloud.



EC2 instances are widely used for:

\- web hosting

\- application servers

\- security labs

\- penetration testing environments

\- cloud infrastructure deployments



\---



\## What is an EC2 Instance?



An EC2 instance is a virtual server running inside AWS infrastructure.



Users can:

\- choose operating systems

\- configure storage

\- assign networking settings

\- manage security controls



\---



\## Common Operating Systems



EC2 supports:

\- Amazon Linux

\- Ubuntu

\- Windows Server

\- Kali Linux

\- Red Hat Enterprise Linux



\---



\## EC2 Instance Types



AWS provides different instance types optimized for different workloads.



Examples:

\- General purpose

\- Compute optimized

\- Memory optimized

\- Storage optimized



\---



\## Launching an EC2 Instance



Basic launch steps:

1\. Choose an AMI

2\. Select instance type

3\. Configure networking

4\. Attach storage

5\. Configure security groups

6\. Launch instance



\---



\## Amazon Machine Images (AMI)



AMIs are templates used to launch EC2 instances.



An AMI includes:

\- operating system

\- software packages

\- configurations



\---



\## Security Groups



Security groups act as virtual firewalls for EC2 instances.



They control:

\- inbound traffic

\- outbound traffic



Example rules:

\- allow SSH on port 22

\- allow HTTP on port 80



\---



\## Key Pairs



Key pairs are used for secure authentication to EC2 instances.



Linux instances commonly use:

\- SSH private keys



Windows instances use:

\- administrator passwords



\---



\## Elastic IP Addresses



Elastic IPs are static public IP addresses assigned to EC2 instances.



Benefits:

\- stable public access

\- easier DNS configuration



\---



\## EC2 Storage



EC2 commonly uses:

\- Elastic Block Store (EBS)

\- instance store volumes



EBS provides persistent storage.



\---



\## Monitoring EC2 Instances



AWS CloudWatch monitors:

\- CPU usage

\- network activity

\- disk usage

\- instance health



\---



\## EC2 Security Best Practices



Recommended practices:

\- enable least privilege IAM access

\- restrict security groups

\- disable unused ports

\- regularly patch systems

\- enable logging



\---



\## Common Security Risks



Examples:

\- publicly exposed SSH ports

\- weak security groups

\- exposed credentials

\- outdated operating systems



\---



\## EC2 in Cybersecurity



Security teams commonly use EC2 for:

\- SOC labs

\- cloud security testing

\- malware analysis environments

\- vulnerability assessment labs



\---



\## Conclusion



AWS EC2 provides scalable cloud computing infrastructure for modern applications and security environments. Proper configuration and security hardening are critical for protecting EC2 instances from attacks.

