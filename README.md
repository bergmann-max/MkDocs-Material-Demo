# MkDocs-Material Demo
Live demo: <https://bergmann-max.github.io/MkDocs-Material-Demo>

For full documentation visit
  * [MkDocs](https://www.mkdocs.org)
  * [MkDocs-Material](https://squidfunk.github.io/mkdocs-material/)
  * [Markdown](https://daringfireball.net/projects/markdown)

Demo repository for MkDocs with the Material theme. Demonstrates:

- **Plugins**: privacy, social, tags, search, glightbox, git-revision-date-localized, table-reader
- **Features**: navigation tabs, instant loading, integrated TOC, code copy, search highlight, dark mode, announce bar, content tooltips, edit link, …
- **Extensions**: admonitions, mermaid diagrams, emoji, footnotes, tasklists, content tabs, critic markup, code annotations, table sorting
- **Deployment**: GitHub Actions + `mkdocs gh-deploy` (`astral-sh/setup-uv`) -> GitHub Pages
- **Versioning**: mike

## Getting started

### Requirements

[uv](https://docs.astral.sh/uv/getting-started/installation/)

### Setup

```bash
# Clone repository
git clone git@github.com:bergmann-max/MkDocs-Material-Demo.git
cd MkDocs-Material-Demo
```

```bash
# Sync dependencies and start the dev server:
uv sync
uv run mkdocs serve
```

Open [http://127.0.0.1:8000/](http://127.0.0.1:8000/) in your browser.

## Project layout

    mkdocs.yml              # Theme, plugins, extensions, features
    pyproject.toml           # Dependencies (uv)
    .github/workflows/ci.yml # Deploy to GitHub Pages
    overrides/
        main.html            # Announce bar template override
    includes/
        abbreviations.md     # Global abbreviations via snippets
    docs/
        index.md             # Homepage
        code.md              # Code highlighting & annotations
        diagrams.md          # Mermaid diagrams
        lists.md             # Task lists, definition lists
        media.md             # Images, video, lightbox
        tables.md            # CSV table reader + sortable tables
        tags.md              # Tag index (auto-generated)
        miscellaneous/       # Admonitions, buttons, footnotes, tooltips, formatting, content tabs
        assets/              # Logo, favicon
        data/                # CSV data files
        javascripts/         # Table sort scripts
        ## License

## License

[MIT](LICENSE)

## Author

Max Bergmann
