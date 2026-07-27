# 🌐 Scenario 4 – Enterprise Network Routing with OSPF

## 📖 Overview

This scenario builds upon the enterprise network developed in the previous scenarios by replacing EIGRP with Open Shortest Path First (OSPF). The implementation includes enterprise IP addressing using VLSM, inter-VLAN routing, Single-Area OSPF, Multi-Area OSPF, bandwidth optimization, Access Control Lists (ACLs), and connectivity verification across the corporate and external networks.

Scenario 4 consists of two stages:

- **Scenario 4-P (Pass):** Implementation of a Single-Area OSPF enterprise network.
- **Scenario 4-D (Distinction):** Extension of the network to a Multi-Area OSPF design, improving routing scalability and organization.

---

## 📋 Scenario Requirements

The following tasks were completed as part of this scenario:

### Scenario 4-P (Pass)

- Design the enterprise network topology
- Perform VLSM subnetting and IP address allocation
- Configure VLANs and inter-VLAN routing
- Configure OSPF on all internal routers
- Advertise all internal subnets using wildcard masks
- Configure bandwidth values for serial links
- Advertise the default route from the gateway router
- Configure standard and extended ACLs
- Restrict Telnet access using standard ACLs
- Verify OSPF neighbours and routing tables
- Verify end-to-end connectivity

### Scenario 4-D (Distinction)

- Convert the Single-Area OSPF network to a Multi-Area OSPF deployment
- Configure OSPF Area 0 as the backbone network
- Configure Area 1, Area 2, and Area 3 for internal LAN segments
- Verify Multi-Area OSPF neighbour relationships
- Verify OSPF databases and routing tables
- Test network convergence after LAN and serial link failures
- Verify end-to-end connectivity following topology changes

---

## ⚙️ Implementation

The enterprise network was implemented using Cisco Packet Tracer. Four routers and two switches were configured to provide secure communication between internal VLANs and external networks.

VLSM was used to efficiently allocate IP address space for user VLANs, management VLANs, serial links, and the database server network. Router-on-a-Stick was configured to enable communication between VLANs through IEEE 802.1Q trunking.

The primary enhancement in **Scenario 4-P** was the implementation of Open Shortest Path First (OSPF) as the enterprise routing protocol. OSPF was configured on all internal routers, internal subnets were advertised using wildcard masks, passive interfaces were configured on user-facing VLANs, bandwidth values were assigned to serial links, and the default route was advertised from the gateway router.

In **Scenario 4-D**, the Single-Area OSPF network was extended to a Multi-Area OSPF deployment. Area 0 was configured as the backbone area, while the LAN networks connected to Latur, Barshi, and Udgir routers were assigned to Areas 1, 2, and 3 respectively. The implementation was validated by verifying OSPF neighbour relationships, routing tables, OSPF databases, and successful route convergence following simulated network failures.

Access Control Lists (ACLs) were configured to secure access to external resources and restrict Telnet access to routers according to the scenario requirements. Finally, routing tables, OSPF neighbour relationships, ACL operation, and end-to-end connectivity were verified to confirm correct network operation.

---

## 📁 Supporting Files

- 🗺️ Network Diagram
- 📄 IP Addressing
- 🌐 OSPF Configuration
- 🌍 Multi-Area OSPF Configuration
- 🤝 OSPF Neighbours
- 🛣️ Routing Table
- 🔒 ACL Configuration
- ✅ ACL Verification
- 📡 Connectivity Test
- ⚙️ Device Configurations
- 💻 Packet Tracer Project
