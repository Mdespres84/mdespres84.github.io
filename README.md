# mdespres84.github.io

Static one-page site, live at https://mdespres84.github.io. GitHub Pages serves these files as they are.

## Files

- `index.html` — the whole site (styles and scripts are inline)
- `Michael-Despres-Resume.pdf` — the résumé the site's buttons link to
- `headshot.jpg` — the headshot; replace it with a file of the same name to swap the photo
- `.nojekyll` — tells GitHub Pages to serve files as-is

## Turn on visitor stats (GoatCounter, free)

1. Sign up at https://www.goatcounter.com/signup and pick a code, for example `mdespres84`.
2. In `index.html`, near the bottom, set `GOATCOUNTER_CODE = 'mdespres84';` and commit.
3. Your dashboard is at https://mdespres84.goatcounter.com. It shows visits, referrers (LinkedIn, Google, email), country, device, and these click events: `download-resume`, `click-email`, `click-linkedin`, `click-linkedin-recs`, `contact-form-sent`.

GoatCounter doesn't store IP addresses or set cookies, so no cookie banner is needed.

## Know which company looked: tracked links

When you send the site to a specific company, add `?ref=` and a short name:

- `https://mdespres84.github.io/?ref=tekmetric`
- `https://mdespres84.github.io/?ref=highlevel`

Each visit through that link shows in GoatCounter as an event named `ref-tekmetric`, and a contact-form message sent from it carries the `ref` too.

## Turn on the contact form (Formspree, free: 50 messages/month)

1. Sign up at https://formspree.io and create a form. Its endpoint looks like `https://formspree.io/f/xyzabcd`.
2. In `index.html`, set `FORMSPREE_ID = 'xyzabcd';` and commit.
3. Every message arrives by email, and Formspree keeps all of them in its dashboard, where you can export a CSV of name, email, company, role, the role they're hiring for, and whether they agreed to future contact.

Until `FORMSPREE_ID` is set, the form opens the visitor's email app with their details filled in.

## Updating

- Swap the résumé: upload a new file with the exact same name, `Michael-Despres-Resume.pdf`.
- Edit copy: edit `index.html` in GitHub's web editor and commit.
