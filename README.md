# Among Us Runner

Offline HTML5 runner. Hit **1,000 pts**, find your girlfriend, try not to get ejected.

## Files

- `index.html` — game
- `sw.js` — offline PWA cache
- `manifest.json` — add to home screen

## Local dev

```bash
python -m http.server 8080
```

Open http://localhost:8080

## Deploy (Vercel + GitHub)

1. Push this repo to GitHub.
2. [vercel.com](https://vercel.com) → **Add New Project** → import repo.
3. Framework: **Other** — no build command needed.
4. Deploy.
