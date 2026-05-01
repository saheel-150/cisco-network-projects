# Multi-VLAN Network with Inter-VLAN Routing

##  Project Overview

This project demonstrates a multi-VLAN enterprise network using Cisco Packet Tracer. The network is segmented into different departments and enables communication using Router-on-a-Stick.

##  Concepts Used

* VLAN (Virtual LAN)
* Trunking (802.1Q)
* Inter-VLAN Routing
* Router-on-a-Stick

##  Network Design

* VLAN 10 → HR → 192.168.10.0/24
* VLAN 20 → Sales → 192.168.20.0/24
* VLAN 30 → IT → 192.168.30.0/24

##  Configuration Highlights

* Switch configured with VLANs and access ports
* Trunk port between switch and router
* Router configured with subinterfaces for each VLAN

##  Testing

* Verified connectivity using ping between VLANs
* First packet loss observed due to ARP (expected behavior)

##  Screenshots

<img width="1010" height="596" alt="topology" src="https://github.com/user-attachments/assets/7d14adf7-041c-46cb-abc4-d2986bb0b18d" />

<img width="866" height="857" alt="vlan-config" src="https://github.com/user-attachments/assets/5ef0131d-eaa1-43da-95a6-fa6ff3334099" />

<img width="647" height="468" alt="ping-test" src="https://github.com/user-attachments/assets/4a0e9b24-8788-429b-aafa-6dd7a09c613d" />



##  Outcome

Successfully implemented VLAN segmentation and inter-VLAN communication in a simulated enterprise network.
