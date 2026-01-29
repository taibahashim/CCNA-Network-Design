# Enterprise Network Project
A complete simulation of a headquarters and branch office network with VLANs, OSPF routing, port security, SSH access, DHCP, and DNS services.


## Table of Contents
- [Network Topology](#network-topology)
- [Key Features](#key-features)
- [Technologies Used](#technologies-used)
- [Configuration Highlights](#configuration-highlights)
- [Screenshots](#screenshots)
- [How to Use](#how-to-use)
- [Future Improvements](#future-improvements)
- [Contributing](#contributing)
- [License](#license)


⭐ Key Features

Multi-site enterprise network design (HQ & Branch)
Department-based VLAN segmentation
Inter-VLAN routing (Router-on-a-Stick)
Centralized DHCP and DNS services
Dynamic routing using OSPF
Secure remote management using SSH
Access control using ACLs
Switch port security implementation
End-to-end connectivity testing and verification

🛠️ Technologies Used

Cisco Packet Tracer
Cisco Routers and Switches
VLAN & Trunking (IEEE 802.1Q)
Inter-VLAN Routing
OSPF (Open Shortest Path First)
DHCP Server
DNS Server
Access Control Lists (ACL)
SSH (Secure Shell)
Switch Port Security

⚙️ Configuration Highlights

🔹VLAN Segmentation

VLANs are assigned per department to isolate broadcast domains
Separate VLANs are used for user traffic and server services

🔹Routing

OSPF is implemented to enable dynamic routing between HQ and Branch
Inter-VLAN routing is configured on the HQ router

🔹Network Services

DHCP and DNS services are centralized at the Headquarters
DHCP pools are created for each VLAN

🔹Security

VLAN isolation to limit unauthorized inter-department communication
Extended ACLs to control inter-VLAN traffic
SSH enabled on routers for secure remote access
ACL applied to VTY lines to restrict SSH access to the Admin workstation only
Port security enabled on access switch ports
