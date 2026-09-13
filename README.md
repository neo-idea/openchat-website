# OpenChat Website

Official website for OpenChat — https://openchat.zpad.app

- `index.html` — landing page
- `privacy.html` — privacy policy (linked from App Store Connect)
- `support.html` — support / FAQ (used as the App Store support URL)
- `styles.css` — shared styles
- `CNAME` — GitHub Pages custom domain (openchat.zpad.app)

## Local preview

Open `index.html` in a browser, or run `python3 -m http.server` in this folder.

## DNS setup (one time)

The site is served by GitHub Pages from the `neo-idea` organization. In the DNS panel for `zpad.app`, add:

```
CNAME  openchat  →  neo-idea.github.io
```

Until that record exists, the site is reachable at https://neo-idea.github.io/openchat-website/
