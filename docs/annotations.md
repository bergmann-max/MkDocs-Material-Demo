---
tags:
  - Content
  - Formatting
---

# Annotations

Annotations are small clickable markers that expand a tooltip containing arbitrary Markdown on click or keyboard focus. They can be placed almost anywhere in a document.

=== "Text annotations"

    ````
    Lorem ipsum dolor sit amet, (1) consectetur adipiscing elit.
    { .annotate }

    1.  :man_raising_hand: I'm an annotation! I can contain `code`, __formatted
        text__, images, ... basically anything that can be expressed in Markdown.
    ````

    Lorem ipsum dolor sit amet, (1) consectetur adipiscing elit.
    { .annotate }

    1.  :man_raising_hand: I'm an annotation! I can contain `code`, __formatted
        text__, images, ... basically anything that can be expressed in Markdown.

=== "Nested annotations"

    ````
    Lorem ipsum dolor sit amet, (1) consectetur adipiscing elit.
    { .annotate }

    1.  :man_raising_hand: I'm an annotation! (1)
        { .annotate }

        1.  :woman_raising_hand: I'm an annotation as well!
    ````

    Lorem ipsum dolor sit amet, (1) consectetur adipiscing elit.
    { .annotate }

    1.  :man_raising_hand: I'm an annotation! (1)
        { .annotate }

        1.  :woman_raising_hand: I'm an annotation as well!

=== "Admonition with annotations"

    ````
    !!! note annotate "Phasellus posuere in sem ut cursus (1)"

        Lorem ipsum dolor sit amet, (2) consectetur adipiscing elit. Nulla et
        euismod nulla. Curabitur feugiat, tortor non consequat finibus, justo
        purus auctor massa, nec semper lorem quam in massa.

    1.  :man_raising_hand: I'm an annotation!
    2.  :woman_raising_hand: I'm an annotation as well!
    ````

    !!! note annotate "Phasellus posuere in sem ut cursus (1)"

        Lorem ipsum dolor sit amet, (2) consectetur adipiscing elit. Nulla et
        euismod nulla. Curabitur feugiat, tortor non consequat finibus, justo
        purus auctor massa, nec semper lorem quam in massa.

    1.  :man_raising_hand: I'm an annotation!
    2.  :woman_raising_hand: I'm an annotation as well!

=== "Content tabs with annotations"

    ````
    === "Tab 1"

        Lorem ipsum dolor sit amet, (1) consectetur adipiscing elit.
        { .annotate }

        1.  :man_raising_hand: I'm an annotation!

    === "Tab 2"

        Phasellus posuere in sem ut cursus (1)
        { .annotate }

        1.  :woman_raising_hand: I'm an annotation as well!
    ````

    === "Tab 1"

        Lorem ipsum dolor sit amet, (1) consectetur adipiscing elit.
        { .annotate }

        1.  :man_raising_hand: I'm an annotation!

    === "Tab 2"

        Phasellus posuere in sem ut cursus (1)
        { .annotate }

        1.  :woman_raising_hand: I'm an annotation as well!

=== "Code annotations"

    ````
    ``` toml
    [project.theme]
    variant = "classic" # (1)!
    features = [
        "content.code.copy", # (2)!
        "navigation.tabs", # (3)!
    ]
    ```

    1.  :material-check: The theme variant must be set to `classic`.
    2.  Adds a copy button to all code blocks.
    3.  Renders top-level navigation as tabs.
    ````

    ``` toml
    [project.theme]
    variant = "classic" # (1)!
    features = [
        "content.code.copy", # (2)!
        "navigation.tabs", # (3)!
    ]
    ```

    1.  :material-check: The theme variant must be set to `classic`.
    2.  Adds a copy button to all code blocks.
    3.  Renders top-level navigation as tabs.
