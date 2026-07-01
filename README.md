# Will You Date Me?

A single-page romantic Neobrutalism web app built with plain HTML, CSS, and vanilla JavaScript.

## Files

- `index.html` — the complete app. This is the file GitHub Pages serves by default.
- `assets/photos/` — optimized local photos used in the Neobrutalist photo collage.
- `.nojekyll` — tells GitHub Pages to serve the static files exactly as-is.
- `.github/workflows/pages.yml` — optional GitHub Actions workflow for deploying to GitHub Pages.

## Deploy on GitHub Pages

### Option A: Deploy from the GitHub website

1. Create a new GitHub repository.
2. Upload all files in this folder to the repository root.
3. Go to **Settings → Pages**.
4. Under **Build and deployment**, choose:
   - **Source:** `Deploy from a branch`
   - **Branch:** `main`
   - **Folder:** `/ (root)`
5. Click **Save**.
6. GitHub will publish the app at:

```text
https://YOUR-USERNAME.github.io/YOUR-REPOSITORY-NAME/
```

### Option B: Deploy with GitHub Actions

1. Create a new GitHub repository.
2. Push this folder to the repository.
3. Go to **Settings → Pages**.
4. Under **Build and deployment**, set **Source** to `GitHub Actions`.
5. Push to `main`; the included workflow will deploy the site.

## Push from your computer

From inside this folder:

```bash
git init
git add .
git commit -m "Initial GitHub Pages site"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPOSITORY-NAME.git
git push -u origin main
```

Then enable GitHub Pages using one of the options above.
