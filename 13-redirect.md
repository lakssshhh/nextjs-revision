# redirect()

Use `redirect()` from `next/navigation` to redirect a request.

```tsx
import { redirect } from "next/navigation"

redirect("/dashboard")
```

This sends the user to `/dashboard`.

Do not confuse it with `router.push()`:

- `redirect()` → server-side redirect API
- `router.push()` → programmatic client navigation
