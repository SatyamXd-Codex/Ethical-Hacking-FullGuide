# Linux Privilege Escalation Basics 🐧⬆️

Goal: move from normal user to higher privileges in legal labs.

## Key Checks

```bash
id  # Shows current user and group IDs.
sudo -l  # Lists commands you can run with sudo.
find / -perm -4000 2>/dev/null  # Finds SUID binaries that may allow escalation paths.
uname -a  # Shows kernel version for known vulnerability checks.
```

## Quick Win 🎯
Run these checks in your own vulnerable lab VM and take notes.

## Memory Hack 🧠
**S.U.I.D** = Sudo rights, User groups, Interesting binaries, Detailed kernel.
