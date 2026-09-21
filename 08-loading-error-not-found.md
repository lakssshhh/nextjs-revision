# loading.tsx, error.tsx, not-found.tsx

Next.js provides special files for route states.

## loading.tsx

Shows loading UI while a route segment is loading.

## error.tsx

Provides an error UI for errors in a route segment. Error boundaries require a Client Component.

## not-found.tsx

Provides the UI shown when `notFound()` is called.

Example:

```tsx
import { notFound } from "next/navigation"

if (!product) {
  notFound()
}
```

### Memory

- `loading.tsx` → loading state
- `error.tsx` → error state
- `not-found.tsx` → missing resource
