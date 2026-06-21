# Image to prompt — Tester Guide

A single-page onboarding guide for testers of the **Image to prompt** Chrome extension
preview build. Pure static HTML (no build step, no dependencies) — served via GitHub Pages.

## Local preview
Open `index.html` in a browser, or:

```sh
python3 -m http.server 8131
# then visit http://localhost:8131
```

## Publishing (GitHub Pages)
Push to `main`, then in **Settings → Pages** set source to branch `main` / `/ (root)`.
The guide goes live at `https://<user>.github.io/<repo>/`.
