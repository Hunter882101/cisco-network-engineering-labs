# Enterprise Network Design & Troubleshooting Lab

## Project Overview

Designed and configured a multi-VLAN enterprise network using Cisco 2911 routers and Catalyst 2960 switches.

The lab focuses on network segmentation, DHCP, inter-VLAN routing, and troubleshooting common connectivity problems involving VLAN assignments, trunking, native VLAN mismatches, and switch access-port configuration.

## Network Topology

![Network Topology](topology.png)

## VLAN Design

| VLAN | Department |
| ---- | ---------- |
| 10   | Sales      |
| 20   | IT         |
| 30   | Guest      |
| 50   | HR         |

## Technologies Used

* Cisco Packet Tracer
* Cisco 2911 Router
* Cisco Catalyst 2960 Switches
* VLANs 10, 20, 30, and 50
* 802.1Q Trunking
* Router-on-a-Stick
* Inter-VLAN Routing
* DHCP
* IPv4 Addressing
* Cisco IOS Troubleshooting

## Network Objectives

1. Segment departments using VLANs.
2. Configure 802.1Q trunking between network devices.
3. Implement Router-on-a-Stick inter-VLAN routing.
4. Configure DHCP for automatic client IP assignments.
5. Diagnose and resolve common network connectivity issues.
6. Verify network functionality using Cisco IOS commands.

## Configuration

### VLAN Segmentation

Implemented VLANs 10, 20, 30, and 50 for Sales, IT, Guest, and HR departments.

### Inter-VLAN Routing

Configured Router-on-a-Stick using 802.1Q trunking and router subinterfaces to enable communication between departmental networks.

### DHCP

Configured router-based DHCP pools to automatically assign:

* IP addresses
* Default gateways
* DNS settings

## Troubleshooting Scenarios

Diagnosed and resolved network connectivity and DHCP issues involving:

* Incorrect VLAN assignments
* Trunk configuration
* Native VLAN mismatches
* Switch access-port settings
* DHCP operation
* Client connectivity

## Verification Commands

```text
show vlan brief
show interfaces trunk
show ip interface brief
show ip dhcp
ping
```

## Verification Results

* Verified VLAN assignments.
* Checked trunk configuration and operation.
* Verified router subinterfaces.
* Tested DHCP address assignment.
* Troubleshot and corrected connectivity issues.
* Confirmed network functionality using Cisco IOS verification commands.

## Skills Demonstrated

* Enterprise network design
* VLAN configuration
* Inter-VLAN routing
* DHCP
* 802.1Q trunking
* Cisco IOS
* Network troubleshooting
* Technical documentation
