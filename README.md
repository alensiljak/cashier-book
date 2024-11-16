# cashier-book
Cashier documentation

https://alensiljak.github.io/cashier-book/

[![Deploy mdBook site to Pages](https://github.com/alensiljak/cashier-book/actions/workflows/mdbook.yml/badge.svg)](https://github.com/alensiljak/cashier-book/actions/workflows/mdbook.yml)

# Introduction

This is the source repository for the Cashier documentation book. It describes the features / requirements for the Cashier app.

# Development

Install `mdbook` with ``.
Preview the book by running `mdbook serve` in the root directory.

Open http://localhost:3000 to view the content.

# Basic mdBook Operations

```sh
mdbook init
mdbook serve --open
```

# Publishing 

There is a GitHub action specific for mdBook publishing, which builds the site and publishes to GitHub Pages.
