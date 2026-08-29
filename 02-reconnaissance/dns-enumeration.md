# DNS Enumeration 🌍

DNS converts domain names to IP addresses.

## Core Commands

```bash
dig example.com  # Shows DNS records for a domain.
nslookup example.com  # Queries DNS in a simple format.
dnsrecon -d example.com  # Performs automated DNS recon on target domain.
```

## ASCII Diagram

```text
Browser -> DNS Resolver -> Authoritative DNS -> IP Returned
```

## Quick Win 🎯
Run `dig` on a domain you own and inspect A, MX, and NS records.

## Memory Hack 🧠
**A-MX-NS** = Address, Mail, Name Server.
