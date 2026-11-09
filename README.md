# Repolex Knowledge Graph of sinatra/sinatra

RDF knowledge graph data for [sinatra/sinatra](https://github.com/sinatra/sinatra), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [rlex](https://github.com/repolex-ai/rlex) query tool:

```bash
cargo install --git https://github.com/repolex-ai/rlex
```

Verify the install:

```bash
rlex --help
```

**rlex is designed to be used primarily by LLMs in a terminal.** Start up your favorite AI assistant and ask it to use rlex. It handles the SPARQL — you just ask questions in plain English.

To load this repo's data:

```bash
rlex download sinatra/sinatra
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── cb22afd7902b566b6eaba6c4ea89739494a65d12
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── cb22afd7902b566b6eaba6c4ea89739494a65d12
│           └── chunk-001.nq.gz
└── blob
    ├── 00d7d26cc4cae474a31f46b0f9fe4824874cdce0.nq.gz
    ├── 0141087fd1335d42620ac46d67a323c09163b145.nq.gz
    ├── 01da339bff87893e18a201b7b857501acd627bd7.nq.gz
    ├── 032031f9285dc5a91ad8385e4eb7051efabe4889.nq.gz
    ├── 037ba6763ee8b85f01db77d6c10e994873a99ed5.nq.gz
    ├── 0382dda53cf33e35f6706b3224401f8cc8ea98f6.nq.gz
    ├── 03dd92d5a923949568a58fd873593a7a18475ef1.nq.gz
    ├── 0471dd85aaa6c118794e137636f7771d8d2fca03.nq.gz
    ├── 047cdda04465786ed7046b119d1531ad072c4b05.nq.gz
    ├── 067e671cb685ef672baa0c811561568c3fa87fcd.nq.gz
    ├── 070f797fedf4e33181eca22f793bc35f66e081a0.nq.gz
    ├── 0801fbddd6a0191e570d5f297249f0cd0bc6880f.nq.gz
    ├── 094e6a8e2150719d783ffc319769e9c24ea29f6c.nq.gz
    ├── 09b43f9bcc761baa77b9706b612c5fd6d46d95ca.nq.gz
    ├── 0b73ae57cacbb7c1fe9441a33a5b2c0699adc4fc.nq.gz
    ├── 0cae7e21d20d185f0b9832e30d958c64780208b6.nq.gz
    ├── 0d26c14ab6016d66ba076765c6a85a7709a65387.nq.gz
    ├── 0d786ba0e16158c37ac72910c8e83bae7339ab95.nq.gz
    ├── 0ea2019f5c99657c7c12d99a2f2116eb7b54db2f.nq.gz
    ├── 0f3aec101b0ea35af09869b05820050fa1f75c19.nq.gz
    ├── 12c980301fdb05605c7753c1fcf147eabd5013ca.nq.gz
    ├── 14b963e1d793ff5165a25c3a3662918fe5c278b2.nq.gz
    ├── 154f9f1f72137053161ec23c326383fb149c0b64.nq.gz
    ├── 156de2115cd2852c807d3ac1fe1d5e7aedaea223.nq.gz
    ├── 167e3bf8d7ce3ac1be7f25a144b4eb7d3d386baf.nq.gz
    ├── 16ad4a43958d41999fe601b673fbe94e130afa40.nq.gz
    ├── 16b86d036c14f3725a477cb0db552fc3a47e9ff5.nq.gz
    ├── 1abbec77cb6c61882455560ca3cf73fba7f4ae26.nq.gz
    ├── 1afd1605f8d5aa2a0d8f2cbbb627f1f3246388eb.nq.gz
    ├── 1cea892e17dc5409a2caa9ab28fddf8165959d12.nq.gz
    ├── 1e6812e59700bb285ce0542c09c183f3729a800a.nq.gz
    ├── 227dc75c5e15097dc1d54becb45fb3b8edc366e4.nq.gz
    ├── 22e759d8eb05322bb647ef409469bfb3284255a1.nq.gz
    ├── 23407f01febfa1ed56f58ee13a824837a576c77b.nq.gz
    ├── 2384b549f96a27d4602aac676b9727ec77509f7f.nq.gz
    ├── 239fac236e492a2b77fb907b56ddcd95a924d2d6.nq.gz
    ├── 24a1a55e0e1b14a855782ea98217e34ced5989e8.nq.gz
    ├── 26723d9e3c22fa8a2e9bf7c4eeafd49bd151b94d.nq.gz
    ├── 26d54af2a0ad51c9317de366d9697366ffaa3fba.nq.gz
    ├── 27b01efdf0b654af2c35f96550df807c6e23bdd0.nq.gz
    ├── 293680bd1b18eb7672c43f4c7aa01d810919e757.nq.gz
    ├── 293e88fbfc2c21d944d4c7d03f5fa1f5209132ee.nq.gz
    ├── 29cdd92f7576539b91710316ad5bd33c78022fde.nq.gz
    ├── 2aba63411de9c69476678bff719ebfd418086b2d.nq.gz
    ├── 2aee666d879ef733f3e07c43d459190e97a354b0.nq.gz
    ├── 2b68c4148be4c71fba38018fdfd2a69f2747a4e2.nq.gz
    ├── 2bea382f46c5d25dbead88f603c913ca8303b83a.nq.gz
    ├── 2cb201f6e76a7de8e4bf83ac0959246216df9d8e.nq.gz
    ├── 2e5130c38dad65657861911be861105b4b490edb.nq.gz
    ├── 2ef371b37763f734a260c347227ee6ec8d0be9d6.nq.gz
    ├── 2f36d22726cb2642e6341a42dd90dffa5217d539.nq.gz
    ├── 31b3fcf96a530c96968e83b754b4f6ec1395797e.nq.gz
    ├── 31c4199ad9d6115ac6f9d643740b191455963bcf.nq.gz
    ├── 31c54c5b41d893bb0918322295cd7e0c96b165f4.nq.gz
    ├── 31dc9cc2934e0d6aaa890501c4d50bafc3ef8ce6.nq.gz
    ├── 34e2e36eb54cc6df4392071ca71486a32a7770ff.nq.gz
    ├── 35348e3ff468455dfafcb80d194c3dc2f3652cf3.nq.gz
    ├── 35d576229c82e312ffb899bec9814fd0a0f9d371.nq.gz
    ├── 372cddc86478f8ff781737297a055e73f751ac6e.nq.gz
    ├── 3743ebb6694534264cce1fb35b642de00fd743b4.nq.gz
    ├── 37a8ee8f048753a402593b61c9918cf4f830deb5.nq.gz
    ├── 37f123d033a3c07e7885c8f3a12096b4dc2f6de2.nq.gz
    ├── 381e39404c639660a8169c9ab715d184f46fcd46.nq.gz
    ├── 39f8c4e2eecf28b4829bfb6f537fac0cc505eb58.nq.gz
    ├── 3bb065c38c3a8dc95a31510f4c03b0a45452d017.nq.gz
    ├── 3be6744e3b624b6ce788e155d6c0096ce806af3a.nq.gz
    ├── 42fc56b34f8784fd60fa06b3203225dd25221894.nq.gz
    ├── 440591803b20ced1efeb140075e7c936b6a71304.nq.gz
    ├── 44da05ca4c11acd43c5a8bcd0b75e45fb06b233a.nq.gz
    ├── 45b983be36b73c0788dc9cbcb76cbb80fc7bb057.nq.gz
    ├── 4633b023ba3471c94f87bc3f950efad1fb2bc950.nq.gz
    ├── 4979bd82f8d46856a5997024ea87bf2f37fc8bc9.nq.gz
    ├── 499f860d0180b1939c472eba5136e0d4273230fa.nq.gz
    ├── 49c7fbaf9b55a62a0c773f5e17053c97307fe91f.nq.gz
    ├── 4b64d4d4d678c97158e6164f01b1895a19284b0c.nq.gz
    ├── 4c7b81875c2791371377a1e3da35c35ce487ea96.nq.gz
    ├── 4ccffd5ffab7c22e83a5da5989905c2aec3fd63f.nq.gz
    ├── 508b5814a65341381a35ca6980b798d949138aba.nq.gz
    ├── 50f8864f243ed79178859025a1b0c2b12e7ff979.nq.gz
    ├── 52ab962ace2c1a15f81a41be25537c82af33be81.nq.gz
    ├── 5324969084abd88217f9b780a1d796cbbae72a87.nq.gz
    ├── 534038b0554d6eb74b84355286558b5a061ff7c6.nq.gz
    ├── 54d4b3ce28ecd4afdb21a4ad36e4fd5c74538427.nq.gz
    ├── 550032acfb3522aea3aad5b84dbdf48d53f58f89.nq.gz
    ├── 555121d8b9b0ad20ccd2a543939b66c51b9f8588.nq.gz
    ├── 55d3284a926a7ab0ef7032274d111bd096f8e9c7.nq.gz
    ├── 58814f4363dd4c16338f3d8cb949bfdba9588d40.nq.gz
    ├── 58bfc04de48126914166e3dac79f3619c3a7d0ce.nq.gz
    ├── 5916765665e87890211957af9e84f38ce67c2e73.nq.gz
    ├── 59d8e49653b37513eac18d1a6ab117f22beeb519.nq.gz
    ├── 5c85330d0ec76d1fd30cf56a13cadd0a1188d61e.nq.gz
    ├── 5d7e679e487757b2adb6a5b42e1dfb14f0a3cad5.nq.gz
    ├── 5dc05fecffc49d14a9ebc86f233423b09d71db94.nq.gz
    ├── 5eb6f2bec756e7f40d1e33ec596f236866831c32.nq.gz
    ├── 6019007b26468b88775d81e74bd432230792ba77.nq.gz
    ├── 603038a4ce09fe4ede82fb6a7a59af59228427a3.nq.gz
    ├── 6034243ec9f704ec386ecb60eafaea048a9fd147.nq.gz
    ├── 60e00e9a35fb3311096f71da1f0f3b6ba7a29cf6.nq.gz
    ├── 614f93fcaa32b9c22827eefb2e784b64e569e156.nq.gz
    ├── 61934d63d6758c5146725158e0e9a7dbc842eae6.nq.gz
    ├── 619f2f0765c89a70762bd20a7d73ee7f11698494.nq.gz
    ├── 61eab8951464fa949a1dcb8bab420487c6185480.nq.gz
    ├── 62602fa03a6481a2435afd1a3244f155b726fc22.nq.gz
    ├── 6447df3346ee6fe624d5ba274eca6bedad2f9ca2.nq.gz
    ├── 646181ebc5d62ae66e83924cd7f28c17f01ca662.nq.gz
    ├── 646576f36ea51ca027af20c000384e676a7779a1.nq.gz
    ├── 65b38efafede6aa3d887482b5747b4c78b8c73b9.nq.gz
    ├── 65b607251064472ba1ca84f33fb1a24a3003161e.nq.gz
    ├── 66265156c14e32f02b480c00d0c1957d5377374e.nq.gz
    ├── 68e84ab848742523055c330949b787ced2446f9b.nq.gz
    ├── 68ef6a6c8e411863492768bcaab606f73f3fce7d.nq.gz
    ├── 6a1198d67171ab06ce08e3e95cdf169a915cec9a.nq.gz
    ├── 6a9eb468076f0e0b0a9fb1f6f87a410794511280.nq.gz
    ├── 6af88d84406c5ca701490f6cc7bac4431bdb6024.nq.gz
    ├── 6bbadd24890b68be092ad2a25ba31c509f0b3e16.nq.gz
    ├── 6c121b377d5080d49c1025caf47a620fab6674e5.nq.gz
    ├── 6de5acb2f0d73d6b5f6bd5ee4569e28e9d701091.nq.gz
    ├── 6e0c9cbf0148c924d0056f3fd9b81fa8b82ec5c9.nq.gz
    ├── 6f3744b83c01c92b96e6ae037cf6bf9a33b00f93.nq.gz
    ├── 6f492b28198913c1930dae9a857083c52ec2c477.nq.gz
    ├── 71a6257539632aa2b02968a395882d40922f1bb8.nq.gz
    ├── 723f0f75c7f8eb7d6ec07a8fd96707546a63e923.nq.gz
    ├── 73968a386959b4572dc51073f38e4974d42fff56.nq.gz
    ├── 747d539e17b30b5f400cd493f5b3285c93c41f26.nq.gz
    ├── 74bf0e4520cad114e8166c7ace7792f3f65d40c3.nq.gz
    ├── 77ed59eb6a81f2f22a626607fd1808aa956195fd.nq.gz
    ├── 781569f1a9af4df2bf32912e636bd849e9174309.nq.gz
    ├── 795d37a7744313061fdd09cc8a1fcbec23ad0885.nq.gz
    ├── 7b26dd4815b0a41e2e0e42929a22612bf79e10e2.nq.gz
    ├── 7e019761710f421e61ad943c47cd901f6f33126f.nq.gz
    ├── 7e6b609180ce2c9f47b07561617b879aebc425dc.nq.gz
    ├── 7eea73069841788df0d766c36244e85bb51ad6f3.nq.gz
    ├── 805c0b21a5a9c0556d3498523458e434431d5ae9.nq.gz
    ├── 8399350bd9d21230956e1c84223c2aa4fa600dce.nq.gz
    ├── 8693ba1c68e600ec43ed2eb9dc2a286124248c65.nq.gz
    ├── 8814566827d37a8a4ffcd205bdd7c76638795e8f.nq.gz
    ├── 88805dc49cd2f8922677aa835ef0586d6e64bf03.nq.gz
    ├── 8d98a3e19daacb2a013af85b61c3b2345d86a332.nq.gz
    ├── 8df06a733d478e2600e47649f9cf209814e6b6f7.nq.gz
    ├── 8eee599b7dab25fbe24f0313c70c16cc1bb26c8a.nq.gz
    ├── 91628b84b09c5892b1666cdde0efda3e71d00324.nq.gz
    ├── 91a0c70be22559d8d00cbb91a89d40113c250a1e.nq.gz
    ├── 92142e179b2b0a3f289e30c494af3af7de575e37.nq.gz
    ├── 92165ecaf4700f169c79b811f0c00cc613f420ec.nq.gz
    ├── 9491f57401e86e1d37e314c330213622e47777ff.nq.gz
    ├── 9522a75e1a6cc6353cf85f2bb98250c6f871f7a7.nq.gz
    ├── 95503582834301030fe39c23c528cb0521d6cce6.nq.gz
    ├── 96007e44d9f0244b94d28c62de4e933cc1c27128.nq.gz
    ├── 980a0d5f19a64b4b30a87d4206aade58726b60e3.nq.gz
    ├── 98b2b438597cabbb190bb798be5fdd0156ab9783.nq.gz
    ├── 9cf87d5eb5516eeeecdf1c89ee61765e61c0a957.nq.gz
    ├── 9d56e3315f9c42f0bfba56c66b4fedc6b62519fe.nq.gz
    ├── a021e5dd1cb0e05ee43cb20c744ab9fa7f87c079.nq.gz
    ├── a028d2e8b828150a2cb441f13a49d87813067a5e.nq.gz
    ├── a15993f3676492c65e8f2114f14c5fcba71cc149.nq.gz
    ├── a385d0cfdf4ca142f036bd9106a160b01f60606f.nq.gz
    ├── a3b0875b6d3e1d055ca02e50c7da07249ab61135.nq.gz
    ├── a4c21726bf8992721c9c26d74cb2f6b96150615c.nq.gz
    ├── a5921f1533791252baf70bf1d38a138531bcdbd5.nq.gz
    ├── a6e7b7b04681532bdaa02b9b6eab8d734f3bbbff.nq.gz
    ├── a764ce2fa3ac2f35225d8d30db417df8f69e804c.nq.gz
    ├── a7be1a3a27e494b66d152f221d7e8b3476a68b37.nq.gz
    ├── a85e7d2c0bed15b4bf4f44746013c7a3cc3b96f1.nq.gz
    ├── aa24fed59b366a63af2436c0592fb9992966f57c.nq.gz
    ├── aa51607282f6e38d6fbee21d30e9b4528c404125.nq.gz
    ├── aabdfaaec568075edfe8313660d27ff7153dda3b.nq.gz
    ├── ab4a98190cf776b43cb0fe57cef231fb93fd07e6.nq.gz
    ├── abd09d0c4460d13f71578ba5c0e4025164dfda86.nq.gz
    ├── acc9f59e681149933c901357b52b313e98ddc520.nq.gz
    ├── ad12e6960205cf292573ac5490ddba410cb2c458.nq.gz
    ├── ad750104757758227be9256d5df13d95ae85738c.nq.gz
    ├── af8144125c4c2b8dbbb581cf0ad091db340271d3.nq.gz
    ├── af8fa95b51cec8f9141edd8c441e17ffb10a2b02.nq.gz
    ├── afba7a3e9862f9f7d6efea822e5e63e4a720abdf.nq.gz
    ├── b22350c1f1700edd4bfc58fc4df33e90c8ce4d97.nq.gz
    ├── b2ae15e9445bbf6758c01a809a15cf3742475f18.nq.gz
    ├── b48d1f060ecb7a5dbba95e6272fdc292443ad2b6.nq.gz
    ├── b5f6031fbdc4f94399f18b2ff0161d6a758ce7f1.nq.gz
    ├── b69797a940a2e9e179b2137364586127922a1355.nq.gz
    ├── b85923a99fc69447ba551bc5d5e34399c1c3bc54.nq.gz
    ├── b8d0a9bfbb976fbb5895f976895dc1284db31238.nq.gz
    ├── b9e2347bc26ee68380fa74ce61a6d4653471e2f5.nq.gz
    ├── ba527d49352d804e29a85725be89582cdf70d254.nq.gz
    ├── bca7fc1a09faec1fac12a6dc654310c01dd888b3.nq.gz
    ├── bcbbc926f4bc36c1711a5043d5a5c178e450b246.nq.gz
    ├── be218e9942cfdab96147c55e6e9bbe557b16372d.nq.gz
    ├── c014466243303e9bdc4bea092dc405bc926fc9d0.nq.gz
    ├── c217a112a03517bb8bd80f615b1ac4c7b6a04e40.nq.gz
    ├── c2e90462ee8f176b8203ace000e3ec40a435ca6c.nq.gz
    ├── c37a20f82f59cc4df05a5578f91fabd0f7e5b61e.nq.gz
    ├── c3c0a1aa47d21721871ada29ea6709ee26f08474.nq.gz
    ├── c4b8f8c86ed6e9fd0d3e0555439368a04533780d.nq.gz
    ├── c4c9a964c209cb5a67f8a29dedb5ac3397d205ab.nq.gz
    ├── c53f830ff56775f1b7921aa227600b7cafd05dfd.nq.gz
    ├── c63918117f6f2fbb9a35bb6409e8a201ceeff550.nq.gz
    ├── c6e07b75925e793a0fe9d8a8c5f176b24fd8f52f.nq.gz
    ├── c729101f22912a3cde0481d5fe06fd8644a6a981.nq.gz
    └── c76a30c678d66378ce5930c7bb6e0f44c5196313.nq.gz

7 directories, 200 files
```

| Directory | What it contains |
|-----------|-----------------|
| `blob/` | Per-file AST graphs, content-addressed by git blob SHA. Each file in the source repo gets its own graph. |
| `aggregate/ast/` | Combined AST graph per parsed commit. Merges all blob graphs for a snapshot of the entire codebase at that point. |
| `aggregate/lsp/` | Language Server Protocol enrichment: resolved symbols, definitions, references, and type information. |
| `aggregate/dataflow/` | Interprocedural data flow edges between functions and modules. |
| `aggregate/repolex/` | Combined graph (AST + LSP + dataflow) per commit. |
| `commit/` | Git commit metadata (author, date, message, parent links). |
| `branch/` | Branch metadata. |
| `tag/` | Tag metadata. |
| `filetree/` | File tree snapshots per commit (which files existed and their blob SHAs). |
| `audit/` | Code architecture and graph audit reports per commit. |

## Source repository

[sinatra/sinatra](https://github.com/sinatra/sinatra)

---
*Parsed on 2026-11-09 by [repolex](https://repolex.ai)*
