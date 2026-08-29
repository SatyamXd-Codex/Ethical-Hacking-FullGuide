# Virtual Lab Setup (Kali + VirtualBox) 🧪

Build a safe place to practice.

## Steps

1. Install VirtualBox.
2. Download Kali Linux ISO.
3. Create VM: 4GB RAM, 2 CPU, 40GB disk.
4. Boot ISO and install Kali.

## “Screenshot in Text” Walkthrough 🖼️

```text
[VirtualBox Manager]
  -> New
     Name: Kali-Lab
     Type: Linux
     Version: Debian (64-bit)
```

```text
[Storage Settings]
  -> Controller: IDE
     Empty -> Choose Kali ISO
```

```text
[Network]
  Adapter 1: NAT (internet)
  Adapter 2: Host-only (private lab)
```

## Useful Commands After Install

```bash
sudo apt update  # Refreshes package list from repositories.
sudo apt upgrade -y  # Installs latest security and bug fixes.
```

## Quick Win 🎯
Take a VM snapshot named `clean-start` before testing tools.

## Memory Hack 🧠
**I.S.O. = Install, Snapshot, Observe.**
