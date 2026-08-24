# Vetnups — landing page (draft)

Single-file static landing page testing the value proposition: *"Vetnups is a
commitment-oriented dating app with vetted profile attributes."*

- `index.html` — the whole page (HTML/CSS/JS inline, no build step).
- Fonts load from Google Fonts (IBM Plex Serif for display, IBM Plex Sans for body, IBM
  Plex Mono for labels/data) over a CDN link.
- Hero photography is hotlinked from Unsplash (free license, no attribution required) —
  Juno Jo and Rebecca Chandler. Placeholder lifestyle imagery, not real product/profile photos.
- The email capture form is a static mock — it does not submit anywhere yet.

## Run locally

Open `index.html` directly in a browser, or serve it:

```bash
python3 -m http.server 8000
# then open http://localhost:8000
```

## Deploy

No build step required. Any static host works as-is:

- **Netlify / Vercel**: point either at this repo's root, no framework preset needed.
- **GitHub Pages**: enable Pages on this repo, serving from the root of `main`.

## Status

Draft / concept only — not connected to the Vetnups product or backend.
