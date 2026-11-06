# Repolex Knowledge Graph of jupyterhub/the-littlest-jupyterhub

RDF knowledge graph data for [jupyterhub/the-littlest-jupyterhub](https://github.com/jupyterhub/the-littlest-jupyterhub), parsed by [repolex](https://repolex.ai).

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
rlex download jupyterhub/the-littlest-jupyterhub
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 4ad828943d8acaa631708b317a5cfbddb258d3db
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 4ad828943d8acaa631708b317a5cfbddb258d3db
│           └── chunk-001.nq.gz
└── blob
    ├── 00bed9432001d6702df6b8b6c18556a350e72a83.nq.gz
    ├── 00d58eebfdbe78ce786354c4ac0d28680b397709.nq.gz
    ├── 010c5dc83648e9813265ebb07297c40918f2bc5c.nq.gz
    ├── 03980131d6848fa6b73a64bbd575704bb0737534.nq.gz
    ├── 03efe6cf563d593ca1d6165a928391b756caf37b.nq.gz
    ├── 03f5b83b0236bf90f1eca7cde17fd9fbf3f0b74a.nq.gz
    ├── 06840f621e55987dc5e1fa5a103375813adc5a85.nq.gz
    ├── 0a4683bad577d5112f9ea8c11c68d04151d59303.nq.gz
    ├── 0d81e9555556fbfd12fe162e7be439336456b2f4.nq.gz
    ├── 0fb6a4c8c5bbdc3f57587c781173566faf1ca302.nq.gz
    ├── 106d53457cfaf484bacd8c4f6e0f944433233124.nq.gz
    ├── 10d4280628dfcb1d1250992c229e065976916adf.nq.gz
    ├── 13f54a84f4b488f5ff488cd1a164a05d64f5171c.nq.gz
    ├── 148e1740b3d8b6aa0387bd7714f6880316517cdb.nq.gz
    ├── 14a52a1c73c805ff430ac19c20c175335d645c98.nq.gz
    ├── 14bc2c76525ba3776edc8263cc8668e74bf074e9.nq.gz
    ├── 151fe7f8e0767dd22d7773d2d8edca0b59ab8727.nq.gz
    ├── 16087a7fcad9502208ad60b89a513df2a3703a27.nq.gz
    ├── 1630096ce9ede5459ddf26716d7907406696e272.nq.gz
    ├── 172d066d0cdb0c83e015b9ef5afae66d51f042ff.nq.gz
    ├── 183fe079f69d0c13ebdcbbd4a02632373662fdf8.nq.gz
    ├── 198b422114409d3e626cc433e9901f9fb152ead7.nq.gz
    ├── 19d8f461f20023e22c1028c707ab2bf41b552560.nq.gz
    ├── 19d9ba6210254ae9eb488e09da99c1cf6c5e2666.nq.gz
    ├── 1a27a5c6fbf9ff9a4bc81a432fa7bf6c71170da8.nq.gz
    ├── 1abbfd935607a1ad76f072982c7f5989c6681a67.nq.gz
    ├── 1afe30b4e31f954f5c0442505aaed00b22249ae3.nq.gz
    ├── 1bdae0b6ead91bd801afeb40c9ac73c0d086984a.nq.gz
    ├── 1cb417a17c36d4cd4cb489dc166f043680735e01.nq.gz
    ├── 1e351e3e19d783a5be6c62b26e40175ae48bbcd9.nq.gz
    ├── 1e5c982f920181d4da33b2fef54feb66c3542cdd.nq.gz
    ├── 209cba6907301510bc0c74054b0fcf11df8b7282.nq.gz
    ├── 22a56f716e88cf85e6e841a94b1b213d59b288ca.nq.gz
    ├── 2400046c3c0adf2b70fad8c9ad8e062090209a6f.nq.gz
    ├── 269ba4b25ea95cc050d756ef22c5376f352f7711.nq.gz
    ├── 27ffd1b0cd29b0ce6b6d3e562d562d4640b95831.nq.gz
    ├── 282c60ec95ce84e8d674abfe686335e9c0e719ba.nq.gz
    ├── 2830847b201f4d302099a8e8bcca3ffe2295283e.nq.gz
    ├── 28c3e451f302056cd664f3e8272c3379232affe3.nq.gz
    ├── 2b826ad6a8fee6cab7c1778d6fb67f3ba3ec6323.nq.gz
    ├── 2b9f2b90212bc990e5a9f83f84228c046aee95d4.nq.gz
    ├── 2c5a32c2e347c9b19bd06cb4b983841f49ac619b.nq.gz
    ├── 2c6504994f7ff691c544a085e04ed9a955d88c91.nq.gz
    ├── 2cd397c1edb17d980acd9a02fb393b053b2c76a8.nq.gz
    ├── 2f367c6c05a040802c5b9ea0f6724abc8211c44c.nq.gz
    ├── 2f65bfd4e2fcd83255270169214c3b4035fbd4ab.nq.gz
    ├── 313cb295483e3527cf927a642ab611dce938430d.nq.gz
    ├── 31c6a69b3a80beaef28080736000f4d9bc9ff2c9.nq.gz
    ├── 3424876c2d5930a3992b6dc6501a5cafd5856b00.nq.gz
    ├── 3439f71da39e13851a0256fb4e6d53b8c3ae6b6d.nq.gz
    ├── 345611965163859449cf23e31a7423cd593ce0d6.nq.gz
    ├── 35618abda22b40d7a008bae483bb1164fff1c980.nq.gz
    ├── 36bf9799a762a9531778502b8427d09195ab58c8.nq.gz
    ├── 371e084b48aa30ab27a76e5db5362e13efd20dba.nq.gz
    ├── 38306e701921127d1007f0ff72c223ccdd88647d.nq.gz
    ├── 3a290564fb8b44d201c9b5d195316e4d950ec40b.nq.gz
    ├── 3bd05d4f717e0afc7d24aa349d1e5f8d663fc4b8.nq.gz
    ├── 3c1db3de546581bad6c86057d4fb23e08e07133e.nq.gz
    ├── 3d4fd23953720cff8d5b83b8ef68478eabb62b29.nq.gz
    ├── 3d5bb29c94cf3f5efc32d15e068d050db7f82798.nq.gz
    ├── 40c2b61333924e1729cb0a442c8776570007e8ae.nq.gz
    ├── 41c254510f7c5ac08f1f185d2f62bec5027f4866.nq.gz
    ├── 41fb2f6236b1f10d546d13e6765348f36919d340.nq.gz
    ├── 42226f2e7ff68b9e6ae9ffe58701e9dd3e2e794c.nq.gz
    ├── 448ab1087517d28107048c556c2774cea9f7894e.nq.gz
    ├── 44d7ba2d62c6e5b9649cd90be93e3559977c5c10.nq.gz
    ├── 450075e958c1093256dfc98f75bbda6b0173e693.nq.gz
    ├── 450767fb6077a52923da2eb4fb39a614a513889b.nq.gz
    ├── 45cd7958f40093ed3648c6190daf28a8f2174065.nq.gz
    ├── 492f4169fb9095255864cb6138b40aa5fd61d71d.nq.gz
    ├── 4a17f131e43cc7de2994080c55f2967ba01d7091.nq.gz
    ├── 4a4a6b1a23afe658760f220e2c596a1446668b5f.nq.gz
    ├── 4d39f53a4b6981682857652c4597dbd63580810b.nq.gz
    ├── 4f4c9e10c2587c04006095bbfcae85aaea730c5b.nq.gz
    ├── 4fa720499be93773c33dfa0a423d426dc4894cac.nq.gz
    ├── 509a6bcb83aa3d9906992bc7f67bfb75269318b5.nq.gz
    ├── 50c1cf7616e4f1d462daf44b9ec79a86ef93e4ff.nq.gz
    ├── 519c53107e50540813d20ef3f70e0631ea3099e5.nq.gz
    ├── 547c7ddcb6c9f5cc5777b950f9e0fc394b846a26.nq.gz
    ├── 55a2185812962b41d48c787662725a21548036f7.nq.gz
    ├── 574ff99efd4539f5ceba9ea7fb749bda1f716c5e.nq.gz
    ├── 57bd2b4206f9d3222986b6a0a5a89144cb9dae2e.nq.gz
    ├── 5a02fc8107862819beebee91250b12c3d954af73.nq.gz
    ├── 5bfcf852a1e3409c669be3b77764524f609cfd54.nq.gz
    ├── 5cc4e1f3c8cbfd9402d4b8940f5e87399c86c142.nq.gz
    ├── 5fc0034ef5ce84e0eaa789eb305aa21d5a1130d9.nq.gz
    ├── 61384dc748cf1d3ccc35fa57454e838e51e20d87.nq.gz
    ├── 6151b8d008d4fd056b46792e14480753a0943a56.nq.gz
    ├── 61885cb535197c7072f79d7e11ce2845dc1ccc47.nq.gz
    ├── 62468ede40474fc422e8c2bf586eb0d73483d1a3.nq.gz
    ├── 638fc4da8dddba9df955b7e808e0c7b2b38df2b7.nq.gz
    ├── 65319c5ef017178eb9b1ce4e7c02fb6eb80d69ef.nq.gz
    ├── 670f722f0fc797b0f5a3397cebcde68caaff2422.nq.gz
    ├── 672ad32a45926b5919ada7cccb206a2f01d336b2.nq.gz
    ├── 67d4d8dcee3d6204f55b32e2b916ed1837fd0c27.nq.gz
    ├── 68a61cb51f09e560b4b6ed35030cfa93bbc53821.nq.gz
    ├── 69399e44fa0fe4a6ebcbc17f73e2a8d50a7e05d9.nq.gz
    ├── 69660185b418354fb4800e6c3467d431b0bf7d0e.nq.gz
    ├── 6bfaf1b847e001f8ca650dfa2fdc0274cb20ad9c.nq.gz
    ├── 6d9898b15d1fd6dadd0b417165324c10e75dfe49.nq.gz
    ├── 6e7f2638a16fa4916208ff5cdf7218a4cb221b35.nq.gz
    ├── 6eca51d55a82d0adca93d9bee8debee8dd95ee9c.nq.gz
    ├── 70487385e40aea3258b62505a81e2686a2692c33.nq.gz
    ├── 70783a2d493ea4167585c4e124688a5cf89ea4aa.nq.gz
    ├── 71fe1a9cca4fb52b0522f00123c5d4bedb72ce80.nq.gz
    ├── 73fdc1f6eec39995a74bfb11d8e6fbf1eaa93997.nq.gz
    ├── 7440511b1c5a046dcc5f19f38f48794edc795b62.nq.gz
    ├── 74ba5da15b58ccefe5e14c0cb08b8839da2c9253.nq.gz
    ├── 74c4417927c67ebe6eba8c9b86cb068f859b556e.nq.gz
    ├── 74ef3579c039b0e60351ed7725dff886e76845e3.nq.gz
    ├── 752cf8fdeb39b62f63d570b632543797eb918c56.nq.gz
    ├── 75a4644aea81ba8d657b08ac9bd6927623ea761a.nq.gz
    ├── 75fdd4c62f4b31aca27d869b67d411278b35a488.nq.gz
    ├── 7662e2a94f4e759c5f1fba531f446b40c7edef8c.nq.gz
    ├── 7a0d5e7164b4e1f10e714e144bf13ade8b288e31.nq.gz
    ├── 7abb617dcb99bb01a9c7797f249267b8faf3c53c.nq.gz
    ├── 7b28885549c75f79df541403f821327c8d24223f.nq.gz
    ├── 7b6bbe6c7fd9c7c96f2ba4fc984c4ae554502bd9.nq.gz
    ├── 7eb253373c592fa0b10c5af51a17c3bff51b1cb6.nq.gz
    ├── 7efec6630930586ba5207001d40f8636f7ff014a.nq.gz
    ├── 826f65b097bc54305dc372d88a3fb1ef279d67a7.nq.gz
    ├── 82bb7b4d4dd75b50f11c4523ae1cc16476c1d793.nq.gz
    ├── 82df1f4ea9f0aaf9246d39dae94f97bebf610a1d.nq.gz
    ├── 84cab6394fcdac9592f07ef98c1514aa3326ff4e.nq.gz
    ├── 86129e8a675af193deffc778c1e43215f118a83c.nq.gz
    ├── 862115ae49d42b76acf376d50399cfd15ed43741.nq.gz
    ├── 88a752ce40bbbef0dcdbd77e6133a2fe93a2abc8.nq.gz
    ├── 893702c4a3efc5f3e550f280b9ffe317c802400d.nq.gz
    ├── 906d49cb2add0e49b5beaaa06d7e8c09bbc824ab.nq.gz
    ├── 90abf537bae731f8842330f086d172396e998b7c.nq.gz
    ├── 91158771d110e299c6e8b0e27b9f94a37e6652e0.nq.gz
    ├── 91821a8708988a6a7aa7c0d4cc1096b85ada0300.nq.gz
    ├── 9364de1fb281ab1401025b1d8a955fa973f239df.nq.gz
    ├── 939175d3cef7edaadd1a811d7325fc440bf2b0ac.nq.gz
    ├── 957feff16aa5c45c756f1b17cad4d673854ae016.nq.gz
    ├── 95bd5e6b85cdc1818ed5bb57986b83fc66616a00.nq.gz
    ├── 97d2c1c8a1c08e1388a4d5b53ca6dd14db65f157.nq.gz
    ├── 97f70dcb5d114ba2c63175f7c6b4b2a0c7c556ef.nq.gz
    ├── 982933c2d5e30282e18cd3dd2340d10bca310607.nq.gz
    ├── 99bc5308479ba2d09807c06238fb128c03c07b6e.nq.gz
    ├── 9b0c8f8cb442ff7b5258028e123730abb172788d.nq.gz
    ├── 9b626ec86e4f5a1f9f37134886bf84d7ff4f5e6c.nq.gz
    ├── 9c899fdd2d960924f4e6a78b51bfc96fa3819835.nq.gz
    ├── 9d3f8cdfd3253fa00cb84e665b4cee68a44d25f0.nq.gz
    ├── 9d60279f91f7b6764981d72a95af25e77f4ec3c9.nq.gz
    ├── 9e4cd7a3854ec959c50e75aac477a2b37fe08c51.nq.gz
    ├── 9f00d83b317652f0973dd4e772a477ee1c2a8b15.nq.gz
    ├── 9f45851595ed8a80a43869146a6ec827e80970ed.nq.gz
    ├── a0610f7a179542641a240c7b022566ad0d7f50ad.nq.gz
    ├── a0bd1f96c1e17422fd67c5b0cf53e340de5fa1b3.nq.gz
    ├── a3bbbc282811fe17eb44f317c81f31b31ee9afc1.nq.gz
    ├── a3d07461b097de566adc7c80f8e0cf357e5bebf2.nq.gz
    ├── a46910691c590405acdd0ebb5bd63564e967487c.nq.gz
    ├── a47185476f821295f35f4573faff8a1ebee3c4b1.nq.gz
    ├── a5b08578fd91f09e28114ce4b4b4d00a910c11d5.nq.gz
    ├── aacb743e6775f2b31c0885dea44fedc79e26cbde.nq.gz
    ├── ab447520a5d14c37fe41a0ac6b071032480325e0.nq.gz
    ├── aba56aec6455e18def47a65db59dd0beec7e7b04.nq.gz
    ├── adcdefe54b06bdef0cee73c24eb478b4e28d8902.nq.gz
    ├── b01a32bb4bfa3709fc4e181ad2055cff577640b9.nq.gz
    ├── b03903f1b83a7e39a23c032c029f9809fa48eca8.nq.gz
    ├── b102cd56edf8f082a5a159dc2663960fcc590d9c.nq.gz
    ├── b3625b8f67a9861491134feb82642ca76e7e8067.nq.gz
    ├── b38e470a7396f78b9cd3c9e62f05e2bceb43581d.nq.gz
    ├── b48e03249bee0f2840aaa48a48f39321cdee128f.nq.gz
    ├── b7250a07a361f9b4c269299e8a77b7168095add1.nq.gz
    ├── b738bf2e19ddaf9c6b1ea0b2b9d1a203f02b553c.nq.gz
    ├── bbbbdb4e10553b29487bd3acd973ef139a1c8037.nq.gz
    ├── bbc76ff33e421ce5e23f2ace867a440bb95b1cd6.nq.gz
    ├── bc33a8860be3a435eadbe0056f22843618165ef6.nq.gz
    ├── bc425a83efae6e296acd8e1ff22e46ddd8d86bed.nq.gz
    ├── bc6f72d4bb1a9bc073b756d554c64a93b1fcf678.nq.gz
    ├── bca39e3da7d484fca8fe7de2a92c6b103125fe5b.nq.gz
    ├── bcdf58cc5c845df65f0a6b84e4d16c705889d778.nq.gz
    ├── bd08c8244085a4d7905c8b1ef5f461b7c00d246f.nq.gz
    ├── bef74cc36c55e6325af7f673e0fd6aeeeb6b21bb.nq.gz
    ├── c086c7fcae03f8dc9e015e29ecb79fa488c5d8db.nq.gz
    ├── c2f8a0982a315b19c9f8a9f7232116d242a1caac.nq.gz
    ├── c3ec06b2c831ea622c10496b5b03e1f9d83720d9.nq.gz
    ├── c49abc52cbfc33258f56c3861511d69ee8d5a685.nq.gz
    ├── c55d51392a55d1702e49e5a21d914366f8a28f76.nq.gz
    ├── c6c2a0f9c8cbd3717a4fa2ba634425abd76b693a.nq.gz
    ├── c815c9cd526df6a644eee6b903d6a0b8412ba21c.nq.gz
    ├── caa3040e12311bf01787d876e4b84fb075b1de3e.nq.gz
    ├── cba37035a496f76720ff3526354bf76e2dac30af.nq.gz
    ├── ccafb50637e0beeccf725b90422aa4ea27354b65.nq.gz
    ├── cd74b35bc6b370baa647867f265a06e50845fc8d.nq.gz
    ├── ced1b162b2d61ff350a2da2cc866d3b30c182508.nq.gz
    ├── cf797c4f2a58bc69e52d68571dfcd60aeb6f63b7.nq.gz
    ├── d1dd03265b35c95d2f7e31cc4cfcffd4dc890c26.nq.gz
    ├── d24f916255c890eec1cd244461839089e98c4ebc.nq.gz
    ├── d344bc3566de33f2100b7fa08f4c56610f419c78.nq.gz
    ├── d35c73a983afe0db407d968d1aa2ab47b8bcf749.nq.gz
    ├── d408c3fbc54399eecfc0250935feb74b6e667d1b.nq.gz
    ├── d5810d859563c7cf6cef78997028f149567c724f.nq.gz
    ├── d6200b5cc521bf36d1f721931f46931ac809921e.nq.gz
    ├── d6397d360e0d8a277b20ca5d45943b06c2f37bf7.nq.gz
    └── d746f4569d3ea0b91abba12af7a81fbe26a1023b.nq.gz

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

[jupyterhub/the-littlest-jupyterhub](https://github.com/jupyterhub/the-littlest-jupyterhub)

---
*Parsed on 2026-11-06 by [repolex](https://repolex.ai)*
