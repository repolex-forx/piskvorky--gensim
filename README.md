# Repolex Knowledge Graph of piskvorky/gensim

RDF knowledge graph data for [piskvorky/gensim](https://github.com/piskvorky/gensim), parsed by [repolex](https://repolex.ai).

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
rlex download piskvorky/gensim
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 37f90ec121eb7cd401448a947e80953e0c53ccdc
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 37f90ec121eb7cd401448a947e80953e0c53ccdc
│           └── chunk-001.nq.gz
└── blob
    ├── 006917b6006a590adc50e16783c10b1804fd2ab5.nq.gz
    ├── 0173311997602681d1cf3a7ae38b12460671be06.nq.gz
    ├── 0254b29f18a5bce7078ad4d0656107b2d23d37c8.nq.gz
    ├── 02f17568f75a969ec52946a84fb0ca11d82d580d.nq.gz
    ├── 03b212c4c2da95c739ed27c0ccccdf3bf9ba375b.nq.gz
    ├── 0503d21f6928f0faa1d212f34904cf5542f7dc38.nq.gz
    ├── 059dfe0d5b0e23e0589575170bc4774945d82c87.nq.gz
    ├── 05ed4488931ed5952ca1cac61367cf1ad72fa1da.nq.gz
    ├── 064b9ad1e9c9704d9e1204a4c4691f8561a400bd.nq.gz
    ├── 079608c5cabf7676cfcea9b88355e8410307e259.nq.gz
    ├── 088163624dcdcbb29dfd24e8d50c388a15a13456.nq.gz
    ├── 088b345b54f5c4a3113c1ab89fed0a75a2d7e7fc.nq.gz
    ├── 0978adc0ed1cb9104c384f1913a491b4e204cfea.nq.gz
    ├── 09818d48ba8c5f9844143a1322c2520e84d7f769.nq.gz
    ├── 0aada925b87468d0dc2e237e8bca284cc94cf3cd.nq.gz
    ├── 0ab71d7206859de4208d6d1efc812b9021bb4287.nq.gz
    ├── 0adbc82d4ee8aee227c0d672b67aa978c9495817.nq.gz
    ├── 0b5600885173a7cd793a516614a941151ad9eac3.nq.gz
    ├── 0b9832dedf3efd3455081b4e7ae972c7f7980d95.nq.gz
    ├── 0bc216a7aa6e3636b044fd895b8a3cb36f112da0.nq.gz
    ├── 0d69524eda7bd4f6a9171205aad2b72f7e1a42b1.nq.gz
    ├── 0dd06ef5003ca88669dc357f7f93fa1f0286bb21.nq.gz
    ├── 0de846d454c925c94dc037e04232dcdc50794ec9.nq.gz
    ├── 0e2b28057807bcb3ed2900ae5ff608c3202c8534.nq.gz
    ├── 106cbd44377e5d6ae330c6d4bba46739189743f3.nq.gz
    ├── 11011ed1f2ea13044844bbf0557b23e5ce7045aa.nq.gz
    ├── 1120c5762ba50434db0e3ed94c47caf4ad660cc0.nq.gz
    ├── 11dcb87833465d7361c4c9696ac9482a240d52d9.nq.gz
    ├── 11f3d795c39ffa750378f4736b5c203fdd1210ba.nq.gz
    ├── 11f49538be25484d51dedeaa618936cb6c1a1f4a.nq.gz
    ├── 1335992cf6051eab69e2aef62459e9a1fd5d76b6.nq.gz
    ├── 136253e5f5f25bf4325fcdc94b71c1a70fd09eee.nq.gz
    ├── 13892b5604abeea6cea42cbed88c7797ca060d28.nq.gz
    ├── 13c3cf876ece39d982e7be0be623fac1cef6a016.nq.gz
    ├── 13ec7fa9ae33f960ffcbef708106fd3c0781d2ec.nq.gz
    ├── 13f779c2c217630055a1abd880d570d07c28d2a4.nq.gz
    ├── 1401815bb8188f5451a25e9a55228213e0996f5d.nq.gz
    ├── 14304c72f2ab90b87fd051fea94c2584794e0a13.nq.gz
    ├── 147e78bd7aa41ea28d14c6adbf68fa99cb3a4d1a.nq.gz
    ├── 14eea34f887c1217b01d793d325e9ef25389558f.nq.gz
    ├── 14ffb68199da3d65e3d3b0e3313c856abb04c3c4.nq.gz
    ├── 1512b59b5c84ed8730f5aa2e0806095b991a07dc.nq.gz
    ├── 156ea36581ed75541589f50c0a37a96ee216a461.nq.gz
    ├── 15c1b867fddaf98e7b9db8d7b9a98ac22ea300e9.nq.gz
    ├── 16edc070c8875d0363de7502a901c2d4551d1528.nq.gz
    ├── 1734ea99d76b5e8f75478c426783d2e0a7c50764.nq.gz
    ├── 1791d4117561e8a4fccd8fedf57d537ecd0cb555.nq.gz
    ├── 18e9934299e420ad2849d25c2f66287ea535cb82.nq.gz
    ├── 18f4ee7b1611a9ba38d9f8bc8bad3e4da95e3306.nq.gz
    ├── 1971e44b14889570af360270f96a8f047331e0b4.nq.gz
    ├── 19f1328ef4d77f19260d074ee55d99ee94352fee.nq.gz
    ├── 1a0b73f44b0de9aad7de99f8ffa81de5b73dcf1e.nq.gz
    ├── 1a3a9ab789c1ebf7b2ceaca588466f693dea1002.nq.gz
    ├── 1be01245764250f466921c1a5a2ccecc1d3145f3.nq.gz
    ├── 1be3e19b04597db39ff779f3d4ac6c72e7b74473.nq.gz
    ├── 1bf6ac707d03b8d7a43961c8485ec969e2169b8e.nq.gz
    ├── 1c1846c8e56544eca6c61031aa6e657faecd2dfb.nq.gz
    ├── 1c54d1482d2b683ac9055cc9e4daedd982d4632d.nq.gz
    ├── 1c91685d28064e0a2fe9eeafe11b8c15ea43533b.nq.gz
    ├── 1c9e13f527c2982d6fced18b82d08fa30b7f1567.nq.gz
    ├── 1cb34ec17e499f07578cd5042d2a9d608d0ccb99.nq.gz
    ├── 1cc2ffb55be637706c08d31b76bac3a024989b47.nq.gz
    ├── 1dfba0d0e85dc24284b6b76e24e4084cde6bb252.nq.gz
    ├── 1e7a89b847a68e7a6c8d0313574a686510ef4c40.nq.gz
    ├── 212df08fb0f61335eb1eec6c973b661f27bae08e.nq.gz
    ├── 2297e57b28c9dc849dfd72901ab4e751178aeca2.nq.gz
    ├── 233f8e605efca4bef384a7c603d53fdc385428bc.nq.gz
    ├── 236c1dce80179c71bf6a26daf30dc8ec6acbe0a5.nq.gz
    ├── 2419272e5b296efc937c64aee6090067885e5113.nq.gz
    ├── 246482421f0850f3f3544a7c107e01fdd13297ee.nq.gz
    ├── 24a0f59e8cb44c96d5ee4908dbaae2dd22611051.nq.gz
    ├── 24aafe2f8b3bff9a9a23729c6916bd44572fc4e1.nq.gz
    ├── 2614252723f470ebba0e2185c9c96181d2e60d89.nq.gz
    ├── 26392d68c486fd8594ee5cc5b2d3305b65a02b7e.nq.gz
    ├── 2639f20546a9bc911dcf91a629bfcf35d3c0a74e.nq.gz
    ├── 265afb3af93d4a269d3adba5f27fedef0c712790.nq.gz
    ├── 26ebfe67475cc460deb0877995adfbf9b268e10f.nq.gz
    ├── 26f535a9964bd2f14c25cad56f2f991bfa8f75e6.nq.gz
    ├── 278d39cf0b85e279be3315f1c613653681a0310f.nq.gz
    ├── 279a62cda2cb09e5888cc3db033b541dbba08384.nq.gz
    ├── 28564b1f6e0eccd125b888ad23d175b9e58c21be.nq.gz
    ├── 2873f6883c12879fa47601a87a0e2449a666d42a.nq.gz
    ├── 28c01ce1723d9e11483191bc7492320e06cda19f.nq.gz
    ├── 293633fddd184bfcbdde86488fb70d7cb8ed18af.nq.gz
    ├── 29463954c17ff83ed4a69fd9ee7d9ac76eac4714.nq.gz
    ├── 2952457732b173890ec8b52933d6d1d1a8e3ce24.nq.gz
    ├── 29882e4ab967f64f36c9775e972b872fe42f7b88.nq.gz
    ├── 29ab875a59f2bcb692f74730d8d61ba16d3a1a85.nq.gz
    ├── 29d65b3ad115d49f1fb800e24cefd9e9a07efad8.nq.gz
    ├── 2abd5179e09671de1ea9ef48a9dc3fc4bce9b465.nq.gz
    ├── 2aed4b58db4973c9433b03af0fbc6089b8006702.nq.gz
    ├── 2ba6b2dac90fcf39a18d368d0fb19d4d5f995859.nq.gz
    ├── 2c5906d4b766c097b57c147b2ebb1648e7d2557d.nq.gz
    ├── 2c7267803ddc87c5d0c617e73abe645412f7a70f.nq.gz
    ├── 2ca675618dcc94b5655ceeeed8ec332a91fc3b62.nq.gz
    ├── 2cd37d590fef6d83aa6e9de9355c2eb6d65ee33b.nq.gz
    ├── 2f29a3a7313bbc2c647d5ebac1c9460ae2ac7dcd.nq.gz
    ├── 2f4524aacc261af226ebfdd4bc4b0b78a94073f9.nq.gz
    ├── 2f7838f34417aa4d110db0ade01b1ffad0812b71.nq.gz
    ├── 2f81571a62618686ed668313e6ec5a5549e3c7ea.nq.gz
    ├── 30b7135f171ca3b5655362aa53781ebfaa941af2.nq.gz
    ├── 30c2e9d8eb90aea7b505c43f56ee167ef0c6b473.nq.gz
    ├── 30cbe5a8699b074bdc8138c9029f652ee09b7455.nq.gz
    ├── 31787ab10cd5127b5ae3ffe8d81dafcb64b98e95.nq.gz
    ├── 319b5089a6a71e39f2280b4eb96d7da53a22b9ec.nq.gz
    ├── 327697506e1ee9908fb0f5d2e85c26db8335546f.nq.gz
    ├── 3404f37e2e312757841abe20343588a7740768ca.nq.gz
    ├── 34955b1e53aaf9cf8207479429dad8fb5c07906e.nq.gz
    ├── 3547663706d9a1c05da1713c907b611242afd1ac.nq.gz
    ├── 35acda2fa1196aad98c2adf4378a7611dd713aa3.nq.gz
    ├── 35c2e113b5d6abc52d6c224f13e85e2ce2e8710e.nq.gz
    ├── 35e81eff9254c4a8069bd9a87d1721c23a99d343.nq.gz
    ├── 36a2236d078cd8781f1c4ea248ef4a885fe2051d.nq.gz
    ├── 3754cb4b61288097ce7b1f675a14a7e4615442f6.nq.gz
    ├── 37f753e5eff96ee552fce14bb35a283174f298f2.nq.gz
    ├── 3869b42cb67731e1fd348fc3808322419465688a.nq.gz
    ├── 3885475a7eb1ad268e511ca74f830723bc1ff4c2.nq.gz
    ├── 38b2ba350796eeed9dec12d7240439d659790fb6.nq.gz
    ├── 3a41ccc2cf42e34e1b445de99c025312fec1dee5.nq.gz
    ├── 3a49c0897c016f6e6839b4a156bbe3365b51528c.nq.gz
    ├── 3bec935a8e49a97f1e96588640c1921ee37024df.nq.gz
    ├── 3bf9843328a6359b6bd06e50010319c63da0d717.nq.gz
    ├── 3d64b0d2eac02a0f2d233cd795fb15e775ec219d.nq.gz
    ├── 3dcde65da5e796ebb23602793686a5c90f12937d.nq.gz
    ├── 3e796884908831cec2e723fbf0e61e7d30e2ade1.nq.gz
    ├── 3f62454677177f3686ddc21d4745896cf827268a.nq.gz
    ├── 400014a4b06eee3d0c0d54402a47ab2601b2862b.nq.gz
    ├── 40b2d588f7afff6adcd47f6e094674aa7396839a.nq.gz
    ├── 40f7e22e32741c0e2f220dca87c6b3948dfab2aa.nq.gz
    ├── 4185bc9ba87a03afe2adf5e5d2ff20b9494e0218.nq.gz
    ├── 41f08392249cda7fcc336a40530f6c8795a37e1d.nq.gz
    ├── 422e835e5b68ee8457fd3a7aec8035ba518cbad9.nq.gz
    ├── 425a6564b335bdd83e218f2e705a80df3f72e573.nq.gz
    ├── 42e63c94bee224c27c1b9bc5b5d6a4470df3e414.nq.gz
    ├── 4322d8020e5aedeae87b836366dad7fe1ac4bdff.nq.gz
    ├── 43b8f4cdf689138c3220f005551e8c7a7bd4b211.nq.gz
    ├── 43e7c50f643cc8a00a0164c5a14e9f71ab272931.nq.gz
    ├── 4412c1f52c2db09b8f60ed73cbd6b5d6f346d498.nq.gz
    ├── 4416b13867e35891228371431ea762bf86784970.nq.gz
    ├── 4481a99be57b07413d72fc4b8d3f5b318b16a4f8.nq.gz
    ├── 44ba51b7417d2c74e1fd68a773ea61723b10db63.nq.gz
    ├── 4532a18cab07fd6fcb659378ea7068a88cbb5d03.nq.gz
    ├── 4558924532a21c7c521ffb8c03bf75435832d66a.nq.gz
    ├── 45afba20ff8d10171b09ce5e7d33628463d7cb3f.nq.gz
    ├── 46064f62c698eee2d80c0f48dd9076442aed54d4.nq.gz
    ├── 4616b0fe71d29f3ce5b1aa63111197fa8d79a50d.nq.gz
    ├── 46df6d2f8443faae63737bf6a8ed69641bcbba78.nq.gz
    ├── 474884846fcbbc256c074f0bc6ea651c8430a99e.nq.gz
    ├── 47abac9b481df17fc32072bdbc87ad51d517ce89.nq.gz
    ├── 48166e31ef1c4af7a255747e98f286c08510138c.nq.gz
    ├── 49d217c174682f29f25393a19cb057e07d4d3f6c.nq.gz
    ├── 49f7b9aecac6f02f012e5fd3d270c4ecca3355fd.nq.gz
    ├── 4a51b934e4aec2697e19e5dfbf197745ceae8944.nq.gz
    ├── 4aacf67a99ac0adfc62bf3839867c6ec3d44789a.nq.gz
    ├── 4b4b7b2851343d86a8c6caee246f527f68c512c0.nq.gz
    ├── 4be07bceee0bd0d88bdc1339d92ebdd8f8ccc259.nq.gz
    ├── 4c6ef607941ce700a31cdd133201dbc117f6e0cb.nq.gz
    ├── 4c875a4a5b441e9f66425c2b8418d08be158ff13.nq.gz
    ├── 4cb9ca49eeb5ab14115662e43b5054f1041656ae.nq.gz
    ├── 4cd37de75750de98751cc05e18af34541380ad11.nq.gz
    ├── 4e19eea8b1a612f44242c406bd1bd79cd48d5f60.nq.gz
    ├── 4e3098881bf491031f8ce84114d431f9b51e18bf.nq.gz
    ├── 4e4c43c7bc1fbb0cd044e54f3a0b37069f7bd138.nq.gz
    ├── 4f14f563931b0eb355d795f7e12997fb855993e0.nq.gz
    ├── 4f40de02beedc8231d92547265994bebe12e1e14.nq.gz
    ├── 4f75e068fe953cea48828ff408d0e36f7485b259.nq.gz
    ├── 4fab716e66aeae8e014ea8ba58ad46b85bfda545.nq.gz
    ├── 4fd7ea01e57d41d44e7ea51e598c49f7d2b8e9b8.nq.gz
    ├── 4ffacc1fc2f75c218b4d7322fa52da85b7f8732b.nq.gz
    ├── 50d6c53b0761bfe50c9c65dc7d77d8649d430847.nq.gz
    ├── 5231cf28d08ef6903c3f634478c8858128d7dcfe.nq.gz
    ├── 52475ea2f90d4af8cbe5203bbb52941082496f64.nq.gz
    ├── 525af8d548384a4475d439d039d6d1f57f3cc0d0.nq.gz
    ├── 52df9cc4fd47216a545205497676dd04baf94f99.nq.gz
    ├── 539cab39e7271715ebc473d140aab7927dd4621b.nq.gz
    ├── 53b8c2385da7e8d7d17d90c47259a5aba9647331.nq.gz
    ├── 53ec1cc8d17272712718fac57ab62139b7717594.nq.gz
    ├── 54095f59c9c952ce9a3d821c9238d16c61b56a4f.nq.gz
    ├── 544b24749a10b7a9768ff81059c6627be2f30cb9.nq.gz
    ├── 54516e082e520230ff5dade798d7de8748d516d8.nq.gz
    ├── 5463d1c15ac41c9059e3fb3381b9ce423c711bba.nq.gz
    ├── 54f51573091bc9269492840baec30038fdc2c53f.nq.gz
    ├── 55673248d6783bc8b6839ba7d648ee9442ff3d61.nq.gz
    ├── 5588fa114f80613ed398cb821c5e1b5071a73f0b.nq.gz
    ├── 55b06aad1073c90721500d41acda40154d137f5f.nq.gz
    ├── 55d4627d537397674fe92f91fb2cea5502f4cd16.nq.gz
    ├── 55e0de89b72f8a5010cb4e030d78bebee81e8665.nq.gz
    ├── 560c047c25833034bebfebabe4e3365817406f13.nq.gz
    ├── 56369fe2ba103ba282084b281cda2a6774a705f9.nq.gz
    ├── 56607bd22282f2aedc9659c51a2853f52fc9536e.nq.gz
    ├── 5814dc4334affdcaea20aef3fa92add26626d8ec.nq.gz
    ├── 58da1b579f4813983e2893d8c3182ee4b2e755f8.nq.gz
    ├── 58e999828e40e1b9bf6771a9b2de09354c815aa1.nq.gz
    ├── 595f0616a7818f6c9cb1ada83e688af3465c01b8.nq.gz
    ├── 5a40db83ceac602ffa985350791bea167cecb4be.nq.gz
    ├── 5b88361a31c678aacaf84f4cbc3a09e0102d6347.nq.gz
    ├── 5b9ab911a0a060f287d73912c4a776f6d35f3910.nq.gz
    └── 5c083a494e46cfcd530658c32f66da3ceb327643.nq.gz

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

[piskvorky/gensim](https://github.com/piskvorky/gensim)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
