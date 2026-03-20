# Repolex Knowledge Graph of colinhacks/zod

RDF knowledge graph data for [colinhacks/zod](https://github.com/colinhacks/zod), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [lexq](https://github.com/repolex-ai/lexq) query tool using [uv](https://docs.astral.sh/uv/getting-started/installation/).

If you have uv installed, just copy/paste this into your terminal:

```bash
uv tool install git+https://github.com/repolex-ai/lexq
```

This installs lexq onto your system, in your user context. Verify the install:

```bash
lexq --help
```

**lexq is designed to be used primarily by LLMs in a terminal.** Start up your favorite LLM and ask it to use the lexq tool. It's that easy!

To load this repo's data:

```bash
lexq download colinhacks/zod
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   ├── 11aba3cc6bd430eec8260c4037265925709f924a.nq.gz
│   │   ├── 1b1108030c2116620117af7e238aed50c23fc186.nq.gz
│   │   ├── 248e210df242d18d7d2882c343d011d43bf4a4c1.nq.gz
│   │   ├── 65d8f4ffb3099319e88e9406c062da8568bf6a3a.nq.gz
│   │   ├── 70615e6a4e05adafe7e471f4706e90f8ee798292.nq.gz
│   │   ├── 7478b1f87279cd37e1de2a9be9c57861b66ec20d.nq.gz
│   │   ├── 7fe864e34294b465362ba55aa59626208edb1a49.nq.gz
│   │   ├── 8a48f9185341a61bb39428bf97087ed2dc5932f5.nq.gz
│   │   ├── 93b0b6892cc0cfee8d0bec4e2e1242c7df771f95.nq.gz
│   │   ├── 9eb7eb136f3e702e86f030e6984ef20d4d8521b6.nq.gz
│   │   ├── a19acb8f90226cfa6036672385479af5874ba975.nq.gz
│   │   ├── a1d2d089dd66ac0bbaf0fdd64709c66d796e83a3.nq.gz
│   │   ├── a233ca87bf888f5b821bc8ae8ae3343c1edba9e2.nq.gz
│   │   ├── bd5d2f4183503306e92d4883e0732e03763e8e6d.nq.gz
│   │   ├── c190a84bfe552c3804c0e0e04447b53257194de5.nq.gz
│   │   ├── cce89eb531cf9225faf87bc45d432da6561df8a0.nq.gz
│   │   ├── e82979dbcfe3324f895e714cf993eed60f20c287.nq.gz
│   │   ├── fa4eebba089badc7590c6ad7dc3a60c252702282.nq.gz
│   │   └── fdd708493e4422dba6453908af55ef0d58767c03.nq.gz
│   ├── dataflow
│   │   ├── 11aba3cc6bd430eec8260c4037265925709f924a.nq.gz
│   │   ├── 1b1108030c2116620117af7e238aed50c23fc186.nq.gz
│   │   ├── 248e210df242d18d7d2882c343d011d43bf4a4c1.nq.gz
│   │   ├── 70615e6a4e05adafe7e471f4706e90f8ee798292.nq.gz
│   │   ├── 7478b1f87279cd37e1de2a9be9c57861b66ec20d.nq.gz
│   │   ├── 7fe864e34294b465362ba55aa59626208edb1a49.nq.gz
│   │   ├── 8a48f9185341a61bb39428bf97087ed2dc5932f5.nq.gz
│   │   ├── 93b0b6892cc0cfee8d0bec4e2e1242c7df771f95.nq.gz
│   │   ├── 9eb7eb136f3e702e86f030e6984ef20d4d8521b6.nq.gz
│   │   ├── a1d2d089dd66ac0bbaf0fdd64709c66d796e83a3.nq.gz
│   │   ├── a233ca87bf888f5b821bc8ae8ae3343c1edba9e2.nq.gz
│   │   ├── bd5d2f4183503306e92d4883e0732e03763e8e6d.nq.gz
│   │   ├── c190a84bfe552c3804c0e0e04447b53257194de5.nq.gz
│   │   ├── cce89eb531cf9225faf87bc45d432da6561df8a0.nq.gz
│   │   ├── e82979dbcfe3324f895e714cf993eed60f20c287.nq.gz
│   │   ├── fa4eebba089badc7590c6ad7dc3a60c252702282.nq.gz
│   │   └── fdd708493e4422dba6453908af55ef0d58767c03.nq.gz
│   ├── lsp
│   │   ├── 11aba3cc6bd430eec8260c4037265925709f924a.nq.gz
│   │   ├── 1b1108030c2116620117af7e238aed50c23fc186.nq.gz
│   │   ├── 248e210df242d18d7d2882c343d011d43bf4a4c1.nq.gz
│   │   ├── 65d8f4ffb3099319e88e9406c062da8568bf6a3a.nq.gz
│   │   ├── 70615e6a4e05adafe7e471f4706e90f8ee798292.nq.gz
│   │   ├── 7478b1f87279cd37e1de2a9be9c57861b66ec20d.nq.gz
│   │   ├── 7fe864e34294b465362ba55aa59626208edb1a49.nq.gz
│   │   ├── 8a48f9185341a61bb39428bf97087ed2dc5932f5.nq.gz
│   │   ├── 93b0b6892cc0cfee8d0bec4e2e1242c7df771f95.nq.gz
│   │   ├── 9eb7eb136f3e702e86f030e6984ef20d4d8521b6.nq.gz
│   │   ├── a19acb8f90226cfa6036672385479af5874ba975.nq.gz
│   │   ├── a1d2d089dd66ac0bbaf0fdd64709c66d796e83a3.nq.gz
│   │   ├── a233ca87bf888f5b821bc8ae8ae3343c1edba9e2.nq.gz
│   │   ├── bd5d2f4183503306e92d4883e0732e03763e8e6d.nq.gz
│   │   ├── c190a84bfe552c3804c0e0e04447b53257194de5.nq.gz
│   │   ├── cce89eb531cf9225faf87bc45d432da6561df8a0.nq.gz
│   │   ├── e82979dbcfe3324f895e714cf993eed60f20c287.nq.gz
│   │   ├── fa4eebba089badc7590c6ad7dc3a60c252702282.nq.gz
│   │   └── fdd708493e4422dba6453908af55ef0d58767c03.nq.gz
│   └── repolex
│       ├── 11aba3cc6bd430eec8260c4037265925709f924a.nq.gz
│       ├── 1b1108030c2116620117af7e238aed50c23fc186.nq.gz
│       ├── 248e210df242d18d7d2882c343d011d43bf4a4c1.nq.gz
│       ├── 65d8f4ffb3099319e88e9406c062da8568bf6a3a.nq.gz
│       ├── 70615e6a4e05adafe7e471f4706e90f8ee798292.nq.gz
│       ├── 7478b1f87279cd37e1de2a9be9c57861b66ec20d.nq.gz
│       ├── 7fe864e34294b465362ba55aa59626208edb1a49.nq.gz
│       ├── 8a48f9185341a61bb39428bf97087ed2dc5932f5.nq.gz
│       ├── 93b0b6892cc0cfee8d0bec4e2e1242c7df771f95.nq.gz
│       ├── 9eb7eb136f3e702e86f030e6984ef20d4d8521b6.nq.gz
│       ├── a19acb8f90226cfa6036672385479af5874ba975.nq.gz
│       ├── a1d2d089dd66ac0bbaf0fdd64709c66d796e83a3.nq.gz
│       ├── a233ca87bf888f5b821bc8ae8ae3343c1edba9e2.nq.gz
│       ├── bd5d2f4183503306e92d4883e0732e03763e8e6d.nq.gz
│       ├── c190a84bfe552c3804c0e0e04447b53257194de5.nq.gz
│       ├── cce89eb531cf9225faf87bc45d432da6561df8a0.nq.gz
│       ├── e82979dbcfe3324f895e714cf993eed60f20c287.nq.gz
│       ├── fa4eebba089badc7590c6ad7dc3a60c252702282.nq.gz
│       └── fdd708493e4422dba6453908af55ef0d58767c03.nq.gz
└── blob
    ├── 000500c88f03b68c4d7b254da04024d2a5915b57.nq.gz
    ├── 003e2ebbbb66f87af5bc207b3570b61a5defa151.nq.gz
    ├── 007720966a480779fa1b56a16f5e26a7604c4ba2.nq.gz
    ├── 00ae06618eff44f7ba871bfbcd24797e1d5d9140.nq.gz
    ├── 00b9e6bd64b4bef7ce62774109303ed9bbbaff60.nq.gz
    ├── 00f4160279d97b6471a13bfaa1e837c3d8ea494c.nq.gz
    ├── 01dd44d91551f1156a0ac59c8e3f7dc06d70020f.nq.gz
    ├── 01dd952343c305a6351d0d8749a066aa30787931.nq.gz
    ├── 02b096113b9887bea7bd17e5a5a091f682c838bd.nq.gz
    ├── 02e66e57f2a27341b3b195f7d9fe2dbb84299b3f.nq.gz
    ├── 033aa5be21def223fa3ed881920ccc5648bbcee8.nq.gz
    ├── 04579a66e8a7da7dc505a4bfde4121416ec130c1.nq.gz
    ├── 04697c711e2bc1959ea2cc899f409536eae94757.nq.gz
    ├── 046c68fec81ef1429ec43f8b0900f9586dbf2358.nq.gz
    ├── 049900bd4bf91f0956ff258912eaf35fe08e3875.nq.gz
    ├── 05476e788064e04e7e99617fdb1992832e9c1d6a.nq.gz
    ├── 0595f511bfea0f1692ad981d5307674bf81a3891.nq.gz
    ├── 059ba0bf8b71b6e2e2f95df2e13e4c8b73abd8c3.nq.gz
    ├── 05f3ffbe1ef8497fb6fb166456622854e47818ee.nq.gz
    ├── 05fdd6cb2abebdd518ce8ce95b492581ba9b2bbb.nq.gz
    ├── 0626bac9447ddc2d09aa137107fd7858ae6188d7.nq.gz
    ├── 0688a09250e72b2ab84fd3049a7f815c11d06fe1.nq.gz
    ├── 0703a84bba6b3161e8b380988d707b6d1e8af476.nq.gz
    ├── 077a2a23da509f5e449f3db72e45938e3e45761e.nq.gz
    ├── 078c64b706e26159d47b6aab77a010e8ae61e43b.nq.gz
    ├── 082d90712a7bb70479e3b0afc26e76f8fc377d26.nq.gz
    ├── 08405db3d129c6ac126ed6a4407f1298e283e70a.nq.gz
    ├── 085f4962c2dba50b26eae0b510aca5841e4838b9.nq.gz
    ├── 0977f97ff4795939c9657d0934e526c3adba4d9c.nq.gz
    ├── 09ab1e8b9bcced65bb834ddf64aaed7545d88b8f.nq.gz
    ├── 0a4ca3c6c7aa91706a28f6c96a1719b2acbbcfc6.nq.gz
    ├── 0a5d5c23d3e1d88f02fc7a7b409d715d15203c84.nq.gz
    ├── 0a9668079427bf7c4be0cf100044f45bbdd0678e.nq.gz
    ├── 0aa0d86f05e42d810b13162863427aafdafa5bfb.nq.gz
    ├── 0ab1ee02051578ec3cfd5cfb02547e0c9ebd578f.nq.gz
    ├── 0ab905d49f328aff4815c4893b94fd227f0b3f47.nq.gz
    ├── 0b49dc125d5fb83aa9f2848bf13af46bac0cc456.nq.gz
    ├── 0ba668a01475a400a1507799d418fb7a601b2d3f.nq.gz
    ├── 0c09b85dd3846aa941579205317ed30d0222a731.nq.gz
    ├── 0c14f6eac688e9a7ec262a6eff250c8f5bfcd921.nq.gz
    ├── 0c3c160b855fe702ecc7b1bfbacaa11411bec0d0.nq.gz
    ├── 0c63a21a7936055ca94dded291621dc7f91956fb.nq.gz
    ├── 0ca2082c027358709c512ef3ae8e4b4221c60b4c.nq.gz
    ├── 0cffc900c27926c96e9f88810d554f760b8cf311.nq.gz
    ├── 0d065f760db6762ae145be6f6bfa53755300e042.nq.gz
    ├── 0d4b70c978f7bcac50dbdb97fb8d105a8a14c200.nq.gz
    ├── 0d5662abba73e98bbef93f63f44cb84b9af26d13.nq.gz
    ├── 0d72635cc3b3de4ff6db8654039f372f097c656d.nq.gz
    ├── 0e1f9e4dd9bee4641ae1a3709132cdecc9bb71a3.nq.gz
    ├── 0e3d5e1b0ca9b57ec45014625da96eff4476340e.nq.gz
    ├── 0e7c3259e18b1b6091ead583b66d69cf11059e58.nq.gz
    ├── 0fafdb4e79e6f404496b8cf459b4379922c98fa3.nq.gz
    ├── 0fb14668e97875b68c8eb9299b4d67bcfb1dab6b.nq.gz
    ├── 100d7a6332b9b8461312f3f1db49bb647c3dadcb.nq.gz
    ├── 10735fed45e44623dec9358fc13fdcbe25a5bff7.nq.gz
    ├── 11710315d8e1b5ef239a22e3bff68bba7fce0b58.nq.gz
    ├── 11aac89448d9e1bc73f35b0ed8f96a86955cb91f.nq.gz
    ├── 11b7aff0d5feeaa7e000ffaf0524680df8818868.nq.gz
    ├── 125694c0da59bdd6ba6f24f4d356e1060205098b.nq.gz
    ├── 12b967d4be4a97ab0a5db90acb09cd1cbe10432a.nq.gz
    ├── 12ce125fe5d82d308099636c3e27d869f9763b03.nq.gz
    ├── 1319844f86b489479849976a0ae91bc1931705b9.nq.gz
    ├── 1327ca344fb9609d18b852911f088c3652ad3d17.nq.gz
    ├── 137699de55bbfc8c9b6e17313fbe34f9aeb23b23.nq.gz
    ├── 14614be5aba371ca14c6da541626ab55023e23e8.nq.gz
    ├── 1557254afb78c04858d56225d13049ed809a3b2c.nq.gz
    ├── 15b08a4fa1e2c3eafaaacf8d1e0c1fbe4151cb9e.nq.gz
    ├── 15e8327fbf48c5d604e3254f38afd3cdb2878f52.nq.gz
    ├── 166ee5d8cc9dc32d762837220513bd648850dbf6.nq.gz
    ├── 16d53abc74726c84fdc081933e56df50373da2c3.nq.gz
    ├── 174acdf4e145cde83be7f2cd1de80d855749f421.nq.gz
    ├── 179568c08ad921822d032dcbdac04ff496e6b59a.nq.gz
    ├── 17c57c8411cfa3769dc7795a47921791433d066e.nq.gz
    ├── 17e63698948605b2456bdb8e8c8e9829928b7b1f.nq.gz
    ├── 186ad7d04b2e1e763074878386d30e2d9ddddd61.nq.gz
    ├── 18bad943567b8d618c36038df2a120f46ddee0cc.nq.gz
    ├── 18f94aa18f4aabb636ac69d155105786a08dd98f.nq.gz
    ├── 19411a995a132a31a4f4a8c42000562d23b9d180.nq.gz
    ├── 1990b6b5e968076a7cb08b8d9a888dd0ee7d3672.nq.gz
    ├── 1a4521f050e1c3045dcd2d2f95db0be495ff7cf4.nq.gz
    ├── 1a650649b04506ff397d6e8392071d5eaf013fc4.nq.gz
    ├── 1a668051346859bf52010d7bfb5d7a982ba640fa.nq.gz
    ├── 1b28962db47652b39c82c54bc610c6d418075bce.nq.gz
    ├── 1b810f1c348e74c76201b0093a107c1cd532d8e1.nq.gz
    ├── 1c30074d38460e7e0096a35c91a0debe82319fe6.nq.gz
    ├── 1c35c3e3c62f25cd1d2d049b8d1fb09eaeb4e6af.nq.gz
    ├── 1c4885dc7d5fb12d196b8edb68459e88f2e98657.nq.gz
    ├── 1ca8cede25d71cbe0f25f17be9711a3ea131a76a.nq.gz
    ├── 1cf41a09ac9c1e5f45b07a36188fef24fa5ece7e.nq.gz
    ├── 1d10346797b3e19c19dda1c6f1df924dace19ec5.nq.gz
    ├── 1d38ddad6b20066fce9f10c01da591d7976fa259.nq.gz
    ├── 1d8faa8ee2e7299d9f973078ea8e60b8689940ad.nq.gz
    ├── 1dc16981b347d1700f5cb588253170ce01d02115.nq.gz
    ├── 1dc972cc80d4dd5ebaa7f89c847c2acfc968db9e.nq.gz
    ├── 1de895cf00aff211f9f1054384c0c198b1ea72a5.nq.gz
    ├── 1e6cec1458152ca9ac2d83a50b09a9ac36c07e29.nq.gz
    ├── 1f22460844904f876c674bf942853d99ad94bd68.nq.gz
    ├── 1f4a902a72f78bd9fe808d876c95a53a77090b19.nq.gz
    ├── 20302bb208a333706e92847241a8412a1bf55e1e.nq.gz
    ├── 204517b28e979085034d4660b7411d0c33bbfcd6.nq.gz
    ├── 205d2666492d00db9763c9c801a30fd437210c88.nq.gz
    ├── 20addf54a976c0595e14ff056926be06efdcff82.nq.gz
    ├── 2120a67ec62a7049bb524f30d80c6a852cd70996.nq.gz
    ├── 213695a0e1e929f9ec952bb17d0656aa22c571f4.nq.gz
    ├── 21d7db2aa64d6eb517d7c250cc91057fea9f3bfb.nq.gz
    ├── 222d3fb5b1930d488c4ca0d2347bc4a8953fe696.nq.gz
    ├── 2271df9d9fc8d0dc06b949b8a12a86573f93de72.nq.gz
    ├── 2292a3a84f70e2cb11a95b7b0017bb1a62359520.nq.gz
    ├── 22be848ce388836ac1861cb20b5f3856ceb8b8a7.nq.gz
    ├── 22dfa3e096cf9eb170265452a6ef269c105b9256.nq.gz
    ├── 22e423f9be2a54cc0f581e7de1d6b82e29968661.nq.gz
    ├── 2326971648a98bc06863ad5833ceb483f98858db.nq.gz
    ├── 232d8f7eaf54223b3d12ed4c7e7c2a51d6bb5099.nq.gz
    ├── 2373de715829f5b86d4072c011bfcb852717e403.nq.gz
    ├── 24417a3e525e19c3cade26513ae8aeed110647ce.nq.gz
    ├── 2509e2c4bdc7fae73f1032481bd802eb0abcd1a5.nq.gz
    ├── 254c2eab8dd7ea8b4981302a926bfba196dac99d.nq.gz
    ├── 256dcafe38550f7d9a09b34e8f4f05f6b4d0f1d8.nq.gz
    ├── 25971c62ca9318ffe70e2e3cd151cb36d81050b9.nq.gz
    ├── 25cf60c5e2b433d8a953bd1fd450287ccbdd4759.nq.gz
    ├── 264c5d550c283d3de3cf38a52b955f8058f64435.nq.gz
    ├── 265296521ff0c01abe3892fb952e67795c362e10.nq.gz
    ├── 28652f68f43b87f231870fba5c85b475a2479053.nq.gz
    ├── 28bdbb88fa2d62a96cb5cafad27324857a57ffcf.nq.gz
    ├── 290cd9190cc55cd031291ca4b3a4ae6804530e48.nq.gz
    └── 294e30e3162af8b4f105eb77f0bcda272590cf5f.nq.gz

7 directories, 200 files
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

## Source repository

[colinhacks/zod](https://github.com/colinhacks/zod)

---
*Parsed on 2026-03-20 by [repolex](https://repolex.ai)*
