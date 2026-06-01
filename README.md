# Vyzee Pitch Deck — Vercel Deploy

A self-contained slide deck (mobile-optimized). Fonts load from Google Fonts CDN; everything else is local.

## Files
- `index.html` — the deck (renamed from the working file so Vercel serves it at `/`)
- `deck-stage.js` — slide engine
- `vercel.json` — clean URLs + no-cache headers

## Deploy (drag & drop)
1. Go to **vercel.com/new**.
2. Drag this whole `vercel-deploy` folder onto the page (or zip it and drop the zip).
3. No build step, no framework — Vercel serves it as a static site. Click **Deploy**.

Your live URL appears in seconds. Re-drag the folder to update.

## Local preview
Open `index.html` directly, or run any static server:
```
npx serve .
```
