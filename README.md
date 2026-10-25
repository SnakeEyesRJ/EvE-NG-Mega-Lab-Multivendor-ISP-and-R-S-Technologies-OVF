# SKYNET-ISP — Service Provider Lab

![Profile Banner](PROFILE20%COVER-2026.png)

A hands-on EVE-NG lab project focused on service provider networking, routing, switching, and multivendor network infrastructure technologies.

**Author:** [Emildo Lahud](https://github.com/SnakeEyesRJ)  
**Repository:** [EvE-NG-Mega-Lab-Multivendor-ISP-and-R-S-Technologies-OVF](https://github.com/SnakeEyesRJ/EvE-NG-Mega-Lab-Multivendor-ISP-and-R-S-Technologies-OVF)

---

## Network Topology

The diagram below illustrates the SKYNET-ISP Service Provider Lab topology.

![SKYNET-ISP Lab Network Topology](03%20-%20Topology%20Screenshot/SKYNET-ISP-LAB-TOPOLOGY.png)

[View the full-resolution topology](03%20-%20Topology%20Screenshot/SKYNET-ISP-LAB-TOPOLOGY.png)

## Technologies Implemented

SKYNET-ISP is a multivendor Service Provider network environment built with EVE-NG, designed to demonstrate ISP routing, MPLS services, VPN technologies, IPv6, and network interoperability.

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

> **Note:** The technologies listed above describe the lab's documented design and known configurations. Feature availability may vary by device platform and software version.

## Project Contents

- **Full Lab VM:** Complete lab VM archive hosted on Google Drive.
- **Topology:** Network topology diagram.
- **Lab Configurations:** Device configuration files in TXT format.
- **Documentation:** Project presentation and lab instructions.
- **EVE-NG Windows Client Pack:** Supporting client integration resources.
- **WinSCP:** Supporting file transfer resource.
- **Reset Instructions:** Instructions for clearing device configurations before starting.

## Download the Full Lab VM

The complete VM archive is hosted externally on Google Drive because of its size.

**[Download the SKYNET-ISP Lab VM](https://drive.google.com/file/d/1BP6e-y3PhWYCiR8qE8X3xzRlJFo3omaf/view?usp=drive_link)**

The archive is not stored in this GitHub repository. Access depends on the sharing permissions configured for the Google Drive file.

## Lab Configurations

Device configuration files are available in the [`02 - LAB Configs .TXTs`](02%20-%20LAB%20Configs%20.TXTs/) directory.

These files provide a starting point for examining the lab's device configurations and networking scenarios.

## Documentation

- [Project Presentation (PDF)](05%20-%20Skynet%20Lab%20Documentation/Skynet-ISP-LAB-Presentation-V.12.0-EN-US.pdf)
- [English Instructions](07%20-%20READ%20THE%20INSTRUCTIONS/READ-ME-IMPORTANT.txt)
- [Reset Configurations — English](WIPE-ALL-CONFIGS-BEFORE-START.txt)

## Getting Started

1. Review the network topology and project presentation.
2. Download the full lab VM archive from the Google Drive link above.
3. Review the supplied instructions before starting the lab.
4. Confirm that your EVE-NG environment and required device images are compatible.
5. Review the device configuration files as needed.
6. Follow the reset instructions only when a clean configuration state is required.

### Important: Configuration Reset

**Read `WIPE-ALL-CONFIGS-BEFORE-START.txt` before performing any reset operation.**

Reset procedures may erase device configurations and remove work from previous lab sessions. Back up any configurations you want to preserve before proceeding.

## Related Project — SecureCRT Keyword Highlight

In addition to the SKYNET-ISP lab, I maintain a separate project for multivendor SecureCRT keyword highlighting.

The project provides keyword-highlighting resources intended to make network CLI output easier to read and help identify important commands, protocol states, and troubleshooting information.

**[Explore the SecureCRT Keyword Highlight — Multivendor Repository](https://github.com/SnakeEyesRJ/SecureCRT-Keyword-Highligh-Multivendor)**

This is a separate project and is not required to run the SKYNET-ISP lab.

## About the Author

**SnakeEyesRJ/BR**  
Senior Network Engineer & Instructor

Focused on routing and switching, service provider networking, multivendor interoperability, network infrastructure, and technical training.

- **GitHub:** [@SnakeEyesRJ](https://github.com/SnakeEyesRJ)
- **SKYNET-ISP Lab:** [View Repository](https://github.com/SnakeEyesRJ/EvE-NG-Mega-Lab-Multivendor-ISP-and-R-S-Technologies-OVF)
- **SecureCRT Keyword Highlight:** [View Repository](https://github.com/SnakeEyesRJ/SecureCRT-Keyword-Highligh-Multivendor)

## Disclaimer

This repository is provided for educational, training, testing, and laboratory purposes.

All product names, trademarks, software names, and vendor references belong to their respective owners. Users are responsible for obtaining the appropriate software, licenses, and permissions required for their environments.

Feature availability and compatibility depend on the specific software images, versions, and configurations used.

## Support the Project

If you find this project useful:

- ⭐ Star the repository.
- 👀 Follow the project as it evolves.
- 🧪 Experiment with the lab and share constructive feedback.
- 🛠️ Contribute improvements and documentation where appropriate.

---

**Project:** SKYNET-ISP  
**Repository:** [SnakeEyesRJ / EvE-NG-Mega-Lab-Multivendor-ISP-and-R-S-Technologies-OVF](https://github.com/SnakeEyesRJ/EvE-NG-Mega-Lab-Multivendor-ISP-and-R-S-Technologies-OVF)

*Explore. Configure. Validate. Troubleshoot.*
