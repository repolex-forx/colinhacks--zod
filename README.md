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
│   │   ├── 4063e802d539d04182fc3e66a543ae6d1ba5658e.nq.gz
│   │   ├── 59768246aa57133184b2cf3f7c2a1ba5c3ab08c3.nq.gz
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
│   │   ├── ca3c8629c0c2715571f70b44c2433cad3db7fe4e.nq.gz
│   │   ├── ca42965df46b2f7e2747db29c40a26bcb32a51d5.nq.gz
│   │   ├── cc63f950158db212c5e9b75e7d22faca851ea624.nq.gz
│   │   ├── cce89eb531cf9225faf87bc45d432da6561df8a0.nq.gz
│   │   ├── e62341b1aaf720709ee5f31785db25d5c0491659.nq.gz
│   │   ├── e6939195fbb5191402ba3d6f5b7aade463de6e51.nq.gz
│   │   ├── e7a9b9b3033991be6b4225f1be21da39c250bbb0.nq.gz
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
│   │   ├── 4063e802d539d04182fc3e66a543ae6d1ba5658e.nq.gz
│   │   ├── 59768246aa57133184b2cf3f7c2a1ba5c3ab08c3.nq.gz
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
│   │   ├── ca3c8629c0c2715571f70b44c2433cad3db7fe4e.nq.gz
│   │   ├── ca42965df46b2f7e2747db29c40a26bcb32a51d5.nq.gz
│   │   ├── cc63f950158db212c5e9b75e7d22faca851ea624.nq.gz
│   │   ├── cce89eb531cf9225faf87bc45d432da6561df8a0.nq.gz
│   │   ├── e62341b1aaf720709ee5f31785db25d5c0491659.nq.gz
│   │   ├── e6939195fbb5191402ba3d6f5b7aade463de6e51.nq.gz
│   │   ├── e7a9b9b3033991be6b4225f1be21da39c250bbb0.nq.gz
│   │   ├── e82979dbcfe3324f895e714cf993eed60f20c287.nq.gz
│   │   ├── fa4eebba089badc7590c6ad7dc3a60c252702282.nq.gz
│   │   └── fdd708493e4422dba6453908af55ef0d58767c03.nq.gz
│   └── repolex
│       ├── 11aba3cc6bd430eec8260c4037265925709f924a.nq.gz
│       ├── 1b1108030c2116620117af7e238aed50c23fc186.nq.gz
│       ├── 22f3cc6ed52a28c984a0319a1a03e1af244cee02.nq.gz
│       ├── 248e210df242d18d7d2882c343d011d43bf4a4c1.nq.gz
│       ├── 3b75ae584e31d8bd06f7298247cd3d27520cf881.nq.gz
│       ├── 4063e802d539d04182fc3e66a543ae6d1ba5658e.nq.gz
│       ├── 59768246aa57133184b2cf3f7c2a1ba5c3ab08c3.nq.gz
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
│       ├── ca3c8629c0c2715571f70b44c2433cad3db7fe4e.nq.gz
│       ├── ca42965df46b2f7e2747db29c40a26bcb32a51d5.nq.gz
│       ├── cc63f950158db212c5e9b75e7d22faca851ea624.nq.gz
│       ├── cce89eb531cf9225faf87bc45d432da6561df8a0.nq.gz
│       ├── e62341b1aaf720709ee5f31785db25d5c0491659.nq.gz
│       ├── e6939195fbb5191402ba3d6f5b7aade463de6e51.nq.gz
│       ├── e7a9b9b3033991be6b4225f1be21da39c250bbb0.nq.gz
│       ├── e82979dbcfe3324f895e714cf993eed60f20c287.nq.gz
│       ├── fa4eebba089badc7590c6ad7dc3a60c252702282.nq.gz
│       └── fdd708493e4422dba6453908af55ef0d58767c03.nq.gz
└── blob
    ├── 000500c88f03b68c4d7b254da04024d2a5915b57.nq.gz
    ├── 002e17d9c011e9a1a9dd867c401fc878c8bf15a5.nq.gz
    ├── 003caa409b1265d209a3ad049d7c9c2e7fafd8ef.nq.gz
    ├── 003e2ebbbb66f87af5bc207b3570b61a5defa151.nq.gz
    ├── 007720966a480779fa1b56a16f5e26a7604c4ba2.nq.gz
    ├── 00aaa0d3e1609ddf3801b6a110405352074b4627.nq.gz
    ├── 00ae06618eff44f7ba871bfbcd24797e1d5d9140.nq.gz
    ├── 00b9e6bd64b4bef7ce62774109303ed9bbbaff60.nq.gz
    ├── 00b9fc8e61955d91a7bf3bdc027dce0f062b8a1c.nq.gz
    ├── 00c5ebc67c72b17f76201dcb3ed65881f9954a23.nq.gz
    ├── 00f4160279d97b6471a13bfaa1e837c3d8ea494c.nq.gz
    ├── 010708c6b9e8c69389d105e9e097cb91cfb428cb.nq.gz
    ├── 0117594c5cc9c7c42f4313e3ee6d7d7f295b8e97.nq.gz
    ├── 012277e5c20934bb4a2f1470aa31b84f7235580b.nq.gz
    ├── 016c954fce821de87946e5c12a1bc32a19c2953f.nq.gz
    ├── 017a1c13e48a2570642ce99d66b345020e3ca0aa.nq.gz
    ├── 01b1cfa41eb378b996600a0a50a691a8201ba560.nq.gz
    ├── 01dbc4f1e1acee18b28771fedfef1eb0fc8e4928.nq.gz
    ├── 01dd44d91551f1156a0ac59c8e3f7dc06d70020f.nq.gz
    ├── 01dd952343c305a6351d0d8749a066aa30787931.nq.gz
    ├── 01f3a1a0d8e36d74fe86aeadf212a350d9261636.nq.gz
    ├── 0221b1753bd0e91f7e29410422914ea6d6bcd5ab.nq.gz
    ├── 023043aa1eb600da2e9c6f3175e4cea46d4c80da.nq.gz
    ├── 0242cb654c50fdcf57c4ea0b124a0d5d3b1a1977.nq.gz
    ├── 0264f82ef2e381ed4e855932c1992a10da28b015.nq.gz
    ├── 02a6e05d10047ab2cb844e5e886b699c42748f1b.nq.gz
    ├── 02b096113b9887bea7bd17e5a5a091f682c838bd.nq.gz
    ├── 02e66e57f2a27341b3b195f7d9fe2dbb84299b3f.nq.gz
    ├── 030ea821b694ed03e210b418c8742c7a535ac816.nq.gz
    ├── 033aa5be21def223fa3ed881920ccc5648bbcee8.nq.gz
    ├── 03b9c7871a2d36c9cdd46e4717794649224bd2fe.nq.gz
    ├── 04579a66e8a7da7dc505a4bfde4121416ec130c1.nq.gz
    ├── 045b65f83e96a233149eaa1c84101a86b5a3056d.nq.gz
    ├── 04658fd762c14831d2855ec59d28e3f36bdba80c.nq.gz
    ├── 04697c711e2bc1959ea2cc899f409536eae94757.nq.gz
    ├── 046c68fec81ef1429ec43f8b0900f9586dbf2358.nq.gz
    ├── 049900bd4bf91f0956ff258912eaf35fe08e3875.nq.gz
    ├── 04e1efe409c08704fb115f0df4b777815cea1bfa.nq.gz
    ├── 05476e788064e04e7e99617fdb1992832e9c1d6a.nq.gz
    ├── 0562e5ea78bd4c52e967277173bcc799a9a9f586.nq.gz
    ├── 05674fec92559a9e3c2eab95febe564ee0264569.nq.gz
    ├── 058bf6cb30da6580a7837aacb2e343a398e22819.nq.gz
    ├── 058da47fa9bcdb1140ab45d8e5dd97a8f97c10cc.nq.gz
    ├── 0595f511bfea0f1692ad981d5307674bf81a3891.nq.gz
    ├── 059ba0bf8b71b6e2e2f95df2e13e4c8b73abd8c3.nq.gz
    ├── 05bcf9e25e00f7a5e8777f3aa0ecb28b0837187c.nq.gz
    ├── 05e4c51bd2781d47565eefc2c5388dafafac90a6.nq.gz
    ├── 05f3ffbe1ef8497fb6fb166456622854e47818ee.nq.gz
    ├── 05fdd6cb2abebdd518ce8ce95b492581ba9b2bbb.nq.gz
    ├── 0626bac9447ddc2d09aa137107fd7858ae6188d7.nq.gz
    ├── 0652c7e26e38935c2f4c0a469f987f5cd03f6fe3.nq.gz
    ├── 0665af2751ee92f65e702d020b63ec9dd0bc0642.nq.gz
    ├── 0682c4713e40362b395c3fc89c33648f264e84e9.nq.gz
    ├── 0688a09250e72b2ab84fd3049a7f815c11d06fe1.nq.gz
    ├── 0703a84bba6b3161e8b380988d707b6d1e8af476.nq.gz
    ├── 07193fd135b70d85ed46a806faf921fea9370ad3.nq.gz
    ├── 0731f81a2bd65fe420b7d1254e6a0ca7a858dca7.nq.gz
    ├── 073703ed43add822cb05d2c52801e7d1212192e5.nq.gz
    ├── 073bc533d96b18c5be94f7338326b8c54e770018.nq.gz
    ├── 077a2a23da509f5e449f3db72e45938e3e45761e.nq.gz
    ├── 078c64b706e26159d47b6aab77a010e8ae61e43b.nq.gz
    ├── 07b380c1468c0b61a5c6f6e589e4b16d4da8088c.nq.gz
    ├── 07c698b548b1ed16c85c33626a8a1c14587affe4.nq.gz
    ├── 07f40fb006efe1e14fe40dfa5a1aa57ea45d98df.nq.gz
    ├── 082d90712a7bb70479e3b0afc26e76f8fc377d26.nq.gz
    ├── 0839322bb95b5563a92d33467df6e7e6f85bef6f.nq.gz
    ├── 08405db3d129c6ac126ed6a4407f1298e283e70a.nq.gz
    ├── 084deaa5bccb65fc53d80e0e94939126d755850d.nq.gz
    ├── 085f4962c2dba50b26eae0b510aca5841e4838b9.nq.gz
    ├── 08649953c0e14eedf2220570f8b55241f7bb1718.nq.gz
    ├── 08d9e5fc831af08a4f0df0344dcd0b2bfde07ad7.nq.gz
    ├── 093a08857152114e20e34c861cb16f72a78ae1a7.nq.gz
    ├── 095e4af5675efb25b470bb3149e6bd3cd8d36963.nq.gz
    ├── 096278dcf5b01079cd18cc0fddbdf59a3e0961ce.nq.gz
    ├── 0968a1efbd7c5feb4db67a7f11c13751d6b2a57c.nq.gz
    ├── 0977f97ff4795939c9657d0934e526c3adba4d9c.nq.gz
    ├── 09ab1e8b9bcced65bb834ddf64aaed7545d88b8f.nq.gz
    ├── 09d880e9166fd5703c61aac5ee5d5e4e2f93cc70.nq.gz
    ├── 09ec4515279c718bbafd94e6dbef962f215b6136.nq.gz
    ├── 09f5a200445f073981407384c87e37bf4f9ece99.nq.gz
    ├── 0a4ca3c6c7aa91706a28f6c96a1719b2acbbcfc6.nq.gz
    ├── 0a5d5c23d3e1d88f02fc7a7b409d715d15203c84.nq.gz
    ├── 0a9668079427bf7c4be0cf100044f45bbdd0678e.nq.gz
    ├── 0aa0d86f05e42d810b13162863427aafdafa5bfb.nq.gz
    ├── 0ab1ee02051578ec3cfd5cfb02547e0c9ebd578f.nq.gz
    ├── 0ab905d49f328aff4815c4893b94fd227f0b3f47.nq.gz
    ├── 0b0574e80fc5fc67966a4f78bcf2507a239c298b.nq.gz
    ├── 0b0adbacd878c510a94e46b07b002c916cd6be43.nq.gz
    ├── 0b0e678b7c87c7181656c4f9474b446cd0298ad2.nq.gz
    ├── 0b49dc125d5fb83aa9f2848bf13af46bac0cc456.nq.gz
    ├── 0b78004b5a4885b0be58aa39b40bbd8b3ae67442.nq.gz
    ├── 0ba668a01475a400a1507799d418fb7a601b2d3f.nq.gz
    ├── 0c09b85dd3846aa941579205317ed30d0222a731.nq.gz
    ├── 0c14f6eac688e9a7ec262a6eff250c8f5bfcd921.nq.gz
    ├── 0c2a1d96f42a29a9ad420c1ac3a60e64e4d91baa.nq.gz
    └── 0c3c160b855fe702ecc7b1bfbacaa11411bec0d0.nq.gz

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
*Parsed on 2026-03-31 by [repolex](https://repolex.ai)*
