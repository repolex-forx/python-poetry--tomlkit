# Repolex Knowledge Graph of python-poetry/tomlkit

RDF knowledge graph data for [python-poetry/tomlkit](https://github.com/python-poetry/tomlkit), parsed by [repolex](https://repolex.ai).

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
rlex download python-poetry/tomlkit
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 858186a3edb4cad6d66281ee7ad5fb07fe820406
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 858186a3edb4cad6d66281ee7ad5fb07fe820406
│           └── chunk-001.nq.gz
├── blob
│   ├── 000b94c92e74eed0a1df8c23a537c09149bd2f5f.nq.gz
│   ├── 012a2fbdb9194fa1e1b747dcd8d66cdff50b2e6e.nq.gz
│   ├── 02f25d79dc9dc85af7b7a9aebe03d698ea43124a.nq.gz
│   ├── 0ba163ab895541395f035dc9eedc6ccc4bef2ee4.nq.gz
│   ├── 116de35214674f7530978e90ca9b8bc13db6aa1a.nq.gz
│   ├── 13493aab29766e02c2096c4e4b0dd58c98fc5f8c.nq.gz
│   ├── 153be5e2f6f996741b53558d8bc7825ec091699c.nq.gz
│   ├── 166e8e54a30f7d71878e7f0b9a651daba48f5614.nq.gz
│   ├── 19155c818208099975b6a35c05a18527d1940dca.nq.gz
│   ├── 2485730432cb9d26a5024075c34ad95933e3679d.nq.gz
│   ├── 2650ed372390a7af13e28d4abf64d4daf4c6049a.nq.gz
│   ├── 2aa36d5c7593ecf1551056aad60cec58e6010edf.nq.gz
│   ├── 2ba9192a7334e0ee088d3347dfc9a1280b01a8cb.nq.gz
│   ├── 2da7099d23199ad4b5e9aaad57f6b568c7ade2e1.nq.gz
│   ├── 2f0fc034b09ed9df9faa17b3e8f8e36b77432f12.nq.gz
│   ├── 324576bf939a85b4ec3664d67ef1be6ac475d3e8.nq.gz
│   ├── 351c79e70ed1df306ec3f476b9059688e80d5a9e.nq.gz
│   ├── 3585d56c98aaaf760c27ecb2fcdb894df4fea368.nq.gz
│   ├── 3628c5b67d113987e3cd5aee9cd900f2ed059338.nq.gz
│   ├── 3737b80e78be9511d03f2373e8d8ad189705a09b.nq.gz
│   ├── 38856c8737a8e8066b1204d85b676883e2a292c2.nq.gz
│   ├── 3c205741a7c4fe121c6b3a5aadaa104a6d623b4b.nq.gz
│   ├── 3ef203c860d474caeedb1160d522a6fe43772786.nq.gz
│   ├── 40159ef58074297bc8cdd4023b632bcab3020ff9.nq.gz
│   ├── 44cf2b30e6888272f6b278672d0077cd5948b1e7.nq.gz
│   ├── 44d5cd6ca5792f5eb847f9e6f0e8bf55c840a372.nq.gz
│   ├── 473357e8d62dc306a8afaf1841ec695b8ff65efd.nq.gz
│   ├── 4a88fd4857b21114e1ffd58b8604d29c35958d9e.nq.gz
│   ├── 4f2d733b731f052f95f008d23fd2c94375fbc513.nq.gz
│   ├── 586cf8ac7188c2e65219de4b3e8d128c487261f5.nq.gz
│   ├── 5c4689d95cf968a43f42cb7241b625fa22948b44.nq.gz
│   ├── 5f9cc33b409adb539f9330e312d661096da73ccd.nq.gz
│   ├── 6239539181bf8d4a9cbb3bc25f87b8a2d16ced0d.nq.gz
│   ├── 667353eeb98e6436a5c4df96dff32d3072654622.nq.gz
│   ├── 66fa224397bf1c370ae22369bc78b54d265b7e12.nq.gz
│   ├── 69fdbb530f7bdedfd3517276ff8cbbee66ad194b.nq.gz
│   ├── 6d2f73a963b8ef4474afc96c5cec4291dee27be4.nq.gz
│   ├── 6d7d98d99ee1043ad3a736135770ef0860835e94.nq.gz
│   ├── 6e6f085d53063cb4b044ba177117d86ce029fdc7.nq.gz
│   ├── 71fac2e101150b35482b02c1e040789fe29bf835.nq.gz
│   ├── 74f71bafc040e4bfd15b19f1573064543b0f439a.nq.gz
│   ├── 7c3506965ea3909d1e9f178ec364f4e4ef342389.nq.gz
│   ├── 82ab5799d82e3c1dafc93f179ab5ba958584e33f.nq.gz
│   ├── 83cf5d9fb337c073b6719086a5475184414b469e.nq.gz
│   ├── 84ef7782313e156c86550cc652a7126abe098994.nq.gz
│   ├── 852c25d4ef7171b7290ebd36b8b909a51671f50e.nq.gz
│   ├── 8589df9740350ad7e789723a86b1855283b913f5.nq.gz
│   ├── 87b90a99195394d0b7ba779a66842fa6d28365ef.nq.gz
│   ├── 8a7d301322e8cb01711523278c9a5211909a37a5.nq.gz
│   ├── 8c7b1a64f0ae42b19ddbc0f2f4f13f82304ee45f.nq.gz
│   ├── 8e2715041a23900771f15b90a31057bc209ccd65.nq.gz
│   ├── 9347ee6d1118eada1e571e21dfc785d04edd5ee0.nq.gz
│   ├── 9727d9c6f672d2f91389424a771d1fa835b24bb3.nq.gz
│   ├── 9b18a665de5ebfc82d9ec0a8cbc3b7673df53ab2.nq.gz
│   ├── 9b84da9d526fc2f244ec5da4ec1feb120f65ea67.nq.gz
│   ├── a1c30cb929f3ca42684e09be92033d3b94f4a561.nq.gz
│   ├── b170ce53c039087a0f2310449aeee66eb7b9fa32.nq.gz
│   ├── b2e9caa0e0d36e66f1385506da8ada7af460a748.nq.gz
│   ├── b2f3c492116bb4c9e5071d488ce640c1e3d59497.nq.gz
│   ├── b308f1203e4f7e9c29486110dd51c203993de0d3.nq.gz
│   ├── b5d824ec5a688463817a68a6194507b18fbacdea.nq.gz
│   ├── c2a68470604e1935cf9b84927cad15fdc40ac28f.nq.gz
│   ├── c2bd97822acf09c62e344ef59f2a15fe14964d10.nq.gz
│   ├── c4f96cf14c09bbc2aca5e8717b816bf8fce28c9f.nq.gz
│   ├── c5b923af032896d19afa22b539e8a1a2979ec6e7.nq.gz
│   ├── c9b7cc47df2292ec6605b565b9fa18a652aa64e5.nq.gz
│   ├── cbb9ee44ca8f94f81999e8c3ed29ab32cf2e4e50.nq.gz
│   ├── cf6134aaa3dbe2a6b118a6f4cdec5014f7222436.nq.gz
│   ├── d4bb2cbb9eddb1bb1b4f366623044af8e4830919.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── eb04efdf6ed2fe5fae249c69cf8e426dddf23a4c.nq.gz
│   ├── ebc4dcba75a3d06d420d56c4fd8280b78bcf7448.nq.gz
│   ├── ed0ccefd983096e09b0cf79bb5614b00b956404e.nq.gz
│   ├── ee29442bb98481d5d2559b24df6d48d581ba133f.nq.gz
│   ├── ef7e9ac1708624da87aef533cac83a19f3c52212.nq.gz
│   ├── f05426f5f77269aed3e7d38d481772c2797fd90b.nq.gz
│   ├── f5862fa1e6572bb24b92f364d19c05438421f0ac.nq.gz
│   ├── f7338866a5f5d6dc2bc68847fd7285610a9e11a0.nq.gz
│   └── fca881b9cf9f6597b720d416ab0e4f5781040a6b.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 858186a3edb4cad6d66281ee7ad5fb07fe820406.nq.gz
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

[python-poetry/tomlkit](https://github.com/python-poetry/tomlkit)

---
*Parsed on 2026-10-10 by [repolex](https://repolex.ai)*
