# My Website (GitHub Pages)

This is a minimal, responsive starter for a personal website hosted on GitHub Pages.

## Customize

- Update the site title, tagline, links, and email in `index.html`.
- Replace `USERNAME` and `REPO` placeholders with your actual GitHub info.
- Tweak colors and spacing in `assets/css/styles.css`.

## Deploy to GitHub Pages

1) Create a new GitHub repository (e.g. `my-website`).

2) Initialize git locally in this folder and make an initial commit:

```bash
git init
git add .
git commit -m "Initial site: GitHub Pages starter"
```

3) Add the remote and push (replace `USERNAME` and `REPO`):

```bash
git remote add origin https://github.com/USERNAME/REPO.git
git branch -M main
git push -u origin main
```

4) Enable GitHub Pages:

- Go to your repo → Settings → Pages
- Source: "Deploy from a branch"
- Branch: `main` and folder `/ (root)`
- Save. GitHub will publish shortly.

5) Visit your site:

- `https://USERNAME.github.io/REPO`

## Optional: Custom domain

1) In your repo, go to Settings → Pages → Custom domain and enter `yourdomain.com`.
2) In your DNS, add a CNAME record from `yourdomain.com` to `USERNAME.github.io`.
3) Add a file named `CNAME` at the repository root with your domain:

```
yourdomain.com
```

GitHub will provision HTTPS automatically after DNS propagates.

## Notes

- A `404.html` is included for friendly not-found pages.
- This site is static and does not require Jekyll or any build step.
- If you ever add folders starting with `_`, consider adding a `.nojekyll` file to bypass Jekyll processing.

