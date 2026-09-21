# Data Fetching

Server Components can fetch data on the server.

Example:

```tsx
const res = await fetch("https://api.example.com/products")
const products = await res.json()
```

Server-side data fetching is useful because sensitive logic and credentials can remain on the server.

For database-backed applications, a Server Component or server-side function can call the database layer directly.
