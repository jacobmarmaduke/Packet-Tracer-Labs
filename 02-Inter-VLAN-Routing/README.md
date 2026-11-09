# Inter-VLAN Routing – Cisco Packet Tracer Lab

## Objective
Configure router-on-a-stick to allow communication between two separate VLANs using a single physical router interface.

## Network Equipment
- 1 Cisco 1941 Router
- 2 Cisco 2960 Switches
- 4 PCs

## Skills Demonstrated
- VLAN configuration
- 802.1Q trunking
- Router-on-a-stick configuration
- Router subinterfaces
- Inter-VLAN routing
- Default gateway configuration
- Network connectivity testing

## VLAN Configuration

| VLAN | Name | Network | Default Gateway |
|---|---|---|---|
| 10 | SALES | 192.168.10.0/24 | 192.168.10.1 |
| 20 | IT | 192.168.20.0/24 | 192.168.20.1 |

## Cisco Technologies
- VLANs
- IEEE 802.1Q
- Router subinterfaces
- Inter-VLAN routing

## Testing and Verification
- Verify VLAN configuration using `show vlan brief`.
- Verify trunk links using `show interfaces trunk`.
- Verify router interfaces using `show ip interface brief`.
- Test connectivity between VLAN 10 and VLAN 20.
- Verify PCs can reach their default gateways.

## Troubleshooting
Document any configuration errors encountered and how they were resolved.

## Conclusion
This lab demonstrates how a Cisco router can route traffic between multiple VLANs using router-on-a-stick and 802.1Q encapsulation.
