## What is a Router
- Connected to a network just like a host
- Has both an IP address and a MAC address
- Unlike hosts, routers forward packets that are not destined for themselves

## Routing Table
- A map of all networks the router knows about
- Used to decide where to send each packet

## Three Ways a Router Learns Routes
| Type | Definition |
|------|-----------|
| Directly Connected | Networks the router is physically connected to |
| Static Routes | Manually added by a network administrator |
| Dynamic Routes | Automatically learned from other routers |

## Important Rule
- If a router receives a packet with an unknown destination IP it drops the packet
- No match in the routing table = packet is discarded

## Quick Reference
| Term | Definition |
|------|-----------|
| Routing Table | Router's map of all known networks |
| Directly Connected | Route learned from a physical connection |
| Static Route | Route manually configured by an admin |
| Dynamic Route | Route automatically learned from other routers |
| Packet Drop | What happens when destination IP is unknown |
