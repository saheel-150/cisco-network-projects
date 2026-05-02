# Project 2: OSPF Dynamic Routing Network

##  Objective

To design and implement a multi-router network using OSPF (Open Shortest Path First) for dynamic routing.

##  Concepts Used

* OSPF Routing Protocol
* Subnetting (/30 for point-to-point links)
* Multi-router topology
* ARP & connectivity troubleshooting

##  Topology

3 Routers connected linearly:
R0 — R1 — R2
Each router connected to a PC network.

##  IP Addressing

| Device | Interface | IP Address  |
| ------ | --------- | ----------- |
| R0     | G0/0      | 192.168.1.1 |
| R0     | G0/1      | 10.0.12.1   |
| R1     | G0/0      | 192.168.2.1 |
| R1     | G0/1      | 10.0.12.2   |
| R1     | G0/2      | 10.0.23.1   |
| R2     | G0/0      | 10.0.23.2   |
| R2     | G0/1      | 192.168.3.1 |

##  Routing Protocol

* OSPF Process ID: 1
* Area: 0

##  Verification

* OSPF neighbors reached FULL state
* Routes learned via OSPF (`show ip route`)
* Successful end-to-end ping (PC0 → PC2)

##  Troubleshooting Done

* Fixed ARP resolution issue
* Resolved one-way ping problem
* Corrected cable and interface mismatches

##  Outcome

Achieved full network connectivity using dynamic routing with OSPF.

---

 Built as part of Cisco Packet Tracer Lab Series

