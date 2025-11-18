# App Support Site (GitHub Pages)

## Quick Deploy
1. Create a new repo (public): `app-support` (or any name).
2. Add these files.
3. GitHub → Settings → Pages → Build and deployment →
   - Source: `Deploy from a branch`
   - Branch: `main` / `/ (root)`
4. Wait for the green check → your site goes live at `https://<username>.github.io/<repo>/`.

## Custom Domain (optional)
1. In this repo, edit `CNAME` to your domain like `support.yourdomain.com`.
2. In your DNS, add a CNAME record:
   - Name/Host: `support`
   - Target: `<username>.github.io`
3. Back in GitHub Pages, enable **Enforce HTTPS**.

## What to edit
- In `index.html` replace `{{App}}`, `{{Company}}`, email address, and form URL.
- Add your real Privacy Policy and Terms URLs.
- Optional: replace `favicon.ico` with your own.

## Local edits
No build step is required. It’s static HTML + CSS for maximum speed.
