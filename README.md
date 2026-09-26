# Repolex Knowledge Graph of repolex-ai/git-lex

RDF knowledge graph data for [repolex-ai/git-lex](https://github.com/repolex-ai/git-lex), parsed by [repolex](https://repolex.ai).

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
rlex download repolex-ai/git-lex
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   ├── 0e1ae4b9510d699f3b78c432f3877d8c65cde634
│   │   │   └── chunk-001.nq.gz
│   │   └── d79791e26e44dbd3667f05caa6a97fcd12b3d146
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   ├── 0e1ae4b9510d699f3b78c432f3877d8c65cde634.nq.gz
│   │   └── d79791e26e44dbd3667f05caa6a97fcd12b3d146.nq.gz
│   └── repolex
│       └── 0e1ae4b9510d699f3b78c432f3877d8c65cde634
│           └── chunk-001.nq.gz
└── blob
    ├── 00866109f4a4d69cef0aadccb46362bb98392c9a.nq.gz
    ├── 00a489a92ff98ee7bdee3f5baa3065d96db91873.nq.gz
    ├── 016e539fcd441436a19dedf86c0a972852cb8073.nq.gz
    ├── 0208815566ea09eb90fc6033ef749ff60c76f87b.nq.gz
    ├── 0222fc0587d2e8c3d0e8ce760b1cb2983902a951.nq.gz
    ├── 02803c64cf6cdf0a0e13e0961395bff075a747e0.nq.gz
    ├── 03d72533b2a07d1b742dbeb071066a097819b492.nq.gz
    ├── 04258ea1e1fb36cf569680162eacfdb7be6f262b.nq.gz
    ├── 0437cd015f1d0e6a5531bd3681dd45341f226154.nq.gz
    ├── 061b0a3adc577a194a31cda09184e3c88aae1cd9.nq.gz
    ├── 063050f0c43d4d4d72305620f2cca69e7a81e98f.nq.gz
    ├── 0687cc7a359e0a2939b269ea9038a794ac4ba6c4.nq.gz
    ├── 06df8e0c2d7ff6355b2604ea39dcc1dc5047e015.nq.gz
    ├── 08186e72b2495f468b924e88eab457c6d194b70a.nq.gz
    ├── 0a2693aeed7bd87588fb978dffe2790bea7ee664.nq.gz
    ├── 0b5a72b208a660088e3866f63be87fb891bc3bb5.nq.gz
    ├── 0c566eef09158f8233b0ed34c83b9fa956f5a2cf.nq.gz
    ├── 0ccef777026707116a8455e5375822655cfefa8c.nq.gz
    ├── 0d6362a5a03b2a92926cc5b46424bcea14294782.nq.gz
    ├── 0ed6bda2a3e20cb2d95eddab86a98267840c7655.nq.gz
    ├── 0f16ddd98afdcbcc8264a28a48c64bfd1bce7d65.nq.gz
    ├── 0f8d8605f983612ed2aceed7372f422207874f6c.nq.gz
    ├── 108b026030924f4827b3fff61f5d79b60d37e138.nq.gz
    ├── 12273867390dd8533640a3370c5573e5dcf0168a.nq.gz
    ├── 13f2e7c8371aacda848a95400b57b6086e1be904.nq.gz
    ├── 141baa6a14a58f7f90d009183237abcdcaf5b655.nq.gz
    ├── 15d5c08cec65f845cc20c5fd314eff9c26e873b8.nq.gz
    ├── 16f44baee2db1bcbd1291252793e343eed9c427a.nq.gz
    ├── 189f6f59ef2d67f9a55af31bf1f700d3b1e2ce2e.nq.gz
    ├── 19d1fac060149d2648301078d9c2de6737c9919b.nq.gz
    ├── 1af604637885a28ae0a260b203b9ae5c8e63681c.nq.gz
    ├── 1d570a74cc30adf48ab4e0266eed1fb3d77465c5.nq.gz
    ├── 1d8544629876d424b33fa0ffc21dc631bfbdbcaa.nq.gz
    ├── 1eb39e5dcda9c19c23487fe13f8a515d23be70fc.nq.gz
    ├── 208cf8803ce961ff0f7789b1dac0c01233ca3d8d.nq.gz
    ├── 2179caa759c3369ed209df50d96aa4915f6cc98a.nq.gz
    ├── 233f83bcd5ea370f5a0bea69f39794517099b7a2.nq.gz
    ├── 2427667e2df6aab7669cba0b4bd47200eec97fa3.nq.gz
    ├── 2611479fd8b1eaddbaf9719dbf6de749550848bb.nq.gz
    ├── 27cd58a2d22a36682afc8c09802e53df17d3d7f2.nq.gz
    ├── 2957bcfa1931f2453530b25e2416f5dd6adcd619.nq.gz
    ├── 29810af1e8e400e79d621c0faed721deb61658d5.nq.gz
    ├── 2b79623f0b6d564d92cf96fc63c9083256afa9b9.nq.gz
    ├── 2c06d646dbd289cae74366f292d8306acc1396a1.nq.gz
    ├── 310bfc9e56b69b99e0a71f7ca918ad703d138e9b.nq.gz
    ├── 342628f7dedf97a970680f5edeef818205c3bb9d.nq.gz
    ├── 34343f0bbfb7301810798dc930d12aa57b0bdcee.nq.gz
    ├── 349d858d6fb2ea82f5e29f7d79aa5d683fdab80d.nq.gz
    ├── 356f1f43b2569a829c0f28ca121b0824196640b8.nq.gz
    ├── 35ea1138df65b2248dd17301445feee2ce4a948a.nq.gz
    ├── 3695dce11b155555ba218776032651472ec34547.nq.gz
    ├── 3762d766823e1ddf44e7036c0ac6c4326749426d.nq.gz
    ├── 37c5a767daada44a37191fba60063934a79e2a10.nq.gz
    ├── 3852e06955db2f1dc572a78cbad8df6e7f9167cd.nq.gz
    ├── 3a42bbc6196ffa8ca171be531fe15cfd3c3d3a26.nq.gz
    ├── 3a5ea1e5bedea5cf8bbb7cb9b04b10c5ee9feebc.nq.gz
    ├── 3aa2bf469d37b8642eb71cb4eda00fda94d462ce.nq.gz
    ├── 3b66a85f640ab807e1f091a7481167c832bedc61.nq.gz
    ├── 3ca0303a9580f3ea0ca98903c1d748a73de98d3b.nq.gz
    ├── 3dbce0aa63212fe235b8cc9f7a40fca667f89c42.nq.gz
    ├── 3e2f207fbffd0864d30bfcc59eff4a9ee44bce99.nq.gz
    ├── 408f2a823cc34ca87b8e62377622f0469c3f10b4.nq.gz
    ├── 4106f11ed826a16a5558c8980c64d2177071cab8.nq.gz
    ├── 4134ebbb108469f688b4cdf7425da5f902d4604c.nq.gz
    ├── 41a84e828d595a160a731952009ed23271223a48.nq.gz
    ├── 41c3ba9cd82a615f67ef6b46fa899716f892e506.nq.gz
    ├── 42497b8b79b06e4daeb8a15501ba30dc623d9650.nq.gz
    ├── 4298d701082eea670484b52274859f9b5519b946.nq.gz
    ├── 42ae741a98f0e57d0f6b4e41156e86ecdda11b50.nq.gz
    ├── 42f3c3b67df8d2e1130afb33ef968044fc6e591f.nq.gz
    ├── 43809ad8edb56e6dabf654b27bd04b92a24d67d8.nq.gz
    ├── 459d879f5f79270d530f320327ed8e8317952fbf.nq.gz
    ├── 4667e3e2ae98b0911c619f29edd45ccaf3ca2d74.nq.gz
    ├── 48c993b7cf9891f7bb51099215cd25473f6eaab3.nq.gz
    ├── 4a3024dc24c78fe33b208ce3a60d6dfcafde8e4e.nq.gz
    ├── 4b37888eb345a49bd7ce8c3c27dae5f2aa4ca547.nq.gz
    ├── 4c55630dd72cf4917fbe4900633480bdde379e1b.nq.gz
    ├── 50d833e95d8ec711cb09d760e9d8ffe649a3b41f.nq.gz
    ├── 5251d269cc6fd76fa87a8078580d1c11fad3d73c.nq.gz
    ├── 52ed591a79e450573a8c5eeb813f645b4053cccd.nq.gz
    ├── 53e49049c0781d0622f8d69dad74f9c3c985cae5.nq.gz
    ├── 54066bfc37b7febbab134e0f001fb4ddf4203151.nq.gz
    ├── 549dc5b5ef368fdcd96216be65b9ab15b798092b.nq.gz
    ├── 55d5d494079053bb0763cfbbf7468927a68447a2.nq.gz
    ├── 57af24d66c6d49fcaeac86958d3045c98b757cf0.nq.gz
    ├── 599e187c9b8953366d0b216c8fe429c30f06a4c4.nq.gz
    ├── 59f01bcf241bcb5c273d255a8630ce17eff10736.nq.gz
    ├── 59fc944c9eef1328a545b0274228a6d234fd5a57.nq.gz
    ├── 5da94781de7ed2228f03dff09145a028563747d8.nq.gz
    ├── 5e03f7426c78904c9581bb0131801103170e19cd.nq.gz
    ├── 602437d774fe680aa74cb5ef4a983297e20548a8.nq.gz
    ├── 62d9aa065e0ec4684972edc08120749a13cec44d.nq.gz
    ├── 6407059f5293930d53fdd3b57f5ecd931d2542b3.nq.gz
    ├── 656c6a5c542d7b9138d8ccb8d5c6a0545a59bb53.nq.gz
    ├── 65d4fc564b4b3cfa81824ff9d92cf23eceea7082.nq.gz
    ├── 65ebfefdb33641cfa36b9ffa2ac7567967ec3165.nq.gz
    ├── 6622c199f0d3b6de3790cb0d50d5c1e7e82525a2.nq.gz
    ├── 665ba83b418604c9fb3545f97c95044c67534c92.nq.gz
    ├── 6754c8979c41db98eea5a83efdf937ae069b9af4.nq.gz
    ├── 6765781f13413763187bfd26df5d1c06318b715d.nq.gz
    ├── 68e15bdafad48f7b552f1366c543dd8804518a42.nq.gz
    ├── 6908cfc6b4d28c029e17fcf2232f7b627462cdcc.nq.gz
    ├── 694225406625ada113f955fe90df1de791c08b80.nq.gz
    ├── 6cf50bfd9ec12b5945ccafc16126357b18be3977.nq.gz
    ├── 6d1978d9d40b3d89832b149b7d6a67c3da6f56d4.nq.gz
    ├── 6f2c440c91b0047a87a19a69c642b9934419bdf1.nq.gz
    ├── 6f2db13ff7a727baf81e884f220492e4fef988ff.nq.gz
    ├── 701750f08b391632181f0a48aa1af3bedb96b322.nq.gz
    ├── 72430bdb952dd68b13e1f2ce62198bc7ca40a1f5.nq.gz
    ├── 7414e2e40670938206048f446cb3024cdaacbf9c.nq.gz
    ├── 75ac0fc3ebf93ceca1dbcc1d9509f8deb4c3affe.nq.gz
    ├── 76538457532237d7d53b30004d7ab6d523f030d6.nq.gz
    ├── 765703fa44c1d5ebaaa6e8e37024d88be7d27140.nq.gz
    ├── 7744180da490c80bd59286ac3e58dfc04399472f.nq.gz
    ├── 7913c88b29555f77c8882576137fa33712d76c3c.nq.gz
    ├── 7976c3ac59f170caeadd1bf24394625943f3901c.nq.gz
    ├── 7a5fd7de82cd4146f10dd2e3d5ea0571622207aa.nq.gz
    ├── 7ca63c9cba25ef1dbbd90eabab9b50848c9d85e8.nq.gz
    ├── 7ed7149ad409a785ab439bce42c26a9bf62a7b86.nq.gz
    ├── 7f0584eed98c0bf6d7e22fb8b3c4b84a860204f8.nq.gz
    ├── 7fc5f27289ac486f896c801bc2730e6110b48cb3.nq.gz
    ├── 84693e38995db3078ed089061f70f7e704f47064.nq.gz
    ├── 8475d96ffaa2dee1c2e143e0697ee1a6a35700e5.nq.gz
    ├── 8714597f0fa9955ecd302247e67d50054de34b76.nq.gz
    ├── 87e1197dc4705af35ccfffe3e0021dd70b096759.nq.gz
    ├── 8866d3daca8fc8078977b6e117a5bb5250ab3055.nq.gz
    ├── 8886ff9bc0500b232fb569437c2baaa6929ee128.nq.gz
    ├── 8935576b3142595833d6e7976a22c089a35006ec.nq.gz
    ├── 89619a07cf8cbee4f456ce5f0593475381975cc9.nq.gz
    ├── 8a7471e0f8bd679880fa5697a44f39ebbf2bfa93.nq.gz
    ├── 8b47c62cbf6fbdad4165182c029983ee9b62d1b0.nq.gz
    ├── 8b52642d2bf5c809950a751b838db4c396553fe1.nq.gz
    ├── 8b608a9c8c55f7e2c6735e2ab76e55a829f86eb1.nq.gz
    ├── 8b674f173bd0c476fad98b28d19e9f46360f8837.nq.gz
    ├── 8e44d4072fd44c60a1b4eec52383820509abb4d5.nq.gz
    ├── 8e881720d66a0e648e59c9d60bac64c34ee90b99.nq.gz
    ├── 8ec19e5af5296db66e5b19c8870cecdd18080417.nq.gz
    ├── 91f8f39f6c68f3a64db51df37ae43d92cc914509.nq.gz
    ├── 928988c8de8077dc17b2bc4f4ac73041b5cf5ef2.nq.gz
    ├── 95640c2cb6f6fae7a8b507b7c8a40a536033308d.nq.gz
    ├── 96150f40508af0683cccc92accaad81e7d0b3837.nq.gz
    ├── 9700b1ee50855032df505678910b58bae4a06365.nq.gz
    ├── 9732e9922fc2140a71d3c7885008f10b29f8ad27.nq.gz
    ├── 983d0f43846dc7c825415ebab990e49f5b3c0293.nq.gz
    ├── 992fb719b25a4b0673996a13ba1c75a1cc295019.nq.gz
    ├── 996c85eff8113153563fcd6234e95ee5712566c6.nq.gz
    ├── 9c2fb2d23c2fcb53b98174a96ebc160dcb73e51f.nq.gz
    ├── 9c5e5048e6e609191cc4999601fce8d2c2608ced.nq.gz
    ├── 9c9298b98341cf61d319617fb561f21390b36ca7.nq.gz
    ├── 9dca5b4379570ba1665b6f0fdec93f9cf2f377ec.nq.gz
    ├── a19d0e58bd86f83e35fc0d51bf69ee4c1bf0c68b.nq.gz
    ├── a26ee1abccd3bb2852fc6be9407f058d44cf7d20.nq.gz
    ├── a33460282f28ba51b2a9a764e0da2fd0ac73a7e7.nq.gz
    ├── a4dff2e6f102b06ffbb09f9f7a93dfcacf4074d5.nq.gz
    ├── a5398612561d652e02d832e33c3de52ac5d15c57.nq.gz
    ├── a7002fb0b255b47091f1a3e7ae371267a3577efc.nq.gz
    ├── a8b5b3f492dd2d7d946737710348e880c76644d4.nq.gz
    ├── a90ca2279498ffe233156759ac65166c9f56eb35.nq.gz
    ├── aa8693554254733b25645294a596ecdff6d4a562.nq.gz
    ├── ac64730fdb24d149efd526188e79fc51c17f5086.nq.gz
    ├── afb5a81c9187edd67a54f176db10bdbe1d632324.nq.gz
    ├── b259f3506b1e55f9cf0233fe3b0e04c88954911e.nq.gz
    ├── b2e32cbf98a4d4c86b388b8239e0037ec5eaeb7c.nq.gz
    ├── b375fea38484c49c9fa5d8b3927f942665aa2911.nq.gz
    ├── b383ace58892c887c2ba0a2f3c3aac4562e9634e.nq.gz
    ├── b8ad8c71305d319695a90432e7b737af7ef9861e.nq.gz
    ├── b9af6705f2ce6cb289723646659dba43f29a5e4a.nq.gz
    ├── ba3f0ae5bcb3a8eba0c1fcded426061f7c0ca67d.nq.gz
    ├── bb4b270128ea32f5b26f476362cc234fe7218e39.nq.gz
    ├── bde16bc60ba280dae4718aceb3d653f64d61f6d4.nq.gz
    ├── be6d8f3bb80d9f5e2010c5a6154273811902161e.nq.gz
    ├── bf22612aa8a64e7c9c04d141563f7d4984ccb0c2.nq.gz
    ├── c08c774251ea5b6d1acf061f9c315321a39fd07b.nq.gz
    ├── c253f47e750e95612761bcf664cb4c6c73c9c7e5.nq.gz
    ├── c37237640c26b6516f9c7290ec864e7ec24ab294.nq.gz
    ├── c57836e0d0684fda4ea5c06aab918dd15f70127b.nq.gz
    ├── c6fb6917bf78967c827cad5d23b329edfd398d0c.nq.gz
    ├── c70d20f3676196c567ed4f3b9fef94c8f5fc312e.nq.gz
    ├── c83a96165cfab128fac908c0411701472d6cd2d5.nq.gz
    ├── c900d7f70392ca3d02d09b2a29985edd9ed2ae82.nq.gz
    ├── c92634d9e960661088456b8e44f2ea3fc852bbaf.nq.gz
    ├── c9af5dea3f7f2484fc7bb1ddc6175d66081de17d.nq.gz
    ├── ca1ed9fac60a9ee5d6b615e599e006acef1061b7.nq.gz
    ├── cb0b9e0f2217191de4604c26b56f6fb7440aeaf5.nq.gz
    ├── cbff8c3bbaf6313af2c09cf7958176a798a3349c.nq.gz
    ├── ce98b7a6040f2bc4cdd430b1f263bcf5e34a3751.nq.gz
    ├── d2ac7bce05d763704d16e6f5900b3355acc67c88.nq.gz
    ├── d38d39445b8308e26eae92cbbe2479b12a7ac7bc.nq.gz
    ├── d40983ee07ffc01b59c606ceb0d4534b967fe28f.nq.gz
    ├── d43cdba073ea0fec04ca450e999f10da9a999db0.nq.gz
    ├── d56a0a6e40278d17fc54b89ca159b74ad8a9a0fb.nq.gz
    ├── d56dbe40cff2583b0711e2c4b9cfb6e5b3b4b605.nq.gz
    ├── d5b6305f36465f9f0321c0a0a4042087e2a885a9.nq.gz
    ├── d6e26ad3ec8ddebc798176e637ee8629e057390d.nq.gz
    └── d7066e4b257d42384f8d190322a6bdba1bb47171.nq.gz

9 directories, 200 files
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

[repolex-ai/git-lex](https://github.com/repolex-ai/git-lex)

---
*Parsed on 2026-09-26 by [repolex](https://repolex.ai)*
