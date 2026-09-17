# K.Popov Marketer — portfolio

Static one-page portfolio (cinematic CRT-TV theme). No build step, no dependencies.

- `index.html` — the site
- `assets/` — all videos and images
- `.nojekyll` — tells GitHub Pages to serve files as-is (optional)

## Hosting (GitHub Pages)
1. Put these files in the root of a GitHub repository.
2. Repo **Settings → Pages → Build and deployment → Source: Deploy from a branch**, branch `main`, folder `/ (root)`.
3. The site goes live at `https://<username>.github.io/<repo>/` in ~1 minute.

All asset paths are relative, so it works from any folder or subpath.
