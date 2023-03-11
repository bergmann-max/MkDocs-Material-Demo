# Start

Welcome to my [MkDocs-Material Demo project](https://github.com/bergmann-max/MkDocs-Material-Demo) on GitHub! This repository serves as a way for me to gain experience with the MkDocs documentation generator, specifically using the Material theme.

The project includes a basic demo site built with MkDocs-Material, showcasing various features of the theme such as navigation menus, customizable site search, and responsive design. I've also included some sample Markdown files to demonstrate how to structure and format content in a way that works well with MkDocs-Material.

This project is primarily for my own personal reference, but I hope that others who are interested in using MkDocs-Material will find it helpful as well. I plan to continue experimenting with this theme and adding to the demo site over time, so be sure to check back for updates!

If you have any questions or suggestions for improvements, please feel free to open an issue or submit a pull request. Thanks for checking out my project!

!!! info "For full documentation visit"
        * [MkDocs](https://www.mkdocs.org)
        * [MkDocs-Material](https://squidfunk.github.io/mkdocs-material/)
        * [Markdown](https://daringfireball.net/projects/markdown)

## Getting started

### Requirements

#### Python

Install [Python](https://www.python.org/) using your package manager of choice, or by downloading an installer appropriate for your system from [python.org](https://www.python.org/downloads/) and running it.

#### pip

If you're using a recent version of Python, the Python package manager, [pip](https://pip.pypa.io/en/stable/installing/), is most likely installed by default. However, you may need to upgrade pip to the lasted version:

    $ pip install --upgrade pip

If you need to install pip for the first time, download [get-pip.py](https://bootstrap.pypa.io/get-pip.py). Then run the following command to install it:

    $ python get-pip.py

### Installing MkDocs w/ MkDocs-Material

1. Install the necessary packages using pip:

        $ pip install mkdocs-material mkdocs[i18n] mkdocs-glightbox mkdocs-git-revision-date-localized-plugin mkdocs-table-reader-plugin

1.  Clone the repository:

        $ git clone git@github.com:bergmann-max/MkDocs-Material-Demo.git

1.  Change your current working directory

        $ cd MkDocs-Material-Demo

1.  Run the command to start a local server that hosts your MkDocs site

        $ mkdocs serve

1. Open up [http://127.0.0.1:8000/](http://127.0.0.1:8000/) in your browser, and you'll see the default home page being displayed        

## Project layout

    mkdocs.yml    # The configuration file.
    docs/
        index.md  # The documentation homepage.
        ...       # Other markdown pages, images and other files.    
