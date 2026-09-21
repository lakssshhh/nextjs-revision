# Layouts

A `layout.tsx` wraps pages and persists while navigating between routes in that layout.

## Root layout

`app/layout.tsx` is the root layout and is required in the App Router.

## Nested layout

`app/dashboard/layout.tsx` applies to dashboard pages such as:

- `/dashboard`
- `/dashboard/settings`
- `/dashboard/profile`

Example:

```tsx
export default function DashboardLayout({ children }) {
  return <div><nav>Dashboard</nav>{children}</div>
}
```

Think: **layout = shared UI around multiple pages**.
