# Repolex Knowledge Graph of trevorstephens/gplearn

RDF knowledge graph data for [trevorstephens/gplearn](https://github.com/trevorstephens/gplearn), parsed by [repolex](https://repolex.ai).

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
rlex download trevorstephens/gplearn
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 0390aea8639ce5f6c0b388400e07b58c05acad6a
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 0390aea8639ce5f6c0b388400e07b58c05acad6a
│           └── chunk-001.nq.gz
├── blob
│   ├── 05cb907f0d689892e2f6b6dddaab34ba43d89552.nq.gz
│   ├── 077cc53ea0e1810f20057cd4f1be711d8d1f10bc.nq.gz
│   ├── 07e10d114411f53f0dd5770242efa4ddb000dbe5.nq.gz
│   ├── 0dd83854e8a85ee987e2554091b5f7baf857a0a2.nq.gz
│   ├── 173367ff1db4d26c45836a47bb523bb89decbdbf.nq.gz
│   ├── 1863efd126d89b4f23ad62e3bc307a8861fce235.nq.gz
│   ├── 18a2ca750a56508d0b654f1eb37281c9c13103d0.nq.gz
│   ├── 1cdb000d474d4aa6efbc5ba1d241bf17547fe1f7.nq.gz
│   ├── 2178930dabc77eb85883e9a1ac9ca58abf667e1f.nq.gz
│   ├── 24227b3b898be14f023c0663c869abb2b65ecbd5.nq.gz
│   ├── 266e5d8423aa6db80dc1291df2e071fa4b0718d8.nq.gz
│   ├── 290c2350afca8351a09948974b1ca59b95399424.nq.gz
│   ├── 3819e840e56403b418394da13477600b02503627.nq.gz
│   ├── 40456197e90751ebd4f56259f84702af4bff5de7.nq.gz
│   ├── 43ad0bfe03200e791cb0575cf268601965e0e385.nq.gz
│   ├── 51ae7f4d69f5bcfa7f25a3e2572a7947c5ef15d4.nq.gz
│   ├── 5438612cb661cb5ceec9a48de03ed467d2392e9c.nq.gz
│   ├── 5465e110066460261bf194972e3162a11e22b3bc.nq.gz
│   ├── 555f549b6f4b894758289bb4f020bf6cb89c1635.nq.gz
│   ├── 6a22776e766165a20c55af91b5f005de2a291184.nq.gz
│   ├── 6d5814661d2b2070b1dc73cb49fcf525df6ccd15.nq.gz
│   ├── 6feb3fbab14c1e8f7489dfd4866639812aec07e9.nq.gz
│   ├── 7bf5b2a98950836a7e10f5557b9996dfeee0b50f.nq.gz
│   ├── 7c822d3ff72f981a6e64a9cae8a8071a5497d7b3.nq.gz
│   ├── 7d57832b75c83c68e5f31571646140df9b01608f.nq.gz
│   ├── 7e6b583c595f44a5796b6e5ed3ad81f6205ea6a3.nq.gz
│   ├── 7eee1bd530834def5c9fdb321ff78cc118b6c8ad.nq.gz
│   ├── 82b83338f8b151aeeaaa213730cd27fe3eeb8b90.nq.gz
│   ├── 876059a4a2acc682642cffee4894fbff507eb56f.nq.gz
│   ├── 89484f91229c5d5b2ab5e35447ce66ba46b1a429.nq.gz
│   ├── 95948ea2ce7767f6559765ccb003755935b132d4.nq.gz
│   ├── 977105702d398fddec7d23967e0138485af77a87.nq.gz
│   ├── a23aec6bd13edd3f5ba26f91c701e8c635de6f3e.nq.gz
│   ├── a4b346749b8308a593557724f383bfe03c15aec6.nq.gz
│   ├── aadaa3fc070071b8e030d13e8e138cc821825bdb.nq.gz
│   ├── ac91c677113c2c21c4dd0a931540ac2096b93943.nq.gz
│   ├── acb692d75d977f763717e60755fbc20b6dede38d.nq.gz
│   ├── ae8d61aca034b2ee280498390051f7a4edab73e0.nq.gz
│   ├── b19a05051d9bf67377f74a4b78851b6d62da8c12.nq.gz
│   ├── b4764362d34df6661e4b89f6df6f4afcf269e0ae.nq.gz
│   ├── b95d490061a6f1f8ad895b5bfe261e1d96e2317f.nq.gz
│   ├── bd100118f2d1ce0bf79e9e583d8913df96b3d7bb.nq.gz
│   ├── c3dc94e25bc61fefc13aefe9bdaad505227dae87.nq.gz
│   ├── d55759abf9fed68729a26ed7755321c9ba976f98.nq.gz
│   ├── dd52f98c99d88b404b23b754f36b867705e2743f.nq.gz
│   ├── e0d640c7d3ef3f5d743152f1b79fe345fce60b17.nq.gz
│   ├── e2cd04ff01dda4c2067ec8a1960a29fbfcd34a1d.nq.gz
│   ├── e3731aeebb4e7fa7e6a29e3d154886b7fee1d145.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e6d8fec0b318e5f475807b34977f9227398ec827.nq.gz
│   ├── ed8cbe85f6a6ebfc67996811ec3837d497e6b0ce.nq.gz
│   ├── efaf6bd55eed52f4f370204b2c4ff5d4ad38d6af.nq.gz
│   └── fd99cf947f9f2abcca97bf95e375404e1978a4b0.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 0390aea8639ce5f6c0b388400e07b58c05acad6a.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 61 files
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

[trevorstephens/gplearn](https://github.com/trevorstephens/gplearn)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
