# CNRoutingAssignment

This repository contains the Cisco Packet Tracer files for the Computer Networks practical assignment on Router Configuration and Routing Protocols.

## Repository Contents

| File | Description |
|------|--------------|
| `Task1.pkt` | Basic router configuration — hostname change, console password, and login authentication. |
| `Task2.pkt` | Static routing configuration across a three-router topology connecting three separate networks (Network A, B, and C), with IP addressing and static routes configured on all routers, and verified end-to-end connectivity. |
| `Task3.pkt` | Dynamic routing configuration on a three-router linear topology. Includes RIP configuration (Part A) and EIGRP configuration (Part B, with RIP removed), both verified for full connectivity between all networks. |

## Task Overview

### Task 1 – Router Basic Configuration
- Configured hostname as `KandyNSBM_<StudentID>`
- Set console password to `NSBM`
- Enabled login authentication on the console line

### Task 2 – Static Routing Configuration
- Configured IP addressing on three routers (ComputingRouter, BusinessRouter, ScienceRouter) and their connected LANs
- Configured static routes on all routers to enable full inter-network communication
- Verified connectivity via ping tests between Network A ↔ B, A ↔ C, and B ↔ C

### Task 3 – Dynamic Routing Configuration
- **Part A (RIP):** Configured RIPv2 on all three routers (KandyNSBM, ColomboNSBM, GalleNSBM) and verified connectivity between PC4 and PC5
- **Part B (EIGRP):** Removed RIP configuration and configured EIGRP (AS 10) on all three routers, then re-verified end-to-end connectivity

## How to Use
1. Download and install [Cisco Packet Tracer](https://www.netacad.com/courses/packet-tracer)
2. Open any `.pkt` file listed above
3. Click on a router and go to the CLI tab to view its configuration
4. Use `show running-config`, `show ip route`, and `show ip protocols` / `show ip eigrp neighbors` to inspect the active configuration
5. Test connectivity using the Command Prompt on end devices (PCs) with the `ping` command

## Author
- **Name:** H. K. Chamod
- **Student ID:** 39163
- **Module:** Computer Networks
- **Assignment:** Practical Assignment – Router Configuration and Routing Protocols using Cisco Packet Tracer
