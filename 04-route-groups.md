# Route Groups

Folders wrapped in parentheses are **route groups**.

Example:

```text
app/
└── (auth)/
    ├── login/
    │   └── page.tsx
    └── signup/
        └── page.tsx
```

The group name does not appear in the URL.

So:

`app/(auth)/login/page.tsx`

maps to:

`/login`

Route groups are useful for organizing routes or applying different layouts without changing the URL.
