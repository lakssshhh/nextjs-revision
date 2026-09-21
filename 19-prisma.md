# Prisma & Database Access

Direct Prisma/database access should normally happen on the **server**.

Typical architecture:

```text
Browser
   ↓
Next.js Server Component / Server Action
   ↓
Prisma
   ↓
PostgreSQL
```

Do not put direct Prisma access in a Client Component.

Why?

- database credentials stay server-side
- database logic stays away from browser JavaScript
- server-side code can safely communicate with the database

### Quick rule

**Prisma → server-side code.**
