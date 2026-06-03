---
draft: false
date: 2025-06-03
authors:
  - max
categories:
  - Tutorial
---

# Deploying Your MkDocs Site

Once your documentation is ready, you need to deploy it. Here are the most common
approaches.

## GitHub Pages

The easiest way to deploy is via GitHub Actions and GitHub Pages:

``` yaml title=".github/workflows/ci.yml"
name: ci
on:
  push:
    branches:
      - master
permissions:
  contents: write
jobs:
  deploy:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v4
      - uses: astral-sh/setup-uv@v3
      - run: uv sync
      - run: uv run mkdocs gh-deploy --force
```

## Manual deployment

``` bash
uv sync
uv run mkdocs build
# Copy site/ to your web server
```

## Versioned deployment with mike

For multi-version documentation, use [mike](https://github.com/jimporter/mike):

``` bash
uv run mike deploy 1.0
uv run mike set-default 1.0
```

## Summary

| Method         | Effort | Versions | CI/CD |
|----------------|:------:|:--------:|:-----:|
| GitHub Pages   | Low    | No       | Yes   |
| Manual         | Medium | No       | No    |
| mike + CI      | Medium | Yes      | Yes   |
