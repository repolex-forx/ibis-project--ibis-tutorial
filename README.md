# Repolex Knowledge Graph of ibis-project/ibis-tutorial

RDF knowledge graph data for [ibis-project/ibis-tutorial](https://github.com/ibis-project/ibis-tutorial), parsed by [repolex](https://repolex.ai).

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
rlex download ibis-project/ibis-tutorial
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 17696929a318f23e21cb15c22babfadd36a7906f
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 17696929a318f23e21cb15c22babfadd36a7906f
│           └── chunk-001.nq.gz
├── blob
│   ├── 004ec8a99309ba7f34d06a81867482cb7f83e328.nq.gz
│   ├── 008000b2cd362f9b7b2ecaa318a536811cdf85fd.nq.gz
│   ├── 0d270b8091a7a0c8151dcfaa98f1a6378530d60d.nq.gz
│   ├── 1100035e888ab3a1e5b2e7c7e42b023e391f2347.nq.gz
│   ├── 1262cb6c115b88f103e1fde1b5dcbbe4ac7d0d43.nq.gz
│   ├── 14004eed1bb0c57e54ed27e22a875c22e516f327.nq.gz
│   ├── 247f010e935bb84c7e64ea34092e6a81beb82a69.nq.gz
│   ├── 27def557be2f4909a8cb18ff6ba80b95b9f43641.nq.gz
│   ├── 2be0130091140b29333abed79b0e7de80961bc4f.nq.gz
│   ├── 31ee2ec1960b00744ec995ce3455f2a25ab7be4f.nq.gz
│   ├── 3408778059b2866086b84f8b78a59ddf8b0a1d86.nq.gz
│   ├── 3a2a2158e11c9070831840536455f5c5a670d181.nq.gz
│   ├── 3b6312e9df94a6f4c452bec2bd5028b3a5cc8f49.nq.gz
│   ├── 56bdbca21722bee3cabe3f84727ee5b73b10bfde.nq.gz
│   ├── 59de2bf209de8c3887ba0b45748d40c674a74bae.nq.gz
│   ├── 6c9634be15f1abdea6ace18367069787a1021219.nq.gz
│   ├── 70b393c74e66e5f19537e2dbf7cb53183414e668.nq.gz
│   ├── 7f0755bda1eb0064b005ab6e9686c1fc56c0c731.nq.gz
│   ├── 7fb3014f8861c24d57362a018b2163337110ff39.nq.gz
│   ├── 811ccd6a0fcd318de0dad3ec65f90bf3f1df0c44.nq.gz
│   ├── 88363999e71856f9420ca43a0379e4bab006ede7.nq.gz
│   ├── 89edab587cbe26c7459c4aa416164b360fe1ff32.nq.gz
│   ├── 8cfa8dbf30095af52a3d7a7b3c1df033968e323c.nq.gz
│   ├── 8fca061bf7c5ec6877a499b9a0aca4164c3a576f.nq.gz
│   ├── 92d93b9862216ce8eef1ef1062ebec6edbd919eb.nq.gz
│   ├── 9916a6de27b0b04ffbb9553d386bdc0cb52dc225.nq.gz
│   ├── a1e8a8995994fc82a7353443ed6b73f38d8db200.nq.gz
│   ├── abebeea598fbc3d7e6d9c110dc68a4bf650f1678.nq.gz
│   ├── ae006bd2ec7d35ae43949fb37a6306a1eebf5a8d.nq.gz
│   ├── b4805dc03d1a480c630ed6ed83b6b3c6e77dd180.nq.gz
│   ├── b75f7c7def0e21d78d819512997d458803a21108.nq.gz
│   ├── b7deb6b74ff2114356070038719e1f549b5691f5.nq.gz
│   ├── be83aa25b994fd1f16e0745bbdd5d3bdc05e8cb4.nq.gz
│   ├── c037db63acc7ad90abd4d325d6aa6bdd30c2ba31.nq.gz
│   ├── c06e9afc72b2154cdc9249c2b7f6a71ea145485a.nq.gz
│   ├── c38cb3059d39f50f64d602104ccd7c2b4a53fa05.nq.gz
│   ├── c3c15bbcf779ebdc4518324ed966697469973e08.nq.gz
│   ├── cde6bf40c045c6f32ba217120eb994677f3f9bb1.nq.gz
│   ├── d7815db6911a704bc9be52088ff6e195df834b5d.nq.gz
│   ├── dd533804df64ccb2a0b65c75411e0857129962fb.nq.gz
│   ├── e5bf902098e4e6d2485bab094aaca63f9048615a.nq.gz
│   ├── e8cd2e66ca1b371f10e94fb60d2e9d0dfd316d8d.nq.gz
│   ├── f1d1bb96948592dc5dfbcf2be9dec4e7d6fd8fe3.nq.gz
│   ├── f2053ed21c7e27eb9f0bc76e85fcc72bbca93ff4.nq.gz
│   ├── f22eee5b2cfb68cc5f387ac3cbaccf426e67a5ef.nq.gz
│   ├── f279156b7f2489483f9aaeb2d3add8b741e53c09.nq.gz
│   ├── f4c408a9e7997a24567f46f9d2d2f7d8bb3210f6.nq.gz
│   ├── f7d4ff11d713747d0d9ca3e9259499929e9fff4b.nq.gz
│   ├── f98f0cee1337dff9eef59e2e9f26162bc832c6fb.nq.gz
│   ├── fcc59b4be1aae09782ea9f3d69e13f88d4b3f268.nq.gz
│   └── fd6ee320f1af05aa66728da08296eddc6cbfe0a5.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 17696929a318f23e21cb15c22babfadd36a7906f.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 59 files
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

[ibis-project/ibis-tutorial](https://github.com/ibis-project/ibis-tutorial)

---
*Parsed on 2026-10-21 by [repolex](https://repolex.ai)*
