# SSTI (Server-Side Template Injection) 🧩

SSTI happens when user input is rendered as template code.

## Detection Payloads (labs)

```bash
{{7*7}}  # If output shows 49, template expression may be executed.
${7*7}  # Alternate syntax for some template engines.
```

## Quick Win 🎯
Identify template engine type from error messages in labs.

## Memory Hack 🧠
**T.E.M.P** = Template Engine Misuse Problem.
