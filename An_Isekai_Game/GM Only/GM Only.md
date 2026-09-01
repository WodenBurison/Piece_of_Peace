---
title: GM Only
---

# GM Only

Everything under this folder is excluded two ways:

1. Quartz's `ignorePatterns` (in `quartz.config.yaml`) keeps it out of the
   built site, even if it were committed.
2. `.gitignore` keeps it from ever being committed to the repo at all —
   which matters because GitHub Pages on the free tier requires a **public**
   repo, so anything committed is visible to anyone who looks at the repo,
   rendered or not.

Because this folder is gitignored, it has **no git backup**. Back it up
however you'd back up any local-only folder (Obsidian Sync, a separate
private repo, plain file backup) if you want history/redundancy on it.

Suggested subfolders: `NPCs/`, `Factions/`, `Bestiary/`, `Plot/`.
