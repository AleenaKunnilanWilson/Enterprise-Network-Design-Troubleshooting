# 🌐 Scenario 6 – Enterprise Network with PPP and CHAP Authentication

## 📖 Overview

This scenario demonstrates the implementation of a complete enterprise network using Cisco Packet Tracer. The network integrates VLANs, Inter-VLAN Routing, OSPF dynamic routing, Access Control Lists (ACLs), DHCP, NAT/PAT, and Point-to-Point Protocol (PPP) with CHAP authentication.

This scenario is completed in two stages. The Pass task implements a complete enterprise network using VLANs, Inter-VLAN Routing, OSPF, ACLs, DHCP, NAT/PAT, and static routing. The Credit task extends the implementation by configuring PPP encapsulation and CHAP authentication between Nagri_R1 and Daspur_R2, followed by connectivity verification across the authenticated serial link.

---

## 📋 Scenario Requirements

### Scenario 6-P (Pass)

Implement the enterprise network by:

- Configuring VLANs and Inter-VLAN Routing
- Configuring OSPF dynamic routing
- Implementing Access Control Lists (ACLs)
- Configuring DHCP services
- Configuring NAT/PAT
- Configuring static routing where required
- Verifying end-to-end network connectivity

### Scenario 6-C (Credit)

Extend the Pass implementation by:

- Configuring PPP encapsulation on the serial link
- Configuring CHAP authentication between Nagri_R1 and Daspur_R2
- Verifying successful PPP link establishment
- Verifying successful CHAP authentication
- Testing end-to-end connectivity across the authenticated PPP link

---

## ⚙️ Implementation

The network was implemented using Cisco Packet Tracer and configured using Cisco IOS CLI. The implementation combines enterprise networking technologies with secure WAN connectivity using PPP and CHAP authentication.

Key technologies implemented include:

- VLAN Configuration
- Inter-VLAN Routing
- OSPF Dynamic Routing
- Access Control Lists (ACLs)
- DHCP
- NAT/PAT
- Static Routing
- PPP Encapsulation
- CHAP Authentication
- Connectivity Verification
- Network Troubleshooting

---

## 📁 Supporting Files

### Scenario 6-P (Pass)

- 🗺️ [Network Diagram](Scenario-6-Network-Diagram.png)
- 📄 [IP Addressing](Scenario-6-IP-Addressing.png)
- 🌐 [Nagri_R1 OSPF Configuration](Scenario-6-Nagri_R1-OSPF-Configuration.png)
- 🛣️ [Nagri_R1 Routing Table](Scenario-6-Nagri_R1-Routing-Table.png)
- 🌐 [Daspur_R2 OSPF Configuration](Scenario-6-Daspur_R2-OSPF-Configuration.png)
- 🛣️ [Daspur_R2 Routing Table](Scenario-6-Daspur_R2-Routing-Table.png)
- 🌐 [DHCP Configuration](Scenario-6-DHCP-Configuration.png)
- 📋 [DHCP Address Allocation - PC0](Scenario-6-DHCP-Address-Allocation-PC0.png)
- 📋 [DHCP Address Allocation - PC1](Scenario-6-DHCP-Address-Allocation-PC1.png)
- 🌍 [NAT Configuration](Scenario-6-NAT-Configuration.png)
- 📋 [NAT Translation Table](Scenario-6-NAT-Translation-Table.png)
- 🌐 [Internet Connectivity Verification](Scenario-6-Internet-Connectivity-Verification.png)

### Scenario 6-C (Credit)

- 🔐 [Nagri_R1 CHAP Configuration](Scenario-6-Nagri_R1-CHAP-Configuration.png)
- 🔐 [Daspur_R2 CHAP Configuration](Scenario-6-Daspur_R2-CHAP-Configuration.png)
- 📡 [Nagri_R1 PPP Interface Status](Scenario-6-Nagri_R1-PPP-Interface-Status.png)
- 📡 [Daspur_R2 PPP Interface Status](Scenario-6-Daspur_R2-PPP-Interface-Status.png)
- ✅ [PPP and CHAP Connectivity Verification](Scenario-6-PPP-CHAP-Connectivity-Verification.png)

### Implementation Files

- ⚙️ [Device Configurations](Scenario-6-Device-Configurations.txt)
- 💻 [Packet Tracer Project](6C.pkt)
