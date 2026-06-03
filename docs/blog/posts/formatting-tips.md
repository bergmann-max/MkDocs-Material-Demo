---
draft: false
date: 2025-06-02
authors:
  - max
categories:
  - Tutorial
---

# Formatting Tips for MkDocs Material

MkDocs Material supports a wide range of formatting options that make technical
documentation shine.

## Admonitions

Admonitions (call-outs) are great for drawing attention to important information:

!!! tip "Pro tip"
    Use `!!! tip` for helpful suggestions and best practices.

!!! warning "Watch out"
    Use `!!! warning` for things users should be careful about.

## Code blocks with annotations

``` yaml title="mkdocs.yml"
theme:
  name: material # (1)!
  features:
    - content.code.copy
```

1.  Always set the theme name to `material`.

## Diagrams with Mermaid

``` mermaid
graph LR
  A[Markdown] --> B[MkDocs];
  B --> C[Material Theme];
  C --> D[Beautiful Docs];
```

## Math with KaTeX

Inline math like $E = mc^2$ and block equations:

$$
\int_0^\infty e^{-x^2} dx = \frac{\sqrt{\pi}}{2}
$$
