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

<img width="647" height="468" alt="ping-test" src="https://github.com/user-attachments/assets/65ce5888-4864-4b4f-8695-951af8ea5e6c" />

<img width="866" height="857" alt="vlan-config" src="https://github.com/user-attachments/assets/10de342a-d49e-4aea-8aa1-083f21d2f63a" />

<img width="1010" height="596" alt="topology" src="https://github.com/user-attachments/assets/39b5929c-8326-438e-b38a-e76019c0c6ed" />


##  Outcome

Successfully implemented VLAN segmentation and inter-VLAN communication in a simulated enterprise network.
