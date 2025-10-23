# Auto-Deploy Portfolio (GitHub Actions → GitHub Pages)

This is a tiny demo project to practice GitHub Actions and automatic deployments to GitHub Pages.
Push to the `main` branch and the workflow will publish the contents to GitHub Pages automatically.

## Files
- `index.html` — demo homepage
- `styles.css` — simple styling
- `.github/workflows/deploy.yml` — GitHub Actions workflow that deploys to Pages

## Quick start
1. Create a GitHub repo and push this project to `main`.
2. Go to **Settings → Pages** in your repo and make sure **GitHub Actions** is selected as the deployment source.
3. On every push to `main` the workflow will run and publish the site to `https://<username>.github.io/<repo>`
