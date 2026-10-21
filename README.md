# Repolex Knowledge Graph of pydata/pydata-google-auth

RDF knowledge graph data for [pydata/pydata-google-auth](https://github.com/pydata/pydata-google-auth), parsed by [repolex](https://repolex.ai).

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
rlex download pydata/pydata-google-auth
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── ab923498a4f923c060c54e3b3913d002fc15bbfc
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── ab923498a4f923c060c54e3b3913d002fc15bbfc
│           └── chunk-001.nq.gz
├── blob
│   ├── 010e975cc01c153b43a1b36f0efb1863198e4cb1.nq.gz
│   ├── 038b005ed3217a6422a7956475b9f34eaf1042e4.nq.gz
│   ├── 0f5fe48db05c0c42fa4f4f0537f1112f3da061dc.nq.gz
│   ├── 101f090beddd5d9cf3f0b2a6546488c6ffa6ab86.nq.gz
│   ├── 14465db2c9d73ba25793439a83df228025e7de25.nq.gz
│   ├── 152c93a4236071a249247ec076ea83a068f37132.nq.gz
│   ├── 164a40c77a59077cc6061b4c9e1c703f1a0939ee.nq.gz
│   ├── 16a14b7f75d5821b7c7b759db71c7b8cdc957b41.nq.gz
│   ├── 19dbdae9e9718324c84f103be8d0b11e967a67b5.nq.gz
│   ├── 1a96e3642af391242ec0e3a9b4fd90da0f42060c.nq.gz
│   ├── 1c2f6eb814d2d4eef83c5fad4c7f8fa18a17f460.nq.gz
│   ├── 1ff53d2b94828b81b82582dd02f54672730c646e.nq.gz
│   ├── 20fef6fc033cb3a1eeb9e95b148805a1b0063943.nq.gz
│   ├── 2fd7fcb86cdf117d556d931b84959d484ab2a732.nq.gz
│   ├── 3e53d9080c7989352b22fdc59f8e044be694d91b.nq.gz
│   ├── 493d121122cc89f09483f873afb94ec108ad0974.nq.gz
│   ├── 50f5303c330dd4843d168f5dcbe085ee053ad54e.nq.gz
│   ├── 53f230ec0d56a39cfac9fed2a35be566acc14cc6.nq.gz
│   ├── 57a876769fafd0bc3c9ebe9f230bb19f618afe70.nq.gz
│   ├── 6ef8c8c06bbad7fa9a9240f49168999a77065d8d.nq.gz
│   ├── 7286198e96ddb902573b5d72a09437976982785d.nq.gz
│   ├── 776ae7a00fb26fa48e47b252ba7390c6c78328c6.nq.gz
│   ├── 7f69caf30b486ac45a15b7e1329a441de0ceed69.nq.gz
│   ├── 87946903327070dfb842f63510bf852c14fcc834.nq.gz
│   ├── 88453476604cefeec5c69c14b87e9c8341a9b1ee.nq.gz
│   ├── 89cb6807a59dc3204ab26ce1f01432a118e19fd1.nq.gz
│   ├── 924de26253bf437fe14610f9fdcf537935b1b3ac.nq.gz
│   ├── 96447080a84d3992a7642c1ba4d1afffbffaabca.nq.gz
│   ├── 97eda6586d38d1bf80551c8b319dd7c81f0ec495.nq.gz
│   ├── 9880bdb60134db5722f5061c9f26a1aa9e8e5bf0.nq.gz
│   ├── 99ce08bd35ed9fd5ca6941c7ec44f172d9cb3df0.nq.gz
│   ├── 9a206fd585547b2587031d4a10f7a3442c0c8a75.nq.gz
│   ├── 9b3bd341954d0b26f4cda1f703c96cb7e03f5607.nq.gz
│   ├── 9ccd1272642a78d6de32f3bdb1c75fcc28f96274.nq.gz
│   ├── 9ea95f57dcbf24dc3b0316ebe92ef708b14862d3.nq.gz
│   ├── a103dfadefc40a220d391ebaa7e574248e9d549a.nq.gz
│   ├── a2387af626d5b5534a51d2da06f4fde228585383.nq.gz
│   ├── a24df9970a349002fe29e380c6ec163b0bf4fd81.nq.gz
│   ├── ab6d1068585fdb9d4c1631593f66024fcd4d8223.nq.gz
│   ├── b05fbd630881531732d3137a7ae6882b3881614e.nq.gz
│   ├── b6692566943537a846bac66212bfe4847d233d6b.nq.gz
│   ├── c9f74cc996382856eb6087be5f5c7ddf41ccf1e0.nq.gz
│   ├── d297b485dbf9c8f98c495e145a0f9ac924dd0723.nq.gz
│   ├── dd77f038db1109c2cb0f94f974502cc049294102.nq.gz
│   ├── e56511b0d3390a381fef7ce466c7af7a03c7a2b8.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e87801cb0e81931b21119fb62e83aa678d7931d8.nq.gz
│   ├── f1dd65167d6a4def082cc2234c2176e92ee10584.nq.gz
│   └── f480e1a4ab6f53494c7bd2f9e05d2ee2b667b32d.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── ab923498a4f923c060c54e3b3913d002fc15bbfc.nq.gz
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

[pydata/pydata-google-auth](https://github.com/pydata/pydata-google-auth)

---
*Parsed on 2026-10-21 by [repolex](https://repolex.ai)*
