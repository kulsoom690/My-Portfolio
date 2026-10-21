# Kulsoom Bano Portfolio

Static portfolio site built with HTML, CSS, and JavaScript. The main page loads public repositories from the GitHub API.

## Run locally

From this folder, run:

```powershell
python -m http.server 8000
```

Open `http://localhost:8000`.

## Publish with GitHub Pages

1. Create a GitHub repository for the portfolio.
2. Copy the **contents of this folder** into the repository root (including `.github` and `.nojekyll`).
3. Push the files to the `main` branch.
4. In the repository, open **Settings → Pages** and confirm that GitHub Actions is selected as the build and deployment source.
5. The included workflow deploys the portfolio on each push to `main`. It stages only the personalized page, its required icon font assets, the portrait photos, and the CV; the unused template demo pages are not published.

The hero portrait gently crossfades between transparent-background cutouts of your photos, pauses automatically when the page is hidden, and has pause/next controls. Visitors with reduced motion enabled can still change photos manually.

The page uses a lightweight, locally rendered star field, subtle galaxy-colored gradients, scroll-triggered section reveals, and hover/focus details. Star animation and section motion are reduced for visitors who request reduced motion.

The GitHub repository section and Google Fonts require an internet connection. The contact links and CV download work without a backend.
