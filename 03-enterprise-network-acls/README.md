# Enterprise Network Design & ACL Implementation

## Project Overview

Designed and configured a simulated enterprise network using Cisco routers and switches to segment Users, IT, Servers, and Management departments.

The lab demonstrates VLAN segmentation, inter-VLAN routing, DHCP, and extended Access Control Lists (ACLs) to control communication between network segments.

## Network Topology

![Network Topology](topology.png)

## Technologies Used

* Cisco Packet Tracer
* Cisco Routers
* Cisco Switches
* VLANs
* 802.1Q Trunking
* Router-on-a-Stick
* Inter-VLAN Routing
* IPv4 Addressing
* DHCP
* Extended ACLs
* Cisco IOS Verification Commands

## Network Objectives

1. Segment enterprise departments into separate VLANs.
2. Configure inter-VLAN routing using Router-on-a-Stick.
3. Automate client IP addressing with DHCP.
4. Restrict unauthorized traffic between departments.
5. Permit approved communication between network segments.
6. Verify and document network security policies.

## Configuration

### VLAN Segmentation

Created separate VLANs for:

* Users
* IT
* Servers
* Management

### Inter-VLAN Routing

Implemented Router-on-a-Stick using 802.1Q trunking and router subinterfaces to enable communication between departmental networks.

### DHCP

Configured DHCP pools to provide:

* IPv4 addresses
* Default gateways
* DNS settings

### Access Control Lists

Developed and applied extended ACLs to restrict unauthorized inter-department traffic while permitting approved communication between network segments.

## Troubleshooting

Verified network connectivity, trunk operation, VLAN assignments, and ACL functionality.

Troubleshooting included:

* VLAN configuration
* Trunk operation
* Router subinterfaces
* IP addressing
* ACL behavior
* Inter-department connectivity

## Verification Commands

```text
show vlan brief
show interfaces trunk
show ip interface brief
show ip route
show access-lists
ping
```

## Verification Results

* Verified VLAN assignments and trunk operation.
* Tested connectivity between network segments.
* Tested ACL functionality using simulated traffic.
* Reviewed ACL hit counters to confirm policy behavior.
* Documented and tested network security policies.

## Skills Demonstrated

* Enterprise network design
* VLAN segmentation
* Inter-VLAN routing
* DHCP
* Extended ACLs
* Network security fundamentals
* Cisco IOS troubleshooting
* Technical documentation
