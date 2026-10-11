# Repolex Knowledge Graph of psf/python-in-edu

RDF knowledge graph data for [psf/python-in-edu](https://github.com/psf/python-in-edu), parsed by [repolex](https://repolex.ai).

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
rlex download psf/python-in-edu
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── d4634d5357aea80ac260786bcdc3e1d13b042810
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── d4634d5357aea80ac260786bcdc3e1d13b042810
│           └── chunk-001.nq.gz
├── blob
│   ├── 048ca5a9df615aad6e6e8336cfb78aeb9c02f589.nq.gz
│   ├── 1762ee9792eec26feef0c47fd507fdd39bc67158.nq.gz
│   ├── 197701dd6a81df5f6e45396d0b296bf1f38329ae.nq.gz
│   ├── 2185f88fb2a4111c9834c525998f0ceaee5f9729.nq.gz
│   ├── 273f7e426e0eb7357b9bfb5933d1731e27e23ffa.nq.gz
│   ├── 27d7e06d6f9fc1397f1c53a41c9531a14c83004f.nq.gz
│   ├── 2d250fefc45da154fe16629b7f2260ec5505a166.nq.gz
│   ├── 366557c6e0d018d57749e7f91e10bbfab6f2fe09.nq.gz
│   ├── 398a9507f084094035f165f1b7023ceb02eb6538.nq.gz
│   ├── 3db8c3e00d862ad40fbc68a097dc94cc8e707fb2.nq.gz
│   ├── 451affb9871a2d36c5709bbdd56ee4d638972631.nq.gz
│   ├── 46f1ce72ee7f84e32ddf0092daac1ee4c86c9b73.nq.gz
│   ├── 48232d505ce6dfbdfd9671cab4b63945bb336f97.nq.gz
│   ├── 4973048a44f8fa72a1d545d11097ed6e6257414f.nq.gz
│   ├── 583b69bbfae2dabc98b80ac0be178421538f9018.nq.gz
│   ├── 58ad3b04c616eaf0be5bcd9f43dd0f5c650c7f45.nq.gz
│   ├── 5ea44ac955c1f8b52054bd0a50fc0c429428f619.nq.gz
│   ├── 62c6ffc9fdf70235f5c7e49d88725eedaec6e091.nq.gz
│   ├── 665892eb78f8484916edf055226cb1b1478affc3.nq.gz
│   ├── 6b7193212517d601906f8dc32a58294a88b94784.nq.gz
│   ├── 6bdacd466c1fb616c1144f30b7ccfe8e01dcdb5f.nq.gz
│   ├── 740acaeb07b4cf52e263b61886324bd2f38a697d.nq.gz
│   ├── 77fe47d048e0d5874b7c3b771365c44c51acd216.nq.gz
│   ├── 7f78169e4405d196c71b658aebfc3e63fa4eea1e.nq.gz
│   ├── 80a5308b80d4d9b9ca767b74b9c37d5aad068b60.nq.gz
│   ├── 87a77ced8476c6ce5951f93553f757c4f058acea.nq.gz
│   ├── 898734704190b4d23356c3f5cc8cead09e75e01f.nq.gz
│   ├── 8b2939447cd62400738d411a052069ba3fa6bf66.nq.gz
│   ├── a31e4163ffc636213d5353812502bb0d39432eb4.nq.gz
│   ├── a7da6671aab8568fe454d9e4bccdcdf661b6f7ff.nq.gz
│   ├── a9bc8bebfc5de6e06e74ec4ad15bc552b72724a2.nq.gz
│   ├── ae2a70821c1be7fa6abfd2bad2057f5ea67c5d6a.nq.gz
│   ├── b0c93f06a0d39e910e3757e7c65aad1d62788411.nq.gz
│   ├── b4d9cf0b41241b1e68e2566d78196ad251e4cd84.nq.gz
│   ├── c08439b01e592d2fa649c4d25010f659b193b64d.nq.gz
│   ├── c0fde851ce1edeaef9e064985746b0f618477d30.nq.gz
│   ├── c6f7782f61975eb26db83a0e0f32e62ec86d4b1e.nq.gz
│   ├── d04765f216fcc80fd533c5daabc96aa67b81ad02.nq.gz
│   ├── d3ee873ceb0b2c8104ea97446f8fdbf08885dba1.nq.gz
│   ├── d4324384635bde81f0db5c47d9c283c10a2c7943.nq.gz
│   ├── dc2478340f6a04a2d4217f02fb75e977ffbfa635.nq.gz
│   ├── e59851bf12c60217f48f6cba114b6293072a9515.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e9fe71ac23017106563f35f84615ca6a379e373c.nq.gz
│   ├── ea2c1755b626f28cbe1c699c160cd052beb52e4c.nq.gz
│   ├── f2155dc9d17a4cd50bbcd0d106c4e5d471c5595f.nq.gz
│   ├── f35501eba7b55b1b9eaf7fb97f82e6049f1deac8.nq.gz
│   ├── f5adb2a140c9e7626e3f23b42cac05a7fea43e94.nq.gz
│   ├── f89d79db8d237b3c90fcb48b481df2de771d420f.nq.gz
│   ├── fb25763f731a9e9892469d304a67ae81d13660bb.nq.gz
│   └── fc7d7c77e5c62fb5e4283604ed4a48796368c7e8.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── d4634d5357aea80ac260786bcdc3e1d13b042810.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 59 files
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

[psf/python-in-edu](https://github.com/psf/python-in-edu)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
