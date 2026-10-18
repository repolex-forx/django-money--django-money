# Repolex Knowledge Graph of django-money/django-money

RDF knowledge graph data for [django-money/django-money](https://github.com/django-money/django-money), parsed by [repolex](https://repolex.ai).

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
rlex download django-money/django-money
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── b255e278870a24cf70b200787c5fa4c8081df465
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── b255e278870a24cf70b200787c5fa4c8081df465
│           └── chunk-001.nq.gz
├── blob
│   ├── 0191da14abcb99b1852a8c0f202390d12722c14f.nq.gz
│   ├── 098a240201454392d0b8089d179c52fe91fc0cff.nq.gz
│   ├── 0f341c7b0ca191bb91175026a836aef971215e12.nq.gz
│   ├── 14e0e1e48e88e68357d6c9c01338c7a96ca94ce1.nq.gz
│   ├── 15a45715763cc794e8638d3256135b7c592dd8f2.nq.gz
│   ├── 1731e3d5d41961466bda5a11df03b35e83f3948f.nq.gz
│   ├── 1b614259e5b53aeb9198bac24f9a289b997306b4.nq.gz
│   ├── 1f912e49ac3a820e82ae108d6cba943322b1deaf.nq.gz
│   ├── 20d0168b3983a7eeb74830335e6463c3f53e8325.nq.gz
│   ├── 22adb99f4f3e3bd0347d104f87e311bb5e7d5dba.nq.gz
│   ├── 25984567fca04e2195bf904205b119664d97c316.nq.gz
│   ├── 26b80c4bda0f4c69bb3a50661e97a6fcc0c1f482.nq.gz
│   ├── 2a78b486cddbf3de7fd0e10d6bcfd9019383e6df.nq.gz
│   ├── 2d97df58b65a9c252914ae2f1a4348b4a45449e4.nq.gz
│   ├── 32e1a3a8e34938fd53651fe4858d3f82af6c58ee.nq.gz
│   ├── 351589ce973c10cd809aeb35e8ab58ace1caf6c1.nq.gz
│   ├── 3528bbe28add063bdefdbb6055466ff821b890b3.nq.gz
│   ├── 36fad2c6925196c03bbf692ae25b4380ff002a58.nq.gz
│   ├── 3ac7e12012ea0096cb314db6eae9722eca067fa6.nq.gz
│   ├── 40f10c9af368db78ac4103d96a1fc65249595cf0.nq.gz
│   ├── 42f9f0007e883e7a455aa554741c50d2a8f0747e.nq.gz
│   ├── 444156e5b7a9548fe7c970482e9087149b4dbde0.nq.gz
│   ├── 48902292c0e3f9d503248d6df44b3dc26deb4d39.nq.gz
│   ├── 48e2af9be7d01ec052b86d789c1a2a9327a9e466.nq.gz
│   ├── 4b1a63f6696b503d48f4abaae09c652e529bc78a.nq.gz
│   ├── 4cc9d770145fce1c880bea23ca58212f0c318a23.nq.gz
│   ├── 4e52bbe80c35270b92fa180a2698443146650174.nq.gz
│   ├── 4fb1ec677402e32f15f0e72d6f86668cb5c9bde4.nq.gz
│   ├── 51c436b7b1ff5a08d08d1ef473ea019a121e13dd.nq.gz
│   ├── 57cfb3adc5c48e959ae76151e6fbd5ff442a084b.nq.gz
│   ├── 5a9ac0d576081dbda67ba0774a56501ead70a2f0.nq.gz
│   ├── 5adb10bbe7afe2d1991af899b668ded1bf2aa86b.nq.gz
│   ├── 61d954b2bbca23ea0d67f661a45b2a7fbb6286e5.nq.gz
│   ├── 6334d133eadb55382a4829df7b3b318e7f0594cf.nq.gz
│   ├── 6ca3bb53487d5d2a4ae3a7ca9f28238b07a26f57.nq.gz
│   ├── 6df84fa3dc8d50ad692cc0850b727373ce780efe.nq.gz
│   ├── 73354a5f03d093ac405d322628f8549bf5c00dfe.nq.gz
│   ├── 754db28eb5fc1cb82c3042b6c9a8fb6a8e26d9cf.nq.gz
│   ├── 763a728d4d077027eeb77ad604660fd7c3413da6.nq.gz
│   ├── 77035e30487fd2c719bb16b951df62edac5b2e7a.nq.gz
│   ├── 7727127bfbd16fe8095eaf2ac52f62636558d6f6.nq.gz
│   ├── 7989cf40fa7b159c9f4e07dfcf0a2c85c080ac71.nq.gz
│   ├── 7b06482929dd4ea52fdd23d26b526d044f7fd6fc.nq.gz
│   ├── 7c21c9d539ac39373ada67dd9fd064dbed97b044.nq.gz
│   ├── 7f8baee3584d4d76275bee3aac9f151b1684436d.nq.gz
│   ├── 80ec3dd8623bde35865997c631d5762565e8d12f.nq.gz
│   ├── 88a4c3501ef2abb2f518e150974d563d0859b96e.nq.gz
│   ├── 90a7be5920b0196b0eb049220e999a270c9a5cb3.nq.gz
│   ├── 938c2a88b108ad06e4d0768bed6a47e6ae14c168.nq.gz
│   ├── 9925ee9c4da16e1720f7d4e4b9387ed933d9cb92.nq.gz
│   ├── 9e95a68f0b9e6e6af4c06543141df72e6e9f0871.nq.gz
│   ├── 9fc8229269bbbf3fe9312a2e3fbf44fd8234f3e3.nq.gz
│   ├── a027e89189a623965dde7ff772c5557b1613b810.nq.gz
│   ├── a4fce5b8e32f394776fe4fd981d13270ca63b3a8.nq.gz
│   ├── a804e7a1fa449eabc62f6b11577210dea5cb18df.nq.gz
│   ├── a92df1d92d0cd1850d64ada84265aed6409ae1be.nq.gz
│   ├── a9f07b714e386a01e412f91eacd572517a462cc4.nq.gz
│   ├── adbc5cfb48ceda40e7fe08b0274a82b5e24b886a.nq.gz
│   ├── b202327a862e70f2e572cfc4b3c1888d99330d78.nq.gz
│   ├── b5699edf2c8810101022dc8d868be2330f89eab8.nq.gz
│   ├── ba5b95f53aa608cad53873ca03ac587f75028991.nq.gz
│   ├── baedae59cbc9170a488666b7cae66af3ea65c06a.nq.gz
│   ├── c113648ebba11c1248dc4cee268315e3952812d9.nq.gz
│   ├── c1e6a19c453afd2812a8b004b6d5a9ba67c719fd.nq.gz
│   ├── c436d858da134586bf84b6f5786834ad68977121.nq.gz
│   ├── c692273407d2a92304e67fc5e978b181f6b716b4.nq.gz
│   ├── c8fb70de5990c031ea591719de4817671a2442fd.nq.gz
│   ├── ce8f1d551ef720b84a7b29dff5129f21600062ce.nq.gz
│   ├── d76f0c589d87aa00145da2ff4efe119726f72fd7.nq.gz
│   ├── d809f74c9f1b0024a1a97a1a893f4929000646b3.nq.gz
│   ├── dc4b736cf85d9a2ef2c5530c10aaa2af8ce37f5a.nq.gz
│   ├── de1958be2e1a5e72bcedfbd2335a153212966983.nq.gz
│   ├── e026ec2d576c7a24cc5f54a0c128712f0f725566.nq.gz
│   ├── e3119a9cd9f817deedfc3a07dfce4d2f72816355.nq.gz
│   ├── e582053ea018c369be05aae96cf730744f1dc616.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── f01a1419cba7f7ba3e8f1cfb25d5d6d4c96d7c81.nq.gz
│   ├── f5f992fa0b0a74fec4aac796d9f81d59720931fc.nq.gz
│   └── ff61b86ef8809df616a26343131d88627adf4e7e.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── b255e278870a24cf70b200787c5fa4c8081df465.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 87 files
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

[django-money/django-money](https://github.com/django-money/django-money)

---
*Parsed on 2026-10-18 by [repolex](https://repolex.ai)*
