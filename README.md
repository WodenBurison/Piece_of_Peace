# Piece of Peace — Campaign Wiki

Player-facing wiki for *Piece of Peace*, built with [Quartz 5](https://quartz.jzhao.xyz)
from an Obsidian vault and deployed to GitHub Pages.

## Editing

Open `content/` directly as your Obsidian vault. That folder is the single
source of truth — nothing else syncs into it.

- `GM Only/` and `Drafts/` are gitignored and excluded from the built site.
  They stay on your machine only. See `../docs/PUBLISHING-AND-PRIVACY.md`.
- Add `draft: true` to a page's frontmatter to keep a single page out of the
  built site without moving it into `Drafts/`.

## Local preview

```
npm i
npx quartz build --serve
```

## Publishing

See `../docs/SETUP.md` for first-time GitHub setup, and
`../docs/PUBLISHING-AND-PRIVACY.md` for how the draft/GM-only exclusion
actually works and what it does and doesn't protect.

Once the repo is connected to GitHub, publish with:

```
npx quartz sync
```
