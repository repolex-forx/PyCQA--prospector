# Repolex Knowledge Graph of PyCQA/prospector

RDF knowledge graph data for [PyCQA/prospector](https://github.com/PyCQA/prospector), parsed by [repolex](https://repolex.ai).

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
rlex download PyCQA/prospector
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 58a90fc31b081621b75fa88f2e0c8cd906d0e012
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 58a90fc31b081621b75fa88f2e0c8cd906d0e012
│           └── chunk-001.nq.gz
└── blob
    ├── 013e4b7ec4eaa42e6c73bebdf41ce3e357bc6153.nq.gz
    ├── 048b6bfe80506ce3b56168df85c2bf69c1b378dd.nq.gz
    ├── 05a7a1f6ebfc9d4e0369aed911d335ff4f70591f.nq.gz
    ├── 089af1dee24274acac49dc4a74eb25333b52c69b.nq.gz
    ├── 0bbd85bca26e3a1ad5d2fa67acb6f264d80ad331.nq.gz
    ├── 0c9d0928e7ae3a6d158e6fc40c940856a9a92da6.nq.gz
    ├── 0e6b870a6f9b116b3b367e2091f63361f32e13ce.nq.gz
    ├── 0f6eacdb74977defdbba635ce18be5e198c2394f.nq.gz
    ├── 10e14c42e948e36e2eedd9c632f61af7eb5ec1f5.nq.gz
    ├── 12a4831439d2280ab062b88d0ae502dab92afc53.nq.gz
    ├── 13419f81b5972085435d3414f4323407b9d245bb.nq.gz
    ├── 159c0fb39f7a852bcf59a553ab609d3ca6a5556d.nq.gz
    ├── 15eea908548e46b1c81c7f570972fff5c10c100a.nq.gz
    ├── 16592afd84cdf8c904498bdf92dcb12ef4bc30ea.nq.gz
    ├── 16b2a4e9cbd2a566b0241a1db9d3d5a2347f15ba.nq.gz
    ├── 1773da40725797bdc1f35bca593e93c7ba275b30.nq.gz
    ├── 17ea552b496e0318977617115153dfc1c2a3a343.nq.gz
    ├── 1825e027f9d0658339104ba5689d10aaacbbfcff.nq.gz
    ├── 1878368bba2541d7aa4a5c254ed0b10331d0af77.nq.gz
    ├── 1a9c6b0c623d5a58b241ea7354926c426dd24369.nq.gz
    ├── 1e286903eb5af587bcd117143c773cbb95975408.nq.gz
    ├── 1eaea122055236c08427a80fb18e8a004298131c.nq.gz
    ├── 219d5c29d4f23142a16af41fea90571a033a06bd.nq.gz
    ├── 233b5b3c079eeea4ac11f8681553646af96487bd.nq.gz
    ├── 2364fb6f7a490e600e3ef7f9fc131904f9f7c8f1.nq.gz
    ├── 259104a07fc49892956ec33d1c890bae5b1f1178.nq.gz
    ├── 25ab6a2a8e6324c801c9926795e4da0bb9e6ac94.nq.gz
    ├── 286736f9ecdf09262087554c01174a3ada461695.nq.gz
    ├── 28e7c4aad1f81b996ca2c4f47cfbddaf0f4693f6.nq.gz
    ├── 2a287d36bb9348485687cdcf8e57df89e128ffcf.nq.gz
    ├── 2b993c2beaa5eb339e22919298b24d796397a706.nq.gz
    ├── 2c1bba9361e8131c349908e1a47af5d776c744b8.nq.gz
    ├── 2cbe4cca708e2f6f3007b676e8ebc374756b58b2.nq.gz
    ├── 2e77d90c20e4ded538543ca92c11496c5b9cf186.nq.gz
    ├── 2ef6ebf381a0e251eb311a3e55aa6e4b767346e0.nq.gz
    ├── 31494045e94416c1b3f3a9683779b206210bc7ee.nq.gz
    ├── 3205b89e232e4b3ec9400f8ed906ef2631d9bf74.nq.gz
    ├── 340b49ceb27389f3ad13196f7b8d72e5e6ec73e5.nq.gz
    ├── 34bdfe1155809e7b89e72e116903e7f90002b599.nq.gz
    ├── 369f13d952795850e2189faaa444bab5baea46b8.nq.gz
    ├── 3890d31dd97d8a6dd9a194d7a170edb4bcd0bfd6.nq.gz
    ├── 3a7145236cc493bc40d3c7a00f790a3759c1e85f.nq.gz
    ├── 3c18eab144e0e134ddb0140e469fa4c18bcf5c23.nq.gz
    ├── 3d20c03f0cf0cc3581b99d534cd93f39d6785f03.nq.gz
    ├── 4126d0405afa97d29748428dd54a60076a400f7f.nq.gz
    ├── 4265cc3e6c16c09774190fa55d609cd9fe0808e4.nq.gz
    ├── 42e492a1231c96b39687f4986540abbf2eedb514.nq.gz
    ├── 43820e96e86b15b15eb508a0e5859a35729e53ee.nq.gz
    ├── 44895c830673fe892d4640b7b2257200387f6db3.nq.gz
    ├── 46c5ea7dcbed76a2d51a28520d042c5db6c5b495.nq.gz
    ├── 4a3d7161203fd1b64473df1cd5ac53070a747691.nq.gz
    ├── 4a4980ceffc0ea82b7d134ac5dc2e2b04999c9bc.nq.gz
    ├── 4a54e0551646542688bde431866bb274d5882df6.nq.gz
    ├── 4ae375671d6d3b4a6d30694b40c84a0de3090f7f.nq.gz
    ├── 4b5e1c76206a978a64137833435ae73fa2f7a7ff.nq.gz
    ├── 4bc59fd4cae56ef14993b3972ebf5ace3c54b2b5.nq.gz
    ├── 4ccd77e7a61fce1836b9e7922c8ea126f34f9c30.nq.gz
    ├── 505354164632a661c42aba6beb3c7e269f7d9360.nq.gz
    ├── 53b3214ed8146a43600b4ff7c5595595ce4cb6eb.nq.gz
    ├── 53c52f83672fbfa0d69deb04f6921448dc2407ef.nq.gz
    ├── 566a867d2f9f2ef7bd4946a2b2943ab1778334a1.nq.gz
    ├── 5769e1e4e18b90219a513b8548f7fcc39920bbb4.nq.gz
    ├── 58e7acb30069f5794c939fb020b29269c2486596.nq.gz
    ├── 5a1af7a9fe40b52144f1c33939f21ddb1e909c95.nq.gz
    ├── 5a599e1212a4ea5bcf7f67c41412cefe9b356a86.nq.gz
    ├── 5a7977b7010e418a8e60d7aea0fc7a5e499e15b3.nq.gz
    ├── 5a87f587382400a2a072244bb7a191d0c7da2cb0.nq.gz
    ├── 5ba39a26a0f2a58fc835126a40db53733bad6dec.nq.gz
    ├── 5bb1d6a4a9647c96f11c3154b9ca61499100a272.nq.gz
    ├── 5bb99011994ea36aaa2912f8a07f414b16635537.nq.gz
    ├── 5c186577545e57cf916f16cdfdf0b037211e6c9a.nq.gz
    ├── 5cbd064c980c8f8fe9fed102334e17efed8357d9.nq.gz
    ├── 5ceb5faa1cfccfe87336859a41c109731d5698d2.nq.gz
    ├── 5d3ba40cd672bf7d485073b2fd590f4638a6560b.nq.gz
    ├── 5daa07da103b4091532f82e668dd86f1276444ea.nq.gz
    ├── 5df2eb8ce30be3e7e70d1ecea25e8fcede0341c6.nq.gz
    ├── 5ea235ec16eb48615af2bb16788b3a59e53832b2.nq.gz
    ├── 5ebc361961a87ffc81161403544f66eb8b74f590.nq.gz
    ├── 5f058b47c030a7836cb5eeeff0a8c46f7d41883c.nq.gz
    ├── 5f2aa5cce537f3be24b095a6032ef54010768ea8.nq.gz
    ├── 610a8ff2f067082d353ab3b85727420460500e96.nq.gz
    ├── 61118cc5ae09b7dfe5ebde5c51c2cabc9b8b7f6d.nq.gz
    ├── 613685b50c2d7ea568b2f3db3cdc214d93e92204.nq.gz
    ├── 614466aeabacd06d34c43c5d6c8f2a0dc9124f46.nq.gz
    ├── 61bcd79446a947c46225d89bdd1be74ce52f396d.nq.gz
    ├── 631cc67d12139bca569a43044bc5362f2ae9572b.nq.gz
    ├── 636907165d5779e98a9f2a06f44a471c6662c788.nq.gz
    ├── 6433e5bdf97c740cfa79d2307a454b308a11b575.nq.gz
    ├── 64e947dc7d701af056c9075df228b1b614bfddbe.nq.gz
    ├── 658f727d911983504bba74437bb50d2b9073b2fa.nq.gz
    ├── 659910d19811d199db229892388e4c851d7c3236.nq.gz
    ├── 65e23a794f1bd45c64f8b656f4e118d142ffeac4.nq.gz
    ├── 67e588d6601c97d8d24724140e3a8bec93796804.nq.gz
    ├── 6c8394a637a8a547b889ed9bd8383a47fe184f64.nq.gz
    ├── 6d4d240fa2886813fb0185479fbb6ffd8c8ee7c3.nq.gz
    ├── 6e548ee185ce97171e9372583b1b486274f8b630.nq.gz
    ├── 6f63ddfcc754d28f94ab446818de8c6bc04f1c8e.nq.gz
    ├── 703e54e807840d1a4ca1d8ea5d78060ab1525100.nq.gz
    ├── 71e1460f59683b83a3ce4a5f76b29a3c2ef47d3d.nq.gz
    ├── 720c82d0ea64f305c501beddf7c702cfeb2e51c8.nq.gz
    ├── 722178703041676e8ef05e48e57501e41c3b1e4d.nq.gz
    ├── 7331fc4ba82d8b23a7c3ab16fd65c77d048c3f93.nq.gz
    ├── 77d3221e66d896057df4dd7e89708d54e16d9c25.nq.gz
    ├── 79ef3361eaaf25f593319dbaa0cd8b3fd70a81ce.nq.gz
    ├── 7b59faffb87d12b7868b44d6490666a631cddb06.nq.gz
    ├── 7b980caaf26287fe6c800ea4f07e8973ce9c7d26.nq.gz
    ├── 7f303ee4ccd911e7df983abdd8000a343999d0d3.nq.gz
    ├── 7f3915be3149dcdae2cab8e3f1e84fbb1dd8131d.nq.gz
    ├── 7fca9ec1a2ef493bc9ff3f0a22d854f2ab2d4438.nq.gz
    ├── 801bdbca3d10e31e8de15f7caa846c7c8ec11582.nq.gz
    ├── 81f521f97e5fb8dd8eede7a23c7b5bfd1e41b3f8.nq.gz
    ├── 81fefbca76cda97953a5227c1a05ccd488cdc1b0.nq.gz
    ├── 826d1a7b77d8fae69fdbcee3e0c118ba2843fc2b.nq.gz
    ├── 8379f74caa7a9efd9ac474b5379f57e78c2dc3cd.nq.gz
    ├── 85980e09d394cbe4c7c21d318512ce2dde9f4834.nq.gz
    ├── 860dcb45308ba6a92e635cdf72a05746f395fc68.nq.gz
    ├── 88059d8b6369776b8ced9d42d2ad53a0792f0a7b.nq.gz
    ├── 888762552421471b5d1400ef8e1288ca43991444.nq.gz
    ├── 88e633f606cffe9667589cb137db2bede0ca4fff.nq.gz
    ├── 8900d7b3fe4e6db74be2857f3e0e0ddc06e6198a.nq.gz
    ├── 8b8d18fa3c7e27b0ec026087a1d9f49812fe5dd0.nq.gz
    ├── 8e33da3c6408612de8bffe0e77d038140b220496.nq.gz
    ├── 900de0c367d09d33425fa5b6dc80fa377c910e98.nq.gz
    ├── 902fee0659d4755adab5d178302376e88c33b1a3.nq.gz
    ├── 9035613f908b2b9287412976a270345923743386.nq.gz
    ├── 90630394bd784f1de6e29ce2e0ff7789d1ad2fad.nq.gz
    ├── 90f25ab6563a0c8c54414ac8638a328ede601a60.nq.gz
    ├── 914fd7ed2a4bc115150f7a56698ff4f502f05383.nq.gz
    ├── 91c3c483b00a6b985aed70042907cdf1e3583cb0.nq.gz
    ├── 91ea04c3d65e1ca7ba835950fbf87cdf41c51b7b.nq.gz
    ├── 92c05770b8b9660d5a1120ee32e55996ce3bef99.nq.gz
    ├── 92cbbd991d491f190fb94f987f8c85948387e2b3.nq.gz
    ├── 92d70531112d3834889dd1993fd549229f44b62d.nq.gz
    ├── 92f884a9083a68a1d689ecf01f94af2a71e558f1.nq.gz
    ├── 931c83802d5af256719400beb257e080cbab309b.nq.gz
    ├── 94b0a716ef77cb00d594eadd4aac84c7f381e146.nq.gz
    ├── 95c2a194b561864350eafd824c463a13f3368d73.nq.gz
    ├── 992522c7b7c7c0884327562c2a171a5c5e03587a.nq.gz
    ├── 9c19d076267ce3f5c1170e881daf8748936485f9.nq.gz
    ├── 9cab7916b2106b24fc391c7ce18f6331da0d2e1b.nq.gz
    ├── 9ea9a5aa4d05e3062e923e273609d01ce0af9bef.nq.gz
    ├── 9edec8d0e2225389317bdee19c7b2acf29563a5d.nq.gz
    ├── 9eec637fa6ed2d4eda9e66906da0957f17fa000d.nq.gz
    ├── 9feca8b765934eca0cb44c0066febef20eafa7a1.nq.gz
    ├── a0da760451bae357593339d7d3b3340826f0e860.nq.gz
    ├── a18a4b63a0ee715c27679e6109414f12dd8c8484.nq.gz
    ├── a3dc32cd1d425ea97ea01eaaa7e91cdc93b3bd77.nq.gz
    ├── a98fb515cf09fb5e8f5e6ad54595143a2cc8b047.nq.gz
    ├── ab615e49035c5f2d109f351154ec2a6d93cc5e40.nq.gz
    ├── acd503fb3cb7e7533cb65620643be22dc0c5a85c.nq.gz
    ├── ad6f754999ceb5b104e0a2bea9f49794ddd4ae7a.nq.gz
    ├── aee5bbe6b0863a10709ebbbe195fac9176196a4d.nq.gz
    ├── af57f742a35b1e020224edbc66df081e206dd70c.nq.gz
    ├── b00e56d42a6d6cd80dfd5355b71b148d39610d94.nq.gz
    ├── b4543493b5e9e25565ab85304a0b66cfb9401301.nq.gz
    ├── b456eec782242ace657ee6e10874a4dbfe62a3f5.nq.gz
    ├── b49c1d07f9f0d4a9483108be7cc8e02629fe877f.nq.gz
    ├── b53929678eba526f4f057b075350b6f0594f3222.nq.gz
    ├── b85a3fabf4db0216ee30587c1aa1d6fc27771c4e.nq.gz
    ├── b85b7a0f5442ad93c8d83c6a4edc7a5844e82bfb.nq.gz
    ├── b98204921d985c7d25303450657e08a728fe1fae.nq.gz
    ├── b9d9d2ddad7e3e186fc1da39520316c317c60c34.nq.gz
    ├── bb70a50ca744793b51595fd416f583f9a8690759.nq.gz
    ├── bbe6fc2fd06abf514ca9f3cf7cfa134479d35644.nq.gz
    ├── bebdfc600f0cb03456a43253065df11cab7a89f0.nq.gz
    ├── bedfa8fc5250e995e1a8b380687d534f1f51e778.nq.gz
    ├── c04328e4d7555dfd774f4d8f47b336d8d50a6bb6.nq.gz
    ├── c2ab344bae7ee66ec7637f801ec2de84e8c192ed.nq.gz
    ├── c367ba6dc97675420fbfba3f94ffeb85ce804791.nq.gz
    ├── c48e0c199df51bf74d2562dcf4f364877ee06c73.nq.gz
    ├── c4ffec41773d9231e1bf6af3c5fd5f7690f19e24.nq.gz
    ├── c628554f400ab73c6e0cfcc4d323cbf2f5cf0f80.nq.gz
    ├── c63d9b0375d6ff55b38b2515cab52ee7cef29db4.nq.gz
    ├── c85a6f17d9ea584693804616ef62d5b45fd50eb5.nq.gz
    ├── c8876c3e3ea967bc8d68781d52bdcdc45c17f0b6.nq.gz
    ├── c9bc9a83c8ddcc1c2ebc0a0d4fc765c4da1dae63.nq.gz
    ├── cafc510deeb99667eb5be5febea431a73f3ea3ac.nq.gz
    ├── cb2434bbf80318516ebf1579ed16db5b2718c191.nq.gz
    ├── cba80d7ca79efae893398aa737d7eb2d4b3d28f5.nq.gz
    ├── cc726c259465099a59f22c391b137d85ea8dbdbf.nq.gz
    ├── cd01de259eeb8eec83c3f961cc3c4608efbe7be3.nq.gz
    ├── cdb95a30ef78d47e50d5a7971820a5095d8dba5a.nq.gz
    ├── ce5566dfed20ea7a57377b23687ad741d38ea0c6.nq.gz
    ├── ce8d4089264dd4fe8bb04868df120904d28159ad.nq.gz
    ├── d33fbb1b424e6858ba666551ded690299dbddff5.nq.gz
    ├── d351584c77d50a2acdb0f0d16f31205cd461744e.nq.gz
    ├── d533bed3b253799fd1737944812f728feb7903a1.nq.gz
    ├── d6e2cf8e5d50b0b46d6c73ec0bcb5c2020041692.nq.gz
    ├── d871288a214c00de07e52324a761306bb40a07c0.nq.gz
    ├── dc39e80daaf61b40446d7a949afccde3a22bcc71.nq.gz
    ├── dc6b111208c31c434299473f215cd2fd46a4e80c.nq.gz
    ├── dc8cb981224ca6d9ba64379ce96c525412f42f13.nq.gz
    ├── dccdc882cab41a3f69d4a511646f28aef27a2461.nq.gz
    ├── ddb784c1bd973ad8abff80f9b16c491853284854.nq.gz
    ├── ddd8da9e06b90197c99ae26d3dc17937c22f4b66.nq.gz
    ├── df826d11ce65bbf79bcf8d9ae93eda2b8d2061ea.nq.gz
    ├── df913e834988bc77d314bdcd7002e13ab3ee26d3.nq.gz
    └── e075ceb092d95547854179987b69a3545e7ff848.nq.gz

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

[PyCQA/prospector](https://github.com/PyCQA/prospector)

---
*Parsed on 2026-10-12 by [repolex](https://repolex.ai)*
