# Enterprise Network Security Lab

## Overview
This project documents an enterprise-style network and cybersecurity lab I designed earlier in my academic journey to understand how real-world organizations structure, secure, and segment their networks.

The goal of the lab was to model a realistic corporate environment, focusing on:
- Network segmentation
- Firewall placement
- Secure access controls
- Server role separation
- Offensive and defensive security testing

While originally created several years ago, the architecture reflects core security principles that are still widely used in modern enterprise environments.

---

## Network Topology
![Enterprise Network Diagram](diagram/network_topology.png)


---

## Architecture Summary

### Network Zones
- **Internet / Edge**
  - External network access routed through an edge router

- **DMZ (Demilitarized Zone)**
  - Public-facing services such as web and email servers
  - Isolated from the internal network via firewall rules

- **Internal LAN (10.10.10.0/24)**
  - Domain Controller (Active Directory)
  - Application and internal service servers
  - User workstations and internal systems

---

### Security Controls
- Firewalls enforcing strict segmentation between Internet, DMZ, and internal LAN
- Limited inbound access to internal resources
- Controlled RDP access
- Site-to-site VPN for secure inter-network communication

---

### Systems & Platforms
- Windows Server (Domain Controller, internal services)
- Windows Server 2022
- Windows 10 Pro workstations
- Ubuntu Linux systems

---

### Security Tooling
- **Kali Linux** for penetration testing and attack simulation
- **Greenbone / OpenVAS** for vulnerability scanning and assessment

---

## Skills Demonstrated
- Enterprise network segmentation and DMZ design
- Firewall placement and access control concepts
- Windows Active Directory environments
- Linux and Windows system administration
- Vulnerability scanning and penetration testing fundamentals
- VPN and secure remote connectivity

---

## Context
This lab represents foundational work in my cybersecurity learning path. It is included here to demonstrate early understanding of enterprise security architecture and to complement more recent hands-on security projects.

---

## Author
Bryant Aguirre  
Computer Science & Cybersecurity  
University at Buffalo
