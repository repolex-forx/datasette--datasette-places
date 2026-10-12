# Repolex Knowledge Graph of datasette/datasette-places

RDF knowledge graph data for [datasette/datasette-places](https://github.com/datasette/datasette-places), parsed by [repolex](https://repolex.ai).

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
rlex download datasette/datasette-places
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 5429ce8eddcaabffc94d76da0e7f206a84c70268
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 5429ce8eddcaabffc94d76da0e7f206a84c70268
│           └── chunk-001.nq.gz
├── blob
│   ├── 0275adfcf954ba2495088dd8f5daf4e28ad38e94.nq.gz
│   ├── 081aecd1ad750c23eb6b08d10709a336a2609461.nq.gz
│   ├── 0ac2c7ba8af0a4ccf9acba4c4105a2b1db86be2e.nq.gz
│   ├── 0c9e0021ee924da865a159121da14033d301d2fd.nq.gz
│   ├── 0f1644b793a6de535fb3c925d861ac9e48d59f02.nq.gz
│   ├── 12abb23fcbfb47ebd4f183043be564f1e4a79ecb.nq.gz
│   ├── 13fb068a6ed6a990eacbb4c619e165de57b14b9b.nq.gz
│   ├── 166568311d23b7974aa03ce4b4a2480aae57478d.nq.gz
│   ├── 18dc1c17cdd69a47811968af7f678735ce386d24.nq.gz
│   ├── 1c295f0abe7ade741a33d2f12263544d5a49ddf7.nq.gz
│   ├── 2975bf87e601dc98f600e55d9fca40bed69e3514.nq.gz
│   ├── 2d6c4980ca267a6d6fd566b7d6b4d8601e957fad.nq.gz
│   ├── 3665bf36a6ebad6551729b0ef5c7b1a6b7757dac.nq.gz
│   ├── 48de16b2a54be2f40587ef9f47180fc49915c6d5.nq.gz
│   ├── 4b6df8f934dde8b6af011f753449d13eeb82588c.nq.gz
│   ├── 4eb451193db4f0dbef66ea2701fd067917624c75.nq.gz
│   ├── 4ed8a93e3a6b4d7d63951a6f9b175c96c1ae6e63.nq.gz
│   ├── 58c262340bf99d81051b6167e087cde8ea80373a.nq.gz
│   ├── 6b65cf0176a2c1406155dc8f481ff94016ce9535.nq.gz
│   ├── 6e3a280e685c3eccdf71b470daa13332f6c35353.nq.gz
│   ├── 6f0c460e687210a50b2103f5f8f98c8a058ff164.nq.gz
│   ├── 77a6c38e0470687df0a2fff3fe6cee40b21a663f.nq.gz
│   ├── 84c0c928749bfa5c667d25d9e922c1786ba649bb.nq.gz
│   ├── 88d3f122d66d9dad4fbed2c327233b8b856a6cb0.nq.gz
│   ├── 8aebee73f3445840dfdf3be10ae485f205227317.nq.gz
│   ├── 8b8cbd47f8f7ce7925755267f091482ff6a5df24.nq.gz
│   ├── 90ed3c7822b159452d4e8ac3d32f2a4ddaa83978.nq.gz
│   ├── 91128c795fa40230037462f626e4138eafe80891.nq.gz
│   ├── 9215649b8a600a91c0df96536540cc542e95c978.nq.gz
│   ├── 959f4af5035c8c422080feec728bc6e488d924ea.nq.gz
│   ├── 97687857662a015c6803da8d6f8cb6e075a92aa4.nq.gz
│   ├── a287f79cd6ef864b8a5af8f2062fa296d727a738.nq.gz
│   ├── a605a346c0545eb1d8acfd012b88c61ccf05e42b.nq.gz
│   ├── aba79118e1cb3950ae19cc24574549f4c9de05be.nq.gz
│   ├── ad724b502d6e75f26337051b37ace10c481a2a0f.nq.gz
│   ├── ba9c694b77244fd4cb52c6affb5f224797718ce8.nq.gz
│   ├── bf61d4cdb21c77f5eca47ef5a9d32185fad36c97.nq.gz
│   ├── c72420588c40fb33bece1c7fe534379ba1b72e55.nq.gz
│   ├── cf263fee6d6f64af3a15193e12cff5258672040c.nq.gz
│   ├── d16d456620801dc654ce92917cdfd7cb435bdc69.nq.gz
│   ├── dfd337bbec4b63c62d087f8b42701bb297155c09.nq.gz
│   ├── e3b1a418631995652a618b59a8652affcffba0f9.nq.gz
│   ├── e5704301f545febf6aec222fdb1a7c1726b8fbcd.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e82cbe4b5a785071aa40e1c99aa85de86dd7b497.nq.gz
│   ├── e926220535b0e996450c378007e181c89e2963dd.nq.gz
│   ├── f09e722c1443eefb47ce4efd914967a9b098baaa.nq.gz
│   ├── f893d05ae4df4844484f5ae43553fdbeba0f8a81.nq.gz
│   └── fc712804cae49a5226dfa0c6b97d618919965f44.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 5429ce8eddcaabffc94d76da0e7f206a84c70268.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

12 directories, 56 files
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

[datasette/datasette-places](https://github.com/datasette/datasette-places)

---
*Parsed on 2026-10-12 by [repolex](https://repolex.ai)*
