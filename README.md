# BRL Sermons

The permanent BRL Sermons repository preserves sermon archives, preaching outlines, presentations, listener handouts, supporting material, metadata, and legacy sermon sources.

## Current package standard

Newly standardized sermons use **BRL Sermon Package Specification v2.0**:

```text
<sermon-package>/
├── 00-metadata/
│   └── sermon.json
├── 01-L3-archive/
├── 02-L2-pulpit/
├── 03-powerpoint/
├── 04-listener-handouts/
│   ├── elementary/
│   ├── middle-school/
│   ├── high-school/
│   └── adult/
├── 05-supporting-material/
└── README.md
```

**L3** is the fullest sermon archive/exposition. **L2** contains pulpit/preaching outlines, with `20-minute/`, `30-minute/`, and `40-minute/` variants when those resources exist. Handouts may have elementary, middle-school, high-school, and adult variants when available.

Create resource folders only when actual resources exist. The listener-handout audience subfolders shown above are part of the standard organization, not required empty folders: create each ONLY when its corresponding handout exists. Record missing resources in `00-metadata/sermon.json`, rather than creating empty placeholder folders. Manifest resource paths are relative to the package root. Resource existence does not imply approval.

## Sermon lifecycle

- `sermons/draft/`: resources being prepared or standardized.
- `sermons/in-review/`: packages awaiting review.
- `sermons/published/`: packages placed in the publication lifecycle stage.
- `sermons/archived/`: retained archived packages.

Status placement does not itself establish doctrinal or editorial approval. The sermon manifest records review status and publication readiness.

## Current v2.0 packages

| Sermon | Identity | Location |
|---|---|---|
| The Direction of Worship | BRL-SER-410.001 | `sermons/draft/BRL-SER-410.001 - The Direction of Worship/` |
| Plan of Salvation | BRL-SER-410.002 | `sermons/draft/BRL-SER-410.002 - Plan of Salvation/` |
| The Law of Death, The Grace of Life | BRL-SER-410.003 | `sermons/draft/BRL-SER-410.003 - The Law of Death, The Grace of Life/` |
| Getting to Know God | Canonical ID unresolved | `sermons/draft/s02-getting-to-know-god/` |
| Jesus' Memorial Service | Canonical ID unresolved; archived | `sermons/archived/Jesus' Memorial Service/` |

## Listener handout standards

BRL Sermons supports four standardized listener-handout audiences:

```text
04-listener-handouts/
├── elementary/
├── middle-school/
├── high-school/
└── adult/
```

These are distinct resources designed for different audience levels and should not be treated as interchangeable versions of the same handout.

- **Elementary:** age-appropriate, highly visual listener material.
- **Middle School:** more structured engagement, including drawing rather than elementary-style coloring and Context Circle work where applicable.
- **High School:** bridges the middle-school and adult formats, with more mature content and guided/fill-in interaction.
- **Adult:** sermon notes and study-oriented listener material.

Only create an audience folder when a handout for that audience actually exists. The `00-metadata/sermon.json` manifest should identify exactly which listener-handout audiences are available.

Do not infer an audience for an older or unclassified handout. Keep it directly under `04-listener-handouts/` and record it as unclassified until reviewed; do not assign it to an audience folder by guesswork.

## Protected legacy collections

The original Derek Dodd and Josh Hetrick legacy sermon collections are currently stored **outside this repository** as protected source archives. They are intentionally excluded from the active brl-sermons Git repository at this stage. Their protected-source status applies regardless of where they are stored; their current external locations are not prescribed as permanent.

These collections must not be automatically renamed, reorganized, deduplicated, normalized, or deleted. Future legacy-sermon work may import selected sermons into standardized BRL Sermon Package v2.0 packages inside this repository. Importing or standardizing a sermon must not require altering or deleting its preserved external source.

## Series

Series membership and order should ultimately be represented by metadata/indexes rather than duplicate sermon packages. `series/` is reserved for that organization. Existing Hebrews planning under `sermon-series/hebrews/` is protected and has not yet been migrated.

## Standards and provenance

See `docs/standards/`. BRL 070.002 v1.0 is retained historically; v2.0 is the current package specification. The nested v1 template is historical material and has not been replaced with a v2 template.

Migrated packages preserve original filenames and provenance where practical. Package migration reports and SHA-256 inventories verify preservation. Historical metadata may remain even when it describes an older structure; the current v2.0 manifest provides the active resource inventory. Historical migration reports describe their migration-time state.

## Identity and change safety

Do not assign, normalize, or change BRL sermon IDs without deliberate identity review. Record conflicting observed IDs as evidence in metadata rather than silently correcting them.

Repository-wide bulk moves, deletions, ID changes, or protected-archive modifications require explicit review. Preserve sermon content and provenance, and verify resource hashes when reorganizing files. Licensing remains unresolved; the root LICENSE file does not currently supply license terms.
