# Vinted Ireland Finder — experimental MVP

A free, mobile-friendly **connectivity test** for Vinted catalogue search, intended for iPhone Chrome and GitHub Pages.

## What works
- Search field, country checkboxes (Ireland, Poland, unknown), and persistent preferences.
- Direct, read-only test of a Vinted catalogue endpoint from the browser.
- If the endpoint returns compatible JSON and permits cross-origin access, clickable listing cards and basic country filtering.
- Open the same search on Vinted in a new tab if direct requests fail.

## What is not yet proven
- **Live Vinted search is not verified**. GitHub Pages is static and cannot bypass Vinted's cross-origin (CORS) restrictions.
- Country filtering depends on seller-country data being included in results. Unknown sellers are shown by default.
- No background backend, proxy, scheduled scraping, or paid API is included.
- The page is a test build, not a functioning replacement for Vinted until live data access is verified.

## Publish for free using GitHub Pages
1. Create a **public** repository named `vinted-ireland-finder`.
2. Upload `index.html` to the repository root (and optionally this README).
3. Open **Settings → Pages → Build and deployment**.
4. Select **Deploy from a branch**, branch **main**, folder **/(root)**, then Save.
5. After deployment, open `https://YOUR-USERNAME.github.io/vinted-ireland-finder/` in Chrome on iPhone.

This project is not affiliated with Vinted. Do not enter Vinted credentials into the prototype.
