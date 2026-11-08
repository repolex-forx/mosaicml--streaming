# Repolex Knowledge Graph of mosaicml/streaming

RDF knowledge graph data for [mosaicml/streaming](https://github.com/mosaicml/streaming), parsed by [repolex](https://repolex.ai).

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
rlex download mosaicml/streaming
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 1381ca1213fc95b6573efb44e5ec9f85c765ce1c
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 1381ca1213fc95b6573efb44e5ec9f85c765ce1c
│           └── chunk-001.nq.gz
└── blob
    ├── 01522761b9483aff378c1eb004ead398331f7898.nq.gz
    ├── 019b1d1233e1671ed9d86e585d9e598e9e31ba4c.nq.gz
    ├── 02678df7823e30da9f86200537a9a4299e87ef19.nq.gz
    ├── 027f461f2369af67f4803c1bb41899466dd3a815.nq.gz
    ├── 029ddae090bc641162114cf87b28773783deb71a.nq.gz
    ├── 02d551d975c88f9ee8b297f7cb91ab07ebf0e826.nq.gz
    ├── 02ddfcd95ad11af398456d944edad1d3e36f6d04.nq.gz
    ├── 033af1c8de74d604226b365c116d7b1deea151af.nq.gz
    ├── 0549aa865e7e214a85b8eddc485d3c1466c42a74.nq.gz
    ├── 0895a3def8a3b84f2ca0aa4d6ec14b14962be0bd.nq.gz
    ├── 095d87f3368db495a9f74c555f52ac4406b67f4b.nq.gz
    ├── 0bc6c0e2e020ba2e04837f3a993c003ef88f6445.nq.gz
    ├── 0bddc78338e250c93d0c8580e085c931df10077c.nq.gz
    ├── 0ddf3dcb5396bd21399d3ff035bfc3e780c10b86.nq.gz
    ├── 0eb6781ad808a0406be9a5ba7fae0bd5850d421e.nq.gz
    ├── 0ef377ab6eb325faf888e1658c35f072b6e09aae.nq.gz
    ├── 0f5b97bce5a8f7aaefeec39b0fc7eb6c71058d67.nq.gz
    ├── 106ba18156e7c2800b1f035826a5363392617c41.nq.gz
    ├── 10d362cb2c6c64da942270a65c4ab18eb2398043.nq.gz
    ├── 10ed3070af45b3315cf4edba61baf63058438837.nq.gz
    ├── 13c4b3d1242d49d09f228a64c85f5eb4e057ec91.nq.gz
    ├── 13cd1fd99af655accd7cd8c47718ec83302acc56.nq.gz
    ├── 15b21b9105e897837929a6288a6119e7ee1b1e57.nq.gz
    ├── 15c620792a1638ee344ea2ba445d7745332be8da.nq.gz
    ├── 1617124d095acf611a5f3f978681594552b7f5c0.nq.gz
    ├── 161844b4e9e91ed20d75ddb152d767d96f2e9ec1.nq.gz
    ├── 175f96efb620a29c9e7e789439a7d4625062faa4.nq.gz
    ├── 176dbf5eef4ebb047695c32d0e0b8203c4bb3dfc.nq.gz
    ├── 191b50af99077d16c3ed6c3ab625692435dee8c0.nq.gz
    ├── 199d01a85d2a2881ffd4b45262702a100694c28b.nq.gz
    ├── 19bdc9a2e1d2982c571289c536db068436fc7208.nq.gz
    ├── 1a2d45f16da8e4390b92c8a70ba07f3cc6ecdcb2.nq.gz
    ├── 1a4ad32917c6e1d532d39dbf342a9012e71e4dc1.nq.gz
    ├── 1a5da91f96f2ab55e83d89b44a9ea3bce9f4e840.nq.gz
    ├── 1bc18af0c16b293b11447592c23919128ef902de.nq.gz
    ├── 1bcd60841a2cb4872754223d9b4e9de169d1dba9.nq.gz
    ├── 1cd8b5d4da55657b6733d283d0a9324b1c1f7af4.nq.gz
    ├── 1d27c520ba20d709fdabdcd162a8a1735842eec3.nq.gz
    ├── 1ee645b902075ac762d2294bf127f05739b1f9a7.nq.gz
    ├── 1f4f12d53c8964427315851046860ac21265d83a.nq.gz
    ├── 20af6533a3f7eee98b779cb31b482627af3982b0.nq.gz
    ├── 216abc0e017938663eef307036c05b2f698b14d9.nq.gz
    ├── 21f57521b5fb89641b1e0bd74f37e1c8184a159a.nq.gz
    ├── 221491f721c3a77d7bc602af8dfb037d6e65ade9.nq.gz
    ├── 2293e942666696d218ce6d1194b4c5d6a75d8c61.nq.gz
    ├── 229b36b69576ed7a76a1f8a1ba5f12f661e4c513.nq.gz
    ├── 242a5ef9ee3c8bd760e0d5c1532d2834d77c363f.nq.gz
    ├── 2465c1e5d87aa829d440a77c54e5015cced9d0ca.nq.gz
    ├── 247c91ffe15a7a96506c37e4e3ae1e151cda7177.nq.gz
    ├── 252d21af689cef00770e93681fdb4c10a146425f.nq.gz
    ├── 257a69d2a8da4656e7230fb19bf4d76bfa438011.nq.gz
    ├── 25ab476505b5a0a1e122258195f0e205290d719e.nq.gz
    ├── 261eeb9e9f8b2b4b0d119366dda99c6fd7d35c64.nq.gz
    ├── 2642332942951aa0a6471e665cc0617b84c70dd7.nq.gz
    ├── 264569a2e58a4d2b0e1c6185eb02e299cf74b7e3.nq.gz
    ├── 265ea7d24319325ea6a2958fa2c088cdaac85686.nq.gz
    ├── 27402344a431458e559688fdeb16ab1fa09e0ab2.nq.gz
    ├── 287ddb0798efa4040f581e94c88619c443818659.nq.gz
    ├── 2b22f244c785c80756fb26f3dd55661147942f9f.nq.gz
    ├── 2b290595e29ffafe7c24553a5ba68d5393517c66.nq.gz
    ├── 2b60b79cee013094a5bb059906067b947e6526ac.nq.gz
    ├── 2e6cc9945a46f35dd4c45e924934355b306f95a1.nq.gz
    ├── 2e98391384c1e22ba849d8eb889fb3b178577a5d.nq.gz
    ├── 30b5c4eb326920ff727f71008915fa385f145712.nq.gz
    ├── 310f3c180c4451566ec9a55c745b9a44c3ef61c1.nq.gz
    ├── 31b2f5c884ec1a02c4ebdf0fd0090496146b6208.nq.gz
    ├── 334b47b7b22f025475b0036427d8503922c65651.nq.gz
    ├── 3355bbaf03fdd1fef547b23bd4ca497e98b9ba1c.nq.gz
    ├── 339fcea5445de06dc1bf61d3f66c505e4fe7bb7a.nq.gz
    ├── 3402cc8defac74b53e1f82128cadbd70190d53e7.nq.gz
    ├── 34a471e10aa19ca1f2b9018577dae1718b18063a.nq.gz
    ├── 35005ad2aaced3d1c29d70ef02d9833af0f64620.nq.gz
    ├── 361b1d71e9ce05cdb2bb049c689dec4387b0d92d.nq.gz
    ├── 38c0ed4f9e572f7d7161c9db18913cffb5fb7467.nq.gz
    ├── 391d34f95b5038a55a947cc9caa2f8499f3b2c4d.nq.gz
    ├── 3b464fd92504058cae17a15f07e1ac900a11a763.nq.gz
    ├── 3c8efb395a813cbe806ef447c885a54ef484402e.nq.gz
    ├── 3ffb8b1ea73383d7d19b1d28b2335dd711cbf9dc.nq.gz
    ├── 41a2a74a1a2c56e60d42041b1835a216b5420aae.nq.gz
    ├── 422727a2aa79323ab5d309769fedda0cba36f250.nq.gz
    ├── 42cfaa1f6f173b79164fd8befaabdd6874e16644.nq.gz
    ├── 43da9246960fc8227ce87700a393a4a0cd230926.nq.gz
    ├── 447b8bdbedead866c068b2e4a6c84e4f8c65d990.nq.gz
    ├── 44b723b5bfca550d27b9522bd8e35181187686d8.nq.gz
    ├── 461e7fc59c0ba8fbdad4e00b62a332573196a30c.nq.gz
    ├── 46bac76fbc5548fbafbe5a6e651a28397735467f.nq.gz
    ├── 470f8a37ca6be60fbfa458e0be72f317d934ca49.nq.gz
    ├── 4aea1bc3859734c48073af3d40335df0e6ab6f49.nq.gz
    ├── 4ccf12bc48217eb29dd1bf7336b2c403739dee76.nq.gz
    ├── 4ce4f019c3525221b117dc0b7b858cd343b515ce.nq.gz
    ├── 4e8e1ad7f05af496e0b438580541da1917bc8f6e.nq.gz
    ├── 5017d98c922a548a32e235a6f029f226672cf134.nq.gz
    ├── 50b2dbf60cf7151e56f69f107439389695004a52.nq.gz
    ├── 517492a608b283314c4af81e8eb63acb5403eda4.nq.gz
    ├── 51c3ea16bc2442e9e39b8a5208db09245fbe5efa.nq.gz
    ├── 51c7d3471d996d95ca0de652c3713fab303ab12e.nq.gz
    ├── 52e9401673b2d0f2ff8575561cfa3d3839cba900.nq.gz
    ├── 53166bbe756ae3ef864b453bca0fc9a133895a6d.nq.gz
    ├── 536b7d352df5df9cb8131351645516982f7fd702.nq.gz
    ├── 54e63c51c03bba654475965354ff4638f9172632.nq.gz
    ├── 5504160c1792fb4985ba68c4d7b3d05934d6e0eb.nq.gz
    ├── 556fca65482f1bab2bee2c140d0b2118f14fe208.nq.gz
    ├── 558b30f12c12292c4be0ecd2c63dbff904a83919.nq.gz
    ├── 55ebccea4505e3edd0f0e1ff6ea75364e7c7328b.nq.gz
    ├── 56148a175b058a0d24a6dde0b9da5374b734a049.nq.gz
    ├── 57125d28e56522bab29fafe23ac3ee3280dc2b7a.nq.gz
    ├── 57f678948a727039b2032010f9cf40a2983b109e.nq.gz
    ├── 58b2140785803701751cb45194f59642942820cf.nq.gz
    ├── 58eda5148a43ed03b879d6b553345882b0eaf715.nq.gz
    ├── 5a6ed73eda00e75fd6b926487a3ab55b4d0e852c.nq.gz
    ├── 5ca94e8ae198fc7c5ddea4082e998a085ffb84bb.nq.gz
    ├── 5d1da14830d3296ef1a117447e686f80ce24c364.nq.gz
    ├── 5d3711d0662cf6026ce82f77c2712b73d1711b23.nq.gz
    ├── 5dc62ac93bd8a8a9b943aef0871e3094f31008b3.nq.gz
    ├── 5dce1c91c4a4723a40aea0903b093b5451ebf021.nq.gz
    ├── 5dd055989b19dd13d8d985a440901ab0c261e0bd.nq.gz
    ├── 5e93a17a702c40f8192a8ec40c816641a2810f46.nq.gz
    ├── 600bebd90635710c1d06ab79e6adba73c27711d6.nq.gz
    ├── 60b0fc7671e5dd006f731daafb65ad204ef78ecc.nq.gz
    ├── 60beb52aa2b6beb35ffcceefd7104ff455a5a528.nq.gz
    ├── 61d9447a2f758d14994862dabd3df713e08bc663.nq.gz
    ├── 62c019ad93fa9c13475c73af18df161efbf339bd.nq.gz
    ├── 62d927c9498a97bca3c2a2e6ae410bb281328db6.nq.gz
    ├── 63e1e8d9aaec480b5e7ae34687d08d7764325b25.nq.gz
    ├── 64c3a70e5096cad3b6139b9384e31986a0aa70b3.nq.gz
    ├── 65271d8e24c98407f11ccf2ccf06eabf0743dd9b.nq.gz
    ├── 66c0e00d40b03acaebd4f2a0b37dc1d292920245.nq.gz
    ├── 670fffa8aadce9f1a1737258b01f4655cd4c0b58.nq.gz
    ├── 694b8ee3670cf82345cc3a12bbc10ff07bc7c802.nq.gz
    ├── 6a4bb87c8b8aef1574cc10fef7f9058ea276dae4.nq.gz
    ├── 6b062df53130a92631fde0a664c1418348e9e2fe.nq.gz
    ├── 6ba6ac1296e4639e344c1fb48e0dc5a6f2bf6066.nq.gz
    ├── 6baa0a48cd86245f7080732fc67a2ee7780b67f8.nq.gz
    ├── 6c52f6272c6c9ad94b6d26e0c9422f0120437948.nq.gz
    ├── 6c5873d7f84c12e7b0f0f41b8018f25354db151f.nq.gz
    ├── 6e437613af21180012c82832d4a68652d3130ecc.nq.gz
    ├── 70c44c04783143c79e12af8da9ef8a70ed04eb4d.nq.gz
    ├── 72e05d6bc74ebe530ae74c73194debc2e209cd21.nq.gz
    ├── 738a379e1917f82e46e0cd6c68882840c9e3f913.nq.gz
    ├── 753318e6f3716e6a106c9d69f8c18f7fddc0005c.nq.gz
    ├── 79b79e8f497b07bb5adc9b380bbae6766c545814.nq.gz
    ├── 7a5c678da462284720f7773040fad144c94b72fb.nq.gz
    ├── 7af27923284df689648f3cde878e94ab70acb5eb.nq.gz
    ├── 7bd680e2a874c8f3fc3b07a23d0afa5c0bb0cef3.nq.gz
    ├── 7be3e632a1b234acf25d09744b94b04b50023492.nq.gz
    ├── 7bf04983b3fd2ac7c1871b0cd376dc36867003a7.nq.gz
    ├── 7d30b8b780d1e5b17d8babad20ce72d2e2a29986.nq.gz
    ├── 7d960a73c7fa01ed9bd02b12329f45cca251f44a.nq.gz
    ├── 7d9cbef47dcd10ecbdc0dbdfd4559ece242fae86.nq.gz
    ├── 7e8a11631f05df3e3c65e91229fb3934cefbc222.nq.gz
    ├── 802686bd448582d043d92f163ee4c74527910f5e.nq.gz
    ├── 8166ae609e6b74ecaf74f745e8b9d2402192488f.nq.gz
    ├── 8179e419b5c581cfbaf2e5554fb419484caf2df4.nq.gz
    ├── 8274a1b1861bdb11bf49236c9b9532443df7c670.nq.gz
    ├── 83e9f5943277b2b2917a98f631d69a1b568b8f1c.nq.gz
    ├── 84a08ef7b36cd8940ccf811f2db7614bb58e83d5.nq.gz
    ├── 85b08ed47b31a33d94999d779556df5386279ddd.nq.gz
    ├── 85e1b4163439527b9e93d21db051534a18db2414.nq.gz
    ├── 85e9fb62f42db60f9ade2a184e66aaa9cfad0b4c.nq.gz
    ├── 87fb68c0a886fcd33df62c50a22e5b99cea27cfb.nq.gz
    ├── 882261e8567ca9fdc2ffdaaeddc69534c1111dbd.nq.gz
    ├── 8a9fd8d51905da16855ea43a27f74cf1c6516f9b.nq.gz
    ├── 8aeb04fd7a087db5434e5c07a6c47c9469032d2a.nq.gz
    ├── 8b63ce358f342f7a33073574f986bceb9f2ab15e.nq.gz
    ├── 8c9430d8bf2fb37294a96fa0a41b07745a44f1f3.nq.gz
    ├── 8f81103c9158f39eedc1a39cc0f811c0db836102.nq.gz
    ├── 90bc137424d7126da28ce74798e2d902ba28e9cb.nq.gz
    ├── 910895ecf422dd9c9a1e450afe591f11ef89c1bb.nq.gz
    ├── 914f0215e6967a6017fa742c052b2724423b4b18.nq.gz
    ├── 950f7759dd7b389513b00a7f699ce2e64486adc3.nq.gz
    ├── 952dc70bc6853a2d4d89abe0f070dd4f54e83a94.nq.gz
    ├── 96f08b7469d316dd1e181566e81dd79811a98469.nq.gz
    ├── 971e79cd2962f8168d75936167cba4808f790875.nq.gz
    ├── 97e98a8b39b986b98b1ee1b68caa87d8ae821cb4.nq.gz
    ├── 98ce965cc9f124e7bd62d25abea7b715ff1d3529.nq.gz
    ├── 9917e5e1abaf648cb191ef297084c1876cf6902c.nq.gz
    ├── 9a2b4573e3bde22a1bbc071e899d472a53a71988.nq.gz
    ├── 9c629b740e9efbbf6f89b410698e6837b69cfc8d.nq.gz
    ├── 9c6baeb59aa7aa55cc35c01804e46d93dfe1d486.nq.gz
    ├── 9cd1b12ea3ef8234ce6ae44f63c868ff48bfcf94.nq.gz
    ├── 9decae99dba2bdae9b7b1adb1d9561f0d693481f.nq.gz
    ├── 9e75be0e43aea614a3910a1d8ba433260416b097.nq.gz
    ├── 9fe5ad930a21e279115a8c28a01eb1f43b07043f.nq.gz
    ├── a00eb1e7d82468c8c23f09dbce3317427c53a3a7.nq.gz
    ├── a0bca503d1238d352e4d684c85eb5b748ea3bc0d.nq.gz
    ├── a191e7ff3bd8a4776917278f7f9995da38fc818a.nq.gz
    ├── a451f66a710fc2dc4451e1428b56359a6ad421a0.nq.gz
    ├── a5b168569449097ae471521d3ef1e3ec3367cc55.nq.gz
    ├── a7094fe3b6c58c0df6b677d4fa96fd55a9a835fe.nq.gz
    ├── a79e98f2dd20f97acac580943d7a636190edaaad.nq.gz
    ├── a7a3bc7e51024b010dbe42b3c2ca69905e0a93e0.nq.gz
    ├── abfe45211bcee91ab1fc99486dc2c8594325ade3.nq.gz
    ├── ad3d7e64155ce89b1c50716a86ee45d1dfbb1458.nq.gz
    ├── ad8e01a74fd8c89523696f8681ec8e609c8ea5d7.nq.gz
    ├── ade261f2a1b59e2308ba6dfc8f52cb8b660d04e7.nq.gz
    ├── aec242818e11ec9491a4be7eb9cabcd124dffa0b.nq.gz
    ├── aeedd5ea06a179a8c97821201bd0326e55792e85.nq.gz
    └── afa1f9fb08ee2c3cfc46a228846e0e3b78561947.nq.gz

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
| `audit/` | Code architecture and graph audit reports per commit. |

## Source repository

[mosaicml/streaming](https://github.com/mosaicml/streaming)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
