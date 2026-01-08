\# AWS S3 Basics



\## Overview



Amazon Simple Storage Service (S3) is a cloud storage service provided by AWS for storing and retrieving data.



S3 is commonly used for:

\- backups

\- static website hosting

\- cloud storage

\- log storage

\- data archival



S3 is highly scalable and widely used in modern cloud environments.



\---



\## S3 Buckets



Data in S3 is stored inside containers called buckets.



Each bucket:

\- has a globally unique name

\- exists within a specific AWS region

\- can contain multiple objects



\---



\## S3 Objects



Objects are files stored inside buckets.



Each object consists of:

\- data

\- metadata

\- unique key name



Examples:

\- images

\- documents

\- backups

\- logs



\---



\## Bucket Permissions



S3 bucket permissions determine who can access stored data.



Access can be:

\- private

\- public

\- restricted through IAM policies



\---



\## Public vs Private Buckets



\### Public Buckets



Accessible from the internet.



Used for:

\- public website content

\- downloadable resources



Risks:

\- accidental data exposure

\- unauthorized access



\---



\### Private Buckets



Accessible only to authorized users or services.



Recommended for:

\- sensitive data

\- internal backups

\- application storage



\---



\## IAM and S3 Security



IAM policies control access to:

\- buckets

\- objects

\- storage actions



Example permissions:

\- s3:GetObject

\- s3:PutObject

\- s3:DeleteObject



\---



\## S3 Versioning



Versioning stores multiple versions of objects.



Benefits:

\- accidental deletion recovery

\- rollback capabilities

\- ransomware protection



\---



\## S3 Encryption



S3 supports encryption:

\- at rest

\- in transit



Encryption methods:

\- SSE-S3

\- SSE-KMS

\- client-side encryption



\---



\## S3 Storage Classes



AWS offers different storage classes for cost optimization.



Examples:

\- Standard

\- Intelligent-Tiering

\- Glacier

\- Glacier Deep Archive



\---



\## Logging and Monitoring



S3 activity can be monitored using:

\- CloudTrail

\- S3 access logs

\- CloudWatch



Monitoring helps detect:

\- unauthorized access

\- suspicious downloads

\- bucket changes



\---



\## Common Security Risks



Examples:

\- publicly exposed buckets

\- weak IAM permissions

\- unencrypted sensitive data

\- exposed backups



Many cloud data breaches involve S3 misconfigurations.



\---



\## Security Best Practices



Recommended practices:

\- block public access

\- enable encryption

\- use least privilege IAM policies

\- enable logging

\- monitor bucket activity



\---



\## S3 in Cybersecurity



Security teams commonly use S3 for:

\- log storage

\- backup retention

\- forensic evidence storage

\- malware sample storage



\---



\## Conclusion



Amazon S3 is a powerful and scalable cloud storage service. Proper access control, encryption, and monitoring are essential for protecting data stored in S3 environments.

