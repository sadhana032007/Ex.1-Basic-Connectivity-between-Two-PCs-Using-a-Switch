## Ex. No 1. 	Basic Connectivity between Two PCs Using a Switch
# Date : 15/10/2026
# Name : Sadhana S

# Objective

          “To configure and test basic LAN connectivity between two PCs using a switch.”
________________________________________
# Apparatus/Tools Required
•	Cisco Packet Tracer Software
•	Devices: PCs, Switch, Router, Cables
•	Optional: Wireless Router, Server, Cloud
________________________________________
# Network Topology Diagram

<img width="640" height="396" alt="Screenshot 2026-10-15 173629" src="https://github.com/user-attachments/assets/8313b7ea-2742-41b2-ad10-285ed3a84953" />

________________________________________
# IP Addressing Table (if applicable)
Device Name	Interface	IP Address	Subnet Mask
PC0	NIC	192.168.1.2	255.255.255.0
PC1	NIC	192.168.1.3	255.255.255.0
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

<img width="640" height="396" alt="Screenshot 2026-10-15 173913" src="https://github.com/user-attachments/assets/ad37bba2-3619-4a9c-9a2b-b0a11123ef1e" />

<img width="640" height="396" alt="Screenshot 2026-10-15 174000" src="https://github.com/user-attachments/assets/435dd748-d8d8-4896-9645-06df8e6f5752" />

<img width="640" height="397" alt="Screenshot 2026-10-15 174331" src="https://github.com/user-attachments/assets/e4bd9d62-ed6d-4609-b23d-20957dbbf040" />


________________________________________
# Result
“Successfully configured and verified basic LAN communication between two PCs using a switch in Cisco Packet Tracer.”
	
