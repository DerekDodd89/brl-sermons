# BRL Sermon ID Standard and Registry

Status: authoritative; explicitly adopted 2026-09-13. Governs permanent sermon identities and supersedes deferred ID language in BRL 070.002 v2.0. Historical v1.0 and sample IDs remain historical evidence, not allocation authority.

## Architecture

BRL-SER identifies a BRL Sermon resource. Use three-digit numeric components as shown below. A series-container ID is not an individual sermon ID.

| Namespace | Allocation |
|---|---|
| BRL-SER-410.xxx | Derek Dodd / primary BRL individual sermons |
| BRL-SER-411.xxx | Joshua (Josh) Hetrick sermons |
| BRL-SER-412.<series>.<sermon> | Individual sermons belonging to sermon series |
| BRL-SER-412.001 | Hebrews series container |
| BRL-SER-412.002 | Sitting at the Feet of Rabbi Jesus series container |
| BRL-SER-412.003, .004, ... | Available for future explicitly registered series; not yet assigned |
| 413–499 | Reserved/unallocated for future expansion; no meanings assigned |

A permanent ID must never be silently reused or reassigned. Before assignment, check active IDs, reservations, and historical aliases. Record explicit authorization and preserve former permanent IDs as aliases. A legacy series label remains a label even when stored in legacyAliases; its kind is recorded in provenance.identityHistory. Historical aliases are unavailable for unrelated reuse. Preserve original source filenames/bytes and historical metadata. Series sequence remains in metadata independently of folder names.

## Assigned sermon IDs

| Permanent ID | Title | Package path |
|---|---|---|
| BRL-SER-410.001 | The Direction of Worship | sermons/draft/BRL-SER-410.001 - The Direction of Worship |
| BRL-SER-410.002 | The Plan of Salvation | sermons/draft/BRL-SER-410.002 - Plan of Salvation |
| BRL-SER-410.003 | The Law of Death, The Grace of Life | sermons/draft/BRL-SER-410.003 - The Law of Death, The Grace of Life |
| BRL-SER-411.002 | First Corinthians — Chapter One | sermons/draft/BRL-SER-411.002 - First Corinthians Chapter One |
| BRL-SER-411.003 | Are You Watching and Seeking Jesus? | sermons/draft/BRL-SER-411.003 - Are You Watching and Seeking Jesus |
| BRL-SER-411.004 | A Banquet with Jesus | sermons/draft/BRL-SER-411.004 - A Banquet with Jesus |
| BRL-SER-412.001.001 | The Introduction | sermons/draft/hebrews-01-the-introduction |
| BRL-SER-412.001.002 | The Voice of God | sermons/draft/hebrews-02-the-voice-of-god |
| BRL-SER-412.001.003 | Jesus Superior to the Angels | sermons/draft/hebrews-03-jesus-superior-to-the-angels |
| BRL-SER-412.001.004 | Drifting Away | sermons/draft/hebrews-04-drifting-away |
| BRL-SER-412.001.005 | Jesus Superior Humanity | sermons/draft/hebrews-05-jesus-superior-humanity |
| BRL-SER-412.001.006 | Jesus Is Superior to Moses | sermons/draft/hebrews-06-jesus-is-superior-to-moses |
| BRL-SER-412.001.007 | Warning from the Wilderness | sermons/draft/hebrews-07-warning-from-the-wilderness |
| BRL-SER-412.001.008 | Entering the Rest | sermons/draft/hebrews-08-entering-the-rest |
| BRL-SER-412.002.001 | Blessing Life | sermons/draft/BRL-SER-412.002.001 - Blessing Life |
| BRL-SER-412.002.002 | Jesus' Claims of Deity | sermons/draft/BRL-SER-412.002.002 - Jesus' Claims of Deity |
| BRL-SER-412.002.003 | Jesus' Model Prayer | sermons/draft/BRL-SER-412.002.003 - Jesus' Model Prayer |
| BRL-SER-412.002.004 | Passover Lamb | sermons/draft/BRL-SER-412.002.004 - Passover Lamb |
| BRL-SER-412.002.005 | Sitting at the Feet of Jesus | sermons/draft/BRL-SER-412.002.005 - Sitting at the Feet of Jesus |

## Reservations and unresolved identities

- BRL-SER-412.001.009: reserved exclusively for Hebrews sermon 9, Jesus the Superior Priest. NOT assigned to the current package: title/body inconsistency requires review. Its manifest id remains null.
- Getting to Know God: null permanent ID; BRL-S000001 / BRL-S000002 remain unresolved observations, not approved aliases.
- Jesus' Memorial Service: null permanent ID; source contains an assignment placeholder.
- Proper Baptism: outside the current package inventory; historical BRL-S070-0001 evidence remains unresolved. Do not assign BRL-SER-411.001 during this migration. This is not an allocation of 411.001 to Proper Baptism.

## Controlled aliases and mappings

| Historical identifier | Current permanent ID / reservation | Kind |
|---|---|---|
| SER-HEB-001 | BRL-SER-412.001.001 | Legacy series label |
| SER-HEB-002 | BRL-SER-412.001.002 | Legacy series label |
| SER-HEB-003 | BRL-SER-412.001.003 | Legacy series label |
| SER-HEB-004 | BRL-SER-412.001.004 | Legacy series label |
| SER-HEB-005 | BRL-SER-412.001.005 | Legacy series label |
| SER-HEB-006 | BRL-SER-412.001.006 | Legacy series label |
| SER-HEB-007 | BRL-SER-412.001.007 | Legacy series label |
| SER-HEB-008 | BRL-SER-412.001.008 | Legacy series label |
| SER-HEB-009 | BRL-SER-412.001.009 — reserved only; current ID null | Legacy series label |
| SER-RABBI-410.001 | BRL-SER-412.002.001 | Former permanent ID |
| SER-RABBI-410.002 | BRL-SER-412.002.002 | Former permanent ID |
| SER-RABBI-410.003 | BRL-SER-412.002.003 | Former permanent ID |
| SER-RABBI-410.004 | BRL-SER-412.002.004 | Former permanent ID |
| SER-RABBI-410.005 | BRL-SER-412.002.005 | Former permanent ID |

## Website/catalog integration requirement

The Sermon Engine must recursively discover valid 00-metadata/sermon.json manifests from the authoritative top-level sermon repository, within its approved lifecycle folders. It must not scan only 410, 411, 412, or any specific ID block. The unified catalog must support 410, 411, 412, and all future allocated 400-series blocks. ID blocks control classification and identity, not discoverability. Preserve null identities and distinguish reserved IDs from assigned IDs. Series containers are not additional sermon records. Publication/visibility policy is separate from ID discovery. This migration changes no lifecycle or doctrinal/editorial review states.
