# Heedwell Care website

One-page site for Heedwell Care Services Limited.

## Deploy on GitHub Pages
1. Create a public repo (e.g. `heedwell-site`) and upload everything in this folder.
2. Settings → Pages → Source: "Deploy from a branch" → `main` / root → Save.
3. Custom domain: enter your domain in Settings → Pages, then at your registrar add:
   - `A` records for `@`: 185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153
   - `CNAME` for `www` → `<your-github-username>.github.io`
4. Tick "Enforce HTTPS" once the certificate is issued.

## Quick edits
- WhatsApp number / message: `WA_NUMBER` and `WA_DEFAULT` near the bottom of `index.html`.
- Facebook / LinkedIn / TikTok: replace each `<span ...>` icon in the footer with `<a href="LINK" target="_blank" rel="noopener">` (same SVG inside).
- Email: uncomment the email line in the Contact section once info@ exists.
