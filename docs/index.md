# Start

A demo site built with [Zensical](https://github.com/squidfunk/zensical), a static site generator based on the Material theme ecosystem. The site demonstrates navigation, search, responsive layout, and Markdown content formatting.

[Source on GitHub](https://github.com/bergmann-max/zensical-demo)

!!! info "For full documentation visit"
    * [Zensical](https://github.com/squidfunk/zensical)
    * [Markdown](https://daringfireball.net/projects/markdown)

## Getting started

### Requirements

Install [uv](https://docs.astral.sh/uv/getting-started/installation/) -- it manages both Python and packages.

### Setup

1. Clone the repository:

        $ git clone git@github.com:bergmann-max/zensical-demo.git

1. Sync dependencies and start the dev server:

        $ cd zensical-demo
        $ uv sync
        $ uv run zensical serve

1. Open [http://127.0.0.1:8000/](http://127.0.0.1:8000/) in your browser.

## Project layout

    zensical.toml  # The configuration file.
    docs/
        index.md  # The documentation homepage.
        ...       # Other markdown pages, images and other files.
