# mkdocs-terminal-example-highlightjs

This repository is used to publish an example MkDocs site to GitHub pages.  The site demonstrates how to enable browser-side code highlighting with the [highlight.js javascript library](https://highlightjs.org/).

## Site

[ntno.github.io/mkdocs-terminal-example-highlightjs](https://ntno.github.io/mkdocs-terminal-example-highlightjs/)

## Source Code

The source code of the site is located in the `ntno/mkdocs-terminal` repository in the [tests/examples/highlightjs](https://github.com/ntno/mkdocs-terminal/tree/main/tests/examples/highlightjs) subfolder.

## CI/CD

A [GitHub Action workflow](https://github.com/ntno/mkdocs-terminal/actions/workflows/pages-deploy-example-site.yml) in the `ntno/mkdocs-terminal` repository updates this site's static files in the [`gh-pages` branch](https://github.com/ntno/mkdocs-terminal-example-highlightjs/tree/gh-pages).