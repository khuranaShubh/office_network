This project showcases a departmental network infrastructure simulated using Cisco Packet Tracer. It demonstrates the interconnectivity between various departments in an organization, segmented into VLANs/subnets, with appropriate routing and switching configurations.


📌 Project Overview
This network setup is designed to simulate real-world departmental communication and secure segmentation across different organizational units. The topology includes:

Four Departments:

Computer Department (192.168.3.0/24)

IT Department (192.168.2.0/24)

Chairman Department (192.168.1.0/24)

Server Room (1.0.0.0/24)

Routing:

Main Router connected to all subnet gateways

Static/Dynamic routing configured for inter-network communication

Switches & Hosts:

Each department has its own switch and multiple hosts

Each department has a printer and a manager PC

Chairman segment includes VC and Chairman PCs

Server Room includes a Server and Laptop

🧑‍💻 Devices Used
Routers: 2

Switches: 4

PCs: 9

Printers: 2

Server: 1

Laptop: 1

🧭 IP Addressing Scheme

Department	Subnet	Devices
Computer Dept.	192.168.3.0/24	3 PCs, 1 Printer, 1 Manager PC
IT Dept.	192.168.2.0/24	3 PCs, 1 Printer, 1 Manager PC
Chairman Office	192.168.1.0/24	Chairman PC, VC PC
Server Room	1.0.0.0/24	1 Server, 1 Laptop
🔧 Features
Inter-departmental communication

Centralized routing via a main router

Separate subnets for each department

Network segmentation for improved security

Realistic setup suitable for network learning and simulation

✅ Future Improvements
Implement VLANs for better Layer 2 segmentation

Add DHCP server for dynamic IP allocation

Integrate firewall or access control lists (ACLs) for security

Introduce backup connectivity with routing redundancy (e.g., OSPF)

🚀 How to Use
Open the project in Cisco Packet Tracer.

Verify connections and power on all devices.

Configure IPs and routing if not already configured.

Test connectivity using ping and tracert between PCs across departments.

Explore communication between client devices and the server.
