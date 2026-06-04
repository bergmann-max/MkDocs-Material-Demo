# Start

Welcome to my [Zensical Demo project](https://github.com/bergmann-max/zensical-demo) on GitHub! This repository serves as a way for me to gain experience with the Zensical static site generator, a modern reimplementation of the Material theme ecosystem.

The project includes a basic demo site built with Zensical, showcasing various features such as navigation menus, customizable site search, and responsive design. I've also included some sample Markdown files to demonstrate how to structure and format content.

This project is primarily for my own personal reference, but I hope that others who are interested in using Zensical will find it helpful as well. I plan to continue experimenting and adding to the demo site over time, so be sure to check back for updates!

If you have any questions or suggestions for improvements, please feel free to open an issue or submit a pull request. Thanks for checking out my project!

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
