<div align="center">

# 🌐 Cybersecurity Networking Roadmap

> [!NOTE]
> This roadmap represents my personal approach to learning networking for cybersecurity.
>
> The focus is on building a deep understanding of networking concepts that are most useful for ethical hacking, penetration testing, red teaming, blue teaming, SOC analysis, and malware analysis.
>
> Use it as a reference and customize it according to your own goals, interests, and experience level.
>
> As my knowledge grows, this roadmap will continue to evolve.
>
> 

### A Structured Networking Roadmap for Cybersecurity


![Status](https://img.shields.io/badge/Status-In%20Progress-blue)
![Focus](https://img.shields.io/badge/Focus-Cybersecurity-red)
![Roadmap](https://img.shields.io/badge/Roadmap-Networking-green)

</div>

---

# 📚 Table of Contents

* [Phase 1 — Networking Foundations](#phase-1--networking-foundations)
* [Phase 2 — Core Internet Protocols](#phase-2--core-internet-protocols)
* [Phase 3 — Web & Application Networking](#phase-3--web--application-networking)
* [Phase 4 — Packet Analysis & Traffic Inspection](#phase-4--packet-analysis--traffic-inspection)
* [Phase 5 — Hacker Networking](#phase-5--hacker-networking)
* [Phase 6 — Enterprise & Internal Network Security](#phase-6--enterprise--internal-network-security)
* [Phase 7 — Wireless Networking](#phase-7--wireless-networking)
* [Phase 8 — Cloud Networking](#phase-8--cloud-networking)
* [Phase 9 — Detection & Monitoring](#phase-9--detection--monitoring)
* [Phase 10 — Modern Networking Topics](#phase-10--modern-networking-topics)
* [Topics You Can Ignore Initially](#topics-you-can-ignore-initially)
* [Most Important Topics To Master Deeply](#most-important-topics-to-master-deeply)

---

# Phase 1 — Networking Foundations

<details>
<summary><b>Expand Phase 1</b></summary>

## 1. Network Basics

* [ ] What is a network
* [ ] LAN / WAN / Internet
* [ ] Client-server model
* [ ] Network devices overview

  * [ ] Router
  * [ ] Switch
  * [ ] Access Point
  * [ ] Firewall

---

## 2. OSI Model

* [ ] All 7 layers
* [ ] Purpose of each layer
* [ ] Protocols per layer
* [ ] Attacks per layer
* [ ] Encapsulation / decapsulation

---

## 3. TCP/IP Model

* [ ] TCP/IP layers
* [ ] Packet flow
* [ ] Communication process
* [ ] Connection lifecycle

---

## 4. IP Addressing

* [ ] IPv4
* [ ] Public vs Private IP
* [ ] CIDR notation
* [ ] Subnet basics
* [ ] Loopback
* [ ] NAT
* [ ] Reserved addresses

### Depth Needed

* Medium-High
* NOT CCNA-level subnetting mastery

---

## 5. Ports & Services

* [ ] Port numbers
* [ ] Well-known ports
* [ ] Common services

  * [ ] HTTP
  * [ ] HTTPS
  * [ ] SSH
  * [ ] FTP
  * [ ] DNS
  * [ ] SMB
* [ ] Open vs closed ports

---

## 6. TCP Deep Dive

* [ ] TCP handshake
* [ ] TCP flags
* [ ] Sequence numbers
* [ ] Acknowledgments
* [ ] Retransmissions
* [ ] Sessions
* [ ] Flow control
* [ ] Stateful communication

---

## 7. UDP Deep Dive

* [ ] Connectionless communication
* [ ] Speed vs reliability
* [ ] UDP-based services
* [ ] UDP attack surface

---

## 8. MAC Addresses & ARP

* [ ] MAC addresses
* [ ] ARP process
* [ ] ARP tables
* [ ] ARP spoofing
* [ ] MITM basics

</details>

---

# Phase 2 — Core Internet Protocols

<details>
<summary><b>Expand Phase 2</b></summary>

## 9. DNS

* [ ] DNS resolution
* [ ] Recursive queries
* [ ] Record types

  * [ ] A
  * [ ] AAAA
  * [ ] CNAME
  * [ ] MX
  * [ ] TXT
* [ ] DNS caching
* [ ] Subdomains

### Cybersecurity Side

* [ ] Enumeration
* [ ] DNS tunneling
* [ ] Recon

---

## 10. HTTP

* [ ] Requests
* [ ] Responses
* [ ] Headers
* [ ] Methods

  * [ ] GET
  * [ ] POST
  * [ ] PUT
  * [ ] DELETE
* [ ] Parameters
* [ ] Cookies
* [ ] Sessions
* [ ] Authentication
* [ ] Status codes

---

## 11. HTTPS / TLS

* [ ] TLS handshake
* [ ] Certificates
* [ ] Certificate Authorities
* [ ] Encryption basics
* [ ] Session keys
* [ ] SNI
* [ ] Cipher suites

---

## 12. ICMP

* [ ] Ping
* [ ] Echo request/reply
* [ ] Traceroute concepts
* [ ] ICMP-based recon

---

## 13. DHCP

* [ ] DHCP process
* [ ] IP assignment
* [ ] Lease mechanism
* [ ] Rogue DHCP concept

</details>

---

# Phase 3 — Web & Application Networking

<details>
<summary><b>Expand Phase 3</b></summary>

## 14. Authentication & Sessions

* [ ] Cookies
* [ ] Sessions
* [ ] Session IDs
* [ ] JWT
* [ ] OAuth basics
* [ ] Authorization flow

---

## 15. APIs

* [ ] REST APIs
* [ ] JSON
* [ ] API requests/responses
* [ ] API authentication
* [ ] API endpoints

---

## 16. WebSockets

* [ ] Persistent communication
* [ ] WebSocket requests
* [ ] Real-time communication

---

## 17. GraphQL Basics

* [ ] Queries
* [ ] Mutations
* [ ] API structure

---

## 18. Same-Origin Policy (SOP)

* [ ] Browser security model
* [ ] Cross-origin restrictions

---

## 19. CORS

* [ ] Cross-origin requests
* [ ] CORS headers
* [ ] Misconfigurations

---

## 20. Reverse Proxies & Load Balancers

* [ ] Reverse proxy
* [ ] Traffic forwarding
* [ ] CDN basics
* [ ] WAF basics

### Examples

* [ ] Nginx
* [ ] Cloudflare

---

## 21. Web Caching Basics

* [ ] Browser cache
* [ ] CDN caching
* [ ] Cache-Control headers
* [ ] Cache poisoning basics

</details>

---

# Phase 4 — Packet Analysis & Traffic Inspection

<details>
<summary><b>Expand Phase 4</b></summary>

## 22. Wireshark

* [ ] Packet capture
* [ ] Packet structure
* [ ] Display filters
* [ ] Following streams
* [ ] TCP analysis
* [ ] HTTP analysis
* [ ] DNS analysis
* [ ] TLS inspection basics

---

## 23. tcpdump

* [ ] Packet capture in Linux
* [ ] Capture filters
* [ ] Traffic analysis

---

## 24. Network Troubleshooting Tools

* [ ] ping
* [ ] traceroute
* [ ] netstat
* [ ] ss
* [ ] nslookup
* [ ] dig
* [ ] curl
* [ ] wget

</details>

---

# Phase 5 — Hacker Networking

<details>
<summary><b>Expand Phase 5</b></summary>

## 25. Port Scanning

* [ ] Open ports
* [ ] Service detection
* [ ] Banner grabbing
* [ ] Enumeration concepts

---

## 26. Nmap

* [ ] TCP scans
* [ ] SYN scan
* [ ] UDP scan
* [ ] Version detection
* [ ] NSE scripts

---

## 27. Firewalls

* [ ] Packet filtering
* [ ] Stateful firewalls
* [ ] Inbound/outbound filtering
* [ ] Firewall evasion basics

---

## 28. VPNs & Proxies

* [ ] VPN basics
* [ ] SOCKS proxies
* [ ] HTTP proxies
* [ ] Traffic routing

---

## 29. Reverse Shells & Bind Shells

* [ ] Listener concepts
* [ ] Reverse connections
* [ ] Shell communication

---

## 30. Tunneling & Port Forwarding

* [ ] SSH tunneling
* [ ] Port forwarding
* [ ] SOCKS tunneling

---

## 31. Pivoting

* [ ] Internal movement
* [ ] Multi-network access
* [ ] Lateral traversal concepts

</details>

---

# Phase 6 — Enterprise & Internal Network Security

<details>
<summary><b>Expand Phase 6</b></summary>

## 32. SMB

* [ ] SMB communication
* [ ] File sharing
* [ ] SMB enumeration

---

## 33. NetBIOS

* [ ] Name resolution
* [ ] Windows networking basics

---

## 34. LDAP

* [ ] Directory services
* [ ] Queries
* [ ] Enumeration basics

---

## 35. Kerberos

* [ ] Tickets
* [ ] TGT/TGS
* [ ] Authentication flow

---

## 36. NTLM

* [ ] Windows authentication
* [ ] Hash-based authentication

---

## 37. Active Directory Basics

* [ ] Domains
* [ ] Domain Controllers
* [ ] Users/groups
* [ ] Authentication flow
* [ ] Trust relationships

---

## 38. Network Segmentation

* [ ] VLAN concepts
* [ ] Trust boundaries
* [ ] Internal segmentation

</details>

---

# Phase 7 — Wireless Networking

<details>
<summary><b>Expand Phase 7</b></summary>

## 39. Wi-Fi Basics

* [ ] Wireless communication
* [ ] Access points
* [ ] Channels

---

## 40. Wireless Security

* [ ] WPA/WPA2/WPA3
* [ ] Handshakes
* [ ] Evil Twin concept

</details>

---

# Phase 8 — Cloud Networking

<details>
<summary><b>Expand Phase 8</b></summary>

## 41. Cloud Networking Basics

* [ ] Public vs private subnet
* [ ] Security groups
* [ ] Virtual networking
* [ ] Cloud firewalls

---

## 42. AWS Networking Basics

* [ ] VPC
* [ ] Route tables
* [ ] Internet gateways
* [ ] Security groups

</details>

---

# Phase 9 — Detection & Monitoring

<details>
<summary><b>Expand Phase 9</b></summary>

## 43. IDS/IPS

* [ ] Intrusion detection
* [ ] Signatures
* [ ] Traffic monitoring

### Examples

* [ ] Snort
* [ ] Suricata

---

## 44. Malware Traffic Analysis

* [ ] Beaconing
* [ ] C2 traffic
* [ ] Suspicious DNS
* [ ] Data exfiltration

</details>

---

# Phase 10 — Modern Networking Topics

<details>
<summary><b>Expand Phase 10</b></summary>

## 45. IPv6 Basics

* [ ] IPv6 addresses
* [ ] IPv6 communication
* [ ] Security implications

</details>

---

# Topics You Can Ignore Initially

> Not necessary for most cybersecurity beginners.

* MPLS
* Advanced BGP
* Advanced STP
* Enterprise QoS
* ISP architecture
* Telecom networking
* Fiber engineering
* SD-WAN
* Carrier-grade routing
* Advanced Cisco enterprise optimization

---

# Most Important Topics To Master Deeply

* [ ] TCP/IP
* [ ] HTTP/HTTPS
* [ ] DNS
* [ ] Wireshark
* [ ] TLS
* [ ] APIs
* [ ] Nmap
* [ ] Packet Analysis
* [ ] Linux networking tools
* [ ] SMB/Kerberos/Active Directory
* [ ] Reverse shells
* [ ] Firewalls
* [ ] Authentication & Sessions
* [ ] Cloud networking basics

---

