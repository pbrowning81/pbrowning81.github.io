# petebrowning.com

Personal site for Peter Browning — product leader and builder.

Static HTML/CSS with no build step. The homepage contains selected work,
including FlowIt and Exile Forge, and links to long-form Field Notes.

## Local preview

Open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Deploy

Hosted on GitHub Pages, served at [petebrowning.com](https://petebrowning.com) (see `CNAME`).
Push to the default branch; Pages publishes automatically.

## Files

- `index.html` — homepage and selected work
- `assets/site.css` — shared site and article design system
- `assets/flowit-dashboard.png` — curated FlowIt product visual
- `assets/product-leaders-who-build-social.png` — social sharing image for the
  first Field Note
- `field-notes/product-leaders-who-build/index.html` — first published Field
  Note
- `headshot.jpg` — profile photo
- `CNAME` — custom domain for GitHub Pages
