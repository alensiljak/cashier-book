This repo has been archived. All the docs have been moved to Cashier Help system within the app.

# cashier-book

Cashier documentation

Hosted at https://alensiljak.github.io/cashier-book/

[![Deploy mdBook site to Pages](https://github.com/alensiljak/cashier-book/actions/workflows/mdbook.yml/badge.svg)](https://github.com/alensiljak/cashier-book/actions/workflows/mdbook.yml)

## Introduction

This is the source repository for the Cashier documentation book. It describes the features / requirements for the Cashier app.

## Development

Install mdBook with

```sh
cargo binstall mdbook
```

Preview the book by running

```sh
mdbook serve
```

in the root directory.

Open http://localhost:3000 to view the content.

## Basic mdBook Operations

```sh
mdbook init
mdbook serve --open
```

## Publishing

There is a GitHub action specific for mdBook publishing, which builds the site and publishes to GitHub Pages.
This runs on commits to the `main` branch or can be run manually.
