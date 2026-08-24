# bookmar-lander

The public marketing/privacy-policy site for [Bookmar](https://github.com/kiorq/bookmar),
kept as its own repo so the app's source (`bookmar`, private) doesn't have
to go public just to serve GitHub Pages.

A single static page (`index.html`, no build step, no dependencies):

- Hero + feature highlights
- A Chrome Web Store link (currently a placeholder — see the `TODO` comment
  in `index.html` and swap it in once the listing is live)
- A `#privacy-policy` section — this is the URL to submit as the privacy
  policy link in the Chrome Web Store Developer Dashboard, e.g.
  `https://<user>.github.io/bookmar-lander/#privacy-policy`

## Publishing

1. Push this repo to GitHub as a **public** repo (Pages requires a public
   repo unless you're on GitHub Pro/Team/Enterprise).
2. Repo Settings → **Pages** → Source: **Deploy from a branch** → Branch:
   `main` / `(root)` → Save.
3. GitHub serves it at `https://<user>.github.io/bookmar-lander/` within a
   few minutes.

## Keeping content in sync

The feature list and privacy-policy text here were adapted from the app
repo's `README.md` and `PRIVACY.md`. If either changes there, update this
page to match.
