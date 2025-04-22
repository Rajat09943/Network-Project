# Network-Project

## 🖼️ Network Topology Preview

![Network Topology Diagram](./Screenshot%202025-04-21%20210436.png)

---







# 🏢 Small Office Network Topology

This project demonstrates a comprehensive network topology design for a **Small Office** environment. The topology showcases how multiple departments are interconnected through switches and routers, with both wired and wireless devices working seamlessly within a multi-subnet architecture.

---

## 📌 Project Overview

The goal of this simulation is to model a realistic small office network, ideal for training, educational labs, or initial planning for real-world implementation. Each department is assigned a subnet, featuring a combination of end-user devices, printers, and access points.

---

## 🖧 Network Architecture

### 🔹 Core Devices
- **2 × Routers (Cisco 2911)** – Interconnects departmental networks and manages routing.
- **2 × Switches (Cisco 2960)** – Acts as central hubs for wired device communication.

### 🔹 End Devices
- **PCs (PC-PT)**
- **Laptops (Laptop-PT)**
- **Smartphones (SMARTPHONE-PT)**
- **Tablet (Tablet-PT)**
- **Printers (Printer-PT)**
- **Wireless Access Points (AccessPoint-PT)**

---

## 🏢 Departmental Layout (Subnets)

Each colored block in the topology represents a distinct subnet/department:

| Color       | Department/Area      | Devices Included                                  |
|-------------|----------------------|----------------------------------------------------|
| 🟡 Yellow    | General Office 1     | PCs, Laptops, Smartphones, Printer, AP            |
| 🟩 Green     | Support Team         | PCs, Laptops, Smartphones, Printer, AP            |
| 🟣 Magenta   | Development Team     | PCs, Laptops, Tablets, Smartphones, Printer, AP   |
| 🟧 Orange    | Management            | PCs, Laptops, Smartphones, Printer, AP            |
| 🔴 Red       | Admin/Remote Office  | PC, Laptop, Printer, AP                           |
| 🟩 Green     | General Office 2     | PC, Laptop, Printer, AP                           |
| 💗 Pink      | Research/QA          | PC, Laptop, Printer, AP                           |

---

## 🔌 Connectivity Summary

- Wired connections (Ethernet) are used for PCs, printers, and laptops where needed.
- Wireless connectivity is provided through Access Points (APs) for mobile devices.
- All devices are routed through the central core switch, which is connected to the routers to manage cross-subnet communication.
- Proper VLANs and IP addressing schemes are assumed.

---

## 🧠 Use Cases

This network design is ideal for:
- 🧪 **Educational simulations (e.g., Cisco Packet Tracer)**
- 🏗️ **Pre-deployment network planning**
- 🧑‍🎓 **CCNA-level training and labs**
- 🧰 **Testing subnetting, DHCP, and routing protocols**

---



## 📁 File Structure


---

## 🚀 Get Started

To simulate this network:
1. Open the project in **Cisco Packet Tracer** or a similar tool.
2. Verify connections and device configurations.
3. Implement VLANs, DHCP, and Routing protocols (e.g., RIP, OSPF, or Static).
4. Test connectivity using the `ping` command or a web simulation.

---

## 📬 Feedback & Contributions

Feel free to fork this repository, suggest improvements, or use this topology as a base for more advanced networking labs.

> **Created by:** [RAJAT SAPEHIA]  
> **Project Type:** Academic / Simulation  
> **Tool Used:** Cisco Packet Tracer

---

