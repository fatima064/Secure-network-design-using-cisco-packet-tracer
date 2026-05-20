# Secure-network-design-using-cisco-packet-tracer

## Introduction

In modern computer networks, security and proper network organization are very important. Organizations use network segmentation techniques to separate different groups of users and reduce unauthorized access between systems. This project demonstrates a basic secure network design using Cisco Packet Tracer.

The project focuses on implementing VLANs (Virtual Local Area Networks) to separate Admin and User groups, improving network management and basic security.

---

# Objective of the Project

The main objective of this project is to understand and implement basic networking and security concepts such as:

* VLAN configuration
* Network segmentation
* Router and switch configuration
* Inter-VLAN communication
* Trunk port configuration
* IP addressing
* Connectivity testing

This project also helps beginners understand how secure communication is managed inside a network environment.

---

# Why This Project is Useful

This project is useful because network segmentation is an important cybersecurity and networking concept used in real organizations.

Benefits of this project include:

* Improves network organization
* Reduces unnecessary communication between users
* Provides basic network security
* Helps in traffic management
* Minimizes broadcast traffic
* Introduces practical cybersecurity concepts

Using VLANs helps isolate departments and control communication more effectively.

---

# Technologies and Tools Used

* Cisco Packet Tracer
* VLAN Technology
* Router and Switch Configuration
* Basic Networking Concepts
* IP Addressing
* Command Line Interface (CLI)

---

# Network Components Used

The network consists of:

* 1 Router
* 1 Switch
* 4 PCs

---

# VLAN Structure

| VLAN    | Purpose          |
| ------- | ---------------- |
| VLAN 10 | Admin Department |
| VLAN 20 | User Department  |

---

# Working of the Project

The project works by dividing the network into separate VLANs. Devices inside the same VLAN can communicate directly, while communication between different VLANs is managed through router configuration.

The switch is configured to assign specific ports to VLAN 10 and VLAN 20. The router is configured using sub-interfaces for inter-VLAN routing, allowing communication between networks when required.

A trunk port is configured between the router and switch to carry traffic from multiple VLANs.

IP addresses are assigned manually to each PC, and connectivity is tested using ping commands.

---

# Step-by-Step Procedure

## Step 1: Network Topology Creation

* Added one router specifically (2911), one switch, and four PCs in Cisco Packet Tracer.
* Connected devices using copper straight-through cables.

---

## Step 2: VLAN Creation

Created two VLANs:

* VLAN 10 for Admin
* VLAN 20 for Users

---

## Step 3: Assigning Ports to VLANs

Switch ports were assigned to specific VLANs:

* Fa0/1 and Fa0/2 assigned to VLAN 10
* Fa0/3 and Fa0/4 assigned to VLAN 20

---

## Step 4: Router Configuration

Configured router interfaces and enabled inter-VLAN communication using sub-interfaces.

Router configuration:

* 192.168.10.1 for VLAN 10
* 192.168.20.1 for VLAN 20

---

## Step 5: Trunk Port Configuration

Configured the switch port connected to the router as trunk mode to allow VLAN traffic.

---

## Step 6: IP Address Configuration

Assigned IP addresses manually to all PCs.

* PC0 → 192.168.10.2
* PC1 → 192.168.10.3
* PC2 → 192.168.20.2
* PC3 → 192.168.20.3


## Step 7: Connectivity Testing

Connectivity between devices was tested using ping commands in the command prompt.

Successful replies confirmed proper network communication.


# Results

The network was successfully configured and tested. VLAN implementation and network segmentation worked correctly, and devices communicated successfully according to the configuration.


# Learning Outcomes

Through this project, I learned:

* Basic networking concepts
* VLAN implementation
* Router and switch configuration
* Network segmentation
* Basic network security concepts
* Troubleshooting connectivity issues
* Practical usage of Cisco Packet Tracer
