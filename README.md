# daily-focus-site

Tiny static site for [Daily Focus](https://github.com/AuriDevcourse/daily-focus) — the landing page and privacy policy.

**Live:** https://dailyfocus.auridev.com

## Pages

- `/` → `index.html` (landing)
- `/privacy` → `privacy.html` (required by Chrome Web Store submission)

## Deploy

Static site on Vercel. No build step. `vercel.json` enables `cleanUrls` so `/privacy` works without the `.html` extension.

Push to GitHub master → Vercel auto-deploys.
