# Dynamic & Catch-All Routes

## Dynamic route

`app/users/[id]/page.tsx`

For:

`/users/42`

the dynamic value is:

`id = "42"`

In current Next.js server contexts, `params` may be async:

```tsx
const { id } = await params
```

## Catch-all

`[...slug]` matches one or more segments.

`app/docs/[...slug]/page.tsx`

`/docs/react/hooks` gives:

```js
slug = ["react", "hooks"]
```

## Optional catch-all

`[[...slug]]` matches zero or more segments.

It can match both:

- `/docs`
- `/docs/react/hooks`

### Quick memory

- `[id]` → one segment
- `[...slug]` → one or more
- `[[...slug]]` → zero or more
