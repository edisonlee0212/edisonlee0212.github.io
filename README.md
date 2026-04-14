# Bosheng Li Personal Website

This repository contains the source for [https://edisonlee0212.github.io](https://edisonlee0212.github.io), a Jekyll-based personal website for Bosheng Li.

It is built on top of the Academic Pages / Minimal Mistakes stack, but this repository is for the site itself rather than the upstream template.

## Key content locations

* Site-wide settings: `_config.yml`
* Top navigation: `_data/navigation.yml`
* Homepage: `_pages/about.md`
* Publications landing page: `_pages/publications.html`
* Projects page: `_pages/projects.md`
* CV page: `_pages/cv.md`
* Blog posts: `_posts/`
* Publication entries: `_publications/`
* Static files such as the PDF CV: `files/`

## Local development

If Ruby and Bundler are installed:

```bash
bundle install
bundle exec jekyll serve -l -H localhost
```

The site will be available at `http://localhost:4000`.

## JavaScript assets

If you edit files under `assets/js/`, install the npm dependencies and rebuild the minified bundle:

```bash
npm install
npm run build:js
```

## Notes

* Uploaded files in `files/` are served directly from `/files/...`.
* Publication records are stored as individual markdown files in `_publications/`.
* This repository is not intended to document or maintain the upstream Academic Pages project.
