# jamesc159.github.io

Personal portfolio.

Plain static HTML/CSS/JS, no build step. GitHub Pages serves the repository root.

- `index.html` — content (edit here to update experience, projects, etc.)
- `style.css` — design tokens (light/dark) and layout
- `script.js` — theme toggle, scroll reveal, active nav

Preview locally:

```bash
python3 -m http.server 8000
```

When you change `style.css` or `script.js`, bump the `?v=` number on their
links in `index.html` so browsers don't keep serving the cached copy
(GitHub Pages caches assets for 10 minutes).
