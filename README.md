# Enterprise Network Infrastructure Portfolio
### Strategy, Architecture, and Engineering Execution

## 📄 Overview
This repository hosts my comprehensive network engineering handbook detailing the end-to-end design, implementation, and hardening of enterprise network topologies on the Cisco platform. 

👉 **[Click here to view the full Network Infrastructure Handbook PDF](./Enterprise_Network_Infrastructure_Handbook.pdf)** (Contains full device scripts, topology maps, and verification outputs).

---

## 🛠️ Lab Directory & Core Competencies
Below is a summarized roadmap of the architectural solutions detailed within the handbook:

### 1. [Project 1: Foundation LAN Construction](./Enterprise_Network_Infrastructure_Handbook.pdf)
* **Scope:** Designed and configured a basic multi-switch LAN architecture supporting enterprise IT operations, end-user subnets, local file servers, and network printers using private IP blocks.

### 2. [Project 2: LAN Optimization, L2 Security & Remote Access](./Enterprise_Network_Infrastructure_Handbook.pdf)
* **Scope:** Implemented Link Aggregation (**LACP/PAgP EtherChannel**) to alleviate server bottlenecks, optimized traffic paths via **Rapid PVST+** root bridge tuning, and mitigated rogue access threats via **Port Security** (Sticky MAC constraints).

### 3. [Project 3 & 7: Enterprise & SOHO Wireless Deployment](./Enterprise_Network_Infrastructure_Handbook.pdf)
* **Scope:** Scaled corporate wireless environments by replacing standalone access points with lightweight APs managed via a centralized **Wireless LAN Controller (WLC)**. Secured networks utilizing **WPA2-Enterprise** and **RADIUS authentication**.

### 4. [Project 4: Enterprise NAT & Traffic Engineering](./Enterprise_Network_Infrastructure_Handbook.pdf)
* **Scope:** Designed and deployed Static and Dynamic Network Address Translation (NAT) maps to securely route internal network zones out to public cloud resources and web environments.

### 5. [Project 6: Network Resilience & Centralized Monitoring](./Enterprise_Network_Infrastructure_Handbook.pdf)
* **Scope:** Configured secure remote management interfaces via **SSH** and introduced automated enterprise telemetry using **Syslog** and Network Time Protocol (**NTP**) synchronization.

---

## 📊 Verification & Implementation Standards
Every lab contained in the handbook has been verified for structural integrity. The document includes:
* **Running Configuration Scripts:** Clean, production-ready Cisco IOS terminal scripts.
* **Topology Diagrams:** Detailed maps visualizing core, distribution, and access layers.
* **Verification Proofs:** Captured terminal command outputs (`show ip interface brief`, `show etherchannel summary`, `show port-security`) and verified `ping`/`traceroute` logs proving 100% network connectivity.
