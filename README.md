# Repolex Knowledge Graph of scverse/mantispy

RDF knowledge graph data for [scverse/mantispy](https://github.com/scverse/mantispy), parsed by [repolex](https://repolex.ai).

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
rlex download scverse/mantispy
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── c28373f7b32449d0fef7c92076957265b76feb61
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── c28373f7b32449d0fef7c92076957265b76feb61
│           └── chunk-001.nq.gz
└── blob
    ├── 03121db62a5e162f87c24da929e0a0d35d2d42fe.nq.gz
    ├── 04975e61b97485b26f2045065be5d2252bc49190.nq.gz
    ├── 04d0ca599dfd92627c5a1f61b5108b175f700473.nq.gz
    ├── 05c9b864a88a41d29af79e7591058347e25a488b.nq.gz
    ├── 07bcba4cb67d317a2f7c6214f51d927dce6292a0.nq.gz
    ├── 08b60c983a279aa2862898ea67441c4290d69729.nq.gz
    ├── 097290196f13e69310d49e10fdb6c06c83a4df7c.nq.gz
    ├── 09b7201a4d425dc6f88694d837885bb4c580ae87.nq.gz
    ├── 0a2ac76f9ce572b0b8123a5cc638c7e2b8e0353c.nq.gz
    ├── 0bb0d2a22a7457f6cc0a4fbd6238ff5cbf3642c6.nq.gz
    ├── 0c6c6530e2a5f77b6996dd8941872a10539fc6a3.nq.gz
    ├── 0c735dc5c0777955c51739f55c7211797d7e4ff0.nq.gz
    ├── 0cca7d1c593d652779527e6294bc6f8c7c459a83.nq.gz
    ├── 0e23e23878ec396febc9e8177b301f5bd5c08e09.nq.gz
    ├── 0ec79e5f1a7f15cb2a1c13ae33f4eea71cbdcecc.nq.gz
    ├── 1188300eb68db3b8bb424d6713bb798b9b3c9e4f.nq.gz
    ├── 12c4acb6167a6ed0e6a8e600003151add1ab1c19.nq.gz
    ├── 13449e5899db362ed98fb631b3ec3bac2466a975.nq.gz
    ├── 14da740e59d172137387179c35e1d02eb85c1654.nq.gz
    ├── 153edaec513b6b865357a381bf5864e195713caa.nq.gz
    ├── 182ae54d792fec4c204124d6cf15076b7af4c96d.nq.gz
    ├── 1d2e1c7a3752a040d9213d5dab69b96b184bc8d9.nq.gz
    ├── 1e2ef09e33f8a4b0f7eeb8e87e551ba8a5270721.nq.gz
    ├── 1f5fd73d7487ca3b89a75a06839649cea8515a60.nq.gz
    ├── 2177e88f67ef9a8bd7bc29db00263fd1bdc990a3.nq.gz
    ├── 217aeb0dbe3a08ff4054f6b083ac638e286c9547.nq.gz
    ├── 22c8138e986e514497e8352ad5df1c8c548fe463.nq.gz
    ├── 22e98d152aa83ec1af314274dd916a655aa7814e.nq.gz
    ├── 2360621ccb075dbe99339e60daf6937f8a535ad3.nq.gz
    ├── 238f4bccd5db5be9c4074e386bf85fd4ca05906c.nq.gz
    ├── 24451882ea4996dcf5b05cd01d25dfa654345189.nq.gz
    ├── 24ab727727982e26d15a371a689e2880f9d8eea2.nq.gz
    ├── 24ee04cc89ca0f8e87ee83aa9e89f2455cbc4723.nq.gz
    ├── 2624b8357a131b64068befef8e42a492eeae42b4.nq.gz
    ├── 2646f988048ebfefcf5b3f5d6ab701b07a316c99.nq.gz
    ├── 26505f53645ee001219132e6c5f2fb904963cc1e.nq.gz
    ├── 2a64db9bca3b2db15f14f6b84c5e0f8a94d7140e.nq.gz
    ├── 2a97b0eaf0b48a2969e299a266c0ae9a259c7ac8.nq.gz
    ├── 2b940524e862f98a14474619cc18241bcc39494b.nq.gz
    ├── 2c4e179e42e52dd46c8229b00f5d9894204ad170.nq.gz
    ├── 2ca2edb42d545b2de39b54471e93b5ad1701fb10.nq.gz
    ├── 2e5fe63d2ef43205a591c582d07bea5a630b9528.nq.gz
    ├── 2f5948349b92da57dca2b91f6a1be01b2809f961.nq.gz
    ├── 2f6c2fbfa6052a8d4f4452ff5fa390d449b4fd4c.nq.gz
    ├── 3070ad3b7d57880140d0b247ac32bf83649dc8b9.nq.gz
    ├── 31690c85ac1f2ce317ce23b23510c8e7ec32f12d.nq.gz
    ├── 322793040792b8440f6bb6db6e29660b8e54b266.nq.gz
    ├── 322970dd660d5a8e12d37864826bfd6c567a842b.nq.gz
    ├── 342b0ecfd91627ad5023fcf5bb51e413b4a0389d.nq.gz
    ├── 34a0a37d6c722cef4ca4d85313e75d5226c96e73.nq.gz
    ├── 34ae0f6542abbcbdc7e5a7aa3c06ef7b0cd46d95.nq.gz
    ├── 36507e941a7499e088b72be620a45e74200a47ff.nq.gz
    ├── 38958ac81fd3ee73540fffe51a81c7554611a9d1.nq.gz
    ├── 38b3cfe7b2092e870bd59a6a0ce575a8ad77ee5b.nq.gz
    ├── 39900adaf7c48eec71f5f2363bb5e7a9eaa95a7a.nq.gz
    ├── 3d0b8728e3023b626c3e0fa55858c674e61b9498.nq.gz
    ├── 3e1fa38f5e4038362cfcc1f19a1237a78e0f3603.nq.gz
    ├── 3f3f561081ac3ff1bc31f646b5a89d96c0a82bc1.nq.gz
    ├── 3f78172f222e9ac9a53c3eb56deaf69db4c3ac46.nq.gz
    ├── 407b893858142026d02735cd2e1c97b04cb1d4ae.nq.gz
    ├── 44bc9776a1a21dd6b6d883488f2a44fac6240276.nq.gz
    ├── 458df2ee8c8f17d31cb9c6f4bb88507f532558cd.nq.gz
    ├── 4664f0e267d162c60122dc4b067ab07f14dc5dfc.nq.gz
    ├── 480428644fe8688a9fb0669f5c019fb75c0eab6e.nq.gz
    ├── 4891856d0aca834120845e027fc00c35bdc63d00.nq.gz
    ├── 48e2b447215ddf3c5bc4294b42b669ea5c88b35c.nq.gz
    ├── 48fa7ae40108de2119dca2dc7ed56079c8dd4ae5.nq.gz
    ├── 491be9d1eb5ca4bf2e1a274e47a907881aa48052.nq.gz
    ├── 4929c23b8cd43adc58c32126c7cd44ed4ff58c36.nq.gz
    ├── 493b62187248db49af4af5e4397d8a5ddc520a36.nq.gz
    ├── 4b222fe367c6efb33fba3133c4b3ad0ee73f8299.nq.gz
    ├── 4b5a08c5e6a3047558520057a3fd801cf153b9eb.nq.gz
    ├── 4c1c5fbfadb1b717e158472ab9d6103dd7be029b.nq.gz
    ├── 4c409401e5ef7032ee38d4aafb8842a8ba769883.nq.gz
    ├── 4d5993ceee584830d66da88fd5e486013b2ae9a5.nq.gz
    ├── 4dd86198701378b4389dac288ea0e5e8db03ea70.nq.gz
    ├── 4df3e85c83de5d983c6d836880804cb94a47767a.nq.gz
    ├── 4f91635455b978640bed0b984efb99163851d1fa.nq.gz
    ├── 512b428f00f6d8cf5211ecd7c37f67829f94e0f9.nq.gz
    ├── 523bd86f73a07d7d993fa22667683545b1a1084d.nq.gz
    ├── 524464ce0c332d2f750ba0d5c3982bc4c294c0fb.nq.gz
    ├── 53017174cd09eebbe974b7d89374b540654ba9b8.nq.gz
    ├── 53020df72f813522e33e4c3d7d45cee5b3c02737.nq.gz
    ├── 53d965dece5281fde878a33f4c3e2d26f4ad27c5.nq.gz
    ├── 5451aaa76894f8ee5d506589d2a16de00a2a3801.nq.gz
    ├── 54ef440dcde3d4f99cfd44a092d63d7c69b3deee.nq.gz
    ├── 56c4bf72c83b3452cf862e02fb88a1bdfe665a40.nq.gz
    ├── 5742cf918b07f1c0bc3728b363369a751efa8bf2.nq.gz
    ├── 5b62547f9aef3da3a38806baf365ea8c059675d6.nq.gz
    ├── 5d00db23c10b11bdae3a9c33cdb0d6dbae91f445.nq.gz
    ├── 5d7fc4820c38db2a82580b020d32684aab5b606f.nq.gz
    ├── 5feef2d01df0a81e7a1574ad73cb2636d12d7a1a.nq.gz
    ├── 5ff52b907af62ceae42c2d624264572e9a222e59.nq.gz
    ├── 600b27d79aa2a42229cb22352bd66ca00f0febd4.nq.gz
    ├── 60248842ef7a835b8fdd148c7fd0b24da0365ea2.nq.gz
    ├── 604d7518e05af7e4b56027bd94b277f3de2bccda.nq.gz
    ├── 6104b9e6f4ae97e25a2fd85f24bc2370b23bab6a.nq.gz
    ├── 616d7ccda8850761dac4da3a20bbed449257af2e.nq.gz
    ├── 61cd9f19775be755ae4d42bbe8230aa8150dadeb.nq.gz
    ├── 621fac56f005436330766317df003227f51a6625.nq.gz
    ├── 62917928339de8df87d6737c230b3d3602e77d16.nq.gz
    ├── 649ef9a53035dc2a1024731d8fba03be02bbaca2.nq.gz
    ├── 6656149410189fe393047cccecb7d08921bef02c.nq.gz
    ├── 66678e378b55a7e2b28d2087164af8999aff39cb.nq.gz
    ├── 66c1ab9a270ce4d5fe99f9852d4aa6f3141e0fee.nq.gz
    ├── 670c0b9925b4164e545c0611b514b1bf4334ecf3.nq.gz
    ├── 691335d1bd912501cd785972faf9043dca9b08cc.nq.gz
    ├── 698b42e6df47d0b939dabd7fc754111b6fab8d09.nq.gz
    ├── 699071cc3fa04b85b93ed4d9c3a216fb150db5bc.nq.gz
    ├── 69f6b0f8275fecb3e264fcfb1b09a9ac2484bdab.nq.gz
    ├── 6e065fa78238cb088c11a4755fc3fab2ec5a85b6.nq.gz
    ├── 6f73abbead096a650a95ee71e173332df422f560.nq.gz
    ├── 6f90fda0018a200a636f0ff8b55bade6403e4753.nq.gz
    ├── 6fe60fcfb97f959a818dc14ded24d37dc636ae2b.nq.gz
    ├── 703ce538d27d633523859ffb7a93a930833d7c41.nq.gz
    ├── 705a27f18067836590aa039771811dead5c75be0.nq.gz
    ├── 7175a9d8280ed244ae8f08a21509cb855f03c912.nq.gz
    ├── 71f776b69634117b18d8f5c45b6b749e3dad7139.nq.gz
    ├── 7239a1ae8acd91b7a2097b787c1552f8fbe53415.nq.gz
    ├── 72a82a7eb7f0afc06663ab1d427e13a9a46727ec.nq.gz
    ├── 73168b985c543417a3596d9e2eb9c2a949a91cda.nq.gz
    ├── 733e0a43312f22ba984b6caa9518265c469f8e3e.nq.gz
    ├── 745b452f44ae8e159c98b890a672a5d642c6d9f3.nq.gz
    ├── 78ba93f466447bccf6ec5a465b67d257253912e1.nq.gz
    ├── 792980d38ba792c7bbe2521403106f6532e0f2e0.nq.gz
    ├── 798c093f7171d5a990a395b11baf0324b6a54d0e.nq.gz
    ├── 7998e4ce82c994a8f9678f2d806b12b36512d7b1.nq.gz
    ├── 79acdc1b195b3483768335341d4c3d2b6004bdd9.nq.gz
    ├── 7b41664e1e2852bd17eb3a8f2d766eea5aa0fb51.nq.gz
    ├── 7e1d26cf546373e962640172566cc8643261d187.nq.gz
    ├── 7e24fb343013d8cc81bb4771d501c28eb4c14ce7.nq.gz
    ├── 7fb1218541e3e834a97b7bb5bc1d4da1a66f5c76.nq.gz
    ├── 7ff60f5e12b2dfab33af564a65b7c188b465ae8f.nq.gz
    ├── 813c743c475a7b1269a24d167fbb0a71b791b4ba.nq.gz
    ├── 81a7f78c05cc74af135e8e207ccf318a6f93f235.nq.gz
    ├── 82d64288644dcac0ec5698ae4cfb63c211e14e76.nq.gz
    ├── 8342949b63117cb4f2c0b4acd39b88237d8301b9.nq.gz
    ├── 84ad5edb5d678515b6d28b5b3ecf5afa7be60f5a.nq.gz
    ├── 85266324a8a657c0c3a16abadc219f58215ef486.nq.gz
    ├── 855b5062b917364d7382e3a3ac8afdb2ece87c6b.nq.gz
    ├── 87e8a22f859c97614c5caff134f61a4a413a6240.nq.gz
    ├── 8826b52b71141d842f53c446ec02a96c275e157b.nq.gz
    ├── 886020f8d8242d36f344967504cd6f77d48cbc89.nq.gz
    ├── 88b9d1988fdb558002be4bb6df56920c2c2da74c.nq.gz
    ├── 8c3db71dbd0dcd1a58806c2f3cc3bf587c3d6f3b.nq.gz
    ├── 8db1c43688962f41414bd2ff4bda34fd7ac7b8bd.nq.gz
    ├── 8dd928c61918a742a353fc1f0407ffc1f048c3ee.nq.gz
    ├── 8f8edf10508db6e7265462242c4b8b56361753c5.nq.gz
    ├── 9009a006d487e0d06e92044c02eab29e1e332414.nq.gz
    ├── 9075e229c08dbe7288e35c80d378047a62cbe23c.nq.gz
    ├── 90e9be266665ecf3c572e30427ad1513ca10be19.nq.gz
    ├── 91e60fdf20566d00b898def26964a4c1e226d5e4.nq.gz
    ├── 93e6829b405214b3dbf34b703168bbaa70cf75e4.nq.gz
    ├── 93e93fcb011458ffec603f9a1929b37ce6932a53.nq.gz
    ├── 961e0da3d1c96a1b8f22e284c9374268c7c55641.nq.gz
    ├── 97a894b16c1786135a179473fb977d2b7af2038c.nq.gz
    ├── 99545158868fcfbf19baf4e52355d126ce7e39ca.nq.gz
    ├── 9a72e8beffa350211326104a9985aef32611a496.nq.gz
    ├── 9afaf3e83d13cf4a0b6c49948661c039310911da.nq.gz
    ├── 9b89ef2d5ab7873a6fc0801e0f3d989f644f1235.nq.gz
    ├── 9be042256673fa28fde6329535782e4b4010a602.nq.gz
    ├── 9ce662ff84c43f4a345dd602926a81d9445b433d.nq.gz
    ├── 9d9ebd4c5292da8c79f1874cbe25238776f0a257.nq.gz
    ├── 9e225cd2f45602e763cb8b66bb139a097112621d.nq.gz
    ├── 9f1d9383e74341edca9bbaa8547291163235975a.nq.gz
    ├── 9f8f2208c4bdc0f0b0cafb4c0d0b5c79d32c32da.nq.gz
    ├── a0bc07d4c2ee0a8e87fc3488e42da07661d4c3ce.nq.gz
    ├── a0c6c853f47f59b01b986455412dd71a25f93458.nq.gz
    ├── a0d8cc145547ed07d7ac56b0d74e6c2240fa53dc.nq.gz
    ├── a25f6c0a2461a1fc75ff648ebaf3faff6ccb0ab8.nq.gz
    ├── a3b93d3a7d69edbacb5f5cc6dcc0d463ceb1f517.nq.gz
    ├── a611342a4b6a5316177b84963b44cf2cb7370ae1.nq.gz
    ├── a65e7c535331933b80e869b2a775bb5e50bbed0a.nq.gz
    ├── a8ef98404eeb4e8fbf8867283817a743725abc41.nq.gz
    ├── a969999ab83a4d5e665ed2e522129f764d023163.nq.gz
    ├── ac61db74d74aa00b3aa63f75fbb2c6401128d3b5.nq.gz
    ├── ad47532ce93f6f9f9216def47b63cd548d98420c.nq.gz
    ├── ad92163ffd481adf0951c65779e48a86cf5ec77b.nq.gz
    ├── ae66a340f8916d6dbbd00b0e147da61f56233674.nq.gz
    ├── b0d0a3ea3897464eafe415d564acaece2d924d31.nq.gz
    ├── b11ff3c1cc8127c846168f83957cd4fb53e0ad4b.nq.gz
    ├── b25e5c18539c3ee5a6a5199bd63c65a2e70b7a2d.nq.gz
    ├── b47999fab26b895705405aa1576ff7c3ad7c053a.nq.gz
    ├── b50ca7b5d2a3c8271bc8843424cefb4c866d2346.nq.gz
    ├── b5df473faf7b13c30137408b6ae3a16226eaa2c1.nq.gz
    ├── b62fe4bed8f67bc5346257ef59e1565a780d3781.nq.gz
    ├── b84f4be41a9a6de5e54a42966aede689bab030fa.nq.gz
    ├── b86d3aa9121a13633d014c3320f6bf1cd8ebf3ab.nq.gz
    ├── b87c36e1f26e470e26391b580c4cb93023d1ea71.nq.gz
    ├── b89979cd1bc2e727b4ea2c636575965f4492d4e8.nq.gz
    ├── bbdbedf8a42541abb476e54ead46978045559f87.nq.gz
    ├── bc6e679db8ca45e604e05f247b1004dcd128f866.nq.gz
    ├── bc81ac0983ae3eafe0f1fd29f7895aa1b49c503b.nq.gz
    ├── bd6c77d26935721ea7b544078f0a67a96246b57c.nq.gz
    ├── bdb644696e5507848c8c867d8b28b30f38e46296.nq.gz
    ├── bdca75f6c35f368cac9d26ff0b96ef50e6f6bbbb.nq.gz
    ├── be9ac70b8444c84bda9a344b610b15691a87965f.nq.gz
    └── bf78faa725441752aadd2acb46ca499f3fe14a9f.nq.gz

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

[scverse/mantispy](https://github.com/scverse/mantispy)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
