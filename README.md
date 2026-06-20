# paridanDKE.github.io

Personal projects site for Dan Parii, published with GitHub Pages.

## How it works

This repo is named `paridanDKE.github.io`, which makes it a GitHub Pages
**user site**: GitHub automatically publishes the root of the `main` branch to
**https://paridanDKE.github.io**. No build step — it's plain static files.

- `index.html` — the single-page site (header, projects, publications)
- `style.css` — styles
- `.nojekyll` — tells GitHub to skip Jekyll processing and serve files as-is

## Editing

Edit `index.html` to add/change projects, then commit and push to `main`.
Changes go live in a minute or two.

## Local preview

Open `index.html` directly in a browser, or run a local server:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Enabling Pages (one-time)

If the site isn't live yet, go to the repo's **Settings → Pages** and set the
source to **Deploy from a branch → `main` / root**.
