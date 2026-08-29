# Ethical Hacking Full Guide 🎯

Welcome! This repo teaches ethical hacking from zero. No coding background needed. 📚

> ⚠️ Learn only on systems you own or have written permission to test.

## 🚀 Hacker Roadmap (ASCII Animation Style)

```text
[Level 0] Curious Beginner 🐣
      |
      v
+------------------+
| 01 Preparation   |  🐧 Linux + 🌐 Networking + 🐍 Python
+------------------+
      |
      v
+------------------+
| 02 Recon         |  🔎 OSINT + DNS + Subdomains + Ports
+------------------+
      |
      v
+------------------+
| 03 Assess        |  🧪 Scan for weak points
+------------------+
      |
      v
+------------------+
| 04 Web Hacking   |  🕸️ OWASP + SQLi + XSS + more
+------------------+
      |
      v
+------------------+
| 05-10 Advanced   |  📡 Network, 💻 System, ⚔️ Exploit,
|                  |  📱 Mobile, 🐞 Bug Bounty, 🧾 Forensics
+------------------+
      |
      v
[Level Pro] Responsible Security Tester 🛡️
```

## 🧭 Easy Navigation

| Step | Topic | Link |
|---|---|---|
| 1 | Preparation | [`01-preparation/`](./01-preparation/) |
| 2 | Reconnaissance | [`02-reconnaissance/`](./02-reconnaissance/) |
| 3 | Vulnerability Assessment | [`03-vulnerability-assessment/`](./03-vulnerability-assessment/) |
| 4 | Web Hacking | [`04-web-hacking/`](./04-web-hacking/) |
| 5 | Network Hacking | [`05-network-hacking/`](./05-network-hacking/) |
| 6 | System Hacking | [`06-system-hacking/`](./06-system-hacking/) |
| 7 | Exploitation | [`07-exploitation/`](./07-exploitation/) |
| 8 | Mobile Hacking | [`08-mobile-hacking/`](./08-mobile-hacking/) |
| 9 | Bug Bounty | [`09-bug-bounty/`](./09-bug-bounty/) |
| 10 | Forensics | [`10-forensics/`](./10-forensics/) |
| 11 | Handbook | [`11-handbook/`](./11-handbook/) |

## 🔁 How a Reverse Shell Works (ASCII Flowchart)

```text
Attacker Machine          Victim Machine
+----------------+        +----------------+
| nc -lvnp 4444  | <----  | bash -> /dev/tcp|
+----------------+        +----------------+
       ^                          |
       |------ command output ----|
```

## 🎨 Before vs After Security Example

| Scenario | Before (Vulnerable) ❌ | After (Safer) ✅ |
|---|---|---|
| SQL Query | String concat with user input | Prepared statements |
| File Upload | No extension check | Allowlist + size check |
| Auth | No MFA | MFA + strong passwords |

## 🧰 Emoji Cheat Boxes

- 🐧 **Linux:** `ls`, `cd`, `chmod`
- 🌐 **Network:** `ip a`, `ping`, `netstat`
- 🔎 **Recon:** `nmap`, `whois`, `dig`
- 🛠️ **Web Testing:** Burp Suite, `sqlmap`, browser dev tools
- 🧾 **Forensics:** logs, hashes, timelines

## ✅ Learning Rules

1. Practice in legal labs only.
2. Take notes after each command.
3. Repeat small steps daily.

## 🏁 Quick Win

Run this on your own machine:

```bash
ip a  # Shows your network interfaces and local IP addresses.
```

## 🧠 Memory Hack

**R.E.C.O.N** = **R**ecord target, **E**numerate info, **C**heck ports, **O**bserve services, **N**ote risks.

## 🤝 Contributing

See [`CONTRIBUTING.md`](./CONTRIBUTING.md).
