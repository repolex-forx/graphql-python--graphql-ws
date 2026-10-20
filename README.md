# Repolex Knowledge Graph of graphql-python/graphql-ws

RDF knowledge graph data for [graphql-python/graphql-ws](https://github.com/graphql-python/graphql-ws), parsed by [repolex](https://repolex.ai).

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
rlex download graphql-python/graphql-ws
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 7ef25ecfaf5390bf1a0cb4023272d8cb074368c2
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 7ef25ecfaf5390bf1a0cb4023272d8cb074368c2
│           └── chunk-001.nq.gz
├── blob
│   ├── 0552c7b3eecc56e5ec146be0240df85813103074.nq.gz
│   ├── 086445f85eda5aa80989fec6ccaf14aa533526e0.nq.gz
│   ├── 158ba138fbfb0501e68443d73ac66b12adda2d79.nq.gz
│   ├── 1b65bb4606e66cc3c4d0d53d5461930f2f826782.nq.gz
│   ├── 216d4f632af9ca26b04bd62a87f3d714ef0fe223.nq.gz
│   ├── 250649964bbc36f4bec2942f69238aa6f7c02c1a.nq.gz
│   ├── 3034ca9ef4cb18e56763f71e8f2195ef717b23cc.nq.gz
│   ├── 336a0c61b0ae65668f283249391d7f2a5fc16e23.nq.gz
│   ├── 340999a5847b4672f54a96392b5b86de0f3887c9.nq.gz
│   ├── 347bd139a27a205bad5fbe25260b8a0a3da204d4.nq.gz
│   ├── 35b4d4d4690e76ee7894bda4d720f87dbf9ab636.nq.gz
│   ├── 395e0df0796690bac29bc7679af77c76965a4ec7.nq.gz
│   ├── 3b85c4959f55b07e610c958e5e92bdf46f9062d7.nq.gz
│   ├── 3ce3e0906c2309e4ce81828e33574aaef6e9a048.nq.gz
│   ├── 40c43fdcc0fcfa9dcbad7620706d1ce2bf4f3e9c.nq.gz
│   ├── 424d95f86771b928cfc01128a8dd7a34ee3b04d3.nq.gz
│   ├── 42a70e7a26ec28fc8764a337346500d6b497f73c.nq.gz
│   ├── 42b6bba9b7971f2c03c2ccb1d152d73331c3b2cd.nq.gz
│   ├── 4734531377976249c14edcee802f2d56307a91cd.nq.gz
│   ├── 499febb26a7a3d60bebadc3df1da2ce990131b31.nq.gz
│   ├── 49ef2557b16e4c1443f257beab7762f2ae57644e.nq.gz
│   ├── 4c024ca3154b96107759f67d094e9fd2e9abd6ae.nq.gz
│   ├── 5259b87e06b538030f3affc5efbefd25ae174463.nq.gz
│   ├── 557e99ff56bd34d17ef88eb3b308709f1ed120ab.nq.gz
│   ├── 595968a7d66efd9b2732790f765cba73fdd4c359.nq.gz
│   ├── 62e2f8b33643ac7689639a98be487418aa84523a.nq.gz
│   ├── 65a68164df0b354594fafaea43682a1383f98e31.nq.gz
│   ├── 67a356c2b7a429073d0aacd7612cb43ed7eb6986.nq.gz
│   ├── 68781b0c8b5aa9de7728c75843b7faf03a051b2a.nq.gz
│   ├── 6c7b22b2471b8476d6a2a70b0b0fb04aa69df842.nq.gz
│   ├── 6d3e723982e928f8cfcaf02ee0fb4511497b4bb9.nq.gz
│   ├── 709f7cfe23dfcba2f4fa2bb1b4b1318e761b376e.nq.gz
│   ├── 7126c9e8f2bfe2c5265c97612b019a1d62f95ddd.nq.gz
│   ├── 72a33558153fb57def85612b021ec596ef2a51b9.nq.gz
│   ├── 738d9e7a609bd7edbb78841467f63454f58d1a0d.nq.gz
│   ├── 7638f3df3427830de3e628b370bc2ac45a4d7514.nq.gz
│   ├── 7bb3f24269f0847cdbc6bd1918de7800ccf72bd8.nq.gz
│   ├── 7d2851f3433850acbaba000877865886830abcb6.nq.gz
│   ├── 7d385e90b3f27681e8d6ee423c8e4879e560bb3e.nq.gz
│   ├── 8a8ccc0487b50bc003e4ed0ef80a9fb2dfbd660a.nq.gz
│   ├── 8b57a60ca09c49ec9edd9373fdd6e21811e53b61.nq.gz
│   ├── 8db3ef0af264f6f0454ade2dc3e3c50089d38fab.nq.gz
│   ├── 8f007b98891b1c65b4bf7250c1673156f6c4bdc2.nq.gz
│   ├── 968fe182d6e64bb201a480450ccc552538697a1d.nq.gz
│   ├── 98e6873e91c622efae7b89fce663d71c01b165dd.nq.gz
│   ├── 9d01766121c7b9dd2bf84c14707b9fa0eb81f747.nq.gz
│   ├── 9da1ca87387c17d2a6752e45fe8aa13a9972b651.nq.gz
│   ├── a14bd67a478792dd543f8b1ab3bbca92ef3178e1.nq.gz
│   ├── a21ca5ed70086dd1b965db8056567f63ace3b5ef.nq.gz
│   ├── a2315adde59adb93e535f52498e87af78cbc2145.nq.gz
│   ├── a7349708ec37b8920fd4174584f8e339278693b9.nq.gz
│   ├── a77e5a64711d9e52f8c12a6e42cb63e020f2f3e5.nq.gz
│   ├── ae107c721e38a118a44ff3f98df7d08a8b22ff43.nq.gz
│   ├── b41aac49ea6f123fc87e1c77137f26d34bcaea86.nq.gz
│   ├── b7d6849f73e9606fe294d092566633ccea14bda7.nq.gz
│   ├── ba4a0a44c0d89f760206b9f711c6739fcc110f7d.nq.gz
│   ├── baf8837130083f0db73e62256a2d2a1522bef9e2.nq.gz
│   ├── c0adc6768750c709752a70fa6d772cfcde445cda.nq.gz
│   ├── caf790deadd753b2da3777e5a59f686d3d080347.nq.gz
│   ├── cd2e5480c584737e9de252f9a90090baf828ebbc.nq.gz
│   ├── d08b0f386496d3d28d21111b65e70ce946af9dfb.nq.gz
│   ├── d0e41c49690a0a99a2bb7125ebe6ef7da556dccd.nq.gz
│   ├── d1d86bc31962a5eceb9f573cd88e026c11b6947d.nq.gz
│   ├── d4a2c4405ec2e962c521a13af91bf5f7098a62a8.nq.gz
│   ├── db6893c3fbd79f453ed95b66024bc61d98e336de.nq.gz
│   ├── e122f914a87b277e565fc9567af1a7545ec9872b.nq.gz
│   ├── e582053ea018c369be05aae96cf730744f1dc616.nq.gz
│   ├── e58af994a8e34f66597a0374e4c42797f217fd92.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e8e73777023598a17c05b555e442aea1e9921dad.nq.gz
│   ├── ea0438c4c8ac9460c8af89bcdc59ad30536dba8f.nq.gz
│   ├── eb480504d7618ab6c150c69bf32c49ce07e26678.nq.gz
│   ├── eb65bb2283849a14ed67fad05fca35b04b780c6a.nq.gz
│   ├── ed7f66601f58d52abc61188e55f3aebdcc2c4830.nq.gz
│   ├── efd145bd6b277eaec5c0fe4ec12a8ec07c3b3708.nq.gz
│   ├── f6b6c68e7405d04ad3c03742b9bebb0b057ed27a.nq.gz
│   ├── f9f1e5be556b9a2b499f6ef15dbc32b665ee8471.nq.gz
│   ├── fa6c6a99541c10ceb13cfa93d371cb21f88d4cfc.nq.gz
│   └── fe762baec0ec3bef676d5b0062376d7eb9d11b95.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 7ef25ecfaf5390bf1a0cb4023272d8cb074368c2.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 87 files
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

[graphql-python/graphql-ws](https://github.com/graphql-python/graphql-ws)

---
*Parsed on 2026-10-20 by [repolex](https://repolex.ai)*
