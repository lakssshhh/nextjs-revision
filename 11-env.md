# Environment Variables

Server-only secrets should not be exposed to browser code.

Example:

```env
API_SECRET=super-secret-value
```

Server-side:

```ts
process.env.API_SECRET
```

## Public variables

Variables prefixed with `NEXT_PUBLIC_` can be exposed to client-side code.

```env
NEXT_PUBLIC_API_URL=https://api.example.com
```

### Golden rule

**Never put secrets in `NEXT_PUBLIC_` variables.**
