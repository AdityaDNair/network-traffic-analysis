DHCP (Dynamic Host Configuration Protocol) Basics

Date - 4th March, 2026

Objective - To understand how DHCP assigns IP configuration automatically and how the DHCP process works.

What is DHCP?
- DHCP automatically assigns IP addresses to devices on a network.
- It reduces manual configuration.
- It helps manage IP address allocation efficiently.

DHCP Process (DORA)
1. Discover – Client broadcasts a request for an IP address.
2. Offer – DHCP server offers an available IP address.
3. Request – Client requests the offered IP.
4. Acknowledge – Server confirms and assigns the IP.

Information Provided by DHCP
- IP address
- Subnet mask
- Default gateway
- DNS server

Ports Used
- UDP port 67 (server)
- UDP port 68 (client)

Security Relevance
- Rogue DHCP servers can assign malicious configurations.
- DHCP starvation attacks can exhaust IP pools.
- Monitoring DHCP logs is important in network security.

Reflection - Understanding DHCP helps in troubleshooting connectivity issues and detecting network misconfigurations.
