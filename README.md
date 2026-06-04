# Zensical Demo

Live demo: <https://bergmann-max.github.io/Zensical-Demo>

For full documentation visit:
- [Zensical](https://github.com/squidfunk/zensical)

Demo repository showcasing the static site generator.

## Getting started

### Requirements

[uv](https://docs.astral.sh/uv/getting-started/installation/)

### Setup

```bash
git clone git@github.com:bergmann-max/Zensical-Demo.git
cd zensical-demo
```

```bash
uv sync
uv run zensical serve
```

Open [http://127.0.0.1:8000/](http://127.0.0.1:8000/) in your browser.

## Project layout

    zensical.toml            # Site config (theme, extensions, features)
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
        media.md             # Images, video, GLightbox
        tables.md            # Markdown & HTML tables, sortable
        tags.md              # Tag index
        math.md              # KaTeX math rendering
        grids.md             # Grid cards layout
        annotations.md       # Annotation marks
        miscellaneous/       # Admonitions, buttons, footnotes, tooltips, formatting, content tabs
        assets/              # Logo, favicon
        javascripts/         # Table sort, KaTeX init scripts

## License

[MIT](LICENSE)
