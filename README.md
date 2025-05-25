#  🏫 Campus Network Project

This project demonstrates a full campus network design implemented in Cisco Packet Tracer, featuring multiple buildings, VLAN segmentation, routing protocols, DHCP, security, and essential network services.

---

##  🌍 Network Overview

### Faculties and Buildings

**1. Faculty of Engineering**  
Comprises several buildings:  
- SSP Building  
- Electrical Engineering Building  
- Administration Building  

Each building contains multiple floors and houses a total of 8 departments. Departments are segmented using VLANs, with each department assigned a unique IP subnet, for example:  
- 192.168.1.0/24  
- 192.168.2.0/24  
- 192.168.10.0/24  
- and others...

**2. Faculty of Health**  
Contains 2 departments:  
- Staff  
- Student Labs  

---

##  🛠️ Technologies and Features Implemented

- Cisco Packet Tracer for network simulation and visualization  
- VLAN creation and port assignment for departmental segmentation  
- Subnetting and IP addressing strategy tailored to each VLAN  
- Inter-VLAN routing using **Router-on-a-Stick (ROAS)** configuration  
- Router-based DHCP server for dynamic IP address allocation  
- RIPv2 dynamic routing protocol setup for internal routing between routers  
- Static routing configured for access to an external email server hosted in the cloud  
- Switch port security (Port Security) to restrict unauthorized access to the network  
- SSH configuration for secure remote management of network devices  
- Testing and verification of network connectivity across VLANs, departments, and campuses  

---

## 🛠️  Key Network Design Highlights

- **VLAN Segmentation:**  
  Each faculty, building, and department resides on a **separate VLAN and IP subnet**, providing logical separation, traffic management, and enhanced security.

- **Routing Protocols:**  
  - **RIPv2** is used for dynamic routing between internal routers across buildings and campuses.  
  - **Static routing** manages connectivity to the external email server hosted offsite (cloud).  

- **DHCP Server:**  
  Devices in Building A and other locations receive dynamic IP addresses via router-based DHCP servers, simplifying IP management.

- **Security Features:**  
  - Switch ports utilize **Port Security** to limit MAC addresses and prevent unauthorized device connections.  
  - **SSH** is enabled on routers and switches to secure remote access for administration.

- **Hierarchical Network Design:**  
  The network is structured with core, distribution, and access layers for scalability, performance, and simplified management.

- **Email Server:**  
  A functioning email server is included within the network, supporting communication needs.

---

## 📂  Project Files and Usage
campusNetwork/

┣ 📄 README.md ← Project documentation

┣ 📂 campusNetwork.pkt ← Cisco Packet Tracer network topology file


---

##  🚀 How to View and Explore

1. Open the `campusNetwork.pkt` file using **Cisco Packet Tracer** (version 8.x or higher recommended).  
2. Navigate through the topology to inspect:  
   - VLAN configurations and port assignments on switches  
   - Router configurations for DHCP, routing protocols, and interface setup  
   - Device IP addressing, routing tables, and connectivity  
3. Use simulation mode to send traffic across VLANs and campuses to test routing and DHCP assignments.  
4. Verify email server functionality and SSH access to network devices.  

---

##  📢  Notes

- The IP subnets and VLANs are designed to ensure proper isolation and efficient traffic flow between departments and faculties.  
- RIPv2 provides a simple and scalable routing solution for this campus network setup.  
- Security configurations such as Port Security and SSH help safeguard network access and management.  
- This project is intended as an educational reference for campus network design using Cisco Packet Tracer.
- shotout to gurutech for the project idea.  

---

Feel free to reach out for any questions or suggestions!
