# IDOR (Insecure Direct Object Reference) 🛒

IDOR appears when changing IDs gives access to others' data.

## Shopping Cart Example

```text
/cart?user_id=101   (your cart)
/cart?user_id=102   (should be blocked)
```

If server only trusts URL ID, data leak happens.

## Quick Win 🎯
In labs, change numeric IDs and observe access control responses.

## Memory Hack 🧠
**I.D.O.R** = ID in request, Data ownership check Required.
