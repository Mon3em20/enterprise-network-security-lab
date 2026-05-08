# Enterprise Network Security Lab

## Overview

This project documents the design, deployment, and hardening of a simulated enterprise network infrastructure using Cisco Packet Tracer.

The lab was built to demonstrate practical enterprise networking and infrastructure security concepts including secure routing, centralized authentication, monitoring, access control, and network hardening across a multi-router environment.

The deployment process was fully documented through a structured operational workflow covering:
- Enterprise network design
- OSPF routing configuration
- AAA authentication
- SYSLOG monitoring
- SSH hardening
- ACL enforcement
- IPS deployment
- DMZ segmentation
- Infrastructure verification

---

# Objectives

- Design a segmented enterprise network infrastructure
- Configure secure dynamic routing using OSPF
- Implement centralized AAA authentication
- Enable centralized SYSLOG monitoring
- Secure administrative access using SSH
- Apply ACL-based traffic filtering
- Deploy IPS security policies
- Simulate enterprise-grade infrastructure security practices

---

# Technologies & Concepts

## Routing & Infrastructure
- Cisco IOS
- OSPF Area 0
- WAN Connectivity
- Enterprise Subnetting
- DMZ Segmentation
- VLAN-Based Architecture

## Security Hardening
- AAA Authentication
- TACACS+
- SSH Version 2
- Device Hardening
- Login Protection Policies
- Secure Administrative Access

## Monitoring & Visibility
- SYSLOG Centralization
- Infrastructure Logging
- Event Monitoring
- Router Auditing

## Security Controls
- Extended ACL Policies
- Intrusion Prevention System (IPS)
- Access Restriction Rules
- Administrative Access Control

---

# Lab Architecture

The simulated infrastructure includes:

- Multiple Cisco 2911 routers
- Internal enterprise departments
- DMZ services
- AAA server
- SYSLOG monitoring server
- Administrative management systems
- ISP simulation connectivity
- Multi-subnet enterprise topology

---

# Key Implementations

## OSPF Dynamic Routing
Configured OSPF Area 0 between interconnected routers to enable dynamic route propagation and scalable enterprise routing.

## AAA Authentication
Implemented centralized TACACS+ authentication to secure administrative access and improve access control management.

## SYSLOG Monitoring
Configured centralized SYSLOG logging for infrastructure monitoring and event visibility.

## SSH Hardening
Secured router management access using:
- SSH version 2
- RSA key generation
- Secure VTY configuration
- Login protection mechanisms

## ACL Enforcement
Implemented extended ACL policies to restrict unauthorized traffic between network segments and sensitive services.

## IPS Deployment
Applied Cisco IOS IPS policies for traffic inspection and intrusion prevention simulation.

---

# Skills Demonstrated

- Enterprise Network Design
- Cisco IOS Administration
- OSPF Routing
- Infrastructure Hardening
- AAA/TACACS+ Configuration
- SYSLOG Monitoring
- ACL Policy Management
- IPS Deployment
- Network Segmentation
- Technical Documentation

---

# Repository Contents

- Full enterprise network security report
- Network topology design
- Security configuration workflow
- Routing and hardening documentation
- Infrastructure verification evidence
- Enterprise security implementation methodology

---

# Lessons Learned

- Enterprise infrastructure security requires layered defensive controls across routing, authentication, monitoring, and segmentation.
- Centralized authentication and logging significantly improve administrative security and operational visibility.
- Proper network segmentation and access control policies reduce enterprise attack surface exposure.
- Infrastructure hardening is critical for maintaining secure enterprise environments.

---

# Disclaimer

This project was developed in a simulated educational lab environment using Cisco Packet Tracer for authorized cybersecurity and network security learning purposes only.