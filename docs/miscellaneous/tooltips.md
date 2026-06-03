---
tags:
  - Reference
---

# Tooltips

```
[Hover me](https://example.com "I'm a tooltip!")
``` 

[Hover me](https://example.com "I'm a tooltip!")

***

```
[Hover me][example]

  [example]: https://example.com "I'm a tooltip!"
```

[Hover me][example]

  [example]: https://example.com "I'm a tooltip!"

***

``` 
:material-information-outline:{ title="Important information" }
```
:material-information-outline:{ title="Important information" }

***

```
 The HTML specification is maintained by the W3C.

*[HTML]: Hyper Text Markup Language
*[W3C]: World Wide Web Consortium
```

 The HTML specification is maintained by the W3C.

*[HTML]: Hyper Text Markup Language
*[W3C]: World Wide Web Consortium

## Glossary

The Snippets extension can be used to implement a simple glossary by moving all abbreviations in a dedicated file, and auto-append this file to all pages with the following configuration:

```title="includes/abbreviations.md"
*[HTML]: Hyper Text Markup Language
*[W3C]: World Wide Web Consortium
```

It's highly recommended to put the Markdown file containing the abbreviations outside of the docs folder (here, a folder with the name includes is used), as MkDocs might otherwise complain about an unreferenced file. 