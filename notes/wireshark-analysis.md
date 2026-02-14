\# Wireshark Packet Analysis Basics



\## Overview



Wireshark is a network protocol analyzer used to capture and inspect network traffic in real time.



Cybersecurity professionals use Wireshark for:

\- packet analysis

\- troubleshooting

\- incident response

\- malware investigations

\- network monitoring



Wireshark is one of the most widely used tools in networking and cybersecurity.



\---



\## What is a Packet?



A packet is a small unit of data transmitted across a network.



Packets contain:

\- source IP address

\- destination IP address

\- protocol information

\- payload data



\---



\## Common Protocols in Wireshark



Examples:

\- TCP

\- UDP

\- HTTP

\- HTTPS

\- DNS

\- ICMP



\---



\## Capturing Traffic



Wireshark captures packets from network interfaces such as:

\- Ethernet

\- Wi-Fi

\- VPN adapters



Captured traffic is displayed in real time.



\---



\## Packet Structure



Wireshark displays packet information in multiple layers:

\- Frame Layer

\- Ethernet Layer

\- IP Layer

\- Transport Layer

\- Application Layer



\---



\## TCP Analysis



TCP is a connection-oriented protocol used for reliable communication.



Wireshark helps analyze:

\- TCP handshakes

\- retransmissions

\- resets

\- suspicious connections



\---



\## DNS Analysis



DNS traffic reveals:

\- domain lookups

\- suspicious domains

\- malware communication



Analysts often inspect DNS requests during investigations.



\---



\## HTTP Analysis



HTTP traffic may expose:

\- URLs

\- cookies

\- login requests

\- user-agent strings



Unencrypted HTTP traffic can reveal sensitive data.



\---



\## Packet Filters



Wireshark supports filters to simplify analysis.



Examples:



```text

tcp

```



```text

http

```



```text

ip.addr == 192.168.1.10

```



\---



\## Suspicious Traffic Indicators



Examples:

\- repeated failed connections

\- large outbound traffic

\- connections to malicious IPs

\- unusual DNS activity



\---



\## Following TCP Streams



Wireshark allows analysts to reconstruct communication sessions using:

\- Follow TCP Stream



Useful for:

\- analyzing conversations

\- inspecting payloads

\- investigating attacks



\---



\## Wireshark in Incident Response



Investigators use Wireshark to:

\- identify attacker communication

\- analyze malware traffic

\- investigate exfiltration attempts

\- reconstruct timelines



\---



\## Common Use Cases



Examples:

\- troubleshooting connectivity

\- detecting malware traffic

\- identifying port scans

\- analyzing suspicious packets



\---



\## Best Practices



Recommended practices:

\- capture traffic legally

\- filter unnecessary packets

\- secure packet captures

\- analyze traffic in isolated labs



\---



\## Importance in Cybersecurity



Wireshark is an essential tool for:

\- SOC analysts

\- network engineers

\- incident responders

\- malware analysts



\---



\## Conclusion



Wireshark provides deep visibility into network traffic and is an essential tool for cybersecurity investigations, packet analysis, and network troubleshooting.

