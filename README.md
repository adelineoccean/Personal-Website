# Personal-Website

Personal website for Adeline Occean — portfolio, resume, and contact information.

Live demo: https://adelineoccean.github.io/Personal-Website/

## Overview

This repository contains a small static website built with HTML and CSS. It includes:
- index.html (home)
- about.html, resume.html, interest.html, socials.html (subpages)
- CSS files and image assets

## Quick start

To preview locally:

- Open index.html directly in a browser (works for basic static pages), or
- Serve via a simple HTTP server (recommended to avoid issues with some assets):

  - Python 3:
    ```
    python -m http.server 8000
    ```
    Then open http://localhost:8000 in your browser.

## Deploy

- This repository is set up for GitHub Pages. To publish from the default branch:
  1. Push code to the `main` branch.
  2. In repository Settings → Pages, confirm Deployment source is set to the branch/root you use.

## Notes & TODOs

- Add or update `favicon.ico` at the repository root and reference it in the head.
- Ensure all image paths are consistent (e.g., use `./img/` for assets).
- Fix typos (e.g., `at="logo"` → `alt="logo"`) and move footer inside the `<body>`.
- Consider adding a LICENSE (MIT if you want permissive reuse).
- Add `README` screenshot and a short description for the repository page.

## Contact

For changes or questions: adelineocc9@gmail.com
