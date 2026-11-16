# johannesvsbusch.github.io

Personal website, built with plain [Hugo](https://gohugo.io) — no theme, no Node, no other dependencies.

## Preview locally

```sh
hugo server
```

Then open http://localhost:1313. The page reloads when a file changes.

## Where things are

**Content (edit these to change what the site says)**

| What | Where |
|---|---|
| Name, bio, links, interests, education | `data/profile.yaml` |
| Awards, organizing, reviewing, teaching, contact | `data/<name>.yaml` |
| Supervised students (kept, not shown) | `data/supervision.yaml` |
| Publications, one folder each (`index.md` + `cite.bib`) | `content/publications/` |
| News (kept, not shown) | `content/news/` |
| Photo | `assets/img/avatar.jpg` |

**Presentation (edit these to change how it looks)**

| What | Where |
|---|---|
| Which sections the homepage has, and their order | `content/_index.md` |
| Top-bar menu, site title, address | `hugo.yaml` |
| Colours, fonts, spacing | `assets/css/main.css` |
| HTML templates | `layouts/` |
| Icons (SVG) | `assets/icons/` |
| Browser-tab icon | `static/favicon.ico`, `static/icon.png`, `static/apple-touch-icon.png` |

## Adding a publication

Copy an existing folder in `content/publications/`, rename it, and edit `index.md` and `cite.bib`.
The folder name becomes the address: `/publication/<folder-name>/`. Write `me` in the author list for yourself.

## Publishing

Pushing to `main` builds and publishes the site through `.github/workflows/deploy.yml`.

## Credits

Icons: Heroicons (MIT), Simple Icons (CC0), Academicons (SIL OFL). Font: Inter (SIL OFL).
