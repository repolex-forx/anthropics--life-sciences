# Repolex Knowledge Graph of anthropics/life-sciences

RDF knowledge graph data for [anthropics/life-sciences](https://github.com/anthropics/life-sciences), parsed by [repolex](https://repolex.ai).

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
lexq download anthropics/life-sciences
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 00dd850d85e573f30809d4aae6c930fc03bdf079
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 00dd850d85e573f30809d4aae6c930fc03bdf079.nq.gz
│   └── repolex
│       └── 00dd850d85e573f30809d4aae6c930fc03bdf079
│           └── chunk-001.nq.gz
├── blob
│   ├── 000139d8b5aeca0f47cb3c21e01b9279571fc7d9.nq.gz
│   ├── 043399988974cd4c61c598135bf5f32315f92278.nq.gz
│   ├── 09afa780816983ae1d9b70036733a491530ec20b.nq.gz
│   ├── 0c4a45401ad06e661550f10507432af644184b8a.nq.gz
│   ├── 12212475adb1d44a88f2310169e89b6512248602.nq.gz
│   ├── 124750e92ebcf31fc3cf4f23f3ee711b40f9e382.nq.gz
│   ├── 1695075a42275796b36f53bbf504f62187adb181.nq.gz
│   ├── 2644c836208c0162e84cdfae930d18ed971e367d.nq.gz
│   ├── 277fc9704b5961f149369bd8ae98589c5a9752fb.nq.gz
│   ├── 2e505d5ba88096891b4c25c062813c4451452a14.nq.gz
│   ├── 3057216242834e709b65829337e9daa33eddd440.nq.gz
│   ├── 32b69fcbf54db7fa7af2b7bf90202508ae427d37.nq.gz
│   ├── 381f1558ceb2fc5db19e9a445e170486dafa0009.nq.gz
│   ├── 3c3c46ac6cf1979c8455e94e0db01fd61c9a7bc8.nq.gz
│   ├── 3e23a1927b378afdba5bb03af87fb5b5276fcedd.nq.gz
│   ├── 3f218f44bcffbe42956c9edfea3117184abc4de8.nq.gz
│   ├── 3fb4e75e7616fcaa31fde16ade39f2ae23ab5b3e.nq.gz
│   ├── 40a7b6eb0a3be571a9bf755dfc64795117e656ae.nq.gz
│   ├── 525ce851c796a21818f0f209226a9f62b56d65ac.nq.gz
│   ├── 52757903620b2565f7d80d253b6386d7d5820302.nq.gz
│   ├── 5e9c5184cad5257bb75cb020ad14507c3c264c61.nq.gz
│   ├── 5eeefde3e9f41be99eddb0305fdd281ab53b8cfb.nq.gz
│   ├── 604d966e0cf31fdccaf862cba94736b80c85c435.nq.gz
│   ├── 625a74b34170774f3276066149a42cde2f3e0116.nq.gz
│   ├── 626e3d6a74e4978aaffe425fbaf5b2f2accb3949.nq.gz
│   ├── 63a1aa5c47e32b1a88838bca16c207e305b1efc7.nq.gz
│   ├── 647c8f15860b2d2c8cc76669c4bd0a49399991a7.nq.gz
│   ├── 6494766c80da066350ac0c267e998e7e40b22974.nq.gz
│   ├── 6cbcc168ec0a881902427a955dc1d5bfb06c574e.nq.gz
│   ├── 6d5acff80f431a6b8ed287b70a2065adc04af0e9.nq.gz
│   ├── 6e5316c3a040620be0219b980b8733a1642023d8.nq.gz
│   ├── 70bafb9f7b1b7dadb3ff5ba49be92a0511917b6e.nq.gz
│   ├── 7231fc1af1c9974e4183c22f05e00f370646a2b4.nq.gz
│   ├── 73530f24bd068026aba09a14f15580c97a7ddf09.nq.gz
│   ├── 73ee0e482db77119042429d6d9353514099b450d.nq.gz
│   ├── 73ee4d777571dee3a4cfa1393b5f8c4d61766eda.nq.gz
│   ├── 78592fd5cf34f6b364e00a38ac61a4410897c1f4.nq.gz
│   ├── 78a64f78882750f21d1e5c30bc60d1f2af024ec1.nq.gz
│   ├── 7b55611e89dfa7ace30b52e8e6c8c52110beac64.nq.gz
│   ├── 7ed56227acc13c64420e2d62bef127ed9fdc1c44.nq.gz
│   ├── 802bcba30c01d1e7bffd53249924cfb412c4f6fd.nq.gz
│   ├── 827b68392b20c774a472039e7d8fe4aade8465ab.nq.gz
│   ├── 8436f56b3cfe6c366bd71ee41d7573ba96da4c3e.nq.gz
│   ├── 84bf4e02c709c5412dfa1991f1423954b10402e7.nq.gz
│   ├── 84cf808a9ae674a54ba02fa252b7181c11fbe290.nq.gz
│   ├── 860059053f2a539cad745ea228bd7fe6e818150b.nq.gz
│   ├── 870b0643f3014e1fec4c36e0f424bf4727867fa6.nq.gz
│   ├── 87378061232d9f5752edb7b47e8036cf820bc66c.nq.gz
│   ├── 87e3fc743ae469040903c93512d3347fc4628fbd.nq.gz
│   ├── 8864aab9b26654c83ac87223c2ddba69e4467d67.nq.gz
│   ├── 8baa529f05a1b5c158ba19c493c76dd7a3f992a1.nq.gz
│   ├── 8da8b6ab21aea67ed4e4e86cf491153742f2dfa1.nq.gz
│   ├── 914b151d803d1e7bed4be585f2dad82dc2d273dd.nq.gz
│   ├── 989530924d583299b84108e4f3866b3fe547843b.nq.gz
│   ├── 9d0185e9256ed75c8a1b3ca0cac6c270cea84a61.nq.gz
│   ├── a139a4dbe32900d6d8860b6268c5c2effab6aef4.nq.gz
│   ├── a1eccb38711de95a2c9f4efec6ce50137656e65c.nq.gz
│   ├── a331d61311fd883f60f567106604dd49466df9ff.nq.gz
│   ├── a5f698d7a153855c5b1fe2ba0214a617eecc490b.nq.gz
│   ├── ab2a9a3a9862ada6dfea65819ce4f8da61778e3d.nq.gz
│   ├── b3fa0d3ed4418030670836cbe2fad262c739b179.nq.gz
│   ├── b7097c2b56469f70d3feb0604c88f29c290b4261.nq.gz
│   ├── bfbd9d0361116bcc9a1d58c64f52cef7a6d91c0b.nq.gz
│   ├── c1a59290df66f56086bdeadbde974184b04fc90f.nq.gz
│   ├── c377b144eb2662fdf504c7e726edb17559631e29.nq.gz
│   ├── c65b9a40e887c13d65befcb646b6cf5843bd696d.nq.gz
│   ├── c6f8dd0b3f8248c552ca9b335c3eed923987283d.nq.gz
│   ├── c9f2dce92159f433e85eb84b9f07ebf4553b247e.nq.gz
│   ├── d0f4d0e25abdacc8a0dbf93144e35a2b35c03a52.nq.gz
│   ├── d20e654700d4c42ab0628c34a5ebb828f2b03cbf.nq.gz
│   ├── d282de060ca322bab085544815f31608af3a6325.nq.gz
│   ├── d2a09c54d4055211953f557bc50c3f949137fdd8.nq.gz
│   ├── d32014be9dd57745f8db3d4ccd28addad07d9d8b.nq.gz
│   ├── d5602e0de436f73671b6c3eca5efa5d5bb06ff35.nq.gz
│   ├── d7f558eb244d33e5f8aaa2ee8a3764da5000d8a9.nq.gz
│   ├── d84d11047a98adea1cacdf2b9b2e151637037ecc.nq.gz
│   ├── e53256ab7bb4592772397f38776386ba85dc9159.nq.gz
│   ├── e54768c4efa9c98c9a00acfea8dd5db7846cb286.nq.gz
│   ├── e71126053bfbde754ff445dce006a718aaffe42b.nq.gz
│   ├── e729b5573a87140244c91692d31bc15b332d3044.nq.gz
│   ├── e7edadefb0a906e6d8323af6a790ee7e67a4d3aa.nq.gz
│   ├── ea24b77741ce9a5ada324f3921dc83824ceebea2.nq.gz
│   ├── f0061f9ffe3f6e5f493854c6bd490a39d1521fb5.nq.gz
│   ├── f101ceb8845e9ef51d38d18a527724fad46c1f65.nq.gz
│   ├── f1ba1f126e20cd7d0d1b0522e91209d0053d7e13.nq.gz
│   ├── f32a1d34417671b890f498c48e5556fb67107214.nq.gz
│   ├── f477487cc1594f3a9308073e5ae705a51a83c341.nq.gz
│   ├── f94423d46a7680550760ba390bb996d84c50be13.nq.gz
│   ├── fab94ebf92b4c3d0d30ce2dfebe57b1919939dff.nq.gz
│   ├── fb8258b52826e3da409be34db6fc7ec7b9eacdbe.nq.gz
│   ├── fd25e8086099a16acc7d4134fc30713424211d82.nq.gz
│   └── fde5233c882a08da57c78d5ac354123b728ba435.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 00dd850d85e573f30809d4aae6c930fc03bdf079.nq.gz
├── filetree
│   └── 00dd850d85e573f30809d4aae6c930fc03bdf079.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 102 files
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

[anthropics/life-sciences](https://github.com/anthropics/life-sciences)

---
*Parsed on 2026-04-16 by [repolex](https://repolex.ai)*
