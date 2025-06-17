🧪 Week 1 – Performance Assessment: Multiple Routers
This assessment demonstrates my ability to configure a small subnetted network using multiple routers and various network devices in Cisco Packet Tracer. It builds on the skills developed in the Guided Practices and applies them in a more independent, hands-on scenario.

✅ Task 1 – Add and Connect Three Routers
Use three Cisco 4331 routers (instead of 4321).
Add serial modules and connect them using serial cables.
Label each router with your student ID and device type.
Take a screenshot of the connected and labeled routers.
Deliverable:
📸 Screenshot of connected and labeled routers.

✅ Task 2 – Add Additional Devices
Add the following devices:
3 × 3560 switches
4 × PCs
1 × Server
1 × WRT300N wireless router
1 × Smartphone
Label each device using your student ID.
Connect all devices as shown in the Guided Practice.
Take a screenshot of the full network.
Deliverable:
📸 Screenshot of labeled and connected network.

✅ Task 3 – Configure the Network
Configure router interfaces with IP addresses and subnet masks.
Set clock rates on DCE ends of serial links.
Configure VLANs and trunks on S1 and S2 switches.
Leave S3 with default settings.
Configure DHCP pools on R1, R2, and R3.
Verify IP address assignment on PCs, server, and wireless router.
Deliverables:

📸 show ip interface brief on R1, R2, R3
📸 Clock rate configuration on each router
📸 show running-config on S1 and S2 (VLANs and trunks)
📸 DHCP IP address verification on all end devices
✅ Task 4 – Configure Static Routes and Test Connectivity
Connect R1 G0/0/0 to the CSU-DSU using a straight-through cable.
Configure static routes on R1, R2, and R3.
Configure a default route on R1 to the Internet (e.g., ip route 11.0.0.0 255.0.0.0 11.0.0.254).
Verify routing tables and test connectivity between devices.
Deliverables:

📸 R1 connected to CSU-DSU
📸 Ping from R1 to Internet server
📸 show ip route on R1, R2, R3
📸 Ping results:
PC1 → PC4
PC2 → Server
PC3 → Internet server
