# Repolex Knowledge Graph of BerriAI/litellm-admin-agent

RDF knowledge graph data for [BerriAI/litellm-admin-agent](https://github.com/BerriAI/litellm-admin-agent), parsed by [repolex](https://repolex.ai).

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
rlex download BerriAI/litellm-admin-agent
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 3fdd3d33907f2cf63760a970a8f2aa8950b84908
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 3fdd3d33907f2cf63760a970a8f2aa8950b84908
│           └── chunk-001.nq.gz
├── blob
│   ├── 0187aaa9db16338981be144d28658082be3d3ac6.nq.gz
│   ├── 0324b05586559df34fe6433d6ad41d3d47edea60.nq.gz
│   ├── 07b48673c36051c31016a9081f2f8b4ed1d06591.nq.gz
│   ├── 0c35e244888a8a86b26c4e438cf5ac6583a7bc9d.nq.gz
│   ├── 0c939b4fa47d069bfcd5d6d22fe5950f9d638724.nq.gz
│   ├── 0d8b17bd7426919de18a536f6e0cb307c7b979d5.nq.gz
│   ├── 2557d77f56a24f515e3fb89783bb2251b9df18a6.nq.gz
│   ├── 2b41afa68533b517009ce006e00aedb44011277a.nq.gz
│   ├── 3920d688d9fcdaf191dc445ef81fcfbb9ef986d5.nq.gz
│   ├── 3d32dd0ebbb3ae7458f033430d1c920c65f83993.nq.gz
│   ├── 42eaf66603d056dc6de640209b927add891d3cc2.nq.gz
│   ├── 4671fe4fd54fa7d7ea707857f5cc0a13525fc13c.nq.gz
│   ├── 4995d49b9ea0e833a46763cbe94ad9a193cbfbd5.nq.gz
│   ├── 4cdb152950841c705dd0485cab022958ded20341.nq.gz
│   ├── 51dcd91e3fad259d726b6794c62a4723a5e32311.nq.gz
│   ├── 555909176d04e6cfb1692a571d696e02b5d050cb.nq.gz
│   ├── 565b3f47eb88ecd56b108157844548e0f93ba1ec.nq.gz
│   ├── 6717d704f0f80c7e46c7a5b269e5d072c2b15b57.nq.gz
│   ├── 67c73b27070da1d1237d55fdbff31ac33b78d2d0.nq.gz
│   ├── 6c9b84c5216a8ea17223ddf20d3fc42658019b55.nq.gz
│   ├── 6e98c6ad1e51f53009445c5c78e5a358e1ca12e8.nq.gz
│   ├── 71cd637c2ad3ae9cbf7a6ae30277c66c8c049ffb.nq.gz
│   ├── 7731ff686d905f63345c002e8e79ae66c25deb90.nq.gz
│   ├── 77cbb62188b88d8af7c1830f3a52e4a9bc247ac9.nq.gz
│   ├── 82791b5addf6b83128e49ef0a0c4b73cc43733d7.nq.gz
│   ├── 881340d754c43f8e73c06bd4fd344ed998e47723.nq.gz
│   ├── 9396ce10325a9a41e80278f3ace55763ca61b9a2.nq.gz
│   ├── 9b16e1e9f6c6ea2b5e6507a1281a0710d8cbd0e3.nq.gz
│   ├── a7fbe2ddd2921e3ac6c12fd0e3496ca916640620.nq.gz
│   ├── aba21837d11b4f230f73ed091f1a06699cd95151.nq.gz
│   ├── afe7167098d0024c55c562aad9a42c6db06cbc2b.nq.gz
│   ├── b5936ea662a07b1de67dfff95276bae4037c38b4.nq.gz
│   ├── bb20818a38e3269e27ac6258f4d6ea3b3cb8fe01.nq.gz
│   ├── bb56e77cd2f144231bb2059b68bb5c3ef36d9827.nq.gz
│   ├── bca1fcd6818b9ee2fe0bf8e1d2e69ac77e9443a5.nq.gz
│   ├── c65c52db8f0f3c6d11be6aa3c52bcaf9bf589487.nq.gz
│   ├── c91754448c4e8f676a2dedc5d9724ad9fa9754ae.nq.gz
│   ├── ca58da7b3f5418feb8a7fb557427dfb74386b994.nq.gz
│   ├── d47f51cecfa964d49dc4a1ab0500a53a1d391628.nq.gz
│   ├── d71e024fa51ac9f26b2e7f9747eb562e2795221a.nq.gz
│   ├── da7b287adfcf68d23b9285f37e9ed761b42ac911.nq.gz
│   ├── daf1f908edddcf9d2b28dfaeb19d4ba3ab566d6b.nq.gz
│   ├── dce963ac0bb8656eb35cfaf3aa9ff06f8807e7e8.nq.gz
│   ├── e016cdf6520689c1b247d6f1963bf46d36b40137.nq.gz
│   ├── e19ad3491ceddcccc51eb72d770cc52dc790a48e.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e8fa1dc83ff3753ab5eff35aeef6dca2a574a9c2.nq.gz
│   ├── ec84d00f7908632b6adaf295c4e6faba57da3cb6.nq.gz
│   ├── f160e6ba63aceaed6523af671e8fb4c371154ed8.nq.gz
│   ├── f2362c4bb5b813c23149014c640b326c2b0ee0d5.nq.gz
│   ├── f96002676a7198aacc8af55a4f49f79a755660d1.nq.gz
│   └── fcbbf23eebe24a300febff01b5abb431a25d9e60.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 3fdd3d33907f2cf63760a970a8f2aa8950b84908.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

12 directories, 59 files
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

[BerriAI/litellm-admin-agent](https://github.com/BerriAI/litellm-admin-agent)

---
*Parsed on 2026-10-10 by [repolex](https://repolex.ai)*
