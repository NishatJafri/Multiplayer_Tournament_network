# Multiplayer_Tournament_network
Multiplayer Tournament Network using VLAN and inter-VLAN routing. The network is segmented into multiple VLANs for teams, admin, server, and broadcast. It ensures secure, controlled communication with restricted inter-team access and efficient traffic management, simulated in Cisco Packet Tracer.

## Overview

This project demonstrates the design and implementation of a **Multiplayer Tournament Network** using VLAN (Virtual Local Area Network) and inter-VLAN routing. The network is structured to simulate a real-world tournament environment with controlled communication between different entities.

---

## Key Features

* VLAN-based network segmentation
* Inter-VLAN routing (Router-on-a-Stick)
* Controlled communication using access rules
* Reduced broadcast traffic
* Scalable and organized network design

---

## Network Structure

The network is divided into multiple VLANs:

* VLAN 10 → Team A
* VLAN 20 → Team B
* VLAN 30 → Team C
* VLAN 40 → Team D
* VLAN 50 → Team E
* VLAN 60 → Admin
* VLAN 70 → Server
* VLAN 80 → Broadcast

---

## IP Addressing

Each VLAN is assigned a separate subnet:

* 192.168.10.0/24 → Team A
* 192.168.20.0/24 → Team B
* 192.168.30.0/24 → Team C
* 192.168.40.0/24 → Team D
* 192.168.50.0/24 → Team E
* 192.168.60.0/24 → Admin
* 192.168.70.0/24 → Server
* 192.168.80.0/24 → Broadcast

---

## Access Control Rules

* Teams can communicate within their VLAN
* Teams can access the server
* Teams cannot access other teams
* Admin has access to all VLANs
* Broadcast can access teams and server but not admin

---

## Technologies Used

* Cisco Packet Tracer
* VLAN (802.1Q)
* Inter-VLAN Routing
* Networking Concepts (IP addressing, switching, routing)

---

## Testing & Verification

The network is tested using ping commands:

* ✅ Same VLAN communication (Successful)
* ✅ Team to Server communication (Successful)
* ❌ Team to Team communication (Blocked)
* ❌ Broadcast to Admin (Blocked)

---

## 📷 Screenshots

👉 Add your screenshots here:

* Network Topology
* VLAN Configuration (`show vlan brief`)
* Routing Verification (`show ip interface brief`)
* Ping Results

---

## Conclusion

This project successfully demonstrates VLAN segmentation, inter-VLAN routing, and access control in a multiplayer tournament environment. It ensures secure, efficient, and scalable network communication.

---

## Author

**Nishat**
MCA Student

