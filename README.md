# furnace-causalities

The **public, curated milestone log for the Furnace research arc** — the source that backs the project website.

- [`milestones.md`](milestones.md) — reverse-chronological, externally-facing, jargon-defined-inline. This is the canonical file; the website renders from it.

## Why this is its own repo
Milestones used to live inside `PRI_at_commitment/milestones.md`. As the work moved off that repo (the morphology line now lives in `t0-morphology-furnace`, with `PRI_at_commitment` as the PRI-detection trunk), the milestone log was pulled out into this dedicated repo so the website has a stable, method-agnostic home to point at — independent of any single code repo's lifecycle.

## Relationship to the research vault
The Obsidian research vault (`the_GOAT`) symlinks `wiki/milestones.md` → this repo's `milestones.md`, so curated milestone entries written from the vault land here. Raw internal session notes stay in the vault's append-only `wiki/log.md`; this file is the sparse, public-facing curation.

## Conventions
- One entry per shipped milestone (sparse — not every session).
- `### YYYY-MM-DD — short headline`, newest at top.
- Externally accessible tone; define jargon inline.
