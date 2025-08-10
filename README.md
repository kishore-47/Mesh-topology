#Mesh Topology – Cisco Packet Tracer
This project demonstrates the design and configuration of a Mesh Topology in Cisco Packet Tracer, ensuring high availability, fault tolerance, and redundant network paths.

📘 Project Overview
A Mesh Topology connects every switch to all other switches, providing multiple data paths for network reliability. Even if one link fails, communication can continue through alternative routes.

Key Advantages:

High fault tolerance

Multiple redundant paths

Reliable and continuous connectivity

🖥️ Network Topology
Components Used:

Switches: 4 × Cisco 2960-24TT

PCs: 4 × End devices with static IP addresses

Cables: Copper straight-through for PC-Switch connections, Copper cross-over for Switch-to-Switch connections

IP Address Plan:

Device	IP Address	Connected To
PC0	192.168.10.1	Switch1
PC1	192.168.10.2	Switch3
PC2	192.168.10.3	Switch4
PC3	192.168.10.4	Switch2

(Add a screenshot of your topology here)

📂 Files
File	Description
mesh_topology.pkt	Cisco Packet Tracer project file
README.md	Project documentation
topology_screenshot.png	Network diagram image

⚙️ Configuration Steps
1️⃣ Connect Devices

Connect each PC to its respective switch.

Interconnect all switches in a full mesh pattern.

2️⃣ Assign IP Addresses

Configure each PC with its respective IP address and subnet mask (255.255.255.0).

3️⃣ Test Connectivity

Use the ping command between all PCs to verify full connectivity.

🎯 Learning Objectives
Understand the concept of Mesh Topology.

Learn to connect switches in a full mesh configuration.

Assign and manage IP addresses for end devices.

Test end-to-end connectivity in a redundant network design.

🧠 Key Notes
Full mesh topology offers the best fault tolerance but uses more cables and ports.

Works well in critical networks where downtime is unacceptable.

In large networks, a partial mesh can be used to reduce cost.

💡 Author
Kishore Anand M
🎓 B.Tech IT | 🧠 Pre-final Year
🔧 Aspiring Network Engineer | 💡 AI & No-Code Tools Explorer
🌐 LinkedIn: (Add your profile link)

🛡️ Mesh topology ensures that your network stays up and running even if multiple links fail, making it a robust choice for critical communication networks.
