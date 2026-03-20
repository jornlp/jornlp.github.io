# Minimal Personal Link Site

A single-page static site inspired by Carrd/Linktree.

## Edit your info

Open `index.html` and update:

- `Your Name`
- Bio text under the heading
- Link labels and `href` values in each section (`Key Links`, `Projects`, `Research Group`)
- Footer date (`Last updated`)

## Local preview

From this folder:

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000`.

## Deploy quickly

### GitHub Pages

1. Push this folder to a GitHub repo.
2. In repo settings, enable **Pages**.
3. Set source to the main branch root.

### Netlify

1. Create a new site from this repo.
2. Build command: none
3. Publish directory: `.`

Because this is plain HTML/CSS, no framework setup is needed.
