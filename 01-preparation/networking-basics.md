# Networking Basics 🌐

Think of a network like a city map. Devices are houses. Ports are doors.

## OSI Model (Simple)

| Layer | Real-Life Analogy |
|---|---|
| Application | You write a letter ✉️ |
| Transport | Post office picks speed (fast/normal) |
| Network | Street address routing |
| Data Link | Apartment floor and room |
| Physical | Road and cables |

## Useful Commands

```bash
ip a  # Shows your device IP addresses.
ping 8.8.8.8  # Tests if internet path is reachable.
traceroute 8.8.8.8  # Shows route hops to destination.
ss -tuln  # Lists listening TCP/UDP ports.
```

## ASCII Flow

```text
Laptop --> Router --> ISP --> Internet --> Server
```

## Quick Win 🎯
```bash
ss -tuln  # See which services are open on your own machine.
```

## Memory Hack 🧠
**IP = Internet Postal address.** Ports = door numbers.
