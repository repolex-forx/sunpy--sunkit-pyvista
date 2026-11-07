# Repolex Knowledge Graph of sunpy/sunkit-pyvista

RDF knowledge graph data for [sunpy/sunkit-pyvista](https://github.com/sunpy/sunkit-pyvista), parsed by [repolex](https://repolex.ai).

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
rlex download sunpy/sunkit-pyvista
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 0e9de86652e8b36c0ba62d22a7aa6e6faebfc4e4
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 0e9de86652e8b36c0ba62d22a7aa6e6faebfc4e4
│           └── chunk-001.nq.gz
├── blob
│   ├── 042a14edc8b181b004853f273371c3576c37ff22.nq.gz
│   ├── 0c68c10f45c4c950aaeb0f4d53ba132344656976.nq.gz
│   ├── 17115b5a35c71b05af947a99da9580005f03776c.nq.gz
│   ├── 1dee5d15fc1751750133b5e6e3a3a8ac31cf1d95.nq.gz
│   ├── 2119f51099bf37e4fdb6071dce9f451ea44c62dd.nq.gz
│   ├── 2140b1c29df0d36a7c367603b000f892cd758e8f.nq.gz
│   ├── 24b30dc324df67371ed7e099b70f07a4312530c6.nq.gz
│   ├── 25644588c5d0118dfc0045d8303aa514ec6c3d14.nq.gz
│   ├── 27a99baee6e0ea78fef2636295896cf14d2925a1.nq.gz
│   ├── 2be9b092ad82cb7e5568effe3f88d05131342659.nq.gz
│   ├── 382f6e7693a2a0f3d078984f7e227a8757462a84.nq.gz
│   ├── 3b4c79c888738203f8373634d413f0102818e7a1.nq.gz
│   ├── 44ba36216457bc3fff82336dc32457fba1651cd7.nq.gz
│   ├── 459aaaf62429bcc0d67b6a345df485e8af12433e.nq.gz
│   ├── 4770f5539162357bdcd477cec1f07d19874d7d19.nq.gz
│   ├── 4cacafcc7d1b7093ba14ea31e704c27aadd39f2a.nq.gz
│   ├── 4f878b9cdafa0c1d4943f0ffed221cd03eb0e962.nq.gz
│   ├── 544a2dba78d51ed662a71e941aac2b984933725b.nq.gz
│   ├── 5bb1cc982b2b1e3e1a9954cc24afb0c0444816b5.nq.gz
│   ├── 62063c0de4f183f299902ddc95697dd15b6b45a6.nq.gz
│   ├── 67b82f693f53cef785f9750c2c65c0bc3c191c8b.nq.gz
│   ├── 6890bc29b654e742c8ef0455cc88b9b0fc379c00.nq.gz
│   ├── 6c6aee5b5ed11818abb2babe94ac6cc4ff1b160e.nq.gz
│   ├── 6fd80a1bd0cac9bbe07c6d97e945fa3ecfa8278b.nq.gz
│   ├── 73872a169114f1a8920e4c24d371a0a1878db3fe.nq.gz
│   ├── 74c3aa0740fbc27f66573f1597c43bf25e46e652.nq.gz
│   ├── 78a2c4e6f59ee23ab82afeb05e4245d30d1ae195.nq.gz
│   ├── 79183a10f68f0e9358958edd409f6a158a741e54.nq.gz
│   ├── 82848dc895460b3faa0e33d7369ea405af329091.nq.gz
│   ├── 8fe09b731963a1272a62a3360bbf019ea563aef2.nq.gz
│   ├── 91a269448f07493360bf0ddef68de18a91b70d09.nq.gz
│   ├── 92ea707303e3d1f4b6fc3bb3446d173c4f8d3c10.nq.gz
│   ├── 95c40d356a6a7c4d7d4e6651202029ccbd67752c.nq.gz
│   ├── 978d376a7e3118b4feff24b6095e0ca8acd6804d.nq.gz
│   ├── 9992d081aa5e63ff6bfdaea04b9d9eb8fff0f435.nq.gz
│   ├── a2304b617f185b47fe5133f2edc3b9ed59790008.nq.gz
│   ├── a3678c42ba4e535aa6fe8a762603275a4319378c.nq.gz
│   ├── ab35134244d36ed4ba0bee14a31a1dfd03109796.nq.gz
│   ├── b08d3e8fad859ddd64ddf9b80e9b42257c9c2c7c.nq.gz
│   ├── b0e4d6202d2b0a19c8a6dc4bd2e9502fddf16ecd.nq.gz
│   ├── b66a0740e1ecc20b4121be469509704a3a06a636.nq.gz
│   ├── bd4cc3df7558aa0a309a915f1253456510796f45.nq.gz
│   ├── c04b87e55107964b08d8eef06322c52c628c5166.nq.gz
│   ├── c5be6220d9f23148c0c8afb2c1f4ca13735b7215.nq.gz
│   ├── c7eb571fe58c36be3a01741aef7c6a46a729fa21.nq.gz
│   ├── c82334553632d12caf96bd3d3d332d9683d2635c.nq.gz
│   ├── c8d7e11a4afb03b0f6bba22e190a51366732fe0c.nq.gz
│   ├── d0c4c1f13174282ebcd4b1fcd189e1938f154179.nq.gz
│   ├── d173547dafe856418316d866c48fd35e5566f37a.nq.gz
│   ├── d3ef1d996b8a0972076bf8989849b0f41310e07b.nq.gz
│   ├── d4bb2cbb9eddb1bb1b4f366623044af8e4830919.nq.gz
│   ├── d554419dd1ee26d16a5dda0b9ab962228097ee8a.nq.gz
│   ├── d7700aecf97960f310b392801d5936f980b5d99a.nq.gz
│   ├── d7da593156e765998f81d3df9451792eee74af6c.nq.gz
│   ├── eb90b61afdd8bb869a43f0dce33d703d82515e07.nq.gz
│   ├── eba9d3764444ff184f1f1d199ff964ef38e18bed.nq.gz
│   ├── ee0a7a85ff616be8b2b148a6eab01c0c14a49c73.nq.gz
│   ├── efe4f3eda9c396a0f906dc384c7ccf9be8b35153.nq.gz
│   ├── f8ba2f2fd3e1c9a266b40f36aa0fccb91ea2f577.nq.gz
│   └── f9101a2e28c6b67ff19dcc3f0b045ac2b7ccbd51.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 0e9de86652e8b36c0ba62d22a7aa6e6faebfc4e4.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 68 files
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

[sunpy/sunkit-pyvista](https://github.com/sunpy/sunkit-pyvista)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
