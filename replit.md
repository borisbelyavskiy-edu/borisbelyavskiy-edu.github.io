# Boris Belyavskiy personal site

This project is a root-level, publish-ready Jekyll portfolio for Boris Belyavskiy. GitHub Pages should publish from the `main` branch and `/` (root).

## Run & operate

- GitHub Pages builds the site automatically from the Markdown and Liquid files.
- To preview locally, install Ruby, Bundler, and Jekyll, then run `jekyll serve`.
- No backend, database, JavaScript application, or external service is required.

## Site map

- `index.md` — home page and positioning
- `about.md` — biography, research, and teaching
- `experience.md` — professional experience and selected outcomes
- `contact.md` — public email, GitHub, and ORCID links
- `_layouts/default.html` — shared document shell and SEO tags
- `_includes/header.html` and `_includes/footer.html` — shared navigation and footer
- `assets/css/style.css` — responsive dark editorial visual system
- `assets/favicon.svg`, `sitemap.xml`, and `robots.txt` — publishing and discovery support

## Content rules

- Keep professional claims grounded in the supplied biography and experience.
- Put page content in Markdown/front matter; keep shared structure in layouts/includes.
- Use `relative_url` for internal links so the site remains compatible with GitHub Pages path settings.