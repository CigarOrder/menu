# Cigar listings (static site)

This is a minimal static site you can host on GitHub Pages. Edit `data/listings.json` to update the items and prices; commit and push to update the live page.

Quick local preview (requires a simple static server):

```
python -m http.server 8000
# then visit http://localhost:8000
```

Deploy to GitHub Pages (recommended):

1. Create a new GitHub repository (e.g., `cigars`).
2. Initialize and push:

```bash
git init
git add .
git commit -m "initial site"
git branch -M main
git remote add origin https://github.com/<your-username>/<repo>.git
git push -u origin main
```

3. In the repository Settings → Pages, choose the `main` branch (root) as the source and save. The site will be available at `https://<your-username>.github.io/<repo>/`.

If you want, tell me your GitHub username and a repo name and I can generate a ready-to-push repo or give exact commands filled in.
