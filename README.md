# Computer Networks Lab Projects

This repository contains the code and documentation for a series of laboratory exercises related to Computer Networks. The exercises explore various networking concepts including switching, routing, VLANs, and routing protocols using GNS3 network simulation software.

## Table of Contents
- [Project Overview](#project-overview)
- [Lab Exercises](#lab-exercises)
  - [Exercise 1: Introduction to GNS3 - Basic Switching](#exercise-1-introduction-to-gns3---basic-switching)
  - [Exercise 2: Introduction to GNS3 - Router Configuration](#exercise-2-introduction-to-gns3---router-configuration)
  - [Exercise 3: Introduction to MikroTik](#exercise-3-introduction-to-mikrotik)
  - [Exercise 4: Cisco Router Configuration](#exercise-4-cisco-router-configuration)
  - [Exercise 5: OSPF and BGP Routing Protocols](#exercise-5-ospf-and-bgp-routing-protocols)
  - [Exercise 6: VLAN Configuration](#exercise-6-vlan-configuration)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)

## Project Overview

The project focuses on implementing and simulating various network topologies and configurations using GNS3 (Graphical Network Simulator-3). Each lab exercise covers different aspects of computer networking, including:

- **Layer 2 Switching**: Ethernet switches, VLANs, and basic connectivity
- **Layer 3 Routing**: Static routing, dynamic routing protocols (OSPF, BGP)
- **Network Devices**: Cisco routers, MikroTik routers, and various end-user devices
- **Network Protocols**: TCP/IP, routing protocols, and network address translation

The exercises progressively build networking knowledge from basic switch configuration to complex multi-router networks with dynamic routing protocols.

## Lab Exercises

### Exercise 1: Introduction to GNS3 - Basic Switching

**Files**: `1084522_asksi1.gns3project`, `1084522_asksi1.pdf`, `1a_Askisi_Eisagogi_GNS3.pdf`

This exercise introduces the GNS3 network simulation environment with a basic switched network topology.

**Network Topology**:
- 1 Ethernet Switch (Switch1)
- 4 Virtual PCs (PC1, PC2, PC3, PC4)
- 4 Ethernet links connecting all PCs to the switch

**Key Features**:
- Basic GNS3 environment setup
- Ethernet switch configuration with 8 ports
- All ports configured as access ports on VLAN 1
- Simple star topology for basic connectivity testing
- Introduction to VPCS (Virtual PC Simulator) for endpoint simulation

**Learning Objectives**:
- Understand GNS3 interface and workspace
- Create and configure Ethernet switches
- Connect virtual PCs to switches
- Test basic Layer 2 connectivity using ping
- Introduction to network topology design

---

### Exercise 2: Introduction to GNS3 - Router Configuration

**Files**: `1084522_askisi2/1084522_askisi2.gns3project`, `1084522_askisi2.pdf`, `1b_Askisi_Eisagogi_GNS3.pdf`

This exercise extends GNS3 knowledge to router configuration and inter-router connectivity.

**Network Topology**:
- 3 Cisco 7200 Series Routers (R1, R2, R3)
- 3 point-to-point links connecting the routers
- Cisco IOS: c7200-adventerprisek9-mz.153-3.XB12.image

**Key Features**:
- Cisco router deployment in GNS3
- Router-to-router connectivity configuration
- Basic router interface configuration
- Console access to routers via Telnet (ports 5000, 5002, 5004)
- Introduction to Cisco IOS command-line interface

**Learning Objectives**:
- Configure Cisco router interfaces
- Establish router-to-router connections
- Understand Cisco IOS basics
- Configure IP addressing on router interfaces
- Test connectivity between routers
- Introduction to routing concepts

---

### Exercise 3: Introduction to MikroTik

**Files**: `1084590_askisi3.gns3project`, `1084522_ASKISI3.pdf`, `3_Ergasia_Eisagogi_Mikrotik.pdf`

This exercise introduces MikroTik RouterOS as an alternative routing platform.

**Network Topology**:
- 1 MikroTik Router (Microtic-1) - QEMU virtual machine
- 1 Virtual PC (PC1)
- 1 Cloud connector for external connectivity
- 2 network links

**Key Features**:
- MikroTik RouterOS configuration
- Integration of virtual machines (QEMU) with GNS3
- Cloud connectivity for internet simulation
- MikroTik web interface (WebFig) or command-line configuration
- Basic routing and NAT configuration

**Learning Objectives**:
- Introduction to MikroTik RouterOS
- Differences between Cisco IOS and RouterOS
- Basic MikroTik router configuration
- Configure internet connectivity via cloud connector
- NAT and firewall basics on MikroTik

---

### Exercise 4: Cisco Router Configuration

**Files**: `1084522_askisi4.gns3project`, `askisi42.gns3`, `1084522_askisi42.pdf`, `4_Askisi_CiscoRouter_Configuration.pdf`

This exercise focuses on advanced Cisco router configuration with Linux integration.

**Network Topology**:
- 1 Cisco 7200 Router (R1)
- 1 Debian 11.6 Linux Virtual Machine (Debian11.6-1)
- 1 NAT device for internet connectivity
- 2 network connections

**Key Features**:
- Integration of Linux systems with Cisco routers
- NAT configuration for internet access
- Advanced Cisco IOS configuration
- Router-to-server connectivity
- DHCP, DNS, and other network services

**Learning Objectives**:
- Configure Cisco routers for server connectivity
- Understand NAT and PAT concepts
- Integrate Linux systems in network topologies
- Configure routing between different network segments
- Advanced Cisco IOS commands and configurations

---

### Exercise 5: OSPF and BGP Routing Protocols

**Files**: `1084522_askisi5.gns3project`, `1084522_askisi5.pdf`, `5_Askisi_ospf_bgp_GNS3.pdf`

This exercise implements dynamic routing protocols in a complex multi-router network.

**Network Topology**:
- 6 MikroTik Routers (Mikrotik-1 through Mikrotik-6)
- 1 NAT device for internet access
- 8 interconnecting links forming a complex topology
- Multiple routing domains and autonomous systems

**Key Features**:
- OSPF (Open Shortest Path First) configuration
- BGP (Border Gateway Protocol) configuration
- Multiple autonomous systems (AS)
- Inter-AS routing with BGP
- Intra-AS routing with OSPF
- Route redistribution between protocols
- Complex network topology with redundancy

**Learning Objectives**:
- Configure OSPF on MikroTik routers
- Understand OSPF areas and neighbor relationships
- Configure BGP for inter-AS routing
- BGP peering and route advertisement
- Route redistribution strategies
- Analyze routing tables and protocol behavior
- Understand the difference between IGP and EGP protocols
- Network redundancy and failover

---

### Exercise 6: VLAN Configuration

**Files**: `1084522_askisi61.gns3project`, `1084522_askisi6.pdf`, `6_Askisi_VLAN_GNS3.pdf`

This exercise covers Virtual LAN (VLAN) configuration and inter-VLAN routing.

**Topics Covered**:
- VLAN creation and configuration
- Switch port modes (access and trunk)
- Inter-VLAN routing
- VLAN tagging (802.1Q)
- Layer 2 and Layer 3 switching concepts

**Key Features**:
- Multiple VLANs on a single switch
- Trunk ports for VLAN traffic
- Router-on-a-stick configuration
- Inter-VLAN routing
- VLAN segmentation for network security and performance

**Learning Objectives**:
- Create and configure VLANs
- Understand VLAN benefits and use cases
- Configure trunk ports (802.1Q tagging)
- Implement inter-VLAN routing
- Troubleshoot VLAN connectivity issues
- Design segmented networks using VLANs

---

## Technologies Used

### Network Simulation
- **GNS3** (Graphical Network Simulator-3) v2.2.38
  - Network topology design and simulation
  - Device emulation and virtualization
  - Protocol testing and analysis

### Network Devices

#### Routers
- **Cisco 7200 Series Routers**
  - IOS: c7200-adventerprisek9-mz.153-3.XB12.image
  - Used for Cisco IOS configuration exercises
  - Dynamips emulation

- **MikroTik RouterOS**
  - QEMU-based virtual machines
  - Alternative routing platform
  - Used for OSPF/BGP and basic routing exercises

#### Switches
- **Ethernet Switch** (GNS3 built-in)
  - 8-port configurable switches
  - VLAN support
  - 802.1Q tagging

#### End Devices
- **VPCS** (Virtual PC Simulator)
  - Lightweight endpoint simulation
  - Basic TCP/IP stack
  - Ping and trace route utilities

- **Debian Linux 11.6**
  - Full-featured Linux system
  - Network services and applications
  - Real-world server simulation

#### Network Components
- **NAT** (Network Address Translation)
  - Internet connectivity simulation
  - Private to public address translation

- **Cloud Connector**
  - External network connectivity
  - Internet simulation

### Routing Protocols
- **Static Routing**: Manual route configuration
- **OSPF** (Open Shortest Path First): Link-state IGP
- **BGP** (Border Gateway Protocol): Path-vector EGP

### Network Protocols
- **Ethernet** (Layer 2)
- **IP** (Internet Protocol)
- **TCP/UDP** (Transport Layer)
- **ICMP** (Ping, traceroute)
- **ARP** (Address Resolution Protocol)
- **802.1Q** (VLAN Tagging)

---

## Usage

### Running the Exercises

#### Starting a Project
1. Open GNS3
2. Navigate to **File → Open Project**
3. Select the desired exercise `.gns3project` file
4. Click the **Start All Devices** button (green play icon)
5. Wait for all devices to boot (routers may take 1-2 minutes)

#### Accessing Devices

**For Cisco Routers:**
```bash
# Right-click on the router → Console
# Or use Telnet to the console port shown in the topology
telnet localhost <console_port>

# Example for Exercise 2:
# R1: telnet localhost 5002
# R2: telnet localhost 5004
# R3: telnet localhost 5000
```

**For MikroTik Routers:**
```bash
# Right-click on the router → Console (CLI)
# Or access via WebFig (web interface) if configured
# Default username: admin
# Default password: (empty)
```

**For Virtual PCs (VPCS):**
```bash
# Right-click on PC → Console
# Use commands like:
ip <ip_address> <netmask> [gateway]    # Configure IP
show ip                                 # Display configuration
ping <ip_address>                       # Test connectivity
trace <ip_address>                      # Trace route
```

### Example Workflows

#### Exercise 1: Testing Basic Connectivity
```bash
# On PC1 console:
ip 192.168.1.1 255.255.255.0
save

# On PC2 console:
ip 192.168.1.2 255.255.255.0
save

# Test connectivity:
ping 192.168.1.2
```

#### Exercise 2: Router Configuration
```bash
# On R1 console:
enable
configure terminal
interface FastEthernet 0/0
ip address 10.0.1.1 255.255.255.0
no shutdown
exit

# Verify configuration:
show ip interface brief
show ip route
```

#### Exercise 5: OSPF Configuration
```bash
# On MikroTik router:
/routing ospf instance
add name=default router-id=1.1.1.1

/routing ospf area
add instance=default name=backbone

/routing ospf network
add network=10.0.0.0/24 area=backbone

# Verify OSPF:
/routing ospf neighbor print
/routing ospf route print
```

### Documentation Files

Each exercise folder contains:
- **`.gns3project`**: GNS3 project file (open with GNS3)
- **`.pdf`**: Exercise documentation and assignment description
- **`.docx`**: Exercise report and solutions (student submission)

Refer to the PDF files in each exercise folder for:
- Detailed assignment requirements
- Network topology diagrams
- Configuration instructions
- Expected outcomes and verification steps

---

## Project Structure

```
Computer Networks/
│
├── Exercise 01/                              # Introduction to GNS3 - Basic Switching
│   ├── 1084522_asksi1.gns3project           # GNS3 project file
│   ├── 1084522_asksi1.pdf                   # Exercise solution/report
│   ├── 1084522_asksi1.docx                  # Exercise solution/report (editable)
│   └── 1a_Askisi_Eisagogi_GNS3.pdf          # Assignment description
│
├── Exercise 02/                              # Introduction to GNS3 - Router Configuration
│   ├── 1084522_askisi2/
│   │   ├── 1084522_askisi2.gns3project      # GNS3 project file
│   │   ├── 1084522_askisi2.pdf              # Exercise solution/report
│   │   └── 1084522_askisi2.docx             # Exercise solution/report (editable)
│   └── 1b_Askisi_Eisagogi_GNS3.pdf          # Assignment description
│
├── Exercise 03/                              # Introduction to MikroTik
│   ├── 1084590_askisi3.gns3project          # GNS3 project file
│   ├── 1084522_ASKISI3.pdf                  # Exercise solution/report
│   └── 3_Ergasia_Eisagogi_Mikrotik.pdf      # Assignment description
│
├── Exercise 04/                              # Cisco Router Configuration
│   ├── 1084522_askisi4 .gns3project         # GNS3 project file (primary)
│   ├── askisi42.gns3                        # GNS3 configuration file
│   ├── 1084522_askisi42.pdf                 # Exercise solution/report
│   ├── 1084522_askisi42.docx                # Exercise solution/report (editable)
│   ├── 4_Askisi_CiscoRouter_Configuration.pdf       # Assignment description
│   └── 4_Askisi_CiscoRouter_Configuration+.pdf      # Assignment description (extended)
│
├── Exercise 05/                              # OSPF and BGP Routing Protocols
│   ├── 1084522_askisi5.gns3project          # GNS3 project file
│   ├── 1084522_askisi5.pdf                  # Exercise solution/report
│   ├── 5_Askisi_ospf_bgp_GNS3.pdf           # Assignment description
│   └── 5_Askisi_ospf_bgp_GNS3+.pdf          # Assignment description (extended)
│
├── Exercise 06/                              # VLAN Configuration
│   ├── 1084522_askisi61.gns3project         # GNS3 project file
│   ├── 1084522_askisi6.pdf                  # Exercise solution/report
│   ├── 6_Askisi_VLAN_GNS3.pdf               # Assignment description
│   ├── 6_Askisi_VLAN_GNS3+.pdf              # Assignment description (extended)
│   ├── chapter4.zip                          # Additional resources
│   └── vIOS-L2.zip                           # Cisco IOS switch image
│
└── README.md                                 # This file
```

---

## Contact

**Student ID**: 1084522  
**Course**: Computer Networks Laboratory  
**Institution**: University of Patras

For questions or issues regarding these exercises, please contact the course instructor or refer to the course materials.

---
