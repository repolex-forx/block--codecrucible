# Repolex Knowledge Graph of block/codecrucible

RDF knowledge graph data for [block/codecrucible](https://github.com/block/codecrucible), parsed by [repolex](https://repolex.ai).

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
rlex download block/codecrucible
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 8a6299fe165e931bbdb59ae56f5a432b1f2d5992
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 8a6299fe165e931bbdb59ae56f5a432b1f2d5992.nq.gz
│   └── repolex
│       └── 8a6299fe165e931bbdb59ae56f5a432b1f2d5992
│           └── chunk-001.nq.gz
├── blob
│   ├── 01fd113d260d09ef4a30909373cd3b0192921d26.nq.gz
│   ├── 0278d36d3f1ba0f73b91c74152ff480600594554.nq.gz
│   ├── 02b53301b4470726555cdb6b8b2a7d31abeea832.nq.gz
│   ├── 03c1aac3ed5892fbeafc7eab350956dd5e4b61ab.nq.gz
│   ├── 0626dc14e1f949a960f9fc4347b369c18a908478.nq.gz
│   ├── 0698381afe4addb2a1e26c4fc89d131ee49d242c.nq.gz
│   ├── 06f48b2d8f61022678dc1bffa760a025fdedb297.nq.gz
│   ├── 0b5c6b9677154c36202cd1e668956e9993e5d9f3.nq.gz
│   ├── 0ba9db25329d0b336e39ca8cde8470c5b7bc45eb.nq.gz
│   ├── 1122225300e7c255f73c424160daf2a82d3272de.nq.gz
│   ├── 133a5a5cb70a9c3a4afb20515ffe7d39d1592dfd.nq.gz
│   ├── 139d9ae5a4adaaa00b1b42272dcfce79f6060193.nq.gz
│   ├── 14a20bc38db8e90cd07187e6d662c74102cbb6e1.nq.gz
│   ├── 14d82b2a6f32b77aa235b5afc25fb1075d4f2adc.nq.gz
│   ├── 14f171f306f7e95b9a04a13eb9ea991583773e7f.nq.gz
│   ├── 1557a5f4e33a373da8caee7c45fc13e8573bf84d.nq.gz
│   ├── 155dd9e9ec9b108ddfaa19dd12175c05aa899e93.nq.gz
│   ├── 16e064f8cd1d37e24991701231dac132f761b8d9.nq.gz
│   ├── 17a5f3ed5c8ce4eb23dd3ae457856299c6627bad.nq.gz
│   ├── 17e9804fc92ddde2b82c24c24a31aaebffe92962.nq.gz
│   ├── 1b4991b411d3cfe2f2782cb07a0b6c0fa3b64767.nq.gz
│   ├── 1c9a30478e2af159b16ca9f64a41fe80abc96bef.nq.gz
│   ├── 1d340f53379629940ecd8759f5773621bb50c0b2.nq.gz
│   ├── 1d4eef3fb21c4ecc73490af754c3925588039d19.nq.gz
│   ├── 1ed5774b3855630e582f062cd076c6de8e800daa.nq.gz
│   ├── 249e1dd6e453dda67f2249797a22430aa0bcf38c.nq.gz
│   ├── 24fb6715394a6cad35c6b1c18cc252316a161d07.nq.gz
│   ├── 25f0bc5ed80683a81f46e6bfd1cf8ea0b56c6807.nq.gz
│   ├── 27b05181a5d29fa398c3200219d354ece0c1ae0d.nq.gz
│   ├── 2ac1f379ec0f23d2fbb48a8969e174b8fa755e66.nq.gz
│   ├── 2ea22dd943c870ce6e7e32728999dc84d199eb83.nq.gz
│   ├── 33c7b2be0fe09d3a85e88d82741d9d72595b2ba7.nq.gz
│   ├── 3474fdcaf78a530c73b9625a386a209c381b4f98.nq.gz
│   ├── 34ca3524c29daa63fc2dce2e7ff6e4d5a77efa0f.nq.gz
│   ├── 351a97308d749922b99ed59d10033b43c2699b43.nq.gz
│   ├── 35f40d706ae505dfa2bad6322ecc86445bc8c75d.nq.gz
│   ├── 38a1929527d144b0393d190e171b9d40df7a9ed8.nq.gz
│   ├── 39105b8ed3f57facedfccd8b2bbe38cbdb1a5115.nq.gz
│   ├── 418a01c70665634fc8f3af329aac61e23925e930.nq.gz
│   ├── 42da51706be6a8a8539e288823b47b376f1f18b8.nq.gz
│   ├── 4333fddb93176dda3b6daccb465faf9dd46abf21.nq.gz
│   ├── 46cadec9722ff874a94af45ec422ec62f574630d.nq.gz
│   ├── 48fa6770503e17e1f4bf722373a38251c74cbf31.nq.gz
│   ├── 4aad24f6f8659a8e1618937b6aeb989a979157a9.nq.gz
│   ├── 4f241efd6828d4846b54035042a33976509ebe9d.nq.gz
│   ├── 510660c3a3de2e0a1868366fc500023ac08eb102.nq.gz
│   ├── 51e83aeb0fbb4295a6c88fcb4974a0590429be8b.nq.gz
│   ├── 5336c66788fabec79d3670c77ea6b552ebe21cc3.nq.gz
│   ├── 5587e38e91a9afe757f5a15e3beb7efcaafb0de2.nq.gz
│   ├── 57ced724ff6133591661bb453702848dc31374c3.nq.gz
│   ├── 59fc0427139005fa90386835233ec5123dcd5724.nq.gz
│   ├── 5c55f81021e035a0123da51ab347dae37f706117.nq.gz
│   ├── 5d60552e8d8a977ece446b2d55a9ba928da032bc.nq.gz
│   ├── 5e299e2b0a4be1c57189a9983551df309c217ec1.nq.gz
│   ├── 5eed1a93875f80429664789acb0de5e6a0667058.nq.gz
│   ├── 6043e6bfb4536a27a23aef7175cd0654bf2c3064.nq.gz
│   ├── 613fb287de518e041bc823cc78e140e59312a13f.nq.gz
│   ├── 648f68d3df57f2a992b8a1798a5ab409be49047a.nq.gz
│   ├── 65551fd5147011c42f05ae5b85608f4d5926a804.nq.gz
│   ├── 657917fd04e091e585abebbf382b753ecbcb75ec.nq.gz
│   ├── 67a63c8fc440ef08ea9a604a48673cf9f42dacde.nq.gz
│   ├── 68293b892e16c8e65931bf643362e590db95d965.nq.gz
│   ├── 6a1dcecacc5a90e89738873f0b7f69c1a2393809.nq.gz
│   ├── 6bccf43368fd7c96d9c659562a5142b8b8cb98a1.nq.gz
│   ├── 6eb86e9f1cab8b75afba965951f13ecb683bbb32.nq.gz
│   ├── 6ebd7abc50efeee0c4e8b8b6839b67531138595c.nq.gz
│   ├── 7048db4f48a6f6e4b22c53837d6389ab63be9f11.nq.gz
│   ├── 727fa76160dbd9996a8a2d3140e83fb48f5949d0.nq.gz
│   ├── 77b6d0d1ad2f2904a4fba07d326556b5b9758228.nq.gz
│   ├── 77c47afa0023176b5652b65a3109979c5e8c4de1.nq.gz
│   ├── 7bb830a275e6a1f9bf1149a9ca2287cd569af0b7.nq.gz
│   ├── 7dd8e56d23249fceff576718d813d69892de72f0.nq.gz
│   ├── 8027655bcabb0a3fdc9bd35f87159938808ecb1f.nq.gz
│   ├── 8099ea2ae05850907a290228545b1bd8a4557a3d.nq.gz
│   ├── 842165ef8010138365c17afd26787428b8330a9e.nq.gz
│   ├── 84ad49f3be377be283e04c77bd08fefbb7adb117.nq.gz
│   ├── 862ee3c28647e7a58801a75236855c269c1448ae.nq.gz
│   ├── 8756cbb15e6602e6b48b266304bfa99586700c06.nq.gz
│   ├── 88c7c4563c10efac3eac05c69b58ba3480f0366d.nq.gz
│   ├── 88f208811a9366aa775835d8106ecd5da6872ded.nq.gz
│   ├── 895259fa88d9ae049c4c8d8aad690fd47008d06c.nq.gz
│   ├── 8953f37377d95699c70d663e548c3b8554211c19.nq.gz
│   ├── 8a174cf876626c8065d12f41573d462de05fc41d.nq.gz
│   ├── 8a2b114ba5d50afe8ac1a6822e1a12d77c59dc1b.nq.gz
│   ├── 8d3dc46a6cf8e548273a449770196c86d07b25a9.nq.gz
│   ├── 8e1af2f6b242056dff7bef8e56959be47225b046.nq.gz
│   ├── 9037b2f4de5f3ad8ffdb976a99abd8743c1a93ab.nq.gz
│   ├── 9472471584ec86c6fd5ed33b1f65ab3cd57116de.nq.gz
│   ├── 94bf8af03a244decbcae9e15416231359a4442e5.nq.gz
│   ├── 9582fc588754f78d9875691a3bd5e674295436b3.nq.gz
│   ├── 97f9dda9f15756320ffa67c56885b37d00058a2e.nq.gz
│   ├── 9d88876ab28c69ed2283ae3632a728aff0d4bfc1.nq.gz
│   ├── 9e2f6473c0e8effde19047aba90591fb5052709f.nq.gz
│   ├── 9fee3c4a38e8f6067f00665dd8824220a335c6cd.nq.gz
│   ├── a07294037d96a86a9a7a3cf8ba074870e54a3616.nq.gz
│   ├── a1a7cb2268c714d14194fc8592d923c3ed9155e8.nq.gz
│   ├── a1aaea5ef94d2a29978d4ec56fa37f390bebb484.nq.gz
│   ├── a23cd0342ec564f59e33d6d2941976f9c2773704.nq.gz
│   ├── a2453dd8907dc099eea420c27f1bb8ac054c85b3.nq.gz
│   ├── aacd1481efe101675b34a56fae0ab642e3841285.nq.gz
│   ├── ac4aa7035bf3b0d93bb8cf062646b3015e13d2fb.nq.gz
│   ├── adab058f21c479a1044930edb13f07ab4089c36f.nq.gz
│   ├── ae2c9359880235603c30ee969bf6dfe69e8cca2a.nq.gz
│   ├── af59412c89db18f7c774bebd0707399f4226ffb0.nq.gz
│   ├── b02dd2e45ba28f5b175523a79f53401b0cb0d4ed.nq.gz
│   ├── b094fa36044a907965cf8841d243e3ffbf88fcb5.nq.gz
│   ├── b15e7781cbd10082a7ce64a9832c93e3796e9c7f.nq.gz
│   ├── b2d257687bebba017b1acfc54e80264e357f0c28.nq.gz
│   ├── b3047a4069b7798b3aee8b1145dedd3cb31d1d73.nq.gz
│   ├── b96ae9856300204d422e321df17dbba1734c0a11.nq.gz
│   ├── ba460065ce118ee8602a495a6438ee57ca79d387.nq.gz
│   ├── babaeee4f28396d8b4dc7ab2575e3bc27f8eab8d.nq.gz
│   ├── bb35c9b3939e4a8b29369d91141a129a5853a37e.nq.gz
│   ├── bf0db60535ca22a1571c10b2b170eaa96734a08b.nq.gz
│   ├── bf6c980d5a3ed0236e9799f93144c1a0ef59aeb3.nq.gz
│   ├── c0964020d839c8995d1db17ecee4c71dc4e57721.nq.gz
│   ├── c1c7d4099dc800bb273c25225a5ee16e13442f0a.nq.gz
│   ├── c266e40ba5e031bf94128c637ee389bbc92172b9.nq.gz
│   ├── c353e3a039fdad2e368d2031ec4d03dc102c98fd.nq.gz
│   ├── c3c133f5893ac838a9810231002a590e8b3b7b93.nq.gz
│   ├── c527891ad931901e4fed468a40dff822a2666c2f.nq.gz
│   ├── c57da95cb3d64d263851800691fce60ca9cb4144.nq.gz
│   ├── c5a526faf5105844033519557785ea8c014fcabb.nq.gz
│   ├── c85d116e5e5f7e8eb761939f331ceb8e44844713.nq.gz
│   ├── c90158bfeda85854646735f97cbfd261eb463f0b.nq.gz
│   ├── c985eb69bfd006e59d486ec480e31df911d629f0.nq.gz
│   ├── ca3c2ace0d0fd69265c79d7d623c48a9e86d5b9d.nq.gz
│   ├── d0a6fd4d5168ed0b9276186fa77073094dd9926a.nq.gz
│   ├── d0bfc24c6ec72f42eea153c950a9903393986a8d.nq.gz
│   ├── d0caa410236e023a829e297639f0cfd02adf62e2.nq.gz
│   ├── d51a8e9b75d6cd587514be2d6c2389f10860831a.nq.gz
│   ├── d78419b3ded81eedd7bdfdf7998fa4813ff8c53e.nq.gz
│   ├── d807baef7b6d1849e46eff541ff3e7881464667b.nq.gz
│   ├── dd6f974a0f073447ac4e0762d339bf3bbf42b6b9.nq.gz
│   ├── df7a4af984b329ed7a5eec9482dd415f60fbcd43.nq.gz
│   ├── dfb0ffecdaabbdf1df9ee9bd9a86d187a1760edf.nq.gz
│   ├── e193261013744ac0f21b16402c994342a57d4157.nq.gz
│   ├── e3eb4fcd3919d3bd8e512c14bf8fb52d8a282b38.nq.gz
│   ├── e5ec06183175ee4da37183332745bfaeaf5e2174.nq.gz
│   ├── ea499be93e28b3d89419c2894d9508f6df61caa2.nq.gz
│   ├── eca63bfd5f5a2c3943748af4c2d5c6186280e6b9.nq.gz
│   ├── ed0639e07ffaa99cbd956a9061e11dadab601b4a.nq.gz
│   ├── edcc4097444534161baba3d26dc67ace3a1ab75c.nq.gz
│   ├── eebc16a24e76a5a5c4517c75a6c4e22420356862.nq.gz
│   ├── eee842671a8951589784f81623efcc0065334b0b.nq.gz
│   ├── f050ebb59c52e4488f9fe1ab44658f6e00f00916.nq.gz
│   ├── f21b67d06e03fc52c7999ff318928462aeea0b10.nq.gz
│   ├── f3601e62a21407bfb28192a873164056ea19e183.nq.gz
│   ├── f3ca74e9e7ef02ada26da482d92e968b2601f841.nq.gz
│   ├── f93f39e2fa427881801ebb8f6e0205dbd90c0512.nq.gz
│   ├── fa463b027f992d54339cd3e401fa9a538cfb2c43.nq.gz
│   ├── fa89c98fc4fae90e2abdbbc786587541de03673c.nq.gz
│   ├── fd183db1e88b5fb89c38108e75ee1e8555ecb669.nq.gz
│   ├── fe430df352b980685cf5a1c0cfbf552001d65bc5.nq.gz
│   └── fffe4a514feef3857e0d0f5a0fea5950557bfe99.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 8a6299fe165e931bbdb59ae56f5a432b1f2d5992.nq.gz
├── filetree
│   └── 8a6299fe165e931bbdb59ae56f5a432b1f2d5992.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 165 files
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

[block/codecrucible](https://github.com/block/codecrucible)

---
*Parsed on 2026-10-01 by [repolex](https://repolex.ai)*
