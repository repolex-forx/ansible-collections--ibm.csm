# Repolex Knowledge Graph of ansible-collections/ibm.csm

RDF knowledge graph data for [ansible-collections/ibm.csm](https://github.com/ansible-collections/ibm.csm), parsed by [repolex](https://repolex.ai).

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
rlex download ansible-collections/ibm.csm
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 2df0ff80399e1dba580066f2a0368d587b9178c8
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 2df0ff80399e1dba580066f2a0368d587b9178c8
│           └── chunk-001.nq.gz
├── blob
│   ├── 0164155b81025416095f31a4732098ec238e6476.nq.gz
│   ├── 073085d85cb808fd8652a6738dcee7fb98fbf55d.nq.gz
│   ├── 074585daf3e701159e2849567cae0b85b1b9e66b.nq.gz
│   ├── 0863a5b781596941acaf725205a65e757e33d9ab.nq.gz
│   ├── 0c87e3303d9400219fa0e1d449c6e368a98fdea7.nq.gz
│   ├── 1b98d5e0b45081f29ff58d1c863161503f53e6fd.nq.gz
│   ├── 202553280aca32f2a380eae850703a2d0e7144b7.nq.gz
│   ├── 233961cc331561657aa382048ea55ee6eb687f12.nq.gz
│   ├── 244eeb20e309a8915866b344e66a034ab07caef1.nq.gz
│   ├── 2f6d78b8e43c348a39e43ff5b2397c81ad7b53a5.nq.gz
│   ├── 33bda953ece85ca619398ef38debe3da0cadc3bd.nq.gz
│   ├── 3749e4f6b441eee578ee5b15b3d57ec52b1f9b5b.nq.gz
│   ├── 41bd0a2ef74793ac57d424cd12a6cf553400c4ea.nq.gz
│   ├── 4f167ca32485aa98415a20cd14e713ca8bd2fa22.nq.gz
│   ├── 56f62edeb5b554152b02bbc4450c62a823c4bf99.nq.gz
│   ├── 5d3b553c80fb87062bc2349e3bb47ae3e4559128.nq.gz
│   ├── 607ff1333a6f28ce69866d5e68adeb3081aebc03.nq.gz
│   ├── 77f2026d0b1471947d52d0b237afc12d309cd5e5.nq.gz
│   ├── 7e4742475d4d8ddbf8b5299b90196344c14bb86f.nq.gz
│   ├── 819b01efd240a00d7293b31ec592e47a67c73c61.nq.gz
│   ├── 81b4fe2354d639849437ff276fdb76cdf500adec.nq.gz
│   ├── 83551755e08f2d9bf9cfaa48236b1e2ed753ed24.nq.gz
│   ├── 837311e971571a729a2cf506b2ab7cbf6bc853e3.nq.gz
│   ├── 83b6509b9b0d7efa88d9164a47041a3512a7c784.nq.gz
│   ├── 8584e0f39170214fcdb9bb124acfbe2490ec9af3.nq.gz
│   ├── 89699587f68651607244c61dd4501f45b442bb2f.nq.gz
│   ├── 8e77af1243158540d57639c2e37ab73d43a8be9b.nq.gz
│   ├── 8eac80241eb2c7abb0ea776bc69dd351a6e25cce.nq.gz
│   ├── 9dccf7ef174657345b77b37626c52cdc0390117f.nq.gz
│   ├── 9fad0d343c07aa82e21752481014bb870092c693.nq.gz
│   ├── b38a33010991fea3d106fdc7a11931b02eb988c5.nq.gz
│   ├── b93f88ac7386249b44a38c83e88827240fd75b5a.nq.gz
│   ├── c3caad0de5d160bf65a6c2cfd2a78c320114f23a.nq.gz
│   ├── c5b166034a42983bb9c9a7156b9cf906a5903787.nq.gz
│   ├── c9b6414700cdc9b0764d3211d0b8792ca4bb8cce.nq.gz
│   ├── cca89c5573ea0a5ff6112aaa0395d08d3414107d.nq.gz
│   ├── cdfdfb9286c4c934b54ea77131ec3474fde9111e.nq.gz
│   ├── d068b36fad3093ff40f3046f7e1053c781ac04f2.nq.gz
│   ├── d760eb5977fa8263affaab195608b0fbc56b128f.nq.gz
│   ├── d93f8ec54b92c35f1bf2ce39a3298e71f99666f0.nq.gz
│   ├── e5a81b83fac8ac9457c8806b71e8748d360240c7.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e7c5b3ed10198f4dfe154674ee1ff735d7a5174a.nq.gz
│   ├── ef7a15b508821b3b6fea858d1a354eae07f5474e.nq.gz
│   ├── f32a475f6132245b14d85be1b967485f9e3f52a0.nq.gz
│   ├── f9940b724b198d06407d7217daecfbe219234a37.nq.gz
│   └── fe4ff4b29f5fa920172e92db1226f4611b2427ec.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 2df0ff80399e1dba580066f2a0368d587b9178c8.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 55 files
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

[ansible-collections/ibm.csm](https://github.com/ansible-collections/ibm.csm)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
