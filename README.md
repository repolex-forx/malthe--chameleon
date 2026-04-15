# Repolex Knowledge Graph of malthe/chameleon

RDF knowledge graph data for [malthe/chameleon](https://github.com/malthe/chameleon), parsed by [repolex](https://repolex.ai).

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
lexq download malthe/chameleon
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 10e5d32e7b974cd5150e2963bcf915ebfd6f4683
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 10e5d32e7b974cd5150e2963bcf915ebfd6f4683.nq.gz
│   └── repolex
│       └── 10e5d32e7b974cd5150e2963bcf915ebfd6f4683
│           └── chunk-001.nq.gz
└── blob
    ├── 01743f9f2ce07baf17418ff6aa1572e1c4b30aa2.nq.gz
    ├── 01825354ad6c1a2ce6fc7a4a9dda5837e928f530.nq.gz
    ├── 01fef619761d7f8de57c6c465e85fa954831c190.nq.gz
    ├── 0261e302e9459396e2fa1bf999439c9b1aecbaed.nq.gz
    ├── 02e93034ef03c4d4f7ca981435821bbb82eabbaa.nq.gz
    ├── 035ac3a53f935c12f3e2faec87359657628d1b03.nq.gz
    ├── 03ba43010d0879871cbe638ec8b2f692faf1d90e.nq.gz
    ├── 050752b39fa9322121ca854cf4d3dd8425333ff7.nq.gz
    ├── 053e8c9aced5675c1a23487fce85f58e84528b84.nq.gz
    ├── 05ac901329d8157344554caba5238e4e5d4471f1.nq.gz
    ├── 07b8268cf013af8df91ee3d9c6555d81dc587f02.nq.gz
    ├── 0897316e4670a2e487db1c359a370e5905ed23b3.nq.gz
    ├── 08d7d69aedab1b33da687cafe04c4517dac9fe2a.nq.gz
    ├── 0c0464ff164af92733a55db5351d07abcadbfde3.nq.gz
    ├── 0c61c651198cad4b89a46542ff27df67c53ea752.nq.gz
    ├── 0ce5bdcc0cbeb5232f5d50c9722aa0cb8b1921e2.nq.gz
    ├── 0d88f28718c0a89d71ac11f5dadeb7605f3e9b3b.nq.gz
    ├── 0fa183eccfbb628f4442f9575b2ac5430eeb1b10.nq.gz
    ├── 1074b11016b1f601e396efdb9f748a7a3a4b1254.nq.gz
    ├── 11a949cc0457398b96e95211c016a6518c7766d9.nq.gz
    ├── 12303b1af2185eb29894629b99431fea831367b1.nq.gz
    ├── 127203195ef587e0484a7ec29eded40070b2917d.nq.gz
    ├── 12c419b65b5e12d5899fcaf5b4c4ce50b0421934.nq.gz
    ├── 138fbd91c975c7a32eca2505cb9beef7158cf6ca.nq.gz
    ├── 13dda8c8a53a0f3c68c9354f324d6c8f99979503.nq.gz
    ├── 144871b2a37da074c2135c5caf940b99e6c3172d.nq.gz
    ├── 149e27348e9456d5e107e92e8e501232d2b81533.nq.gz
    ├── 14f8e8b137c33d83d52295357b1dd294a7bf93fe.nq.gz
    ├── 173a4fb5731671a8c5c21809cef40c35e2e821bd.nq.gz
    ├── 180e6f7baa9fb7b28b4de23d467de887d90e30fb.nq.gz
    ├── 189027f9287cb9a91f5f5a1b492ca313923bf85f.nq.gz
    ├── 192be695800037aeecc4840778ed63654eaef094.nq.gz
    ├── 1a3099e8f3a69ec3a3ca2440ef835fa44dff3a27.nq.gz
    ├── 1a564e0166ea93706c0a42c07e38da122741ab58.nq.gz
    ├── 1acdf7cde8971147cf1f8946613e129172b774ad.nq.gz
    ├── 1aeda2f872923e10270581fa3e77beb5973a0295.nq.gz
    ├── 1b7214a13723b394ef1d904118459f8d3879cb82.nq.gz
    ├── 1ba033c1a7227638c1dfc3eb2fcb0c253de0e28f.nq.gz
    ├── 1bdbbc65f02c0787239bbde7414f0f3e470f6145.nq.gz
    ├── 1c5f34da28af3e3fe31b16a3b413ef622da4cf8c.nq.gz
    ├── 1dbbd5bb7c03fc81114f234273b85e88ccb5d0f1.nq.gz
    ├── 1fe69596da33ad53293c57b21df375bf5309dee6.nq.gz
    ├── 2171480ecf77dcc5b66a89806e60a12e1bf4786d.nq.gz
    ├── 217476d9a915d7f6b0fe05437a643089ca500ed3.nq.gz
    ├── 230f0ce453dce04fb59621cefe389abbff8b334f.nq.gz
    ├── 2407e43ea0e2137e62e024ad9966ccd419db4d5f.nq.gz
    ├── 2437f60530d087cc1c5a703e5d8c267a18b0fde2.nq.gz
    ├── 24e7d155002f64438d7f2de033833c9c16700b51.nq.gz
    ├── 26529309454e5ab5025a8040fe9d1320a9d9cbab.nq.gz
    ├── 27b6a4c79391f4707eb380c423fef25177264222.nq.gz
    ├── 27ea42e4fbddad1cca32ebf4f335cb29e7dd31ba.nq.gz
    ├── 27f6b186bb6e1f961af627c552a76bdbd8c0b0ec.nq.gz
    ├── 289d0f6feb361224c317161c4dde63398a5b858b.nq.gz
    ├── 29315ea715e40eb21587d01c2b98f8a8a767bfbb.nq.gz
    ├── 298dad8ff93a873320be203e209ad5bc884a82eb.nq.gz
    ├── 2b72251ff344e1862bc212905cd2a9a0ea2d74dc.nq.gz
    ├── 2cdbc4baff2acca93286e1b4c1b645207f35c71f.nq.gz
    ├── 2d20b13a7ff3435d2b604c37535553aaad8c5fe6.nq.gz
    ├── 2d80c8f3fbc2db7b1913570e07d9c276f483e616.nq.gz
    ├── 2e06201beda50f12086a05e990d98ded3e1f3047.nq.gz
    ├── 2e3f1d81dd7d3398c9956e0f6fd2ecdae54ffdda.nq.gz
    ├── 2f4aae4e28066148ea38f526ea1ffde36d14bd16.nq.gz
    ├── 2f83961eddbf67c762165bb3a527e90b565e29a8.nq.gz
    ├── 2ff23b233f4b83cb384f112c31092c2247e18276.nq.gz
    ├── 3123c467f5c6ecd42100b37c805d71ea9d6adb34.nq.gz
    ├── 315ff860cfa01703ed8ba4f5ec4faa3947722fbb.nq.gz
    ├── 3208fa9aa5d6159cd75c4e3bbfa1ea80d34e705b.nq.gz
    ├── 32401c043bc1e68ad0b64db19fd3bd949c707afc.nq.gz
    ├── 32b914770bd0ac9217734b5b6c449e0cac5ed825.nq.gz
    ├── 33a64ce5ae500e89a73f7b65624d7af7495238ba.nq.gz
    ├── 33c012441a74e03240daafbd4682b64929d75d07.nq.gz
    ├── 33f26b5eab7add85cb5fbfc41597dab37f9d497e.nq.gz
    ├── 33fa38e13b20f1011fe68e3a00d8223e998012d6.nq.gz
    ├── 34797a67d7a3bcbf3ab40b7d1387ce138aa53682.nq.gz
    ├── 34b9bb5a1a52c599734168cc93b754e217e70ca0.nq.gz
    ├── 3503501593a7dcec44a8d9f01f8851c905e3ce98.nq.gz
    ├── 35aa5da2b9f178a23d759f0b575d3fe7d696c614.nq.gz
    ├── 35ab70b987cd21dc440176f73cf71ea5cc6d05f9.nq.gz
    ├── 35dbd656d968c1bf3b7bf59153eeba205b723b17.nq.gz
    ├── 362cb8a943173ebb4c96db9ad4f644ae36c760ff.nq.gz
    ├── 3767473dbda74af37ae587250a02da05f437d9c9.nq.gz
    ├── 378f9252df240f598aac6d434865195aae321c12.nq.gz
    ├── 3837b831ad842cf7cae37ac5d819f45682760084.nq.gz
    ├── 387e1fbc1e25a42bd23d8f06a3965c5e3478e100.nq.gz
    ├── 38902c6433eb1d9f1281f7d68188a2cba8542319.nq.gz
    ├── 38a4334b278864f31727eb857216b33edea73f36.nq.gz
    ├── 391d719c9b8c80cae662806a5ab241266974a26a.nq.gz
    ├── 39529ddbfd807bd0c63b109a64ff8f13e6a7bcbb.nq.gz
    ├── 39a346342f255c2c9be0539183111b3bc0f238d2.nq.gz
    ├── 3a2d21619edc2f96b2e121c4c05f6c07fa9cdb26.nq.gz
    ├── 3a48662fcbfcc96efee817f62e8eb0598d1c55ad.nq.gz
    ├── 3a7ddaa716fcc0df32c2959bc3ea1b305784490c.nq.gz
    ├── 3d2c2566a73b719fcbc2adca131d79cdc5a20397.nq.gz
    ├── 3d9574791336b2ba99c14134b13a5d0e2e1c6d0f.nq.gz
    ├── 3dbc526dfd057c629cf94f479881ab2789f69f70.nq.gz
    ├── 3dee3f3600574ca792a6c8817a8cf981054b8d24.nq.gz
    ├── 3e6b74cbf2415ec6a319bac03ab259f729959d6e.nq.gz
    ├── 3e703e34ce3cb7743aaddb065f2a63409fe49f74.nq.gz
    ├── 3f33a4c760024973677a5ef638f03d63d9f75740.nq.gz
    ├── 3f448b4cea3e1ef90eae0e8078950df4edfa1910.nq.gz
    ├── 402e5fb7ea50559da67971b35d74041b1f0144d1.nq.gz
    ├── 40a44d8ea385e8f73dcdc14b826ba7732518e4dd.nq.gz
    ├── 40e5542aecefe5d098875f2b4a4c513eb2cb7016.nq.gz
    ├── 413cf8ded84be6ae19d514960f9983f46364058b.nq.gz
    ├── 41725da466d76d863f8e8e0e4bff8db905966106.nq.gz
    ├── 41d300e95071ad7d8c8a1c8ba35d9bb7bea92ced.nq.gz
    ├── 4570903fee07b7aa0a55c755e5bf3adbc51f4672.nq.gz
    ├── 467963bc0a2df03555837cfc5de47c912edb5c88.nq.gz
    ├── 46d7ae3a6698dc9c7bf230f908e80f6a8a20202e.nq.gz
    ├── 47f1f723e312b8082474439266b0d7e9659bc326.nq.gz
    ├── 482e67879e8511483d9be194a65fbd1d32d01c8b.nq.gz
    ├── 487fbb3f0c3397594d0ba2a6592972641e2726a6.nq.gz
    ├── 48e462960b3fab4675bdbc2b7a117da313d9e6ee.nq.gz
    ├── 49f6af95176aa089dc717a63c0d08d56ce96f5e8.nq.gz
    ├── 4a2271e32fbc7350b866c2783e035a966cafbcba.nq.gz
    ├── 4cac44b4e4bf95833ee8fddaa641b08e96db1133.nq.gz
    ├── 4d40d1046e586d0c25401533858027facc0f6ae1.nq.gz
    ├── 4e0d71118ee335079fe06f966a740a53530b9ce9.nq.gz
    ├── 4fbd7d1034db399007aa9530b310cd0d66b4ac0b.nq.gz
    ├── 5054129547a13820a85a5473ffaa44be1ac294e3.nq.gz
    ├── 51ee1a375cb846fe09603bdc8109740125b7f82d.nq.gz
    ├── 525912a91d85a7c0a4ce38019ad0059b233e41d4.nq.gz
    ├── 5271887f26db19b7b8946ab459f269f285a79aa0.nq.gz
    ├── 52afa1b7f8795d769126f022831468a0bb72d5c9.nq.gz
    ├── 52e207096da6e33b4833a00c1f2728f7b5539093.nq.gz
    ├── 52f8278806a467ec634b9b8a34878c4d81c1a4bc.nq.gz
    ├── 53fca7d3ff9ea54fc631eb9d7a51d87f2f840bd2.nq.gz
    ├── 540c31c79a5935418044ac0a2ea5134211dfb1b6.nq.gz
    ├── 55ab49620b46624ebd3abe16eb9b5a6c6bfd7d61.nq.gz
    ├── 56b50996a7e1e45e5069352cd823311a451ddc35.nq.gz
    ├── 5726e7db6f9417ffb958d2878c20de60e448366c.nq.gz
    ├── 599f3d608b5c0cc4551e00db7445bc497e8713a2.nq.gz
    ├── 5a2f15c1ba1cb13dcdc26a7587705ad89a120bca.nq.gz
    ├── 5b839e76bc62b0fff83cf2f360e149514ae3fdec.nq.gz
    ├── 5d1c88b946f1f37eb63458542c28dc93920abbc4.nq.gz
    ├── 5d7c650944d1642c566a700f9bc03fad944d8143.nq.gz
    ├── 5eef54acaf1ac3a6289c563eed703222290524dd.nq.gz
    ├── 608ded1ac051435f65b5bda4c8fc7f564cc35448.nq.gz
    ├── 60981e0cdd92bd7a54c06d69e18f2ada3a440bdd.nq.gz
    ├── 612f38d6d5b1d1d4dc8e6dcbd044fb17a8632860.nq.gz
    ├── 6141cd56cfe63ea2ecbe54253d14bddc09657e37.nq.gz
    ├── 61ef312d7c7eef264ee0450210c5f85716fb4578.nq.gz
    ├── 627b74ecdfb3535e5da7ee0735eddcade854038d.nq.gz
    ├── 63655a1d60b418769a8d5f323ffcd6e928506ecf.nq.gz
    ├── 639776734a2f6c0ee748133505146bdf729d4e35.nq.gz
    ├── 63c0f78469df80ea340ca128b28041c35b62ff0c.nq.gz
    ├── 65866c3926f77097d9d8c748de08cff183c4187e.nq.gz
    ├── 65b731cf6ddcbd0945eb89eee7b984cf721f98be.nq.gz
    ├── 666f43de0fe142ab0d78b803be5a2e9d9c587228.nq.gz
    ├── 666fbb26119495a019852043f99bb516437cc131.nq.gz
    ├── 66746c37cb07152b3893eb03e110aa7dfacff82a.nq.gz
    ├── 66b1973c5daab2af555756ebb2c3a4dc0f4b6f4c.nq.gz
    ├── 66d8886421d67d99bf648a3dbf0609a6a44f0e64.nq.gz
    ├── 6776201300cd921b71c247c5837481c2a2648fce.nq.gz
    ├── 677a559e0a002115f3da5cdd552e0788b04b3542.nq.gz
    ├── 67dfbc1fea1c8b4a6aa88a3d498c4acbc4b05d17.nq.gz
    ├── 689b98953423f9c5d8142860ea5bcd2cb210e085.nq.gz
    ├── 68e12bfeb2f5b54a01727873f912172edaee5438.nq.gz
    ├── 6a61c5dc69e40f2607f8eadb224ee616df8a3b6b.nq.gz
    ├── 6ab5ec30f050273497a3a99ca56c173853e36fe4.nq.gz
    ├── 6b3af2b8479f80b6997f03e17dba1ae882e04396.nq.gz
    ├── 6bc3af4f92f85f953c088295f25523e35cd36cde.nq.gz
    ├── 6bd85ad8ea73556befe6b002d2cd3df44748cf8b.nq.gz
    ├── 6c15eb55d3ca85f639b4aefbd2d5aebef4de82c5.nq.gz
    ├── 6cd6b4386bc3942a69f93a428001c2dae8b9222f.nq.gz
    ├── 6ce2a3eae2076a555a2403d45420b7136bd0bf1c.nq.gz
    ├── 6d785263c33065e0237843b4e0387afee4f2d44a.nq.gz
    ├── 6eb5cc0965059a07c09cc06aca24a49ceee08022.nq.gz
    ├── 6eb992edc72e6e2c6b7184fd7669094f05c9f528.nq.gz
    ├── 6ef39dc49e41578dca64cb1a0dca3295ed40ce09.nq.gz
    ├── 705772d674411fd0abf18d5c495667e821db9a55.nq.gz
    ├── 712d2696bef7441d9fb8ee53dddf6228ca524ae2.nq.gz
    ├── 7133ff089f38aba97e06d16447123f60365534e5.nq.gz
    ├── 71697f82b04f6d8aed5c45d47bb57f9a9d5214b9.nq.gz
    ├── 71f54ea6fcf11ce4d650bd2e8f176ceca07481ee.nq.gz
    ├── 7343d0f795d8b1d0c765c3b6d04c8b736062b854.nq.gz
    ├── 735ee025374c303e3517aa599622a35fa32fba0d.nq.gz
    ├── 747ddeb00f5cb80ebaea35606b775d4b6c1bc5e3.nq.gz
    ├── 74a97aa431ea28a435cd1cb346ecc0ffd864c166.nq.gz
    ├── 76a980b6d4e80282faa7df85d0251e67cbb0780b.nq.gz
    ├── 773fda08c19e8283fc36a267c72e655fa666f55b.nq.gz
    ├── 7753c7547254de9421e2854a0456beff81d06176.nq.gz
    ├── 779967ec7f2cbb46cd5a96e1805024b11a1795e5.nq.gz
    ├── 780074f7d0592309e48da53ea5dc3fe70c2d9f0f.nq.gz
    ├── 781c901cef0e791b3a5c428ed6b51de4614057a9.nq.gz
    ├── 78f579786ed2709a21301cb381dcf9737c9d6dc9.nq.gz
    ├── 791d1c5854d05a8843a05b73554261fe9170945d.nq.gz
    ├── 792d6005489ebee62cde02066f19c5521e620451.nq.gz
    ├── 7958919a508aea9eec2160a598c36a00dd0d5c30.nq.gz
    ├── 7ae8f6c73a4b47ec18492ebefed16c63f5f5ef22.nq.gz
    ├── 7c055744a3f0a17b8402f0e321dc022e7f82d6a3.nq.gz
    ├── 7d52f31c0e382ed81cfa7b3ca9279ae37074de6e.nq.gz
    ├── 7eb1c8068a637239876c0f327a55b7791c0f6287.nq.gz
    ├── 7f0bb4ab8b72c494307b612e1138fdb9d2b81f31.nq.gz
    ├── 7fbef49502dc038173ecda9979330557cfee99b7.nq.gz
    ├── 817b301afbafa6443f08174f824437db91bf4cbc.nq.gz
    └── 8252f854afda95861d8f608e6126783b5fe9f121.nq.gz

8 directories, 200 files
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

[malthe/chameleon](https://github.com/malthe/chameleon)

---
*Parsed on 2026-04-15 by [repolex](https://repolex.ai)*
