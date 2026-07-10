# Ali Tavakoli - Academic Portfolio

Static academic portfolio for [alii-tavakolii.ir](https://alii-tavakolii.ir/).

## Structure

- `index.html` - biography and profile overview
- `education.html` - education and coursework
- `research.html` - research interests and experience
- `projects.html` - selected projects
- `honors.html` - honors, teaching, and activities
- `resume.pdf` - downloadable academic resume
- `style.css` and `fonts/` - shared styling and self-hosted fonts

## Local preview

Run any static HTTP server from the repository root, for example:

```bash
python -m http.server 8000
```

Then open `http://localhost:8000/`.

## Deployment

The site is static and can be deployed directly to Cloudflare Pages or any static hosting provider. `wrangler.jsonc` contains the Cloudflare configuration.
