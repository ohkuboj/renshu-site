# Renshu website

Three static pages, no build step:

- `index.html` — landing page
- `privacy.html` — privacy policy (use as the App Store / Google Play privacy policy URL)
- `support.html` — support page (use as the App Store support URL)

## Before going live

1. In `index.html`, replace `APP_STORE_URL` and `GOOGLE_PLAY_URL` (2 of each) with the store listing links.
2. In `privacy.html`, fill in the highlighted `[...]` items and have the team review it.

## Publish on GitHub Pages

1. Create a **public** repo on GitHub, e.g. `renshu-site`.
2. Upload these files to the repo root (Add file → Upload files → Commit).
3. Settings → Pages → Source: "Deploy from a branch", Branch: `main`, folder `/ (root)` → Save.
4. After a minute or two the site is live at `https://ohkuboj.github.io/renshu-site/`.

To add teammates: Settings → Collaborators → add their GitHub usernames.

## Custom domain (optional)

Buy a domain, then in Settings → Pages → Custom domain, enter it and follow GitHub's DNS instructions.
