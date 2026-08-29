# Password Cracking Basics 🔐

Use only hashes/passwords you own or have permission to test.

## Hydra (Online Login Testing)

```bash
hydra -l admin -P rockyou.txt ssh://192.168.1.10  # Tries passwords from list for SSH login user admin.
```

## Hashcat (Offline Hash Testing)

```bash
hashcat -m 0 -a 0 hashes.txt rockyou.txt  # Cracks MD5 hashes using straight wordlist mode.
```

## Quick Win 🎯
Generate a test hash of your own password and crack it locally.

## Memory Hack 🧠
**O.O** = Online (Hydra), Offline (Hashcat).
