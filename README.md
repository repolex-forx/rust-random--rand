# Repolex Knowledge Graph of rust-random/rand

RDF knowledge graph data for [rust-random/rand](https://github.com/rust-random/rand), parsed by [repolex](https://repolex.ai).

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
lexq download rust-random/rand
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   ├── 29056a059ef1d97b09e3671c1cdc244cce80885d
│   │   │   └── chunk-001.nq.gz
│   │   └── 2c43268c8260cad21d171b94807e6cd8b96e50b7
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 29056a059ef1d97b09e3671c1cdc244cce80885d.nq.gz
│   └── repolex
│       └── 29056a059ef1d97b09e3671c1cdc244cce80885d
│           └── chunk-001.nq.gz
├── blob
│   ├── 0278248a708773671bf17a22549e4c3b8f0448c2.nq.gz
│   ├── 02ece6f98ef77b34d8aabe6ed2a72610951e6244.nq.gz
│   ├── 040cd05cfed911cc1aab6aa55ab6afb5cfffd6e9.nq.gz
│   ├── 0a5591f396d5c4f11d14600829f4cbcfd2bd3bb5.nq.gz
│   ├── 0a5d1497acdfb4b7bcc02c537be9db6520189d62.nq.gz
│   ├── 0ab7458377f38f545dddfa25d7af82eaff1c0495.nq.gz
│   ├── 0e6bf9a1e18e6bcf36c37cc2751843ac95790bf2.nq.gz
│   ├── 128c21308e7a93bd8aa9d6356766059222a2e8d9.nq.gz
│   ├── 147303d44a767dd8b5b390c2d3d6d1cf8d396d14.nq.gz
│   ├── 16fe87b06e802f094b3fbb0894b137bca2b16ef1.nq.gz
│   ├── 17d74680f8cf2d2571d1d5873cb4d14cc6b12246.nq.gz
│   ├── 188f48ca19a4ab1c9f3f3f4165ce62b81d7865ad.nq.gz
│   ├── 1af35432e5c6c6c08ae95767f79d82d20b5392bc.nq.gz
│   ├── 1c02992b2d7b8d8ae113a7336825b06a74344504.nq.gz
│   ├── 1ce01fdd0f2611b06876ca86159108dd6142c8a5.nq.gz
│   ├── 1ed59ab1503f11c3a868476d55d27a0cb8045158.nq.gz
│   ├── 2006f4176fa1ca3a258a9a441bff8e80df2e6cf4.nq.gz
│   ├── 2091d6c3d292c9fcc9dc1bcf85eb74bce6fed1de.nq.gz
│   ├── 209adf21c8b9c4c1a865f3c664f34dbad7b514e3.nq.gz
│   ├── 21823f50d8b57645902b8843682255e03a237e82.nq.gz
│   ├── 22a5733f37f932976b709d7c1a0722ee70361e81.nq.gz
│   ├── 22ba4a05d323e54e402bc5ec106169a59ae8410f.nq.gz
│   ├── 22e08ae6b655966daf7143ccbc798292cb637bd9.nq.gz
│   ├── 266651f10dc78b84ab0cb8e572754e66236b6cb9.nq.gz
│   ├── 27116375fd4ad37ba71326746e2cea700cf19336.nq.gz
│   ├── 2caf61a289d6e0f10f1393f89fdf51e54327d4e1.nq.gz
│   ├── 2cc2029141f956c07e48f090d80b19473b20eb24.nq.gz
│   ├── 2db9ac1fa2c6bfad026c1fb7172a43d99e36c19f.nq.gz
│   ├── 3047e9236df75df02d418eeda93b1b2c570a032d.nq.gz
│   ├── 30b095c3cffb74c7f095fcc1998afb29b8a0de8e.nq.gz
│   ├── 311a41b29d8f9168f765e6b66187fbf6ef7904f5.nq.gz
│   ├── 315a5b06095d1087a76a9173bf970b06fa34c0af.nq.gz
│   ├── 33ea382d38322d192bc85bcacc8e254227fcf541.nq.gz
│   ├── 3596c775345c92695c83e550547212a820650207.nq.gz
│   ├── 36449c0c826d1378764d5415056a848c1574f6bf.nq.gz
│   ├── 376bb95e741af08c9d6b195c0c41ece5fe80b4a4.nq.gz
│   ├── 396f5880e02b8c39065092a8efcf7241db0e95d7.nq.gz
│   ├── 39c779f40cd364fa0e214b029de91a9cd4155940.nq.gz
│   ├── 3a41450227a305a18a44a171c9cc1fc1c14fd53d.nq.gz
│   ├── 3af4e86fdec419c19245bafc28af7fb5e4ecda3e.nq.gz
│   ├── 3c386e8629c475626fdd044f28753d35b0583541.nq.gz
│   ├── 3e8f8b03eff49399dbb970e391dd895f9b1d57b6.nq.gz
│   ├── 3ea72c38424a995dbd84306f62e06462f31a4e21.nq.gz
│   ├── 4018361648ef578ca84408d3fb03bba09c31861e.nq.gz
│   ├── 40986863482606beae148a9f31e2d950dad64070.nq.gz
│   ├── 40cea06e1e4b7d0c81332dfd6f4352060b84cfc0.nq.gz
│   ├── 4542a3b6f9dad12d6b0a6811ace36f1f95191e91.nq.gz
│   ├── 467e66f98b69f5a9b45b6e7fa38bfd285b4914b9.nq.gz
│   ├── 468d907caf99fb0cc0dcbb3c322cbb69f740ffd1.nq.gz
│   ├── 46c3483d94419d96ab9a6786768f0ae4f33300a3.nq.gz
│   ├── 483714f9bf549e59ec137bdf09d70d0d6795923a.nq.gz
│   ├── 49c53e6fbfd526033026f18e2f2cea558f320d48.nq.gz
│   ├── 4b589f268981ea0276100310638b1581dba32803.nq.gz
│   ├── 4c671b8aad8d261a23a9b19b308cbf96813d5296.nq.gz
│   ├── 4f4a0b7a3d980896a0486036a1926ad14bfb8599.nq.gz
│   ├── 5238339a0266e58f5e3d632a605c87adee643662.nq.gz
│   ├── 53b043c4a33ed2e5934348a7dfff28cd2c6bc6d9.nq.gz
│   ├── 56cb9c225f79970ee0529273d58e6f59e62c542a.nq.gz
│   ├── 56e75b600cdc74ab68b3a568d4fb70ba019a33bf.nq.gz
│   ├── 57de284be632d616a213e70fca3618555601e95d.nq.gz
│   ├── 5863a1a0ff972e7e61896d19c55c4a6e9b48c727.nq.gz
│   ├── 5acbadb3acc550390bca8aef8ac6a79aac66dd70.nq.gz
│   ├── 5b7e3c3a691cb68a1aa2e80bc1f79d71d4be0b10.nq.gz
│   ├── 5c2cd97c21f48fd2cbdfc28f736f4ae423190489.nq.gz
│   ├── 5d8fa23b3005aa71800059d67b502f40300ca61b.nq.gz
│   ├── 5ddca3f2284ae0945bac7d4ee164c4f964f46d7f.nq.gz
│   ├── 63bde3670606dd3fe41c71b9397387f6d0bd9f04.nq.gz
│   ├── 649e081787c23f56db07c9170b237ea33a19f597.nq.gz
│   ├── 657136395f4ffef97752cbab510ae066fd58440a.nq.gz
│   ├── 659ff26218d1729400765ef3af11d888664ab042.nq.gz
│   ├── 68acd2f07994ba9a5e28c51c389d12971b5046d8.nq.gz
│   ├── 69a0ce7cf2a58de8c226c0be752784a6d45f28c1.nq.gz
│   ├── 6a47b86341798a374e7c24f3ecedeeb5bded66a4.nq.gz
│   ├── 6b0e7c6cf33059174d1df4dfd85152329a8a089b.nq.gz
│   ├── 6b2aba351783be7c2cd6ed1f576de51f260b8797.nq.gz
│   ├── 6bb708a82a2f216515d3fa51a345851d6350988a.nq.gz
│   ├── 6ec047348420347f806b315bcb0313997b0fb298.nq.gz
│   ├── 6edf27dbb3cc47be020ca78aaa8b804c2cbfc663.nq.gz
│   ├── 6f967f5ee242fa6d72d98122d5466b82dd39019e.nq.gz
│   ├── 71cf73c903347828067212ef61803e471698bcfb.nq.gz
│   ├── 7380f702ebbc76910c437bac00888a97bf72d981.nq.gz
│   ├── 75b350053f3f2d2df299c1a925b863080b0c3558.nq.gz
│   ├── 7808bafee833ff3353523c853f66dc9d3e593e7f.nq.gz
│   ├── 7af1e50ff0fc96b4276fb16a4b7b0189569013ba.nq.gz
│   ├── 7b68b35cf6217355773743e0437008780ca62284.nq.gz
│   ├── 7cbd61249fbac95dbf4b673a0c4c4f412de0466d.nq.gz
│   ├── 7d4b88cae1d58cfbf3990700d813566497c283d9.nq.gz
│   ├── 7e8f0c9ba3218873bde467b9a6a1120d19558823.nq.gz
│   ├── 7ecdeae32e40b8ce2c67775e4f07cede8460d9cc.nq.gz
│   ├── 808bb67a4ef17d23944c240ebac15ff4bf77de53.nq.gz
│   ├── 83224890b05b9ceba380946c90c5520e8f9c5e8d.nq.gz
│   ├── 8483944c09a7297205186bce3cd30d2ea59bf77a.nq.gz
│   ├── 84cdf21a58c6d2faad24d3750b76916e2ed39742.nq.gz
│   ├── 852a850bd3ce803ecbc66078e8e9d609eb80cce1.nq.gz
│   ├── 882754fae4445ca97ef827d67b496c5f823e35d6.nq.gz
│   ├── 88cfdab6ba233ffc486cf6e5686f46b07e5def5b.nq.gz
│   ├── 88fba026f24535ab402e5f4289ad5a45b8c208ca.nq.gz
│   ├── 8a8354bd5d3c4fb0271eda1234efe5375ed9b03c.nq.gz
│   ├── 8c90f4e4bd2651b9134e27a41b6aefb6ad4920a9.nq.gz
│   ├── 8e0c361259484119ddc0094304065c58f7189348.nq.gz
│   ├── 8e1aea1158cfa0088fee6432424c7ff5c38d2ee0.nq.gz
│   ├── 8e3d0fb22fc953f08a3855264eb08c4fe5cfc078.nq.gz
│   ├── 8e636e18175ff2fd8211e22bece8050f7d0fef68.nq.gz
│   ├── 8ebe6b8ec1fa8a62dce698b234a82878b6bb4f7d.nq.gz
│   ├── 8ed8c50289a72385494e44d6ca83ec46eb140ecb.nq.gz
│   ├── 8fbf33b96c60b8a8f8b402ce738e818d1264f652.nq.gz
│   ├── 8fc290aae993394c92b9fcf7f727242a81207e0f.nq.gz
│   ├── 901462ea7ca3276c785fd81da90ebfd9e4f1ffee.nq.gz
│   ├── 9090ab8250acad7cad36dd595a92976eeb48cb82.nq.gz
│   ├── 90c57c87bcd80d1be9978d4284f35f5c85bb9357.nq.gz
│   ├── 961dc27d31b729430ca83e81b0ed1abc5012863d.nq.gz
│   ├── 96b94575ae6a021c1cb37f4e99d8bc0fe7ef9ebc.nq.gz
│   ├── 97abc2f206e1e60420e08d8b8d0e247602e7de09.nq.gz
│   ├── 9af0b9e535cc3d8c0afaa9c131c610bcb0b85c60.nq.gz
│   ├── 9b8f2081acd5044a4706afe2ff4bcbf8f39ec851.nq.gz
│   ├── 9cb257b85024662623fed1e5e7a7b9ab1aafd6fd.nq.gz
│   ├── 9d61627a3efa1645b1d9395886e09d0ac6e3bb00.nq.gz
│   ├── 9dd6c0a1ae60cf490d5911b5b6d9a72cbed2e693.nq.gz
│   ├── 9f4bb7e3edf3c8e00324e58c0a0beabe8b231b60.nq.gz
│   ├── 9fd6e999ecc8a0481150ea78c9d884737014bd27.nq.gz
│   ├── 9fe58394aefc36a508783ec863ed39debb86bbe0.nq.gz
│   ├── a02fb59b165bbdf59ae2313cf8de45fab3f2f900.nq.gz
│   ├── a2ae496a60ddb7e5bf36310705ee38485867849a.nq.gz
│   ├── a320f48f441f5fc1f24c39a7068f7b0e2b4bb007.nq.gz
│   ├── a355bbcdf571ade637e0d9f90f8bde8154461836.nq.gz
│   ├── a3e76cabdc9bc90e7e8c16d4a42abb5845c3d7e0.nq.gz
│   ├── a4cfbeed61d20aeea2f5bce63009025a05d186d4.nq.gz
│   ├── a5e040c076988b8ebc8c209749a88ed0b3a19b55.nq.gz
│   ├── a629d7d8c72e969fd83e6a6ad8f6881ced174d68.nq.gz
│   ├── a63ab18147eeb68098f1e7f56a294ab7a8b1de80.nq.gz
│   ├── a7b4ebc12673d8333ca60eb9774ef4d817414399.nq.gz
│   ├── a9b82fdde0508a7feecc57fd1abf9093cce7bb68.nq.gz
│   ├── abf3243c10f89c98636c1fed36b276f099702a6d.nq.gz
│   ├── abfdf798c06b423ab234ee1db8190e404a6e94b9.nq.gz
│   ├── ac38e8174a6574dd3fe349f39a23ee25f82d3824.nq.gz
│   ├── b188dd675ee95ae82d50faaa73df10d9b9dddcbb.nq.gz
│   ├── b1b89e0ff594fdab4d957587ec2de5662991a46a.nq.gz
│   ├── b2ff499effa5dfec06c0d8a16e4c9fbde70856af.nq.gz
│   ├── b35f06919848847207f5e3f3a32876332e6873c9.nq.gz
│   ├── b4081daf355a05a489444a5f3088ad6d75868ef6.nq.gz
│   ├── b54fffacab2835c2ad637dcd4a2a4b8f98beb8ca.nq.gz
│   ├── b5a97f52fadf2017307682327d76ea80210f4f12.nq.gz
│   ├── b9042c04f52fb55f0e8f7239d2c656bf51c85617.nq.gz
│   ├── b9d43e91be69f4f167a66ed6e896ffa8ad607c50.nq.gz
│   ├── b9fef23012bc713cf031134efa099cf6749e5049.nq.gz
│   ├── baa3480ccef6e3a6744b9378c9058d759361930d.nq.gz
│   ├── baf65ed07a7a9f5a506421b4505df271de975512.nq.gz
│   ├── bb4ce0fb9fbf570251382e222fe24516f9e89f67.nq.gz
│   ├── bd011d57d58275a7af14cbecb2cd9ea6dfc220b5.nq.gz
│   ├── bda523ad48547551b098eb00d5eb9348c2bd02c2.nq.gz
│   ├── bdd4ba0f3c94bd339d37846752560cd0b65d168f.nq.gz
│   ├── bf7c8a2746549f9fcb113e2a882c5dbe959fe029.nq.gz
│   ├── c11c305ab17af6ea234cb47fc89a07fdd1e5df3c.nq.gz
│   ├── c16c63f3c4b76e590bdd055f68ab232d11564162.nq.gz
│   ├── c1ae665147b350dc84e4d07575f52330e9311833.nq.gz
│   ├── c37588067ba74887f1ffcac50155f310d811d2fa.nq.gz
│   ├── c8010e28c10d5f02848775c656431edf647b986f.nq.gz
│   ├── c80befdd48d861090290a0b2d67d74a689e9e845.nq.gz
│   ├── ca1ce30410f26cb3f27ac2710ad7c0c88ae8a4e0.nq.gz
│   ├── cbe4a59c592f4d7d93585d43c179e045b748c398.nq.gz
│   ├── ce3098a16987a35eb4cfc135f367d710b88a3135.nq.gz
│   ├── cec9bb1f50561e7f24f4fd77ba741d776c033f85.nq.gz
│   ├── cf656074cbf6271db6b819562629ac28bc7023c6.nq.gz
│   ├── d05e1cc9ee7f7876ff69b30bb9efbd4ef770a13c.nq.gz
│   ├── d0d9d976ed3663f061a7df1abb24cf438a23248c.nq.gz
│   ├── d242f972606c44bd668fbcdd5828fa37f1d75ee9.nq.gz
│   ├── d46f058e98ccef0251fa2625b29d799680502759.nq.gz
│   ├── d58fa752599855a143b06c08e47e82759c2e8bf9.nq.gz
│   ├── d8e0189f223de492f712440964b20d75ebd4ad08.nq.gz
│   ├── d93b5baf341d9813bb48a51f42a7e8e4af89ec52.nq.gz
│   ├── dd0bbfbdf29ab7aa693f41d768a4f0dbbeaaf01b.nq.gz
│   ├── ddde3804d71494ffc1a9a14bf8f747242aaa2536.nq.gz
│   ├── dee4ed11e6be013ca2426be0b8c894111425a0f5.nq.gz
│   ├── dfdd6928ef0ac3689d38a3308aa38708c3e814a1.nq.gz
│   ├── e05bcc1dfa3b68550f85b7eed1afdf54af5fa731.nq.gz
│   ├── e2aa157f7e7c91600fb82b51d996cc38f9623dd3.nq.gz
│   ├── e374bddf321370d3335a277066c0e7fc748ce38c.nq.gz
│   ├── e52af5f25fe6cfc1f61726d64c64d8a3558d7e86.nq.gz
│   ├── e83c1746420f845c9adf592b0e7a010d415a6a42.nq.gz
│   ├── eadd0563b05128ab5c81024c24f17122b5258c4e.nq.gz
│   ├── ec88efe218f5bd8352b47289b9f240a07fd6527b.nq.gz
│   ├── edc91223295fb624557a50f07c2a03f1d1c68cc1.nq.gz
│   ├── ee23a1db447a46d7b752e42dd113cef7a3414016.nq.gz
│   ├── ef0b4bff66b1182d5b24a5538f61d08a56832232.nq.gz
│   ├── ef344a6196f0de10739294478391fdfaa9670ae3.nq.gz
│   ├── efc72fffd57f825aca784210f1c0ad0872959c7d.nq.gz
│   ├── f9cfe8029c861b441e8dcf968fa406f592e19dee.nq.gz
│   ├── fa6bc68ccf50f5567add09e0f39f501f8db31e06.nq.gz
│   ├── fadc6dcdeeb5c8199de1d8641ec4d0710087eeea.nq.gz
│   ├── fc23a57d960e39f09999d7eb249f03b4becdb141.nq.gz
│   ├── fe47f2d41616cf2c4c91be9d1827b2bc7508b1c2.nq.gz
│   └── fead913ba1d7a34fae8b87046f4477c5c0c563b6.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 29056a059ef1d97b09e3671c1cdc244cce80885d.nq.gz
└── filetree
    └── 29056a059ef1d97b09e3671c1cdc244cce80885d.nq.gz

13 directories, 200 files
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

[rust-random/rand](https://github.com/rust-random/rand)

---
*Parsed on 2026-09-08 by [repolex](https://repolex.ai)*
