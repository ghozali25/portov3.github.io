# Ahmad Ghozali — Portfolio (v3)

Personal portfolio website of Ahmad Ghozali, published with GitHub Pages:

**Live site:** https://ghozali25.github.io/portov3.github.io/

## About

A single-page static portfolio. The page introduces Ahmad Ghozali and walks visitors through his background and work in data.

Sections on the page:

- **Home** — introduction
- **Career** — career journey
- **Skill** — skills overview
- **Project** — selected projects
- **Partner** — partners / collaborations
- **Why Me** — reasons to work together

The page also links to his LinkedIn and Instagram profiles and to a downloadable CV (`assets/cv.pdf`).

## Structure

```
.
├── index.html      # the whole site (single page)
└── assets/
    ├── css/        # stylesheets
    ├── js/         # scripts
    ├── img/        # images
    └── cv.pdf      # downloadable CV
```

## Running locally

No build step — it is plain HTML/CSS/JavaScript. Either open `index.html` directly in a browser, or serve the folder with any static file server, for example:

```bash
python3 -m http.server 8000
# then open http://localhost:8000
```

## Deployment

The site is served by GitHub Pages from the `master` branch of this repository; pushing to `master` updates the live site.
