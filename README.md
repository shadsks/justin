# Vyzee — Pitch for Justin

Static deck. 14 slides + custom premium nav. No build step.

## Deploy to Vercel

**Option A — drag & drop (fastest)**
1. Go to https://vercel.com/new
2. Drag this whole `vercel-deploy` folder onto the page.
3. Deploy. Done — Vercel serves `index.html` at the root.

**Option B — Vercel CLI**
```bash
cd vercel-deploy
npx vercel        # preview deploy
npx vercel --prod # production deploy
```

**Option C — Git**
Push this folder to a GitHub repo, then "Import Project" on Vercel.
Framework preset: **Other**. Build command: none. Output dir: `.`

## Files
- `index.html` — the deck
- `deck-stage.js` — slide engine (keyboard arrows, thumbnail rail, print)
- `vercel.json` — static config

## Controls
- Arrow keys ← → or the bottom nav buttons
- Fonts load from Google Fonts CDN (needs internet on first view)
