# Mathematical Foundations of RL & Online Decision Making

Course website for the PhD-level course at Stockholm University, taught by Sindri Magnússon.

## Deploying to GitHub Pages

1. Create a new repository on GitHub (e.g. `rl-course` or `math-rl`)
2. Push this folder's contents to the repo:

```bash
git init
git add .
git commit -m "Initial course site"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPO.git
git push -u origin main
```

3. Go to **Settings → Pages** in your GitHub repo
4. Under **Source**, select `main` branch and `/ (root)` folder
5. Click **Save** — your site will be live at `https://YOUR-USERNAME.github.io/YOUR-REPO/`

## Files

- `index.html` — the complete single-page course website (self-contained, no build step needed)
- `_config.yml` — tells GitHub Pages not to apply a Jekyll theme
- `README.md` — this file
