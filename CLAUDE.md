# CLAUDE.md — Writing (context for sessions here)

This repo (`arian-agrawal/writing`) is Arian's **personal writing corpus**: essays, blog posts,
and theses. Any Claude session started here should inherit this context.

Part of Arian's canonical-homes system (see the `canonical-homes` note in
`~/.claude/projects/-Users-arianagrawal-Arianclaude/memory/`). Sibling homes:
- **Personal notes/wiki:** `~/vaults/personal` (life wiki; capture, people, projects, areas).
- **Work notes/wiki:** `~/vaults/work` (SPC working layer).
- **SPC code:** `~/Dev/spc`, `~/Dev/skills`, `~/Dev/Cowork` (team-owned).
- **SPC data / confidential:** `~/Documents/Work` (local, un-synced).

## Layout

- `essays/` — longer-form pieces on tech and investing.
- `blog/` — blog posts and event recaps.
- `theses/` — ideas and concept explorations.
- `README.md` — human-facing index of pieces.
- `investment-memos/` — **removed from this repo.** SPC investment memos contain non-public deal
  metrics and now live in `~/Documents/Work/investment-memos/` (local, un-synced). Never re-add
  confidential memos here; link out to that path or the system of record instead.

## How to help with writing here

- Match Arian's voice: direct, concrete, opinionated, example-led; short paragraphs; no filler
  or generic AI throat-clearing. Prefer specifics over abstractions.
- New pieces go in the right folder as kebab-case `.md` (e.g. `essays/the-title.md`); add a line
  to `README.md`.
- This is public/publishable writing — keep SPC-confidential specifics out. If a piece needs
  private deal detail, that stays in `~/Documents/Work` and is referenced, not inlined.
- Drafts and half-ideas can be captured in `~/vaults/personal/inbox.md` first, then promoted here
  when they become real pieces.

## Backup

Laptop-only; git → `arian-agrawal/writing` is the backup. Commit + push when a piece is done
(no cloud sync service).
