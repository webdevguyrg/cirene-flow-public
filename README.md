# CireneFlow — Website

Public marketing site for **CireneFlow**, a private, on-device voice-dictation app for macOS.

## Hosting

This is a single, self-contained static page — no build step, no framework, no server.
It is served with **GitHub Pages** from the `main` branch (root folder). The `.nojekyll`
file tells Pages to serve the files as-is (no Jekyll processing).

To enable: repository **Settings → Pages → Source: Deploy from a branch → `main` / `/ (root)`**.
The site then goes live at `https://webdevguyrg.github.io/cirene-flow-public/`.

## Invitation form

The "Request access" form submits to [FormSubmit.co](https://formsubmit.co), which forwards
each request by email. The first submission triggers a one-time activation email to the
destination inbox — click the link in it once to enable delivery.

## Files

| File | Purpose |
|---|---|
| `index.html` | The entire website (HTML, CSS, JS inline) |
| `.nojekyll` | Serve files as-is on GitHub Pages |

© 2026 GrowTech Development, LLC.
