# Repolex Knowledge Graph of tiangolo/markdown-include-variants

RDF knowledge graph data for [tiangolo/markdown-include-variants](https://github.com/tiangolo/markdown-include-variants), parsed by [repolex](https://repolex.ai).

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
rlex download tiangolo/markdown-include-variants
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 6bee43fcda6c1997f0c08b5f1f7cb7e511bf9c06
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 6bee43fcda6c1997f0c08b5f1f7cb7e511bf9c06
│           └── chunk-001.nq.gz
├── blob
│   ├── 03a1c05922a0787e68a6803dc8629025bce55f7c.nq.gz
│   ├── 0477c3d1deb7157b594541a7e8a5e8b20102f29d.nq.gz
│   ├── 06cb182ddf9b860cc0c73ff78d974726cba566ed.nq.gz
│   ├── 0b1f614647bd914b962ada70b6c3f24a95388cce.nq.gz
│   ├── 1591365077b207a09fca211cc2654400cbf9cdf6.nq.gz
│   ├── 17bd4a8da46b2b702ccb029a51b21806a6f24015.nq.gz
│   ├── 1a2d342a2d550632e50083943c1a53ce88889024.nq.gz
│   ├── 20d28376f4964185940ca8b79bcdd527dcf715ba.nq.gz
│   ├── 21af3d8e786fbec46f38c1aa8c718ed0e2ddf25f.nq.gz
│   ├── 2461d468146d4893a971c969c2a6c3f6e6201902.nq.gz
│   ├── 2e5e42001c7155d68abbc5e5428c20e87839b211.nq.gz
│   ├── 318b68afc3859d3e323b5de4c6ca7f5e2a350b5f.nq.gz
│   ├── 39604494de5c19f4c66858788c52c58f621ec792.nq.gz
│   ├── 3dae60a5149d757e60a7bb65b22ea109f7f10c41.nq.gz
│   ├── 411e9ac15e3fbae25447c32026ad94a6ce848cb0.nq.gz
│   ├── 44407f6b8d88d5e72c7a6ad3f1299e3222b72f40.nq.gz
│   ├── 5a06bb00540977c5ec8f9d2210ec9dc6a706bbd7.nq.gz
│   ├── 5ce095558c76329e1da9aa603da513ac8c0805f3.nq.gz
│   ├── 5ec08609c35a7e9cfe1eee10d48c77a8d6b1ee05.nq.gz
│   ├── 602fc7272d41be835466e527387d30a274aa95a2.nq.gz
│   ├── 6d5610afdd68bd33bac3de4f18111324bc564f02.nq.gz
│   ├── 6f45751272d8da0bba7709477cd83475c0ad6f72.nq.gz
│   ├── 70cd4435dcdf46ecd6ed08d126a0f7bc40cca988.nq.gz
│   ├── 7b86131e9d62c78467dcda590e3675abe00d4f16.nq.gz
│   ├── 7da7d7f4c81a2368b15bdcb2011e84e33044f29e.nq.gz
│   ├── 85a378996886ad54a9bc07c6999ff2745caa8dd3.nq.gz
│   ├── 8c09ee3aa6bea42b8743714cc3cc770b2f719399.nq.gz
│   ├── 96edc7b212ad6f5b674e88bc7452ffe840bc34c9.nq.gz
│   ├── a4cb856a41d1fadc49163fed649c6d7dd70ca143.nq.gz
│   ├── a512020e6ec5b08646e34ef9f276f8bcae97b7e8.nq.gz
│   ├── a73339bf81370efc24e667e80c0cd6d8b8b80687.nq.gz
│   ├── aa0abb67b099225d15023a60138deade2bb53f62.nq.gz
│   ├── af4285cc4cb1530e98975f25502b09c8534f04b6.nq.gz
│   ├── b1450c451cf94efcf4426a68f898c6dcf5a2e3b3.nq.gz
│   ├── b38a5688ea24d59767eb906d5f8fad514d2360b6.nq.gz
│   ├── b65b73afdada60e901397be479ceed255019f90c.nq.gz
│   ├── b680a5fa76a360be11c7268079af6e0c60b460ad.nq.gz
│   ├── b7dd288305ae2f60f669341fbde036b564e47ce8.nq.gz
│   ├── bd28b9c5c27e0dfa60da94179ec9b23f2be8be0c.nq.gz
│   ├── bf745637b71aae59dab4a66d6c2038f4c40ef969.nq.gz
│   ├── c06f66f22afd77d7c26ed41216a05437211e5c79.nq.gz
│   ├── c5289e0ed283c7cb745ae84d335f92aa5dfa5442.nq.gz
│   ├── c5ad76dca2255a1fbcf8ad0f6106a7e6b2af071b.nq.gz
│   ├── cb37b562faadc19adb1637521f04c3036a701db6.nq.gz
│   ├── d1014661d5e924afa81e429beaf30c53fb9e849c.nq.gz
│   ├── d9c14aa894da6bde28ac32656852a601a5fe9abe.nq.gz
│   ├── d9d90842ca19d41e798495120bb1526a93efdbf0.nq.gz
│   ├── e1398c25d4fd2963955f36c53423bd0970b19d21.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e7012621c7ae40c227f1634714f3d455ba002ef9.nq.gz
│   ├── ec69490bdff92ab067f015dab3858c495a75e58d.nq.gz
│   ├── ef706eaeccc818c83d2921d7d1199f6ff9210a65.nq.gz
│   ├── f9288b379d7938599edb0fe50f36a18e04802884.nq.gz
│   └── ff4b114b186342c2380e790aa54ac24eb506b217.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 6bee43fcda6c1997f0c08b5f1f7cb7e511bf9c06.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

12 directories, 61 files
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

[tiangolo/markdown-include-variants](https://github.com/tiangolo/markdown-include-variants)

---
*Parsed on 2026-10-10 by [repolex](https://repolex.ai)*
