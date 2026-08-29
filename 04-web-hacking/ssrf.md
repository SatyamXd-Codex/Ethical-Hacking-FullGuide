# SSRF (Server-Side Request Forgery) 🌊

SSRF makes a server request attacker-chosen URLs.

## ASCII Diagram

```text
Attacker -> Web App (fetch URL feature) -> Internal Service (127.0.0.1/admin)
```

## Test URL Examples (labs)

```bash
http://127.0.0.1:80  # Tests access to localhost from server-side request feature.
http://169.254.169.254/latest/meta-data/  # Tests cloud metadata access in vulnerable environments.
```

## Quick Win 🎯
Use PortSwigger SSRF labs to test localhost blocking.

## Memory Hack 🧠
**U.R.L** = User URL -> Request by server -> Leak risk.
