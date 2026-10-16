# mdespres84.github.io

Static one-page site, live at https://mdespres84.github.io. GitHub Pages serves these files as they are.

## Files

- `index.html` — the whole site (styles and scripts are inline)
- `Michael-Despres-Resume.pdf` — the résumé the site's buttons link to
- `headshot.jpg` — the headshot; replace it with a file of the same name to swap the photo
- `.nojekyll` — tells GitHub Pages to serve files as-is

## Know which company looked: tracked links

When you send the site to a specific company, add `?ref=` and a short name:

- `https://mdespres84.github.io/?ref=tekmetric`
- `https://mdespres84.github.io/?ref=highlevel`

A contact-form message sent from that link carries the `ref`, so you know which company it came from.

## Turn on the contact form (Formspree, free: 50 messages/month)

1. Sign up at https://formspree.io and create a form. Its endpoint looks like `https://formspree.io/f/xyzabcd`.
2. In `index.html`, set `FORMSPREE_ID = 'xyzabcd';` and commit.
3. Every message arrives by email, and Formspree keeps all of them in its dashboard, where you can export a CSV of name, email, company, role, the role they're hiring for, and whether they agreed to future contact.

Until `FORMSPREE_ID` is set, the form opens the visitor's email app with their details filled in.

## Updating

- Swap the résumé: upload a new file with the exact same name, `Michael-Despres-Resume.pdf`.
- Edit copy: edit `index.html` in GitHub's web editor and commit.
