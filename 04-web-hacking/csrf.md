# CSRF 🧷

CSRF tricks a logged-in user into sending an unwanted request.

## Analogy
It is like someone forcing your hand to sign a form while you are already logged in.

## Basic Defense Checklist
- CSRF token
- SameSite cookies
- Re-auth for sensitive actions

## Quick Win 🎯
In a test app, check if password-change form has CSRF token.

## Memory Hack 🧠
**T.C.R** = Token, Cookie flags, Re-check identity.
