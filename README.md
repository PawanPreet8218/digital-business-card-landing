# Digital Business Card Landing Page

Static landing page for GitHub Pages.

## First deployment

Requirements: Git installed, write access to `PawanPreet8218/digital-business-card-landing`, and GitHub authentication configured.

```powershell
cd "c:\Users\HP\Downloads\landing-page (5)"
git init
git branch -M main
git remote add origin https://github.com/PawanPreet8218/digital-business-card-landing.git
git add index.html README.md
git commit -m "Deploy landing page"
git push -u origin main
```

Then open the repository on GitHub:

1. Go to **Settings > Pages**.
2. Under **Build and deployment**, choose **Deploy from a branch**.
3. Select branch **main** and folder **/ (root)**, then click **Save**.
4. Wait for the Pages workflow to finish. The site URL will be shown in **Settings > Pages**.

## Redeploy after changes

```powershell
cd "c:\Users\HP\Downloads\landing-page (5)"
git add index.html README.md
git commit -m "Update landing page"
git push
```

GitHub Pages automatically rebuilds the site after each push to `main`. If there are no changes to commit, edit the page first or use `git status` to inspect the current state.
