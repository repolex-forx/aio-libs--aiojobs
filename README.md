# Repolex Knowledge Graph of aio-libs/aiojobs

RDF knowledge graph data for [aio-libs/aiojobs](https://github.com/aio-libs/aiojobs), parsed by [repolex](https://repolex.ai).

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
rlex download aio-libs/aiojobs
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 154e3575c221cfeae57e36de9a6e689d16a948e3
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 154e3575c221cfeae57e36de9a6e689d16a948e3
│           └── chunk-001.nq.gz
├── blob
│   ├── 0b2f7b0655f41276d418ca8302dbaec8b7e7e829.nq.gz
│   ├── 13b78dbbc893ac0a492fecbb65dbd7204524a50d.nq.gz
│   ├── 14d9f09bbf4d3bb483a7957a4b48d474191fb25f.nq.gz
│   ├── 1bb61f09f702e3ae1b11b310078dce10df79788e.nq.gz
│   ├── 1cc2f4e456d39956f4f847458b3a5114faa40f2f.nq.gz
│   ├── 20cd0d2a55bf4bcea90c970709880d52480f9d53.nq.gz
│   ├── 227f0bba9aef1404df8468985d8b2ef7a43d02a1.nq.gz
│   ├── 2aa379ad0276dc7c1b9a6918c5fee4047d0775c5.nq.gz
│   ├── 2b87a55c5c088796ea09a749b0153c3a3e44b569.nq.gz
│   ├── 2dd98724b276b74732acbefbe19cf6a44649ca45.nq.gz
│   ├── 2f88959189eec492f83a0a1848dc0e996da9b07b.nq.gz
│   ├── 311442b2ff88ea079b91f2310a9281069f36cb5d.nq.gz
│   ├── 36979982708b367032730848375b2a457cf360b8.nq.gz
│   ├── 3a61d52fbc1daf6bec5f9e8ce1ea7c76ead08f4d.nq.gz
│   ├── 3fb15340481311b750e120dd070c6ef1cc6da544.nq.gz
│   ├── 407145b4476651041ef50802e9ebc8a8a7f9c6fd.nq.gz
│   ├── 451eb1a9a525256c431409f1ac64e13d300df365.nq.gz
│   ├── 4f11d41d92944d7a361f02651f0def9b2acbc806.nq.gz
│   ├── 56b6e563e1364e1c0ded8b87f83578010fd6028c.nq.gz
│   ├── 595cbb11ddfa75b0e747fca7f3a39f7977e66428.nq.gz
│   ├── 6ab31399fb1b59ff76c7412944ebbc3121517933.nq.gz
│   ├── 73a8c6e2faaf523b23df6c6f1913a119c34fdd79.nq.gz
│   ├── 75b88637f02817df474d3eebafc51669b6e7e637.nq.gz
│   ├── 8053aa2d590b9286d02be7300bfca1b5bad18263.nq.gz
│   ├── 8ea6f280606f8b74ae8c26c1352a97521022c52a.nq.gz
│   ├── 9a483c508f8b630e527bedc0e87918e1ff788056.nq.gz
│   ├── a209a6ad1780a80d5b3328b8bd12c51f6740b68b.nq.gz
│   ├── a5dda1d1bced3155928575073ca65372761a93b3.nq.gz
│   ├── a8320a28e43d3eb696999967c724102caa24885c.nq.gz
│   ├── ab25048e4542c9d70c677a3206248329b8d8bbab.nq.gz
│   ├── ab5f92a8e883647ec48878989c9a9d26e28c00e1.nq.gz
│   ├── b6ff2b54006ededf10dabdf0826dd55d0c692096.nq.gz
│   ├── b9fb8a6e0f4a5ce99899eb97d872c6b90f4bb678.nq.gz
│   ├── bdcd58cccceb837f33aec75295a3abb3ce738793.nq.gz
│   ├── c8bfa350d661c1d91e5022b1938c2f13fedec73c.nq.gz
│   ├── cef5daa63fc40ccd4fbf47c29545eb11c46963ea.nq.gz
│   ├── d6354c0c6d0aff3536fa8ead4df2de1504df27bc.nq.gz
│   ├── d9be53c373e9c596b96dd26235671ec3a2ee40c9.nq.gz
│   ├── da62c1e09b773e7ba5a4c8b0f1d43571b54b38b5.nq.gz
│   ├── db1e11d1252e5e39bb2b43179d8113207f1310b0.nq.gz
│   ├── dcf2c804da5e19d617a03a6c68aa128d1d1f89a0.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e7352237f0eae29984130df0cf335a97c15570ef.nq.gz
│   ├── ef61eb7016b7c45ccf402dd8fef15cd66d0aca80.nq.gz
│   ├── ef640734a1c87db2f613a608c0a01e3c6483dbba.nq.gz
│   └── f7768b9c46df7b83af946410c261fbe9457b4c5f.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 154e3575c221cfeae57e36de9a6e689d16a948e3.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 54 files
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

[aio-libs/aiojobs](https://github.com/aio-libs/aiojobs)

---
*Parsed on 2026-10-10 by [repolex](https://repolex.ai)*
