## Ex. No 1. 	Basic Connectivity between Two PCs Using a Switch
# Date : 	20.10.26	

# Objective

          “To configure and test basic LAN connectivity between two PCs using a switch.”
________________________________________
# Apparatus/Tools Required
•	Cisco Packet Tracer Software
•	Devices: PCs, Switch, Router, Cables
•	Optional: Wireless Router, Server, Cloud
________________________________________
# Network Topology Diagram

<img width="1918" height="1156" alt="image" src="https://github.com/user-attachments/assets/8e4516c1-0a53-490a-93a5-61ca973b6587" />

________________________________________
# IP Addressing Table (if applicable)
Device Name	Interface	IP Address	Subnet Mask
PC0	NIC	10.0.0.1	255.255.255.0
PC1	NIC	10.0.0.2 	255.255.255.0
Router0	Fa0/0	192.168.1.1	255.255.255.0
________________________________________
# Procedure
Step-by-step commands/configurations.
Example:
1.	Open Cisco Packet Tracer and add two PCs and one Switch.
2.	Connect the PCs to the switch using straight-through cables.
3.	Assign IP addresses to the PCs.
4.	Use the ping command to verify connectivity.
________________________________________
# Commands Used (if any)

For PC IP assignment:<br>
nginx<br>
CopyEdit<br>
Desktop > IP Configuration > Enter IP: 192.168.1.2 / Subnet: 255.255.255.0<br>
For Router Configuration (CLI):<br>

________________________________________
# Output (Screenshots / Ping Results)
<img width="1918" height="1158" alt="image" src="https://github.com/user-attachments/assets/85eb4e9d-f9e3-4237-9020-b2012e3ab176" />
<img width="1918" height="1198" alt="image" src="https://github.com/user-attachments/assets/b7daa9f2-e961-4400-a1c2-9a284c5cf524" />
<img width="1918" height="1198" alt="image" src="https://github.com/user-attachments/assets/260c9387-8511-459d-ab86-0dc00a6db1c1" />


________________________________________
# Result
“Successfully configured and verified basic LAN communication between two PCs using a switch in Cisco Packet Tracer.”
	
