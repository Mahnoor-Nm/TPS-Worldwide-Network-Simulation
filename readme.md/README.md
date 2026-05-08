
# Design and Simulation of TPS Worldwide's Enterprise Network Infrastructure

## Project Overview
This project involves the design and simulation of a scalable, secure, and enterprise-grade network infrastructure for **TPS Worldwide**, a leading fintech company based in Karachi, Pakistan. The simulation is implemented using **Cisco Packet Tracer** and replicates a real-world corporate environment to facilitate seamless communication and robust service delivery across multiple departments.

## Key Features
- **Hierarchical Network Model**: Utilizes a two-tier topology consisting of a Layer 3 Core Switch and multiple Layer 2 Access Switches.
- **VLAN Segmentation**: Logical separation of departments to reduce broadcast traffic and enhance security.
- **Centralized Services**: Dedicated Server VLAN hosting essential services like DHCP, DNS, FTP, and Web servers.
- **Inter-VLAN Routing**: Configured via Switched Virtual Interfaces (SVIs) on the Core Switch.
- **Scalability**: Supports 180+ devices with the ability to add new departments easily.

## Network Architecture
The network is segmented into several VLANs to ensure organizational efficiency:
- **VLAN 10 (Development)**: Internal dev environment.
- **VLAN 30 (HR)**: Human Resources department.
- **VLAN 50 (Servers)**: Centralized infrastructure (DHCP, DNS, FTP, HTTP).
- **VLAN 70 (Guest)**: Isolated Wi-Fi network for visitors with simulated internet access.

## Technical Specifications & Configurations
- **Core Switch**: Layer 3 Switch handling inter-VLAN routing.
- **DHCP**: Automated IP allocation per VLAN.
- **DNS**: Internal domain name resolution (e.g., `ftp.tps.com`, `intranet.tps.com`).
- **FTP**: Secured file sharing across Development and QA departments.
- **Web Server**: Intranet access for internal company documentation.

## Testing & Validation
The following tests were successfully conducted to verify the network integrity:
1. **Intra-VLAN Communication**: Devices within the same department can communicate.
2. **Inter-VLAN Routing**: Controlled communication between different departments via the Core Switch.
3. **Service Accessibility**: Successful FTP login, DNS resolution, and Web browsing from client PCs.
4. **Internet Connectivity**: Verified internet access for the Guest VLAN through a simulated router.

## Project Contributors
- Syeda Maham Ikram
- Fizza Mubben
- Mahnoor Nadeem
- Rabbania Akhter

## Supervisor
Sir Fauzan Saeed

## Files in this Repository
- `TPS COMP NETWORK PROJECT.pkt`: The Cisco Packet Tracer simulation file.
- `Computer Network Project Report.docx`: Detailed documentation and configuration logs.
- `CN Project.pptx`: Presentation slides summarizing the project.
