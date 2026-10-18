# Repolex Knowledge Graph of cool-RR/PySnooper

RDF knowledge graph data for [cool-RR/PySnooper](https://github.com/cool-RR/PySnooper), parsed by [repolex](https://repolex.ai).

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
rlex download cool-RR/PySnooper
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 4be5c156ffc3315011c42ba521c4d8487052d289
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 4be5c156ffc3315011c42ba521c4d8487052d289
│           └── chunk-001.nq.gz
├── blob
│   ├── 027a7f20ae12f41651b2cbd17551e97a9ee0c7e8.nq.gz
│   ├── 03dd32c947d7561936bae36c4d25c1867391941f.nq.gz
│   ├── 052b465cffec9270c4ad454127311822cce46de2.nq.gz
│   ├── 0b734a3bb3b9c15dadf25dce8df1f4390a546b0c.nq.gz
│   ├── 1495159d57b6e3e381c4486d067b718cf0dae884.nq.gz
│   ├── 17d88051ee68c1d43ea1e9aeadfa125d213050fb.nq.gz
│   ├── 1d744e24db8271214e23dd83e4f26cc943a32a89.nq.gz
│   ├── 200bbecebed9bad20036f157df6a6257e0c5f44a.nq.gz
│   ├── 2229c38aa40960f27f55e929b3aa80a239b612b6.nq.gz
│   ├── 222efdca6dc3a570b81adda5bc0cd792e7c4e66d.nq.gz
│   ├── 225fd162e8e78c37cdb170394fe0ce1bf3bd04a2.nq.gz
│   ├── 2a5ab02fa7925142045285eb2b223b10c40b7877.nq.gz
│   ├── 2d9580b2f72b4b0861a3ceeb0a6ec90eb3e20c99.nq.gz
│   ├── 301e8a5627f143d7b6805c891b8d2010ef566a05.nq.gz
│   ├── 3184e37a551d38c7767486d2620e89a192df5111.nq.gz
│   ├── 35df35a0f4d4c735e555aae612caf3a7ccea7095.nq.gz
│   ├── 3d3d00dea3adc59e73f37955d4a9423f5175f1ec.nq.gz
│   ├── 3ef1b0390c92fd3f4ba3bb5c188bf07f1d40994e.nq.gz
│   ├── 4ac21c3decb681a6f48c10e329a8558be84560c9.nq.gz
│   ├── 58059a0ee3b847583ea1a94b6df7778ea8342e03.nq.gz
│   ├── 58c08229518cd595f2a1eb3d1f94cd116e8ab0c6.nq.gz
│   ├── 5f56de49bacc55a57ad839f3d95696168918cd08.nq.gz
│   ├── 64e9d0bc03d9c3b31877f865be57d6f15f99c3ef.nq.gz
│   ├── 7074e07cbe425f4d7f02184d01059e52bd72b481.nq.gz
│   ├── 7f1f4d0af10e19aa2b4bc6b1798dbc5b634427e7.nq.gz
│   ├── 8bd76ac04a5177f003861250949368db7c022f8e.nq.gz
│   ├── 9df3d1918db81d402de88a13dbacf104ffc191bb.nq.gz
│   ├── 9f78d1b6a6da73cd8a67e2c710b69f19080dae4e.nq.gz
│   ├── a3d2d98f65800e5eca52800f2c86ffe71aa860ce.nq.gz
│   ├── a3e6dfdbcadbbff8dac48feec7cc9a3b46b64682.nq.gz
│   ├── a56e0efcc52450962fcf88da027b469dbd39f401.nq.gz
│   ├── a5e469eec5921bd7b6547f2e42da3496260621e3.nq.gz
│   ├── aa6e52643b15c5c20bb51492f18e94d7d757c414.nq.gz
│   ├── c80d79dc41e500b912e6e28dd6e285825274e170.nq.gz
│   ├── d36ce6093a71a332fdda5c6dad5fd848a08670c0.nq.gz
│   ├── db60abd54a29bb59764162ecaf1f3134757d4155.nq.gz
│   ├── e633a72849e19965eb7ada3f6162a48279cf2a63.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── f08df14ce54012f7bb6590aa584eeeb910557541.nq.gz
│   ├── f1968436257b8aebb50518337fbba4f75cd2c387.nq.gz
│   ├── f855e0082c1d58fccd179b958dab3c5cee8275cf.nq.gz
│   └── fed528d4a7a148fd0bf0b0198a6461f8c91b87e9.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 4be5c156ffc3315011c42ba521c4d8487052d289.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 50 files
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

[cool-RR/PySnooper](https://github.com/cool-RR/PySnooper)

---
*Parsed on 2026-10-18 by [repolex](https://repolex.ai)*
