# Repolex Knowledge Graph of TransformerOptimus/SuperAGI

RDF knowledge graph data for [TransformerOptimus/SuperAGI](https://github.com/TransformerOptimus/SuperAGI), parsed by [repolex](https://repolex.ai).

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
rlex download TransformerOptimus/SuperAGI
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── c3c1982e7bd6a11cfed53c5a193ea502f924b1b6
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── c3c1982e7bd6a11cfed53c5a193ea502f924b1b6
│           └── chunk-001.nq.gz
└── blob
    ├── 001aa88c6e0122d7706eece13b6cea12104e8d06.nq.gz
    ├── 01f7da6ee8804df8a58a3490088a21ad214a2c03.nq.gz
    ├── 027c054cf93f55314d991e489255f0f62e64da5c.nq.gz
    ├── 0304c34ac3f15ef5777795ecb8f28c8fcbcb388b.nq.gz
    ├── 031b941fd4a19f06c189da7611529ce78b64deb3.nq.gz
    ├── 033e7aabc3b3246412aa9f2e81066d99891ff994.nq.gz
    ├── 03ca9b61ddcc1bc1a8de61a6454ed1fce5654fc4.nq.gz
    ├── 04624e797763c3d1cc6bd916511aa83e52819609.nq.gz
    ├── 0474f5fa276b48f07d5ccef009d92152c8c3f757.nq.gz
    ├── 060925fedd448cbcaf7407e4013dfeb23b43be49.nq.gz
    ├── 063a048104275d3d174784265b4f8134feb1721d.nq.gz
    ├── 064c21642d3b19a005d3776ef2243328bc572d52.nq.gz
    ├── 06ae699f22d413ed488676f933b39080ecaca5a9.nq.gz
    ├── 070571bcff360d7a6c5a52e35f55a73c5e1b5f8d.nq.gz
    ├── 075d83290a0a4ffcfdd2da6efe35d80dd65a402f.nq.gz
    ├── 09bf17f3d313ddcd0d270a5b5778a59aed8bb451.nq.gz
    ├── 0ab124dd757abecb1d2169bc95a4a47c586a384e.nq.gz
    ├── 0ac7b90b95ee5befcf4aab0fe8c7e70008e2e5a7.nq.gz
    ├── 0b525b782539b0ced9d9f2477709e73772bb3332.nq.gz
    ├── 0bf5019f8dc4ef746896636d4c07ab49f6c2473b.nq.gz
    ├── 0bfc4218015708b2972a67e56ed49b70959ece37.nq.gz
    ├── 0c3a43e758c44a877c6656a31c52b4025981cd7d.nq.gz
    ├── 0c48d4f35c6e6e6a3c060dfa279567ed7fcca2cc.nq.gz
    ├── 0d5449f5ec7960ff460f4c3a0b3616a16c5139cf.nq.gz
    ├── 0d58006214bf22343cfedd2845f07001e98a725a.nq.gz
    ├── 0e81eae083d2aab87c9e440dbb4371f6dba9ac62.nq.gz
    ├── 0ef8c3ebd60437ab7207a8ad0bddb3f743620f1f.nq.gz
    ├── 0f49bdb0f000cee487cee2f4196d833afd86ccd5.nq.gz
    ├── 10e8aff7566078db1ca78bf049d202cef766ffb7.nq.gz
    ├── 112dc275d4692f19d263d0bf9b663fa854f6c2e6.nq.gz
    ├── 1269ca6784aa14dd6301bca55e842bab58aef433.nq.gz
    ├── 1304b2df420184cc8e90523efea5af86dc397ee6.nq.gz
    ├── 137776cbaec7d40116d99a0fd6c09dc77e737836.nq.gz
    ├── 15153145bdefed391291e696ea6d07de7dcc0113.nq.gz
    ├── 15396bb9598f0b83f97f1fd8b4c40d81d2c59b8a.nq.gz
    ├── 15924c5515284a0d4a95f7e9851ae709d13d8554.nq.gz
    ├── 15bd7ab2235b6dbf7cf79012649eb7c67454eb25.nq.gz
    ├── 162d91b9404c2a842038af1ca9b525617182265c.nq.gz
    ├── 16cf4de3b10c8f0213c60a3009e364ffaa9a2fd1.nq.gz
    ├── 16d38464ad1d887a722610ba5bf9ff76b3d69bed.nq.gz
    ├── 17e4fbe66fdccceb356795ad67d05adde0ecf39c.nq.gz
    ├── 1801102378c5dd3a0ce84c7f9806be4eb9689cc4.nq.gz
    ├── 18c91471812cb6f4c4e8d0fc407f70c4612e1648.nq.gz
    ├── 18d614ce05bc5f3a5199c5c3b9b86ca187d550e0.nq.gz
    ├── 191bfe1c9de2fb12e958eb0cfc795c70318cb383.nq.gz
    ├── 19793fa13a442ffa613604d852387f16230a1a7f.nq.gz
    ├── 19fe1f4adf0b55c69e97332103fd116cb1a6f5ec.nq.gz
    ├── 1aff59ea661c0f3907ec3486f136aaabbe67ccf8.nq.gz
    ├── 1b2cf30a923ee12b1010054af5e6456f0ce20d8f.nq.gz
    ├── 1b65ee7accae50922d967ab8ac959b6514f89205.nq.gz
    ├── 1bc8c7f4613f982e3dfa367562a764cf5bd4c73b.nq.gz
    ├── 1c84561f42ccfb5e7701ddc3840829094e4c94cd.nq.gz
    ├── 1cee61dbfbb920b833b6cf9c1d3dcace11e4f0ce.nq.gz
    ├── 1cf09f4cd3adf5da14ae9c36a17bbdf5977a4855.nq.gz
    ├── 1d57026c770b1b83e5dc26dac59bc727fdf28532.nq.gz
    ├── 1e72aaf7c9b5cffda1179d13e94c9bac45fd8311.nq.gz
    ├── 1f895e78db9606ff2aea4d39d5ec9b869b9e588f.nq.gz
    ├── 1fc9f50bd46c1f6ad5866699d30ef0f911e66034.nq.gz
    ├── 1fca38a2fa0d2b415f0b5bb31510bd96a583f5f0.nq.gz
    ├── 1fd19d7bf9218ff31b27e61a10dff88544e5967f.nq.gz
    ├── 20b4344771a15db258eac84606ddf0ad61dbcf05.nq.gz
    ├── 210c1a51bf9c5134b67f08697fafa593b87a0967.nq.gz
    ├── 215b7d2ed6588c165c407c277981e29718d2d8aa.nq.gz
    ├── 223859d31c6fe0fc3d2271a7eac7d432a7db254c.nq.gz
    ├── 232e168ad86ed3de323a0cc9143cd36d255e7d7c.nq.gz
    ├── 2470bfa6862336c177f53a2da23957c740c35ed8.nq.gz
    ├── 24fd5731dc36e98dd3aadbcc54a2327837c28992.nq.gz
    ├── 270ec22806b6ff1af36275ef075fb7ed76a55bbc.nq.gz
    ├── 272d8865bd6912a948856b5fa2a5ec48335da8d7.nq.gz
    ├── 2730909bf605d8e29522e35959e9f998434bde7e.nq.gz
    ├── 27a0d3107b40e23a0adaa7bbfced4cc9f0ef71b8.nq.gz
    ├── 27c0772fad6f4fadf7c46c1763ddae4501471f4a.nq.gz
    ├── 2834a80f19e5ad2ffd0f0bf251916720cafe525a.nq.gz
    ├── 28e1a21b605c5c642783fe39a49e46f95e21fd0e.nq.gz
    ├── 28ee1df149161dc8568f6969fb2426e584a02c60.nq.gz
    ├── 290342e23c4c54bb649ee6a98d5522d754274301.nq.gz
    ├── 2915949ebd808a251b8c134564c2d82311ff8774.nq.gz
    ├── 297ef8716aaf97dd6a122062aefed5364d0b77cb.nq.gz
    ├── 2a2e4b3bf8ba1c86d96fc2f5786597ad77a0e5e9.nq.gz
    ├── 2aa49a5423668f8bd38dd8b60fc346487776f825.nq.gz
    ├── 2ba46a14879b030c68117f67ed4c1b79bffdabba.nq.gz
    ├── 2c21d136d831f0d52257565cd1b25f7329b82348.nq.gz
    ├── 2c6e581dac340f2cc1c6db5d2514c97c5464cc3e.nq.gz
    ├── 2d0c2bdc8a3a808f81d51c59a1de16ce3ea27932.nq.gz
    ├── 2d108d7d9132b294bcb62b7cb7a4dcec824a9dc4.nq.gz
    ├── 2e50fdb67d7e01e62513fcceb592b56f8de83d51.nq.gz
    ├── 2e5f9386946c1428f64b52e95f5cc948cf2cbdfb.nq.gz
    ├── 2e78bc7cddfa0673521e65144fce53badd999fbb.nq.gz
    ├── 2f5f84355427e08c2f5741acaa54bc2705c14700.nq.gz
    ├── 301da3f05f8d02cd3dbd41c81cb582879321aae4.nq.gz
    ├── 302cfd2ed767a18b6454e44d15cb5798c21d84ed.nq.gz
    ├── 30347b01b60a1141702b858caaf874917cd4df15.nq.gz
    ├── 30394d113dc3a6eaaa4cbc1d62fc7eae6e900dff.nq.gz
    ├── 303b8364a045993575a23f9224fd29bd54c679e7.nq.gz
    ├── 329e5d7030b81d1a82f2c223056152b269383a55.nq.gz
    ├── 32e8dcd841135c87176e366af1e9cb88debf10d5.nq.gz
    ├── 32f39be18169dbb1bb8237932612cffcf73c5013.nq.gz
    ├── 34d11ec814e4b4b52c2d5d9562b8ef25f76cf29c.nq.gz
    ├── 3500dd705635b4352064e65592e4aa73620717db.nq.gz
    ├── 35719d9da74e8aa7cc7e9a4fe32060f460747243.nq.gz
    ├── 35b7946ad7c7ac711cf5f9fb1f440aa6b892a88c.nq.gz
    ├── 35c4c04b844f5bc6144975240eb67579281c07e0.nq.gz
    ├── 36b603ef9e8b51fa983685b78559dbf908469fcc.nq.gz
    ├── 370eeee4f6251797276115c662066a7a0cfcba7a.nq.gz
    ├── 397f3c74ccb1ed8580d567c7509a0e2fc803d6b1.nq.gz
    ├── 39a0089deec5ab96507ae5a3dd0f8546e9726064.nq.gz
    ├── 3a5498ceccca15ba8675e3573bf7fb0b751d3d89.nq.gz
    ├── 3bb345cd2dbf26e33372c7115ecaf5709e2e2254.nq.gz
    ├── 3c7dec055846ee5e3cd996bf712c54b8cc11218c.nq.gz
    ├── 3cd8dc031d3f69eb570cb413f848d91b4810b994.nq.gz
    ├── 3d0d1ff043c44a01436d31131a2a9ebc08e050d5.nq.gz
    ├── 3d2bdf2f7a5f74fd977ea098939793446be8cd7b.nq.gz
    ├── 3d54f624b74db56b28d4c050703144d9b3819d8a.nq.gz
    ├── 3dbcd5cce107ec2e9356e269e9b80404d2d6a538.nq.gz
    ├── 3e6128b2278ff06f61402454ce989d7015e8f864.nq.gz
    ├── 3ecbdc84fc504ee44e0516f7ea0366a1365d9b38.nq.gz
    ├── 3f34cec6f751afe779a716d4cfa165efb86c5f79.nq.gz
    ├── 3f4bce0ef7528445d7c610004ee3047571ab6dc7.nq.gz
    ├── 3f6e05b5b1d868239bdfe81757f52c06cc68f1cc.nq.gz
    ├── 3fcd6b4491b1d9020746090a62d3ebbab85e69fb.nq.gz
    ├── 40e25d82f5b3c6b81388faa8afd708a7ae19bda6.nq.gz
    ├── 40f74ab16ec6f806d54a9689800548dda704de9f.nq.gz
    ├── 41de4968e6be330f9f9513510714f311f60ad813.nq.gz
    ├── 41ee4c6bd3bd4927ffecb7369b5db187e1e0a269.nq.gz
    ├── 4215928458a013b1aa02fc0112695a43d4bd148d.nq.gz
    ├── 4256ab321559221781e5eeed6f35593ac50cdb21.nq.gz
    ├── 425b252119f7d21fa073925b0fa341f4822ff679.nq.gz
    ├── 4395be0d1518bd9c57b9e4ee7905f8bb359cc9dc.nq.gz
    ├── 44c90db50019a9f824bb975a8219ae077c35fa3d.nq.gz
    ├── 4591d327a73f6558a6a28db1fed53b2696453669.nq.gz
    ├── 45e91ee4d568696cdda526a35d24f669af3d8412.nq.gz
    ├── 46d810b0382e20d131399000724f6eb9c163f5dd.nq.gz
    ├── 46da86c64dd1f004820d009c86189b17b2497c16.nq.gz
    ├── 46fd9ae14388033ecdad5944c045e39cffa7be60.nq.gz
    ├── 47267a5858eef4f790211c0bc86431dc716850e5.nq.gz
    ├── 4758cecb873b92dcf70342d3a0bec23acc829853.nq.gz
    ├── 47f83f040043cba2c2c7769402a95e319610e884.nq.gz
    ├── 4845bc5ad34473310e5215dd1d1591681add3f5a.nq.gz
    ├── 4a8153de81887c757938d236d96965cee90e3374.nq.gz
    ├── 4b38103f4c23de004666e0316855db62e57d2ad0.nq.gz
    ├── 4b41c3b03fe6339b29e8d69eee9e0a003d4e60be.nq.gz
    ├── 4b9bce554403ad28272d40db47b5319c61784d08.nq.gz
    ├── 4c9a3430634b8f34f20bca00c56557fc9ea870a0.nq.gz
    ├── 4d66d374c6defa0e0457dbdceceee4d6ee096213.nq.gz
    ├── 4d76ce7043ffc8e3e08d970175b43358acad44d1.nq.gz
    ├── 4de32bc7cb4b6ec60e4bfbc3b351931ea6f7a15c.nq.gz
    ├── 4e5c12903656eb0dc29794fb9d3cf0e4ba359524.nq.gz
    ├── 4eedf86e8cfe2d2858687d5b9410c62f5e58a3d7.nq.gz
    ├── 4f6b9cc15b31403c612495e7fe70d0f77fe01a81.nq.gz
    ├── 4f9d46c43becdb620ac325e558fc851b6810e5e6.nq.gz
    ├── 50af2d98a57f28841ece36ddecc4eee1afa09015.nq.gz
    ├── 51e787bcee261d9ba03d5151163bbe7b736fe436.nq.gz
    ├── 5277a861ad3a901413cecc0b59c8cf95739863d0.nq.gz
    ├── 52a6c00a6b6a6f51a5ce84c96ccc0d30a467d003.nq.gz
    ├── 535bf7f2a8434e67387be92dc1b21588ed215168.nq.gz
    ├── 53846a1d39b61d112990209f69af94bcd8590512.nq.gz
    ├── 5417926c08ee6429891e513257743df5da4414fa.nq.gz
    ├── 54ed66b1fdf8f0ecbcfb7d445e9ca046b9d1ac69.nq.gz
    ├── 54fbacb69a5c87709b5a84e569709e30b137882d.nq.gz
    ├── 55ba710d18ea60b6ea4fe54916e26d8c55f0c9f3.nq.gz
    ├── 55df2863d206fa1678abb4c92e90c45d3f85c114.nq.gz
    ├── 55ec3478a2eb822464aadf380d6dcb54a005613e.nq.gz
    ├── 56b75aab33f1cf2a21b0f9c658ccade07151bbea.nq.gz
    ├── 56df0e285be9689ab1f8ea698ce748e6d1b02af2.nq.gz
    ├── 57cc41c1101c09c9dcb9443a30e8718dba883c75.nq.gz
    ├── 5989926740b66b540ccf6859f99b42c980efb5f9.nq.gz
    ├── 5a9bac05f9697425f668c800ab7ff6f75ab571c3.nq.gz
    ├── 5ad7740b648737dab3613b326957d01e691ea57b.nq.gz
    ├── 5ad917fe2d36296b256856a0f419a6bc97e215b0.nq.gz
    ├── 5b5c5cf9301cc753fff7981b5f748249d21cbce0.nq.gz
    ├── 5b8c1c127c54ae8e7cef439f120fb9fc6efc6860.nq.gz
    ├── 5c1731d3aa5dac6b81c9aceccef8a15e3d16aa66.nq.gz
    ├── 5c57a396326254854e8c4d26a564d2bc04a029ea.nq.gz
    ├── 5cb4df53f528b55bd8e9a5af9e11e4dbad5e6e76.nq.gz
    ├── 5ce81d2110957d778164afadb38831b371dc3528.nq.gz
    ├── 5d9e68b35781d214db0c79006fe68983fcdde459.nq.gz
    ├── 5d9f775a262650344a9e10c4a0cc2322187ec417.nq.gz
    ├── 5e827d506b04e6482ab9ed7a8a62c5804f1d22b9.nq.gz
    ├── 5e8fa01753320eae24749afaf2da3c37aacab5e7.nq.gz
    ├── 6063dd56b5485e3e8897e1e38ea941ae155541b7.nq.gz
    ├── 615a8a26aa98ce26b9fb74b88e6b0c667f8511ab.nq.gz
    ├── 61654b4cace009a265c4a83b4ba1b6b9989fad7d.nq.gz
    ├── 61a2d53834d7d9090917002bd715570260e4fc3c.nq.gz
    ├── 62ace630532d5cc3c40f7bf7c29c297569c25e16.nq.gz
    ├── 632f59083f399f06cb8943059a248bca3cd9a35d.nq.gz
    ├── 634ad8d2cb7ca976789ff677740a3c62c822cc25.nq.gz
    ├── 642f26377df5d113948a57c82dedf4a1734f5271.nq.gz
    ├── 642f8597b60ae9e205d72d4ecde8cce30b6bb5f3.nq.gz
    ├── 64e57b9005dcdbedaccddfdad463f2c846c27e1b.nq.gz
    ├── 6567f798a52c1349b1c51cb81efd869f6b317f76.nq.gz
    ├── 66570367e51a0087c18e4fcc215d0beb1c24e20e.nq.gz
    ├── 66a7086d17e44b4a0a4369e80bcc643ffde70f36.nq.gz
    ├── 6727e63feb1a0aa4917c447296375ee0a9c3c6ff.nq.gz
    ├── 682e50824a4ef45bc567e7d52149d58483c3918b.nq.gz
    ├── 6873933a4be4b43fac4ee6c140e82bb3e7652574.nq.gz
    ├── 68b08279c7a2671fffaa0be2a0c819fc4a88475c.nq.gz
    ├── 68c41783d797dce62b5f9d2183a22d8bea21e97f.nq.gz
    └── 691cbc60d2503e762bbd05f638c58d56c2398440.nq.gz

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

[TransformerOptimus/SuperAGI](https://github.com/TransformerOptimus/SuperAGI)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
