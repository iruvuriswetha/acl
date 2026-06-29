📌 Project Overview

This project demonstrates the implementation of **Extended Access Control Lists (ACLs)** in Cisco Packet Tracer to control access between different LANs and servers in an enterprise network.
The network consists of three routers connected through serial links, two LANs, and a server network. Extended ACLs are configured to allow specific clients to access only designated servers while blocking access to other servers.
🎯 Objectives
- Configure a multi-router network.
- Implement static routing between routers.
- Configure Extended ACLs.
- Restrict server access based on source network.
- Verify connectivity using ping and troubleshooting commands.
🛠️ Network Topology
 LAN 1
- Network: **192.168.1.0/24**
- Connected to Router 1
Server Network
- Network: **192.168.2.0/24**
- Server0: **192.168.2.1**
- Server1: **192.168.2.2**
- Server2: **192.168.2.3**
LAN 2
- Network: **192.168.3.0/24**
- Connected to Router 3
WAN Links
- Router1 ↔ Router2 : **10.0.0.0/30**
- Router2 ↔ Router3 : **20.0.0.0/30**
🔒 Security Requirements
LAN1

- Allow access only to **Server1 (192.168.2.2)**
- Deny access to Server0 and Server2
- LAN2

- Allow access only to **Server2 (192.168.2.3)**
- Deny access to Server0 and Server1

---

⚙️ Technologies Used

- Cisco Packet Tracer
- Cisco Routers (1841)
- Cisco Switches (2950)
- Extended ACL
- Static Routing
- IPv4 Addressing

---

📋 Verification

The following tests were performed:
From LAN1
- ✅ Ping Server1
- ❌ Ping Server0
- ❌ Ping Server2
 From LAN2
- ✅ Ping Server2
- ❌ Ping Server0
- ❌ Ping Server1
## 📚 Networking Concepts

- IPv4 Addressing
- Routing
- Static Routing
- Extended Access Control Lists (ACL)
- Router Configuration
- Network Security
- Packet Filtering
 




