# enterprise-network-pfsense

## Overview

This project consists of designing and implementing a secure enterprise network for TechCorp using pfSense in a virtualized environment with GNS3.
The goal is to build a segmented, secure, and scalable network infrastructure that reflects real-world enterprise requirements.

## Network Architecture

The network is structured around VLAN segmentation, with a centralized firewall managing all traffic.

## VLAN Configuration
VLAN	Department	Subnet
10	Development	192.168.10.0/24
20	Marketing	192.168.20.0/24
30	Support	192.168.30.0/24
40	HR	192.168.40.0/24
50	Guest	192.168.50.0/24
## Security Features
Inter-VLAN traffic control using firewall rules
Network segmentation for enhanced security
Guest network isolation with captive portal
NAT configuration for secure Internet access
## Implemented Services
DHCP server per VLAN,
NAT (Network Address Translation),
VPN (OpenVPN),
Captive portal (Guest WiFi),
QoS (traffic prioritization for voice/video).
## Configuration Screenshots
VLAN Configuration,
Firewall Rules,
DHCP Configuration,
Captive Portal.
## Challenges
Hardware resource limitations
Nested virtualization issues
Instability of the virtual environment
## Future Improvements
IDS/IPS integration (Snort)
SIEM implementation
Active Directory with Windows Server
Firewall redundancy (High Availability)
