# veogrowth.com

Managed outbound operations for B2B sales leaders.

## Stack

- Single-file static site. No build step, no framework, no npm dependencies.
- Everything lives in `index.html`: HTML, CSS, JS, inlined SVG logo + favicon, OG meta.
- Fonts loaded from Google Fonts (Fraunces, Instrument Sans, JetBrains Mono).

## Deploy

Any static host works. Recommended: **Vercel** or **Cloudflare Pages** — both free, both auto-deploy on every `git push`.

### Vercel (fastest)

```bash
npm i -g vercel
vercel --prod
```

Or connect the GitHub repo at vercel.com → point `veogrowth.com` DNS at Vercel.

### Cloudflare Pages

1. Cloudflare dashboard → Pages → Connect to Git → pick this repo
2. Build command: *(leave empty)*
3. Output directory: `.`
4. Deploy. Add `veogrowth.com` as a custom domain.

## Before going live — one manual step

Generate a 1200×630 Open Graph image for social link previews:

1. Open `og-cover.html` in a browser
2. Screenshot the dark stage area at exactly 1200×630 (DevTools → right-click the `.cover` node → **Capture node screenshot**)
3. Save as `og-cover.png` at the repo root

The site already references `/og-cover.png` in its OG meta. Upload the image and link previews light up on Slack, LinkedIn, iMessage, etc.

## Files

- `index.html` — the site
- `og-cover.html` — the 1200×630 stage to screenshot for the OG image
- `vercel.json` — deploy config (clean URLs, security headers)
- `robots.txt` — crawler config
- `README.md` — this file

## Editing

Everything is inline in `index.html`. No state to manage, no components, no framework. Find the string, change it, `git push`. Live in under a minute.

## Contact

dmitry@veogrowth.com · book a call: https://calendly.com/veogrowth/discovery
