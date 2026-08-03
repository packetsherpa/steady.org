---
name: music-only-since-the-split
description: steady.org is music and personal writing only; technology writing moved to packetsherpa.org and must not come back here.
metadata:
  type: project
---

steady.org was a mixed technology/music/personal site until the split. The
technology writing moved to **Default Deny** (`packetsherpa.org`, also served at
`damiendeville.com`) in two steps:

- 2026-08-02 — `packetsherpa.org` was cloned out of this repo with full history,
  taking the technology notes.
- 2026-08-03 — this repo was cut down: `content/technology/`,
  `archetypes/technology.md`, and `ideas/technology/` deleted, and `hugo.toml`,
  `AGENTS.md`, `README.md`, `WRITING.md`, `STYLE.md`, and the about/home copy
  rewritten for a music-only site.

`content/music/` is now the only post section. Do not add technology notes here.

**No redirects.** Damien decided on 2026-08-02 that readership is too small to
justify them, so the old `steady.org/technology/:slug/` URLs 404. That is
intentional; do not "fix" it by adding aliases.

Landmine worth remembering: the split was not clean. The
`egress-filtering-is-the-control-we-never-implemented` note was drafted *here*
on 2026-08-01/02, after the clone, so it existed only in this repo even though
`packetsherpa.org`'s handoff notes claimed it had been carried over. It was
migrated on 2026-08-03 just before the deletion. If anything else surfaces that
looks like it should be on the other site, check both working trees rather than
trusting either repo's `project-context.md`.

The three files under `ideas/technology/` were deleted too. They are recoverable
from this repo's history and are byte-identical to copies in
`packetsherpa.org`'s history, which deliberately removed them from a public repo
(commit 94208ae, "dont put ideas in a public repo").

See [[site-deploys-from-main]].
