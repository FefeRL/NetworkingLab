# Cisco Packet Tracer VLAN Lab

This is a simulated corporate network built in Cisco Packet Tracer, showcasing:

- VLAN segmentation (HR - VLAN 10, IT - VLAN 20)
- Trunking between switches
- Router-on-a-stick inter-VLAN routing
- Static IP configuration and subnetting
- Web server hosting and client access testing
- Physical rack simulation and logical design

## IP Addressing Scheme
| Device       | VLAN | IP Address     | Role     |
|--------------|------|----------------|----------|
| HR-PC1       | 10   | 192.168.10.2   | End user |
| IT-PC3       | 20   | 192.168.20.2   | End user |
| Web Server   | 20   | 192.168.20.10  | Host     |
| Router G0/0.10 | 10 | 192.168.10.1   | Gateway  |
| Router G0/1.20 | 20 | 192.168.20.1   | Gateway  |

## Skills Demonstrated
- VLAN configuration
- Cisco CLI basics
- Inter-VLAN routing (router-on-a-stick)
- Static IP planning and subnetting
- Troubleshooting using ping and command-line tools
- Physical topology design (rack layout)

## Usage
To open the project:
1. Open Cisco Packet Tracer
2. Load the `.pkt` file
3. Explore topology, run pings, inspect VLANs and trunk ports

## Author
Fernando Huizar Jr.
