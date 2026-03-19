# Repolex Knowledge Graph of hukkin/tomli

RDF knowledge graph data for [hukkin/tomli](https://github.com/hukkin/tomli), parsed by [repolex](https://repolex.ai).

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
lexq download hukkin/tomli
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── a678e6fdeffa89bd28e4ecc148b926a4e1bbbc7b.nq.gz
│   ├── lsp
│   │   └── a678e6fdeffa89bd28e4ecc148b926a4e1bbbc7b.nq.gz
│   └── repolex
│       └── a678e6fdeffa89bd28e4ecc148b926a4e1bbbc7b.nq.gz
└── blob
    ├── 00046814ae359ca76a48cf9bcc6ad18f87f81ba5.nq.gz
    ├── 00196bb03ea818f196a2de0d95ab7760414b5443.nq.gz
    ├── 001a570d8492563507deb7fd3829afd1d9c0c313.nq.gz
    ├── 003002442866cba465c5a380098ef1fbde9ebc7c.nq.gz
    ├── 00d19f3ad2feeb3f5bf97e48b9d02965c9516567.nq.gz
    ├── 00da544427e29f972a344c5a7124450becd82100.nq.gz
    ├── 0197832b9e5d39473324dfb70a41621bac9a33a1.nq.gz
    ├── 01d4d1381cd57a2542bd98548032fd4d7007bf10.nq.gz
    ├── 01fc6558d5c79e3646a72f53a5ea01f0d41598c0.nq.gz
    ├── 026167ecf54c276968ad1b432bc63ba23e34e715.nq.gz
    ├── 0267e704256754b747acf73378683f77875116fd.nq.gz
    ├── 026e7a92c73316bb2b26b213f85651f1c9c26a96.nq.gz
    ├── 029b70c7971ec6ede115d495904d499a111dd5e6.nq.gz
    ├── 02c09c4241febcacd24df9b7c4e62088ce27353c.nq.gz
    ├── 02ebf13a0c8ce48f5268396c5b480c417a29922c.nq.gz
    ├── 030622807661ec6c14dacde0f0d5522e9c223195.nq.gz
    ├── 03181b1a4553e062233a9318be9032d320ce4de1.nq.gz
    ├── 032edb7266c4332e6a08e451d7ce05d187b7f0fa.nq.gz
    ├── 034efebdfe5b972a63e0f8e3855387913f9579c7.nq.gz
    ├── 0370d6cdb671a0897a416c2ec7d98c654d9ff190.nq.gz
    ├── 03fe3a3e4ffd6650b2fa20d23b424883d1d7f1cc.nq.gz
    ├── 047978e5bc784825b6f92aa5ca8c0827049358c6.nq.gz
    ├── 04ef4fad2f4b176fae1358027d40590c28f8574f.nq.gz
    ├── 0519ecba6ea913e21689ec692e81e9e4973fbf73.nq.gz
    ├── 051ec73136b2b6c2f933a5a380253aa42bb0b848.nq.gz
    ├── 054eb8ac100c8ab1cffa07093181b1727b316386.nq.gz
    ├── 0556547e9836c2fef23841503e69226c18512382.nq.gz
    ├── 05a59303bba7bbaf60323d28a8e72960f705b02c.nq.gz
    ├── 05c0860d11cccd6d0f76610db7762f28872f71a7.nq.gz
    ├── 05ed411aa869fd0dcce9b315d31e4034819fcd9d.nq.gz
    ├── 05f2507ecb687f308c655182da0a1f28d34a18a1.nq.gz
    ├── 0632e9ccde38c0497cee287587b82c79221fe6c8.nq.gz
    ├── 06bfde493370196db0ee5355ce9c073af4c3c272.nq.gz
    ├── 072812a75ef73c191e682cab098a103c756460a6.nq.gz
    ├── 0789e146df6baab46df6b8667d002246ac9d645b.nq.gz
    ├── 08576a817fc6da0e6549263da4941166bafea9d5.nq.gz
    ├── 090b43a79092da8c6dd3f5d2c7847e18d434661d.nq.gz
    ├── 090b474834610cb018e511c9e8aa67ed0a6986fa.nq.gz
    ├── 092da2ff9ea220cc52523d25fffbb57a226a426e.nq.gz
    ├── 0967ef424bce6791893e9a57bb952f80fd536e93.nq.gz
    ├── 099bcd3ff308b0def86584ff5a586c2e56ccda99.nq.gz
    ├── 09a7c083d14f88e9c9aea7b0279535284e3b05ae.nq.gz
    ├── 09abec0015a2abee71da02552b837ac4c99dbc54.nq.gz
    ├── 09b8e099db065f0706a648f40da566b1b65dedc6.nq.gz
    ├── 09f998f4163e1bff9e58278ebd89573819285c18.nq.gz
    ├── 0a1640dc2b77a0b7c228914416c978f740a43699.nq.gz
    ├── 0a4083de557c57a0b1adf17a5c980165feb52107.nq.gz
    ├── 0a566674643806e9aa03f7ff3152d2fe6128e7ca.nq.gz
    ├── 0a6a6a69725c4af727e5f86ecc3436b3b2726061.nq.gz
    ├── 0aae2303d8217b3672286264fded735641413543.nq.gz
    ├── 0ac004695c50bc36a4c509444574801b43055cde.nq.gz
    ├── 0aee16f67c8fbe4e4976fc3ec908f602e8d45b08.nq.gz
    ├── 0b10db3a70eabc7fa1785a071ccb366436004727.nq.gz
    ├── 0b5b4bbfdb74bb81dede09bc2868ff2b201e5ead.nq.gz
    ├── 0b836f17dc0e130fa9d2147d99d9e9f6e1fa3a1f.nq.gz
    ├── 0ba716847945103784dfdfd686346ad54b2b7346.nq.gz
    ├── 0bb5196551a3d74829149338329e28053ac8bbee.nq.gz
    ├── 0c292fcab730d5ee7e3026407407b992fdcabab8.nq.gz
    ├── 0c4b619096ee495f3ba15a56735b30282f7cb830.nq.gz
    ├── 0c9d17f03717cec3412750dd20106b8c2ed9c917.nq.gz
    ├── 0cc36d0d28154acd0cf9c4399a7f3c5b499373bc.nq.gz
    ├── 0d1e7b8b46010c08ef18bab3fea096497f369b35.nq.gz
    ├── 0d834741618f3eeb73841a103b46afa17c1a3b0f.nq.gz
    ├── 0dc5c6c4db355c20d8d46336f46af6505d81ef6e.nq.gz
    ├── 0e06868be98e8468f5bd05c9aa07e0257a8f4781.nq.gz
    ├── 0e12f5e5a1d76543ef591bd29fddd64da11fda6f.nq.gz
    ├── 0f20d18f16b664ceb050c1c3828f902233b7ff37.nq.gz
    ├── 0f3377cd990e3c696738f8e31a7df415505b8763.nq.gz
    ├── 0f53629de0bad163ffe775197510b5f910b5c599.nq.gz
    ├── 0f5c8011ea58f304ad8ade7aed752c1488e8999c.nq.gz
    ├── 103d928bcf7c2f399df2123bffa516431bfa55f2.nq.gz
    ├── 108b21e8beed7700ac65a0cfebfb68c3ee1406f5.nq.gz
    ├── 109f18437379e959171ad4c845882cbdc6821a05.nq.gz
    ├── 10e17783f3cca3b59e6665cc62fa8e300dedef90.nq.gz
    ├── 1103325cbdbc2be1184a9b46b32d79755f4d0913.nq.gz
    ├── 11aa8a35e4b25b5bca3ee2582f28462e6f7eb454.nq.gz
    ├── 126ff2d54f25fec8c8cf24defaeee9bcc6a8ccef.nq.gz
    ├── 1298c2da5166dee563115fdef5de55d4eb35adc3.nq.gz
    ├── 12a84c7f728d296ee3a0e06e5d102b4391b2fe79.nq.gz
    ├── 12bfd60037adc93628df346405bc199b84c05064.nq.gz
    ├── 13570d3b6a9a9a473a23a56af8228564f6ba06d9.nq.gz
    ├── 13697eac9f3a9da420e81f1e4988d5c73e16087c.nq.gz
    ├── 1369dcb114ce2f70caebd2b0bcf0933611d4559f.nq.gz
    ├── 1426f36af33da6f311794c6c024957720a98ef0e.nq.gz
    ├── 1474cc8608b90ace3caae3e5a7b203e14c72a64e.nq.gz
    ├── 14c3df787351b32b526c09ad0c104b5f5b0f6b8b.nq.gz
    ├── 14eaf338507725c27afaecc218d40a01e91a5326.nq.gz
    ├── 151607371298457f1d6c06758b9259da9e4f7c43.nq.gz
    ├── 1532d79a590c41fa87f4e51fe5348ef2b790f987.nq.gz
    ├── 1548b5ea30a7b41f40597cf3cd947a8aed5add7d.nq.gz
    ├── 154abadd5c3eb6d4d83c9147cc44a415111e4698.nq.gz
    ├── 1577c9bd194271947a155ada35fc2098099cf23f.nq.gz
    ├── 15e2b84b86494290c93822849937b63281a35743.nq.gz
    ├── 16254cf07f3621bcbb15f0320c6e9635fa7142d2.nq.gz
    ├── 163e7bbe3ba8a83a74f27d594f3f135f76583a1c.nq.gz
    ├── 17a9361b3fd7c1f04cba6e72d98aa63bbc8c18d4.nq.gz
    ├── 17e774e237c46481b87d3df0140b28fdc19437dd.nq.gz
    ├── 18bffe10c25d3a22f65028cb051da12bac8186fb.nq.gz
    ├── 194d8166795ede0fbe11a2aff905848e0a593314.nq.gz
    ├── 194d9e61880ee9d7ba6f490f7a6f4bc3a895b98a.nq.gz
    ├── 196e854b0336d4dd1f704a69d452479f43c17f81.nq.gz
    ├── 1a7289074ed131de598a6a296121779e2102615d.nq.gz
    ├── 1b21ae449adfdfde7b28d68142219a2a2668682f.nq.gz
    ├── 1b5bd092c5c54e408681c5bc215f34136f9d6029.nq.gz
    ├── 1bdf17a00387a186f130b0463037dd63c0502954.nq.gz
    ├── 1be4a5f8ebe68faa1b5d8b770b7cfbdb993ae4ac.nq.gz
    ├── 1bed5eb37a7282f1fde0d6fa44a0f733cc8312ba.nq.gz
    ├── 1c1370b6496a574649f5a4bc44d4cbea6e19c1c3.nq.gz
    ├── 1c1bf63b94bdd337d42a8dede8377eaad14ceeef.nq.gz
    ├── 1c2a56444406ded2e81b1a637843a6e2f66db438.nq.gz
    ├── 1c2ee7619f8d9485fdd8a35c94a291d7759ed204.nq.gz
    ├── 1c3c34b8571fa58ca31d741440b9921b7c7c8eb6.nq.gz
    ├── 1c5787ef727bf435dd31468c33ecf4c0f728e0be.nq.gz
    ├── 1cae3a9b18d2c736ffb720c75b535038d6bb2e06.nq.gz
    ├── 1cdb181a5205fa9bf548d7cb4e9b9b806672003f.nq.gz
    ├── 1d03d0be133e0460d24cbde920a3f6b8cdd52bbd.nq.gz
    ├── 1d3f2d43f467e9d313d8737b06d346b2ce40ef44.nq.gz
    ├── 1d9cdf6a437faaaa797b19970f1733d949ffe2ab.nq.gz
    ├── 1db2639639b8f163e8e0fe5cf90253c819ce53e3.nq.gz
    ├── 1dcc2c84b95b0ee3c980cc2168da9b9d421fc227.nq.gz
    ├── 1dceaa6317205886bf4fa84b34f11f8bb565ce14.nq.gz
    ├── 1dd0199b023c397f8d9ca48f3fcfad28e44a9e2c.nq.gz
    ├── 1e09a8bf78d684892e3c056cb584722c66c12807.nq.gz
    ├── 1e158fe1c421879cfb90b85b516324f4fd563d8d.nq.gz
    ├── 1e4ac8ae37bc58627d9cc639a1bac2c6115bd9b3.nq.gz
    ├── 1e5ac12d3ceebe41be26069c7c95d6776cf62b43.nq.gz
    ├── 1eb1b5c52928fba6e6c72ffe250612486a3f6447.nq.gz
    ├── 1eed83331d8df2c856e578e80e8656ea1cafd6f5.nq.gz
    ├── 1f04108209eb3636911747e8e1bb41af92ab3e24.nq.gz
    ├── 1f66348b237161244a40a38f5fbcb78aed58bba8.nq.gz
    ├── 1f80fbd1dfb36fe7b2da81394b486300287f011a.nq.gz
    ├── 1f8709ab9f46f7312d2eb04fef672ce0b2027f85.nq.gz
    ├── 1fd099d3683e2ccf48cfda86366866fa0ab0f709.nq.gz
    ├── 200220ad93ab517118d20f668ee206f373bb0078.nq.gz
    ├── 2003e3b228177129c25b5096b887d8de7f6eda44.nq.gz
    ├── 20b4aa7c98df57d4f617aa052cd411540a6117c0.nq.gz
    ├── 20d9895ea6f466fd8e5ce9c9a43ca7d1d4e893a4.nq.gz
    ├── 20f3835b707d60f4d27a3eeaac8e84f8363642f8.nq.gz
    ├── 218838a73e4c44a0abe1a23d9bfcdf840f4061e8.nq.gz
    ├── 22544a081fea000e7ce3b1ea515a1d012edfca28.nq.gz
    ├── 22697a2bf1fbae6d6ce91341585ed1936d4c6316.nq.gz
    ├── 22927931ae1c76c3863b3a87a4888bd534f3ceba.nq.gz
    ├── 23036b876401a46577f0d9807ee1f28f6bf28a8c.nq.gz
    ├── 2317adcad4e4bb8f1c1b310ac88c4b96a2edf1a5.nq.gz
    ├── 23585e65b6b89119d494173978cc739e62c6f05f.nq.gz
    ├── 238a0b7ceea3535e23e24e421cec69e65e441f77.nq.gz
    ├── 23f530030d608a5625c0b3d02754085fc33a732c.nq.gz
    ├── 23fc99986edd5ac65fb77cb683cc86d4f8fdb607.nq.gz
    ├── 243398569be313f12048f1142acb671b434731c7.nq.gz
    ├── 246d7e91fe4fb16ba1f2b3f89294fbff0c6ea1c7.nq.gz
    ├── 249786d8984b96cd74f2909843bc79fa7b67957d.nq.gz
    ├── 24f2005c615eff9b13624ff347997f4d6350b16a.nq.gz
    ├── 2540d252776b3e31850c2717eae9ffc41f340512.nq.gz
    ├── 256e6c08d5304ab8f670de9d4d9f38e6c532e32e.nq.gz
    ├── 2576f1bd5331ee2d8dc5bd6c064a887006908b61.nq.gz
    ├── 25a037894eb0fc9adef5fa3ef69547dd087b7662.nq.gz
    ├── 25c02e73da2905d84e07c80d6f73382eda0d5b81.nq.gz
    ├── 25c5e683c14a213b92ca9077ede752dfeb0c7831.nq.gz
    ├── 2624c1d5453ae6a74e4df508cf0286ed4a8bdc40.nq.gz
    ├── 2655cfd3ab0bcee9b1fa269cd0ee3137fb1daff9.nq.gz
    ├── 26d1668f4201d6daba206418e3e5bdcca3bd4856.nq.gz
    ├── 26d17ee1ec15016a4ccd04a15e0d249be78c92af.nq.gz
    ├── 27077c0d2ebee6f16c0b4786800ef209aa3dd4af.nq.gz
    ├── 2725bca0006db42c8ee38c15dfa290bbe57f9a94.nq.gz
    ├── 27369a5e2d3bbba835b527f313b9c219dbdc43da.nq.gz
    ├── 27fe86f36775e505c143697c69f5f2272fe87efe.nq.gz
    ├── 2906e258cd02c7113b95f87ddae32303eadc1dcc.nq.gz
    ├── 296cf9d68fa1bd03c7fd4cddabe1d22767561764.nq.gz
    ├── 2997c91cfaa873abc16a6d7581140dbb98b6299e.nq.gz
    ├── 2a20d8c905954cf9c5527231f3637bc6f3a01953.nq.gz
    ├── 2a9645509a79e30976e7c8db967e5c4af8b4a6bc.nq.gz
    ├── 2aff00cc58409d5762dea2c4596784e11dd17447.nq.gz
    ├── 2b32de3bbecf3a97eee1cc7a305408c2787352e7.nq.gz
    ├── 2b35093ef5573086319251b92c614c1df938c265.nq.gz
    ├── 2b724b03f683abe4973130cdf6ad7e2500fc39df.nq.gz
    ├── 2c0cb4efb33f0652df1077ece0d46aea2565ca98.nq.gz
    ├── 2c85d56ccf869d77f47bd742debea6da003ab5ff.nq.gz
    ├── 2d2913a3959707fb3114003caf841ac07b90ad92.nq.gz
    ├── 2d7b2426cdfd33b6c8a0970492745d6c135c634b.nq.gz
    ├── 2d80143d8867bb90e7e4e866d0cd0ad7c928d39d.nq.gz
    ├── 2d85110f865dbca5ef5913c914a1591add9106ed.nq.gz
    ├── 2d8d0b4cb8028a76db91a0455d23fc054577541b.nq.gz
    ├── 2d9404b1ebb78062e82e742dde69f906e0d446d6.nq.gz
    ├── 2dbdf4ef94594b71a24a395a02940ea815e822af.nq.gz
    ├── 2ebcaa8fba16d559af62fd4ab1ccbcc778b791ff.nq.gz
    ├── 2efd659b8d8e9ccd57ce64b33c271c23221de4b2.nq.gz
    ├── 2fc5b5569634d5cc16386dce5aedb0dbb640a0cd.nq.gz
    ├── 2fccf269cd88cd7422108034ab024fd252128532.nq.gz
    ├── 2fdde6b526f64bfb95c489ec8f68e79f5ce46a05.nq.gz
    ├── 3038891afec8d4e6608ae4209365cf31f94b7f41.nq.gz
    ├── 304b89aa4ece2cf51c332d3ca44eba042a85b7ad.nq.gz
    ├── 3132fb1c722542a7f28c24779c46fa62ca3f990c.nq.gz
    ├── 3157ac981d37991ea98e6191aaac27b6983d2c60.nq.gz
    ├── 31ff67e4233d080b8f666bf3bb57870ad8c1c2c6.nq.gz
    ├── 32322c451ea0e3aad1fa17fb63b0d17b9780706e.nq.gz
    ├── 3277caa95f4ab0c332319badf26aefb7426a3c97.nq.gz
    └── 32cbe7924b480dbf4e2b69117b97f01c899e265f.nq.gz

6 directories, 200 files
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

[hukkin/tomli](https://github.com/hukkin/tomli)

---
*Parsed on 2026-03-19 by [repolex](https://repolex.ai)*
