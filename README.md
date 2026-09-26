# Portfolio

Static portfolio site — plain HTML/CSS/JS, no build step.

## Before you push

Your photo, resume, email, phone, GitHub, and LinkedIn are already wired in. Two things left, both marked `TODO` in `index.html`:
- Live demo links for AI Finance Manager (and any other project) once it's actually deployed somewhere
- GitHub links currently point at your profile (`github.com/SiddhantBansode`) for every project — swap in each project's own repo URL once they're pushed as separate repos, so visitors land on the right code instead of just your profile

## Push to GitHub

```bash
cd portfolio
git init
git add .
git commit -m "Initial portfolio"
git branch -M main
git remote add origin https://github.com/<your-username>/<repo-name>.git
git push -u origin main
```

## Publish with GitHub Pages

1. On GitHub, open the repo → **Settings → Pages**.
2. Under **Build and deployment**, set **Source** to `Deploy from a branch`, branch `main`, folder `/ (root)`.
3. Save. Your site goes live at `https://<your-username>.github.io/<repo-name>/` within a minute or two.

If you want it at the root of `https://<your-username>.github.io`, name the repo exactly `<your-username>.github.io` instead.
