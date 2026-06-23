# H&H City Tower — Landing Page

Standalone marketing landing page for the H&H City Tower commercial offering.

The page is a self-contained build: `index.html` contains the inlined markup,
styles, and scripts, and references a small set of media assets in the repo root.

## Contents

| File | Purpose |
|------|---------|
| `index.html` | The landing page (site root) |
| `favicon.svg` | Site favicon |
| `hero.jpg` | Hero poster image |
| `hero-bg.mp4` | Hero background video |
| `gallery-1.jpg`, `gallery-2.jpg`, `gallery-3.jpg` | Project gallery images |

## Local preview

The page is fully static — open `index.html` directly, or serve the folder:

```bash
python -m http.server 8000
# then visit http://localhost:8000
```

## Deploy

Any static host works since `index.html` is the root. To use **GitHub Pages**,
enable Pages on the default branch from the repo root directory.
