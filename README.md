# Repolex Knowledge Graph of langchain-ai/langchain-cohere

RDF knowledge graph data for [langchain-ai/langchain-cohere](https://github.com/langchain-ai/langchain-cohere), parsed by [repolex](https://repolex.ai).

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
rlex download langchain-ai/langchain-cohere
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 28e67ec8089c7523926465c720860b2aba5c9000
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 28e67ec8089c7523926465c720860b2aba5c9000
│           └── chunk-001.nq.gz
├── blob
│   ├── 01d166ed35350eb886b1963ea206eaa5d324ded3.nq.gz
│   ├── 01f902039196aafa396af532044ab2b611063b85.nq.gz
│   ├── 034e2dbc7e0d0ad9be4ea494e0b0a8570c531dc3.nq.gz
│   ├── 06e40ab7c136da7c25c0f8280fbef563fa44b872.nq.gz
│   ├── 08dd6dec2097dc3718d90788a82aa87e1ee60c21.nq.gz
│   ├── 096ac10c3c15cd8d4482c61aa16a7ce66b1d74e1.nq.gz
│   ├── 0b0943d45cdc3ca49c8e2c6532fc470d09012e99.nq.gz
│   ├── 0b1504bce75bfa766afbeba69be096578b7d8e79.nq.gz
│   ├── 0d2ee440295109e2284f90afeacc5ef9a8d3ff73.nq.gz
│   ├── 0e05d58d8e75800697f09d7c7ed0577812394c73.nq.gz
│   ├── 0f201dd85be8a3c808a8c62a70a7fe05c045b1b1.nq.gz
│   ├── 10c7cda631e44590bcded19785675f588b2c04ac.nq.gz
│   ├── 13576dbcb552858603cc84d1e665ff76524f2c98.nq.gz
│   ├── 146289dc6eb456aaa8d60a3894943e1e7ef27f8c.nq.gz
│   ├── 16f9c3ccf15383cb764429e679991e3481bb24fb.nq.gz
│   ├── 17357bbb0a65fab201bfce9f9ca79901b626260c.nq.gz
│   ├── 1806e8830c87f0286a6ed9a5c327bf042a65542d.nq.gz
│   ├── 1ad2c5e215136e949cf84738b9d4767466849d0a.nq.gz
│   ├── 1b7f8856160fa5da9753daee7e5966d2eccbfc79.nq.gz
│   ├── 1d755d76c3cd4be3e3bae9a261eebae523f01359.nq.gz
│   ├── 2185d552d4ffee1e17fa22ec0d99501caf5c2f98.nq.gz
│   ├── 244cfb47607aaa5f2bedd266f0eb41c039da9201.nq.gz
│   ├── 268fdeb010ea20d48ca474a2f9993f8833ef55c3.nq.gz
│   ├── 26d4808234dd72f693860cb60cb41aac547b2e3b.nq.gz
│   ├── 278c6eaa635d2f0efddc0f8a10448c9236168f0e.nq.gz
│   ├── 29a50f42e2b9a5874024d08ac93e189e8fbed226.nq.gz
│   ├── 29e7622c78b084f72bccf26803b13c190fa37157.nq.gz
│   ├── 2bcccf39d89c048836b3eb712884d04f65bd7fb3.nq.gz
│   ├── 2e9c286ba94afbb7aeb3d92ec61ea21842bbd06c.nq.gz
│   ├── 31047599264dd3036479c0205e5d783ed931c8a1.nq.gz
│   ├── 32b4c8ee9d93f619efc31ea3b1a7158e373626cd.nq.gz
│   ├── 33ecccdfa0fbda27b1ff362a812403db4cd30e31.nq.gz
│   ├── 3784bf3e021ddec36be0287b9ab14a077677a0fb.nq.gz
│   ├── 37f73a5bda72c8e3ac28f1ec0dab377d7b8c3b23.nq.gz
│   ├── 3942da4b79b17b71e3acf9957e6dbde4eab0f388.nq.gz
│   ├── 3d0db224a4c96b75d6361edd5e30e9080a302c7c.nq.gz
│   ├── 3d724950249ecbd7675118f08b6bb5348bd07343.nq.gz
│   ├── 40735cd239b91e75eceb71052a04cbbde1dd5f3f.nq.gz
│   ├── 413c82fd9f04b35231b40f7303381d7aa0463953.nq.gz
│   ├── 4216a9d5d6eb9fc3dc17da8cbab60996bb72feae.nq.gz
│   ├── 45988ba091de05c84aa6fa27efbefd4f170d1043.nq.gz
│   ├── 4921c3c48079fa9fa926cb662ca2fc2ee4ed68d1.nq.gz
│   ├── 4e12f19693932f291a34ece0aac22419d882880c.nq.gz
│   ├── 4f6e7533b1ee8c75706da43308487cb43e496b85.nq.gz
│   ├── 507791e6d457da7c4a172d2db3fc7c9e10435be7.nq.gz
│   ├── 5507ae3bcbad9d57f3af3911913c4c21c21899fa.nq.gz
│   ├── 57d0481d4b50c89fee2cb9e88242639d8e674028.nq.gz
│   ├── 58bf0d89ac5ee618b1c67e625ab2427689a9ac7d.nq.gz
│   ├── 5908d415ac7f16a026d1a8d6f516e87aa6753db1.nq.gz
│   ├── 5a0de939860ea3f36ca4999226fba7bedb69d4a6.nq.gz
│   ├── 5a7f60619febd6dce0f3404cd99b8466295b8148.nq.gz
│   ├── 5b14e2c6165aa4bb344f696ea5ef85de044c63ce.nq.gz
│   ├── 5c1032176548c52c32f66e8afaba16529637df5f.nq.gz
│   ├── 5d229bd5a17ab6d4f9f9fe7341bc0b3aa44a24f1.nq.gz
│   ├── 60a8b0c73bd623dc73c9738bb0c84e8f183225e2.nq.gz
│   ├── 62df84443a71e250d7c3de0f959fb10fb9c80ba5.nq.gz
│   ├── 64a652f58235ff40577ed724c39fdce997274ac4.nq.gz
│   ├── 687c3c99f121f02d3d6612035cbf327ea4efdc12.nq.gz
│   ├── 68b099f0e5592611a52cbe7f8635f0625ebfeed5.nq.gz
│   ├── 690918a4b89ee99810b4bbd52372028b029ce627.nq.gz
│   ├── 695613c7ba8fd6d98c3dd463c73f703d79c926d6.nq.gz
│   ├── 6d6b9e9c1680b226a9afae1861336c1e881df00d.nq.gz
│   ├── 6db1555eaa05f7c01c6249b3186e8fceabf910e9.nq.gz
│   ├── 6f6f40e351b0f28090e2f4c084d500a3074fec70.nq.gz
│   ├── 70195b2916c61b05ec8eac248445d70842906ece.nq.gz
│   ├── 7483967405f8eb2326b1f2e5c9fc176b0960beb4.nq.gz
│   ├── 7c800e0df0bcebd7c2f559dfe714dbb36755d83f.nq.gz
│   ├── 7f975935f0014ef9bfaa53472f65b308f0fa3ed1.nq.gz
│   ├── 8111b05e44fb94f761cc3fe3cc55b040e143b2ed.nq.gz
│   ├── 8455c0f7197f827d7a43103e3fb5bd182ca9e8bc.nq.gz
│   ├── 86f4474f86c15d46d53461f50a3959c9089caf8f.nq.gz
│   ├── 89d887160dc5e158b2e0d309d2faf3bb18c80878.nq.gz
│   ├── 8b137891791fe96927ad78e64b0aad7bded08bdc.nq.gz
│   ├── 8bb8d9108e329c518a75cb378bc8b9a61dd5efd4.nq.gz
│   ├── 90061b1cfb83eabf6730a40173d70ceac792e128.nq.gz
│   ├── 9085d2198ad875881be622e8da37741120bac495.nq.gz
│   ├── 908e51c02b1175d9388b051dd6985d44f6716e60.nq.gz
│   ├── 946d6cb80272e4b55f4e479d505deb4571a3abb0.nq.gz
│   ├── 9a2dc14b6c57da6dbf7522fc9013b0f21aa7eafb.nq.gz
│   ├── 9c53d3c82413cc561e2f6cc7ae3c46ec4b948fa7.nq.gz
│   ├── 9e3527786c4bf29077dcc43c883362d848b1bbe6.nq.gz
│   ├── a09a786ee5ae5aaacdc434c07ce37b581ba3e92a.nq.gz
│   ├── a24d9d0ad3e996aecb6b3ecbae94e49aa8b586ae.nq.gz
│   ├── a426955d2b841a80e86f1e1bea7b0673b7ea5471.nq.gz
│   ├── ac8062d68ae0cffe050a674807f43b637df35489.nq.gz
│   ├── ad8c4fa5fd221fb3a6ec90f28b500546d15a1009.nq.gz
│   ├── b2d497a9220ffa6e7240e30a26e7a21ad3efc51b.nq.gz
│   ├── b3dc1d2ab50f45dabe5ff6681239d6accaaa0447.nq.gz
│   ├── b58ce16726de5d25208a2a1e5b80bc3688447952.nq.gz
│   ├── b7aee2a94539b5a044d85ba3b16a3d6db4dde9a7.nq.gz
│   ├── b8495138110873ac73582a91e0528d9417d97c63.nq.gz
│   ├── b87a786810cdf527086fea10fb4d4d16935fd0cf.nq.gz
│   ├── bc56c4d89448a963d0b6486989809d653dab9a97.nq.gz
│   ├── bccabd45405761c96588f8d979486ffee31ca0ef.nq.gz
│   ├── bcd4f1777ed964f1d2167df767ffa3d8fa81fc27.nq.gz
│   ├── bdec5151c28dde849f0fab8b6e587be97a416755.nq.gz
│   ├── bee8a64b79a99590d5303307144172cfe824fbf7.nq.gz
│   ├── c01e7a80e46cae699f168c92fab5ade71a6bda7d.nq.gz
│   ├── c078d57a0d527c54440523c597ac268f5a739734.nq.gz
│   ├── c0d838969a616d75c9cbc32aa2e9ab02deab8a65.nq.gz
│   ├── c28f950ce468b1ae9ea5753952ca2fe2434f3590.nq.gz
│   ├── c520e85ab1cc0be78131a1b05330297a331bb729.nq.gz
│   ├── c8afd484ae68a0861fa0a2abca72f296b8cf5225.nq.gz
│   ├── ca4bd78c4cf9bf8a72f1a93ec1aefa4e6ee12cfc.nq.gz
│   ├── cdb4881c7392cbeb08c24f2e5f5b66233b094104.nq.gz
│   ├── d24b1f6aacf5c07c73146848b9c0cdaf69ec2569.nq.gz
│   ├── d6af87c78f6509f398c26b82aca4aa63854c51ce.nq.gz
│   ├── d743a6aec6918447bc1625d78139422e215bda6a.nq.gz
│   ├── da8e5313d06a820dcf48152579bdf9e208fc7f3b.nq.gz
│   ├── de4a146c872700b2c4170b92272f59e713c165c0.nq.gz
│   ├── ded86eeac6b12fdb8e82080f4368e3649bea3f12.nq.gz
│   ├── defebe686982f8f6aaaf8008ad372ab3a6ce81fc.nq.gz
│   ├── e152f867ab7f573fe6073393c18e6930929d2a1b.nq.gz
│   ├── e5a0dfce247935d8d73d62d847a667c5cfa75c29.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e749128d8c95631c39d980ea3658656cef55e99a.nq.gz
│   ├── eabb4f4484ab479a8f2ce10b0879799ba712fd3e.nq.gz
│   ├── eb401117676826510c9ada43c0bfd511fb860112.nq.gz
│   ├── ed0f965eebf9f1595caec5274b44147801883ec0.nq.gz
│   ├── ed8f28a6ba40636c2cb046dc4aa16422cde2af4c.nq.gz
│   ├── ee107c1e81e52cfee63c51b8ccc5969d3cc2e34d.nq.gz
│   ├── f14366bcb7c1a62025203bf4b0da5809b7d32696.nq.gz
│   ├── f54cf3825a951be71c06d8f38aab1c28efe49884.nq.gz
│   ├── f5c5df09f7535d20c858efecbfc7fa01cea7213f.nq.gz
│   ├── f71472494b6696fb5b5bef8cb1c4a570cf7412ce.nq.gz
│   ├── faa2338beec848b370903230596f01e7ea03767d.nq.gz
│   ├── fac7ed3fd49c2749033ada1a0560fa0b68f04360.nq.gz
│   ├── fb6072abe5c3015bcfb0a3b95660778e90419f89.nq.gz
│   ├── fc0602feecdd6748623c852ab534e1ca612673c7.nq.gz
│   ├── fc81ef7abd688f6581b8a3766632a2e794088217.nq.gz
│   ├── fd21a4975b7f0ba8e857761bc1cb9aef2c2086f2.nq.gz
│   └── fe85ea70f8e79ae0e0111f92b558354b7b76d3f4.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 28e67ec8089c7523926465c720860b2aba5c9000.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 140 files
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

[langchain-ai/langchain-cohere](https://github.com/langchain-ai/langchain-cohere)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
