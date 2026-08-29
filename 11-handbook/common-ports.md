# Common Ports and Services 🚪

| Port | Service | Why It Matters |
|---|---|---|
| 21 | FTP | File transfer, often weak auth |
| 22 | SSH | Remote admin access |
| 23 | Telnet | Insecure remote access |
| 25 | SMTP | Email server exposure |
| 53 | DNS | Domain resolution target |
| 80 | HTTP | Web apps and APIs |
| 110 | POP3 | Email retrieval |
| 139/445 | SMB | Windows file sharing attacks |
| 143 | IMAP | Email access |
| 443 | HTTPS | Encrypted web traffic |
| 3306 | MySQL | Database exposure |
| 3389 | RDP | Windows remote desktop |
| 8080 | HTTP-alt | Dev/admin web panels |

## Quick Win 🎯
Run `nmap` on your lab VM and match found ports to this table.

## Memory Hack 🧠
**22-80-443** are the “daily trio”: SSH, web, secure web.
