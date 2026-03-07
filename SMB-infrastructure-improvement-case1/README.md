# 📊 Educational Case Study: SMB Infrastructure Resilience

> ⚠️ Note: This project is an **anonymized case study** modeled after a real SMB environment.  
> All sensitive data has been removed. It is published for **educational and portfolio purposes** to demonstrate architect‑level thinking and practical execution.

---

# 📊 Infrastructure Improvement Project
> This project was based on a survey conducted in a local SMB where the infrastructure had multiple points of failure, no fault tolerance, and no high availability.

⚡ Design a **cost‑conscious, fault‑tolerant, and highly available infrastructure** that ensures 24/7 continuity.  
This project demonstrates how open‑source solutions (Proxmox, TrueNAS, OpenWRT) and structured project management can deliver **enterprise‑grade resilience** on an SMB budget.

💡 The idea was to start improving the infrastructure with a small budget. By using project management tools like Jira and deploying open-source solutions such as Proxmox, TrueNAS, OpenWRT, and others, the company could achieve a more robust and fault-tolerant infrastructure.

---

## 🔎 What will you see here?
- 🛡️ Fault Tolerance
- 🔄 High Availability
- 🌐 Mesh Topology
- 🧩 Network Architecture & Design
- 📅 Project Management
- 💰 Budget Management
- 📈 Scalability & Security Planning
- 🔧 Change Management

---

## 🏗️ First Scenario – Original Infrastructure


![Original Infrastructure](images/Original%20Infrastructure.png)

> This baseline scenario highlights common SMB infrastructure pitfalls: single points of failure, redundant ISP contracts, and limited scalability.


- ❌ 5 unnecessary ISPs (can be reduced to 3).
- ⚠️ Low fault tolerance: only 1 router/firewall between LAN/WAN and 1 core switch for the entire infrastructure.
- 🔄 Almost no redundancy, except in the database.

## 🚀 Proposed Scenario – New Deployment


![New Deployment](images/New%20Deployment.png)


- 🌐 Mesh topology in the backbone infrastructure.
- 🛡️ High Availability and Fault Tolerance with 2 routers/firewalls and 2 core switches.
- 💻 Proxmox Hypervisor to reduce unnecessary endpoints.
- 📡 WLC and 2 APs to optimize connectivity and eliminate redundant ISPs.

### 📊 Outcomes
- ISP overhead reduced by ~40% while maintaining redundancy
- Downtime risk lowered from single point of failure to N+1 redundancy
- Hardware endpoints consolidated via virtualization
- Backbone prepared for future hybrid cloud or Kubernetes HA expansion


---

## 📚 Lessons Learned
- Redundancy is non‑negotiable: Even small infrastructures need multiple paths and devices to avoid single points of failure.
- Budget constraints drive creativity: Open‑source solutions like Proxmox, TrueNAS, and OpenWRT can deliver enterprise‑grade resilience without heavy licensing costs.
- Project management matters: Using tools like Jira ensured visibility, accountability, and structured rollout, reducing risks during migration.
- Network design impacts scalability: Moving to a mesh backbone and introducing HA routers/firewalls created a foundation for future growth.
- ISP rationalization improves stability: Reducing from five providers to three cut costs and simplified troubleshooting, while still maintaining redundancy.
- Virtualization consolidates resources: Proxmox reduced unnecessary endpoints, lowering hardware overhead and improving manageability.
- Change management is critical: Documenting each step and validating improvements minimized disruption and built confidence in the new setup.
- Security and availability go hand‑in‑hand: Fault tolerance and HA not only protect uptime but also strengthen the overall security posture by eliminating weak links.

> ✅ This case study demonstrates my ability to **analyze risks, design resilient architectures, and execute structured change management** — skills directly transferable to enterprise infrastructure roles.

---

## 📢 About This Case Study
This repository is part of my **Infrastructure Improvement Portfolio**, showcasing real-world scenarios and reproducible labs.  
It is intended for recruiters, peers, and IT professionals interested in **fault tolerance, high availability, and open-source infrastructure design**.

---

## 🔑 Keywords

> High Availability, Fault Tolerance, Mesh Topology, Proxmox Virtualization, TrueNAS Storage, OpenWRT Networking, Network Architecture & Design, Project Management (Jira), Cost-Conscious Infrastructure, Scalability & Security Planning, Change Management, SMB Infrastructure Case Study, Enterprise-Grade Resilience, Risk Analysis & Mitigation

