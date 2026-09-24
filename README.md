# Boris Belyavskiy — personal site

This repository is a root-level Jekyll site designed to publish directly to GitHub Pages from the `main` branch and `/` (root).

## Update the site

- Edit `index.md`, `about.md`, `experience.md`, or `contact.md` to update page content.
- Shared navigation and the footer live in `_includes/header.html` and `_includes/footer.html`.
- The global layout and SEO metadata live in `_layouts/default.html`.
- Visual styles live in `assets/css/style.css`.
- Update the canonical `url` in `_config.yml` if the GitHub Pages username changes.

## Preview locally

Install Ruby and Bundler, then install Jekyll and the GitHub Pages dependency:

```bash
gem install bundler jekyll
bundle exec jekyll serve
```

If the repository does not have a `Gemfile`, the site can also be previewed with:

```bash
jekyll serve
```

Open `http://localhost:4000` in a browser.

## Publish with GitHub Pages

In the repository settings, choose **Pages**, select the `main` branch, and select `/ (root)` as the folder. GitHub Pages will build the Markdown and Liquid files automatically.

## Lighthouse

With the local site running, use Chrome DevTools → Lighthouse and audit the mobile and desktop versions. The site avoids third-party scripts, uses semantic HTML, and keeps the visual system in one stylesheet to support strong Performance, Accessibility, Best Practices, and SEO scores.