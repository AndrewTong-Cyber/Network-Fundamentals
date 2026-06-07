# OSI Model - Part 2

## Layer 4 - Transport (Service to Service)
- Ensures the right data reaches the right program
- Uses ports to tell programs apart

## TCP vs UDP
| Protocol | Favors |
|----------|--------|
| TCP | Reliability |
| UDP | Efficiency |

## Ports
- Servers listen on pre-defined ports
- Clients pick a random port for each connection

## Encapsulation (Sending)
| Layer | Result |
|-------|--------|
| Layer 4 + Data | Segment |
| Layer 3 + Data | Packet |
| Layer 2 + Data | Frame |

## De-Encapsulation (Receiving)
- Opposite of Encapsulation
- Each layer strips off its own header on the way up

## Quick Reference
| Term | Definition |
|------|-----------|
| TCP | Reliable, slower |
| UDP | Fast, less reliable |
| Port | Identifies which program gets the data |
| Segment | Layer 4 data unit |
| Packet | Layer 3 data unit |
| Frame | Layer 2 data unit |
