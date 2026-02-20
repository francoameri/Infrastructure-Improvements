This project has been done by a survey conducted in a local SMB where the Infrastructure had a lot of points of failure, no fault tolerance nor High Availability.

This was a proposal for the company to reduce the risks to a bare minimum and - because it was a 24/7 service - any failure would have been covered by the implementation of Fault Tolerance and High Availability devices.

The idea behind this project was to start improving the whole Infrastructure with a small budget. Therefore, using project management tools like Jira and deploying the Infrastructure with Open-Source based tools like Proxmox, TrueNAS, OpenWRT and other tools,
we would have a more robust and fault-tolerant Infrastructure.

What will you see here?
-Fault Tolerance.
-High Availability.
-Mesh Topology.
-Network Architecture and design.
-Project Management.
-Budget Management.
-Planning for future Scalability and Security.

First Scenario - Original Infrastructure:

-5 unnecessary ISPs, can easily reduce it to just 3.
-Low fault tolerance: only 1 router/firewall between LAN/WAN, 1 core switch for the whole Infrastructure.
-Almost no redundancy, only on the Data Base.

Proposed Scenario - New deployment.

-Mesh topology in the Backbone Infrastructure.
-High Availability and Fault Tolerance with 2 Router/Firewalls and 2 Core Switches.
-Proxmox Hypervisor to reduce unnecessary Endpoints.
-WLC and 2 APs to reduce the 2 unnecessary ISPs.
