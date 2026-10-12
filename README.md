# Repolex Knowledge Graph of jazzband/prettytable

RDF knowledge graph data for [jazzband/prettytable](https://github.com/jazzband/prettytable), parsed by [repolex](https://repolex.ai).

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
rlex download jazzband/prettytable
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 5fec60c0fd85530e5299d8c6e39dc030bfd7ce9f
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 5fec60c0fd85530e5299d8c6e39dc030bfd7ce9f
│           └── chunk-001.nq.gz
├── blob
│   ├── 0be4f1243e5204b280284c98ae14af8e70cddb3a.nq.gz
│   ├── 0f9d417a4e3aa076329de1a19fc2681c44f2cf20.nq.gz
│   ├── 172e634745005edb344270f1e6b9bf84b30c65ca.nq.gz
│   ├── 22aa54c8b276356fe4c9f969f39ed32ab074b9e2.nq.gz
│   ├── 2a39e8164f32a9f8f441a2e436fa0ff9c25c2017.nq.gz
│   ├── 2e37f36b089fd107950602fcddd0767c9a4a370d.nq.gz
│   ├── 3a01fa8d595f49fc4bbd0e7bf668cc5c6bbeac35.nq.gz
│   ├── 3e1e73875d096cdb27ad278b495176e79211a653.nq.gz
│   ├── 40264bd565c09cf983d2e55b2af4ada516d55d59.nq.gz
│   ├── 462e6dfeccc67afd2c68a13b0953cbc0573bd8d1.nq.gz
│   ├── 485d85fea1f8ecb8a8c9a248511c44a6b13d8bd7.nq.gz
│   ├── 4ce713d32eeeeb9a72bad8c4ee89f9df4a9e4603.nq.gz
│   ├── 4cf2f389066bc681c2f959b1d33e8e7e3ed8f6e7.nq.gz
│   ├── 4dc5d86f520f9a617605d620de7b406870284693.nq.gz
│   ├── 52c3c694cba56b371c8ba4d1b3f01b921fe0195a.nq.gz
│   ├── 5876dcfeac45fd01cb14299dc51919477fa015cc.nq.gz
│   ├── 5a8d6611fb61daab57321f0f762f1718c25b46f1.nq.gz
│   ├── 68c38e23a6d5277fb4cd393a6de8035ef20288c0.nq.gz
│   ├── 6a84239ba63daf20b3c8641b9ecbae084e1ebc86.nq.gz
│   ├── 703e85dc4921f7a985ee2381cfe065db24d86179.nq.gz
│   ├── 70e6237f3cc81aa99089ff7e07d32e73e5de480a.nq.gz
│   ├── 7262ba665dc5ba2699bb72b122eb42110521fda9.nq.gz
│   ├── 77fd1aa5bb4ea9bccd6501bd957d61b7e939b5d5.nq.gz
│   ├── 7faa7c819211a0d5f451eb2c86b2127451457503.nq.gz
│   ├── 818461f944bb848437e895c6be7c76585f1bf9d9.nq.gz
│   ├── 889311b49011ed1673b9cdb1660f7cfa31adf02e.nq.gz
│   ├── 9468cd03c383a41ab55801fb7bb1d48a218a61dd.nq.gz
│   ├── a56611cb365199868aa261d0cb8010f042edf041.nq.gz
│   ├── a806b876e51bf918b8429a5e6fda00234a5d0a44.nq.gz
│   ├── acfd31c2a000eff69666a222e5e3eb950731ce54.nq.gz
│   ├── ad65ed9437801998450676f815571db71955fded.nq.gz
│   ├── b4b12198ee8bfd9dca23b1fda7f56293ac59d1c2.nq.gz
│   ├── bc4e4e8498c5395f0b2dd5992e20371771a58196.nq.gz
│   ├── c04b72c287622d4c0a533d0a31213ad4cf3eb290.nq.gz
│   ├── c0da2c2b05fa4ba3c2573f6e1f254720ca21d73c.nq.gz
│   ├── c25becb19d7fd0efff97346f5809b8d7b4a4c4ba.nq.gz
│   ├── cb6fed3eb821a2e0fb06a625c2af89b4bc4577ec.nq.gz
│   ├── cdb5c98fd92794825c84901a5696869038265b60.nq.gz
│   ├── db79645b020092d90e05255f405af89f8f84cede.nq.gz
│   ├── dfbb1598a4fcbb38d02a1e63f0fe1546e326086e.nq.gz
│   ├── e4d8008db050519a41105ecef1f7fdce9b8d6b90.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e928b5292825f1e0c94e2155cef2660ce52e3464.nq.gz
│   ├── f472440a53a040f2811cb7cacfba04b112182b4a.nq.gz
│   └── ffd1381a652df47e8c6a99465e486a6e80ee1812.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 5fec60c0fd85530e5299d8c6e39dc030bfd7ce9f.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 53 files
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

[jazzband/prettytable](https://github.com/jazzband/prettytable)

---
*Parsed on 2026-10-12 by [repolex](https://repolex.ai)*
