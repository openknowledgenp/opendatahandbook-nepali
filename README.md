# Handbook Introduction

The Open Data Handbook (first issued in 2010 and regularly updated) is a guide to open data, specifically open government data. It was first issued in 2010 by Open Knowledge International and has been regularly updated since. The handbook has been used by governments and civil society organizations around the world as an introduction and blue-print for open data projects.

The Nepali version of this handbook will include content from Global [Open Data Handbook](http://opendatahandbook.org), and include Licensing terms from [Open Definition](http://opendefinition.org).

Access Handbook: https://handbook.oknp.org

## Local development

This is a [Jekyll](https://jekyllrb.com) site. To build and preview it locally:

```sh
bundle install
bundle exec jekyll serve
```

Then open http://localhost:4000.

## Deployment

The site is published at [handbook.oknp.org](https://handbook.oknp.org) via GitHub Pages, served from the `gh-pages` branch.

Deployment is automated with the GitHub Actions workflow at [.github/workflows/deploy.yml](.github/workflows/deploy.yml): every push to `master` builds the Jekyll site and publishes the result to `gh-pages`. There's nothing to run by hand — just push to `master` (or trigger the workflow manually from the Actions tab) and the live site updates within a couple of minutes.
