# 🏫 Campus Network Design Project

This project showcases the design and implementation of a **full campus network** using Cisco Packet Tracer. The network simulates a real-life university campus environment with multiple branches, buildings, VLAN segmentation, and dynamic routing protocols.

---

## 🏢 Project Overview

The campus network is divided into **two branches** representing two faculties:

### 1. Faculty of Engineering
- Comprises several buildings:
  - SSP Building
  - Electrical Engineering Building
  - Administration Building
- Each building contains multiple floors and houses a total of **8 departments**.
- Departments are segmented using **VLANs**, each assigned its own IP subnet, for example:
  - 192.168.1.0/24
  - 192.168.2.0/24
  - 192.168.10.0/24
  - and others...

### 2. Faculty of Health
- Contains **2 departments**:
  - Staff
  - Student Labs

---

## 🌐 Network Features

- **VLAN Segmentation:** Each department is isolated with its own VLAN and subnet for better network management and security.
- **Routing:**
  - **RIPv2** protocol is used for dynamic routing between routers.
  - **Router-on-a-Stick (ROAS)** configuration enables **inter-VLAN routing** on Layer 3 devices.
- **DHCP Server:**
  - IP addresses are dynamically assigned to devices within VLANs using a router-based DHCP server.
- **Email Server:**
  - A fully functional email server is integrated within the network to simulate real communication services.

---

## 🖥️ How to View and Use This Project

- The project is built using **Cisco Packet Tracer**.
- To open and explore the network:
  1. Install **Cisco Packet Tracer** (version compatible with the `.pkt` file).
  2. Open the file `campusNetwork.pkt` using Cisco Packet Tracer.
  3. You can explore the network topology, inspect devices, VLAN configurations, routing tables, and simulate network traffic.
  4. Use the simulation mode to observe packet flow and routing behavior across VLANs and branches.

---

## 📂 Project Files
campus-network/
┣ 📄 README.md ← This documentation file

┣ 📂 campusNetwork.pkt ← Cisco Packet Tracer project file


---

## 🛠️ Technologies and Concepts Used

- Cisco Packet Tracer
- VLAN Segmentation & Trunking
- Router-on-a-Stick (ROAS) for Inter-VLAN Routing
- Dynamic Routing Protocol: RIPv2
- DHCP Server Configuration on Routers
- Email Server Integration in Campus Network

---

## 📝 Notes

- This network design provides a realistic simulation of a university campus with segmented departments and scalable routing.
- Useful for learning practical networking concepts and Cisco device configurations.
- The project demonstrates hands-on skills for network design, IP addressing, routing protocols, and service integration.

