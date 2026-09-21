# Metadata & next/image

## generateMetadata

Use `generateMetadata()` when metadata needs to be generated dynamically.

Typical metadata:

- title
- description
- Open Graph information

## Image

Use `Image` from `next/image`.

It provides built-in image optimization features such as appropriate sizing and lazy loading behavior.

```tsx
import Image from "next/image"

<Image
  src="/profile.png"
  alt="Profile"
  width={200}
  height={200}
/>
```
