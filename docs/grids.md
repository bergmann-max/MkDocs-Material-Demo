---
tags:
  - Reference
---

# Grids

Grids arrange blocks into responsive layouts. They come in two flavors: card grids (each item rendered as a levitating card) and generic grids (any block elements arranged side by side).

=== "Card grid (list syntax)"

    ````
    <div class="grid cards" markdown>

    -   :material-clock-fast:{ .lg .middle } __Set up in 5 minutes__

        ---

        Install [`mkdocs-material`](https://pypi.org/project/mkdocs-material/)
        with `pip` and get up and running in minutes

        [:octicons-arrow-right-24: Getting started](index.md)

    -   :fontawesome-brands-markdown:{ .lg .middle } __It's just Markdown__

        ---

        Focus on your content and generate a responsive and searchable static site

        [:octicons-arrow-right-24: Code blocks](code.md)

    -   :material-format-font:{ .lg .middle } __Made to measure__

        ---

        Change the colors, fonts, language, icons, logo and more with a few lines

        [:octicons-arrow-right-24: Formatting](miscellaneous/formatierung.md)

    -   :material-scale-balance:{ .lg .middle } __Open Source, MIT__

        ---

        Material for MkDocs is licensed under MIT and available on
        [GitHub](https://github.com/squidfunk/mkdocs-material)

        [:octicons-arrow-right-24: License](https://github.com/squidfunk/mkdocs-material/blob/master/LICENSE)

    </div>
    ````

    <div class="grid cards" markdown>

    -   :material-clock-fast:{ .lg .middle } __Set up in 5 minutes__

        ---

        Install [`mkdocs-material`](https://pypi.org/project/mkdocs-material/)
        with `pip` and get up and running in minutes

        [:octicons-arrow-right-24: Getting started](index.md)

    -   :fontawesome-brands-markdown:{ .lg .middle } __It's just Markdown__

        ---

        Focus on your content and generate a responsive and searchable static site

        [:octicons-arrow-right-24: Code blocks](code.md)

    -   :material-format-font:{ .lg .middle } __Made to measure__

        ---

        Change the colors, fonts, language, icons, logo and more with a few lines

        [:octicons-arrow-right-24: Formatting](miscellaneous/formatierung.md)

    -   :material-scale-balance:{ .lg .middle } __Open Source, MIT__

        ---

        Material for MkDocs is licensed under MIT and available on
        [GitHub](https://github.com/squidfunk/mkdocs-material)

        [:octicons-arrow-right-24: License](https://github.com/squidfunk/mkdocs-material/blob/master/LICENSE)

    </div>

=== "Card grid (block syntax)"

    ````
    <div class="grid" markdown>

    :fontawesome-brands-html5: __HTML__ for content and structure
    { .card }

    :fontawesome-brands-js: __JavaScript__ for interactivity
    { .card }

    :fontawesome-brands-css3: __CSS__ for presentation
    { .card }

    </div>
    ````

    <div class="grid" markdown>

    :fontawesome-brands-html5: __HTML__ for content and structure
    { .card }

    :fontawesome-brands-js: __JavaScript__ for interactivity
    { .card }

    :fontawesome-brands-css3: __CSS__ for presentation
    { .card }

    </div>

=== "Generic grid"

    ````
    <div class="grid" markdown>

    !!! info "Admonition"

        Sed sagittis eleifend rutrum. Donec vitae suscipit est.
        Nulla tempor lobortis orci.

    !!! warning "Another admonition"

        Sed sagittis eleifend rutrum. Donec vitae suscipit est.
        Nulla tempor lobortis orci.

    </div>
    ````

    <div class="grid" markdown>

    !!! info "Admonition"

        Sed sagittis eleifend rutrum. Donec vitae suscipit est.
        Nulla tempor lobortis orci.

    !!! warning "Another admonition"

        Sed sagittis eleifend rutrum. Donec vitae suscipit est.
        Nulla tempor lobortis orci.

    </div>
