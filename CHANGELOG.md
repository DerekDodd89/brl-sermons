# BRL Sermons Changelog

This history records repository work; it does not imply that the migrations or cleanup have been committed to Git. Entries are ordered by phase. Dates are omitted where not needed to establish the sequence.

## Initial repository structure

- Initial commit `3e753dd`, "Initial BRL Sermons Module structure," established root documentation and planning-file scaffolding.

## Phase 1 — Galatians v2.0 reference migration

- Added BRL 070.002 v2.0 as the working package standard while preserving v1.0 historically.
- Migrated The Law of Death, The Grace of Life as the reference package, retaining ID `BRL-SER-410.003` and original artifact filenames.
- Accounted for 15 original files: 13 moved artifacts and two historical records retained in place. SHA-256 verification confirmed preservation.
- Recorded the transferred PowerPoint as an unapproved mockup, not the final sermon presentation. The inventory lists only the existing 20- and 30-minute L2 variants.

## Phase 2 — Remaining modern sermon migrations

- Standardized The Direction of Worship, Plan of Salvation, Getting to Know God, and Jesus' Memorial Service into v2.0 packages.
- Preserved 21 original files through 20 moves and one historical metadata file retained in place; original filenames and SHA-256 hashes were verified.
- Added package manifests, READMEs, and old-path-to-new-path migration reports. Preserved DOCX/PDF counterparts and meaningful variants.
- Retained existing IDs. Getting to Know God and Jesus' Memorial Service remain flagged for identity review, without assigned canonical IDs. Resource existence remains separate from approval.

## Phase 3 — Verified repository cleanup

- Audited cleanup candidates before a narrowly approved deletion-only cleanup.
- Removed 42 files: 40 empty .gitkeep placeholders, codex-test.txt, and the hash-confirmed extensionless Constitution duplicate. Retained the matching Constitution DOCX.
- Removed 55 obsolete or empty directories, including superseded sermon scaffolding. No substantive sermon resources were removed.
- Revalidated all five manifests and 36 inventoried resource hashes before and after cleanup. No unexpected files disappeared.
- Preserved legacy collections, Hebrews planning, both package specifications, the nested v1 template, manifests, package READMEs, historical metadata, and migration reports. The locked v1.0 specification was left untouched; its path, size, and modification time were checked, but its content hash could not be checked during cleanup.
