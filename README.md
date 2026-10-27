Stadium Network Segmentation | VLAN Security Lab

Project Overview

Designed and configured a simulated stadium network using Cisco Packet Tracer to demonstrate VLAN segmentation, switch configuration, and network connectivity testing.

The network separates ticketing operations, security systems, and guest devices into different VLANs.

Network Architecture

* Switch: Cisco Catalyst 2960
* VLAN 10 — TICKETING: Ticketing-PC
* VLAN 20 — SECURITY: Security-PC
* VLAN 30 — GUEST: Guest-PC and Guest-PC2

IP Addressing

Device	VLAN	IP Address	Subnet Mask
Ticketing-PC	10	192.168.10.10	255.255.255.0
Security-PC	20	192.168.20.10	255.255.255.0
Guest-PC	30	192.168.30.10	255.255.255.0
Guest-PC2	30	192.168.30.11	255.255.255.0

Configuration and Verification

* Created VLANs 10, 20, and 30 using Cisco IOS commands.
* Assigned switch access ports to the appropriate VLANs.
* Configured static IPv4 addresses.
* Verified VLAN configuration using show vlan brief.
* Tested network connectivity using ping.
* Saved the switch configuration.

Connectivity Test Results

* Guest-PC → Ticketing-PC: 0/4 replies
* Guest-PC → Security-PC: 0/4 replies
* Guest-PC2 → Guest-PC: 4/4 replies

These results demonstrate communication within VLAN 30 and the absence of inter-VLAN connectivity in this Layer 2 topology.

Security Considerations

VLAN segmentation creates separate Layer 2 broadcast domains. If inter-VLAN routing is introduced, additional security controls such as access control lists (ACLs) would be required to enforce traffic restrictions.

Skills Demonstrated

* Network segmentation
* Cisco IOS CLI
* VLAN configuration
* Switch port configuration
* IPv4 addressing
* Network troubleshooting
* Connectivity verification
* Technical documentation

Tools Used

Cisco Packet Tracer

Project Files

* Stadium_Network_Segmentation.pkt — Packet Tracer simulation
* Video demonstration — to be linked after upload

Career Relevance

This project demonstrates foundational networking skills relevant to cybersecurity, network administration, and IT infrastructure supporting large venues and stadium operations.
