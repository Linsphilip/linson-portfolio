# Linson Philip — Professional Portfolio

Static portfolio website prepared for GitHub Pages or any static hosting provider.

## What is included

- `index.html` — complete single-page portfolio
- `assets/css/style.css` — responsive styling
- `assets/js/main.js` — mobile navigation and footer year
- `assets/images/profile.jpg` — web-optimised profile image with EXIF/GPS metadata removed
- `assets/documents/Linson_Philip_CV_EN.pdf` — English CV
- `assets/documents/Linson_Philip_CV_DE.pdf` — German CV
- `assets/documents/*.tex` — LaTeX sources for both CV versions
- `.nojekyll` — prevents GitHub Pages from applying Jekyll processing

## Local preview

The site can be opened directly by double-clicking `index.html`, but a local HTTP server is better for testing:

```bash
python -m http.server 8000
```

Then open `http://localhost:8000`.

## Publish with GitHub Pages — existing repository

1. Back up the current repository.
2. Copy the contents of this folder into the repository root. Do not copy the outer folder itself unless you want the site in a subdirectory.
3. Remove obsolete generated MkDocs content such as the old `site/` directory if it is still in the repository.
4. Commit and push:

```bash
git add .
git commit -m "Update professional engineering portfolio"
git push origin main
```

5. In GitHub, open the repository and go to **Settings → Pages**.
6. Under **Build and deployment**, select **Deploy from a branch**.
7. Select branch **main** and folder **/(root)**, then save.
8. GitHub will display the published URL after deployment.

If the repository is named `linsphilip.github.io`, the site URL will normally be:

`https://linsphilip.github.io/`

If the repository has another name, for example `portfolio`, the site will normally be:

`https://linsphilip.github.io/portfolio/`

Because all asset links in this version are relative, both setups work.

## Publish with GitHub Desktop

1. Open the existing portfolio repository in GitHub Desktop.
2. Use **Repository → Show in Explorer/Finder**.
3. Replace the old website files with the contents of this folder.
4. Return to GitHub Desktop and review the changes.
5. Enter a summary such as `Update professional portfolio`.
6. Click **Commit to main** and then **Push origin**.
7. Enable GitHub Pages using the Settings steps above.

## Before going public

- Open every CV button and external link.
- Test the website at desktop and mobile widths.
- Confirm dates and language levels.
- Confirm that all publicly stated project information is permitted to be shared.
- If you later add screenshots or plots from research projects, anonymise device/customer identifiers and avoid internal network information.
- Replace the social preview image later with a dedicated 1200×630 image if desired.

## Optional custom domain

If you later buy a domain, configure it under **Settings → Pages → Custom domain** and add the DNS records provided by GitHub. Do not add a `CNAME` file until the actual domain is known.
