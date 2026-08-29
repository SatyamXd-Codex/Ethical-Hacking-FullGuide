# Directory Bruteforcing 📁

Web servers may hide folders not linked in pages.

## gobuster

```bash
gobuster dir -u http://example.com -w /usr/share/wordlists/dirb/common.txt  # Tries common folder names on target site.
```

## ffuf

```bash
ffuf -u http://example.com/FUZZ -w /usr/share/wordlists/dirb/common.txt  # Replaces FUZZ with each wordlist entry.
```

## Quick Win 🎯
Run against your own local test app only.

## Memory Hack 🧠
**W.U.R.D** = Wordlist, URL, Results, Document.
