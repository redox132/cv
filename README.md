# rida.me

Personal CV / portfolio site. Plain HTML + CSS, no build step, no framework — just `index.html` and `styles.css`.

## Editing

Open `index.html` and edit directly. Things marked with a `placeholder` tag or obviously generic text (e.g. "Company Name", the LinkedIn link) are examples and should be replaced with real details:

- **Experience** — the three entries under "Experience" are example structure based on repos/activity visible on this machine; replace with your actual work history.
- **LinkedIn** — currently a placeholder link; update `href` in the contact nav.
- **Skills / Projects** — adjust to match what you actually want to highlight.

## Local preview

No server required — just open `index.html` in a browser, or serve it locally:

```bash
python3 -m http.server 8000
```

## Deployment

This repo is published via GitHub Pages from the `main` branch root.
