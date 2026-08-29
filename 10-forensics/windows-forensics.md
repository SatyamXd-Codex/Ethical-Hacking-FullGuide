# Windows Forensics Basics 🧾🪟

Windows Event Logs store security clues.

## Important Event IDs

| Event ID | Meaning |
|---|---|
| 4624 | Successful login |
| 4625 | Failed login |
| 4688 | New process created |

## PowerShell Commands

```bash
Get-WinEvent -LogName Security -MaxEvents 20  # Shows latest 20 security log events.
Get-WinEvent -FilterHashtable @{LogName='Security'; ID=4625} | Select-Object -First 10  # Lists first 10 failed login events.
```

## Quick Win 🎯
Filter failed logins and map time + username.

## Memory Hack 🧠
**S.I.P** = Security log, ID filter, Process trail.
