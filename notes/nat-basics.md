NAT (Network Address Translation)

Date - 11th March, 2026

Objective - To understand how NAT allows multiple devices in a private network to access external networks using a single public IP address.

What is NAT?
- Network Address Translation is a technique used by routers to translate private IP addresses into a public IP address before sending traffic to the internet.
- It helps conserve IPv4 address space and improves network organization.

Why NAT is Needed
- IPv4 address space is limited
- Many devices need internet access
- NAT allows sharing of one public IP among multiple devices

Types of NAT
- Static NAT – One-to-one mapping between private and public IP
- Dynamic NAT – Uses a pool of public IP addresses
- PAT (Port Address Translation) – Multiple devices share one public IP using different ports

How NAT Works
1. Device sends a request from private IP
2. Router replaces private IP with public IP
3. Router keeps track of session using port numbers
4. Response is translated back to the original private IP

Security Relevance
- NAT hides internal IP addresses from external networks
- Helps reduce direct exposure of internal devices
- However, NAT is not a replacement for a firewall

Reflection
Understanding NAT is important for analyzing real network traffic and designing secure network infrastructures.
