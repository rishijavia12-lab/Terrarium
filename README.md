# Terrarium website

Static site for Terrarium. No build step.

## Pages
- `/` → index.html
- `/support` → support.html  (App Store Connect → Support URL)
- `/privacy` → privacy.html  (App Store Connect → Privacy Policy URL)

## Launch day (when the app is live)
Search the files for `LAUNCH DAY`:
1. Every page's top nav, plus index.html (2 more places): swap each "Coming soon" line for the commented-out `<a>` Download button below it.
2. Every page's `<head>`: uncomment the `apple-itunes-app` tag.
App Store link: https://apps.apple.com/app/id6816771004

## Deploy on GitHub Pages
1. Create a public repo (any name, e.g. `terrarium-app`) and upload everything in this folder to its root.
2. Settings → Pages → Deploy from a branch → `main` / `(root)`.
3. Site: https://YOUR-USERNAME.github.io/terrarium-app/
