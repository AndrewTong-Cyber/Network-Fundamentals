## Types of Frames
| Frame Type | Destination MAC | Behavior |
|------------|----------------|----------|
| Unicast | Specific host MAC | Sent only to that host |
| Broadcast | ffff.ffff.ffff | Flooded to every device on the network |

## Broadcast Rules
- Broadcast frames are always flooded
- Switches only send broadcasts if traffic is going to or from the switch itself

## VLANs (Virtual Local Area Networks)
- Divides switch ports into isolated groups
- Devices in different VLANs cannot communicate directly even if on the same switch
- Think of it like walls inside a building — same building but separated rooms
- Example: VLAN 20 is completely isolated from VLAN 10
- Switches perform all three actions (Learn, Flood, Forward) within each VLAN separately

## Multiple Switches
- Each switch maintains its own independent MAC address table
- Each switch performs Learn, Flood, and Forward independently
- They do not share MAC tables with each other

## Quick Reference
| Term | Definition |
|------|-----------|
| Unicast Frame | Sent to one specific destination MAC |
| Broadcast Frame | Sent to all devices using ffff.ffff.ffff |
| VLAN | Logical separation of switch ports into isolated groups |
| MAC Address Table | Each switch keeps its own separate table |
