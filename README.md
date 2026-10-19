# Repolex Knowledge Graph of mkdocstrings/mkdocstrings

RDF knowledge graph data for [mkdocstrings/mkdocstrings](https://github.com/mkdocstrings/mkdocstrings), parsed by [repolex](https://repolex.ai).

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
rlex download mkdocstrings/mkdocstrings
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── e9538c4045166202cc4442c56ae890b94173b9ae
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── e9538c4045166202cc4442c56ae890b94173b9ae
│           └── chunk-001.nq.gz
├── blob
│   ├── 002b2a0406a2be01fdcfcd78c4a90218458ac9cd.nq.gz
│   ├── 04d053f69a771c7a0a193a522237859a39164b36.nq.gz
│   ├── 0536cbbe261b2d97ed3d94f5b1fd86596a2ae486.nq.gz
│   ├── 07633b731d7edd5de3e2e1655c39196c9a4accf4.nq.gz
│   ├── 09210825d0c22a2d4d0383b922f92c0f79c20b76.nq.gz
│   ├── 097af88d7928b7eaf0a21a1ccd9836d1f67ffd76.nq.gz
│   ├── 0ca7fabfe18b401de8974a8668482dfddfb3b9e3.nq.gz
│   ├── 10d8b208f0c0b9adaef2d663ce8db7a59d2cf2de.nq.gz
│   ├── 120df7ae2ca7479b03ea15d18f6cede1a3e3eac7.nq.gz
│   ├── 12f7bb2add8782b7fe0a89ae8a17043a44d6a98a.nq.gz
│   ├── 145615dc479a2a9df250d27bf80db5ed7376d9ba.nq.gz
│   ├── 15af30211d7425b521d520028e92f9ac4e4cef45.nq.gz
│   ├── 161fcbd0ec980ab9e4a384e2ceda3ce11c479d9c.nq.gz
│   ├── 18365bd2da44a148bdbc2b34b583d6733b2253b9.nq.gz
│   ├── 1d8c9a901240fd321ee575a4b5a7e2ec5c02ba04.nq.gz
│   ├── 230002988a33f43c773844006fbefc16ffd5a64c.nq.gz
│   ├── 266e44c0bf6abd7f7189448bbaed8c8f387872fd.nq.gz
│   ├── 276c7e5e06bcf6635c7eace9cbc8092145f978db.nq.gz
│   ├── 2d46305a68da4b9569bf6813f4d2fb1131653842.nq.gz
│   ├── 2df98fbcac88d8d93c9d18648ba7d5a800100ce0.nq.gz
│   ├── 2fcf869f97e3db32d04bba2de14fc59596538076.nq.gz
│   ├── 30571233ab2743c8bfa278db17f69b884823c94f.nq.gz
│   ├── 339c20a8416d3a9ff84348d85e5a4354ac0082ce.nq.gz
│   ├── 35ec8f1917b21691560159f7e6051600f0674f58.nq.gz
│   ├── 3c4058b8548fcb5c5196f4bb4ec78b082a5b301b.nq.gz
│   ├── 461f7e3d73ca89f0dee46d673a8057f563b9873f.nq.gz
│   ├── 4eb290d59ac1bd166116bccefa0e6ca636ed135d.nq.gz
│   ├── 51587578d052005002f5e1f131bfeb180807caed.nq.gz
│   ├── 5677ad2a1aa2af32b38a8e2082ddaa31786a9e2b.nq.gz
│   ├── 594db4b77bea9b9526090f20da3807b1d9ca79a9.nq.gz
│   ├── 5b25a00f43bcb9d2a68e49250995865e6608c26c.nq.gz
│   ├── 5e5386e33165828da961ea66fa0cd5397beb9231.nq.gz
│   ├── 61415d0c6340f7243db1b34843043f98f2bd047b.nq.gz
│   ├── 61935e5d49e2b4f90babe55d6bda7b7401cfc1b9.nq.gz
│   ├── 6270ba3eb02efabd54e73c4bf88c16445145ee7c.nq.gz
│   ├── 64588fdf38088fa82bb3092356e4b53939797c7a.nq.gz
│   ├── 6571bd996a476b5861edc2a0011d8ac1b40dd81f.nq.gz
│   ├── 66197827c711e5904d4122c9c3cd17c0c15e462b.nq.gz
│   ├── 697d5cc6fdb8e1c0075ff7d4a52a6e327c86b7d4.nq.gz
│   ├── 6a802f742ef2a868b634fe85aa36a8e186cf54f3.nq.gz
│   ├── 6aaa222d5f3e1f8ed032eb4d0d99261866b6237a.nq.gz
│   ├── 6cb05666849ff72b1741a9e01d07914219566897.nq.gz
│   ├── 6dded574c7bad74aac6e84b14845cf2aa3e0bb8d.nq.gz
│   ├── 6f0f2faf32486394750d5d5421e2261430b73fef.nq.gz
│   ├── 6fc0fd2c8c8c878f8868203a42b81f0628da2de4.nq.gz
│   ├── 72836ce71f09127e55c5f57394e2f2abfc77ff81.nq.gz
│   ├── 73145eec7e2a896212b2a9165dcc7449f0abd318.nq.gz
│   ├── 74cea744533fe7b69994639370f28fcf3b1b317e.nq.gz
│   ├── 79432d1ebec287a3aa70b6b3c72d39d73509e491.nq.gz
│   ├── 80abd2b478f6ebeb2a31c9d29c3fd493a21d7dcb.nq.gz
│   ├── 812789e68bf5688ca56d42a80caecd04c1e0c4b4.nq.gz
│   ├── 82377e2175cb6a3e81bcd4650e4c158db89a8004.nq.gz
│   ├── 8b4bf9be1ecb53126d7486cd38fe5bcb1c6a7563.nq.gz
│   ├── 91d1001898cfca45aa0ad1a3092b675ab90008d1.nq.gz
│   ├── 92ac8ec5dbe177b6e29da9600c7c3fd18d8069b9.nq.gz
│   ├── 92f7a9ee8023c5a432a4fdc88f2aeecd9b796b0d.nq.gz
│   ├── 97724fa80f2fd81fddb1eb8b00029dc4fee78054.nq.gz
│   ├── 98cbfdd106f6af898b9ceed1ec1f707b532c5173.nq.gz
│   ├── 9ba0fd25bb755f8ee1eda0d46f322b92ec79be9d.nq.gz
│   ├── 9bf4860074a6c180f114d66ef26de7fe2fa0b38f.nq.gz
│   ├── 9cf9c5d4e40ec1e5f7c6a45327554f0b8598dbef.nq.gz
│   ├── 9cfeaf7bb2e83f61caf89e004e6d1062f05f39c8.nq.gz
│   ├── a09379f1b6893041a9e5249ae2b8e054b532cd23.nq.gz
│   ├── a8be8db1716eb9814ce07165ce978b244769211e.nq.gz
│   ├── ba7f20c785c8efbe6f6545948a24f29f1f5deae5.nq.gz
│   ├── c2eda0df52a5c1bd708ad342b50fcc917be81192.nq.gz
│   ├── c9d7338cc3f61ab184e88e96c74e5614ebc39a12.nq.gz
│   ├── cb61d2c0916cbd849ecb6d32006a20a44a18e2ac.nq.gz
│   ├── cc0f09f312be304bb2cb2c5c8e2d444d130ec455.nq.gz
│   ├── ce91662b3feb6d0512ed974ff74e5a11f90b1d2f.nq.gz
│   ├── d46138d4961a06453c56e733de8c6691475ed5f0.nq.gz
│   ├── dc711a48b9bd2f8029f3af22e74526a2cb8661f3.nq.gz
│   ├── dc9a8f17c6e3f0117661042120c4413a21065bce.nq.gz
│   ├── de5bba87c67724bccf4739396c1d991aa99486f1.nq.gz
│   ├── e287f3e8b4289f9e2e8ff2445c59d6889c4ebf5a.nq.gz
│   ├── e3e4168ce5c7b567c90318b15a17c5e3f599650f.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e6bb5b91b56c550fab69e0f2898006069366f3da.nq.gz
│   ├── e9e63022b1086030d257bb9b8d7ab2db1fa3ef76.nq.gz
│   ├── f072271cb235e97740a9887ebc76955c62749a18.nq.gz
│   ├── f3b208974a079769f2da13bf76a849d9bca1e995.nq.gz
│   ├── f65bd6207f28d359f66d56cea554192308db986f.nq.gz
│   ├── f6ab1aa2cdbbb6aa245be35e5090520815c3f7ef.nq.gz
│   ├── f97321a5d0ecc1a536fc3eeca5a23f446efb07bd.nq.gz
│   ├── fa643a48db29a6af0351a889c887632cdd63ed1a.nq.gz
│   ├── fa812cec2b5033767baefb236aca89aaad4780e2.nq.gz
│   └── ff1786efe5b70df9a2b06838057905d01837b505.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── e9538c4045166202cc4442c56ae890b94173b9ae.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 95 files
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

[mkdocstrings/mkdocstrings](https://github.com/mkdocstrings/mkdocstrings)

---
*Parsed on 2026-10-19 by [repolex](https://repolex.ai)*
