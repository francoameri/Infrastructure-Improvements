📊 Infrastructure Improvement Project
This project was based on a survey conducted in a local SMB where the infrastructure had multiple points of failure, no fault tolerance, and no high availability.

⚡ Objective: Reduce risks to a bare minimum and ensure continuity in a 24/7 service by implementing Fault Tolerance and High Availability devices.

💡 The idea was to start improving the infrastructure with a small budget. By using project management tools like Jira and deploying open-source solutions such as Proxmox, TrueNAS, OpenWRT, and others, the company could achieve a more robust and fault-tolerant infrastructure.

🔎 What will you see here?
- 🛡️ Fault Tolerance
- 🔄 High Availability
- 🌐 Mesh Topology
- 🧩 Network Architecture & Design
- 📅 Project Management
- 💰 Budget Management
- 📈 Scalability & Security Planning
- 🔧 Change Management

🏗️ First Scenario – Original Infrastructure


![Original Infrastructure](images/Original%20Infrastructure.png)


- ❌ 5 unnecessary ISPs (can be reduced to 3).
- ⚠️ Low fault tolerance: only 1 router/firewall between LAN/WAN and 1 core switch for the entire infrastructure.
- 🔄 Almost no redundancy, except in the database.

🚀 Proposed Scenario – New Deployment


![New Deployment](images/New%20Deployment.png)


- 🌐 Mesh topology in the backbone infrastructure.
- 🛡️ High Availability and Fault Tolerance with 2 routers/firewalls and 2 core switches.
- 💻 Proxmox Hypervisor to reduce unnecessary endpoints.
- 📡 WLC and 2 APs to optimize connectivity and eliminate redundant ISPs.

📚 Lessons Learned
- Redundancy is non‑negotiable: Even small infrastructures need multiple paths and devices to avoid single points of failure.
- Budget constraints drive creativity: Open‑source solutions like Proxmox, TrueNAS, and OpenWRT can deliver enterprise‑grade resilience without heavy licensing costs.
- Project management matters: Using tools like Jira ensured visibility, accountability, and structured rollout, reducing risks during migration.
- Network design impacts scalability: Moving to a mesh backbone and introducing HA routers/firewalls created a foundation for future growth.
- ISP rationalization improves stability: Reducing from five providers to three cut costs and simplified troubleshooting, while still maintaining redundancy.
- Virtualization consolidates resources: Proxmox reduced unnecessary endpoints, lowering hardware overhead and improving manageability.
- Change management is critical: Documenting each step and validating improvements minimized disruption and built confidence in the new setup.
- Security and availability go hand‑in‑hand: Fault tolerance and HA not only protect uptime but also strengthen the overall security posture by eliminating weak links.

