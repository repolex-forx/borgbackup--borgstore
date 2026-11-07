# Repolex Knowledge Graph of borgbackup/borgstore

RDF knowledge graph data for [borgbackup/borgstore](https://github.com/borgbackup/borgstore), parsed by [repolex](https://repolex.ai).

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
rlex download borgbackup/borgstore
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── f6e41c191a368ada4fe41ad22d31adff3489d13c
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── f6e41c191a368ada4fe41ad22d31adff3489d13c
│           └── chunk-001.nq.gz
├── blob
│   ├── 00ecceeaec67e2ff98c6390809e905025b5b1f9f.nq.gz
│   ├── 01ce68a37d484407571a6bf4ea45b1a9bdad2ba1.nq.gz
│   ├── 02c3ff926687310c482d8273cfc14352bad2650b.nq.gz
│   ├── 08c290747e92882b3bc28ff02e43e3ade8efb015.nq.gz
│   ├── 0a963533266c6b6bc690f39ed691e0fc6aaa5a81.nq.gz
│   ├── 0bf6bda35dae03d51aba6213e9dee486076aa33c.nq.gz
│   ├── 0fa56358d9bbaaf1e7595f62465b8d7a504eeb2e.nq.gz
│   ├── 10b461c4c9b6fac797a1332a90a3c6e9d886693c.nq.gz
│   ├── 28780a2c9ef9d16be7b01f0a914535000bf26562.nq.gz
│   ├── 2c539a591ff935661a1c24c7dd42eedc26ec3d38.nq.gz
│   ├── 2ddd8d0c8f71ad8e0bcf1e22cd2d3326c728e788.nq.gz
│   ├── 2f0b591e58a51f36acea0cdee50ff08a597c1613.nq.gz
│   ├── 2fa0a6ff036404efda34635771488f9cfd216646.nq.gz
│   ├── 323483e41c50a50930af37099ca93b4ab651c790.nq.gz
│   ├── 349277773434807ccec955b335b46f2861221f07.nq.gz
│   ├── 369e217ecb4af66651ca681e0d8efb1d38daecc0.nq.gz
│   ├── 37d083e6919215261e0e83a0aa12c4f8b53155e4.nq.gz
│   ├── 3daa7d1cadf1aa295ece275b4e8ce1586c923abc.nq.gz
│   ├── 42476f4268da1c9f808398d12e7d433b4ce89b15.nq.gz
│   ├── 42aa71c1133989f90214454cc661172bb727ee27.nq.gz
│   ├── 448bfc1e3b028259d8559c0cef5d9c0c7fe39567.nq.gz
│   ├── 461b1ef388843793c9611f8bea4d7823dfe173a7.nq.gz
│   ├── 46e5f5d79ad87344b5c51d51cb4b0a5ee0dbc524.nq.gz
│   ├── 52e593551da4b1a44bf4e0319a5379bb8ff9d813.nq.gz
│   ├── 53095e8f03af99c153fb203f071f98c9d6e868e9.nq.gz
│   ├── 584a0f4be4b97e0740d011a28757f463e74617fb.nq.gz
│   ├── 5f5113ccc35115b0b85ec50f8592b067cf38aa15.nq.gz
│   ├── 65724ab9aec833de2ff0b4a5268155c095ccce7e.nq.gz
│   ├── 6a45b1ffac754399ff6bdcab7b7517ab141fe97e.nq.gz
│   ├── 7b479a93d4d6d8464d5fbaeadd08a9033b61a20f.nq.gz
│   ├── 7f89185b46943b7a1ea7c5baf3dcfc336ac8a296.nq.gz
│   ├── 83307ee0ccffa8162bf9fd97e407bf20e07d896f.nq.gz
│   ├── 88395fa26c9a4adfb5894c978fb5ab4c7f189437.nq.gz
│   ├── 8c18200cfeddf54271c7512c90ccd699f7555bdf.nq.gz
│   ├── 8e4406c24a3923f93255c944416f5931f8df452c.nq.gz
│   ├── 926e9a5f64e0e2b9ad931ccaf26176c0226ad32b.nq.gz
│   ├── 9604d88d6cb1156fe8529c6f2a94b2b6cc9609a1.nq.gz
│   ├── 99b815e2a62415e53498339de7d39887ac535940.nq.gz
│   ├── 9dcf3069928b9d04a8e29a3fedb9be6c291fd130.nq.gz
│   ├── 9e704d7b0319a0355a79fb6dcdb872af17a55a98.nq.gz
│   ├── a0688e273f8edaed0b76645d0d2fde2e7b6051e1.nq.gz
│   ├── a8eef8efe6d1ccecc8d6c6d2fbc9f8c3955f0ea8.nq.gz
│   ├── b85fcd66e27cf38217787b439fd5133a1f9dd44e.nq.gz
│   ├── b90907ee12eabffb32e604a720d24f2d1a9a9179.nq.gz
│   ├── b9899610593b753e45efdd7d1828bc6a6f41e3aa.nq.gz
│   ├── ba2f03265f60f3d072430495e81408ad865df8c4.nq.gz
│   ├── ba388047dbb331fa9e377bcaca8f196914d9e69d.nq.gz
│   ├── c129ef8409de25be69ab0c1201efece162149f32.nq.gz
│   ├── c1b10c4021db441a30d61d317dc06b65317de618.nq.gz
│   ├── c2d577f73d7ec49e71a7d838c8b5cf90ee4e2ae8.nq.gz
│   ├── cabacb0b973691bac6792567cdd80ddb26ec6398.nq.gz
│   ├── cc9c3a058b2beacf8865fe1fc372c49df288e846.nq.gz
│   ├── d4bb2cbb9eddb1bb1b4f366623044af8e4830919.nq.gz
│   ├── d776a352892e34faf8f6f928db54611a964218f5.nq.gz
│   ├── deb47f8b8bac800a15a54b69b077bfe6b2ff3313.nq.gz
│   ├── e0d2b0b3cffa7c4a1f36bbdde0aa13185503b636.nq.gz
│   ├── e146b1a0e49f5e26798bde23aa267e9291e59e66.nq.gz
│   ├── eabb6d6e3df0f71d671984dcc585c540cea40609.nq.gz
│   ├── edabcf4edd742629b55b02636e13ba0b1b0044ab.nq.gz
│   ├── f385e9f327c8d011c812e47881ad42b5876f384a.nq.gz
│   ├── f399b21451ae0995532d313425ad0ebe97503a06.nq.gz
│   ├── f41ba268283f0e7ae672acbdb24173d84f0edc17.nq.gz
│   └── f814959c5f67e7a5ff63213785f0577c9934c5b7.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── f6e41c191a368ada4fe41ad22d31adff3489d13c.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 71 files
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

[borgbackup/borgstore](https://github.com/borgbackup/borgstore)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
