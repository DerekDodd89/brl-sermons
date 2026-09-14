# Permanent ID architecture migration — 2026-09-13

Explicitly authorized migration. No staging, commit, or push. Only five Rabbi package folders were renamed; descriptive Hebrews folders remain unchanged. Earlier import reports retain historical paths.

Verification: 22 manifests resolve; 70 inventoried resources match; 19 unique assigned sermon IDs; 3 null IDs. BRL-SER-412.001.009 is reserved only. Every pre-existing file is accounted for under the mapping. Files outside the authorized manifest/README/spec changes match their pre-migration SHA-256.

## Package mapping

| Old folder | New folder | Previous ID | New ID |
|---|---|---|---|
| sermons/draft/hebrews-01-the-introduction | sermons/draft/hebrews-01-the-introduction | null | BRL-SER-412.001.001 |
| sermons/draft/hebrews-02-the-voice-of-god | sermons/draft/hebrews-02-the-voice-of-god | null | BRL-SER-412.001.002 |
| sermons/draft/hebrews-03-jesus-superior-to-the-angels | sermons/draft/hebrews-03-jesus-superior-to-the-angels | null | BRL-SER-412.001.003 |
| sermons/draft/hebrews-04-drifting-away | sermons/draft/hebrews-04-drifting-away | null | BRL-SER-412.001.004 |
| sermons/draft/hebrews-05-jesus-superior-humanity | sermons/draft/hebrews-05-jesus-superior-humanity | null | BRL-SER-412.001.005 |
| sermons/draft/hebrews-06-jesus-is-superior-to-moses | sermons/draft/hebrews-06-jesus-is-superior-to-moses | null | BRL-SER-412.001.006 |
| sermons/draft/hebrews-07-warning-from-the-wilderness | sermons/draft/hebrews-07-warning-from-the-wilderness | null | BRL-SER-412.001.007 |
| sermons/draft/hebrews-08-entering-the-rest | sermons/draft/hebrews-08-entering-the-rest | null | BRL-SER-412.001.008 |
| sermons/draft/hebrews-09-jesus-the-superior-priest | sermons/draft/hebrews-09-jesus-the-superior-priest | null | null; .009 reserved |
| sermons/draft/SER-RABBI-410.001 - Blessing Life | sermons/draft/BRL-SER-412.002.001 - Blessing Life | SER-RABBI-410.001 | BRL-SER-412.002.001 |
| sermons/draft/SER-RABBI-410.002 - Jesus' Claims of Deity | sermons/draft/BRL-SER-412.002.002 - Jesus' Claims of Deity | SER-RABBI-410.002 | BRL-SER-412.002.002 |
| sermons/draft/SER-RABBI-410.003 - Jesus' Model Prayer | sermons/draft/BRL-SER-412.002.003 - Jesus' Model Prayer | SER-RABBI-410.003 | BRL-SER-412.002.003 |
| sermons/draft/SER-RABBI-410.004 - Passover Lamb | sermons/draft/BRL-SER-412.002.004 - Passover Lamb | SER-RABBI-410.004 | BRL-SER-412.002.004 |
| sermons/draft/SER-RABBI-410.005 - Sitting at the Feet of Jesus | sermons/draft/BRL-SER-412.002.005 - Sitting at the Feet of Jesus | SER-RABBI-410.005 | BRL-SER-412.002.005 |

## Changed metadata/documentation hashes

```json
[
  {
    "oldPath": "docs/standards/BRL 070.002 - Sermon Package Specification v2.0.md",
    "newPath": "docs/standards/BRL 070.002 - Sermon Package Specification v2.0.md",
    "beforeSha256": "9fe665516656da8b7a7112802d1f10f6db2f527dc5cdeb09dfd0fca97db3b40c",
    "afterSha256": "1615b0942f0b70858456fe3097892522e3d4ef3130675fe3b4e74476377079ca"
  },
  {
    "oldPath": "sermons/draft/hebrews-01-the-introduction/00-metadata/sermon.json",
    "newPath": "sermons/draft/hebrews-01-the-introduction/00-metadata/sermon.json",
    "beforeSha256": "a140b8479434fee8cc2d80f121ef8734fac4213b2308e8a988c6964947c47876",
    "afterSha256": "d862053bfe2fcfcaa186f1f7b06260ae4c0b3bc8168a847f4f389fd6b6042241"
  },
  {
    "oldPath": "sermons/draft/hebrews-01-the-introduction/README.md",
    "newPath": "sermons/draft/hebrews-01-the-introduction/README.md",
    "beforeSha256": "6886339ad7b12b503f1046b5f9423172003c6401d28a3d671bdbe9bf865f5c5e",
    "afterSha256": "9461c055227116b1262f76f8fd16da895d240c600432246e7cdc214dd78758f8"
  },
  {
    "oldPath": "sermons/draft/hebrews-02-the-voice-of-god/00-metadata/sermon.json",
    "newPath": "sermons/draft/hebrews-02-the-voice-of-god/00-metadata/sermon.json",
    "beforeSha256": "4b3a2d0847af747428e75915cb1dc6cb8f28c400a68a9d4d8b204c0abc01b4d3",
    "afterSha256": "c2357d841de31da329f5baacef5c0384f071a3c4ab592fcd767aeb5e2ed7a6eb"
  },
  {
    "oldPath": "sermons/draft/hebrews-02-the-voice-of-god/README.md",
    "newPath": "sermons/draft/hebrews-02-the-voice-of-god/README.md",
    "beforeSha256": "2a9580256de0f31e1adfd565c42322a7ea798ff1b082c74a3d1a6a08e5bfbd49",
    "afterSha256": "b0b72c3ed65f68ec57fe97fa29a34b6a39d9eb623fb98888b9a13df882acdc18"
  },
  {
    "oldPath": "sermons/draft/hebrews-03-jesus-superior-to-the-angels/00-metadata/sermon.json",
    "newPath": "sermons/draft/hebrews-03-jesus-superior-to-the-angels/00-metadata/sermon.json",
    "beforeSha256": "fefd6dbfefd93af050a1db1202aec6cbae143429542472d90226c02a8e2e63a7",
    "afterSha256": "cb2ccb8f6b84d1ecb962447001aa96c813a78b605e8b511e98637acc83afd650"
  },
  {
    "oldPath": "sermons/draft/hebrews-03-jesus-superior-to-the-angels/README.md",
    "newPath": "sermons/draft/hebrews-03-jesus-superior-to-the-angels/README.md",
    "beforeSha256": "7188be18ce08bf613c3508c3b8f9749e39303523fe12aa02670d48db8e4ec679",
    "afterSha256": "071e5ffb29f65c5e2c228ff57321986dff833626325e1726f03cb31271b0aa05"
  },
  {
    "oldPath": "sermons/draft/hebrews-04-drifting-away/00-metadata/sermon.json",
    "newPath": "sermons/draft/hebrews-04-drifting-away/00-metadata/sermon.json",
    "beforeSha256": "cb7ceb8ebe05ef159f3cd3faa50d8915337324ed61c8a62c3b39ef19f224fb23",
    "afterSha256": "4f3debcb0a92b32517c2e78e8080b8b1aeabf67d192b0bcc5a3c8463785b0b08"
  },
  {
    "oldPath": "sermons/draft/hebrews-04-drifting-away/README.md",
    "newPath": "sermons/draft/hebrews-04-drifting-away/README.md",
    "beforeSha256": "577b539da6e6b491622359bba51f05b456e63f92d5b3400c366c068ce1755d22",
    "afterSha256": "ad2f485e835fd86963054e4c64d8e061a50c62f4ffd07bb894f8d5ce905e8b19"
  },
  {
    "oldPath": "sermons/draft/hebrews-05-jesus-superior-humanity/00-metadata/sermon.json",
    "newPath": "sermons/draft/hebrews-05-jesus-superior-humanity/00-metadata/sermon.json",
    "beforeSha256": "3325c1398493d4c9e33619a53239818ea6351d2eea897f1b851e10598f7bf547",
    "afterSha256": "f2188c0ac6caf9f49064cd6df3ba4dc1a75779dd15d7c7ae6bb59c999ff852ae"
  },
  {
    "oldPath": "sermons/draft/hebrews-05-jesus-superior-humanity/README.md",
    "newPath": "sermons/draft/hebrews-05-jesus-superior-humanity/README.md",
    "beforeSha256": "b78cf03443dc2ba764753a6754be4e85d9f1f83a5235032cca84cdfdf55fd8a1",
    "afterSha256": "9f7c52b441b7662e31578e90e0f6a0f449824364ba2d08b814c289fb49ecc39c"
  },
  {
    "oldPath": "sermons/draft/hebrews-06-jesus-is-superior-to-moses/00-metadata/sermon.json",
    "newPath": "sermons/draft/hebrews-06-jesus-is-superior-to-moses/00-metadata/sermon.json",
    "beforeSha256": "4da03ec3b27764381b8073483a5734b7c99de986dd9da038fd40879dad50efae",
    "afterSha256": "c6604621e2044e6ccbc11ca62c7bc9c34971d2788f13953f8a719277da4f4bb3"
  },
  {
    "oldPath": "sermons/draft/hebrews-06-jesus-is-superior-to-moses/README.md",
    "newPath": "sermons/draft/hebrews-06-jesus-is-superior-to-moses/README.md",
    "beforeSha256": "cc6978f051a2dcc7f7f49ad8a67887529422621c9cf7e21b4758428a6c845f38",
    "afterSha256": "728882439b9c140763f9fdf9e0239e9b31416a39ecbc0b383b06764a43bf944c"
  },
  {
    "oldPath": "sermons/draft/hebrews-07-warning-from-the-wilderness/00-metadata/sermon.json",
    "newPath": "sermons/draft/hebrews-07-warning-from-the-wilderness/00-metadata/sermon.json",
    "beforeSha256": "bcd0cdd957957a3a5d22d205812f2639d9d3df984490dac102564afb1c3431d0",
    "afterSha256": "92bfc00ea57ce549f9050f35d4932f678ca384e969f00a5178f3d61cd4bba5c8"
  },
  {
    "oldPath": "sermons/draft/hebrews-07-warning-from-the-wilderness/README.md",
    "newPath": "sermons/draft/hebrews-07-warning-from-the-wilderness/README.md",
    "beforeSha256": "298831734a02f48b74cc3752b1fae33a0d1c9abf220c9fdb41ea4e29bf28b49e",
    "afterSha256": "8764428608e302cdded5614d35108fe7997e392447642c279d5a078210a5bd93"
  },
  {
    "oldPath": "sermons/draft/hebrews-08-entering-the-rest/00-metadata/sermon.json",
    "newPath": "sermons/draft/hebrews-08-entering-the-rest/00-metadata/sermon.json",
    "beforeSha256": "d16e822568b22ce818f03aa802856e1728da592eaf5c8b5c0630ca28ce0ccd6d",
    "afterSha256": "efda85442cfae4971e5dc9cf8364cab889ce072db8c3df923adc2d5e7364beb1"
  },
  {
    "oldPath": "sermons/draft/hebrews-08-entering-the-rest/README.md",
    "newPath": "sermons/draft/hebrews-08-entering-the-rest/README.md",
    "beforeSha256": "117b9bf7ad35160b1cc6b76c9f608d2f8d5191e71c1a5cff3ce4baaad30c3298",
    "afterSha256": "b7939922f73dee705e2afaf70223661c18a88778c31c0fc9a70f1ce164081285"
  },
  {
    "oldPath": "sermons/draft/hebrews-09-jesus-the-superior-priest/00-metadata/sermon.json",
    "newPath": "sermons/draft/hebrews-09-jesus-the-superior-priest/00-metadata/sermon.json",
    "beforeSha256": "99a7a3987f74726d3b34638f0bd19b765762ccaa35a407e607f06e894b4f145b",
    "afterSha256": "bfc3308f9e36f99430ac5379e7c24d94f34801a4b87f9dfef9ef679784abe4ac"
  },
  {
    "oldPath": "sermons/draft/hebrews-09-jesus-the-superior-priest/README.md",
    "newPath": "sermons/draft/hebrews-09-jesus-the-superior-priest/README.md",
    "beforeSha256": "725a35b5d094d6ad4c17ced1ac8528a4798acb8d768402e542feb435a91177c4",
    "afterSha256": "1cfa56e6054a6a88ed025534249360bcaaa4c1a2e30edb4a837b620bfe6074c4"
  },
  {
    "oldPath": "sermons/draft/SER-RABBI-410.001 - Blessing Life/00-metadata/sermon.json",
    "newPath": "sermons/draft/BRL-SER-412.002.001 - Blessing Life/00-metadata/sermon.json",
    "beforeSha256": "2175f630244f7ebaf4681f649a88900259bd56a762d6133271b745d2600ef3a8",
    "afterSha256": "7e675351bcf29a05298b3a5100e71d276ecba7321eda893f962805c23187ad64"
  },
  {
    "oldPath": "sermons/draft/SER-RABBI-410.001 - Blessing Life/README.md",
    "newPath": "sermons/draft/BRL-SER-412.002.001 - Blessing Life/README.md",
    "beforeSha256": "3512e4e402af79c5eee2e59478aaac0846746dbcdde602a4e3ac44fc394cc432",
    "afterSha256": "91b43c457e71e8766df0e9e31f630d0d0b678ce363ed9f763d9105853800bb17"
  },
  {
    "oldPath": "sermons/draft/SER-RABBI-410.002 - Jesus' Claims of Deity/00-metadata/sermon.json",
    "newPath": "sermons/draft/BRL-SER-412.002.002 - Jesus' Claims of Deity/00-metadata/sermon.json",
    "beforeSha256": "78d84616dbce481b2514da39b94c46fafb110d164cf4a828492f50b83a4bd429",
    "afterSha256": "35b01af0585b9401da25d7cb924192f819af8a9ec43a14deb60177b849f62e23"
  },
  {
    "oldPath": "sermons/draft/SER-RABBI-410.002 - Jesus' Claims of Deity/README.md",
    "newPath": "sermons/draft/BRL-SER-412.002.002 - Jesus' Claims of Deity/README.md",
    "beforeSha256": "cabdca93569284e20ef391fc70e6429564222d727b835274d8ecef5e5f02224e",
    "afterSha256": "9ea698200b5fe477e7e18f7551ae32467300feacc0935d2c80c986a3c44fb24c"
  },
  {
    "oldPath": "sermons/draft/SER-RABBI-410.003 - Jesus' Model Prayer/00-metadata/sermon.json",
    "newPath": "sermons/draft/BRL-SER-412.002.003 - Jesus' Model Prayer/00-metadata/sermon.json",
    "beforeSha256": "291381b0429a1e9e7a99054b3e1eb33ec73ba6e5a564f7d584756b155f4baead",
    "afterSha256": "5fee21b266cbd390f9add73ebf2e108a5028ec803a5054f6c119809d07a46c10"
  },
  {
    "oldPath": "sermons/draft/SER-RABBI-410.003 - Jesus' Model Prayer/README.md",
    "newPath": "sermons/draft/BRL-SER-412.002.003 - Jesus' Model Prayer/README.md",
    "beforeSha256": "bae0190ed41972b576270f67e0a40874d79dff2a80afd49f5b95c632d4803362",
    "afterSha256": "0f2cb23a7f575f2ddf0dcf2a74fe61be4952e57e8291dfc6fae976e5eddfc3d0"
  },
  {
    "oldPath": "sermons/draft/SER-RABBI-410.004 - Passover Lamb/00-metadata/sermon.json",
    "newPath": "sermons/draft/BRL-SER-412.002.004 - Passover Lamb/00-metadata/sermon.json",
    "beforeSha256": "3e8938b2e0cf6b935a26477a5de8162f7fa374b12557ce990e074f66e75a4d28",
    "afterSha256": "4e1cda1223f5c75f51dd0fe93ec7e3c078234f8b485644738cdd26fec5b6bf38"
  },
  {
    "oldPath": "sermons/draft/SER-RABBI-410.004 - Passover Lamb/README.md",
    "newPath": "sermons/draft/BRL-SER-412.002.004 - Passover Lamb/README.md",
    "beforeSha256": "93e9b96ba321c8783898d079852361c5e4af9ca9b45c010e1f38fe3b33eefe4e",
    "afterSha256": "8dd311d100aa49b4f0c83454acea2432c85a87a46d5cd92c1922ed87585b05be"
  },
  {
    "oldPath": "sermons/draft/SER-RABBI-410.005 - Sitting at the Feet of Jesus/00-metadata/sermon.json",
    "newPath": "sermons/draft/BRL-SER-412.002.005 - Sitting at the Feet of Jesus/00-metadata/sermon.json",
    "beforeSha256": "dc2fb4c1c685f055356cd2870d8281cb3f3271c44ff3261a1a5d3e596c2b40c3",
    "afterSha256": "185d6e5e6b344d9edc58e08d616b2bce4ec213c119d5afafbdc8220d18cdef91"
  },
  {
    "oldPath": "sermons/draft/SER-RABBI-410.005 - Sitting at the Feet of Jesus/README.md",
    "newPath": "sermons/draft/BRL-SER-412.002.005 - Sitting at the Feet of Jesus/README.md",
    "beforeSha256": "fbb855ef2e6aeeb5819549f7c561658f0e7dac6edc77f1b721f4c7d452a8a8b2",
    "afterSha256": "1b46ab24651c7779e6f1d0941a570621f201492f0e24411c1919bb9638777d8a"
  }
]
```

## Verified resource inventory

```json
[
  {
    "path": "sermons/archived/Jesus' Memorial Service/01-L3-archive/Jesus' Memorial Service.docx",
    "sha256": "365c9a9d5c8aa4f0e6f9180ed2112b6d0d6b716a0bf851078e7a97051e9b6759",
    "bytes": 22760
  },
  {
    "path": "sermons/draft/BRL-SER-410.001 - The Direction of Worship/05-supporting-material/BRL-SER-410.001 - The Direction of Worship L3 - Archive Metadata & Repository Export.docx",
    "sha256": "bedd3a55b3e735bbcd5029de88d0f367f74ea7542ff1a2e7f042c9d0ae0c0a9b",
    "bytes": 21611
  },
  {
    "path": "sermons/draft/BRL-SER-410.001 - The Direction of Worship/01-L3-archive/BRL-SER-410.001 - The Direction of Worship L3 - Sermon Archive Section II Prayer.docx",
    "sha256": "28faecac3211c42bffa191a67c4a4c085ba4e5bc2c080aa512f415733e852058",
    "bytes": 19671
  },
  {
    "path": "sermons/draft/BRL-SER-410.001 - The Direction of Worship/01-L3-archive/BRL-SER-410.001 - The Direction of Worship L3 - Sermon Archive Section III Singing.docx",
    "sha256": "a48ba41b72e356a73d82f6caa23373db1a0cbb6c213a2d65abeedde4865d04db",
    "bytes": 19823
  },
  {
    "path": "sermons/draft/BRL-SER-410.001 - The Direction of Worship/01-L3-archive/BRL-SER-410.001 - The Direction of Worship L3 - Sermon Archive Section IV The Lord's Supper.docx",
    "sha256": "5fd5869e499a14733528052fcaf475df1ad495a99d23b1d07bf4016f420c88bb",
    "bytes": 20720
  },
  {
    "path": "sermons/draft/BRL-SER-410.001 - The Direction of Worship/01-L3-archive/BRL-SER-410.001 - The Direction of Worship L3 - Sermon Archive Section V The Collection.docx",
    "sha256": "d879ab6bcc05200443b10e06affc736316af20b8c2bc143a8840b7f4863a2cdc",
    "bytes": 19652
  },
  {
    "path": "sermons/draft/BRL-SER-410.001 - The Direction of Worship/01-L3-archive/BRL-SER-410.001 - The Direction of Worship L3 - Sermon Archive Section VI The Word of God.docx",
    "sha256": "ce287bca5ae5fbb9d4691b5bd56aa8cef9468b7d29fbe9277e12525d766eb11d",
    "bytes": 20273
  },
  {
    "path": "sermons/draft/BRL-SER-410.001 - The Direction of Worship/01-L3-archive/BRL-SER-410.001 - The Direction of Worship L3 - Sermon Archive Section VII The Unity of Worship.docx",
    "sha256": "5b522a4e2d5111e143ae8537b5e7835dcd6dedb7e7601c984120ef4e0cb338f5",
    "bytes": 19682
  },
  {
    "path": "sermons/draft/BRL-SER-410.001 - The Direction of Worship/01-L3-archive/BRL-SER-410.001 - The Direction of Worship L3 - Sermon Archive.docx",
    "sha256": "8bb3cdf953b47566a31ebad137cf0fecd49cb22dada0ec41c589225cd8d39c99",
    "bytes": 18049
  },
  {
    "path": "sermons/draft/BRL-SER-410.002 - Plan of Salvation/04-listener-handouts/BRL-SER-410.002_The-Plan-of-Salvation_Handout_V1.0.pdf",
    "sha256": "1958efb4d3dd7610111487ecf6e648f9bba8257c317de6a1d637df3c74c9c35e",
    "bytes": 2256915
  },
  {
    "path": "sermons/draft/BRL-SER-410.002 - Plan of Salvation/01-L3-archive/BRL-SER-410.002_The-Plan-of-Salvation_L3-Archive_V1.0.docx",
    "sha256": "136c2862b9378b95f08ee5a353e6962348ffe8971d3f980505f6d9c379a9b7c3",
    "bytes": 45686
  },
  {
    "path": "sermons/draft/BRL-SER-410.002 - Plan of Salvation/01-L3-archive/BRL-SER-410.002_The-Plan-of-Salvation_L3-Archive_V1.0.pdf",
    "sha256": "0120e0f91699d21c1335d0d2ddff1327fc9b87ac21b32e0a1e9316c2bb0ed015",
    "bytes": 244360
  },
  {
    "path": "sermons/draft/BRL-SER-410.002 - Plan of Salvation/02-L2-pulpit/20-minute/BRL_Plan_of_Salvation_L2_20_Minute_Pulpit_Outline_V1.0.pdf",
    "sha256": "6abee9ef92f4911006074b829eba1fb61a815e29f147f2b7555c8efd9b34a057",
    "bytes": 6899
  },
  {
    "path": "sermons/draft/BRL-SER-410.002 - Plan of Salvation/02-L2-pulpit/30-minute/BRL_Plan_of_Salvation_L2_30_Minute_Pulpit_Outline_V1.0.pdf",
    "sha256": "4894b58b424cad098589b0f5c1ed2863d0aabaddff98464074c097110fac2232",
    "bytes": 9314
  },
  {
    "path": "sermons/draft/BRL-SER-410.002 - Plan of Salvation/02-L2-pulpit/40-minute/BRL_Plan_of_Salvation_L2_40_Minute_Advanced_Pulpit_Outline_V1.0.pdf",
    "sha256": "472ab572805f8f802fac3509310d271c372ab38b497cc140d8b9351d7e6b7571",
    "bytes": 13924
  },
  {
    "path": "sermons/draft/BRL-SER-410.002 - Plan of Salvation/metadata.json",
    "sha256": "0bb2b4cd340504404412821ba485fbd08c306b785e33a4fac24ec2de96bc9e8f",
    "bytes": 2008
  },
  {
    "path": "sermons/draft/BRL-SER-410.003 - The Law of Death, The Grace of Life/FOLDER-MAP.txt",
    "sha256": "163c4274bd5ec21b8cef3a5af9ffab5a2046fce87c1bd09e85c9d98b6e8c93b0",
    "bytes": 473
  },
  {
    "path": "sermons/draft/BRL-SER-410.003 - The Law of Death, The Grace of Life/02-L2-pulpit/20-minute/BRL-SER-410.003_L2_20-Minute_Pulpit_Outline.docx",
    "sha256": "e4e886783cf3e3d2134202f7505d4a9c308e2142c426ec467b9ae9d76f805b34",
    "bytes": 39667
  },
  {
    "path": "sermons/draft/BRL-SER-410.003 - The Law of Death, The Grace of Life/02-L2-pulpit/20-minute/Page 1.png",
    "sha256": "35c26b3aa9033d1a0a230da006da845de3368e5d42205957d880bfd20bcd0781",
    "bytes": 2033122
  },
  {
    "path": "sermons/draft/BRL-SER-410.003 - The Law of Death, The Grace of Life/02-L2-pulpit/20-minute/Page 2.png",
    "sha256": "2d9ea6b688e2d1258667b3f8d2372253f01c336d6a2303c7cf053a89f2edee52",
    "bytes": 1930994
  },
  {
    "path": "sermons/draft/BRL-SER-410.003 - The Law of Death, The Grace of Life/02-L2-pulpit/30-minute/BRL-SER-410.003_L2_30-Minute_Pulpit_Outline_3-Page-Final.docx",
    "sha256": "0181f088e15ba2b353ba7ae540e952421e3a4cdb18095f424d30062810277df5",
    "bytes": 40145
  },
  {
    "path": "sermons/draft/BRL-SER-410.003 - The Law of Death, The Grace of Life/02-L2-pulpit/30-minute/Page 1.png",
    "sha256": "0ca450227b4fa9ca7247eda7c466dc8c2986217ba4affc79b9c4657c8fe7eb9f",
    "bytes": 1968597
  },
  {
    "path": "sermons/draft/BRL-SER-410.003 - The Law of Death, The Grace of Life/02-L2-pulpit/30-minute/Page 2.png",
    "sha256": "431b3323e3a32cd153bb89e40e8872a065fdba0c763c9a0fbd571405abab1192",
    "bytes": 1862907
  },
  {
    "path": "sermons/draft/BRL-SER-410.003 - The Law of Death, The Grace of Life/02-L2-pulpit/30-minute/Page 3.png",
    "sha256": "f6d3bdd770997c08258eeb508433d2b6a5be50fed35f3fcd043170ec48b73575",
    "bytes": 2010994
  },
  {
    "path": "sermons/draft/BRL-SER-410.003 - The Law of Death, The Grace of Life/01-L3-archive/BRL_L3_The_Law_of_Death_The_Grace_of_Life.docx",
    "sha256": "7c8da6a7500fc7ca33467e2848ce9b803a4e09b2f7e2af9dbed35d58267b48e9",
    "bytes": 47035
  },
  {
    "path": "sermons/draft/BRL-SER-410.003 - The Law of Death, The Grace of Life/04-listener-handouts/adult/Adult Handout Rev. 1.png",
    "sha256": "c70ce7efab9361c2c0c34b3582b0ccc68af31dc762642265944509a378bbb96e",
    "bytes": 1640672
  },
  {
    "path": "sermons/draft/BRL-SER-410.003 - The Law of Death, The Grace of Life/04-listener-handouts/elementary/Elementary Listener Handout Rev. 1.png",
    "sha256": "b28cbc89e3f5c15f335933ea08193686b373fd8063e1fe66851fa29208aad1d9",
    "bytes": 1944563
  },
  {
    "path": "sermons/draft/BRL-SER-410.003 - The Law of Death, The Grace of Life/04-listener-handouts/high-school/High School Handout Rev. 1.png",
    "sha256": "69064c0be0b6f8c777a803521add58157479421dfa3363f5b05ced8da47fce9e",
    "bytes": 1784425
  },
  {
    "path": "sermons/draft/BRL-SER-410.003 - The Law of Death, The Grace of Life/04-listener-handouts/middle-school/Middle School Handout Rev. 1.png",
    "sha256": "82151bae4357f573fe93bac0bc5496beb5675a5feaa1f10c1acb242b0a22f83a",
    "bytes": 1857493
  },
  {
    "path": "sermons/draft/BRL-SER-410.003 - The Law of Death, The Grace of Life/metadata/metadata.md",
    "sha256": "990cd162312f7c1ca00bf2d579650af7394528811b516db15ce697f19c53cad0",
    "bytes": 4252
  },
  {
    "path": "sermons/draft/BRL-SER-410.003 - The Law of Death, The Grace of Life/03-powerpoint/BRL_Galatians_2_19-21_Law_of_Death_Grace_of_Life_PPT_Mockup.pptx",
    "sha256": "604ce5774e74c7b7cbecd207792e64c430a58bef92dcc544039dc4609e71728f",
    "bytes": 40173
  },
  {
    "path": "sermons/draft/BRL-SER-411.002 - First Corinthians Chapter One/05-supporting-material/legacy-source/1 Cor_1.docx",
    "sha256": "3018ad296379aca3c4bca7c8a54c1e5fbc8e5d46aec35e60444b86815f167129",
    "bytes": 30131
  },
  {
    "path": "sermons/draft/BRL-SER-411.002 - First Corinthians Chapter One/00-metadata/library-source/library-version-evidence.json",
    "sha256": "6786003700773b9f2732976b96aca15c3721a1ba56ec225404c00aa766dd9d5f",
    "bytes": 767
  },
  {
    "path": "sermons/draft/BRL-SER-411.003 - Are You Watching and Seeking Jesus/05-supporting-material/legacy-source/ARE YOU WATCHING AND SEEKING JESUS.docx",
    "sha256": "cc504c3942a326045f80694ac8d7250c13de7b7e8c8902dc92624c9a8ddba208",
    "bytes": 18865
  },
  {
    "path": "sermons/draft/BRL-SER-411.003 - Are You Watching and Seeking Jesus/00-metadata/library-source/library-version-evidence.json",
    "sha256": "206ee096ee7e08fc98dc7820f8ec3f759dceb5c00f53901ce9a5cb2db775644b",
    "bytes": 826
  },
  {
    "path": "sermons/draft/BRL-SER-411.004 - A Banquet with Jesus/05-supporting-material/legacy-source/A BANQUET WITH JESUS.docx",
    "sha256": "bf5b75c4feb99f7dca39c9e9f2fd0b87c4b751a44bbcd8e76f4273a6745ccb72",
    "bytes": 14921
  },
  {
    "path": "sermons/draft/BRL-SER-411.004 - A Banquet with Jesus/00-metadata/library-source/sermon.json",
    "sha256": "51f272c901b6d8de04018ad41925603d4fc19b6daeec138950600f81bcb74aff",
    "bytes": 1870
  },
  {
    "path": "sermons/draft/BRL-SER-412.002.001 - Blessing Life/05-supporting-material/legacy-source/blessing life (1).pptx",
    "sha256": "ada8885a55448e8b30cc7d023b6105eb9bd975fdf96c721f5b19ec3af198c5b0",
    "bytes": 553940
  },
  {
    "path": "sermons/draft/BRL-SER-412.002.001 - Blessing Life/00-metadata/library-source/blessing-life_metadata.json",
    "sha256": "eeeb6036ed2c36cb12dc9005de57d332610a2d8fd21487eea9ee535727ec4ad2",
    "bytes": 1963
  },
  {
    "path": "sermons/draft/BRL-SER-412.002.002 - Jesus' Claims of Deity/05-supporting-material/legacy-source/Jesus Claims of Diety (1).pptx",
    "sha256": "67237d08bfc5b0d72979e9b683299fbfa23451f8aba3431b5c2dc7aefe7d5213",
    "bytes": 380800
  },
  {
    "path": "sermons/draft/BRL-SER-412.002.002 - Jesus' Claims of Deity/00-metadata/library-source/jesus-claims-of-deity_metadata.json",
    "sha256": "1d6e24dd41f1798461d98a6b8c14f62e5138af0ff9ff176edceaad11c0cb67bc",
    "bytes": 2137
  },
  {
    "path": "sermons/draft/BRL-SER-412.002.003 - Jesus' Model Prayer/05-supporting-material/legacy-source/JESUS' MODEL PRAYER (1).pptx",
    "sha256": "741880add8adb56253aaa780c71d15aaa005cb9837bc2abadf2735ddfee1739d",
    "bytes": 312515
  },
  {
    "path": "sermons/draft/BRL-SER-412.002.003 - Jesus' Model Prayer/00-metadata/library-source/jesus-model-prayer_metadata.json",
    "sha256": "987ad84c7d6aa89e8dec4813aa7f43d4733069eee58d8cf93b44e235d9ba78e9",
    "bytes": 2248
  },
  {
    "path": "sermons/draft/BRL-SER-412.002.004 - Passover Lamb/05-supporting-material/legacy-source/Passover Lamb (1).pptx",
    "sha256": "736e37a18451ef2fcefa99eadf1044a972282c518eaaf0c7c5e75ca9390a7f1a",
    "bytes": 650031
  },
  {
    "path": "sermons/draft/BRL-SER-412.002.004 - Passover Lamb/00-metadata/library-source/passover-lamb_metadata.json",
    "sha256": "33edb9337a5ef9a4f70944ddf3c4dbf9da79abc6fba33bc4e67046cf2a2f2eae",
    "bytes": 2297
  },
  {
    "path": "sermons/draft/BRL-SER-412.002.005 - Sitting at the Feet of Jesus/05-supporting-material/legacy-source/sitting at the feet of Jesus (1).pptx",
    "sha256": "954a10e0233debb261b65c9098fff4f5d2243dbfc265adc2bec870c0778aca89",
    "bytes": 174820
  },
  {
    "path": "sermons/draft/BRL-SER-412.002.005 - Sitting at the Feet of Jesus/00-metadata/library-source/sitting-at-the-feet-of-jesus_metadata.json",
    "sha256": "a15cfcc1348ad91e2fcfd8610cf9cad0ed7564bdab23c54d1c9b6b36914d0f5e",
    "bytes": 2181
  },
  {
    "path": "sermons/draft/hebrews-01-the-introduction/05-supporting-material/legacy-source/HEBREWS 1 THE INTRODUCTION.pptx",
    "sha256": "6dfcc0c24f9982118be118d29b457750a72f825cfa353890dd1a4c5d3317e14f",
    "bytes": 535228
  },
  {
    "path": "sermons/draft/hebrews-01-the-introduction/00-metadata/library-source/HEBREWS_1_THE_INTRODUCTION_metadata.json",
    "sha256": "3bc755eb0630702b14f2cc459e4455b9d193e0c84fdf7c6be1f4029c262dc831",
    "bytes": 1713
  },
  {
    "path": "sermons/draft/hebrews-02-the-voice-of-god/05-supporting-material/legacy-source/HEBREWS 2 THE VOICE OF GOD.pptx",
    "sha256": "89b61a06e762afbbaffbc6745d7dc8579722cb52d6109f10f63c90b52885500b",
    "bytes": 138245
  },
  {
    "path": "sermons/draft/hebrews-02-the-voice-of-god/00-metadata/library-source/HEBREWS_2_THE_VOICE_OF_GOD_metadata.json",
    "sha256": "615966bf524b0a44b3666751c6fac293f209bfac8a71c66ec05eba663c706fa2",
    "bytes": 1974
  },
  {
    "path": "sermons/draft/hebrews-03-jesus-superior-to-the-angels/05-supporting-material/legacy-source/HEBREWS 3 JESUS SUPERIOR THAN THE ANGELS.pptx",
    "sha256": "9d1ee67e6487d05ab5522d2a2c8a1e62ba0d9e046ace905d03600c21be29a208",
    "bytes": 275707
  },
  {
    "path": "sermons/draft/hebrews-03-jesus-superior-to-the-angels/00-metadata/library-source/HEBREWS_3_JESUS_SUPERIOR_THAN_THE_ANGELS_metadata.json",
    "sha256": "92addf9483e8ff03d8dd7f10bde107b537c3589858e8d59d72e257578b023434",
    "bytes": 2304
  },
  {
    "path": "sermons/draft/hebrews-04-drifting-away/05-supporting-material/legacy-source/HEBREWS 4 DRIFTING AWAY.pptx",
    "sha256": "bdca8f5389c038fa4039e927cd9bf997ce7c92d67f0bdabb974588ccec9141a3",
    "bytes": 2609323
  },
  {
    "path": "sermons/draft/hebrews-04-drifting-away/00-metadata/library-source/HEBREWS_4_DRIFTING_AWAY_metadata.json",
    "sha256": "b1aba9ee56b8dc419e8b1bc04a0cddd838c12a5873d094ec12dbb738c45b8564",
    "bytes": 2239
  },
  {
    "path": "sermons/draft/hebrews-05-jesus-superior-humanity/05-supporting-material/legacy-source/HEBREWS 5 JESUS SUPERIOR HUMANITY.pptx",
    "sha256": "f70211d6ca8b794f42308f17c1903a391edcd4918b22d4119a62a1c4f6668b18",
    "bytes": 193246
  },
  {
    "path": "sermons/draft/hebrews-05-jesus-superior-humanity/00-metadata/library-source/HEBREWS_5_JESUS_SUPERIOR_HUMANITY_metadata.json",
    "sha256": "0e39120fee372f702ffc7766985900133433d8d8504a1694629bf73615927cdf",
    "bytes": 2055
  },
  {
    "path": "sermons/draft/hebrews-06-jesus-is-superior-to-moses/05-supporting-material/legacy-source/HEBREWS 6 JESUS SUPERIOR TO MOSES.pptx",
    "sha256": "1afc93dd67bc286c6cd1490def100cd3adc286b1498cda7f3bf3fbffbcea66a5",
    "bytes": 302267
  },
  {
    "path": "sermons/draft/hebrews-06-jesus-is-superior-to-moses/00-metadata/library-source/HEBREWS_6_JESUS_SUPERIOR_TO_MOSES_metadata.json",
    "sha256": "e9544c4e75fc245e747ed9859b8491e8e6cb708a1ff93cdbc7e85f13a8f500a7",
    "bytes": 2036
  },
  {
    "path": "sermons/draft/hebrews-07-warning-from-the-wilderness/05-supporting-material/legacy-source/HEBREWS 7 WARNINGS FROM THE WILDERNESS.pptx",
    "sha256": "158f8ecf56dbae5d0eff97e2ca760820e287a92e72f3589a1df9fb9d859f541e",
    "bytes": 207895
  },
  {
    "path": "sermons/draft/hebrews-07-warning-from-the-wilderness/00-metadata/library-source/HEBREWS_7_WARNING_FROM_THE_WILDERNESS_metadata.json",
    "sha256": "69791af19f16c203794842121848f3bcd58d1e9988b6883d221f4388f4c75ffa",
    "bytes": 2117
  },
  {
    "path": "sermons/draft/hebrews-08-entering-the-rest/05-supporting-material/legacy-source/HEBREWS 8 ENTERING THE REST.pptx",
    "sha256": "cf8a76f00bb6e46a5879b88098da262f114690595840d1f9cfa59b4da10a91e4",
    "bytes": 138650
  },
  {
    "path": "sermons/draft/hebrews-08-entering-the-rest/00-metadata/library-source/HEBREWS_8_ENTERING_THE_REST_metadata.json",
    "sha256": "2ac5421bbd5b253ab76bd0cc96319f0e757677328f2982724e201143c1c491ec",
    "bytes": 2089
  },
  {
    "path": "sermons/draft/hebrews-09-jesus-the-superior-priest/05-supporting-material/legacy-source/HEBREWS 9 JESUS THE SUPERIOR PRIEST.pptx",
    "sha256": "6734bdd2bcd8475a05fbcaee261bfbae25b785a5252c946767ee161097ea2fe1",
    "bytes": 272077
  },
  {
    "path": "sermons/draft/hebrews-09-jesus-the-superior-priest/00-metadata/library-source/HEBREWS_9_JESUS_THE_SUPERIOR_PRIEST_metadata.json",
    "sha256": "7f407b675c2ea6722ab5e8a83dbef5fdcfb50c5cf985c46119e086adc21ef8c5",
    "bytes": 2493
  },
  {
    "path": "sermons/draft/s02-getting-to-know-god/02-L2-pulpit/Getting to Know God S02 Outline.docx",
    "sha256": "26a1cbd1c300940e8da1f04e0eacac23553f713e515287994a1dd8fb91825c6b",
    "bytes": 18702
  },
  {
    "path": "sermons/draft/s02-getting-to-know-god/01-L3-archive/BRL Sermon L3 Archive - Do You Know God - S2.docx",
    "sha256": "3204b2fce9f257eb15bdc9012ccf06669c440f670c29ea1db13da4879455de9c",
    "bytes": 46059
  },
  {
    "path": "sermons/draft/s02-getting-to-know-god/01-L3-archive/BRL-S000001-L3-Sermon-Archive.pdf",
    "sha256": "01a7bf29f2cc70bb1fca1131931f7b6468f3814c91aa8b44caabd3a3152c0521",
    "bytes": 277837
  },
  {
    "path": "sermons/draft/s02-getting-to-know-god/04-listener-handouts/BRL-S000002-Listener-Handout-Getting-to-Know-God.docx",
    "sha256": "c2ba64113ce6409992f69b3d3ae65108e1ed2abd237cddaed51c560658e04a59",
    "bytes": 16920
  },
  {
    "path": "sermons/draft/s02-getting-to-know-god/04-listener-handouts/BRL-S000002-Listener-Handout-Getting-to-Know-God.pdf",
    "sha256": "b47dea92443e22ef0207935e31ef5a862de8fb9f762b3fd4f0c023903d76e2ed",
    "bytes": 87726
  }
]
```

## Preservation

123 original files verified byte-identical at their original or mapped destination. Six 410/411 packages, Getting to Know God, Jesus' Memorial Service, historical import report (including Proper Baptism evidence), v1 specification, Constitution, historical template, and Hebrews planning scaffolding were unchanged. Original sources and raw Library metadata were unchanged. Review/publication states were not changed. 413–499 remain unallocated. No website application files were modified or catalog regenerated.
