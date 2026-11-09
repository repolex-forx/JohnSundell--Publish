# Repolex Knowledge Graph of JohnSundell/Publish

RDF knowledge graph data for [JohnSundell/Publish](https://github.com/JohnSundell/Publish), parsed by [repolex](https://repolex.ai).

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
rlex download JohnSundell/Publish
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 58e943047882a5a6d8135ae2711be8ba7fba57c4
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 58e943047882a5a6d8135ae2711be8ba7fba57c4
│           └── chunk-001.nq.gz
├── blob
│   ├── 000b152ca801c8ca31f0aa674e421708eefa235b.nq.gz
│   ├── 00d3039bc9b24377d461ee72560bf48a2cfea064.nq.gz
│   ├── 012e16af5b590451d0a75ef331f0233c2b2e9a37.nq.gz
│   ├── 02463eacec19b9d812e8e8703704c434962e0c86.nq.gz
│   ├── 0372eddc70a00a31ae9f9f3e9946fcc913cddbe4.nq.gz
│   ├── 06e3c044d023b3ee987f47074f34d10e4d54ffb7.nq.gz
│   ├── 0831757a892860297a4102f4724a4ecf3dc8ddf9.nq.gz
│   ├── 09c3638fcf2168b944d8247db04419f729e51b77.nq.gz
│   ├── 0a80ba56b4b1c923c9874a01460cdecb1e6eac49.nq.gz
│   ├── 0c8cffa9f2e78b5c32a7c027eda24812307d6178.nq.gz
│   ├── 11f1b6b41e59ee179ade2cbe58c5ff24246e37e6.nq.gz
│   ├── 128bdf26c6d2c078dd4754429c4f3838630fc15f.nq.gz
│   ├── 135cab341595e72e2038cb306b193ed2d58c7d16.nq.gz
│   ├── 14ead1eb9f9edee55f769300873096a886340814.nq.gz
│   ├── 17fb9d8f72449d7a484f1d69404b1375b28d72e0.nq.gz
│   ├── 1ab157442da5e4e672463d55e4807bf3a9dea4b8.nq.gz
│   ├── 1bbd3503ac016af7f5a48ff216bfa41bea0cee6c.nq.gz
│   ├── 24eb249ed1dec008232f9f2245f7f098abcee1ca.nq.gz
│   ├── 267d684aaaf9425ed3e850db7933f02e23c3d582.nq.gz
│   ├── 28df79273875bacf9950b9b70277a409a9b0a05d.nq.gz
│   ├── 2ad550878cd30eb970b30acc5aedb4d3a65c93de.nq.gz
│   ├── 2aedc39ed0df8064bab04a41616e3654c3c1a90e.nq.gz
│   ├── 2afca997f5edb6a364ab0e24d65721553fcaeed2.nq.gz
│   ├── 2b3bba98a2f6766c0f295f43dbed9d3404d8ed8b.nq.gz
│   ├── 2e6b77be2c6e59d9a1fddd6577e738662b14acb8.nq.gz
│   ├── 325efb9da99da59bf9dba7218ad55406b01625b3.nq.gz
│   ├── 326a235c03e183f668a3e577362227d011cd596a.nq.gz
│   ├── 33e81dafd976fb70cd4cee78d25ff85e63ae68c2.nq.gz
│   ├── 38674f1c6234fc1e5207da286deb9400268fddd0.nq.gz
│   ├── 39cdcbb4656daaf56c603fe979721f28da9d5be0.nq.gz
│   ├── 3c6db573d00bb51a36ed2f95c8b4ab95d4b1b30f.nq.gz
│   ├── 3df65ebe3926fd4cfa301ed5af4559fa4fcbbce9.nq.gz
│   ├── 411bf428ae665d03d1e2b6ad8edd0c0e69ec29d9.nq.gz
│   ├── 4263e812710cd6719a0c10752cf08f83de3ae28a.nq.gz
│   ├── 4523787738b51f1b10acb6118cf0aa90723817cd.nq.gz
│   ├── 472c50aa6c46b0bd8e83e1d00912fa20b43ed11a.nq.gz
│   ├── 4732dbee352dfdadedacd9be09b02a685a71f942.nq.gz
│   ├── 49389ce3bba0a1bd68bf13343e279538672a1efe.nq.gz
│   ├── 4a92583e7a26e7cdbdedf4656c39f411d2c31352.nq.gz
│   ├── 4dd14caa0b34820cff90215e2fe7af47dca10713.nq.gz
│   ├── 51c88a23a3522ed82ad7c5bb5b97ebf23e571b76.nq.gz
│   ├── 5269da152c8c945de26b45bdd01c34283df89541.nq.gz
│   ├── 52cd192df66c4e938269aabdd0bb04c8cc853f25.nq.gz
│   ├── 59d6533bc41fe19b444afa06d241ef4c28d785d7.nq.gz
│   ├── 5e0c0b090a222f8e29206d1bbe8d2dcc4e82accc.nq.gz
│   ├── 5efd83597a74ea9b6b374ed608797db7feb7ef73.nq.gz
│   ├── 5f63fe92898efa959382b6f1daa4837c2e6f82a6.nq.gz
│   ├── 63e8a7b01ed9bc35db47fb26434299e17e1c3b7d.nq.gz
│   ├── 6489da36fd97216a259e4dd58f6176879ca05cbb.nq.gz
│   ├── 69583b5d10e3105bfa6a95f5f4f3e47c3d817bef.nq.gz
│   ├── 6bc4a056ace39916ed019b8cb0fd684f69b86ee4.nq.gz
│   ├── 701a72d847f27b2863adbdc39a3e77cb846ca705.nq.gz
│   ├── 7066192728a48d70cf4d9c2c5f042e2c327070af.nq.gz
│   ├── 738133bdad0eb3da906407d8bb933d85ad209ed1.nq.gz
│   ├── 74d9a9b483f6143536370b3966bc540169109cfc.nq.gz
│   ├── 74dfd60ed2b835948127c3d80620c5cd8084cc4b.nq.gz
│   ├── 775646b3fd3766da54da8d5fa81619710d9d8d8c.nq.gz
│   ├── 7a3290c090dae0cf19e0a67b899861343ca1efda.nq.gz
│   ├── 7b3bfdc460010ddaf3f0c978b6ff2a41c969a963.nq.gz
│   ├── 80742d3a4733191cd6be766448b4badb274f16f0.nq.gz
│   ├── 81dedb1880929b283c20d664ba2a930f54133c9e.nq.gz
│   ├── 8436b4cb6c6f4e96c51ad7963c05afd7a4aa7a52.nq.gz
│   ├── 84c41c11e8cd2975b9b374bd6e54b56e9026561c.nq.gz
│   ├── 86e9cb00e726adc2420e3392d1e21e8c22c5c8ed.nq.gz
│   ├── 8baa54b76a164a948233382f15740d6dca8cc61a.nq.gz
│   ├── 8f86e1d06200ab11cd052f74750f4097d3a4e2a3.nq.gz
│   ├── 910e577263a52405bb1cfdcceb39296906185fc7.nq.gz
│   ├── 9428d1b4ded3c377980785a988c4966d05fd21bf.nq.gz
│   ├── 96535a1e63f134e495b730e6f91716f75ea61f24.nq.gz
│   ├── 9baa05598e60f1168e45d62782b70ed8a8c064a0.nq.gz
│   ├── 9dd0b6e1ad340d301334706a3a580b76ac6e6735.nq.gz
│   ├── a03888af89758da033593a77d9b026e463188964.nq.gz
│   ├── a09f3c3c2572450b59f1e85641854e0cc4d30ba4.nq.gz
│   ├── a31b2f15a3273d1509f4df9465df223b70cf4df1.nq.gz
│   ├── a8ce1bfe6061236547e39d1a58cd044119bf374c.nq.gz
│   ├── aa0b89b57bd32877132f30d14c431cd4f1e720a7.nq.gz
│   ├── aa640ad91886a6d80b3e9393b4c99712604bdd7d.nq.gz
│   ├── ab26aac64f07667ee3dd9951ebc4b41aa6ce5645.nq.gz
│   ├── bab61d4ed8447b29e540cfb395ed28db5ba3733e.nq.gz
│   ├── bda3c91542c3d44eaf50dcb9c7637b55d22651f0.nq.gz
│   ├── bebd5cd48b2d1f95a35fed56513a53aefdd1205a.nq.gz
│   ├── c49eda8aee09a384967669d133f7d09fc0f517e2.nq.gz
│   ├── c60cd126d11f7478392267e112aec4ca1988fb59.nq.gz
│   ├── c9f12ef5dcb3847de2b109524cdc429866285de6.nq.gz
│   ├── caf0a7acfd701715d4c7ac66dff6196cbd847628.nq.gz
│   ├── cdcede206e303aaa6a5adc06086ac8b71307dd8f.nq.gz
│   ├── cf21214c0a0cd494551b1361ccd84c0b3f7600dc.nq.gz
│   ├── cfae4669a63c4ffbf9f63a2394e95db10e0d5390.nq.gz
│   ├── d3713505c996cc741937565d1d516b051b45711e.nq.gz
│   ├── d3d55a8bfe2586a82ce36e2c8ed2717572655377.nq.gz
│   ├── d41e206b07f3e2631473cdcf015e95a17f0f1aa2.nq.gz
│   ├── d47e2d41c946ac611bd2bf38229807c39a2a5caa.nq.gz
│   ├── d61726cb1668f010ef88717b3efada1a12785297.nq.gz
│   ├── d65778833cf249fcb3da8238750f21ec5609744e.nq.gz
│   ├── d97b805c0c76bfb5f730e68e7402c905669d118e.nq.gz
│   ├── dca39a110d14215a0cdaf34d25479d0f5c8d737d.nq.gz
│   ├── dfe87b681ac2490908b34cfac86cbd1904a4b3af.nq.gz
│   ├── e08ad005cbe0792332801e178575de60d1d804bc.nq.gz
│   ├── e6f7813632fa3c47432aaeb5860f799d01e579d9.nq.gz
│   ├── e836f52dabe428dcd4e6f89b2dd094efcaa8a769.nq.gz
│   ├── ed0e16cf14027f117f379ddfc22373076637c78a.nq.gz
│   ├── ef91271f6cd872bf28398a17a1549fa70e7b4fbe.nq.gz
│   ├── f083976ff53c622633a045c3cad4e8beb0f65f27.nq.gz
│   ├── f08b6caa6986c26200c95bba052fa85c9bf1a2f1.nq.gz
│   ├── f316c9bebc7ee85807b58b29bc363998a50984e4.nq.gz
│   ├── f81064ccb57337618bc93124a3844d9fa879b986.nq.gz
│   ├── fa1e5300efaa2f25660be60ad71f4a2709fc9b89.nq.gz
│   ├── fd4c5b8c70714a48a51f6528896be42c07cbd2cb.nq.gz
│   ├── fe77c63456586f2fe03faeb5340eea8e54f614dd.nq.gz
│   ├── ffa486e7c96629793766a5fa675f6db59b83c491.nq.gz
│   └── ffeaaaa39d37789de7de33d9edd2f896434ecef4.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 58e943047882a5a6d8135ae2711be8ba7fba57c4.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

12 directories, 118 files
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

[JohnSundell/Publish](https://github.com/JohnSundell/Publish)

---
*Parsed on 2026-11-09 by [repolex](https://repolex.ai)*
