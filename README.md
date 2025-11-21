# ahmed-moustafa-homepage

This repository hosts a minimal personal homepage for Dr. Ahmed Moustafa.

How to edit the homepage
- The site sources live under the `public/` directory. Edit `public/index.html` to change content and `public/styles.css` to change styling.
- Recommended workflow (safe):
	- Create a feature branch, make edits, open a Pull Request, then merge after review.
	- Example commands:

```bash
# create a branch, make edits, and push
git checkout -b feat/update-homepage
# edit files (public/index.html, public/styles.css)
git add public/index.html public/styles.css
git commit -m "feat(site): update homepage content"
git push --set-upstream origin feat/update-homepage
```

- If you prefer quick edits, you can update files directly on `main` and push — the site will redeploy automatically, but using branches + PRs is recommended for review.
- You can also edit files via GitHub's web editor (Edit file → Commit) and the workflow will redeploy.

Preview locally
- Run a simple static server from repo root:

```bash
python3 -m http.server --directory public 8000
# then open http://localhost:8000
```

Publishing (GitHub Pages)
- This repo includes a GitHub Actions workflow at `.github/workflows/deploy-pages.yml` that publishes the `public/` directory to GitHub Pages on pushes to `main`.
- After pushing to `main`, Pages build may take a few minutes. Confirm the site in Settings → Pages if you need the exact URL.

Notes
- Do not commit secrets or credentials. If you add integrations that require secrets, list them in the PR and configure them in the repository settings (do not store them in the repo).
- If you want, I can switch to a branch+PR default workflow for future changes and create a template PR for editing the homepage.

Contact
- To update contact info on the site, edit `public/index.html` and replace the email or links as needed.

```
# ahmed-moustafa-homepage