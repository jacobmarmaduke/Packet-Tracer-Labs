# VLANs and Trunking – Cisco Packet Tracer Lab

## Objective
Build a small network using multiple VLANs and configure trunk links between switches to allow VLAN traffic to travel between switches.

## Network Equipment
- 2 Cisco 2960 Switches
- 4 End Devices (PCs)
- Copper Straight-Through cables

## Skills Demonstrated
- Creating and naming VLANs
- Assigning switch ports to VLANs
- Configuring access ports
- Configuring trunk ports
- Allowing VLAN traffic across multiple switches
- Verifying VLAN and trunk configurations

## VLAN Configuration

| VLAN | Name | Network |
|---|---|---|
| 10 | SALES | 192.168.10.0/24 |
| 20 | IT | 192.168.20.0/24 |

## Cisco IOS Commands
- vlan 10
- `vlan 20`
- `switchport mode access`
- `switchport access vlan 10`
- `switchport access vlan 20`
- `switchport mode trunk`
- `show vlan brief`
- `show interfaces trunk`

## Testing and Verification
- Verify VLAN creation using `show vlan brief`.
- Verify trunk connections using `show interfaces trunk`.
- Test connectivity between devices in the same VLAN across both switches.
- Confirm devices in different VLANs cannot communicate without inter-VLAN routing.

## Files Included
- Packet Tracer topology (.pkt)
- Switch configurations (.txt)
- Network topology screenshot (.png)



## Conclusion
This lab demonstrates basic Layer 2 switching concepts, VLAN segmentation, and trunking between Cisco switches.
