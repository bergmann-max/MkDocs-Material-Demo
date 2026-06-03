---
draft: false
date: 2025-06-01
authors:
  - max
categories:
  - General
---

# Welcome to the Demo Blog

This is the first post in the MkDocs Material Demo blog. The blog plugin provides a
full-featured blogging platform integrated directly into your documentation site.

## What the blog plugin offers

- **Posts** with dates, authors, and categories
- **Archive** pages organized by year
- **Categories** for organizing content
- **RSS feeds** for syndication
- **Pagination** for large blogs
- **Drafts** for work-in-progress posts

## Writing a post

Each post is a Markdown file in the `docs/blog/posts/` directory. Frontmatter
controls metadata like the date and author.

```
---
date: 2025-06-01
authors:
  - max
categories:
  - General
---

# Post title

Content goes here...
```

The blog plugin will automatically pick up new posts and add them to the index.
