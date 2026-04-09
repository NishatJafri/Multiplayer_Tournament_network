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

## Screenshots

<img width="940" height="329" alt="image" src="https://github.com/user-attachments/assets/b593ed0b-704c-444f-b517-d0a0bbdbe97b" />
* Network Topology

<img width="431" height="304" alt="image" src="https://github.com/user-attachments/assets/5fe09a9d-112c-415b-b334-b3a86b1fe451" />
<img width="499" height="301" alt="image" src="https://github.com/user-attachments/assets/c455ef7e-425c-45e8-bdf9-9c13a0c54fea" />
* VLAN Configuration (`show vlan brief`)

<img width="944" height="402" alt="image" src="https://github.com/user-attachments/assets/2e23eb9e-2259-4d42-8dce-f2368134abcd" />
* Routing Verification (`show ip interface brief`)

<img width="472" height="156" alt="image" src="https://github.com/user-attachments/assets/a5e3113c-e22b-4e83-9211-8fc8e9bfc991" />
<img width="464" height="156" alt="image" src="https://github.com/user-attachments/assets/b389081f-e3b9-4fd9-874f-3f3e833d74b2" />
<img width="460" height="136" alt="image" src="https://github.com/user-attachments/assets/d95fba7d-c716-4824-bc4b-2d342ffe8572" />
<img width="471" height="136" alt="image" src="https://github.com/user-attachments/assets/d9e0a3eb-870f-4dec-bf33-8835f0ad9ad5" />
* Ping Results

---
## Project File

Download the `.pkt` file and open it using Cisco Packet Tracer:

[Download Project File](./your-file-name.pkt)

---

## Conclusion

This project successfully demonstrates VLAN segmentation, inter-VLAN routing, and access control in a multiplayer tournament environment. It ensures secure, efficient, and scalable network communication.

---

## Author

**Nishat**
MCA Student

