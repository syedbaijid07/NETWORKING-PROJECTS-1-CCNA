# NETWORKING-PROJECTS-1-CCNA
Enterprise network design for 'OUR BANK LTD' using Cisco Packet Tracer. It features a secure Head Office connected to 3 branches. Key implementations: HSRP for 100% uptime, OSPF for dynamic routing, VLAN  Port Security for data safety, and EtherChannel for redundancy. A scalable and robust solution for modern banking infrastructure.

# OUR BANK LTD - Enterprise Network Design & Implementation

This repository contains a comprehensive network architecture designed for **OUR BANK LTD**. The project focuses on creating a secure, scalable, and highly available infrastructure to connect a Head Office with three regional branches.

## Project Overview
The goal of this project is to simulate a real-world banking network environment using **Cisco Packet Tracer**. It ensures 100% uptime and robust security measures to protect sensitive financial data.

## Key Features
* **High Availability:** Implemented **HSRP (Hot Standby Router Protocol)** at the Head Office for automatic failover and redundancy.
* **Scalability:** Designed with future growth in mind, allowing easy addition of devices without disrupting the current network.
* **Redundancy:** Used **EtherChannel (LACP/PAgP)** to increase bandwidth and provide link redundancy between switches.
* **Security:** * **VLAN Segmentation** to isolate departments (Admin, HR, IT).
    * **Port Security** to prevent unauthorized device access at the access layer.
* **Routing:** Dynamic routing implemented using **OSPF** for efficient data flow between the Head Office and Branches.

## Network Topology Details

### Head Office (HO)
* **VLAN 10 (Admin):** 192.168.10.0/27
* **VLAN 20 (HR):** 192.168.10.32/27
* **VLAN 30 (IT):** 192.168.10.64/27
* **Core Devices:** Multi-layer switches and redundant routers.

### Branch Offices
* **Branch 1:** 192.168.20.0/28 (10 Users)
* **Branch 2:** 192.168.30.0/27 (15 Users)
* **Branch 3:** 192.168.40.0/27 (20 Users)

## Files in this Repository
* `project for cisco.pkt`: The original Cisco Packet Tracer simulation file.
* `Project Documentation.pdf`: Detailed technical documentation including IP planning and backup strategies.
* `Capture.PNG`: Network topology diagram screenshot.

## Technologies Used
* Cisco Packet Tracer
* OSPF (Open Shortest Path First)
* HSRP (Hot Standby Router Protocol)
* VLAN & Inter-VLAN Routing
* EtherChannel
* Port Security (Sticky MAC)
