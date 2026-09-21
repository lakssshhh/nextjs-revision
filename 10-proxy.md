# Proxy

Modern Next.js uses **Proxy** for request interception.

Typical uses:

- authentication checks
- redirects
- rewrites
- request-based routing logic

Conceptually:

```text
Request → Proxy → Next.js route
```

Older Next.js material may call this feature **Middleware**. When revising current Next.js, remember the modern terminology is Proxy.
