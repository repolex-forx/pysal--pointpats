# Repolex Knowledge Graph of pysal/pointpats

RDF knowledge graph data for [pysal/pointpats](https://github.com/pysal/pointpats), parsed by [repolex](https://repolex.ai).

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
rlex download pysal/pointpats
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 95ca252901aafb29607b05a10815f9d233196827
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 95ca252901aafb29607b05a10815f9d233196827
│           └── chunk-001.nq.gz
├── blob
│   ├── 09c90ec67cd37fb82ab693ecf041ba78a73ea81f.nq.gz
│   ├── 09d2529e0c009089674834f13417cf47f5a9151f.nq.gz
│   ├── 0a85eacaee1a92f798a287c6ea05872ec0b095dd.nq.gz
│   ├── 0b807689101c9e2c7f76126a9e6c0a82d80f5d38.nq.gz
│   ├── 1c35385003d9494de3670ff27f7055ce28c71439.nq.gz
│   ├── 1f696ac3aa9c4f00469a99c13fbf6bfc6cd78002.nq.gz
│   ├── 2a12f57b3bbf68a3b1d3d29e7be53f2dbc1f1b0b.nq.gz
│   ├── 33d45ce689ed92ef13b8edb3cd1d3135ac7d3a02.nq.gz
│   ├── 34edf5c6ebff0b536c3ed40281f76292e1524216.nq.gz
│   ├── 3cd75709d6cf418113a92de9ef53723a0b57fa5a.nq.gz
│   ├── 44f4ff32ccd2fd0ace322f8d35af56c6389be54c.nq.gz
│   ├── 4af08452cbb88fcdd03bd72133e26cdb1d5f1415.nq.gz
│   ├── 4e3ebb07a86e11684cb46d4bbc422661d8dd483d.nq.gz
│   ├── 4eb6832e8d47077883e4174cb662dd139792b4d7.nq.gz
│   ├── 51b0850b257f19577f48e1551092f5acbf7d562c.nq.gz
│   ├── 53c8d105e701a0a0e1ce982bb986de3a59228a46.nq.gz
│   ├── 5657375a26693d0f647d1dae0b3fc9f1ab2227b9.nq.gz
│   ├── 57b7db745efe936576432b6db0295d43c8a30d1b.nq.gz
│   ├── 5869e7e170a7a9f3e92e79ebc271b505dda29e6b.nq.gz
│   ├── 5a65363d941ce228b5c48d0b027abfd574b7467f.nq.gz
│   ├── 5a65a3b0239c08335842fd87b25b92a130b711f9.nq.gz
│   ├── 5f9c252daea94f4a5ea2c59fa7b3efe7326f0851.nq.gz
│   ├── 693180bf45ebff09e899685b0794c89c6b9680d9.nq.gz
│   ├── 69fb576e87c7a34344db5a49ece996aae0bb8357.nq.gz
│   ├── 6c1cdbe947524d18d566f966cb2c9fa87757b791.nq.gz
│   ├── 7416c71495f3be2eb308851eb58f3c2cedac8073.nq.gz
│   ├── 7b07c6555c4d83f77be37ace605ae883c4e0e83e.nq.gz
│   ├── 7b9877ee991a94b6f99c920e80e8c20a9f09628d.nq.gz
│   ├── 7e191c3127257f28096cf04543a037eab58f2dd7.nq.gz
│   ├── 7f62c03027e309630c7028eef2b30b3c73930b5c.nq.gz
│   ├── 7f6704e54e92dea5e0107c796cc5ad7178f54b7f.nq.gz
│   ├── 7ff010519bee8dfc5332ccd892481b99beea7742.nq.gz
│   ├── 83538b0eb630550b5ff5a67fa76a77a76657b68b.nq.gz
│   ├── 86258161033d07bb41a392b033c1973c3136b86e.nq.gz
│   ├── 87032294180e9994b3e92759def0d2a8fbd024fe.nq.gz
│   ├── 89d6f09057dc4702198c801c7b7e33482d556106.nq.gz
│   ├── 8b8b041370638e0b6dd5eabff03ca96e6359ba84.nq.gz
│   ├── 8d908a6758f2a39adb4b50ddc25a2efba919a66a.nq.gz
│   ├── 8ddd1d66d5e8fb159a68b55eaf2670942883532a.nq.gz
│   ├── 93ad15c7f96bde78716b60f1f5613fae3fcd73f0.nq.gz
│   ├── 96c85ac07d0efc992535eb2e5585e0616e615b82.nq.gz
│   ├── 9bc3c7a58f49001373e2eb20f2014f176ebfec86.nq.gz
│   ├── 9e95e44300dbc35dce2fcf58f12255f484047bcd.nq.gz
│   ├── 9feb65f936f456e3ad6371650093a723d05a3cf9.nq.gz
│   ├── a6df060b28b09dc7bb4325c266e16b5dcda7705f.nq.gz
│   ├── a80451d06240ad68b3b26f8039f1678cd759fb68.nq.gz
│   ├── acfff3142a0e963fc9edd290ace2e7a167f7e5ef.nq.gz
│   ├── b203b02e7ac9d6778666b8f710f315a4cfe0dc8d.nq.gz
│   ├── c0207a48f25d7e3f89f952b528368ac269d24371.nq.gz
│   ├── caa55e2056b5ee8cd66a40dfdf91dd6fa195f80d.nq.gz
│   ├── d184ad0d69031dbfb66fae1eed10a8e6cd537c1a.nq.gz
│   ├── dce912cef9bfe3ec5a723c3921325e241aea98f9.nq.gz
│   ├── dfa70fdb4139818975bf6a20a62bc1c72c23dad1.nq.gz
│   ├── e23b581010169d3e1cfeb763d5e97c64560119ff.nq.gz
│   ├── e5f1887af93bc9e41f2eab227e20a0e851516bd4.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e81b5981f2210914f65915d741276740f11e8e5e.nq.gz
│   ├── ea4a37a414c4dd6b51205f917cceb31a1b2be167.nq.gz
│   ├── ecb79b597ad8ddef00f9fa4c966ed3049a98d605.nq.gz
│   ├── ecf4b6fa4f1ba58895325a9cbde6f7d89ce72a2f.nq.gz
│   ├── f876719a034d07e493571b75f9b07a06ffeaa1df.nq.gz
│   └── fe900201f3e30771d3bf30a02ae1a87c7b764e94.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 95ca252901aafb29607b05a10815f9d233196827.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 70 files
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

[pysal/pointpats](https://github.com/pysal/pointpats)

---
*Parsed on 2026-10-16 by [repolex](https://repolex.ai)*
