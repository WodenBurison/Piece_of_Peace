---
title: Example Unrevealed Region
draft: true
tags:
  - world
  - region
---

# Example Unrevealed Region

This page demonstrates the **per-file** exclusion option: it lives in a
normal, otherwise-public folder (`World/Regions/`), but `draft: true` in the
frontmatter tells Quartz's built-in RemoveDrafts filter to leave it out of
the built site.

Use this for a single page that isn't ready yet, rather than moving it into
`Drafts/`. Flip `draft: false` (or delete the line) when it's ready to go
live.

Note the difference from `GM Only/`/`Drafts/`: this file **is** committed to
the repo (nothing here gitignores it), so don't put real secrets in a
draft-tagged file sitting in a public folder — use `GM Only/` for that.
