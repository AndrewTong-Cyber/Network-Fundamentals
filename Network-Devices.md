# Network Devices

## Hub
- A device that connects multiple hosts together
- When one host sends data, every other host receives a copy
- No intelligence — it cannot filter or direct traffic

## Hub Diagram
<img width="1114" height="463" alt="Hub" src="https://github.com/user-attachments/assets/9a291c54-4993-41b3-9f61-18e2d00fe3b2" />

## Bridge
- Sits between two groups of Hub-connected hosts
- Only has two ports (one per side)
- Learns which hosts are on each side over time
- Keeps local traffic contained to its own side
- Can forward traffic to the other side when necessary

## Bridge Diagram
<img width="1357" height="605" alt="Bridge" src="https://github.com/user-attachments/assets/c81b37b6-046c-4b8f-81af-c913c130331d" />


## Switch
- Connects multiple hosts within the same network
- Smarter than a Hub — sends data only to the intended host
- Essentially a multi-port Bridge

## Network
- A group of hosts that need to communicate with each other
- All hosts on the same network share the same IP address space

## Router
- Connects different networks together
- Gateway is the router's IP address that hosts use to reach other networks

## Switch & Router Diagram
<img width="1357" height="605" alt="Screenshot 2026-06-03 at 4 03 39 PM" src="https://github.com/user-attachments/assets/0d4ade3f-ad07-4bd8-9e77-5423d97a34b8" />
