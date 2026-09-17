# Repolex Knowledge Graph of evanw/esbuild

RDF knowledge graph data for [evanw/esbuild](https://github.com/evanw/esbuild), parsed by [repolex](https://repolex.ai).

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
lexq download evanw/esbuild
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 6a794dff68e6a43539f6da671e3080efdf11ca70
│   │       ├── chunk-001.nq.gz
│   │       └── chunk-002.nq.gz
│   ├── lsp
│   │   └── 6a794dff68e6a43539f6da671e3080efdf11ca70.nq.gz
│   └── repolex
│       └── 6a794dff68e6a43539f6da671e3080efdf11ca70
│           └── chunk-001.nq.gz
└── blob
    ├── 02b3ac97c97aba574effdb93796bb9eba33657c3.nq.gz
    ├── 03eea3a77d94e0f128ebb0f9e172772d1201e83a.nq.gz
    ├── 05fe75e42ef79134506e8d13f4e58fe743944804.nq.gz
    ├── 06415764ef32716a2358318748a0defbcd04651c.nq.gz
    ├── 06b90c2cd920cda018e1a1258bb5022ca377fecb.nq.gz
    ├── 06c807c61002bc4e908c335455e673cb54a8d4b1.nq.gz
    ├── 071fb909084b36be2369be48a003e05bf552075b.nq.gz
    ├── 07284b47eb472c03f0d5f5ec4fcaeb66b3a63c85.nq.gz
    ├── 07413355ba318f8b7c8a9cd65078219a585fb89b.nq.gz
    ├── 08272e6b3db3f5068e876e2c2b13b4e138d5694d.nq.gz
    ├── 093619d29f4281a88901d7196c17fdeb0998347f.nq.gz
    ├── 0adb3fc6d3f95219a5f30bc0988a6c26a6601be1.nq.gz
    ├── 0b172b5eaae8edc05f5151d782181def5fc00f39.nq.gz
    ├── 0c2e91c27a19e4af9a33016fa2de57c0087b08c4.nq.gz
    ├── 0d52dd1fc04b7de19884895cdf1dab7c6d62a9a4.nq.gz
    ├── 0db1b3aa12fb121a7247c888095eeba5db78ab2c.nq.gz
    ├── 0f6975e81d6c6d23daf17b320cc74084eb9d963d.nq.gz
    ├── 0f8c79a9ed51a49fa3411b346ec8f5b301b6577c.nq.gz
    ├── 0fba60ecbcb28d20299e0ebe61357cd5473d2c95.nq.gz
    ├── 108b2da4654b6d597dc44554de81c81d99ff0945.nq.gz
    ├── 113769d782b77a1c0aa3133d52cf29141a5ab1e6.nq.gz
    ├── 117b050446a5f572df56c904ed79280d340f874e.nq.gz
    ├── 12fcf8d1e6ad3dcaf79f151c90b014d585023188.nq.gz
    ├── 151619498da744bf3cb332034868b4ecf207b39e.nq.gz
    ├── 15a9bf6db828e4b4bebc90faf1acb45605629ed2.nq.gz
    ├── 15c835d5417c06d14182c50afc7c5b2ca0b45fce.nq.gz
    ├── 15dcef6d0e381d9f91c2bcea4408348533aa4592.nq.gz
    ├── 165a262c9b50dfa8e700700bbf024942b1d90cac.nq.gz
    ├── 1848118016a55c064b748ea62856dad5daed63e6.nq.gz
    ├── 19b45820b8c495a522d03900f3c20deee8ca901f.nq.gz
    ├── 1a0e1e8b427515c44d3e14ee78405dc8901f3c61.nq.gz
    ├── 1a6cb72db2bfac9b8976343245747eefeabad3ac.nq.gz
    ├── 1aa2037df6f3d4e10c37681c98533def5b0dc45d.nq.gz
    ├── 1b06b135fadb7cefaec306a7acf0cd7caea50e50.nq.gz
    ├── 1b2beecc607b3f898721e0d252578e484b3b8295.nq.gz
    ├── 1b3c720f4a6e0f657ebc1a93d51e0307999a0274.nq.gz
    ├── 1c9f0af767ed7e4afb74438350a1d81bc6f63887.nq.gz
    ├── 1d9b1fe06740abc4915d5ca638c4927d6f168786.nq.gz
    ├── 1ddecff72c195a074e8517baf688a5dc80ffa9a1.nq.gz
    ├── 20103a9cd2a85ff09477f4b975bb9167167d85f6.nq.gz
    ├── 2027e8dcf3787f5aac9fcd835e2b80cb75a39211.nq.gz
    ├── 208056cb44ec662c8b41b3ee44e15c07571a1b7a.nq.gz
    ├── 22ab13e06652589a47c7345fe28c4cc1d5f855da.nq.gz
    ├── 231eac47231d889ccc9c8b1df1e6406188a930e8.nq.gz
    ├── 2492ebd958d37d34259caaf10e7240b9cf89f4c2.nq.gz
    ├── 24b53065f40b5d7d277a64375956ec19cb2123c5.nq.gz
    ├── 252733c3da6dce742244b12f7eb734779678556c.nq.gz
    ├── 26360132d6c2747c6292e4745d6c42c0e623242d.nq.gz
    ├── 2659b2b52920c670d58a254f7ec400fa9dae0010.nq.gz
    ├── 27fe0380cba08beb9a364667d9f9743e8827f4e5.nq.gz
    ├── 28ab7f76f543a6901d83dba2cdacca2db9d35158.nq.gz
    ├── 2a167ad0848e91806239872b1630f234a2024dc6.nq.gz
    ├── 2aedd5f1e0d29d4d840086328f1c96aba5850414.nq.gz
    ├── 2b05b16f5dd3d22095682175e1d3f222093ba256.nq.gz
    ├── 2b49927d8e7d13090be2bccd8417c21a75e3cd95.nq.gz
    ├── 2b5004c07abe9a17d3f6b5904f16ab1c6d3cfed6.nq.gz
    ├── 2b84ad084a0fc5b0674d8da99ba75290aa0cd05d.nq.gz
    ├── 2b8aa0aa55e31664664a59c771b919212b3c618b.nq.gz
    ├── 2c25185e0e2d4c0d7518b1d74c6f090783117195.nq.gz
    ├── 2d92cf344eb78e465b0cb0e2cef129fc9aaf0fe9.nq.gz
    ├── 30f737a93f3fc9cbf5837a5c33270099701ea08e.nq.gz
    ├── 317b61d933dad4a2f3a745da835b08e153bb4bca.nq.gz
    ├── 339bdcc308f4e961320ff5cab345454cc0432c88.nq.gz
    ├── 34c63dc0ca023851be1f306b5fd4595ec67c7227.nq.gz
    ├── 35b71084ed6a2e7615fd4a1b68048179b8018884.nq.gz
    ├── 369c686441f9321f01efb4af2f29cf5835e0279f.nq.gz
    ├── 36ba93f00d585506ea97bf8cecff9fd2b45f9729.nq.gz
    ├── 36f5328f0d92591a12fbf8ddeeae49b47fefa58d.nq.gz
    ├── 377d1b728c1e57a9fb5d7b80a5155f2443c79fcf.nq.gz
    ├── 39c699ce08b5edc785d402393c3263365e7a4bd4.nq.gz
    ├── 39f802ad92f635f5abfa35657f544caafa4546e0.nq.gz
    ├── 3b36fe25a30ca96b55bec20fef21944762bb6fc9.nq.gz
    ├── 3b3c572faf5f4176cc3c8d07c7a3baf4a80758c1.nq.gz
    ├── 3b574a1977b6f841fef90e2d2dfb18e6eacdc033.nq.gz
    ├── 3b69994af7e1c4400e23042bc7134a782ad38d6f.nq.gz
    ├── 3c8508e44ca0317094c7a96d1591a92969c3a8e1.nq.gz
    ├── 3df4bf699c83f03c7b56e6a50810f249df315fc4.nq.gz
    ├── 3e172c0fd861e3a7002acdbe9427214ec316ff2b.nq.gz
    ├── 3f5aa28fd38df72b67a45e30907f486d5b4272c8.nq.gz
    ├── 3ff4481efddb9a98c29052262b85c5135f6db569.nq.gz
    ├── 412eb687d8543c9ef6d9ccca74104d64c962320e.nq.gz
    ├── 416c5e43d24bdb6c5a4ec16c22cc2020460adee2.nq.gz
    ├── 4176e800e72654d7c946494b41366fc281592056.nq.gz
    ├── 41a9e7aa17605fc83987286ce121fd8f766c809a.nq.gz
    ├── 41f35153f91f15dea20b3950498520bf1aa128ba.nq.gz
    ├── 4461029c4c1bb3bc826a250247fe7d88357110cd.nq.gz
    ├── 4502b23ffe6e6cb07cdfb7570d4e11d58f618524.nq.gz
    ├── 45d3a9adec00efc1c2c011495ee81b1c7840479f.nq.gz
    ├── 47b0c1cb22baa0956d022931b2a9b38cdda948c6.nq.gz
    ├── 4999e80e1455a5e7b4899ecad0917a04ee89e76e.nq.gz
    ├── 49d76816447ecd64a99159b39e11ff75ff08c67e.nq.gz
    ├── 49d9de574b277e97fe261ec86c96453245635d61.nq.gz
    ├── 4a15a74a137bad6d2f79001ea7865cfd2e398aff.nq.gz
    ├── 4a75f51349961ac981c747676b2a20d485237ba7.nq.gz
    ├── 4c608357e2831e4f4c599227e22dd78cbec60fe3.nq.gz
    ├── 4cb2548a263c78d27bba6d0fbaa633414c86b17a.nq.gz
    ├── 4cf45c5bdebb1bbee965bc2b43b51926a63ae719.nq.gz
    ├── 4d759dbbaec892321753adce9b4535c184620096.nq.gz
    ├── 502533b3451c2707cb7e0ba308c4b033459533e4.nq.gz
    ├── 502d3f2ce98570775ddd079dce07fda71fcc4712.nq.gz
    ├── 506fbdf0efd8dea76bc631d5d4ff1a1d444b0430.nq.gz
    ├── 50c8fcba2d1a067a0e80ef9d2c27a4258fef049f.nq.gz
    ├── 51655178bba214759fb5f7c55a7ac16e879e1aeb.nq.gz
    ├── 52c5ca7c85ad74ce66ccf71e457e83fefc529ba7.nq.gz
    ├── 530547bf9892b71a5bd5e85cd90e0dbbc3d77800.nq.gz
    ├── 5323e066f098a465b67273673bc53377aa4d4d7d.nq.gz
    ├── 53f6701fea5eb08de4c90e596fd784dc70ed99e2.nq.gz
    ├── 5489d798bfa9f5e5f144e0411a40a2a252b3fcf6.nq.gz
    ├── 55927e8c7aea42c9a73b27c4408167caf5a6598b.nq.gz
    ├── 55f13425193e1353896f6b982043c4a19b44506c.nq.gz
    ├── 5659f9f6e6b7260998b1f5b9b404c5f36424d25f.nq.gz
    ├── 56cd4a106f972826a1131163acbe45d304294efe.nq.gz
    ├── 58a7b8ba494dbdf580e48daab45301b805b0ef2c.nq.gz
    ├── 594beaca7cb97c84948ca0bc0d5eeda6eebbf361.nq.gz
    ├── 5992d83e74e7d7e267f15f0eddc7963719b66528.nq.gz
    ├── 59a0f450574a84829ef9d37e115f403011764612.nq.gz
    ├── 59a5f4f6d3b2e58ec738031ac09bae0aac5777c4.nq.gz
    ├── 59b248d7fa95167f6177f21337b917722bd64f92.nq.gz
    ├── 59b24bbfa490bc845d8c92f1a233e02565f87433.nq.gz
    ├── 5b199a2363c090b20e33c8e5916a35c4aaa159bb.nq.gz
    ├── 5bc730f4b815e1c9ed03ce7514e64bbd511ab775.nq.gz
    ├── 5cb51d5a50782ca23323c78f479fb5ebfc1a98b1.nq.gz
    ├── 5d32c63facfc6a66da2984e108c41558dddf4b71.nq.gz
    ├── 5def4cbb5b794bab14177aff36be79b25776036f.nq.gz
    ├── 5f74f506df7cd16af8a0802578cbe2c79203104d.nq.gz
    ├── 5f95dcdc88f12d4d717fa433ce2419552703e7d2.nq.gz
    ├── 60277cedde6a92eb621cd44c695f0f8b9bbaa268.nq.gz
    ├── 622eac801e802e532f857028729144882c424451.nq.gz
    ├── 62385b7ad4d5722fd0cb9e3e9ad0202f9d1fddbd.nq.gz
    ├── 6290b53c1c105fe4c98b571d186406aa2f2424b5.nq.gz
    ├── 62ce7e47884d5cac6250d75ce36216f23e1379c4.nq.gz
    ├── 63ee9a3c4d6d2806f22d8c8774e0f0c2911bd8e0.nq.gz
    ├── 64177cc133ef8bef0d5fe5472b7566b305e00c68.nq.gz
    ├── 64372006540815588bc371ccc8d2e7d845a0be1c.nq.gz
    ├── 649f80a2c1a3dde26df2fd777e57a8f5b92ae2aa.nq.gz
    ├── 677e12bc3fc72ac8112cace52b1a01b8b33b6cbf.nq.gz
    ├── 697f087f376ad7f03d3702f9f0e0987315e73f73.nq.gz
    ├── 6a1b7534c26563f3e9981a8a976e45b72e16b6ce.nq.gz
    ├── 6a7b36d7ed78c988acead6c8a9903a9277f0ccc7.nq.gz
    ├── 6b87b41e4562a1e2b20625725505115a9b8fdfd9.nq.gz
    ├── 6b8fe90acb7f254b3ad13620620d07066a621c30.nq.gz
    ├── 6c7ca3a6b402a90cef630395f9e5d8a862be3b93.nq.gz
    ├── 6daf4e7ff56530606b4d4d5631dde256d5022c64.nq.gz
    ├── 6e02d990447c4cc8e7a921ddf40586dc0db4a32e.nq.gz
    ├── 6f0128d77402ece9093b60cd05ff833116254515.nq.gz
    ├── 70ce0069ad2a1c0119867cb5145cc4d5be99bd14.nq.gz
    ├── 7187a78dbfa920ede4e19d71b58fbb16e6bce2e3.nq.gz
    ├── 71c8c9b1f1b0049e5106119695961fc777fc263b.nq.gz
    ├── 72177f1a1667e1a9416d3f791b814222aad8f30c.nq.gz
    ├── 721ecd33c5920980b276fc403321a930a739dfe7.nq.gz
    ├── 7425f29e1ce5f3b90bf926c3c487ec5164b28419.nq.gz
    ├── 76f25d1ad922720c087be6fe8054e0064c1fdbb2.nq.gz
    ├── 77269e3a54933d96ff766d42151651e8cbc6d149.nq.gz
    ├── 77c43129b88f5867d75ac6cfae876859e010456f.nq.gz
    ├── 78649ead8aa60ba4eb30106c53a5d050063443aa.nq.gz
    ├── 78fec66e40f9934854da421e3fe49c2c2d4c6bb7.nq.gz
    ├── 7bb34a51ac26d4433bbfd7e77f8dcbda492b06eb.nq.gz
    ├── 7c603d05bb165cbe718f9c200246311d94d2ad74.nq.gz
    ├── 7c70769d8c5f214e53a4e0cbb0499276e8f2e874.nq.gz
    ├── 7da8a85493338e51ea7110f7523994a95ffae851.nq.gz
    ├── 7e9385d870e20900e52e3069080091e5cdc8313c.nq.gz
    ├── 7e942cf45c8a371a12fb1a750e05d278caa61543.nq.gz
    ├── 7ed71f6fa773fec2325e2f972668f982ab903343.nq.gz
    ├── 7faa76314bbe4c3508f706ac508ed3d6d4dc96f8.nq.gz
    ├── 8053be92606c64fefd0d02f87107601e3d40cf14.nq.gz
    ├── 8068c27fc9957f023daacbafc875802399cd3679.nq.gz
    ├── 808d2d37ca6c90e2ffb44c934916f3f8a90fe456.nq.gz
    ├── 80d8e975646fcf544c30bbb7e548706777338bed.nq.gz
    ├── 81fee4356d5e0d8f8ed0c6c879126fa4b1cfbf3f.nq.gz
    ├── 827062101c3315b836e4e8769cd1767b5a8d1afd.nq.gz
    ├── 828e2acd02884b093572551654c16d1cc4f30fd7.nq.gz
    ├── 82a7f797738a12dc14b00822e708e2132f356ad5.nq.gz
    ├── 84a3722280c14e0ac55c255723f48a066a648acf.nq.gz
    ├── 850e088280e51b12ebb5c9cddd04446fc9c29785.nq.gz
    ├── 85bea9c8f5f4473b9bb57634ed03f7d9c8302d83.nq.gz
    ├── 8968a335ab2ece2a68245e5eff063570144f0a89.nq.gz
    ├── 8b1dd8c401e5b3d51b2b1f9530e8cc5340ee3a7a.nq.gz
    ├── 8b7ca60209ed7258fc2f3a9806b3fea129e667d4.nq.gz
    ├── 8c403821b27284c86747e3daf3ae872b4e69b8c6.nq.gz
    ├── 8d5e8a9c1f73a02183ccd8849c5a917c30a8e0cd.nq.gz
    ├── 8e1cbee598433760e6d2468b4d812bc1fbdf9443.nq.gz
    ├── 903ef5dd019a93e87a325a919cc98fa956b6f3c0.nq.gz
    ├── 906d7d6b33baa8ac6886fbb2486aa5c04c532e28.nq.gz
    ├── 91c8f718163cd8741c11d8e724e00e0e09f05dd6.nq.gz
    ├── 91ecf73c6fa9e6009001cde8e672403e7039bf1e.nq.gz
    ├── 93863d198004eae1c7b17aef26d829dfca4a314f.nq.gz
    ├── 95b86845c21b21653a6f61f52d4c8a7d6b28d725.nq.gz
    ├── 9b3ae0b4470e292e9e0432ec1355595590a33379.nq.gz
    ├── 9c301c61dde3e4448976001e4824d748df5d24fe.nq.gz
    ├── 9d507c79a78a44aaf5a376dcc4e67b2bb3dd0414.nq.gz
    ├── 9d70443e0f184fcd112bb71d713023b82cc9a312.nq.gz
    ├── 9e26c63a2175bd4964ac7b567b8c2f2ae05c8c90.nq.gz
    ├── 9e69c39f58b92dda3496b19481468b5057a1084f.nq.gz
    ├── 9f6a3636380c73b8a88cf5eaa9a314f65e388318.nq.gz
    ├── 9f7d7ec3ab2071a349913900b012e5418162a6bc.nq.gz
    └── a030797d81c119778b386c3c4d728ff9e8780e54.nq.gz

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

[evanw/esbuild](https://github.com/evanw/esbuild)

---
*Parsed on 2026-09-17 by [repolex](https://repolex.ai)*
