# XXE (XML External Entity) 🧬

XXE happens when XML parser resolves external entities unsafely.

## Lab Payload

```bash
<!DOCTYPE x [ <!ENTITY test SYSTEM "file:///etc/passwd"> ]>  # Defines an external entity that reads a local file in vulnerable XML parsers.
```

## Defense
- Disable external entities
- Use secure parser settings

## Quick Win 🎯
In XXE lab, test if parser blocks external entities by default.

## Memory Hack 🧠
**X.E** = XML + External entity.
