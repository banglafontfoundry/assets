# assets.banglafontfoundry.com — landing page

This repository hosts static assets for Bangla Font Foundry. The root includes a small landing page for the assets domain which links back to the main site.

Files added:
- `index.html` — simple landing page that shows a button to visit the main site and auto-redirects after 10s.
- `styles.css` — styles used by the landing page.
- `CNAME` — the custom domain `assets.banglafontfoundry.com`.

Deployment (GitHub Pages):
1. Commit these files to the branch you use for GitHub Pages (commonly `main` or `gh-pages`).
2. In the repository Settings → Pages, set the Source to the branch and root (or `/docs` if you prefer).
3. Ensure `CNAME` is present at the repository root so GitHub Pages picks up the custom domain.
4. Wait for the DNS to propagate (if you already have DNS configured) and for Pages to finish building.

Optional:
- Remove or adjust the meta refresh line in `index.html` if you prefer no automatic redirect or a different timeout.
- Replace the repository link in the page with any other link you want to show.

If you want, I can:
- Open a branch and push these files.
- Create a pull request against a specific branch.
- Adjust styling or remove the automatic redirect.
Tell me which action you'd like and the target branch.
