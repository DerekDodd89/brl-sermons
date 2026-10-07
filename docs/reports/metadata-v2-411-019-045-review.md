# Josh Hetrick Metadata V2: BRL-SER-411.019–411.045

Metadata operation date: 2026-10-06 (America/Chicago). Import dates use the established YYYY-MM-DD operation-date convention. No sermon or preaching dates were invented.

After approved cleanup, 24 Metadata V2 JSON records remain (27 originally created), following the current approved BRL-SER-411.001 structure and checked against corrected BRL-SER-411.018. Filenames follow the requested BRL-SER-411-XXX-metadata.json convention. Retained L3 sources remain unchanged. Duplicate sources and metadata in .022, .036, and .042 were deleted with explicit user approval; those numbered folders retain the five standard directories and .gitkeep placeholders. No L2 outlines, handouts, or presentations were created. Nothing committed or pushed.

## Validation

- 24/24 JSON files parse successfully.
- 24/24 recursively match the approved V2 object keys, scalar types, array types, and array-element structures; also match corrected .018.
- 24/24 legacy-sermon resource paths resolve to real DOCX files.
- 24/24 source SHA-256 hashes equal the hashes captured before metadata creation.
- No duplicate IDs or slugs involving these 24 records, including comparison with existing sermon metadata throughout the repository. Where a title slug was already used, an ID suffix provides uniqueness without changing the source title.
- Catalog command attempted after generation: `node .\scripts\sermon-catalog.mjs`. Failed with MODULE_NOT_FOUND because the script is absent from this checkout. No generated catalog was available to check; catalog inclusion remains unverified.

## Review table

| ID | Title | Main Text | Source Filename | Result |
|---|---|---|---|---|
| BRL-SER-411.019 | A BANQUET WITH JESUS | Luke 14:15-24; Deuteronomy 20:5-9 | A BANQUET WITH JESUS.docx | Validated; manually approved for publication |
| BRL-SER-411.020 | A BETTER MINISTRY OF CHRIST | Hebrews 9:11-14 | A BETTER MINISTRY OF CHRIST.docx | V2 created; validated |
| BRL-SER-411.021 | A VISION OF CHRIST | Psalm 22 | A VISION OF CHRIST final.docx | V2 created; validated |
| BRL-SER-411.022 | — | — | — | Recycled; available for future Josh Hetrick sermons |
| BRL-SER-411.023 | CHRIST IN THE HOME | Mark 2:1 | CHRIST IN THE HOME.docx | V2 created; validated |
| BRL-SER-411.024 | CHRIST IN THE PHARISEES HOUSE | Luke 7:36-50 | CHRIST IN THE PHARISEES HOUSE.docx | V2 created; validated |
| BRL-SER-411.025 | CHRIST’S RESURRECTION AND OUR’S IN ROMANS | Romans 1:4; Romans 4:24-25; Romans 6:4-5, 9; Romans 7:4; Romans 8:11; Romans 8:34; Romans 10:9 | CHRIST’S RESURRECTION AND OUR’S IN ROMANS.docx | V2 created; validated |
| BRL-SER-411.026 | A FEW WORDS CONCERNING THE WORD | John 1:1; John 1:14 | Concerning the advent of Christ.docx | V2 created; validated |
| BRL-SER-411.027 | EXCUSES | Luke 14:15-24 | Excuses during the banquet.docx | Validated; manually approved for publication |
| BRL-SER-411.028 | FIVE POINTS OF THE STAR OF JACOB | Numbers 24:17 | five points of the star of jacob.docx | V2 created; validated |
| BRL-SER-411.029 | FIVE WOMEN IN THE GENEALOGY OF JESUS | Matthew 1:3, 5-6, 16 | five women in jesus’ genealogy.docx | Validated; manually approved for publication |
| BRL-SER-411.030 | Healing at the Pool of Bethesda | John 5:1-17 | healing at the pool .docx | V2 created; validated |
| BRL-SER-411.031 | JESUS ACCORDING TO JOHN | John 20:28; John 1:18; John 5:31-40; John 10:14-15 | JESUS ACCORDING TO JOHN.docx | V2 created; validated |
| BRL-SER-411.032 | JESUS, THE GOOD SHEPHERD OF YOUR SOULS | Ezekiel 34:31 | Jesus, The Good Shepherd of your Souls FINAL.docx | V2 created; validated |
| BRL-SER-411.033 | KING OF THE JEWS | Matthew 2:2 | king of the jews.docx | V2 created; validated |
| BRL-SER-411.034 | THE COMPASSION OF JESUS | Matthew 9:36 | THE COMPASSION OF JESUS.docx | V2 created; validated |
| BRL-SER-411.035 | THE “FEAR NOTS” OF JESUS’ NATIVITY IN LUKE | Luke 1:13; Luke 1:30; Luke 2:10 | the fear nots of luke.docx | V2 created; validated |
| BRL-SER-411.036 | — | — | — | Recycled; available for future Josh Hetrick sermons |
| BRL-SER-411.037 | THE MIND OF CHRIST | Philippians 2:5-11 | THE MIND OF CHRIST.docx | V2 created; validated |
| BRL-SER-411.038 | The Penitent Thief | Luke 23:35-43 | THE PENITENT THIEF.docx | V2 created; validated |
| BRL-SER-411.039 | THE RESURRECTION | Acts 2:22-39 | THE RESURRECTION.docx | V2 created; validated |
| BRL-SER-411.040 | THE TRIAL OF CHRIST | Matthew 20:18 | THE TRIAL OF CHRIST.docx | V2 created; validated |
| BRL-SER-411.041 | The Virgin Birth of Jesus | Isaiah 7:14; Matthew 1:18-21; Luke 1:26-27; Luke 1:34 | the virgin birth of Jesus.docx | V2 created; validated |
| BRL-SER-411.042 | — | — | — | Recycled; available for future Josh Hetrick sermons |
| BRL-SER-411.043 | WAITING FOR HIS COMING | Malachi 3:16-17 | WAITING FOR HIS COMING 2.docx | V2 created; validated |
| BRL-SER-411.044 | WHAT WILL YOU DO WITH CHRIST | Matthew 27:22 | WHAT WILL YOU DO WITH CHRIST.docx | Validated; manually approved for publication |
| BRL-SER-411.045 | YOM KIPPUR & THE CROSS | Leviticus 16 | YOM KIPPUR AND THE CROSS.docx | V2 created; validated |

## Source and review warnings

The user manually reviewed .019, .027, .029, and .044 and approved publication despite their brief/incomplete legacy-source format. All 24 retained records now have status published and doctrinalApproval, editorialApproval, and publicationReady true. identityReview.required remains false. The source descriptions below are retained as provenance notes; no publication review remains pending.

- **BRL-SER-411.019:** Incomplete source: title and a single TEXT paragraph containing Scripture and a rabbinic banquet illustration; no developed sermon divisions. Outline intentionally empty; discovery fields are minimal inferences from the supplied material.
- **BRL-SER-411.027:** Incomplete source: blank THESIS and SUBTITILE, one substantive banquet heading, and extensive generic sermon-template placeholders. No missing arguments or conclusion supplied. Proposition uses the actual introduction; question minimally inferred from title and stated text.
- **BRL-SER-411.029:** Incomplete source: TEXT, INTRODUCTION, and CONCLUSION are blank; body contains only five brief entries. Matthew 1 is inferred from the genealogy and supplied verse numbers. Source spelling Rehab retained; no developed argument invented.
- **BRL-SER-411.044:** Source contains an unfinished sentence: “By the divine attestation of his re”. Remaining sermon and conclusion are present. User approved publication with this legacy-source limitation; missing wording has not been reconstructed.

- Confirmed duplicate cleanup: .021, .035, and .041 remain canonical and byte-for-byte unchanged. Duplicate source and metadata files were deleted from .022, .036, and .042. These recycled IDs are available for future Josh Hetrick sermons; no existing sermons were renumbered.
- Byte-identical matches to earlier legacy folders: .019/.004, .020/.005, .023/.007, .024/.008, .025/.009, .026/.010, .027/.011, .028/.012, .029/.013, .030/.014, .031/.015, .032/.016. These are provenance warnings, not duplicate metadata IDs.
- .026 source title is A FEW WORDS CONCERNING THE WORD despite its filename Concerning the advent of Christ.docx; metadata uses the actual source title.
- .027 source title is EXCUSES despite its filename Excuses during the banquet.docx; generic template headings were not represented as sermon arguments.
- .029 preserves the source spelling Rehab and its five actual entries. The blank TEXT field required identifying Matthew 1 from the listed women and verse numbers.
- .031 retains the source claim of five witnesses and its organization; the text explicitly labels four subsequent witnesses after its discussion of Jesus' own testimony. No additional witness was invented.
- .035 retains the unusual source heading FEAR N0T (zero).
- .037 explicitly says it is adapted from Paul Southern's 1938 Abilene lecture; this is source attribution, not a date assigned to Josh's sermon.
- .039 explicitly says it is adapted from a sermon preached by H. Leo Boles.
- .040 contains a source reference/context inconsistency at Luke 22:26 in its trial discussion. It was preserved in the unchanged source; mainText remains the explicitly stated Matthew 20:18.

## Pre-existing repository duplicate warnings

The full sermon-metadata scan found 5 existing duplicate-ID groups and 17 existing duplicate-slug groups outside this batch. They were not modified.

Duplicate IDs: BRL-SER-410.001, BRL-SER-410.003, BRL-SER-411.002, BRL-SER-411.003, BRL-SER-411.004.

Duplicate slugs: the-direction-of-worship, first-corinthians-chapter-one, are-you-watching-and-seeking-jesus, a-banquet-with-jesus, blessing-life, jesus-claims-of-deity, jesus-model-prayer, passover-lamb, sitting-at-the-feet-of-jesus, the-introduction, the-voice-of-god, jesus-superior-to-the-angels, drifting-away, jesus-superior-humanity, jesus-is-superior-to-moses, warning-from-the-wilderness, entering-the-rest.

Full paths and validation results are recorded in metadata-v2-411-019-045-validation.json.

## Approved cleanup verification

- Publication approval applied to .019, .027, .029, and .044; only review flags changed. Their source files are unchanged.
- .022, .036, and .042 contain only 00-metadata, 01-l3, 02-l2, 03-listener-handouts, and 04-presentation, each containing .gitkeep. No source or metadata record remains for these IDs.
- Canonical .021, .035, and .041 metadata and L3 files match their pre-cleanup SHA-256 hashes.
- Every other retained file in .019–.045 matches its pre-cleanup hash. All 24 retained L3 hashes also match the original import-validation evidence.
- All 24 retained records pass both approved V2 structural comparisons and resource checks. No duplicate ID or slug involves a retained record in this batch.
- Catalog inclusion remains unverified: the catalog script is absent from this checkout.
- Nothing committed or pushed.
