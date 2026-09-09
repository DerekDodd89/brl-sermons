# The Law of Death, The Grace of Life

BRL ID: **BRL-SER-410.003** (unchanged). Primary text: Galatians 2:19–21. Status: draft / unreviewed.

This is the Phase 1 reference implementation of BRL 070.002 v2.0. The package directory name and all existing artifact filenames are preserved. The migration reorganizes resources without editing sermon content or assigning a new ID.

## Current resources

- `00-metadata/sermon.json`: authoritative current resource inventory.
- `01-L3-archive/`: one existing DOCX sermon archive.
- `02-L2-pulpit/20-minute/`: one DOCX and two existing page PNGs.
- `02-L2-pulpit/30-minute/`: one DOCX and three existing page PNGs.
- `03-powerpoint/`: **UNAPPROVED MOCKUP — NOT THE FINAL SERMON POWERPOINT**. The transferred PPTX is preserved byte-for-byte and is not approved for publication.
- `04-listener-handouts/`: elementary, middle-school, high-school, and adult PNGs; all remain unapproved.
- `05-supporting-material/phase-1-migration-report.md`: original-to-current paths and SHA-256 verification.

There is no 40-minute L2 resource and no `02-L2-pulpit/40-minute/` directory. A filename containing “Final” is not evidence of review approval. The relationship between existing outline-page PNGs and DOCX revisions has not been editorially verified.

## Historical material retained

`metadata/metadata.md` and `FOLDER-MAP.txt` are unchanged historical records, not the current inventory. The historical 40-minute “Developed” claim and old resource paths are superseded by `00-metadata/sermon.json`. Its PowerPoint availability now reflects the unapproved mockup.

Old `l2/`, `l3/`, `listener-handouts/`, `powerpoint/`, and `exports/` scaffolding and their original .gitkeep files remain because Phase 1 authorizes no cleanup deletion. In particular, the preexisting `l2/40-minute/` placeholder remains historical and does not represent an available variant.

No other sermon, protected source collection, or v1.0 template is migrated by this package. Existing IDs remain unchanged; the permanent ID convention is deferred.
