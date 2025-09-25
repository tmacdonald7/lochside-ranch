# Lochside Ranch – Netlify Starter

A minimal, SEO-friendly static site for Lochside Ranch with a Netlify contact form.

## Quick Start
1. Open this folder in VS Code.
2. (Optional) Use the built-in terminal (Git Bash or PowerShell).
3. Initialize git:
   ```bash
   git init
   git add .
   git commit -m "Initial Lochside Ranch site"
   ```
4. Create a GitHub repo and push.
5. In Netlify, choose **New site from Git** → connect the repo → deploy.
6. In Netlify → **Domain settings** → add `lochsideranch.com` and follow DNS prompts.

## Files
- `index.html` – homepage + Netlify form (honeypot enabled)
- `robots.txt`, `sitemap.xml` – SEO essentials
- `netlify.toml` – publish config + headers + redirect
- `assets/favicon.ico` – placeholder

## Next Steps
- Add photos and a logo to `/assets`
- Create additional pages (TRF, Lake Conroe, Dogs & Groups)
- Add JSON-LD per page if needed
- Set up Netlify form notifications/webhooks to your CRM (SWAPP)
