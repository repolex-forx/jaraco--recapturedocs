# Repolex Knowledge Graph of jaraco/recapturedocs

RDF knowledge graph data for [jaraco/recapturedocs](https://github.com/jaraco/recapturedocs), parsed by [repolex](https://repolex.ai).

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
rlex download jaraco/recapturedocs
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 3b49b41d9e88377e3b0afb00815f77bd5740fc0e
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 3b49b41d9e88377e3b0afb00815f77bd5740fc0e
│           └── chunk-001.nq.gz
├── blob
│   ├── 03506cf005da13ba3718e34f60b0c42ea7e53637.nq.gz
│   ├── 09eb261b6701cca40361aad4c2bf7712e0aeb084.nq.gz
│   ├── 0a5db84b03727ceca982c227cfccfa3e1c5ac602.nq.gz
│   ├── 0b737aef24e5541c747d1aff4607ba46805d2516.nq.gz
│   ├── 0bf522472d191fbe01f2bf51f21442833a8b06a4.nq.gz
│   ├── 10d412f406891b9683f832fcbc134c9bdf4f916e.nq.gz
│   ├── 1bb9d246c14977fb690b834ebb85b0b7f676bc76.nq.gz
│   ├── 1d4211b19f374910b4062e5a60416d122474a571.nq.gz
│   ├── 1f2aa7533b0423a8eb943f6f4ec02498e39581a0.nq.gz
│   ├── 22b952a6a0a3fc85b5e7cc6501d393fa5dfe8d41.nq.gz
│   ├── 240329c3604d8ead4c10aa8c88352caa8e4ce7b2.nq.gz
│   ├── 2656a805b9a1db735d20cf0f783cf3a950c90575.nq.gz
│   ├── 2779337b307df851cda70b88ed65b1158a735937.nq.gz
│   ├── 29056f38361f9793bfab55f6769e0d2981b74958.nq.gz
│   ├── 2b22de6449505fba5a967fe5bf2cd5867ab6f254.nq.gz
│   ├── 2dde6fcc7214c6a374652ebffaef298ace775e6b.nq.gz
│   ├── 2e3f4dd791a6372b427d618eb0baa8c4dc58e5f0.nq.gz
│   ├── 304196f81e11a168c9894f966e4a617ebf4ed53c.nq.gz
│   ├── 367c282b4ca96ae6943974c3c8d93f468c99b959.nq.gz
│   ├── 382f434863a6554aee93c18aca92fdc450be3712.nq.gz
│   ├── 3c3770ffdecc293b7903867c44e9307d7a7acfeb.nq.gz
│   ├── 3d014d1bc9348281217c6fccb985a9b2a6887dbd.nq.gz
│   ├── 4679bdf3f98fa298a4a72eb3ddfb08f27d08d1ff.nq.gz
│   ├── 4726618e24c8a000885fc7c055566fb4be1b7c3e.nq.gz
│   ├── 499fbe60e3f06699151c5c966e6202b259132ef8.nq.gz
│   ├── 4b4108b948d7a8cae8934c528ecddb946545ee9a.nq.gz
│   ├── 4d4f314be320bf73e2ccbdcd7408dfca9c2a54ab.nq.gz
│   ├── 4daff46a37a255f7fe969e6d4e82470f1e3cd690.nq.gz
│   ├── 5262317863d5300042cb55a159f09ce76661ec29.nq.gz
│   ├── 532ea997ff25578a76bcedb0ba6ea4b9fdf8b5f1.nq.gz
│   ├── 54c9000ec94341dd65c2053251b85b124017b9b5.nq.gz
│   ├── 54cc8303b22089e12053e552d4e6cb852a865b8a.nq.gz
│   ├── 55b52a9f20794242dc4b76167520cdd43a313801.nq.gz
│   ├── 562fef3f21b9d7b58a55e9b2d02680fd027abee7.nq.gz
│   ├── 577e87a793a20e413f7321f4f17ec1eba2ea1962.nq.gz
│   ├── 58de6a573a8790a8e894bc50ff5020a6ebd2dbce.nq.gz
│   ├── 5bdc232005af9be104a00437ae9bc64417a4c1cc.nq.gz
│   ├── 5c5245078703243c70b912236a2ccf099fb25175.nq.gz
│   ├── 5e8fa6e1cb842307b3c88f5e6790bd5efddfc77c.nq.gz
│   ├── 6386c57293cd751968ee5d9d4e70d0f97d0c4486.nq.gz
│   ├── 665a64a807429f62636126b226b2a44ad5842bc7.nq.gz
│   ├── 69bb07f3f59e29d467d80b5e9b72ebc0147c6007.nq.gz
│   ├── 6a65c9c82754c017a80efbd0ae3c9b17d38af274.nq.gz
│   ├── 6e7285622ff1bf623cf76132e95da7cf983f3f48.nq.gz
│   ├── 6f9af3857e53701783ae7ca2683c8db43dba1886.nq.gz
│   ├── 700235be57c1b2872455c0be5333f59cf568e252.nq.gz
│   ├── 724370638fc188317bbc7dc868f1a571995fd796.nq.gz
│   ├── 737b8b4cf14a67b8fabc5c4f71f4bd3cbe94f87d.nq.gz
│   ├── 73fbd95a1f3cd9617ce5631fc4017c91e45d3846.nq.gz
│   ├── 771275f6e2d7d518a6380ece72de248931b068e0.nq.gz
│   ├── 78520ff24463bb7899cf95edaf29728df8012a35.nq.gz
│   ├── 79dff7d59b695a0d97ae9cb7203dfe87eab410a1.nq.gz
│   ├── 7bce94f5010f3438e649fbcfb9e7dfea501ae816.nq.gz
│   ├── 7ecd38e7290e051a4cd33a572e7ae3552f6d0262.nq.gz
│   ├── 83509a9dc1a8571ed13e497597420d8bb5f5da74.nq.gz
│   ├── 8613f0a5ace574bb685c37d13c7090227b12ae38.nq.gz
│   ├── 8d6dd4b6d2ff7dbf1665e640bbc85d841b9b3701.nq.gz
│   ├── 8dc7937cb2f881370130a0278bf571e2aca36748.nq.gz
│   ├── 9162d66ad27cf336874c35917039ca10c019d30b.nq.gz
│   ├── 91a5dc19b327e4587a817bb163e1f458b538662f.nq.gz
│   ├── 93c4b1b04c812595e437e206ef8ba414050c7ddc.nq.gz
│   ├── 9a0f3bce1395ae3819030b822e5d9076c85068ea.nq.gz
│   ├── 9fa710697f319d38e5317ea95afba89fb483f42c.nq.gz
│   ├── a540ff33df7ad0d5a9d02e7eb0e1ccdced291372.nq.gz
│   ├── a93a3d13ff7a52590d68e39c2e494ac16e2d8a0b.nq.gz
│   ├── b3dc9c45fa544908af28e95fc5e06e628365d274.nq.gz
│   ├── b63131cb089da3606a026090ebb373c950c41122.nq.gz
│   ├── b68ae42a8ccd5893d3d011c7314c75a455926950.nq.gz
│   ├── b69e9b216bd5c23b495409bfeb60b86ffaad9b85.nq.gz
│   ├── b8289e407604b8461ba63f62abbc9279740e3d6c.nq.gz
│   ├── bbc6a8bed4accfc4fdb3ae3630b584c5a2f70f14.nq.gz
│   ├── bce2e5cd4d06603c5289360030a7f379b5a6ad24.nq.gz
│   ├── bf8432d99823d62b0d79b7e9dcac10ed3446ac89.nq.gz
│   ├── c1f38648d2fae58ccd2ffaa01a0eac08beff4594.nq.gz
│   ├── c398367854675e4ae755b63b3d70485d87aa0423.nq.gz
│   ├── ce9c6a92e1bb40cab798d9f504d89c6336825d0e.nq.gz
│   ├── d09d61941e2c4771e04973c5b795ebfd515fd33b.nq.gz
│   ├── d18e1c7b1a306460596a0120f14b4d258b9df66e.nq.gz
│   ├── d4edb48cd23727c1e5770d320a61e2a83bb2cbfb.nq.gz
│   ├── d65b9f055e21ec81e5074b8f01b0231d7e1cb27b.nq.gz
│   ├── d708f86dfd7f139929be77498e015ae1c88784c5.nq.gz
│   ├── d71df71365249c86ce7273f7098670923b868fc0.nq.gz
│   ├── de0040dfc7cfb8866694e686cf9f972b8c7d193a.nq.gz
│   ├── debcf0d835dd4d950c08a8d0c4231d9b8bc1a864.nq.gz
│   ├── df678917dd75cea64f4b75da51a11d7731a57f3d.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e7735c06aa75c04c25a2e6eb5e00e72f8401dabe.nq.gz
│   ├── ecca4a0e2219e07f0718aff660548907ac566fc0.nq.gz
│   ├── efcb8cbc2043faa7caf4f92fc7488bd6914c934c.nq.gz
│   ├── f011f6243e0338cf1bb2c6f3494b5b99b62762f3.nq.gz
│   ├── f5b45fc157dac8340184000ec89b566611471a3d.nq.gz
│   └── f94f07f2dca8207252df26f4b59c69e0cbfd90ea.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 3b49b41d9e88377e3b0afb00815f77bd5740fc0e.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 100 files
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

[jaraco/recapturedocs](https://github.com/jaraco/recapturedocs)

---
*Parsed on 2026-10-28 by [repolex](https://repolex.ai)*
