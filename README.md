# SKYNET-ISP — Service Provider Lab

A hands-on EVE-NG lab project focused on service provider networking, routing, and network infrastructure technologies.

## Network Topology

The diagram below illustrates the SKYNET-ISP Service Provider Lab topology.

![SKYNET-ISP Lab Network Topology](03%20-%20Topology%20Screenshot/SKYNET-ISP-LAB-TOPOLOGY.png)

[View the full-resolution topology](03%20-%20Topology%20Screenshot/SKYNET-ISP-LAB-TOPOLOGY.png)

## Technologies Implemented

The SKYNET-ISP lab is a multi-vendor Service Provider network environment built with EVE-NG, designed to demonstrate ISP routing, MPLS services, VPN technologies, IPv6, and network interoperability.

### Network Platforms

- Cisco IOS XR — IOS XRv
- Juniper Junos OS — vMX
- Huawei VRP — NE40E
- Cisco IOL — Switching and aggregation
- EVE-NG — Network emulation and lab environment

### Routing and Control Plane

- BGP — Border Gateway Protocol
- iBGP — Internal BGP
- eBGP — External BGP
- Multi-AS routing scenarios
- Multiple upstream and external BGP peers
- BGP routing policy and route advertisement
- BGP timer tuning
- LDP–IGP Synchronization

### MPLS and VPN Services

- MPLS
- MPLS Layer 3 VPN (L3VPN)
- BGP-based VPN routing
- Provider Edge (PE) and Customer Edge (CE) architectures
- Multi-AS Service Provider routing scenarios

### Ethernet VPN and Layer 2 Services

- EVPN
- Integrated Routing and Bridging (IRB)
- Bridge Domains
- VLAN-based Layer 2 services
- EVPN-based data center connectivity

### IPv4 and IPv6

- IPv4 routing
- IPv6 addressing and routing
- IPv6-enabled EVPN segments
- EIGRP for IPv6 (EIGRPv6)

### Overlay and WAN Technologies

- DMVPN Hub-and-Spoke
- Multi-site connectivity
- Service Provider and customer-edge interconnection

### Upstream Connectivity and AS Scenarios

- Sparkle — External BGP connectivity
- Hurricane Electric (HE)
- Tata Communications
- Verizon
- Customer AS integration
- Multiple autonomous systems and routing domains

### Lab Resources

- Device configuration files in TXT format
- Network topology diagram
- Lab documentation
- EVE-NG Windows Client Pack
- WinSCP installation resource

> **Note:** The technologies listed above describe the lab's documented design and known configurations. Feature availability may vary by device platform and software version.

## Project Contents

- **Full Lab VM:** Complete lab VM archive, hosted on Google Drive.
- **Topology:** Network topology diagram.
- **Lab Configurations:** Device configuration files in TXT format.
- **Documentation:** Project presentation and lab instructions.
- **Reset Instructions:** Instructions for clearing configurations before starting.

## Download the Full Lab VM

The complete VM archive is hosted externally on Google Drive because its size exceeds GitHub's regular file upload limits.

**[Download the SKYNET-ISP Lab VM](https://drive.google.com/file/d/1BP6e-y3PhWYCiR8qE8X3xzRlJFo3omaf/view?usp=drive_link)**

> The archive is not stored in this GitHub repository. Access depends on the sharing permissions configured for the Google Drive file.

## Network Topology

View the [SKYNET-ISP Lab Topology](03%20-%20Topology%20Screenshot/SKYNET-ISP-LAB-TOPOLOGY.png).

## Lab Configurations

The repository includes device configuration files in the [`02 - LAB Configs .TXTs`](02%20-%20LAB%20Configs%20.TXTs/) directory.

## Documentation

- [Project Presentation (PDF)](05%20-%20Skynet%20Lab%20Documentation/Skynet-ISP-LAB-Presentation-V.12.0-EN-US.pdf)
- [English Instructions](07%20-%20READ%20THE%20INSTRUCTIONS/READ-ME-IMPORTANT.txt)
- [Reset Configurations — English](WIPE-ALL-CONFIGS-BEFORE-START.txt)

## Technologies and Topics

The lab covers service provider networking scenarios involving technologies such as BGP, MPLS Layer 3 VPNs, DMVPN, EVPN, and IPv6.

Refer to the topology and project documentation for the specific devices, connections, and implementation details.

## Getting Started

1. Review the topology diagram and project presentation.
2. Obtain the full lab VM archive from the Google Drive link above.
3. Follow the supplied instructions before starting the lab.
4. Review the device configuration files as needed.
5. Follow the reset instructions when a clean configuration state is required.

## Disclaimer

This repository is provided for educational, training, and lab purposes. Review the supplied documentation and software licensing terms before use.

---

**Project:** SKYNET-ISP  
**Repository:** [SnakeLabs / SKYNET-ISP-LAB-OVF-EVE](https://github.com/SnakeEyesRJ/SKYNET-ISP-LAB-OVF-EVE)
