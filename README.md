# Repolex Knowledge Graph of openai/whisper

RDF knowledge graph data for [openai/whisper](https://github.com/openai/whisper), parsed by [repolex](https://repolex.ai).

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
rlex download openai/whisper
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 86098128c0b4f24f0e2aa2994de830614b474227
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 86098128c0b4f24f0e2aa2994de830614b474227
│           └── chunk-001.nq.gz
├── blob
│   ├── 08134dedeae14d28110d6395576073d4a2f93b31.nq.gz
│   ├── 0876010eefb6a79aa719bf038a59c40fb8734a16.nq.gz
│   ├── 13d417bb20440b0bbe79871a47cb6135b42be5bd.nq.gz
│   ├── 196b48f62d3b6f0b77bac2b7dbc2df5e4cfb070b.nq.gz
│   ├── 1dec35cff26c5efb100f92a30aa3a782f9870473.nq.gz
│   ├── 21b90e737abc3fea0bf0270deb81e6e79e03e4d7.nq.gz
│   ├── 21c3a54e5ac2cd281e6253c901055f22dbaf2c00.nq.gz
│   ├── 2340000bc450b127911b5c53080042b60cd79520.nq.gz
│   ├── 28ea26909dbdfd608aef67afc4d74d7961ae4bb6.nq.gz
│   ├── 291bc4bb1f484e6553a5f87faee5568809b0b9ff.nq.gz
│   ├── 2af837570b1e6e87457179f07d63d046cbe0d4f3.nq.gz
│   ├── 31f1d6b4851362ae3af405b09309ec38ac884c36.nq.gz
│   ├── 3480e077d2fc94c521e1cadb2e66cde18138b3ef.nq.gz
│   ├── 355c500b2deb26057bd6bbbb37447d341c577466.nq.gz
│   ├── 471da0573b74319d4097921d94943425622344ae.nq.gz
│   ├── 49485d0090fc0b8bf7b052d0b9b031cd95a8a28f.nq.gz
│   ├── 56b29fbc888dd607c464ca90c427cf633b24f147.nq.gz
│   ├── 599221af593a0381463e462ceacd9740c1b81d1b.nq.gz
│   ├── 602bbe452ce937a9318ab13099da2696ce5c7bcd.nq.gz
│   ├── 616fd57ea7f7e17e8267c9bb02c6b1b32ad95179.nq.gz
│   ├── 67426aa1c9e68af9408a51fff224c3ac566634a4.nq.gz
│   ├── 74a1c3521d9af4a84a0aa65d95b0859138640799.nq.gz
│   ├── 79658fc751882c54fd1fe0dc015281ee19cdbecb.nq.gz
│   ├── 7ae8fabc67c21dafacfa3a4738d105de6f689303.nq.gz
│   ├── 7f89da0ec4208efb7e279cbfac3e69db935a7e94.nq.gz
│   ├── 826250f372c9234e13b8f06a24373d9fa7ceeca0.nq.gz
│   ├── 863e50d0907ade1d6dc179b3af7f55493a679294.nq.gz
│   ├── 8690ae71c5f24c96e1adce0ae26ce1f46fb769aa.nq.gz
│   ├── 896d5e3364156efbcf74d8c6961448ef46f1ea1c.nq.gz
│   ├── 8ee59200898cbdbae7a22720f35564167e262114.nq.gz
│   ├── 9bab838e8f56fdc98a036664e2fca35fb0f334e0.nq.gz
│   ├── a37a88f662ad1248e45bf60028add8ecad25cc6e.nq.gz
│   ├── a4edf0b719c10d28cd83f8c294449f99ff5d5dc0.nq.gz
│   ├── b2d461810955a6a601f9f743cf744215da557e27.nq.gz
│   ├── be006de9a1ae3b9628e796c74277cd6d61e0a34a.nq.gz
│   ├── be424e5fe4eec1458846f93f8868647f6bf2ba61.nq.gz
│   ├── c61c928faf178d508236bb7806f4c87bd6217eed.nq.gz
│   ├── d14f2058e759f8444666e5c58073ae688b61f900.nq.gz
│   ├── d25552598bb9c5400612159ed4bab92ce12a5ce5.nq.gz
│   ├── dfd78bc09628ec841a482e93f4ba1b89a030ea13.nq.gz
│   ├── e44b7c13897eae7f78beb220c61fe77429a3961d.nq.gz
│   ├── f19e3e00984aa80798d73ebbb0776f48b07d1ea5.nq.gz
│   ├── f284ec0453b2c5efb025963f6a56a5dc404f78a7.nq.gz
│   ├── f70e0a37bae2dca627cf8f69ee455cf0aea5f635.nq.gz
│   └── fcb3200010072f0dbf22616d2f5acd27f82c6b63.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 86098128c0b4f24f0e2aa2994de830614b474227.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

12 directories, 52 files
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

[openai/whisper](https://github.com/openai/whisper)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
