# Multi-Site Enterprise Network — OSPF

## Project Overview

Designed and configured a three-site enterprise network connecting a headquarters location and two branch offices using Cisco 2911 routers and Catalyst 2960 switches.

The lab demonstrates dynamic routing, WAN connectivity, IPv4 addressing, DHCP, and structured troubleshooting across geographically separated network sites.

## Network Topology

![Network Topology](topology.png)

The network consists of:

* Headquarters
* Branch Office 1
* Branch Office 2
* Cisco routers and switches
* End-user PCs

## Technologies Used

* Cisco Packet Tracer
* Cisco 2911 Routers
* Cisco Catalyst 2960 Switches
* OSPF Dynamic Routing
* IPv4 Addressing
* /30 WAN Point-to-Point Networks
* DHCP
* Default Gateways
* ICMP Connectivity Testing

## Network Objectives

1. Connect three geographically separated enterprise sites.
2. Configure OSPF to establish routing relationships between routers.
3. Advertise LAN networks across the enterprise WAN.
4. Configure IPv4 addressing and DHCP services.
5. Verify end-to-end connectivity between sites.
6. Troubleshoot routing and WAN connectivity failures.

## Configuration

### OSPF Dynamic Routing

Configured OSPF on the Cisco routers to establish neighbor adjacencies and advertise LAN networks between headquarters and the branch offices.

### WAN Connectivity

Implemented /30 IPv4 point-to-point networks for router-to-router WAN connections.

### DHCP

Configured DHCP services to provide IP addresses and default gateway information to client devices.

## Troubleshooting

Performed structured troubleshooting of WAN and OSPF connectivity failures.

Troubleshooting areas included:

* OSPF neighbor relationships
* WAN connectivity
* IP addressing
* Routing information
* End-to-end communication between sites

## Verification Commands

```text
show ip ospf neighbor
show ip route
show ip interface brief
ping
```

## Verification Results

* Verified OSPF neighbor adjacencies.
* Confirmed dynamically learned routes.
* Tested end-to-end connectivity between PCs across multiple sites.
* Documented network topology, addressing schemes, device configurations, and troubleshooting procedures.

## Skills Demonstrated

* Enterprise WAN design
* OSPF dynamic routing
* IPv4 addressing
* Router configuration
* DHCP
* Routing verification
* Network troubleshooting
* Technical documentation

