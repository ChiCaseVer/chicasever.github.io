# ChiCaseVer Static Showcase (GitHub Pages)

This repo hosts the zero-cost static site for **chicasever.com**.

## Quick Deploy
1. Create a public repo named `chicasever.github.io` on GitHub.
2. Upload the contents of this folder (index.html, CNAME).
3. Go to **Settings → Pages**, set the source to `main` branch.
4. In **Custom domain**, enter `chicasever.com` and save.
5. In your DNS provider, add:
   - `A` records for apex: 185.199.108.153 / 185.199.109.153 / 185.199.110.153 / 185.199.111.153
   - `CNAME` for `www` → `chicasever.github.io`

## Editing
- Replace image URLs directly in `index.html`.
- New products: duplicate a card block in the HTML or add rows to your Excel and regenerate.
