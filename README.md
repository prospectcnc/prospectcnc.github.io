# Prospect CNC Ltd

This repository contains the source code for the **Prospect CNC Ltd** business landing page.

The website is a static marketing site used to advertise the company and its services.

## Live Website

https://www.prospectcnc.co.uk/ — hosted on GitHub Pages.

Every push to the `main` branch is deployed to the live site automatically by
`.github/workflows/static.yml`, usually within a couple of minutes.

## Hidden from search engines (on purpose)

The site is deliberately kept out of search results by the `noindex` tag in
`index.html`. `robots.txt` must keep allowing search engines to read `index.html`,
otherwise they can't see that tag. Photos in `assets/img/` are blocked so they
stay out of image search.

## Maintenance

Content updates can be made by editing `index.html` and `assets/css/styles.css`.

Only the website files are published: `index.html`, `robots.txt`, `favicon.ico` and the
`assets/` folder (the list is in `.github/workflows/static.yml`). If you add a new
top-level file or folder that the site needs, add it to that list too.

The site icon is drawn in `assets/icons/icon.svg`; `favicon.ico` and
`assets/icons/apple-touch-icon.png` are rendered from it.

## Ownership

Built and owned by Prospect CNC Ltd.
