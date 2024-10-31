# Project Overview
Budding a startup, requires assistance in setting up a scalable and efficient network infrastructure. This report outlines the creation of a simple network for three employees, ensuring they can communicate effectively and access the internet.

## Requirements

### Devices 

1 Switch (Cisco 2960 with Cisco IOS version 15.0(2) image lanbasek9 or similar)
3 PCs (Windows 10)
3 Ethernet cables

## Network Configuration

### IP Addressing Table
| Device/Interface | IP Address/Subnet Mask|
| ----------- | -----------                |
| PC1/ ETH | 192.168.1.10/25               | 
| PC2/ ETH | 192.168.1.11/25               |
| PC3/ ETH | 192.168.1.12/25               |
| Router/ FastE0/0| 192.168.1.1/25         |

~~Steps Taken .~ 

## Network Design:

Used Cisco Packet Tracer to design the network with a switch connecting three PCs.
IP Addressing:

Assigned static IP addresses to each PC and the router to ensure proper communication.
Configuration:

Configured the router interfaces and ensured the FastEthernet0/0 interface was active with the appropriate IP.
Testing Connectivity:

Utilized the ping command to verify that all devices could communicate with each other and access the internet.

### Challenges Faced
Initial Configuration Issues: Some interfaces were found to be administratively down. This required manual activation and proper IP assignment. NAT configuration was needed to allow PCs to access external networks.

Deliverables
Network Design File: The Cisco Packet Tracer file (.pka) is included in this repository.
README File: This file outlines the project, including setup instructions, IP addressing, and configurations made.
Future Improvements
Consider implementing VLANs for improved network segmentation.
Explore additional security measures such as firewalls and access control lists.

### Conclusion
This project successfully demonstrates the creation and configuration of a simple network, meeting the requirements set forth by Hackers Poulette. The network is scalable, allowing for future growth as the startup expands

## Network Setup File
The Packet Tracer file for this network setup is included in the repository as `A_simple_network.pkt`.

You can download and open it using Cisco Packet Tracer to view or modify the network configuration.
