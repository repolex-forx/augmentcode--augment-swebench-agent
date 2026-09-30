# Repolex Knowledge Graph of augmentcode/augment-swebench-agent

RDF knowledge graph data for [augmentcode/augment-swebench-agent](https://github.com/augmentcode/augment-swebench-agent), parsed by [repolex](https://repolex.ai).

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
rlex download augmentcode/augment-swebench-agent
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 17d813385f50ec59d58fdfe1576f758ed3daaa4e
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 17d813385f50ec59d58fdfe1576f758ed3daaa4e.nq.gz
│   └── repolex
│       └── 17d813385f50ec59d58fdfe1576f758ed3daaa4e
│           └── chunk-001.nq.gz
├── blob
│   ├── 08f2f0bf4d83afa314f4a287e71a98ce462e4567.nq.gz
│   ├── 146c3dd6ad67cc6808974258e95e01e8af66519c.nq.gz
│   ├── 183c974fd4ca1925d6278be86ffb6bc13652aaac.nq.gz
│   ├── 1d396de6aa604418020a5bf980a3b3ec11f69abb.nq.gz
│   ├── 1dab672e73c1aaa587d5dd952053e1244f1b3714.nq.gz
│   ├── 1e018968cd43a9bfc68ab08b0f1aed67f6209a6b.nq.gz
│   ├── 2c0733315e415bfb5e5b353f9996ecd964d395b2.nq.gz
│   ├── 2c5c6b3c20098f525447a8f23edecd9f4ccf7727.nq.gz
│   ├── 36f95288aca3bb9ad82bf44957d865c094ad5a3e.nq.gz
│   ├── 37342986f58fb1022e5ad5383ecf328731744def.nq.gz
│   ├── 3a346e97e53b4735c27762c0ac5fcd3ee31009de.nq.gz
│   ├── 3ab0e379d252cf1938d5b3b754b4c68bb3ddfa2b.nq.gz
│   ├── 41a6ad23de1409487a4860edfd5ac07c4a3b6149.nq.gz
│   ├── 48f22b0b62166fff176b73e75481f7c994b42268.nq.gz
│   ├── 4e1d1c8bda4b7ca12934522c397190b8310352d0.nq.gz
│   ├── 505361d0799d7f33a64b1e9c166a2fa655f0f773.nq.gz
│   ├── 53b48356014bdfb20240a7e328a5b7d4f4aec785.nq.gz
│   ├── 5aa79245fbb812ab29c7c0223b26260f30fb12e0.nq.gz
│   ├── 677d5fdf1e1a8bd4aa8f58820e493db31cdc70e7.nq.gz
│   ├── 6a13fd602a2dc7feaa8ec0d28bc9216165825340.nq.gz
│   ├── 70261082384f5fc37ca1c54853cf4f5312fbe474.nq.gz
│   ├── 73ee1a15be3558e31f649b2106a0c2259c6def70.nq.gz
│   ├── 76f677bf747bf4e783fb0fe0bd5241fc98e1b332.nq.gz
│   ├── 7a45a6f909055acee34e8067db9d48d2a8646a1d.nq.gz
│   ├── 7ef174578c87b0ed1c88258c1dd59f7475053ddd.nq.gz
│   ├── 83ed68a791fbb39a7ecb03da9eeeaaf146759e2c.nq.gz
│   ├── a3d9e9e3c4a5e15e3354ac9b560d22914ba9209c.nq.gz
│   ├── b113241eb6a47f16b663fa07d73b9d3ce7c90438.nq.gz
│   ├── be8a1199f8794e0cd5e16cae2be2c3829f0cf85f.nq.gz
│   ├── bed7ddae8e8dc16dc7deda7236e3de64bd420bbc.nq.gz
│   ├── c27420fad135ec678e9f630e4e152916e2c695ca.nq.gz
│   ├── c7ec2b5fa6340a7ab17e1117d8650a6e2ab267ee.nq.gz
│   ├── cbcba49b55c2ea441aa927f6d926168a4e69f2bf.nq.gz
│   ├── d28b7909905cae3831bf4a168f2ff1ff0571a868.nq.gz
│   ├── d2a6f011a5514905fb939ebb25235d12e51d3820.nq.gz
│   ├── e8f0a0902940ebd57f67e19ad05627d8711933e0.nq.gz
│   ├── ee3e3bf20282c53fd61904c187b11865db7ddd24.nq.gz
│   ├── f336ba8f34df65c2a1e19e98244aade07e7be4eb.nq.gz
│   ├── f622632a14adc56b56aa80056b944b4c28db1e39.nq.gz
│   ├── f6d4d80e1f9449ed0134d82c5c103b7bec8512fc.nq.gz
│   └── fecc03e888c9049217da460a858c2c2f426e7a51.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 17d813385f50ec59d58fdfe1576f758ed3daaa4e.nq.gz
├── filetree
│   └── 17d813385f50ec59d58fdfe1576f758ed3daaa4e.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 51 files
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

[augmentcode/augment-swebench-agent](https://github.com/augmentcode/augment-swebench-agent)

---
*Parsed on 2026-09-30 by [repolex](https://repolex.ai)*
