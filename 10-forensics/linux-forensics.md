# Linux Forensics Basics 🧾🐧

Forensics means investigating what happened.

## Log Locations

| File | Purpose |
|---|---|
| `/var/log/auth.log` | Login and auth events |
| `/var/log/syslog` | General system events |
| `/var/log/kern.log` | Kernel events |

## Useful Commands

```bash
last -a  # Shows login history with host details.
sudo grep "Failed password" /var/log/auth.log  # Finds failed SSH/login attempts.
ps aux --sort=-%cpu | head  # Shows top CPU-consuming processes.
```

## Quick Win 🎯
Count failed login events from your test VM logs.

## Memory Hack 🧠
**L.P.L** = Log, Process, Login history.
