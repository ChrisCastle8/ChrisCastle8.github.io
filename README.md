# Chris Castle — Personal Portfolio

This repository contains a static personal portfolio website for Kasoma Christopher ("Chris Castle"). It appears to be intended for GitHub Pages (repository named `ChrisCastle8.github.io`). The site is implemented with plain HTML, a bit of CSS/JS, and static assets.

## What it is
- A simple personal website / portfolio showcasing the developer, skills, education, and works.
- Main pages: `index.html`, `about.html`, `works.html`, `contact.html`, `thankyou.html`.
- Template copies exist under the `templates/` directory.
- Static assets (images, CSS, JS) are under `static/`.
- No Markdown files, server-side code, or build system are present.

## Technologies
- HTML (primary)
- CSS and JavaScript (static files under `static/`)
- Designed to be served as a static site (GitHub Pages)

## Repository structure (high level)

- index.html — Home page
- about.html — About / bio
- works.html — Portfolio / projects
- contact.html — Contact form page
- thankyou.html — Thank-you page after contact submission
- templates/ — Template versions of the pages
- static/ — CSS, JS, images, and other assets

## Preview locally
Simplest options to preview the site locally:

- Open `index.html` directly in your browser.
- Or run a simple HTTP server from the repository root so relative paths work correctly:

  - Python 3:

    ```bash
    python -m http.server 8000
    # then open http://localhost:8000/index.html
    ```

  - Node (http-server):

    ```bash
    npx http-server -p 8000
    ```

- Or use the VS Code Live Server extension.

## How to edit
- Edit the HTML files directly or update the templates in `templates/`.
- Static assets (images, styles, scripts) live in `static/`.
- Commit changes and push to the `main` branch (or the repository's default branch) to update the GitHub Pages site.

## Deployment
- Repositories named `<username>.github.io` are served automatically by GitHub Pages from the default branch (main) at `https://<username>.github.io`.

## License
- No license is specified in this repository. Add a LICENSE file if you want to set reuse terms.

## Notes
- If you'd like, I can:
  - Customize the README (add author contact, social links, or a deployment badge).
  - Add a LICENSE file.
  - Convert templates to a simple static site generator setup.

