🎓 Chandigarh University Campus Network

A Cisco Packet Tracer-based campus network simulation project that demonstrates secure and efficient communication between multiple university departments using VLANs, routing, and server configuration.

📌 Project Overview

This project simulates a real-world campus network where different departments (Admin, Faculty, Students, Server Room) are connected using VLAN segmentation and routing techniques.

The main goal is to:

Improve network security 🔐
Reduce broadcast traffic 📉
Enable controlled inter-department communication 🔄
🧠 Key Concepts Used
VLAN (Virtual LAN)
Inter-VLAN Routing (Router-on-Stick)
DHCP (Dynamic IP Assignment)
DNS (Domain Name Resolution)
Email Server
Web Server
ACL (Access Control List Security)
🏗️ Network Design
🔹 VLAN Structure
VLAN ID	Department	Network Address
10	Admin	192.168.10.0/24
20	Faculty	192.168.20.0/24
30	Student	192.168.30.0/24
40	Server	192.168.40.0/24
🔹 Devices Used
1 Router
5 Switches
DNS Server
Email Server
Web Server
Multiple PCs
⚙️ Features

✅ VLAN-based network segmentation
✅ Inter-VLAN communication using router
✅ Automatic IP assignment using DHCP
✅ DNS domain: cu.edu
✅ Internal Email system
✅ Web hosting (internal site)
✅ ACL security (Student → Admin blocked)

🔧 Implementation Details
🔹 VLAN Configuration
VLANs created for each department
Ports assigned accordingly
🔹 Routing
Router-on-stick configuration using subinterfaces
🔹 DHCP
Router assigns IP automatically to all devices
🔹 DNS
Domain: cu.edu
Records:
cu.edu
mail.cu.edu
🔹 Email Server

Accounts created:

admin@cu.edu
faculty@cu.edu
student@cu.edu
🔹 ACL Security
access-list 100 deny ip 192.168.30.0 0.0.0.255 192.168.10.0 0.0.0.255
access-list 100 permit ip any any
🧪 Testing & Results

✔️ Successful communication:

Admin ↔ Faculty
Faculty ↔ Student

✔️ DHCP:

All PCs received automatic IP

✔️ DNS:

cu.edu resolved successfully

✔️ Email:

Messages sent between departments

✔️ ACL:

Student → Admin access blocked ✅
🎯 Conclusion

This project successfully demonstrates:

Real-world enterprise network design
Secure communication using ACL
Efficient management using VLAN & DHCP

It provides hands-on understanding of network administration concepts.

🚀 Future Enhancements
Wireless Network Integration 📶
Firewall Implementation 🔥
Dedicated DHCP Server
Network Monitoring System 📊
📁 Tools Used
Cisco Packet Tracer
Networking Concepts (CCNA Level)
👨‍💻 Author

Gaurav Raj
MCA - Chandigarh University

⭐ GitHub Tips
Add screenshots of your topology (very important 🔥)
Upload .pkt file in repo
Add demo video (optional but powerful)
