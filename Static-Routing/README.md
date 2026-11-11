# Static Routing – Cisco Packet Tracer Lab

## Objective
Connect two separate LAN networks using two routers and configure static routes to allow communication between them.

## Network Equipment
- 2 Cisco 1941 Routers
- 2 Cisco 2960 Switches
- 4 PCs

## Network Addressing

| Device | Interface | IP Address |
|---|---|---|
| R1 | G0/1 | 192.168.10.1/24 |
| R1 | G0/0 | 10.0.0.1/30 |
| R2 | G0/1 | 192.168.20.1/24 |
| R2 | G0/0 | 10.0.0.2/30 |

## PC Addressing

| Device | IP Address | Default Gateway |
|---|---|---|
| PC1 | 192.168.10.11 | 192.168.10.1 |
| PC2 | 192.168.10.12 | 192.168.10.1 |
| PC3 | 192.168.20.11 | 192.168.20.1 |
| PC4 | 192.168.20.12 | 192.168.20.1 |

Subnet mask for all PCs: 255.255.255.0

## Skills Demonstrated
- Router interface configuration
- IP addressing and subnetting
- Static route configuration
- Next-hop routing
- Routing table verification
- Network connectivity testing
- Troubleshooting

## Cisco Technologies
- IPv4
- Static routing
- Connected routes
- Routing tables

## Testing and Verification
- Verify interfaces using `show ip interface brief`.
- Verify routing tables using `show ip route`.
- Verify static routes using `show running-config`.
- Ping between the two routers.
- Ping between PCs on separate networks.


## Conclusion
This lab demonstrates how static routes allow routers to forward traffic between separate networks using manually configured next-hop addresses.
