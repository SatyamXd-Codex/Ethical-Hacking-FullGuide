# Writing a Good PoC Report 📝

A good report is clear, reproducible, and respectful.

## PoC Template

| Section | What to write |
|---|---|
| Title | Short bug summary |
| Steps | Numbered reproduction steps |
| Payload | Exact request/input used |
| Impact | What attacker can do |
| Fix idea | How to reduce risk |

## Example Command Capture

```bash
curl -i "https://target.tld/profile?id=102"  # Sends request that demonstrates unauthorized profile access in test scenario.
```

## Quick Win 🎯
Write one mock PoC from a PortSwigger lab you solved.

## Memory Hack 🧠
**S.P.I.F** = Steps, Payload, Impact, Fix.
