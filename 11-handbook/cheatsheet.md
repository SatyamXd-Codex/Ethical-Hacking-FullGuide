# Ethical Hacking Cheat Sheet 🧰

## 🟩 Recon Box
```bash
whois example.com  # Shows domain registration details.
dig example.com  # Retrieves DNS records.
nmap -sV 192.168.1.10  # Scans open ports and service versions.
```

## 🟦 Web Box
```bash
sqlmap -u "http://lab/?id=1" --dbs  # Tests URL parameter for SQLi and lists databases.
ffuf -u http://lab/FUZZ -w common.txt  # Brute-forces web paths using a wordlist.
```

## 🟨 System Box
```bash
sudo -l  # Lists allowed sudo commands for current user.
find / -perm -4000 2>/dev/null  # Finds SUID binaries for privesc checks.
```

## 🟥 Forensics Box
```bash
last -a  # Shows recent login sessions.
ps aux  # Shows running processes and owners.
```

## Memory Hack 🧠
**R.W.S.F** = Recon, Web, System, Forensics.
