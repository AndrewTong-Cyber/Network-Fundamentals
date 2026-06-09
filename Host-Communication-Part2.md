## Host A's First Step When Sending Data
- Always determine if the target IP is on the local or foreign network
- Local = ARP for the target IP directly
- Foreign = ARP for the Default Gateway IP first

## Local vs Foreign
| Target | Action |
|--------|--------|
| Same network | ARP directly for target MAC |
| Different network | ARP for the Gateway MAC first |

## Default Gateway
- The router's IP address on your local network
- Every host uses it as the exit door to reach other networks

## How Headers Are Populated
- L3 (IP) header = always uses the final destination IP
- L2 (MAC) header = changes at every hop along the way

## Quick Reference
| Term | Definition |
|------|-----------|
| Local Network | Same IP address space as your host |
| Foreign Network | Different IP address space, requires a router |
| Default Gateway | Router's IP address used to exit the local network |
| L3 Header | Contains source and destination IP addresses |
| L2 Header | Contains source and destination MAC addresses |
