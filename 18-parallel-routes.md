# Parallel Routes

Parallel Routes let a layout render multiple route slots simultaneously.

Slots are named with `@`.

Example:

```text
app/dashboard/
├── layout.tsx
├── @analytics/
└── @team/
```

`@analytics` and `@team` are slots.

### Important

The `@slot` name is not a normal URL segment.

Parallel Routes are useful for complex dashboards and independently rendered sections.
