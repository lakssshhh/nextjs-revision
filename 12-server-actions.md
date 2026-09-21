# Server Actions

Server Actions are server-side functions that can be invoked from UI interactions such as forms.

A file/function can use:

```tsx
"use server"
```

They are useful when an interaction needs server-side logic without manually creating a separate API endpoint.

### Server Action vs Route Handler

**Server Action**

- server-side function
- commonly invoked by UI/forms
- great for mutations

**Route Handler**

- HTTP endpoint
- explicitly handles HTTP methods
- useful for APIs and external HTTP clients
