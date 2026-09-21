# Navigation Hooks

These hooks come from `next/navigation`.

## useRouter

Programmatic navigation.

```tsx
const router = useRouter()
router.push("/dashboard")
```

## usePathname

Gets the current pathname.

For:

`/dashboard/settings`

it returns:

`/dashboard/settings`

## useSearchParams

Reads query parameters.

For:

`/products?category=shoes&page=2`

```tsx
searchParams.get("category")
```

returns:

`"shoes"`

These hooks are Client Component APIs.
