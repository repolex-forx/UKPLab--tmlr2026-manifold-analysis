# Repolex Knowledge Graph of UKPLab/tmlr2026-manifold-analysis

RDF knowledge graph data for [UKPLab/tmlr2026-manifold-analysis](https://github.com/UKPLab/tmlr2026-manifold-analysis), parsed by [repolex](https://repolex.ai).

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
rlex download UKPLab/tmlr2026-manifold-analysis
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── b2ac1d3af5b51bce596955bd973af4dbf6f7418b
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── b2ac1d3af5b51bce596955bd973af4dbf6f7418b
│           └── chunk-001.nq.gz
├── blob
│   ├── 0316b4baee42ca1f6016e65f2bb3eb5873ef33a9.nq.gz
│   ├── 09d10375355cddf3aab36227d5b1ccb50cb59ebc.nq.gz
│   ├── 0bb08c06b3cea9cd871765ebe6672c6bb0453394.nq.gz
│   ├── 0cafc7a6457d4880f4e82bf4730ab893a4775814.nq.gz
│   ├── 0d39a67c24f01c1af1e9cb675f380c3a1d1b2422.nq.gz
│   ├── 0d9360dc35d158ea1ccd025d9520994762579eec.nq.gz
│   ├── 120c6893b8af8f69dddc51b2734ed561b78c6091.nq.gz
│   ├── 160e4aeb844d3edfd1ef50272220ac7f953b0357.nq.gz
│   ├── 1b2b4c64340d5d0d2db6540f22c84ce0e6ffa30a.nq.gz
│   ├── 1b79957440ede2e2b378edafe91bff7b46952603.nq.gz
│   ├── 20a4c3bb17060a4f2c5b5ef33e5dfd44d42ddccb.nq.gz
│   ├── 2506c95bb41a7b35f1a009429bfba8c947a2059a.nq.gz
│   ├── 3c343bbc99dcd36e5e65c66c6908d9312f71f56f.nq.gz
│   ├── 44bac2a9343ea1c01d3e97c6ddfb3a7786427fd5.nq.gz
│   ├── 45c94f6d8e39f3b7ace728febbb20e6294eff290.nq.gz
│   ├── 46d176d0f6487e5c1c22aa445016d04105d5c8ab.nq.gz
│   ├── 4cef27e61ea9ac6f982e68a89dcb12432298bb71.nq.gz
│   ├── 50fa61aad8b4d9048ed79a4500208b479a67ece5.nq.gz
│   ├── 5477ee2051ef609f70ea0f9a45d482614e2f433f.nq.gz
│   ├── 553f632b5207437b2a0ce85bbaae5bcd4e377779.nq.gz
│   ├── 5640731bd613556d1a0dca87eba46d56973ccd33.nq.gz
│   ├── 5935850cc256ace8cd48f6da3486f2c90fdf8910.nq.gz
│   ├── 5ae44c9cff9f9d3561ab66ed4649b713d0b15d06.nq.gz
│   ├── 5b57031eeb05c2738ef475ad323c9f1586eb0d94.nq.gz
│   ├── 611ab411dbf05526817b24f9e398e09b72466b44.nq.gz
│   ├── 6460414af8e54a7c333918bb6a8f8a5671b9f7df.nq.gz
│   ├── 65b7e0e3302ab85a83fb185be86bdb6a6eaa36b9.nq.gz
│   ├── 6a171a558f6a2db926e56026b27c8a2cc3de9a48.nq.gz
│   ├── 6f7a127fc144f139ef92f3f75d232aa9e10c04a4.nq.gz
│   ├── 73d10e8dde34dc7c9d7e5dd7c3f3860785377b11.nq.gz
│   ├── 74a7561bbc72364613db0c2dd78d7d7672df55a6.nq.gz
│   ├── 76467e382d1e894d5425db30f3b5468a70bb2b3c.nq.gz
│   ├── 78144f54027fe0fecedc7c8f21e644b7f620973c.nq.gz
│   ├── 78a669f8ad76f46a43966dbf90e0a299ec34ff71.nq.gz
│   ├── 8210b16a3e9044d2dcdf8638abe56cf24a90c303.nq.gz
│   ├── 829cafe545fbc5b6a622128620b975639019a6ef.nq.gz
│   ├── 84f9af22f568b47ef4fe4be56bc293722f05d12e.nq.gz
│   ├── 8a32ee34b1603953ed79a91dec01453f67fb93c4.nq.gz
│   ├── 98338f5433324d01136f13bb1f21614baf7111df.nq.gz
│   ├── 9ccc7363dcc9155dec920e64a9820737d3fff0e3.nq.gz
│   ├── a2aacf989699a7315d29c2161c946513bdb68e92.nq.gz
│   ├── b0267eb3ca6718cca29d670a4ad1dc01e685c101.nq.gz
│   ├── c3cb5e40fd9d22d2b967f22f05f53bb79fda40b9.nq.gz
│   ├── c49878aa62a65189eb38d145be9f40db97ddf094.nq.gz
│   ├── ca009c425c5d9a97b200f0edc986d92431eaae47.nq.gz
│   ├── cc98b6933cd0df2705fd39225f24282258cd3685.nq.gz
│   ├── cf94d5d39086287ee7bd05ed57a57bf174f0f5f4.nq.gz
│   ├── d57bea60a5e08058e296e4fa8a0a0108b53da306.nq.gz
│   ├── e2857ce373ecae334de3c504ed73c47e00d911d4.nq.gz
│   ├── e511df2638686f46f6a896592b69b58e54e81aec.nq.gz
│   ├── e5748dd78015f3daba91e76652ef5a8f7530a3ac.nq.gz
│   ├── e5f96bc822fa77ea233bec16f494c3bc7cc7bd8d.nq.gz
│   ├── ea6d05ea8f9d193059c6b06318dbcc5229e7b33a.nq.gz
│   └── ee55869219e019fbd07274fc5c1359fcb2c7886d.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── b2ac1d3af5b51bce596955bd973af4dbf6f7418b.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

12 directories, 61 files
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

[UKPLab/tmlr2026-manifold-analysis](https://github.com/UKPLab/tmlr2026-manifold-analysis)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
