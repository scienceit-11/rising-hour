# Rising Hour — deploy-ready static site

This folder is a complete, self-contained static website: one HTML file plus a
web-app manifest and two icons. No build step, no dependencies, no server-side
code — any static host will serve it as-is.

- `index.html` — the whole app (birth-time rectification calculator, natal
  chart wheel, multi-profile switcher, PDF export via the browser's print
  dialog).
- `manifest.webmanifest` — lets phones install it to the home screen as a
  standalone app (no browser address bar).
- `icon-192.png`, `icon-512.png` — the app icon at both sizes the manifest
  references.

Deploy this folder as-is to GitHub Pages, Netlify, Vercel, Cloudflare Pages,
or any static host, and it becomes a public URL anyone can open — no login,
no backend, no build.
