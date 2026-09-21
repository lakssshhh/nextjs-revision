# cookies() and headers()

Next.js provides request APIs from `next/headers`.

## cookies

Use `cookies()` to read or modify cookies in supported server contexts.

In current Next.js usage:

```tsx
const cookieStore = await cookies()
```

## headers

Use `headers()` to access request headers.

```tsx
const requestHeaders = await headers()
```

These APIs are server-side request APIs.
