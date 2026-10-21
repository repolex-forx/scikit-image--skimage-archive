# Repolex Knowledge Graph of scikit-image/skimage-archive

RDF knowledge graph data for [scikit-image/skimage-archive](https://github.com/scikit-image/skimage-archive), parsed by [repolex](https://repolex.ai).

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
rlex download scikit-image/skimage-archive
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 3bbcc6e8a7bd2c05675b316773796cc7f7fe0a96
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 3bbcc6e8a7bd2c05675b316773796cc7f7fe0a96
│           └── chunk-001.nq.gz
├── blob
│   ├── 0364c38f4ec41b20c9f28fc593ea978fdaca84ce.nq.gz
│   ├── 042f62ea49053157968c38bdd9f8cba691b3a00d.nq.gz
│   ├── 04b597306f6bc6808d2a172755d9386b0d55bd49.nq.gz
│   ├── 09d34c43b6486b35638304e61e72722defa1d1ff.nq.gz
│   ├── 0d3b4eced9397371b6894a70fcb65cb94dae65fd.nq.gz
│   ├── 12f8366dc977cdfa5d1181162a9bb5452a66708d.nq.gz
│   ├── 1311b15b68ff9d0c28da5bd37b88c156b61e22bc.nq.gz
│   ├── 1c1f50c1fa834136044a073b82a20ef7f64208e0.nq.gz
│   ├── 1d3838c1cd74befc609ba93cecf10a6fc2a28e90.nq.gz
│   ├── 1e959fc2e2ef0a75008a54e45c02dc9f0cbf2f17.nq.gz
│   ├── 1f93fb962d176a2c998c8d81b27e7753f88eea40.nq.gz
│   ├── 2216eb0fc0b3b1b01cb376335478493bbecc28ee.nq.gz
│   ├── 22654fc29b03bbb918b3fc8ebfa44bb8f167a790.nq.gz
│   ├── 2277540fc91b7602ea0a23d0f21ecf76f63a2029.nq.gz
│   ├── 2440d0f0c3e7b442f85e11965c8cc41a573e63db.nq.gz
│   ├── 256684efdbc2d5ba36a9367084d2312b3a7cbe5f.nq.gz
│   ├── 28f4c2380662e35427e8d00c700629e901cbc272.nq.gz
│   ├── 29ef21c2b6c9b339d3907cf2bb9f160eff44d647.nq.gz
│   ├── 2c7f52584190596f900dbef8334af806f370a06b.nq.gz
│   ├── 2cd099ee71ec52a01a437dfe1666e843d8c8c651.nq.gz
│   ├── 2d944c34109c1d9c5c6c98ceee3479cc08e3cd77.nq.gz
│   ├── 2de7818cb43ab791460510fcbe2094ac8e0987bb.nq.gz
│   ├── 2ebe97689b7fa966a6178e3e00a4be7a2cfa1621.nq.gz
│   ├── 318704d64b00f072a2f0e142fbee1ac5afbdf4b4.nq.gz
│   ├── 338fddef394808fcac8e77cb18490d189ad8e186.nq.gz
│   ├── 3611bdc044f61ca828d717a98ceddd77cfd7d0ce.nq.gz
│   ├── 388555ffd6d645434101cc0e305e0132a25ff41e.nq.gz
│   ├── 3d3b9306ef1f10d7a1b46ad7e39061aa8f835da8.nq.gz
│   ├── 429ad45fe32e6631839b1d0dcf52f13d168df420.nq.gz
│   ├── 4582bf5430e3292ef5d8dde696837b6d151827d9.nq.gz
│   ├── 4689bd7fe14f9050cfb748a5fe17e9deb8b03578.nq.gz
│   ├── 46a43777733867cd2373bf9158f621181dc12dfc.nq.gz
│   ├── 5336c2509f7f8b638ddeb673caea9dd8ef34848f.nq.gz
│   ├── 54db039ba15eb3e0a2b607e860719c03180a6367.nq.gz
│   ├── 5a338571a74328827a818bba6dc350c3d722c13b.nq.gz
│   ├── 658216df41e6ade572bad992a14db1b6b9006588.nq.gz
│   ├── 68dc53efd76aa808285197fa942a4fd4b3e72548.nq.gz
│   ├── 6919b03a24c884c258a3df2a5da15fe9ff91894f.nq.gz
│   ├── 740da6a1bb8a8c2f4a5b298ce732439d1f81e95f.nq.gz
│   ├── 7533e524399be9bb2879fafa9e0da59d00577dd6.nq.gz
│   ├── 75d612123f0628aedf91342f6cd26972c1953501.nq.gz
│   ├── 7c6db5d1caafdb18fc04185df4921d50e4a3df93.nq.gz
│   ├── 7dd6678bd0b3a52595065b7598ca24f3bf04fac4.nq.gz
│   ├── 7e7847b29998b344e1959c12fa0ac8f48673cbb4.nq.gz
│   ├── 826898334d9bcf1f31bf24550bdc470ed5e44e0d.nq.gz
│   ├── 86932a35307615a588c5dab2e9a1a609990d44d5.nq.gz
│   ├── 8807134b964b61fd6a2142ef4f13730808afcf86.nq.gz
│   ├── 8a454fc5a630ab41e8a597ee703a013a3b4f1d4b.nq.gz
│   ├── 8fc0a3c7ed61f871d0423e17620e2e60ad43734a.nq.gz
│   ├── 919df2704b7fe7150977d7d6e970f4e0e8632bfb.nq.gz
│   ├── 94be1c0c1a5168939003d4fbdd7595af36a6d8ac.nq.gz
│   ├── 94eaf9e4a7802d48a8cc37463261ade333297435.nq.gz
│   ├── 974c213c0365d715b3cedec948fb9d7bf7dd8e03.nq.gz
│   ├── 9855806257b4ca5ee9ffc9b076c28c3020073173.nq.gz
│   ├── 9c945a95c2e21d57f17db9892c071e97b4a5ae6b.nq.gz
│   ├── 9f30ff0446ad0c1a7edb9c5a68b3efc4d7555fc5.nq.gz
│   ├── 9f5a103cac7fcd495d3a2b212c2b0943562555e7.nq.gz
│   ├── a01e8ce0c793700fb4e2a10ab2c2db74812cfaa0.nq.gz
│   ├── a0f76f97afb951997ba9038114fffe7fec8660b3.nq.gz
│   ├── a29d004e935a5674df25f488600f24c7f87ac127.nq.gz
│   ├── a7bd8684062d9108eda26710e2706ed0895cca91.nq.gz
│   ├── a993b7962d2ba20ef2fd8b88e17037ea5c04cbc2.nq.gz
│   ├── aab8961571a6b02f442f9b03397a88531183297b.nq.gz
│   ├── b46995fb3a7e3bfae28cdd55fc3dab288ef4428b.nq.gz
│   ├── b6e9d2f2a7cc79ac31231f827df1fed3cabf2bf3.nq.gz
│   ├── b8623bb08f39b5a168690b4be124228d3a4e5b59.nq.gz
│   ├── b9eb902410afd82ec216ddd40cd2f07446d6df42.nq.gz
│   ├── bfc3c5069dcf5e42d3764d6e16f58a66841c301b.nq.gz
│   ├── c4f215e4414603dd118cf81ad11513412cc4b1e6.nq.gz
│   ├── c524b85332ad7083dd95e6cdee9985e823903889.nq.gz
│   ├── c5a1d26760f690e281c12c7a638af61079246965.nq.gz
│   ├── c9108cc0a3eefe01041a5ddcfe1ab0131986768f.nq.gz
│   ├── cf3678acb44ff3addddd48959a57f69437b14c66.nq.gz
│   ├── d1ee1425c81a8d4f9f5f1281e9994717fea1b55d.nq.gz
│   ├── d23d898d011924c2c1dbcfb45079d77ff7d218c4.nq.gz
│   ├── d9442f9d43ea9a54bf8cf83bda593e1afd668413.nq.gz
│   ├── d94e242e95d355ed4d5fa777d40783e575a07adb.nq.gz
│   ├── da5f13b4dc73c21f0b42fbbabdf11afd87c1548d.nq.gz
│   ├── dd084ea51e220310c945d1465ed518dc576039bc.nq.gz
│   ├── dd1591d3e995f3dfcdbed860e31c73e4a484f1e4.nq.gz
│   ├── e2440a2e3801d9610ed12e348b5e79c7579e40dc.nq.gz
│   ├── e31e69f07dfc9fd2e2e50721e2f1d9b3fdb98aa6.nq.gz
│   ├── e553e29ad1736b5d712b3b3626aa0f198944b35f.nq.gz
│   ├── e5ac3f2b337ba8a9814d27fc622df529a69805ad.nq.gz
│   ├── e6b9825c7c8e9a9c980be297da9aac26bce803d7.nq.gz
│   ├── e6f3ef69285098c4e42781daa846881fb43daa50.nq.gz
│   ├── ec3c312fba71a7e6b57120eb32763b54e3ebc809.nq.gz
│   ├── ece748470f1ec163dd04eaa6518620a97f6ce675.nq.gz
│   ├── eecd67c4a2090d81c67c34c3db5c276763bb45bf.nq.gz
│   ├── f31c330243e1e8a6731f8384bbbe22e74456c926.nq.gz
│   ├── f3fdd2e989c89383d19c0d0a4cce32861652b20f.nq.gz
│   ├── f4a792a3be027705b9568cb116b1a25ac07d1505.nq.gz
│   ├── fad873d620ee40b7f2204f515637ade44062bb02.nq.gz
│   └── fdef97bea4e1b2dadfa5afd869becf65931416d5.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 3bbcc6e8a7bd2c05675b316773796cc7f7fe0a96.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

12 directories, 101 files
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

[scikit-image/skimage-archive](https://github.com/scikit-image/skimage-archive)

---
*Parsed on 2026-10-21 by [repolex](https://repolex.ai)*
