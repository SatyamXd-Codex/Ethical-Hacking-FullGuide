# Windows Privilege Escalation Basics 🪟⬆️

Learn common checks in a Windows lab.

## Core Commands

```bash
whoami /priv  # Lists current user privileges.
systeminfo  # Shows OS and patch details.
net user  # Lists local user accounts.
wmic qfe get Caption,Description,HotFixID,InstalledOn  # Lists installed updates/hotfixes.
```

## Quick Win 🎯
Check if any service runs with high privilege but weak file permissions.

## Memory Hack 🧠
**P.A.T.C.H** = Privileges, Accounts, Tasks, Config, Hotfixes.
