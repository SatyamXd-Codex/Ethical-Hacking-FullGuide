# Port Scanning with Nmap 🚪

Ports are like doors on a server. Open doors may expose services.

## Basic Scans

```bash
nmap 192.168.1.10  # Runs a basic scan for common ports.
nmap -sV 192.168.1.10  # Detects service versions on open ports.
nmap -sC 192.168.1.10  # Runs safe default scripts.
nmap -p- 192.168.1.10  # Scans all 65535 ports.
```

## ASCII Scan Idea

```text
Scanner ---> [22 SSH:open] [80 HTTP:open] [443 HTTPS:open] [3306 MySQL:closed]
```

## Quick Win 🎯
Scan your own VM IP with `nmap -sV`.

## Memory Hack 🧠
**C.V.P** = **C**ommon scan, **V**ersion scan, **P**ort-all scan.
