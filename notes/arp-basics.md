ARP (Address Resolution Protocol)

Date - 8th March, 2026

Objective - To understand how ARP maps IP addresses to MAC addresses within a local network.

What is ARP?
ARP is used to resolve an IP address into a physical MAC address.  
Devices on a local network use ARP to identify the hardware address of another device.

How ARP Works
1. A device wants to communicate with another device using its IP address.
2. It sends an ARP Request broadcast to the network.
3. The device with the matching IP address responds with an ARP Reply containing its MAC address.
4. The sender stores this information in its ARP cache.

ARP Table - Devices maintain an ARP table that stores recently resolved IP-to-MAC mappings.

Security Relevance - ARP can be exploited through attacks such as ARP spoofing or ARP poisoning, where an attacker sends fake ARP messages to intercept network traffic.

Reflection - Understanding ARP is important for network troubleshooting and analyzing packet-level network behavior.
