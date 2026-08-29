# Python Basics for Hacking 🐍

Python helps you automate small tasks.

## Hello Script

```python
print("Hello, Security World!")  # Prints text to screen.
```

## Line-by-Line Port Check Script

```python
import socket  # Loads networking features.

target = "127.0.0.1"  # Local machine.
ports = [22, 80, 443]  # Ports to test.

for port in ports:  # Loop through each port.
    s = socket.socket()  # Create a TCP socket.
    s.settimeout(1)  # Wait max 1 second.
    result = s.connect_ex((target, port))  # 0 means open.
    if result == 0:  # Check if open.
        print(f"Port {port} is open")  # Show open port.
    else:
        print(f"Port {port} is closed")  # Show closed port.
    s.close()  # Close socket.
```

Run it:
```bash
python3 port_check.py  # Executes your script with Python 3.
```

## Quick Win 🎯
Change `ports` list and scan your own lab VM.

## Memory Hack 🧠
**I.L.L.C** = **I**mport, **L**ist, **L**oop, **C**heck.
