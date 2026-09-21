# Server vs Client Components

App Router components are Server Components by default.

## Server Component

Good for:

- database access
- server-side data fetching
- keeping secrets on the server

## Client Component

Add:

```tsx
"use client"
```

Use Client Components when you need browser-side interactivity such as:

- `useState`
- `useEffect`
- click handlers
- browser APIs

### Important

Do not move secrets or direct database access into Client Components.
