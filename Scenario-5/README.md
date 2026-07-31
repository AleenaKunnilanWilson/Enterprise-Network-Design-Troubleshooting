# 🌐 Scenario 5 – Enterprise Network Services using DHCP, NAT & PAT

## 📖 Overview

This scenario demonstrates the implementation of enterprise network services within a routed network using Cisco Packet Tracer. Building on the previous scenarios, the network integrates dynamic routing, access control, Dynamic Host Configuration Protocol (DHCP), and Network Address Translation (NAT) to provide secure and efficient communication between internal and external networks.

The scenario is completed in three stages (Pass, Credit, and Distinction), progressively extending the network from a basic enterprise deployment to a fully functional enterprise network with automatic IP address allocation and Internet access using NAT.

---

## 📋 Scenario Requirements

### Scenario 5-P (Pass)

Implement the enterprise network by:

- Configuring VLANs and Inter-VLAN Routing
- Configuring OSPF dynamic routing
- Implementing Access Control Lists (ACLs)
- Configuring switch management and port security
- Configuring static routing on the ISP router
- Verifying end-to-end network connectivity

### Scenario 5-C (Credit)

Extend the Pass implementation by:

- Configuring DHCP services on the Korba router
- Creating DHCP pools for VLANXXX and VLANYYY
- Excluding reserved IP addresses from DHCP allocation
- Verifying automatic IP address assignment for client devices

### Scenario 5-D (Distinction)

Extend the Credit implementation by:

- Configuring Network Address Translation (NAT)
- Creating multiple NAT public address pools
- Configuring NAT ACLs
- Implementing PAT (NAT Overload)
- Verifying Internet connectivity through NAT translation
- Monitoring NAT translations and statistics

---

## ⚙️ Implementation

The network was implemented using Cisco Packet Tracer and configured through Cisco IOS CLI.

Key technologies implemented include:

- VLAN Configuration
- Inter-VLAN Routing
- OSPF Dynamic Routing
- Access Control Lists (ACLs)
- DHCP Server Configuration
- DHCP Address Exclusion
- NAT Address Pools
- Port Address Translation (PAT)
- Static Routing
- Connectivity Verification
- Network Troubleshooting

---

## 📁 Supporting Files

### Scenario 5-P (Pass)

- 🗺️ [Network Diagram](Scenario-5-Network-Diagram.png)
- 📄 [IP Addressing](Scenario-5-IP-Addressing.png)
- 🌐 [OSPF Configuration](Scenario-5-OSPF-Configuration.png)
- 🔒 [ACL Configuration](Scenario-5-ACL-Configuration.png)
- ✅ [Connectivity Verification](Scenario-5-Connectivity-Verification.png)

### Scenario 5-C (Credit)

- 🌐 [DHCP Configuration](Scenario-5-DHCP-Configuration.png)
- 📋 [DHCP Address Allocation - PC1](Scenario-5-DHCP-Address-Allocation-PC1.png)
- 📋 [DHCP Address Allocation - PC2](Scenario-5-DHCP-Address-Allocation-PC2.png)
- ✅ [PC1 to PC2 Connectivity Verification](Scenario-5-PC1-to-PC2-Connectivity-Verification.png)
- ✅ [PC2 to PC1 Connectivity Verification](Scenario-5-PC2-to-PC1-Connectivity-Verification.png)

### Scenario 5-D (Distinction)

- 🌍 [NAT Configuration](Scenario-5-NAT-Configuration.png)
- 🔄 [PAT Configuration](Scenario-5-PAT-Configuration.png)
- 📋 [NAT Translation Table](Scenario-5-NAT-Translation-Table.png)
- 📊 [NAT Statistics](Scenario-5-NAT-Statistics.png)
- 🌐 [Internet Connectivity Verification](Scenario-5-Internet-Connectivity-Verification.png)

### Implementation Files

- ⚙️ [Device Configurations](Scenario-5-Device-Configurations.txt)
- 💻 [Packet Tracer Project](5C.pkt)
