# App Router & File-Based Routing

Next.js App Router uses the `app/` directory.

## Core files

- `app/page.tsx` → page for `/`
- `app/about/page.tsx` → page for `/about`
- `app/layout.tsx` → shared layout
- `route.ts` → HTTP Route Handler, not a UI page

## Key idea

The folder structure defines the URL structure.

```text
app/
├── page.tsx
├── about/
│   └── page.tsx
└── products/
    └── page.tsx
```

URLs:

- `/`
- `/about`
- `/products`
