# Repolex Knowledge Graph of facelessuser/pymdown-extensions

RDF knowledge graph data for [facelessuser/pymdown-extensions](https://github.com/facelessuser/pymdown-extensions), parsed by [repolex](https://repolex.ai).

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
rlex download facelessuser/pymdown-extensions
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 7a3f1715c6903621ae96b9024c7d372636a5fa86
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 7a3f1715c6903621ae96b9024c7d372636a5fa86
│           └── chunk-001.nq.gz
└── blob
    ├── 030501cd884bdf1aab9ddae23528d133a7193940.nq.gz
    ├── 03b9fe9c29e81e3828c94ef3c8214ae8189247d8.nq.gz
    ├── 045b5e554a0d5987cc052272ed5fe3370afa5a81.nq.gz
    ├── 0478117827f50a4dcc93e9f379ce07e838dd2345.nq.gz
    ├── 04872dd816c8b0b1476c18fc1b73626263b55dad.nq.gz
    ├── 05998e97a0b5a8701d63b2d3cb3e9ccf2aee05cc.nq.gz
    ├── 0695628c2ebaf58801bcfa93be4f8ed9664f8f00.nq.gz
    ├── 076867a72ecd036c336e02f13a6caee877a4d067.nq.gz
    ├── 07ea6b700d3ed29ef6d4c992b5fd9dc40a88345f.nq.gz
    ├── 08effd4aea083cbc7858043831145808ec190185.nq.gz
    ├── 09de440486c4c9ad68332952ac7c8df167d12967.nq.gz
    ├── 0c70f47d2b7cf432861890d7d827302fa08b839b.nq.gz
    ├── 0d4e0f24466515be345de5b380e907f41772ad93.nq.gz
    ├── 0d92396cb43dee823eccca124525d5573758e15c.nq.gz
    ├── 0dcc34fd2038d2627ac42015f9753a0403d88c25.nq.gz
    ├── 0e45c6d84df04c5853108c14bef3247af6dade5a.nq.gz
    ├── 10e843d5a5bbf6ca903a71eb5e731f9daeaa86de.nq.gz
    ├── 10f78556cc9e7f6f8fd9ae1553407641f17b2908.nq.gz
    ├── 110e9121ef8db4d1127cd7dbd1a8e567d705d74b.nq.gz
    ├── 11583c2e443dc1d9dd446e9f3712aabed02adca6.nq.gz
    ├── 11a6f49f76235fbb8391f00b114c5bbfbf281d6b.nq.gz
    ├── 1320b9a3272a5a4a9adc81859d52c68660d1b50d.nq.gz
    ├── 14269b8c3b48c39a883ccfd918d671de7f450b60.nq.gz
    ├── 14787ebbdd5bf77b3fb8bc35f743e5d3403cb5a0.nq.gz
    ├── 15193a0e34c43027081769378e2ef2d305a180e4.nq.gz
    ├── 152970f1b814d97bd70fdfdca3734cb77844ed49.nq.gz
    ├── 15d8bfc4a0637f18b465399e3c9b977663b022f1.nq.gz
    ├── 16031646e4936c04d7983f211288ffffd214fdc6.nq.gz
    ├── 1653b7c40d5d18638dc91ec2d2a4a22e3524a790.nq.gz
    ├── 17072e513bfed81ffdd150e649cfe371f98b7c03.nq.gz
    ├── 18b584192eafd2a799fba5417370d03fb932c507.nq.gz
    ├── 19bb5a7f60cd9536db8356eede204033c397f186.nq.gz
    ├── 1a23110e59fbe5bdd06b4c40d826783d9de79284.nq.gz
    ├── 1a27902c0e2c4cd3e840f55cb6bbc6b5f7ce5ae3.nq.gz
    ├── 1a8688f0cf3229a89d2bb0bafa66fedb482bf9d4.nq.gz
    ├── 1bbb775f961d74eaa923c115c0b7ca56eae9e4f2.nq.gz
    ├── 1c41677fc7b3153eaa051dfb744379e22db4711f.nq.gz
    ├── 1cdd8ff5e9e6c7bfa7457c69d138a7c69c27ae1d.nq.gz
    ├── 1ff35ae8efec12a13f44e7ffaa50cc49d9eb10a4.nq.gz
    ├── 1ff604da9cf15733405334ed648c448900e88e78.nq.gz
    ├── 242e927e9415567a3dc2ec5a9652158bcbd82c0b.nq.gz
    ├── 251331701a928fc81754b972f191cf8a78a348d4.nq.gz
    ├── 2558ba5032ae46129e47864b308d7300735e3594.nq.gz
    ├── 25a2ab64eca2a580037aa1794d356e48cbd1e4f4.nq.gz
    ├── 25dd4f82992a5966884ee1050c1e44ef4906a85e.nq.gz
    ├── 261fcf42efb158dfa1fd39457e6d5705bc73e21f.nq.gz
    ├── 266ef655481cc8f037b7d83c348ec0c7425aea9f.nq.gz
    ├── 26cef884cc44e747bcc8c197b7b5b44f451056e9.nq.gz
    ├── 26dfd0a3f8e60a097b2d6f983f953adcd1391dd8.nq.gz
    ├── 290d31c832bd766d72242606133be5645739b96d.nq.gz
    ├── 2a2cd2989cadbf73bcb41bfadb38414b62ca9113.nq.gz
    ├── 2a6ca64c53f17b5b7801a2c2979efddba5005609.nq.gz
    ├── 2d5bf2dc70a4ae7e291bf3e238a0478c2e7cc999.nq.gz
    ├── 2d792358908c1879c0068c3649f4dc98eb797658.nq.gz
    ├── 2fdabe5784fb85fb5af3ac441f079c7fa57a592c.nq.gz
    ├── 30104bfcc4ce83f02f066143dbada5264987dd2b.nq.gz
    ├── 3140bc640eb83437842a11f3faddec48dd904676.nq.gz
    ├── 31946dd015ced7bdc2d95f306e492d019ec66cf6.nq.gz
    ├── 31b97f3aa5ca69d0679ed8c4f2238af7758b1f62.nq.gz
    ├── 32ce4dcb20f8559be8693bc8128216deb7ce0a05.nq.gz
    ├── 32f5ffeea2bcc7143e255ec72fa2f41e28bda76c.nq.gz
    ├── 34abc501bbd9b71ae910def0e1875a6d5aea9f30.nq.gz
    ├── 3674c854ab3fc780be9cb7685a0d411141d01d96.nq.gz
    ├── 36ae1aa8fea16f906d192cd1301dfc0fcd9b4121.nq.gz
    ├── 36ca5ed9d4cc9e64f8a12b69028e12445d920765.nq.gz
    ├── 3784148d37a0335f8261604523e0dfba80800bc1.nq.gz
    ├── 38849b9cb2c2c0a364a5a7a6e8f73330df086710.nq.gz
    ├── 393d3ab1c2b580b50a3cb14b31e88dd0e28c06bd.nq.gz
    ├── 3a1f939e3a57f40c2db524c3db639a257d356512.nq.gz
    ├── 3a46868bcb2fe738fca127bbb0f73cf86fe8303e.nq.gz
    ├── 3aa88af96b46c4820a59e6a519feb3d36d4c01a0.nq.gz
    ├── 3afcbe02d1448ce29730f0f5e7104408b6901d66.nq.gz
    ├── 3afd036970735061298bcdf445ca7c3ccfd90ad7.nq.gz
    ├── 3c76ef3f694b174d44b466572286203df6024d1b.nq.gz
    ├── 3ca92b7aa0c58566bbf8ddce866ce71f2c93cec7.nq.gz
    ├── 3d79ff266c342f727e822f7290db46041ecbdab0.nq.gz
    ├── 3e31747986287d59845af2b59e882f84d35949bf.nq.gz
    ├── 3e5443286d119a431431f49c464b4fbf7a5002e4.nq.gz
    ├── 3ee700d7ac30b3a36426f605138ab55369653e71.nq.gz
    ├── 405b16d0b8b5bfb5f072acf42cd6d248327d147a.nq.gz
    ├── 40a27f43b4b7d01b9d4fd02e20b6a6653a62dc26.nq.gz
    ├── 45666864cb6ecd325f70664f0ed698b15664f5ca.nq.gz
    ├── 46022a6c10e23f7b317353e318a7f956b89587e5.nq.gz
    ├── 47007a5a9f3f8cca34b3677da79f96df99d7a81a.nq.gz
    ├── 4a31b0e6a0de8f6d575f81f3859be3c8aa89207f.nq.gz
    ├── 4d45dff85f3fb0e9b6a84cfb03be985fbf8b4272.nq.gz
    ├── 4f4112a5f897421cf12d695462469f118569a59e.nq.gz
    ├── 4fd4b94de69f62c54cbcf0487b426ad34823a376.nq.gz
    ├── 514f5cce2fb63fe6970018b4722029be46370985.nq.gz
    ├── 528c55e3ae5ab31701e42285503ea9538f175afb.nq.gz
    ├── 55aff8832d7e5d485ce68e1540c438e045b74b69.nq.gz
    ├── 55cd318d41ead6ecf0219c6f2279846483547da7.nq.gz
    ├── 56249b2688f6997727851709cddcf169d0d2e11d.nq.gz
    ├── 565f960ad3b27e21d7f34b3f74c42a8ffc8e0925.nq.gz
    ├── 56b61058c16da1e56bf4126eed04001655a3c280.nq.gz
    ├── 5718e61d7246b5cdc380e952d16f9467e64ab7a7.nq.gz
    ├── 577d5f1fa2c060b5c8ac0fc47c0bcc6abee20bea.nq.gz
    ├── 598e10d96faf103032d105d4f5a533e75ea9ecf8.nq.gz
    ├── 5aabed6e9cfffb4418155b46b1df626f82b8b0d1.nq.gz
    ├── 5b897fe1b9627c42874f5eabfbf93f121325e3bd.nq.gz
    ├── 5bfde9d7a24bba91b4e33f257d8df38c902cccd9.nq.gz
    ├── 5c181b0574d1019f40137ed3b68afae9a5476e64.nq.gz
    ├── 5c2bf106b1a43fd63b03a757890a9298cf37cc66.nq.gz
    ├── 5d7bb58cdd379305a840102766724346e52a1dc1.nq.gz
    ├── 5e79c033e7db039a859ae904044a6da0d5ed1d27.nq.gz
    ├── 5e9f98b346ef525d1e4962c99f13cac58b92c11f.nq.gz
    ├── 6003f5ee9fcb31c6b73485ff515759ef45fa29aa.nq.gz
    ├── 62b1f7702c7c75bc8fa0967d9017d70788422def.nq.gz
    ├── 63f4cc70bace2e0b1101864afebb19d7b56907b9.nq.gz
    ├── 6661b4b3e6e489df9f0a0514953cca222692b5db.nq.gz
    ├── 67c46ac224f12f9dd8b1df9283c12ac00a948280.nq.gz
    ├── 688ed8787848c5b98aea5b6731c67dbc3707cc90.nq.gz
    ├── 68ce04623dfce1ec95586fb268d65d500e071e1a.nq.gz
    ├── 68f27debe78e85878e12843f106b55b5d69bd1dd.nq.gz
    ├── 6a5d925308254cceba01ef1f8a065ffcdee4e2d9.nq.gz
    ├── 6a945c1162fdc130b84b354acb6c8a2cc46a0baf.nq.gz
    ├── 6b1f00f42b492f4d1b6b2627d40b75c677d0b4da.nq.gz
    ├── 6c6ab6400022c5bc2dc8078f44be31419d632a8a.nq.gz
    ├── 6ded53e2ba6fbc278705571f27fd98cdc37ae592.nq.gz
    ├── 6e9f907872568b140e83a9fc6893b844e835c2ff.nq.gz
    ├── 6ef536c3e21067f4fe74defeeacee8787f4a2ef2.nq.gz
    ├── 707b1a1f8edd69156c2f4abb3ce6f142334386a3.nq.gz
    ├── 70c08084158069e1ccd97872b7b35fdf29c4bfdb.nq.gz
    ├── 72433fa7cd16e2f59798ae64e22cea873e648b04.nq.gz
    ├── 745c7d0d5cd187445e862060df7f8e4f785f55b5.nq.gz
    ├── 75dcf798e37426bb1ee88674503cd72d99e6b5b9.nq.gz
    ├── 76312b708f254428e7e6bb171da1272ff816b2f9.nq.gz
    ├── 78c7abf3c81af9e1577fa830d8b8af0e398ab4e6.nq.gz
    ├── 79c859ff62e2a607b6f6eaeeb5e4025169ce4cda.nq.gz
    ├── 7a029996aa1fa65bc44d669d477de73e6ec5d1ca.nq.gz
    ├── 7aafed4aaa0a1c7e18703d1fea13cd95838af301.nq.gz
    ├── 7ad7ecf5bdcbf7942002dd80c82a4552cbccf4bb.nq.gz
    ├── 7aea57dc4548dd90eb3033a00c5e674e83dd7381.nq.gz
    ├── 7b4e99fcada6b9b3c493e0d064312d05cd694b0d.nq.gz
    ├── 7c69e547b4322aee737dd43c9bac2239ab4866c6.nq.gz
    ├── 7cc6c9022ba2d43616d51f10eb65f76d610fb918.nq.gz
    ├── 7d0fc0668acbfe84138cbf21e4faec1e958a2a44.nq.gz
    ├── 7d2f960bd3cdb6b7b87ec0deb276e549fb49c043.nq.gz
    ├── 7ecc8e4f331377db8d0caed7b316e625af7cb245.nq.gz
    ├── 7f356eeae797003f65aed85666b94c02c123f973.nq.gz
    ├── 801e46a0789db36c9748c5635e40b6a7b66086a7.nq.gz
    ├── 808b5fb30d2eb632a17738eb8c7f51d1219c3d1a.nq.gz
    ├── 809433699d35ecdcfa18a5d68a0ae21d932a35e7.nq.gz
    ├── 81d6bba40530dae414931bf826e17ffd39715127.nq.gz
    ├── 81f9a5c71a3b3a36f9ac69bab5771f23d3a41c68.nq.gz
    ├── 81fb5b8e0ac3c7827d4136511b6fe4cec7470455.nq.gz
    ├── 82d5a4d3e7bcb45442396d76aa16421eb8bce9b1.nq.gz
    ├── 85fef7d773d5f45957c3fbc49b2737aac935cc92.nq.gz
    ├── 86581cf706914a132797e1a958cc377218205c86.nq.gz
    ├── 86fbadb19c10075d95b8e7cd7eb83a7d56f4b2b3.nq.gz
    ├── 876477c2264d48f210afbe379bee463d4048d4b0.nq.gz
    ├── 889df96b2eb61e702ebc0013b1cbbe2d70c8f9b5.nq.gz
    ├── 89a063535dda22857f7e631cbb56ddfc09f697c7.nq.gz
    ├── 8afdcd2aa8a6fd66b4234414c855e0425ed27d5e.nq.gz
    ├── 8ba9cd6daa4070d5ada438f69b9f4b115ef678ff.nq.gz
    ├── 8c7301a6c287acd6a1c6871953afb57f8bdeee2a.nq.gz
    ├── 8e0b46224c070ba35bf2881b42a181b24dda5a3a.nq.gz
    ├── 8e23c970aa1fe7db46c39ad38a4bc563ce5c5acb.nq.gz
    ├── 8e2cc05df8a572b87ef43206bcbb76569929d930.nq.gz
    ├── 8e4735917bb93aade2aa607d036ec67bffe05957.nq.gz
    ├── 8eb2a30f1c80fb598264798c61639d975ecfd6ae.nq.gz
    ├── 8eef0e82086d2cccfc3b2422deee7888e6ca8873.nq.gz
    ├── 8f768db51cffdc84c4728426fd5edd024fa22b60.nq.gz
    ├── 8fe938b2507069f4e817904dd9bded3b075611c2.nq.gz
    ├── 904d8e1af000a75d7a2ab775a0338fe1aa9a9a47.nq.gz
    ├── 913b4bd9b4d3f7fd22f5ebcab00d59e8bc336a2f.nq.gz
    ├── 920aefae7e37592c88e5fa686a8c685c799d5850.nq.gz
    ├── 9291a833e15f569bf5d8648c2ef7b12624397666.nq.gz
    ├── 929d8be7c2a687925e187d8bbe47a3f21c9d795a.nq.gz
    ├── 93e2f4903076ef57e2c007bc36c17b4996628db8.nq.gz
    ├── 9401e6e5c2cac38c0b901464c405196d0437aaa5.nq.gz
    ├── 9418ca4cbeb64f70f6bd58f984f2c82818d53391.nq.gz
    ├── 946857304226ca049c9101ea31aa2c939c2a7fb7.nq.gz
    ├── 94a48a99006d4a3d74c235a06c016d1443d2dcbb.nq.gz
    ├── 94d6c81f314c4c447f93ddf7e8b657f39964bd3f.nq.gz
    ├── 98162e48ee8c26ae3d5433a8c2cdc5153e2905a1.nq.gz
    ├── 9db50059524065f4f381e01d0a578524d918e7db.nq.gz
    ├── a0af627be38cc5c93663f1e40ee47e96a5bcfec0.nq.gz
    ├── a13070cf7546678e7b8337dea47bf524e0317263.nq.gz
    ├── a285bdf56609d2f4118a3f82061ea86e9007c4be.nq.gz
    ├── a3583e7000f10c31242f0215a9329c4ae6de503e.nq.gz
    ├── a57fc5e19ce9288591dfd8c34872916b75b07b09.nq.gz
    ├── a6b1847efd93e072ab5a9d453df8beedc8925d04.nq.gz
    ├── a887aeacc589f45a6fa63d4c277d94daa44dc15a.nq.gz
    ├── aa009f82200cba0148f26b1cadb12705dfa8371b.nq.gz
    ├── aaea4010b0aca3ce0e861ca4acf0c8d4545733e4.nq.gz
    ├── ab59ae87236414ec0e7601c4787d53af6bc78caa.nq.gz
    ├── ab8204dd3a40db388d19d185e39501ce891e2f1b.nq.gz
    ├── abbfd1e796363741a2e40b6ab77c3cc29ec60094.nq.gz
    ├── ac572e21629da0a18a14917d4ffd2be154254834.nq.gz
    ├── aca49ffcfc8de99c2ef41e0df3b98dcb3a16ba87.nq.gz
    ├── ad09be68b0db1148be2ab004bf977dfc7f0d3113.nq.gz
    ├── af64826e8ec6da2cd7225cfe2201368fcde7180e.nq.gz
    ├── afcc7e604f2acd8d150a35287c58567517f0f59e.nq.gz
    ├── b0c035251cf8003488740bc9cf715547660f5ac0.nq.gz
    ├── b0ceb69ffb0a4622244aa3cd185371a259819657.nq.gz
    ├── b472b07997300baf11a86e5c69089cd56f049961.nq.gz
    └── b4c2d38143782a814e321050bb648860ff772288.nq.gz

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

[facelessuser/pymdown-extensions](https://github.com/facelessuser/pymdown-extensions)

---
*Parsed on 2026-11-06 by [repolex](https://repolex.ai)*
