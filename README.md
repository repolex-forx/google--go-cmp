# Repolex Knowledge Graph of google/go-cmp

RDF knowledge graph data for [google/go-cmp](https://github.com/google/go-cmp), parsed by [repolex](https://repolex.ai).

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
rlex download google/go-cmp
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 5deca1c7dab7d33c102d8d7a26794da148485563
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 5deca1c7dab7d33c102d8d7a26794da148485563
│           └── chunk-001.nq.gz
├── blob
│   ├── 0253f5678ab4f0ccede1b36cf29a9073a39a2d27.nq.gz
│   ├── 144ea2351ffc96e1002546010a850dc91a3e887a.nq.gz
│   ├── 1616dd84d52a343f79d5a7221f72ffbae38a75cc.nq.gz
│   ├── 2050bf6b46b79740f83f580856498f0b48aa5e89.nq.gz
│   ├── 236c2924b73db63810d5086af1e304fbd53c43f3.nq.gz
│   ├── 23d166581af2c6817446602afea17a5ccb47cf0f.nq.gz
│   ├── 23e444f62f364099a1faf35c9f4fab61fd7ce277.nq.gz
│   ├── 29f82fe6b2f80bab308e990adb0d556ddaf61254.nq.gz
│   ├── 2ad8701b173da88f3f643e2a537d141762f7260e.nq.gz
│   ├── 31209479ae9c76336699e057068ea1f6dbb2a96a.nq.gz
│   ├── 32017f8fa1d8aa18d984b7d56d8354273659a50a.nq.gz
│   ├── 36062a604ca3e5fb76ea9f0f297ebf1fe06f0c83.nq.gz
│   ├── 3c57526ac1fefdd6d0f5b55b7d39d83c2698ecfc.nq.gz
│   ├── 50632462d06b186d388b1258833190b0213fec46.nq.gz
│   ├── 668d470fd83fee16c69387a94a70e13177f16b92.nq.gz
│   ├── 6717fd418676e15df22a95da56adc550fa3d10bc.nq.gz
│   ├── 76d8dd69740c8d3d86031a24ce756eb9a0d75e90.nq.gz
│   ├── 81622d328540eb696a9cd7c5132ba8c49161b2ba.nq.gz
│   ├── 98533b036ccfd52db2107f8af4a6928b50ca1329.nq.gz
│   ├── 9869f02db2e9d920b19961e48763e5525079b47f.nq.gz
│   ├── 9e56dfa08cb8266722ccfec5188d81ca64926367.nq.gz
│   ├── a09aba25f494175640f4560befaac87966725558.nq.gz
│   ├── a248e5436d98e0ae489e9b017e92a5875e3c4020.nq.gz
│   ├── a3b97a1ad57188171a2bc9439372d740da0b65e4.nq.gz
│   ├── ad6927771de0c5682fb128f7fd7fe9f2006ede98.nq.gz
│   ├── ae319c70aca8c8b148045aa1fd0c3ecfae85cb8a.nq.gz
│   ├── b58f56e6291251f4c3231384a388d03cfcbed859.nq.gz
│   ├── bacba282d729c078cf1eed89de3ba0b700be1253.nq.gz
│   ├── be26cdebf848ff606712270712bc9830d7e4872c.nq.gz
│   ├── be31b33a9e196df598ca4f9a876ab88c52e7e59d.nq.gz
│   ├── be77b951143ae93cc16fe2521a6e215975864abb.nq.gz
│   ├── bfd2de8e6956c594a42d12d74fced812cfdde747.nq.gz
│   ├── c0882fb52da36aeeeb50d8eaabf11bfa990c849a.nq.gz
│   ├── c3c1456423ce105b8b06f90c9c5cae4448d77e31.nq.gz
│   ├── c683763400c29adb73d59b25268009fe0ddc1b72.nq.gz
│   ├── c93990a74c608d5ae38442d4fead891ee128501d.nq.gz
│   ├── c9cb66e77f25e23ac547890953d840d35fbac29c.nq.gz
│   ├── d2f212e5da80c5c7445cf4f272517b33c564e734.nq.gz
│   ├── d47a1740ec8494010b5d316fa9e1d6c25c98cc25.nq.gz
│   ├── d8e459c9b937b8a21c63c7b1d2896f448399953d.nq.gz
│   ├── e505cad0bfc8f0aa4b1013031ae3ee7798e90184.nq.gz
│   ├── e592e3a54fc4cf5a6f4394a787d5ef519e28c148.nq.gz
│   ├── e5dfff69afa15fb9cac39e5b2826d01e97f1e505.nq.gz
│   ├── eacf072bca897b776a8c006df89d6c08c9f4f7f4.nq.gz
│   ├── eb87e9e743871f957bca578e3c957f28212d13ca.nq.gz
│   ├── f43cd12eb5f3ab64bce92b9bb540368bdcf1e1cb.nq.gz
│   ├── fd9e7b07f633dcd4f0902c3eaeabf3e59a442f59.nq.gz
│   └── fe82356746d89084e5c8ab3e907e28adfed9db36.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 5deca1c7dab7d33c102d8d7a26794da148485563.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 56 files
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

[google/go-cmp](https://github.com/google/go-cmp)

---
*Parsed on 2026-11-09 by [repolex](https://repolex.ai)*
