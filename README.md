# University Campus Network Design 🌐

# 📌 Project Overview

This project presents the design and implementation of a university campus network using Cisco Packet Tracer.

The network connects four faculties and a Scientific Computation Center through a hierarchical network architecture. It includes VLAN segmentation, dynamic IP allocation using DHCP, and routing between networks using RIP.

---

# 🎯 Objective

- Design a scalable university campus network
- Connect multiple faculties and departments
- Implement VLANs for better organization and security
- Configure DHCP for automatic IP assignment
- Enable communication between networks using RIP routing
- Simulate and test the network using Cisco Packet Tracer

---

# 🏗️ Network Architecture

The network follows a hierarchical design consisting of:

Core Layer

- Central router connecting all faculties and the Scientific Computation Center

Distribution Layer

- Layer 3 switches used to manage routing and traffic between local networks

Access Layer

- Cisco 2960 switches connecting end-user devices inside labs and offices

---

# 🖧 Network Components

- 1 Central Router
- 4 Multilayer Switches
- Cisco 2960 Access Switches
- Servers
- 800 Client PCs
- Scientific Computation Center

---

#  VLAN Configuration

The network is segmented using VLANs to reduce broadcast traffic and improve security.

- VLAN 1 – Management
- VLAN 2 – Staff
- VLAN 3 – Students
- VLAN 4 – Guests
- VLAN 5 – Teaching Assistants

---

# 🌍 IP Addressing & DHCP

Dynamic IP addresses are assigned using DHCP.

Network ranges include:

- 192.168.1.0/24
- 192.168.2.0/24
- 192.168.3.0/24
- 192.168.4.0/24

DNS Server:

- 8.8.8.8

---

# 🔄 Routing

Routing Information Protocol (RIP) is used to enable communication between different networks and faculties.

This allows devices in separate VLANs and buildings to exchange data efficiently.

---

#  Simulation & Testing

The network was tested using Cisco Packet Tracer through:

- DHCP verification
- Ping connectivity tests
- Traceroute testing
- VLAN validation
- Routing verification

---

#  Key Features

- Hierarchical network design
- VLAN segmentation
- Dynamic IP allocation with DHCP
- RIP dynamic routing
- Scalable architecture
- Improved network organization and security

---

# 🧠 Key Learnings

- Designing large-scale network topologies
- VLAN configuration and management
- DHCP deployment
- Dynamic routing using RIP
- Layer 3 switching concepts
- Network troubleshooting and testing

---

# 🧰 Tools Used

- Cisco Packet Tracer
- Microsoft Word
- PowerPoint

---

# 📦 Project Files

- Network topology image
- Cisco Packet Tracer project file (.pkt)
- Project report (PDF)
- Final presentation (PDF)

---

⭐ Built as part of a Computer Networks academic project.
