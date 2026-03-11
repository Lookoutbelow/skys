# Skys

GitHub Pages-ready static site clone.

## Publish to GitHub Pages

1. Create a GitHub repository.
2. Copy the contents of this folder into that repository.
3. Commit and push:

```bash
git add .
git commit -m "Add Skys site"
git push origin main
```

4. In GitHub, open `Settings -> Pages`.
5. Under `Build and deployment`, choose:
   - `Source`: `Deploy from a branch`
   - `Branch`: `main`
   - `Folder`: `/ (root)`

Your site will then be available at:

- `https://YOUR-USERNAME.github.io/YOUR-REPO/`

## Local preview

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000/`.
