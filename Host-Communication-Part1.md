## Setup
- Two hosts directly connected
- Each host has a NIC with a MAC address
- Each host has an IP address and Subnet Mask
- Subnet Mask defines the size of the network

## How Host A Sends Data to Host B
- Host A knows Host B's IP address
- IP address is obtained from DNS
- Host A creates a Layer 3 header using the IP address
- Host A does NOT know Host B's MAC address yet

## DNS
- Converts a domain name into an IP address
- Example: google.com → 10.1.1.33

## ARP (Address Resolution Protocol)
- Used when a host knows the IP but needs the MAC
- "I know the IP, but I need the MAC"

## ARP Request
- Host A broadcasts asking "Who has this IP? Tell me your MAC"
- Sent to every device on the network using destination MAC: ffff.ffff.ffff
- ffff.ffff.ffff is a reserved broadcast address meaning "send to everyone"

## ARP Response
- Host B replies directly (Unicast) back to Host A with its MAC address

## ARP Cache
- A local table stored on each host
- Saves IP to MAC mappings so ARP doesn't have to repeat every time
- Think of it like a contacts list — once you learn someone's number you save it

## Quick Reference
| Term | Definition |
|------|-----------|
| ARP | Finds MAC address from a known IP |
| Broadcast | Sent to every device on the network |
| Unicast | Sent directly to one specific device |
| ARP Cache | Saved list of IP to MAC mappings |
| IP Mapping | The pairing of an IP address to its corresponding MAC address |
| DNS | Converts domain names to IP addresses |
