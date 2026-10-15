# Repolex Knowledge Graph of sphinx-contrib/typer

RDF knowledge graph data for [sphinx-contrib/typer](https://github.com/sphinx-contrib/typer), parsed by [repolex](https://repolex.ai).

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
rlex download sphinx-contrib/typer
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 9a1e7e1b08d97326b341dc7ccb34f4851d0b0fb6
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 9a1e7e1b08d97326b341dc7ccb34f4851d0b0fb6
│           └── chunk-001.nq.gz
├── blob
│   ├── 0250b9812dc28a499d0c5b697587ce1217c705b5.nq.gz
│   ├── 091679ceb93a0910707ab1e1eb8beea720633d4e.nq.gz
│   ├── 0ba1f5b12c209e2f79aba5e3a5c75b665d124ae3.nq.gz
│   ├── 0ffefddc42f3d644cf454703be04213f2ca6da03.nq.gz
│   ├── 10f11715d5e438527f43ec6d769e5d80239ea2d9.nq.gz
│   ├── 1310a5d351d14496d1be08266a13c888ee07bc6f.nq.gz
│   ├── 140399432165ba1a9805849d5089cb4e440f500f.nq.gz
│   ├── 215607bd51d2283a7f6933313a59cd7257786fb3.nq.gz
│   ├── 23980f450a7d145a59757a632fc52a67ee58299c.nq.gz
│   ├── 24dfe220761663b6f8eb35dfbb10a7abb42fd347.nq.gz
│   ├── 2824dbd6f779a2566ab5570fba0346b9c296d990.nq.gz
│   ├── 28ace065af0f60deb9c87b1cb953555bba4ccdd1.nq.gz
│   ├── 347bf7872ad5e2b5f1dfad89c978c7b40940145c.nq.gz
│   ├── 37e3f9d5df7e3b84a750e95e052c5611c69facea.nq.gz
│   ├── 3873097fe971215b9475292b9f556e0791dcee7f.nq.gz
│   ├── 3a47ef74f78d4b494ce8820d03690b250c9ed1be.nq.gz
│   ├── 3dfc61f8b1f61639c2517bc33578b6c03c74c527.nq.gz
│   ├── 3e3eae0d9f49430b848d952557f4fc8c16191e9e.nq.gz
│   ├── 529cd402f2092f34e1952eb6e52ea10b597fd3be.nq.gz
│   ├── 5407982d09fb1a9a04adf21996325f0deb54c1ed.nq.gz
│   ├── 549140ad60e173b005cf74db85674d066f0fda27.nq.gz
│   ├── 5a518f0589a22af1e81f2e819b6a66df09609966.nq.gz
│   ├── 6043d8be92d09ed758611d7d11a3f615b3537ad8.nq.gz
│   ├── 651e96f96c0b87c63f715bd977ffb76384af58db.nq.gz
│   ├── 65c3420fb0032427b6982036406941b05b904e88.nq.gz
│   ├── 66860f3b77fb713a42806c7744ceeab4bfc88df5.nq.gz
│   ├── 6935d570b0ae0b184399fc8b919d2ffd073548bf.nq.gz
│   ├── 6bff6cf798f509d2e80818d2973bf4d09fad5002.nq.gz
│   ├── 6e9012765896c1c8c3d8c1834defac6d3b1f0cf6.nq.gz
│   ├── 74cea03822505664053b9c88db99cc6abdc3efa3.nq.gz
│   ├── 75704c779d08a5384a138044175ec999305225d9.nq.gz
│   ├── 766d95221fa682973e61ea85dd9aaa67e653f590.nq.gz
│   ├── 7ea47d66a0044983969a10222f8ca30164ebcc96.nq.gz
│   ├── 8235ea60388e867eb7094ab9cefe101768b2c148.nq.gz
│   ├── 8b92feb12bf3e34d9401cb04e18289ceedd0666c.nq.gz
│   ├── 9092c7a590889e977bc55a2aa5f3d2c5c1360b36.nq.gz
│   ├── 922df8f1c7c7570192de861a9efc2ab80b9bd02d.nq.gz
│   ├── 98141b257b0b746dbd2bfddee8670d9bd5ac9745.nq.gz
│   ├── 99e56b83132f3faebece58701f7d43b5116ba7e3.nq.gz
│   ├── 9ba902f9178bca4c95f43a868b07d74d2ac150d2.nq.gz
│   ├── 9f0921702226dc6005685662e27502bfd697d372.nq.gz
│   ├── a1deed933d16939c1242d4c8ea04705590b685d4.nq.gz
│   ├── a6a241cfee4b0de38df4deded1cef355e3f5d132.nq.gz
│   ├── ac387523929c0e4512ef4583ca089949653b9cca.nq.gz
│   ├── ac5eb99d8dff2bdf137ad7373758a53cf8e4852c.nq.gz
│   ├── ae8655bf73f2aca81202336c2e8641e8222dd74e.nq.gz
│   ├── b32d1fa270d892a4f32ccfad6c325bcc429b8047.nq.gz
│   ├── bbc62d15be92af91f4834f0224912d3b81f80b05.nq.gz
│   ├── bc080bfaa0301b7c2edebcabc8cf2af6cb8aa81b.nq.gz
│   ├── c2d89176e2a06a86b99496c155e9cfa8cc33d4a1.nq.gz
│   ├── c5d834c80720828b9e5bbfebcc242b528e3afb6a.nq.gz
│   ├── cc08ee43ba566ab51910cc40ab251b305b876c37.nq.gz
│   ├── d6abfef605840c2805d2cafaecaa33c2c35b0be1.nq.gz
│   ├── d6b36940762af342f1e37b3467d3a80c1784afa1.nq.gz
│   ├── d6becfb0b11818c56755f5ccb5e1b5300ed8fb61.nq.gz
│   ├── d8e42636395f525088a45915a1c5def5aaabcb11.nq.gz
│   ├── db926e96bb5be809b9cd3a8f84f8a00e442c5bd1.nq.gz
│   ├── dc1ca0e7303e8b18469d6e73398fa3619cc61892.nq.gz
│   ├── dca4108a429defff85a83ae7e3be1c475c2b0f93.nq.gz
│   ├── dcae9ee447a5be64d4c2079ca186aba3da0d0df9.nq.gz
│   ├── e2961a0f6f3b63d31553361f13ad4d6097f4afe9.nq.gz
│   ├── e614d2707bcf7505ddb7783faea74d06af727758.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e86e04170b47dc4e019a50eeb27b919c9939979b.nq.gz
│   ├── e8a6d5893b9796ae619c0c46ffd49cf1d1e4536e.nq.gz
│   ├── f902afa313272b1724ef8967300dd69919ff6401.nq.gz
│   ├── fac8dc67693dbe152a292158c457b9db34c6b8d1.nq.gz
│   ├── fd32f06ef84084ef3581ab1f907430e428ed5460.nq.gz
│   └── fe5301aaed8c2927157413e7234931ca66f25dfa.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 9a1e7e1b08d97326b341dc7ccb34f4851d0b0fb6.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 77 files
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

[sphinx-contrib/typer](https://github.com/sphinx-contrib/typer)

---
*Parsed on 2026-10-15 by [repolex](https://repolex.ai)*
