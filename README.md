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
│   │   ├── 22f3cc6ed52a28c984a0319a1a03e1af244cee02.nq.gz
│   │   ├── 248e210df242d18d7d2882c343d011d43bf4a4c1.nq.gz
│   │   ├── 3b75ae584e31d8bd06f7298247cd3d27520cf881.nq.gz
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
│   │   ├── e6939195fbb5191402ba3d6f5b7aade463de6e51.nq.gz
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
│   │   ├── 22f3cc6ed52a28c984a0319a1a03e1af244cee02.nq.gz
│   │   ├── 248e210df242d18d7d2882c343d011d43bf4a4c1.nq.gz
│   │   ├── 3b75ae584e31d8bd06f7298247cd3d27520cf881.nq.gz
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
│   │   ├── e6939195fbb5191402ba3d6f5b7aade463de6e51.nq.gz
│   │   ├── e82979dbcfe3324f895e714cf993eed60f20c287.nq.gz
│   │   ├── fa4eebba089badc7590c6ad7dc3a60c252702282.nq.gz
│   │   └── fdd708493e4422dba6453908af55ef0d58767c03.nq.gz
│   └── repolex
│       ├── 11aba3cc6bd430eec8260c4037265925709f924a.nq.gz
│       ├── 1b1108030c2116620117af7e238aed50c23fc186.nq.gz
│       ├── 22f3cc6ed52a28c984a0319a1a03e1af244cee02.nq.gz
│       ├── 248e210df242d18d7d2882c343d011d43bf4a4c1.nq.gz
│       ├── 3b75ae584e31d8bd06f7298247cd3d27520cf881.nq.gz
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
│       ├── e6939195fbb5191402ba3d6f5b7aade463de6e51.nq.gz
│       ├── e82979dbcfe3324f895e714cf993eed60f20c287.nq.gz
│       ├── fa4eebba089badc7590c6ad7dc3a60c252702282.nq.gz
│       └── fdd708493e4422dba6453908af55ef0d58767c03.nq.gz
└── blob
    ├── 000500c88f03b68c4d7b254da04024d2a5915b57.nq.gz
    ├── 002e17d9c011e9a1a9dd867c401fc878c8bf15a5.nq.gz
    ├── 003e2ebbbb66f87af5bc207b3570b61a5defa151.nq.gz
    ├── 007720966a480779fa1b56a16f5e26a7604c4ba2.nq.gz
    ├── 00ae06618eff44f7ba871bfbcd24797e1d5d9140.nq.gz
    ├── 00b9e6bd64b4bef7ce62774109303ed9bbbaff60.nq.gz
    ├── 00f4160279d97b6471a13bfaa1e837c3d8ea494c.nq.gz
    ├── 01b1cfa41eb378b996600a0a50a691a8201ba560.nq.gz
    ├── 01dd44d91551f1156a0ac59c8e3f7dc06d70020f.nq.gz
    ├── 01dd952343c305a6351d0d8749a066aa30787931.nq.gz
    ├── 02b096113b9887bea7bd17e5a5a091f682c838bd.nq.gz
    ├── 02e66e57f2a27341b3b195f7d9fe2dbb84299b3f.nq.gz
    ├── 033aa5be21def223fa3ed881920ccc5648bbcee8.nq.gz
    ├── 04579a66e8a7da7dc505a4bfde4121416ec130c1.nq.gz
    ├── 04697c711e2bc1959ea2cc899f409536eae94757.nq.gz
    ├── 046c68fec81ef1429ec43f8b0900f9586dbf2358.nq.gz
    ├── 049900bd4bf91f0956ff258912eaf35fe08e3875.nq.gz
    ├── 04e1efe409c08704fb115f0df4b777815cea1bfa.nq.gz
    ├── 05476e788064e04e7e99617fdb1992832e9c1d6a.nq.gz
    ├── 058da47fa9bcdb1140ab45d8e5dd97a8f97c10cc.nq.gz
    ├── 0595f511bfea0f1692ad981d5307674bf81a3891.nq.gz
    ├── 059ba0bf8b71b6e2e2f95df2e13e4c8b73abd8c3.nq.gz
    ├── 05f3ffbe1ef8497fb6fb166456622854e47818ee.nq.gz
    ├── 05fdd6cb2abebdd518ce8ce95b492581ba9b2bbb.nq.gz
    ├── 0626bac9447ddc2d09aa137107fd7858ae6188d7.nq.gz
    ├── 0665af2751ee92f65e702d020b63ec9dd0bc0642.nq.gz
    ├── 0682c4713e40362b395c3fc89c33648f264e84e9.nq.gz
    ├── 0688a09250e72b2ab84fd3049a7f815c11d06fe1.nq.gz
    ├── 0703a84bba6b3161e8b380988d707b6d1e8af476.nq.gz
    ├── 073703ed43add822cb05d2c52801e7d1212192e5.nq.gz
    ├── 073bc533d96b18c5be94f7338326b8c54e770018.nq.gz
    ├── 077a2a23da509f5e449f3db72e45938e3e45761e.nq.gz
    ├── 078c64b706e26159d47b6aab77a010e8ae61e43b.nq.gz
    ├── 07b380c1468c0b61a5c6f6e589e4b16d4da8088c.nq.gz
    ├── 07c698b548b1ed16c85c33626a8a1c14587affe4.nq.gz
    ├── 082d90712a7bb70479e3b0afc26e76f8fc377d26.nq.gz
    ├── 0839322bb95b5563a92d33467df6e7e6f85bef6f.nq.gz
    ├── 08405db3d129c6ac126ed6a4407f1298e283e70a.nq.gz
    ├── 085f4962c2dba50b26eae0b510aca5841e4838b9.nq.gz
    ├── 08d9e5fc831af08a4f0df0344dcd0b2bfde07ad7.nq.gz
    ├── 096278dcf5b01079cd18cc0fddbdf59a3e0961ce.nq.gz
    ├── 0977f97ff4795939c9657d0934e526c3adba4d9c.nq.gz
    ├── 09ab1e8b9bcced65bb834ddf64aaed7545d88b8f.nq.gz
    ├── 09ec4515279c718bbafd94e6dbef962f215b6136.nq.gz
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
    ├── 0ec2f40a05462904511039cb0f3fb6dcf641b7e1.nq.gz
    ├── 0f80aa030fca77c2fae1c3376d81f1abd3fabc9b.nq.gz
    ├── 0fafdb4e79e6f404496b8cf459b4379922c98fa3.nq.gz
    ├── 0fb14668e97875b68c8eb9299b4d67bcfb1dab6b.nq.gz
    ├── 0fb9ca46c608535c7ccf506d5a3881bf3aa3ca22.nq.gz
    ├── 100d7a6332b9b8461312f3f1db49bb647c3dadcb.nq.gz
    ├── 10735fed45e44623dec9358fc13fdcbe25a5bff7.nq.gz
    ├── 108b12e91b95b67cb51aba701aab82aeb9b65634.nq.gz
    ├── 111888e57f88de951ec5f9959b34ada6f076ed93.nq.gz
    ├── 11325a95b6466b4c0b536a323ba13df5a6247631.nq.gz
    ├── 11710315d8e1b5ef239a22e3bff68bba7fce0b58.nq.gz
    ├── 119dbe054fc77363f8e71cbb1f0387f5b4d03005.nq.gz
    ├── 11aac89448d9e1bc73f35b0ed8f96a86955cb91f.nq.gz
    ├── 11b7aff0d5feeaa7e000ffaf0524680df8818868.nq.gz
    ├── 11f726ea801cda1c5c22a427b47e92ac56203415.nq.gz
    ├── 125694c0da59bdd6ba6f24f4d356e1060205098b.nq.gz
    ├── 12b967d4be4a97ab0a5db90acb09cd1cbe10432a.nq.gz
    ├── 12ce125fe5d82d308099636c3e27d869f9763b03.nq.gz
    ├── 1319844f86b489479849976a0ae91bc1931705b9.nq.gz
    ├── 1327ca344fb9609d18b852911f088c3652ad3d17.nq.gz
    ├── 134d03954ccd68f619a82319f17cb2297ebdf558.nq.gz
    ├── 137699de55bbfc8c9b6e17313fbe34f9aeb23b23.nq.gz
    ├── 140f728e66348664fdb051774b5cd768e28c0694.nq.gz
    ├── 14614be5aba371ca14c6da541626ab55023e23e8.nq.gz
    ├── 1557254afb78c04858d56225d13049ed809a3b2c.nq.gz
    ├── 158ac0a67e80411766e508d5376fd253b6928227.nq.gz
    ├── 158bdd1191d2f32bb0730d996e066477e9bbe552.nq.gz
    ├── 15b08a4fa1e2c3eafaaacf8d1e0c1fbe4151cb9e.nq.gz
    ├── 15e8327fbf48c5d604e3254f38afd3cdb2878f52.nq.gz
    ├── 166ee5d8cc9dc32d762837220513bd648850dbf6.nq.gz
    ├── 16d53abc74726c84fdc081933e56df50373da2c3.nq.gz
    ├── 174acdf4e145cde83be7f2cd1de80d855749f421.nq.gz
    ├── 179568c08ad921822d032dcbdac04ff496e6b59a.nq.gz
    ├── 17c57c8411cfa3769dc7795a47921791433d066e.nq.gz
    ├── 17e63698948605b2456bdb8e8c8e9829928b7b1f.nq.gz
    ├── 17e7404b85869a31710ef01f2f186da1b6d8147d.nq.gz
    ├── 1825753a956b37b296ead0b91150583c45b621af.nq.gz
    ├── 186ad7d04b2e1e763074878386d30e2d9ddddd61.nq.gz
    ├── 18bad943567b8d618c36038df2a120f46ddee0cc.nq.gz
    ├── 18f94aa18f4aabb636ac69d155105786a08dd98f.nq.gz
    ├── 19411a995a132a31a4f4a8c42000562d23b9d180.nq.gz
    ├── 1990b6b5e968076a7cb08b8d9a888dd0ee7d3672.nq.gz
    ├── 1a4521f050e1c3045dcd2d2f95db0be495ff7cf4.nq.gz
    ├── 1a650649b04506ff397d6e8392071d5eaf013fc4.nq.gz
    ├── 1a668051346859bf52010d7bfb5d7a982ba640fa.nq.gz
    ├── 1a9fe2c6d0620e7dd3b0ed69bc26d6c80521ef9c.nq.gz
    ├── 1aea6fcdb3fdde7ae3495a19dde5c3704be91041.nq.gz
    ├── 1b28962db47652b39c82c54bc610c6d418075bce.nq.gz
    ├── 1b810f1c348e74c76201b0093a107c1cd532d8e1.nq.gz
    ├── 1c23cb9c583e4664eb620e1479ebff8cd33f92ae.nq.gz
    ├── 1c30074d38460e7e0096a35c91a0debe82319fe6.nq.gz
    └── 1c35c3e3c62f25cd1d2d049b8d1fb09eaeb4e6af.nq.gz

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
