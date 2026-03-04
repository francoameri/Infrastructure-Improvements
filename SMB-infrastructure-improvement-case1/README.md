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
