# Vite + React + Type checking

Added `vite-plugin-checker` in [`apps/web/vite.config.ts`](apps/web/vite.config.ts).

```bash
npx nx serve web
```

works.

```bash
npx nx build web
```

fails, due to the TypeScript error in [`apps/web/src/main.tsx`](apps/web/src/main.tsx).

```ts
const value: number = 'sdfads';
```
