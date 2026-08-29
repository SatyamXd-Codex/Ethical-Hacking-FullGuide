# Subdomain Enumeration 🧭

Subdomains can reveal hidden apps like `dev`, `staging`, or `admin`.

## Tools

```bash
sublist3r -d example.com  # Finds subdomains from public sources.
amass enum -passive -d example.com  # Passively discovers subdomains.
```

## Workflow

```text
Target Domain -> Gather Public Data -> Validate Alive Hosts -> Document Findings
```

## Quick Win 🎯
Try passive scan only first. It is safer and quieter.

## Memory Hack 🧠
**S.V.D** = Search, Verify, Document.
