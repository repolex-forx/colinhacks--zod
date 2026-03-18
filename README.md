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
│   │   ├── 7478b1f87279cd37e1de2a9be9c57861b66ec20d.nq.gz
│   │   ├── 7fe864e34294b465362ba55aa59626208edb1a49.nq.gz
│   │   ├── 93b0b6892cc0cfee8d0bec4e2e1242c7df771f95.nq.gz
│   │   ├── 9eb7eb136f3e702e86f030e6984ef20d4d8521b6.nq.gz
│   │   ├── a1d2d089dd66ac0bbaf0fdd64709c66d796e83a3.nq.gz
│   │   ├── a233ca87bf888f5b821bc8ae8ae3343c1edba9e2.nq.gz
│   │   ├── cce89eb531cf9225faf87bc45d432da6561df8a0.nq.gz
│   │   └── e82979dbcfe3324f895e714cf993eed60f20c287.nq.gz
│   ├── dataflow
│   │   ├── 11aba3cc6bd430eec8260c4037265925709f924a.nq.gz
│   │   ├── 1b1108030c2116620117af7e238aed50c23fc186.nq.gz
│   │   ├── 248e210df242d18d7d2882c343d011d43bf4a4c1.nq.gz
│   │   ├── 7478b1f87279cd37e1de2a9be9c57861b66ec20d.nq.gz
│   │   ├── 7fe864e34294b465362ba55aa59626208edb1a49.nq.gz
│   │   ├── 93b0b6892cc0cfee8d0bec4e2e1242c7df771f95.nq.gz
│   │   ├── 9eb7eb136f3e702e86f030e6984ef20d4d8521b6.nq.gz
│   │   ├── a1d2d089dd66ac0bbaf0fdd64709c66d796e83a3.nq.gz
│   │   ├── a233ca87bf888f5b821bc8ae8ae3343c1edba9e2.nq.gz
│   │   ├── cce89eb531cf9225faf87bc45d432da6561df8a0.nq.gz
│   │   └── e82979dbcfe3324f895e714cf993eed60f20c287.nq.gz
│   ├── lsp
│   │   ├── 11aba3cc6bd430eec8260c4037265925709f924a.nq.gz
│   │   ├── 1b1108030c2116620117af7e238aed50c23fc186.nq.gz
│   │   ├── 248e210df242d18d7d2882c343d011d43bf4a4c1.nq.gz
│   │   ├── 7478b1f87279cd37e1de2a9be9c57861b66ec20d.nq.gz
│   │   ├── 7fe864e34294b465362ba55aa59626208edb1a49.nq.gz
│   │   ├── 93b0b6892cc0cfee8d0bec4e2e1242c7df771f95.nq.gz
│   │   ├── 9eb7eb136f3e702e86f030e6984ef20d4d8521b6.nq.gz
│   │   ├── a1d2d089dd66ac0bbaf0fdd64709c66d796e83a3.nq.gz
│   │   ├── a233ca87bf888f5b821bc8ae8ae3343c1edba9e2.nq.gz
│   │   ├── cce89eb531cf9225faf87bc45d432da6561df8a0.nq.gz
│   │   └── e82979dbcfe3324f895e714cf993eed60f20c287.nq.gz
│   └── repolex
│       ├── 11aba3cc6bd430eec8260c4037265925709f924a.nq.gz
│       ├── 1b1108030c2116620117af7e238aed50c23fc186.nq.gz
│       ├── 248e210df242d18d7d2882c343d011d43bf4a4c1.nq.gz
│       ├── 7478b1f87279cd37e1de2a9be9c57861b66ec20d.nq.gz
│       ├── 7fe864e34294b465362ba55aa59626208edb1a49.nq.gz
│       ├── 93b0b6892cc0cfee8d0bec4e2e1242c7df771f95.nq.gz
│       ├── 9eb7eb136f3e702e86f030e6984ef20d4d8521b6.nq.gz
│       ├── a1d2d089dd66ac0bbaf0fdd64709c66d796e83a3.nq.gz
│       ├── a233ca87bf888f5b821bc8ae8ae3343c1edba9e2.nq.gz
│       ├── cce89eb531cf9225faf87bc45d432da6561df8a0.nq.gz
│       └── e82979dbcfe3324f895e714cf993eed60f20c287.nq.gz
└── blob
    ├── 007720966a480779fa1b56a16f5e26a7604c4ba2.nq.gz
    ├── 00b9e6bd64b4bef7ce62774109303ed9bbbaff60.nq.gz
    ├── 00f4160279d97b6471a13bfaa1e837c3d8ea494c.nq.gz
    ├── 01dd44d91551f1156a0ac59c8e3f7dc06d70020f.nq.gz
    ├── 01dd952343c305a6351d0d8749a066aa30787931.nq.gz
    ├── 02b096113b9887bea7bd17e5a5a091f682c838bd.nq.gz
    ├── 033aa5be21def223fa3ed881920ccc5648bbcee8.nq.gz
    ├── 04697c711e2bc1959ea2cc899f409536eae94757.nq.gz
    ├── 046c68fec81ef1429ec43f8b0900f9586dbf2358.nq.gz
    ├── 0595f511bfea0f1692ad981d5307674bf81a3891.nq.gz
    ├── 05f3ffbe1ef8497fb6fb166456622854e47818ee.nq.gz
    ├── 05fdd6cb2abebdd518ce8ce95b492581ba9b2bbb.nq.gz
    ├── 0688a09250e72b2ab84fd3049a7f815c11d06fe1.nq.gz
    ├── 077a2a23da509f5e449f3db72e45938e3e45761e.nq.gz
    ├── 082d90712a7bb70479e3b0afc26e76f8fc377d26.nq.gz
    ├── 0977f97ff4795939c9657d0934e526c3adba4d9c.nq.gz
    ├── 0a4ca3c6c7aa91706a28f6c96a1719b2acbbcfc6.nq.gz
    ├── 0a5d5c23d3e1d88f02fc7a7b409d715d15203c84.nq.gz
    ├── 0a9668079427bf7c4be0cf100044f45bbdd0678e.nq.gz
    ├── 0aa0d86f05e42d810b13162863427aafdafa5bfb.nq.gz
    ├── 0ab905d49f328aff4815c4893b94fd227f0b3f47.nq.gz
    ├── 0ba668a01475a400a1507799d418fb7a601b2d3f.nq.gz
    ├── 0c09b85dd3846aa941579205317ed30d0222a731.nq.gz
    ├── 0c14f6eac688e9a7ec262a6eff250c8f5bfcd921.nq.gz
    ├── 0c63a21a7936055ca94dded291621dc7f91956fb.nq.gz
    ├── 0cffc900c27926c96e9f88810d554f760b8cf311.nq.gz
    ├── 0d4b70c978f7bcac50dbdb97fb8d105a8a14c200.nq.gz
    ├── 0d72635cc3b3de4ff6db8654039f372f097c656d.nq.gz
    ├── 0e7c3259e18b1b6091ead583b66d69cf11059e58.nq.gz
    ├── 10735fed45e44623dec9358fc13fdcbe25a5bff7.nq.gz
    ├── 11aac89448d9e1bc73f35b0ed8f96a86955cb91f.nq.gz
    ├── 125694c0da59bdd6ba6f24f4d356e1060205098b.nq.gz
    ├── 137699de55bbfc8c9b6e17313fbe34f9aeb23b23.nq.gz
    ├── 14614be5aba371ca14c6da541626ab55023e23e8.nq.gz
    ├── 1557254afb78c04858d56225d13049ed809a3b2c.nq.gz
    ├── 15b08a4fa1e2c3eafaaacf8d1e0c1fbe4151cb9e.nq.gz
    ├── 166ee5d8cc9dc32d762837220513bd648850dbf6.nq.gz
    ├── 16d53abc74726c84fdc081933e56df50373da2c3.nq.gz
    ├── 179568c08ad921822d032dcbdac04ff496e6b59a.nq.gz
    ├── 17c57c8411cfa3769dc7795a47921791433d066e.nq.gz
    ├── 186ad7d04b2e1e763074878386d30e2d9ddddd61.nq.gz
    ├── 18bad943567b8d618c36038df2a120f46ddee0cc.nq.gz
    ├── 18f94aa18f4aabb636ac69d155105786a08dd98f.nq.gz
    ├── 19411a995a132a31a4f4a8c42000562d23b9d180.nq.gz
    ├── 1a4521f050e1c3045dcd2d2f95db0be495ff7cf4.nq.gz
    ├── 1a668051346859bf52010d7bfb5d7a982ba640fa.nq.gz
    ├── 1b810f1c348e74c76201b0093a107c1cd532d8e1.nq.gz
    ├── 1c35c3e3c62f25cd1d2d049b8d1fb09eaeb4e6af.nq.gz
    ├── 1c4885dc7d5fb12d196b8edb68459e88f2e98657.nq.gz
    ├── 1ca8cede25d71cbe0f25f17be9711a3ea131a76a.nq.gz
    ├── 1cf41a09ac9c1e5f45b07a36188fef24fa5ece7e.nq.gz
    ├── 1d10346797b3e19c19dda1c6f1df924dace19ec5.nq.gz
    ├── 1d8faa8ee2e7299d9f973078ea8e60b8689940ad.nq.gz
    ├── 1dc16981b347d1700f5cb588253170ce01d02115.nq.gz
    ├── 1dc972cc80d4dd5ebaa7f89c847c2acfc968db9e.nq.gz
    ├── 1de895cf00aff211f9f1054384c0c198b1ea72a5.nq.gz
    ├── 1e6cec1458152ca9ac2d83a50b09a9ac36c07e29.nq.gz
    ├── 20addf54a976c0595e14ff056926be06efdcff82.nq.gz
    ├── 2120a67ec62a7049bb524f30d80c6a852cd70996.nq.gz
    ├── 22be848ce388836ac1861cb20b5f3856ceb8b8a7.nq.gz
    ├── 22e423f9be2a54cc0f581e7de1d6b82e29968661.nq.gz
    ├── 2326971648a98bc06863ad5833ceb483f98858db.nq.gz
    ├── 232d8f7eaf54223b3d12ed4c7e7c2a51d6bb5099.nq.gz
    ├── 2509e2c4bdc7fae73f1032481bd802eb0abcd1a5.nq.gz
    ├── 254c2eab8dd7ea8b4981302a926bfba196dac99d.nq.gz
    ├── 25cf60c5e2b433d8a953bd1fd450287ccbdd4759.nq.gz
    ├── 264c5d550c283d3de3cf38a52b955f8058f64435.nq.gz
    ├── 265296521ff0c01abe3892fb952e67795c362e10.nq.gz
    ├── 28652f68f43b87f231870fba5c85b475a2479053.nq.gz
    ├── 28bdbb88fa2d62a96cb5cafad27324857a57ffcf.nq.gz
    ├── 290cd9190cc55cd031291ca4b3a4ae6804530e48.nq.gz
    ├── 2aa3d51904efc1560e542466b23ebef28469362c.nq.gz
    ├── 2aa93adda5ceff65a9b94f3013b2121dd6bb1d64.nq.gz
    ├── 2ab8be639343d06d0e806b891e5f9c244d7801f2.nq.gz
    ├── 2ad4194efecd89331e8e50c0f781108188b4c856.nq.gz
    ├── 2b255319531b901fd665d4f1126d636b9627bda9.nq.gz
    ├── 2b2dd4bcc7d1cc9554bc22aa955b1fb24b441600.nq.gz
    ├── 2bee72a1e1127e4f65ce0feffd71cacf1e25484a.nq.gz
    ├── 2c405df0f4087191195817d0fdb7930fc90ae19e.nq.gz
    ├── 2c93bb52b93391e665d01947afadde0d98e0ede5.nq.gz
    ├── 2d07f2fdd242cd2d78ad472e0dc15ecf25376a99.nq.gz
    ├── 2d4231c313080ca4c86cca6ef2756655f935d5fd.nq.gz
    ├── 2d5d6f0c61a94953aa440e13ca2ebfe7074cf02c.nq.gz
    ├── 2e498a7e71d365a9a38da27fbcf3403411675afa.nq.gz
    ├── 2e94024260e04605b68630addf1de935d39f8e5a.nq.gz
    ├── 2eb4ddc5b3a5edd679e36ca2a197e9ebe27acb40.nq.gz
    ├── 300f3015a928a935816dc66d996f2613fb93d66c.nq.gz
    ├── 302b9c3f6442b26712c283a8d44fb26f7ef3164f.nq.gz
    ├── 30e69c27bf62a088331c31ac5ab67936e1c2c647.nq.gz
    ├── 30eb0dd907ce4608673353252d5a1b583eb253f1.nq.gz
    ├── 31c6243e897b5287c2231f685b69d4975e5d9dac.nq.gz
    ├── 31d311c89071a699c5e03d4a3bed5782a99d353b.nq.gz
    ├── 3283723df87104bcfcd0790d9975be0c02c07f33.nq.gz
    ├── 32eacc69880fa6a368bc3581a64401da82fff499.nq.gz
    ├── 338221d631d7f212bb87837202b775f5adf7e7b1.nq.gz
    ├── 33c9b7a56b2c1d5f49c447cd63d53d83ad7c2db7.nq.gz
    ├── 33fbd208ce94e648f206ea66c4ae3cbfd3d0cab9.nq.gz
    ├── 341583d04a5d62dfa18d3fcb55cd66988fd184bb.nq.gz
    ├── 34b6ea4edce854a59e7221e62e925b6397caa48a.nq.gz
    ├── 3619db1d97f527a22c382ed3a7a1d1a6303adfa9.nq.gz
    ├── 3662b3700e22ee7aadcc181f09f9f5bb070ab5c2.nq.gz
    ├── 366c8192da25186afbe98778fc2b30ab94eed46e.nq.gz
    ├── 377289db740df368ef97f91b56b2c8ec7b313761.nq.gz
    ├── 37bcf7c9e5149610a983f12e2906cd1232623f3e.nq.gz
    ├── 37f29faea68d7c549f6c0b75965aa7c473e98aa2.nq.gz
    ├── 391004b905f50a2d76d983054ae8ea97621008f0.nq.gz
    ├── 396435c7669a427746f20993e7a7cbaa2bdd2687.nq.gz
    ├── 39894f7a03ff3e4e7911b8b5f0fe31c19c1d9739.nq.gz
    ├── 3a474aa338fc7d3d7594817353c2e11e6c086f8d.nq.gz
    ├── 3a62a921dbfb893570c0f3a504b3611f0bbd48a6.nq.gz
    ├── 3ae1783170edd713b73a18316edc4d786b4d2174.nq.gz
    ├── 3b06cde39f5ae3e33812da54947d629a47b7303a.nq.gz
    ├── 3b15707de3d1e6f5f8c78764a7639610e103b7a2.nq.gz
    ├── 3ba12735c3a324ef3f3144836d304a3fac578987.nq.gz
    ├── 3bf468a8d6aa5ff23b8b30ced319c2273d2ae869.nq.gz
    ├── 3c4bd60dd43e1b5b1efb5e62f61d824400cf4548.nq.gz
    ├── 3db5c2ac36ef51b6e9f8e17f59a87654b990948c.nq.gz
    ├── 3e2934412956e9d302b8727b27537b763956055f.nq.gz
    ├── 3e71e3ca2d605592b88b1cd840130a1203c44845.nq.gz
    ├── 40add835a9f5de749f40503772c8fba1c52c8ea7.nq.gz
    ├── 41cfbf3ac095af61bf1e68694296a97f591fc221.nq.gz
    ├── 41cfc724d4fc848ec7d0b5b4c00d19770b46e1cf.nq.gz
    ├── 41e82a4ca37ef4a30b48001a680f7d80f8a3d548.nq.gz
    ├── 4229a66d5d5306cc539950c0034ad1957acbfd68.nq.gz
    ├── 42725e1db1f4d46827b3b55172e85d00e79e26a7.nq.gz
    ├── 4363fc421e95ec6c59e986d39d880fb869c390fe.nq.gz
    ├── 443372e8c52c0ce0127e0f6a003e9c6120cf2f5d.nq.gz
    ├── 445c18d19044fd90ec6776e2d973c76a26f4ac90.nq.gz
    ├── 4544a5c9fe037a8923c8bedd56f987ee7a767617.nq.gz
    ├── 45921e7b2cd48d438926a6fe8eeaaf2e624b7009.nq.gz
    ├── 45e2ce67a889a2334e87391a74f05bf5b26b4a61.nq.gz
    ├── 465c0019ca0ab67fdf2c758ce06b5dd4b4320f5a.nq.gz
    ├── 466b1f9a396f5d8d14472d17d287b6ea9b3744c9.nq.gz
    ├── 46f321f2f2561386bebb1406b5c1e29128f0adaf.nq.gz
    ├── 472dea686c8e77ba00a8247399c68470f0d2c989.nq.gz
    ├── 47ef7d6b827151e1f6d1a4e69ec34c6a0813c614.nq.gz
    ├── 48cbdeed6b711921926db72d1e76982392fd7117.nq.gz
    ├── 49327f707b6a72604ea33e9ee0cbc954024be5e9.nq.gz
    ├── 495c1cb7cce1648e77dc4945861ffe832ebb0aeb.nq.gz
    ├── 4970f32d02f4d540e8d08bc70e4bf076fba10ef0.nq.gz
    ├── 4a54daf9c689cfac8756e4c0428d7ace2afa4cf5.nq.gz
    ├── 4ad4d34b672268b01526b7978720c4d8afacd7fb.nq.gz
    ├── 4aef97a14a2a5234b5c16cb3872ce51067aab0ab.nq.gz
    ├── 4b13f906bbe5ac9f7f9081442bc7cb884f508469.nq.gz
    ├── 4b14d454bb73095a3d94d1f422e71c530e8af058.nq.gz
    ├── 4cb0c26c9e9b5ae85b28769649d81684562e2d14.nq.gz
    ├── 4dd9e809492993b97416d7371d777b432148b7a2.nq.gz
    ├── 4ddba9abdebdda3662497e7aa4906b1985e55749.nq.gz
    ├── 4deaee1f47502ed3161cbc8df059ceafea973cab.nq.gz
    ├── 4e2422f60330cc190c4cc76f202ca960a00fda60.nq.gz
    ├── 4e63cbd7b248f3b719b05ab1f819949528845448.nq.gz
    ├── 4ed86d3aa6c11ef1ae258c362a1777c6393b9ea6.nq.gz
    ├── 4ee50696b2365d0bd121e9748df23789dd6e3941.nq.gz
    ├── 4f5b23e692d731671e4d7058b800cfdff32b6cc6.nq.gz
    ├── 4f879beb454890dbe09541facbc1383e68d1ee39.nq.gz
    └── 500f041bd9bb7e3c3fa4cac89d365d5b21982940.nq.gz

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
*Parsed on 2026-03-18 by [repolex](https://repolex.ai)*
