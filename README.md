# Repolex Knowledge Graph of allenai/cached_path

RDF knowledge graph data for [allenai/cached_path](https://github.com/allenai/cached_path), parsed by [repolex](https://repolex.ai).

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
rlex download allenai/cached_path
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 54c53d7ed5ff38743397d92ac8a1d77dea9a19ba
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 54c53d7ed5ff38743397d92ac8a1d77dea9a19ba
│           └── chunk-001.nq.gz
├── blob
│   ├── 02b7fa4219066d67c6461cfc7ae0425597235254.nq.gz
│   ├── 07a5005e323d668eb7e4c8fec7da00a781cd3890.nq.gz
│   ├── 1306a6cf226499541c62211be7326f48ec64724f.nq.gz
│   ├── 1445f4c19c056b58bceb72e3f9af3ec7e54d861a.nq.gz
│   ├── 1aaa6139b623ca31250621b7c0f08b7d26795f8f.nq.gz
│   ├── 1eeea8b310442ea1040fad259a0121e4759e917e.nq.gz
│   ├── 1fd08ed1aa00e00fdfc6e98c4c878ca397f872aa.nq.gz
│   ├── 22c65d51231b0495ad5080704bba6affda1fd380.nq.gz
│   ├── 26527390fe6f589e54f26a010a2f0a403dff929b.nq.gz
│   ├── 33f1eb9f95466ca4e4b7f4fcf617a92abe42c14a.nq.gz
│   ├── 343e67fe94bfa83e8ebfdd3fc4913994cbf56fd9.nq.gz
│   ├── 378eac25d311703f3f2cd456d8036da525cd0366.nq.gz
│   ├── 3f86662bc5f5a906ddf67152e0f55b3f3de45181.nq.gz
│   ├── 4059acaa536824548cd5d2bea5e8d3d00211067a.nq.gz
│   ├── 460b834d06d20dd313c0e06b5ae408ff87111866.nq.gz
│   ├── 47ad494073ecb24c6bfc59833813922588baeaa7.nq.gz
│   ├── 486d510ac773eff8c13ac06d9fcbdaa55d66cb16.nq.gz
│   ├── 4a7f50190e3d89f42361ccac8708f3a1005c1b54.nq.gz
│   ├── 4cea4b8c8a404d20c4760de756820c1b388f33ba.nq.gz
│   ├── 4f95effbb08d84429443288fa585a12670e47689.nq.gz
│   ├── 50aa4424ab7dab0d6690435596dabac073e644ef.nq.gz
│   ├── 539752310339a5b4e438a3ff234f69d955e60772.nq.gz
│   ├── 59e311702c57912d8eca103689f4f43f4f4334fc.nq.gz
│   ├── 5d5a659fc126d84f8ebf7e2c839f346b8992a673.nq.gz
│   ├── 63b5e66a031f11abad8e39195911ecfbf3781e54.nq.gz
│   ├── 6422ee31adf33e90957b97d6881264979003acbe.nq.gz
│   ├── 67d158c82a2ada46a85718f0093c36f29066bea4.nq.gz
│   ├── 699cc9e7b7c5bf63c3549abe36e3eecf8efab625.nq.gz
│   ├── 6fcf05b4b76f8b9774c317ac8ada402f8a7087de.nq.gz
│   ├── 7341b242e60b7fa0e7d4d6dfb014d262e34a75da.nq.gz
│   ├── 741371b8685308e0a39c59746ea191444fd57f5e.nq.gz
│   ├── 766b36d2e7dc2c20cb8072a0566cb20b7b25de80.nq.gz
│   ├── 788b2b0f6e66b7a52fd1fcda0d8d2f85d75ddb35.nq.gz
│   ├── 78f72e77de8a0f33bafca1a0f97a3ae3653e4ee3.nq.gz
│   ├── 7935d935a29566a52381286688211525abfe845f.nq.gz
│   ├── 7c823877b6f7633ced3694414c4054cbf272483b.nq.gz
│   ├── 806d4473c47b3469af434af714495d8626281425.nq.gz
│   ├── 824da8d26a1289bf0d1cf4476380942d88e347c7.nq.gz
│   ├── 83a8f1928f5776947d4bcc25cb74cef6cec7c36a.nq.gz
│   ├── 8a00648b474c6b13dc3febac99c67d37c6cd433d.nq.gz
│   ├── 8a53d9cec04120605bfe44710dbf47f16243c22c.nq.gz
│   ├── 8bf2ba45e79d36797f5610d05c03b050edfee644.nq.gz
│   ├── 9029017735769024712acde7b6a16937046f6110.nq.gz
│   ├── 95c7913eb1bb2f2405bf9e9ef13dedbb0f9ac962.nq.gz
│   ├── 9679691e0fbe87c3b4fc893700782d6ca49eabe1.nq.gz
│   ├── 9b259bdfcf9022e7f4999a318ab7261300644e11.nq.gz
│   ├── 9e63e53b7a96e7f9e61270b49f9625e5fbdb8b9d.nq.gz
│   ├── a497d89b36013af9e734b6c3d9afa2182630c959.nq.gz
│   ├── a5618beff3f27804ad1149ee61850b052da16016.nq.gz
│   ├── a6cd511ab0970757c2020a7bde28ca7c56071f4b.nq.gz
│   ├── aa9577d7a2e8a393543bcd9ea5d3b0563fd738a1.nq.gz
│   ├── ad93d35abdf26f3096530a96edb6f7479c83ee90.nq.gz
│   ├── b53c64f27fcd3717b34b56bbd5ec6c51a994d485.nq.gz
│   ├── bbe89b010844b927ebc0738849fc47de3302a78f.nq.gz
│   ├── c056c0bc71a98186864f55112b7bdc9ce54497c4.nq.gz
│   ├── c5969ef225346d271038da15f3983917192602ab.nq.gz
│   ├── ce5f862fc1628308bce60c4e913735dc55dee7b4.nq.gz
│   ├── d0c3cbf1020d5c292abdedf27627c6abe25e2293.nq.gz
│   ├── d11db528fee328a1a79759bdc490705d69fa70d1.nq.gz
│   ├── d43ca7201d4b4628dbb81389885c6fa994e9ad79.nq.gz
│   ├── d4bea20edb075d71cc1f8a79ca9653849157de2e.nq.gz
│   ├── d7879438b8ba604871f68feb5bc7b647f2ad6ca4.nq.gz
│   ├── d8ef4d99253788df5bfdbe3ce6ce2b135aa04117.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e83189a4054a157b38c11b6e81fc52eb5da22790.nq.gz
│   ├── ef2c0384ddc1efa5945a381ee2ba45129d5035c8.nq.gz
│   ├── f8723ab2050a8463360224bf74d497c8acd7010d.nq.gz
│   ├── f939e75f21a8badb5c40f527abd0e098fe9bc472.nq.gz
│   ├── fac8bb2ba76779f36ae7af61d36ccd1f59f69ae7.nq.gz
│   └── ff915b268aaa18d546203a1920c2749d9072b073.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 54c53d7ed5ff38743397d92ac8a1d77dea9a19ba.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 78 files
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

[allenai/cached_path](https://github.com/allenai/cached_path)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
