# michaeldespres — personal site

Static one-page site, live at https://mdespres84.github.io — GitHub Pages serves these files as they are.

## Files

- `index.html` — the whole site (styles and the copy-email script are inline)
- `Michael-Despres-Resume.pdf` — the résumé the site's buttons link to
- `.nojekyll` — tells GitHub Pages to serve files as-is

## Publish on GitHub Pages (free)

1. On GitHub, create a new **public** repository named `<your-username>.github.io`
   (for example `Mdespres84.github.io`). That name gives you the cleanest URL:
   `https://<your-username>.github.io`.
2. Upload every file in this folder to the repository root (Add file › Upload files),
   including `.nojekyll`. Commit.
3. Go to **Settings › Pages**. Under "Build and deployment", set Source to
   **Deploy from a branch**, branch `main`, folder `/ (root)`. Save.
4. Wait a minute or two, then open `https://<your-username>.github.io`.

## Updating

- Swap the résumé: upload a new file with the exact same name, `Michael-Despres-Resume.pdf`.
- Edit copy: edit `index.html` in GitHub's web editor and commit.

## Adding the headshot later

Upload the photo as `headshot.jpg`, then in `index.html` add this line inside the
hero, right above the `<h1>`:

```html
<img src="headshot.jpg" alt="Michael Despres" width="160" height="160" style="border-radius:50%;object-fit:cover">
```

## Custom domain (optional, later)

A domain like `michaeldespres.com` costs money to register. If you buy one, add it under
Settings › Pages › Custom domain and follow GitHub's DNS instructions.
