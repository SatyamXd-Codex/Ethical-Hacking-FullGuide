# SQL Injection (SQLi) 💉

SQLi happens when user input changes a database query.

## Test Inputs (Use legal labs only)

```bash
' OR '1'='1  # Common test string to check weak login query handling.
```

## sqlmap Example

```bash
sqlmap -u "http://testphp.vulnweb.com/listproducts.php?cat=1" --dbs  # Tests parameter for SQL injection and lists databases if vulnerable.
```

## Types
- Union-based
- Error-based
- Blind (boolean/time)

## Before vs After

| Before ❌ | After ✅ |
|---|---|
| `"SELECT * FROM users WHERE id=" + input` | Prepared statement with placeholders |

## Quick Win 🎯
Test only in PortSwigger SQLi practice labs.

## Memory Hack 🧠
**N.I.P** = Never trust Input; use Parameters.
