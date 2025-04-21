# 🔐 Enterprise Network Simulation for Banking & Insurance Firm (Cisco Packet Tracer)

This project showcases the design and implementation of an enterprise-grade network for **Radeon Company Ltd.**, a fictional US-based banking and insurance firm establishing its first African branch in **Nairobi, Kenya**. The network was developed and simulated using **Cisco Packet Tracer** following real-world enterprise networking principles.

---

## 🏢 Project Overview

Radeon Ltd. operates in a **four-story building**, each housing different departments. The company required a robust, secure, and scalable network capable of supporting both wired and wireless users in each department, centralized services, and secure remote access.

---

## 🧩 Project Goals

- Design a **hierarchical network topology** (Core, Distribution, Access)
- Implement **VLANs per department** to ensure segmentation and security
- Enable **dynamic routing** using OSPF between routers on each floor
- Centralize **DHCP, HTTP, and Email servers** in the server room
- Support **wireless and wired access** for ~60 users per department
- Secure all routers with **SSH access**
- Implement **port security** on all switches using sticky MAC and violation shutdown
- Perform comprehensive testing and verification

---

## 🏗️ Network Layout

### Building Structure

| Floor | Departments                          |
|-------|--------------------------------------|
| 1     | Management, Research, Human Resources |
| 2     | Marketing, Accounting, Finance        |
| 3     | Logistics & Store, Customer Care, Guest |
| 4     | ICT, Administration, Server Room      |

- Each department assigned a **unique VLAN**
- Centralized **DHCP server** provides IP addresses to all devices
- Network designed to support **200+ users**

---

## 🌐 Technologies & Protocols Used

- **Cisco Packet Tracer** (Simulation)
- **Hierarchical Topology Design** (Core, Distribution, Access)
- **VLANs** (Segmentation)
- **IPv4 Subnetting**
- **OSPF** (Dynamic Routing)
- **DHCP** (Centralized IP Management)
- **SSH** (Secure Remote Access)
- **Port Security** (Sticky MAC, Shutdown on Violation)
- **HTTP & Email Servers** (Service Hosting)
- **Wireless Access Points** (Per Department)
- **Device Hardening** (Banner, Passwords, Security)

---

## 🖥️ Key Configurations (Implemented)

- VLAN configuration for each department
- IP address subnetting using base: `192.168.10.0/24`
- OSPF routing between floor routers
- DHCP server with pools for all VLANs
- SSH on all routers for secure remote login
- Port security on access ports using sticky MAC
- HTTP and Email server configurations
- Wireless connectivity setup for all departments

---

## 🧪 Testing & Validation

All configurations were verified with real-time simulation tools and commands:

- ✅ `ipconfig` on end devices to verify DHCP assignment
- ✅ Ping tests within and between VLANs to validate communication
- ✅ `show ip route` to confirm OSPF propagation
- ✅ SSH access tested from client to routers
- ✅ Server access tested using web browser and email client
- ✅ Port security behavior confirmed by MAC address learning and violation triggering

---

## 📸 Screenshots to Include

For better visualization, it’s recommended to include these in your GitHub repo:

- Network topology view in Packet Tracer
- VLAN table and addressing plan
- DHCP configuration screenshot
- OSPF route table (`show ip route`)
- IP configuration on end devices (`ipconfig`)
- Ping test outputs
- Port security (`show port-security interface`)

---



