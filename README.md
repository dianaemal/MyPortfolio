# Personal Portfolio

A simple, fast, single-page portfolio you can customize.

## Quick start

Open `index.html` in your browser.

## Customize
- Update your name in `index.html` (both the `<title>` and header brand).
- Edit the About copy in the `#about` section.
- Replace demo items in `projects.json` with your real projects.
  - Each project supports: `title`, `description`, `tags[]`, optional `demo`, optional `source`.
- Update the links in the Contact section.
- Swap the favicon in `assets/favicon.svg` if you like.

## Notes
- Projects are loaded from `projects.json`. If you serve from file:// and run into CORS issues, start a local server:

```bash
# macOS
python3 -m http.server 5173
# then open http://localhost:5173
```

- Light/dark theme respects your system preference and is saved between visits. 