# Command Injection 💣

Command injection happens when user input reaches system shell commands.

## Test Strings (labs only)

```bash
127.0.0.1; id  # If app appends this to ping command, it may run id command.
127.0.0.1 && whoami  # Tests command chaining in vulnerable input handling.
```

## Safer Coding Idea
- Use allowlists
- Avoid shell execution
- Use safe APIs

## Quick Win 🎯
Test a deliberately vulnerable ping form in a local lab.

## Memory Hack 🧠
**A.A.S** = Allowlists, API calls, Sanitize.
