# Cross-Site Scripting (XSS) ⚡

XSS means attacker JavaScript runs in victim browser.

## Basic Payloads (for labs)

```bash
<script>alert(1)</script>  # Tests if input is reflected and executed as script.
<img src=x onerror=alert(1)>  # Tests event-handler based XSS.
```

## Types
- Reflected
- Stored
- DOM-based

## Quick Win 🎯
Use PortSwigger XSS labs and identify reflected vs stored.

## Memory Hack 🧠
**R.S.D** = Reflected, Stored, DOM.
