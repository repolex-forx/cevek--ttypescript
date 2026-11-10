# Repolex Knowledge Graph of cevek/ttypescript

RDF knowledge graph data for [cevek/ttypescript](https://github.com/cevek/ttypescript), parsed by [repolex](https://repolex.ai).

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
rlex download cevek/ttypescript
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 0c36bbfd76f134dd7275e8d0f86458fbf94bf370
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 0c36bbfd76f134dd7275e8d0f86458fbf94bf370
│           └── chunk-001.nq.gz
├── blob
│   ├── 02610979691af66ee350f8341ee4d5526e3be57b.nq.gz
│   ├── 0378be130732b44fa671d0e556a678704805ec28.nq.gz
│   ├── 0388d864d344eb9ce7e6980398d38dd000ab2e18.nq.gz
│   ├── 19c62bf7a0004aab7bd188aae51ff2564fdfc18d.nq.gz
│   ├── 1c07d44f9c5489a68e7d617bc99a2e948d0595cc.nq.gz
│   ├── 293c5681ad9295ed818658919fcd7a5329fa4291.nq.gz
│   ├── 2acdca39c74af638e97916c7e73718506ddd7aaf.nq.gz
│   ├── 2bc789c7bca7d64334b3a4d783a5d8b644540f6d.nq.gz
│   ├── 3169b181af32eafd20b5a149dd6e4cd4ffb2b4cc.nq.gz
│   ├── 317cff620a78a580eec36713372c6975efa44301.nq.gz
│   ├── 33859e93a026b70349b33f700286c37038bbe31f.nq.gz
│   ├── 359e72fe9edfd1b323e3cdb48c0a0209ec265e84.nq.gz
│   ├── 3ba8fec92bb2dcf328c774a3e4a4bc20664df2aa.nq.gz
│   ├── 43964d2558448dd847ed3d01b72a50437ab2ded5.nq.gz
│   ├── 4622fba33e5e7eedaf27d216990c8106571efa95.nq.gz
│   ├── 4683bdd77e031d563075eba6620747eb30c7e5fb.nq.gz
│   ├── 51de167208e22563a3ed17c2f6088392561c4666.nq.gz
│   ├── 555241cdd30d6fd28a87ae11ee7ca217d1efa82b.nq.gz
│   ├── 59f4ca1081126fb295e834a1b1ccbe358e4c8bdf.nq.gz
│   ├── 5e32f5ef83dccc92a8cdd9d01dde95f7170b263f.nq.gz
│   ├── 614150dbde64fce4fb9dc92a081b8718e04dc2ec.nq.gz
│   ├── 6237af2a6ae36f4bebe151e0a744252f7d052015.nq.gz
│   ├── 65bb0e1104059b3ec268dd2900eca1de2bac2127.nq.gz
│   ├── 6e6cfff38427155a21d2a9ef6e6381da63625adf.nq.gz
│   ├── 7143b6a73ab8a901ccf93752cc36f8e9f8191d93.nq.gz
│   ├── 71c4e015b0fdf56ec227d445cd259d19787f3627.nq.gz
│   ├── 81979740c849539fde863fe0ab5e4cc8f31172af.nq.gz
│   ├── 83e85a7ed846d49c8d38b29cc6425eb0ecbccedc.nq.gz
│   ├── 8b137891791fe96927ad78e64b0aad7bded08bdc.nq.gz
│   ├── 91cc67626babba6b1bd2c76cdec5f57ba467176f.nq.gz
│   ├── 9b55fa59752b5e5c8b27ad45377ed2c4a15214ed.nq.gz
│   ├── a005c76ff04af2d88d0a775d27048550023fbc59.nq.gz
│   ├── a22d3180dc5fdc6788779f0068c88cc1b8cca3ab.nq.gz
│   ├── aee09e82d736b02d4fe9c2c9bd3ee4aebb4753aa.nq.gz
│   ├── b0e7fe4fd9178faa45c8c3137678288a30015352.nq.gz
│   ├── b2115e59cf6b7e0e6562f12b3fecf4754269be19.nq.gz
│   ├── b28737a7e4e622f8fb0900926666143962f09bb4.nq.gz
│   ├── b2ff992b806a585f219c794450ef58b0b2caaf49.nq.gz
│   ├── b3440e75675d7bf2abbe0633c3686f669cca12d5.nq.gz
│   ├── c62aaebb79ca9e38c1c6455900eacae1780814eb.nq.gz
│   ├── cc88005eac1f1f777be8817855189dfc25d73792.nq.gz
│   ├── d4234cdbd1d4dc10fefd2b961aaa8f5ce826eda1.nq.gz
│   ├── d728467fb09df53f66476228020b40ff8c6ee141.nq.gz
│   ├── d7459d12073ddc49b1e69d51f00c9ce78bd1d965.nq.gz
│   ├── dc9f0fc78ba68d5fd5af5a38c91c9a9831570e96.nq.gz
│   ├── e30bc635674ad265a486366eb4be21af21576f31.nq.gz
│   ├── ea1b740f8e1519ad48d6f8267abc7298cbf58c7e.nq.gz
│   ├── ea3d0cf4800785347b43b57a6da99d11888f5f01.nq.gz
│   └── ef6969c9996bb844483a0b06786bd00cfb44bf90.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 0c36bbfd76f134dd7275e8d0f86458fbf94bf370.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 57 files
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

[cevek/ttypescript](https://github.com/cevek/ttypescript)

---
*Parsed on 2026-11-10 by [repolex](https://repolex.ai)*
