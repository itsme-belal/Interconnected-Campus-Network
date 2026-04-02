# 🏫 Interconnected Campus Network

**Course:** Computer Network (CSE405) |
- **Student:** Belal Hossain
- **ID:** 2023-2-60-010
- **Institution:** East West University, Department of CSE
- **Semester:** Fall 2025
- **Instructor:** Md. Khalid Mahbub Khan

---

## 📌 Project Overview

This project demonstrates the design and simulation of an **Interconnected Multi-Building Campus Network** using **Cisco Packet Tracer**. The network connects five separate university facilities into a unified, scalable, and fully functional campus network following real-world networking standards.

### 🏢 Facilities Covered

| Facility | Network Address |
|---|---|
| Main Campus | 140.60.0.0 |
| Library Center | 150.70.0.0 |
| Computer Lab | 160.80.0.0 |
| Faculty Offices | 170.90.0.0 |
| Administration Block | 130.50.0.0 |

---

## ✨ Features

- 🔀 **Dynamic Routing with EIGRP** — Automatic route discovery across all 5 facilities using EIGRP (AS 100) in a hub-and-spoke topology centered at the Administration Block
- 🌐 **Distributed DHCP** — Each facility has its own DHCP server for automatic IP allocation, eliminating IP conflicts
- 🔍 **Centralized DNS Server** — Resolves `www.universitynetwork.com` to the web server IP (130.50.0.3), hosted in the Administration Block
- 🖥️ **Web Server** — A university webpage accessible from all facilities via both domain name and direct IP address
- 🔒 **Network Segmentation** — Each building operates as an independent LAN with its own router and switch, minimizing broadcast traffic
- 📡 **Inter-Facility Connectivity** — All 5 buildings can communicate seamlessly through point-to-point WAN serial links
- ✅ **Verified & Tested** — DHCP allocation, ping tests, EIGRP routing tables, DNS lookup, and web access all verified successfully

---

## 🛠️ Tools Used

- Cisco Packet Tracer
- EIGRP (Dynamic Routing Protocol)
- DHCP / DNS / HTTP Services

---

## 📁 Repository Contents
```
📦 interconnected-campus-network
 ┣ 📄 README.md
 ┣ 📄 Project_Report_CSE405.pdf
 ┗ 📄 Project_Report_CSE405.doc
 ┗ 📄 campus_network.pkt
```

---

> © 2025 | Belal Hossain | East West University | CSE Department
