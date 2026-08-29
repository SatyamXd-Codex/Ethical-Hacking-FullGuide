# Terminal Tools: curl, wget, netcat 🛠️

These are small but powerful tools.

## curl

```bash
curl -I https://example.com  # Fetches only HTTP headers from a website.
```

## wget

```bash
wget https://example.com/file.txt  # Downloads a file from a URL.
```

## netcat

```bash
nc -lvnp 9001  # Starts a listener on port 9001.
nc 127.0.0.1 9001  # Connects to port 9001 on local machine.
```

## Comparison Table

| Tool | Best Use |
|---|---|
| curl | API testing and headers |
| wget | Downloading files |
| netcat | Raw TCP/UDP testing |

## Quick Win 🎯
Try:
```bash
curl https://ifconfig.me  # Shows your public IP from a web service.
```

## Memory Hack 🧠
**C-W-N** = **C**heck (`curl`), **W**rite/download (`wget`), **N**etwork socket (`nc`).
