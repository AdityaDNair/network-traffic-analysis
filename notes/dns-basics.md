DNS (Domain Name System) Basics

Date - 2nd March, 2026

Objective - To understand how DNS resolves domain names into IP addresses and how the resolution process works.

What is DNS?
- DNS translates human-readable domain names into IP addresses
- It follows a hierarchical and distributed architecture
- Essential for accessing websites and network services

DNS Resolution Process
1. User enters a domain name in the browser
2. Request is sent to a DNS resolver
3. Resolver queries:
   - Root DNS server
   - TLD DNS server
   - Authoritative DNS server
4. IP address is returned to the client

Common DNS Record Types
- A: Maps domain to IPv4 address
- AAAA: Maps domain to IPv6 address
- CNAME: Alias for another domain
- MX: Mail server records

Ports and Protocols
- Uses UDP port 53 for most queries
- Uses TCP port 53 for zone transfers and large responses

Security Relevance
- DNS can be targeted by attacks such as spoofing and cache poisoning
- DNS monitoring helps detect suspicious activity
- Secure DNS configurations are important for network security

Reflection - Understanding DNS resolution is critical for network troubleshooting and traffic analysis.
