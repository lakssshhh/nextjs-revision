# Route Handlers

Route Handlers create HTTP API endpoints inside the App Router.

File:

```text
app/api/products/route.ts
```

This is an API endpoint, not a page.

Example:

```ts
export async function GET() {
  return Response.json({ message: "Hello" })
}
```

Other HTTP methods can be exported too:

```ts
export async function POST() {}
export async function PUT() {}
export async function DELETE() {}
```

### Important distinction

- `page.tsx` → UI
- `route.ts` → HTTP endpoint
