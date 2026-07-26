# 🌐 Scenario 3 – Enterprise Network Routing with EIGRP

## 📖 Overview

This scenario builds upon the enterprise network developed in the previous scenarios by replacing the RIPv2 routing protocol with Enhanced Interior Gateway Routing Protocol (EIGRP). The implementation includes enterprise IP addressing using VLSM, inter-VLAN routing, EIGRP configuration, bandwidth optimization, Access Control Lists (ACLs), and connectivity verification across the corporate and external networks.

---

## 📋 Scenario Requirements

The following tasks were completed as part of this scenario:

- Design the enterprise network topology
- Perform VLSM subnetting and IP address allocation
- Configure VLANs and inter-VLAN routing
- Configure EIGRP (AS 65) on all internal routers
- Advertise all internal subnets using wildcard masks
- Configure bandwidth values for serial links
- Redistribute the default route from the gateway router
- Configure standard and extended ACLs
- Restrict Telnet access using standard ACLs
- Verify EIGRP neighbours and routing tables
- Verify end-to-end connectivity

---

## ⚙️ Implementation

The enterprise network was implemented using Cisco Packet Tracer. Four routers and two switches were configured to provide secure communication between internal VLANs and external networks.

VLSM was used to efficiently allocate IP address space for user VLANs, management VLANs, serial links, and the database server network. Router-on-a-Stick was configured to enable communication between VLANs through IEEE 802.1Q trunking.

The primary enhancement in this scenario was the implementation of the Enhanced Interior Gateway Routing Protocol (EIGRP). EIGRP was configured with Autonomous System (AS) 65 on all internal routers. Individual network statements with wildcard masks were used to advertise internal networks, passive interfaces were configured on user-facing VLANs, bandwidth values were assigned to serial links to influence path selection, and the default route was redistributed from the gateway router.

Access Control Lists (ACLs) were configured to secure access to external resources and restrict Telnet access to routers based on the scenario requirements. Finally, routing tables, neighbour relationships, ACL operation, and end-to-end connectivity were verified to confirm correct network operation.

---

## 📁 Supporting Files

- 🗺️ [Network Diagram](Scenario-3-Network-Diagram.png)
- 📄 [IP Addressing](Scenario-3-IP-Addressing.png)
- 🌐 [EIGRP Configuration](Scenario-3-EIGRP-Configuration.png)
- 🤝 [EIGRP Neighbours](Scenario-3-EIGRP-Neighbours.png)
- 🛣️ [Routing Table](Scenario-3-Routing-Table.png)
- 🔒 [ACL Configuration](Scenario-3-ACL-Configuration.png)
- ✅ [ACL Verification](Scenario-3-ACL-Verification.png)
- 📡 [Connectivity Test](Scenario-3-Connectivity-Test.png)
- ⚙️ [Device Configurations](Scenario-3-Device-Configurations.txt)
- 💻 [Packet Tracer Project](3C.pkt)
