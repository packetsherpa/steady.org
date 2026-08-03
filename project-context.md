# Steady (steady.org) — Live State

> Live state only: what is in flight, blocked, and next. Durable facts live in
> `.claude/memory/` (see `.claude/memory/MEMORY.md`). Changelog lives in git
> history.

## Goal

Maintain and publish **Steady** (steady.org), Damien DeVille's writing-first
Hugo site for music and personal writing, with a low-friction "write markdown
locally, push to `main`" workflow.

## Active Work

- Live at `https://steady.org/`.
- **Cut down to music on 2026-08-03.** `content/technology/`,
  `archetypes/technology.md`, and `ideas/technology/` are gone; `hugo.toml`,
  `AGENTS.md`, `README.md`, `WRITING.md`, `STYLE.md`, and the about/home copy
  now describe a music-only site. Technology writing lives at
  `packetsherpa.org`. No redirects — Damien deferred them on 2026-08-02 because
  readership is negligible.
- The `egress-filtering-is-the-control-we-never-implemented` note was drafted
  here on 2026-08-01/02, *after* the split, so it was never carried over. It was
  moved to `packetsherpa.org` on 2026-08-03 before the deletion. Its old URL
  (`steady.org/technology/egress-filtering-.../`) now 404s by design.
- Surviving content: two live-show notes (Death Cab for Cutie at Merriweather,
  Stephen Wilson Jr. at Pier Six) and the about page.
- **damiendeville.com is no longer retired.** It was this site's old domain and
  the plan was to drop it; as of 2026-08-03 it serves `packetsherpa.org`'s
  content as a mirror, because DNS filters block that newly registered domain.
  Do not repurpose or release that domain.

## Blockers

- None.

## Next

- Write posts. Music and show notes are the only content type here now.
- Two pre-existing content bugs worth a cleanup pass: the tag `live-mudic`
  (typo for `live-music`) on a show note, and the cover alt text "Stephen
  Willson Jr." (should be "Wilson") in
  `content/music/stephen-wilson-jr-2026-07-25/`. Tags are also inconsistent
  (`show`, `shows`, `concert`).
- Optional polish: a favicon and site OpenGraph image.
