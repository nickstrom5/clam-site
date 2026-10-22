# Clam: website

The marketing site for **Clam**, an app blocker for iPhone: pick your distracting apps once, tap one button, and they stay locked until the timer ends. No account and nothing to sign up for.

Live at **[getclam.app](https://getclam.app)**.

## What's here

A hand-written static site with no build step, served by GitHub Pages straight from this repo's root.

| Path | What it is |
| --- | --- |
| `index.html` | Home page |
| `how-to-block-apps-on-iphone.html`, `block-tiktok-instagram-on-iphone.html`, `focus-mode-vs-app-blocker.html` | Guides that answer common search questions |
| `privacy.html`, `terms.html`, `support.html` | Pages the App Store listing links to |
| `screenshots/`, `brand/`, `og.png`, icons | Images, the share card and favicons |
| `sitemap.xml`, `robots.txt`, `site.webmanifest`, `CNAME`, `404.html` | Search, PWA and hosting files |

## Run it locally

```bash
python3 -m http.server 8000
```

Then open <http://localhost:8000>.

## Deploying

Push to `main`. GitHub Pages publishes the repo root to the custom domain in `CNAME`.
