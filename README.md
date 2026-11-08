# Repolex Knowledge Graph of canonical/pgbouncer-k8s-operator

RDF knowledge graph data for [canonical/pgbouncer-k8s-operator](https://github.com/canonical/pgbouncer-k8s-operator), parsed by [repolex](https://repolex.ai).

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
rlex download canonical/pgbouncer-k8s-operator
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── a4c57c09f31531c5b548cbd69cc7d9e1bac7dd80
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── a4c57c09f31531c5b548cbd69cc7d9e1bac7dd80
│           └── chunk-001.nq.gz
├── blob
│   ├── 00ce8b99b40058f58c3d5cbdfb406516e36d5a1c.nq.gz
│   ├── 032bfd9336895c6b7fc99559c7fbf3e358358748.nq.gz
│   ├── 04cc32e8fb4a661c1ca2f86baf0083692b63ab59.nq.gz
│   ├── 0511ecdc846e746f012c9288d05ce8375cb58e26.nq.gz
│   ├── 05dc4e23efc7f0fcf066096fb55bf1326742330d.nq.gz
│   ├── 087f6f3c58d5885b5ea92e0efbde8524c04b57a0.nq.gz
│   ├── 0c956a4a883542e0a2f8d441b693e614e231267a.nq.gz
│   ├── 1129c5e34dfa2c9be34d60589bd9c99232f1e480.nq.gz
│   ├── 12ae24b27c36ecbd5dc2a88399fb036ff5912abf.nq.gz
│   ├── 13d2a362bad3d0ee5ebe8d46be3eb6da915e8405.nq.gz
│   ├── 14ba913422c07a9ecadc5bc44d9d3c5c1ae15b52.nq.gz
│   ├── 17229fd35d12f8cfdda4444873140598178fbf2e.nq.gz
│   ├── 18b3e1857c07e0c0bacd42e75bc5a290eccb2f1d.nq.gz
│   ├── 1d8f8da450219def76bf1ea3b59e12d39912d4f8.nq.gz
│   ├── 1f1aee0e5644bd77eb797def6635226a22ee1d97.nq.gz
│   ├── 1f647cc8383a6ab69c2b732605268c284aede321.nq.gz
│   ├── 20331d3656b8d071400d26c9e3d505d7eb575941.nq.gz
│   ├── 2248632c3260857633a66e17c0c5a4015ed8f5f7.nq.gz
│   ├── 2321a0c6732914ecd9a3c0127c5bf125f533f864.nq.gz
│   ├── 2545e4339676c56bd9d0e43f52ba43a4b4dfb66c.nq.gz
│   ├── 276a62c4bdd0d379812d6a416177b101e14db285.nq.gz
│   ├── 2c97a2a269f0bb0ec1eb1785fca299f88ccd2794.nq.gz
│   ├── 2cfeab1c4fabb0787efd3d3ff2ee1702d1ce741f.nq.gz
│   ├── 3028615ea1e2d3057e7f419f66109e8445c50b87.nq.gz
│   ├── 30be5c512f4f1d967d2c922c77aaa08550992e8d.nq.gz
│   ├── 3208793acfb22a0190f1a8eda774a582ef29d7a5.nq.gz
│   ├── 331eb653ddd6742e9a145ef641746346c49f52c0.nq.gz
│   ├── 334ecd0db888ee20f42fdee1ace15785b132fd53.nq.gz
│   ├── 3e791fc7f415c816dfdc4b9c3b1af479a6f3fdb2.nq.gz
│   ├── 42146ac15c66e6b5297e258a2194ad0545b6f736.nq.gz
│   ├── 42b967c723e3930c4a6a4905dfaac5fa8eb90c43.nq.gz
│   ├── 435c28a403c28f4e0f6103d530b6ad5f8d18c5df.nq.gz
│   ├── 48eb83abe9c092ab2e8409ef316078e04b3e8a75.nq.gz
│   ├── 48f17a3b9245e4a89b68acaa6a1311fd07ed8a78.nq.gz
│   ├── 4b08894f75cde328c5984122ef715e932888c870.nq.gz
│   ├── 4b469216162e798b0f6640c248a60d16b44fd52a.nq.gz
│   ├── 4d5b59c798417b13af8299bd4f04a2ba6cd5a59e.nq.gz
│   ├── 4d720dac022aeb4e1420c0eaa2d9e5628f356a79.nq.gz
│   ├── 50d3c80944a060e2d39b0a1fd596d128dcd99204.nq.gz
│   ├── 53f881cf0b3be8c5325b4ccc11e63855b3f365b1.nq.gz
│   ├── 5676ae9de83a607c52eea842d1c6d10600f2662a.nq.gz
│   ├── 571a8d06f4caad1aeefc98e2d45128e531db263f.nq.gz
│   ├── 57f8ad213dd1ccfaf955fb27f99408c82cbb3b92.nq.gz
│   ├── 5be1d93158856891c2a493ea37cb1f116fc81f61.nq.gz
│   ├── 5d051e9b5cee08646e9ede20a58e3d6e14e1c73a.nq.gz
│   ├── 5ffeba4eee6d10c1813f13a10ebd70402956f93f.nq.gz
│   ├── 6011a952289c90571e4ba5f1614479e683f144f6.nq.gz
│   ├── 60475b5e0e87d78bd45a60b322e3915eec6f7902.nq.gz
│   ├── 62134f4ec3dfc917fd2772ccd9e916681bfb702a.nq.gz
│   ├── 64c43c7e7c00807683a5544025e06326f625d5c5.nq.gz
│   ├── 67e36c22038adf0a1df861569770e7aedfef6490.nq.gz
│   ├── 684c26767f2954373f24daf90fae7806e4f90b52.nq.gz
│   ├── 6b76cc46ca66ae228f0463d254223c2912b75a30.nq.gz
│   ├── 6c99e24503596d5510fbd8d5c258b565c7cfbc45.nq.gz
│   ├── 6ccd559eabeae93e4d23215fa450130fa9b37ace.nq.gz
│   ├── 6cdebc05c55d5cd4bd594b16c809ee5905bc9541.nq.gz
│   ├── 6e9ddd7e14fb6e0537020eb7fcf924f9a992eafc.nq.gz
│   ├── 700fa9d57a9878d7fb4ec1c86a235b7c1a565d9c.nq.gz
│   ├── 72fddf008ab045d177acbebfae46c758379224cb.nq.gz
│   ├── 7948cd833d7057628d46a74dfe0c72b4954d4217.nq.gz
│   ├── 7d13cbb2a74b78287466ff1681928b1a811089ec.nq.gz
│   ├── 7dcc612fed9c6c111dd7edc15ab6a24cc15cf6b5.nq.gz
│   ├── 8023d85ddd50aaf00010d9f891a3a38180eed323.nq.gz
│   ├── 82c65c07bd271076e28af180d4c6283e72147bee.nq.gz
│   ├── 839df1e5afb6588ec9ce1e14c0461e1b25b9a656.nq.gz
│   ├── 8593c25e87f6035d882c7b5d3db842a7d3671cd3.nq.gz
│   ├── 8595beda87268b61e8ff300169a84cef3f935c2e.nq.gz
│   ├── 890452c3243d97f19a563e051d27da8116d06d3a.nq.gz
│   ├── 89580c86a66599336b35d5920f07f4b1b8d5360b.nq.gz
│   ├── 8a96a6521228da4e898a6f1ed8efa4f10277020c.nq.gz
│   ├── 8bee4dd05c6e8b2048fdd3911ed2ec15d452a285.nq.gz
│   ├── 8faf6c8811583eb9458f1286147dc75b6d04326c.nq.gz
│   ├── 8fe80688a444c5181ab2c77753733ad24fb6c982.nq.gz
│   ├── 9194e8de88578745bedcc4e4fdab82fa03665c0d.nq.gz
│   ├── 91faa0f24bfa636952c591309e41ad665df35564.nq.gz
│   ├── 92219d71c83a39ce54b28b41c505260ffbdf0ebc.nq.gz
│   ├── 95951bce314c8c03f95cb2c829ef7e9094b43032.nq.gz
│   ├── 96450bdc32382abbcf9ade4798ce335b494b9dc6.nq.gz
│   ├── 970b051b905fbe4afeba8f571ffae09f6ec30b3b.nq.gz
│   ├── 98c6178c8b226418b4e13ced9ffb5669ff2f5df1.nq.gz
│   ├── 991efb36c45b7738bbbfc8cc8744448f732cb2d1.nq.gz
│   ├── 9ef36aca6d2980f250f98016204ad1e4b0f11d84.nq.gz
│   ├── 9f31506ff65d4a34c15eac5cdc04e5e9fb84168f.nq.gz
│   ├── a0601076454d9ba768acd0af1203cc516c152e1e.nq.gz
│   ├── a2aa413a4796543c39c37f7008264a9583f58ea0.nq.gz
│   ├── a48c9e493cfb79bd4b35ec6c77479f79cd01b78e.nq.gz
│   ├── a605744913f35879364d53aa1d31acd8668a3125.nq.gz
│   ├── abe8242dc8cb128efb95d19ff045a6a68085fd69.nq.gz
│   ├── abfec2c5d3d99629b53b34ab2d1ef08c1d3f14e9.nq.gz
│   ├── ae10b530f1670b0e1b82b44b2051474022f2168c.nq.gz
│   ├── ae193df7290fe92a94598c640c5c09ddd9235e66.nq.gz
│   ├── ae229c5bba0cbd02e5c78ee3682863fa55e80205.nq.gz
│   ├── ae2841bf464ce63f1d5c0c0866fb60ec74a11b33.nq.gz
│   ├── af1df49564a13041bc984126703133b177d63f91.nq.gz
│   ├── af6f0a0d459c1b346a586365908626424198fc2a.nq.gz
│   ├── b0fbb34478f1fbab8cd4e79f0f42987afbf911aa.nq.gz
│   ├── b20005225971e87ea357e9b5553c58e15b12dd56.nq.gz
│   ├── b25cec60658ee52aa6f8e733d40220e0b97d0a87.nq.gz
│   ├── b48fd599fe9f68fe9b5dae3a8e88f5177fae2284.nq.gz
│   ├── b4cfc58416f7c7fe7991a99ce6293194780cd26e.nq.gz
│   ├── b807b42637aaf69c9c9d08d13d784aa8fcdeb831.nq.gz
│   ├── bb1bf5b514111a2968aaf7e5cf0ac274f0e2eb03.nq.gz
│   ├── be65444a8106d8eaa7ae3b23699563f5e63da594.nq.gz
│   ├── c750782438909de5e84256c23b91c3ffb9b19548.nq.gz
│   ├── c7b36c25dfe498ea681b9d64d82231d7bcaa9f83.nq.gz
│   ├── ca45df9f1355030013e384ad14377eb46cc2c441.nq.gz
│   ├── cabe84126fa8a0167f8dee2ade6015e91cda97d0.nq.gz
│   ├── cf069ab2e31e0bc00e91379b7b654734cb6bc72e.nq.gz
│   ├── cf79c70b1fbf8d55c13ca16be7666c4700b0dd43.nq.gz
│   ├── d0ed0c326420795c9bc720c2c892f939726ac29a.nq.gz
│   ├── d645695673349e3947e8e5ae42332d0ac3164cd7.nq.gz
│   ├── d9242efcfaa9ce3b0716394a4eef803dae3bb512.nq.gz
│   ├── da86630b3ec051e58cb510041cef94a28252eae2.nq.gz
│   ├── ddeceed051cb6998023f2986793446c6e7b9644d.nq.gz
│   ├── e05d866f7aaa48627f2ddbdeeb1f8a7e0c67048f.nq.gz
│   ├── e58d556c7108c624cd05fd15cace04a5623df1fe.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ee3e102b2df40c76276a25cb52c2be8d0633b3f3.nq.gz
│   ├── f2a1b46e70660f21ff05b62147da86a24060f961.nq.gz
│   ├── f330f89b38fc50328df7cb8547409644f212eb72.nq.gz
│   ├── f866b1273fbbde9b91d877fca8666e8ab1099a4c.nq.gz
│   ├── f9d376c2a665048531d49685e44867d69291e3a7.nq.gz
│   ├── fa078ccb2b5a6199b9e7886083e8c24eb58d2bc1.nq.gz
│   ├── fba5f85b0f44a1e2356ceb3b5d927f214f55814e.nq.gz
│   ├── fc00f8946bc2a9eb345eb51fe96bf3b7700e2df1.nq.gz
│   ├── fcfcc7c1cfe43682fc4ca7ada2a6e6cd8e37b765.nq.gz
│   ├── fd18dce6d75fa39c7e94bd6e7b8737312138dd61.nq.gz
│   ├── fde16d68eb0be32a8ab39bf9387542ea6d61fe7c.nq.gz
│   └── fecf64d9839f591af5e0a6cdc6ecbf72d87e9a44.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── a4c57c09f31531c5b548cbd69cc7d9e1bac7dd80.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 137 files
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

[canonical/pgbouncer-k8s-operator](https://github.com/canonical/pgbouncer-k8s-operator)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
