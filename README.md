# Klyra 🎰

Casino lobby template — Vite, React, Tailwind. Frontend only: no backend, no real money.

Narrow icon rail, sticky discovery bar, ⌘K search, square game tiles with favorites, flat hero. Casino only — not sports betting, not Velora (02).

## Run 🚀

```bash
npm install
npm run dev
```

→ http://localhost:4011

## Scripts 🛠️

| Command | What it does |
| --- | --- |
| `npm run dev` | Dev server on **4011** |
| `npm run build` | Production build → `dist/` |
| `npm run preview` | Preview the build |
| `npm run typecheck` | TypeScript check |
| `npm run lint` | Oxlint |

## GitHub Pages 📄

```bash
# PowerShell
$env:BASE_PATH="/YOUR-REPO"; npm run build

# bash
BASE_PATH=/YOUR-REPO npm run build
```

Publish the contents of `dist/` (add `.nojekyll` if you need it).
