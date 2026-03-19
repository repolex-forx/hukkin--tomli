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
│   │   ├── a678e6fdeffa89bd28e4ecc148b926a4e1bbbc7b.nq.gz
│   │   └── ec0f3f9d1f0c8d70a4fa927f71368a5f6d420f3a.nq.gz
│   ├── lsp
│   │   ├── a678e6fdeffa89bd28e4ecc148b926a4e1bbbc7b.nq.gz
│   │   └── ec0f3f9d1f0c8d70a4fa927f71368a5f6d420f3a.nq.gz
│   └── repolex
│       ├── a678e6fdeffa89bd28e4ecc148b926a4e1bbbc7b.nq.gz
│       └── ec0f3f9d1f0c8d70a4fa927f71368a5f6d420f3a.nq.gz
└── blob
    ├── 00046814ae359ca76a48cf9bcc6ad18f87f81ba5.nq.gz
    ├── 00196bb03ea818f196a2de0d95ab7760414b5443.nq.gz
    ├── 001a570d8492563507deb7fd3829afd1d9c0c313.nq.gz
    ├── 003002442866cba465c5a380098ef1fbde9ebc7c.nq.gz
    ├── 00411dd95fa56eadeef3e6e8ad487206fd2803ac.nq.gz
    ├── 004135598c1e645e6d285adfd8590ba24a362ece.nq.gz
    ├── 00aa2f8325ecb5099e31af7b28577e3d9588b5cd.nq.gz
    ├── 00d19f3ad2feeb3f5bf97e48b9d02965c9516567.nq.gz
    ├── 00da544427e29f972a344c5a7124450becd82100.nq.gz
    ├── 018cb0fafdb7a5669b34a99c7192463434ca9b8c.nq.gz
    ├── 0197832b9e5d39473324dfb70a41621bac9a33a1.nq.gz
    ├── 01a56a51d99765b05aee08bfd2fa9e18279bcaa9.nq.gz
    ├── 01d4d1381cd57a2542bd98548032fd4d7007bf10.nq.gz
    ├── 01dd8812232541e5f9a2175aa49eeec30519ab1c.nq.gz
    ├── 01fc6558d5c79e3646a72f53a5ea01f0d41598c0.nq.gz
    ├── 022b096ee44b899339a86ed3f3e49031b0ca4761.nq.gz
    ├── 024db2911c9f8d12209e5f3571e3f7f24ce31acd.nq.gz
    ├── 025b02a177bcef58c18895d7e74a026f62d07df1.nq.gz
    ├── 026167ecf54c276968ad1b432bc63ba23e34e715.nq.gz
    ├── 0267e704256754b747acf73378683f77875116fd.nq.gz
    ├── 026c93a8b8d78285d84b954950dfe6a2dd2e8bd3.nq.gz
    ├── 026e7a92c73316bb2b26b213f85651f1c9c26a96.nq.gz
    ├── 029b70c7971ec6ede115d495904d499a111dd5e6.nq.gz
    ├── 02c09c4241febcacd24df9b7c4e62088ce27353c.nq.gz
    ├── 02ebf13a0c8ce48f5268396c5b480c417a29922c.nq.gz
    ├── 030622807661ec6c14dacde0f0d5522e9c223195.nq.gz
    ├── 03181b1a4553e062233a9318be9032d320ce4de1.nq.gz
    ├── 032ebcc247f1a0e216b3a880c4bbd7cb06064c0c.nq.gz
    ├── 032edb7266c4332e6a08e451d7ce05d187b7f0fa.nq.gz
    ├── 034efebdfe5b972a63e0f8e3855387913f9579c7.nq.gz
    ├── 0370d6cdb671a0897a416c2ec7d98c654d9ff190.nq.gz
    ├── 03ceb5a248db9f2353ba78bbd784114dfd0e8185.nq.gz
    ├── 03d0e0d3966fa46eaa7dc9a696ca4c5ec137168e.nq.gz
    ├── 03f8618cdd67b3d1f0aa091807cb51a2f0af8b94.nq.gz
    ├── 03fe3a3e4ffd6650b2fa20d23b424883d1d7f1cc.nq.gz
    ├── 042895fbdf88b968e4d2e3c1d2c3f255fea1f976.nq.gz
    ├── 047978e5bc784825b6f92aa5ca8c0827049358c6.nq.gz
    ├── 04d2dffde1005ba34414040591d5d62b47c47ba4.nq.gz
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
    ├── 0704ba7fb06a5c099e609158ee9251ec8f75703d.nq.gz
    ├── 072812a75ef73c191e682cab098a103c756460a6.nq.gz
    ├── 075bf505464b5528ebfb2b7c41cafc5be7055242.nq.gz
    ├── 0789e146df6baab46df6b8667d002246ac9d645b.nq.gz
    ├── 0804919f10a544854971dfc01e313fe785723a89.nq.gz
    ├── 08576a817fc6da0e6549263da4941166bafea9d5.nq.gz
    ├── 090b43a79092da8c6dd3f5d2c7847e18d434661d.nq.gz
    ├── 090b474834610cb018e511c9e8aa67ed0a6986fa.nq.gz
    ├── 092da2ff9ea220cc52523d25fffbb57a226a426e.nq.gz
    ├── 0937f8dcba24f279a4942579f61c543a0dd4e632.nq.gz
    ├── 094fb2cf64c892c5e29df853311f66a25a6f80a6.nq.gz
    ├── 0967ef424bce6791893e9a57bb952f80fd536e93.nq.gz
    ├── 098e7df265245e8ebf8799ac872617643984666a.nq.gz
    ├── 099bcd3ff308b0def86584ff5a586c2e56ccda99.nq.gz
    ├── 09a7c083d14f88e9c9aea7b0279535284e3b05ae.nq.gz
    ├── 09abec0015a2abee71da02552b837ac4c99dbc54.nq.gz
    ├── 09b8e099db065f0706a648f40da566b1b65dedc6.nq.gz
    ├── 09c3b4f7a7554527f1b628e96f2897ade7bc568d.nq.gz
    ├── 09f998f4163e1bff9e58278ebd89573819285c18.nq.gz
    ├── 0a145eca67e9e62802d14a715c8c9d99bfe99555.nq.gz
    ├── 0a1640dc2b77a0b7c228914416c978f740a43699.nq.gz
    ├── 0a1a684345a50424cf2155932a2207bde59f3aca.nq.gz
    ├── 0a4083de557c57a0b1adf17a5c980165feb52107.nq.gz
    ├── 0a566674643806e9aa03f7ff3152d2fe6128e7ca.nq.gz
    ├── 0a6a6a69725c4af727e5f86ecc3436b3b2726061.nq.gz
    ├── 0a96cc54d8009d70e648fbe56c45109613b2141c.nq.gz
    ├── 0aa1722f790c279833a9dba78a336194c8d0b522.nq.gz
    ├── 0aae2303d8217b3672286264fded735641413543.nq.gz
    ├── 0ac004695c50bc36a4c509444574801b43055cde.nq.gz
    ├── 0aee16f67c8fbe4e4976fc3ec908f602e8d45b08.nq.gz
    ├── 0af7025e71403caf497e4f6714d3d17dc147bc8a.nq.gz
    ├── 0b10db3a70eabc7fa1785a071ccb366436004727.nq.gz
    ├── 0b5b4bbfdb74bb81dede09bc2868ff2b201e5ead.nq.gz
    ├── 0b74664ebaa58e6c268ba1c7221b6369e2c11247.nq.gz
    ├── 0b836f17dc0e130fa9d2147d99d9e9f6e1fa3a1f.nq.gz
    ├── 0ba716847945103784dfdfd686346ad54b2b7346.nq.gz
    ├── 0bb5196551a3d74829149338329e28053ac8bbee.nq.gz
    ├── 0c1af395184e0b15be925b4a75a799833c9ef1dc.nq.gz
    ├── 0c292fcab730d5ee7e3026407407b992fdcabab8.nq.gz
    ├── 0c4ac37e0a95e4dbaedf947d1508af8aaa9f1ffa.nq.gz
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
    ├── 0f4abca5506ad0a6f4671f059cf6e2c4d4617734.nq.gz
    ├── 0f53629de0bad163ffe775197510b5f910b5c599.nq.gz
    ├── 0f5c8011ea58f304ad8ade7aed752c1488e8999c.nq.gz
    ├── 103d928bcf7c2f399df2123bffa516431bfa55f2.nq.gz
    ├── 108b21e8beed7700ac65a0cfebfb68c3ee1406f5.nq.gz
    ├── 109f18437379e959171ad4c845882cbdc6821a05.nq.gz
    ├── 10d48ab843a1387623a9c32a97cb0b1b9d968064.nq.gz
    ├── 10e17783f3cca3b59e6665cc62fa8e300dedef90.nq.gz
    ├── 1103325cbdbc2be1184a9b46b32d79755f4d0913.nq.gz
    ├── 112c0c9772aca100ad1dbd708262babd9959acd1.nq.gz
    ├── 11aa8a35e4b25b5bca3ee2582f28462e6f7eb454.nq.gz
    ├── 11fa444073cfb4d3daaa2dfffc9df0b9dac0000a.nq.gz
    ├── 1200f99f6e8293ac2735609861bf8d43e6c8a3e2.nq.gz
    ├── 123f173beb3ac7282059fe64bca9f8e60d65ac68.nq.gz
    ├── 126ff2d54f25fec8c8cf24defaeee9bcc6a8ccef.nq.gz
    ├── 12796e9bca1093dec7451f398e17b50027c59670.nq.gz
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
    ├── 155de0f65d1e7a10aef75a4ecf8e1048f9c3f6cc.nq.gz
    ├── 1577c9bd194271947a155ada35fc2098099cf23f.nq.gz
    ├── 1582c5b88ffbf26eff1cabf6243644d686832582.nq.gz
    ├── 15b11434ff00960720b8895d4678703e8204f5a0.nq.gz
    ├── 15b43b1d0a8ead6e9763601c00b1bc6da097d568.nq.gz
    ├── 15e2b84b86494290c93822849937b63281a35743.nq.gz
    ├── 16254cf07f3621bcbb15f0320c6e9635fa7142d2.nq.gz
    ├── 163e7bbe3ba8a83a74f27d594f3f135f76583a1c.nq.gz
    ├── 166e7ff23debb91445ed24f24f1a5cfdc1fb7d6a.nq.gz
    ├── 16c331ed3983adc8e6cfdd9eab79c9b981876907.nq.gz
    ├── 173878300e5d24c586cf6bcab0722c8e11b9e18d.nq.gz
    ├── 1757a9c380cba0c7bd57f02b70cf9a6313bde3f6.nq.gz
    ├── 177861624d6b531187e0325ac38b097ab34b6fa9.nq.gz
    ├── 17a9361b3fd7c1f04cba6e72d98aa63bbc8c18d4.nq.gz
    ├── 17e774e237c46481b87d3df0140b28fdc19437dd.nq.gz
    ├── 1833d61c55973ee9ce1c6691b2e5bb0f1331c324.nq.gz
    ├── 187c9fd57d9d7b801f1375f5a3dae9ffe90cc28e.nq.gz
    ├── 1884b6d864502bb1ebe12a68c72944dcf0e0a87f.nq.gz
    ├── 18bffe10c25d3a22f65028cb051da12bac8186fb.nq.gz
    ├── 193dbcd76f41616cdab0d9664f8123627c0c24f1.nq.gz
    ├── 194d8166795ede0fbe11a2aff905848e0a593314.nq.gz
    ├── 194d9e61880ee9d7ba6f490f7a6f4bc3a895b98a.nq.gz
    ├── 196e854b0336d4dd1f704a69d452479f43c17f81.nq.gz
    ├── 19a047d43575a66ef16e4bb7aef8a8b17bbb692a.nq.gz
    ├── 19c2897dd256f8335c8d5dca576a4560f2e33c71.nq.gz
    ├── 19c3210fd939e35c47d9a32faca0c8d3fd732b40.nq.gz
    ├── 1a20ef6d674f68ff80e8352bec579fc08d75a03c.nq.gz
    ├── 1a7289074ed131de598a6a296121779e2102615d.nq.gz
    ├── 1ac9eafcc45ae17e4bb1ff22ce51daac2e4e9d40.nq.gz
    ├── 1ae858707264bf6bb97fd7b8b13622c205c51395.nq.gz
    ├── 1b178b48458ef7c5ec941b682a93aba09128dd8c.nq.gz
    ├── 1b21ae449adfdfde7b28d68142219a2a2668682f.nq.gz
    ├── 1b5bd092c5c54e408681c5bc215f34136f9d6029.nq.gz
    ├── 1b6d9f679cd88451d95d244e8eb38c0317dba30a.nq.gz
    ├── 1bdf17a00387a186f130b0463037dd63c0502954.nq.gz
    ├── 1be4a5f8ebe68faa1b5d8b770b7cfbdb993ae4ac.nq.gz
    ├── 1bed5eb37a7282f1fde0d6fa44a0f733cc8312ba.nq.gz
    ├── 1c1370b6496a574649f5a4bc44d4cbea6e19c1c3.nq.gz
    ├── 1c1bf63b94bdd337d42a8dede8377eaad14ceeef.nq.gz
    ├── 1c2a56444406ded2e81b1a637843a6e2f66db438.nq.gz
    ├── 1c2ee7619f8d9485fdd8a35c94a291d7759ed204.nq.gz
    ├── 1c2f2e5312966d9456309d73265528d151b2a76f.nq.gz
    ├── 1c3c34b8571fa58ca31d741440b9921b7c7c8eb6.nq.gz
    ├── 1c47be9fd508bffb4786cde87164c8c7fc0545c6.nq.gz
    ├── 1c5787ef727bf435dd31468c33ecf4c0f728e0be.nq.gz
    ├── 1cae3a9b18d2c736ffb720c75b535038d6bb2e06.nq.gz
    ├── 1ccdd686e905fa760cfbd184f20c12ac62760ec7.nq.gz
    ├── 1cd867567b9dc3b0366dc9401849684edbcf10eb.nq.gz
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
    ├── 1eda5f61ab1c354c50137c17ae1a1c7a6d050fbf.nq.gz
    ├── 1eed83331d8df2c856e578e80e8656ea1cafd6f5.nq.gz
    ├── 1f04108209eb3636911747e8e1bb41af92ab3e24.nq.gz
    └── 1f1f36bff11b9d263e6ca8be6bb1da0ee3a9bc84.nq.gz

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
