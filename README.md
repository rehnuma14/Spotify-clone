# c15 (Sigma project)

A small static site built with `index.html`, `style.css`, and the `assets/` folder.

## What I added
- `README.md` — this file with instructions to push and publish.

## Push to GitHub (two options)

Option A — using GitHub CLI (`gh`) (recommended if installed and logged in):

1. Create and push the repo from the project root:

```powershell
gh repo create YOUR_USERNAME/REPO_NAME --public --source=. --remote=origin --push
```

2. Enable GitHub Pages (deploy site):

```powershell
gh pages setup --source main
```

Option B — manual (no `gh`):

1. Initialize local repo (if not already):

```powershell
# Run these in PowerShell in the project root
git init
git add .
git commit -m "Initial commit"
```

2. Create a repository on GitHub via the website (https://github.com/new) and note the repository HTTPS URL.

3. Add the remote and push:

```powershell
git remote add origin https://github.com/YOUR_USERNAME/REPO_NAME.git
git branch -M main
git push -u origin main
```

4. Enable GitHub Pages in the repository settings: Settings → Pages → Build and deployment → Deploy from a branch → choose `main` and `/ (root)`.

## Live link
After enabling Pages the live URL will be:

```
https://YOUR_USERNAME.github.io/REPO_NAME
```

Replace `YOUR_USERNAME` and `REPO_NAME` with your GitHub username and the repo name you choose.

---
If you want, I can run the git commands for you now — tell me:

- the GitHub repository name you want (e.g. `c15`),
- your GitHub username (or the full repo URL), and
- whether you have the `gh` CLI available and logged-in (I can detect and use it if you allow me to run commands).

If you prefer to do it yourself, follow the steps above.
