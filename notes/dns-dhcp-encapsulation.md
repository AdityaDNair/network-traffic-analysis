DNS, DHCP, and Encapsulation

Date - 21 february 2026

Objective - To understand how DNS and DHCP enable network communication and how encapsulation allows data to travel across network layers.

DNS (Domain Name System)
- Resolves human-readable domain names into IP addresses
- Uses a hierarchical, distributed system
- Common record types include A, AAAA, and CNAME
- Typically uses UDP on port 53

DHCP (Dynamic Host Configuration Protocol)
- Automatically assigns IP configuration to devices
- Operates using the DORA process:
  1. Discover
  2. Offer
  3. Request
  4. Acknowledge

Encapsulation
- Process of wrapping data with protocol information as it moves down network layers
- Each layer adds its own header (and sometimes trailer)
- Ensures correct delivery of data across networks

Key Observations
- DNS and DHCP are essential for network usability
- Encapsulation explains how data flows from the application to the physical layer
- Protocol headers help devices interpret received data

Security Relevance
- Understanding encapsulation helps in packet analysis and intrusion detection
- DNS attacks and rogue DHCP servers can disrupt networks

Reflection - Learning DNS, DHCP, and encapsulation together provides a complete view of how data is prepared, addressed, and delivered across networks.
