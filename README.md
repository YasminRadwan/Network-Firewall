# Firewall Configuration – Cisco Packet Tracer

## Overview
This project demonstrates the implementation of firewall policies on Cisco devices,
including both **router-based ACLs** and **Cisco ASA firewall**. The goal is to
secure network traffic, control access, and protect internal resources.

The lab covers traffic filtering, NAT, object groups (ASA), and verification of
network security, providing a real-world understanding of firewall deployment.

---

## Tools & Technologies
- Cisco Packet Tracer
- Cisco IOS (Router/Switch)
- Cisco ASA Firewall
- Access Control Lists (ACLs)
- NAT (Network Address Translation)
- Object Groups (ASA)
- TCP/IP

---

## Configuration Summary
The configuration includes:

### Router/Switch ACL Firewall:
- Defining standard and extended ACLs
- Applying ACLs on inbound or outbound interfaces
- Filtering traffic based on source/destination IP, protocol, and port
- Verifying allowed and denied traffic

### Cisco ASA Firewall:
- Defining security levels for interfaces (Inside, Outside, DMZ)
- Creating access rules using ACLs
- Configuring NAT for internal-to-external communication
- Using Object Groups for scalable policies
- Verifying traffic with packet-tracer simulation

---

## Key Concepts Covered
- Firewall fundamentals and security principles
- Standard vs Extended ACLs
- ASA security levels and interface roles
- Access rules and traffic control
- NAT configuration for secure Internet access
- Object groups for hosts, networks, and services
- Verification using CLI and simulation commands

---

## Verification
Use the following commands to verify configurations:

- `show running-config` – Review device configuration  
- `show access-lists` – Check applied ACLs and access rules  
- `show nat` – Verify ASA NAT configuration  
- `ping <destination_ip>` – Test allowed traffic  
- `packet-tracer input <interface> <protocol> <source> <destination> <port>` – ASA traffic simulation

---

## Files Included
- `Firewall_Lab.pkt` – Packet Tracer file  
- `config.txt` – Full configuration exported from devices  
- `README.md` – This documentation

---

## How to Use
1. Open the `.pkt` file in Cisco Packet Tracer  
2. Review router ACLs and ASA firewall configuration  
3. Verify NAT rules for internal network connectivity  
4. Check access rules, object groups, and interface security levels  
5. Test allowed and blocked traffic using ping or packet-tracer commands

---

## Author
**Yasmin Radwan**  
Networking & Security Trainee  
CCNA Certified
