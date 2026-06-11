## What is Switching
- The process of moving data within a network
- All devices connected to a switch belong to the same IP network
- Switches are Layer 2 devices — they only use MAC addresses to make decisions

## MAC Address Table
- A table the switch maintains that maps switch ports to MAC addresses
- Think of it like a seating chart — the switch knows exactly which device sits on which port

## Three Switch Actions
| Action | Definition |
|--------|-----------|
| Learn | Records the source MAC address and which port it came from |
| Flood | Sends the frame out of every port when destination is unknown |
| Forward | Delivers the frame only to the correct port using the MAC table |

## How It Works
1. Host sends a frame to the switch
2. Switch learns the sender's MAC address and port
3. If switch knows the destination MAC — it forwards directly
4. If switch does not know the destination MAC — it floods to everyone
5. Once destination responds, switch learns that MAC too and forwards from then on

## Quick Reference
| Term | Definition |
|------|-----------|
| Switching | Moving data within a network |
| MAC Address Table | Switch's record of which MAC is on which port |
| Learn | Switch saves a new MAC to port mapping |
| Flood | Frame sent to all ports when destination is unknown |
| Forward | Frame sent only to the correct port |
