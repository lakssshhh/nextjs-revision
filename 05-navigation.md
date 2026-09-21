# Navigation

## Link

Use `Link` from `next/link` for normal navigation.

```tsx
import Link from "next/link"

<Link href="/dashboard">Dashboard</Link>
```

## Programmatic navigation

Use `useRouter` from `next/navigation` inside Client Components.

Common methods:

- `router.push("/dashboard")`
- `router.replace("/dashboard")`
- `router.back()`
- `router.refresh()`

### Rule

Normal clickable navigation → `Link`

JavaScript-controlled navigation → `useRouter`
