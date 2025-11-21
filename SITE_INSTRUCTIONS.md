This repository hosts a minimal personal homepage for Dr. Ahmed Moustafa.

Site layout
- Static site files are under the `public/` directory. The entry page is `public/index.html` and styles are in `public/styles.css`.

Preview locally
- From the repository root run:

```bash
python3 -m http.server --directory public 8000

# Then open http://localhost:8000 in your browser.
```

GitHub Pages deployment
- A GitHub Actions workflow `.github/workflows/deploy-pages.yml` uploads `public/` and deploys it to GitHub Pages whenever you push to `main`.
- After you push, confirm Pages is enabled in the repository Settings → Pages (the workflow creates the Pages build, but you may need to select the Pages source in older repos).

To add content
- Edit files in `public/` (for example `public/index.html`), commit, and push to `main`. The workflow will redeploy the site.

Contact
- The site contains contact links; update `public/index.html` to use your preferred email or social links.
