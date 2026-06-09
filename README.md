# Atlantic Information Technology Consulting, Inc.

One-page website for AITC, hosted on GitHub Pages at [atlanticit.org](https://atlanticit.org).

## Structure

- `index.html` — Main website page
- `assets/styles.css` — Shared site styles
- `blog/index.html` — Blog listing page
- `Logo_Dark.png` — Company logo
- `CNAME` — Custom domain config for GitHub Pages

## Local Preview

Open `index.html` in any browser.

## Pushing to GitHub

Authenticated via HTTPS using the GitHub CLI:

```bash
brew install gh
gh auth login        # choose HTTPS, authenticate via browser
git remote set-url origin https://github.com/Atlantic-IT/website.git
git push -u origin main
```

## Deployment

The site is served via GitHub Pages from the `main` branch. DNS for `atlanticit.org` must point to GitHub Pages.
