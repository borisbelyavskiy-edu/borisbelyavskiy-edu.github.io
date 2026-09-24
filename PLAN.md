# Portfolio Site Plan

## Summary

Build a publish-ready personal portfolio for **Boris Belyavskiy** as a root-level GitHub Pages Jekyll site at `borisbelyavskiy-edu.github.io`.

The site will present Boris as a strategy consultant and sociologist focused on how people and organizations change in the age of AI. It will use the supplied professional history and achievements without inventing additional employers, clients, metrics, or projects.

## Pages

- **Home** — concise positioning statement, selected proof points, and clear paths to experience, about, and contact.
- **About** — professional perspective, sociology and strategy background, and research identity.
- **Work Experience** — chronological experience across McKinsey & Company, HSE University, and Procter & Gamble, with supplied roles and outcomes.
- **Contact** — a direct way to get in touch, GitHub profile link, and ORCID profile link.

## Visual direction

- Dark-only presentation.
- Editorial and distinctive typography, with a restrained, high-trust consulting feel inspired by the supplied McKinsey reference.
- Single-column, responsive layout with strong hierarchy, accessible contrast, semantic HTML, and no decorative UI that competes with the content.
- Subtle interaction states only; no animation system or unnecessary JavaScript.

## Technical approach

- Jekyll files at the repository root: `index.md`, page Markdown files, `_config.yml`, `_layouts`, `_includes`, `assets`, `sitemap.xml`, `favicon.svg`, and `README.md`.
- Markdown front matter for page content and reusable layouts/includes for shared structure.
- GitHub Pages-compatible configuration with an empty `baseurl`, URL filters for internal links, SEO metadata, Open Graph tags, and a sitemap.
- No backend, database, CMS, contact form service, trackers, or frontend framework.

## Assumptions and placeholders

- GitHub username: `borisbelyavskiy-edu`.
- ORCID: `0000-0002-5174-8719`.
- A public `mailto:` link is desired, but the actual email address was not supplied. The contact page will use a clearly marked placeholder until the address is provided.
- No separate LinkedIn URL, profile photo, logo, or additional project case studies were supplied; these will not be invented.
- The site will be structured for GitHub Pages publishing from the `main` branch and repository root.
