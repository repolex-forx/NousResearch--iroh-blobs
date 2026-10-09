# Repolex Knowledge Graph of NousResearch/iroh-blobs

RDF knowledge graph data for [NousResearch/iroh-blobs](https://github.com/NousResearch/iroh-blobs), parsed by [repolex](https://repolex.ai).

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
rlex download NousResearch/iroh-blobs
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 46454523802b4486f052421600c9e551bfb4f59c
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 46454523802b4486f052421600c9e551bfb4f59c
│           └── chunk-001.nq.gz
├── blob
│   ├── 049ef4855fa1dad78f925936c75627a15949c5dd.nq.gz
│   ├── 07141256c73d101f1138024a2733173a2646df3c.nq.gz
│   ├── 09b2e5b331099c09b97a86faf1525273e94ec720.nq.gz
│   ├── 0c6ea135171f901b9fbe214031875db3664a65b3.nq.gz
│   ├── 0ff5cd2ab1f733b1e9080e7fa05bf1c93e1ff6bb.nq.gz
│   ├── 117c59e256a705f6e12eab7d87cc0bcb183d4ce7.nq.gz
│   ├── 19802836366267478df5529c67af271b7ea22cba.nq.gz
│   ├── 1b5c6d238c4bd29a3f5988f56dbe8c84fa1df525.nq.gz
│   ├── 1c3ea946576002f4cef81c456189084232cf053c.nq.gz
│   ├── 1cbd01bcc374e723b1b9df0086dc318824e9756f.nq.gz
│   ├── 22fe333d43617f5263b1c0d6b1444815e9e82e50.nq.gz
│   ├── 2b658bfea0cfa44cd84bc8c290c9ffdf59a039e9.nq.gz
│   ├── 2ccb8f3baa398d4f8c807e3c2ce3399ff4c77ed0.nq.gz
│   ├── 2d5f18dd41d651dc325cf4d6349130670109cc50.nq.gz
│   ├── 2e1144b1077306821160da4632cc35b2d9aa6c55.nq.gz
│   ├── 2f374e8fbf407f955267616fab1af11396abd1c9.nq.gz
│   ├── 2f4457550a06bd368fe7da9eacd5ff31e20df34b.nq.gz
│   ├── 2f86878741870462aa6e5537877b5989ac7d1dfc.nq.gz
│   ├── 33c21f66f64797ba663b11094606ac3b146fd082.nq.gz
│   ├── 363a2ec60fa3c703a25208f9625591d32b11ba7c.nq.gz
│   ├── 3695832eb6db2c8cd05a8744413d80b588ed08ec.nq.gz
│   ├── 3b09f8daf6a081955e971d5f05979e2b0e1ace57.nq.gz
│   ├── 40ec56f89f4950082af86099b1415c4dda2cfaed.nq.gz
│   ├── 411cc2848015174310a8fd4ffe57e00419ea2cab.nq.gz
│   ├── 47cda5344fb34e897a9db0c2e7bcfa3e8ecee43e.nq.gz
│   ├── 48946abd6266c1dc16685a5981487fda13aa7b9a.nq.gz
│   ├── 48fba6ba32364079e829b7c9522289f0853120e7.nq.gz
│   ├── 4cdf9ec0c399619cd0a202b0f69f80f2c065aa3d.nq.gz
│   ├── 4f0a061fb0432b6fc5e2db3cee1ba9bb9f7f3c3b.nq.gz
│   ├── 4fdb306067e0353cd6ee18b664e7374fb89447bc.nq.gz
│   ├── 502215edd9980486fc21b99dfee8260ad6d902e6.nq.gz
│   ├── 5077c2632513a44b7668e0b1eb3cfe44a7081afd.nq.gz
│   ├── 546dbe70245eb84fe2d42d5d54b3efb6358ff4fa.nq.gz
│   ├── 5f76b7fff3f34e6f5e8047ff53b6a7bd73905cd0.nq.gz
│   ├── 5fe929488d6719d714c218c2646451018736460a.nq.gz
│   ├── 6a54cff22ab239eb55962cbee048e085227a94ca.nq.gz
│   ├── 6cbb5b24d532c7dae6828d9c1dbae9568fa85adf.nq.gz
│   ├── 6cc5a1f3eef36f61df5fb9b10cc56638bd0bf679.nq.gz
│   ├── 6f4aaa6ce51dd27c1712d9bfc5926c5c346a7574.nq.gz
│   ├── 7359d5b5cfc223d3d6e5a7253355a7b07db6430a.nq.gz
│   ├── 764970a8e166a02d22f31d461cafa506b7d9fa53.nq.gz
│   ├── 7bc3a3227adfb511ca70611d44cd118dfba4d162.nq.gz
│   ├── 830e75836ead08e140c8bf78704433e14237170c.nq.gz
│   ├── 84f0a21be5f4d75f0abf2fa3ff3b080d2dcffc05.nq.gz
│   ├── 897e0371c06395b0e53df96661ae512461db4216.nq.gz
│   ├── 8c948c672bdefd4a521d8e618aacd8ac5e9f55bd.nq.gz
│   ├── 91a737d767c08437d9b53ec4943a065e79bfd10b.nq.gz
│   ├── 92ba46f7c9400dfd1a4242f405d027bfcb04fa98.nq.gz
│   ├── 94b6aa63c526eb9871528be06b94742de9063f23.nq.gz
│   ├── 9716faf8648867810b9f79a26f7daeac27f53737.nq.gz
│   ├── 98563057e7e3573f20dbf898430fc830cf9a4cd8.nq.gz
│   ├── 98d96e458c6f4a09b6d918658793fc17311d829d.nq.gz
│   ├── 99241e68564f3b81b7fe477d07f85b39deddc550.nq.gz
│   ├── 9c30d1b79603d724cc67696b6edc8cee6b951b76.nq.gz
│   ├── 9dff077f04e4a2fc565be3e9872355c935e8a472.nq.gz
│   ├── aa9c15292c2b4d8236a1fa01e6109224318fd798.nq.gz
│   ├── afee382a3c2d0639056b380a693f1a5357876a88.nq.gz
│   ├── b235a8c6b300121f27b16c74d66e679e32cf04b7.nq.gz
│   ├── b2a48b5e43c96f747f5ce4eed0c83af457fe8c92.nq.gz
│   ├── b42f88f47085f03ddda4c7fe058544973b8568bd.nq.gz
│   ├── b612e57e7c91173449934cc3261e421fe64c1084.nq.gz
│   ├── ba415df414497ad7e4542a9783d4563f217aad91.nq.gz
│   ├── bb2a4118fbb40d2bc80443156d381be4621166f1.nq.gz
│   ├── bb557e53e0033269efee9efc480aacee4cb4cf56.nq.gz
│   ├── bc9c256940f6df043efd20b1a10c749f06f3e2f8.nq.gz
│   ├── be006de9a1ae3b9628e796c74277cd6d61e0a34a.nq.gz
│   ├── bf78bf793c34e7ca3fff099ce288ce76155f0d1b.nq.gz
│   ├── c021b7f0ad7f85ad66e36086ad39ece48ad39253.nq.gz
│   ├── c0760a088a2c12169369afb6916a3ad5aa2aa7d6.nq.gz
│   ├── c915d7ef3e11cfe483936288a3e46ad10e3bd426.nq.gz
│   ├── cb46228cdef858fae5a1f9499c033fc30d63f521.nq.gz
│   ├── cdcb03786b3c987eae08b1ee1864a0eb6a7171d8.nq.gz
│   ├── ce10865a51524eeb1a646e67310dbe889b4b0837.nq.gz
│   ├── d2542791e0e13270fbbd2d34ba932186ffa8dfe7.nq.gz
│   ├── d3f9a0fc46b38b758bfbbd1dceacfe46a6e696d6.nq.gz
│   ├── da7836e76e00467d1e3094a479416b1ea4658a07.nq.gz
│   ├── dc8ad1d8561458b1092cdb961c3b67eb911c8d16.nq.gz
│   ├── dcfbc4fb4e83e912bfdb57175cbdf63f7546dbe8.nq.gz
│   ├── dddacd85430398e3f1cc4a2db341a01d89b19448.nq.gz
│   ├── e2db9284926852ff674979ca3aba5634c8a627d3.nq.gz
│   ├── e31b44fbe7c743a9011cd9ad6f62ae997316f033.nq.gz
│   ├── e512582a9f0161aafe73ea03ea8ecdfc2e894a09.nq.gz
│   ├── e5529e7fa2c4deb55cbf7668ac06614ec4c2caf0.nq.gz
│   ├── ec7b7103a62b7fe1c937cf49c59436155904232d.nq.gz
│   ├── f5c8fc1aa299c4987f0552c4241832ab10801a28.nq.gz
│   ├── f7dfa82f668edc05e6a73718b4c2800c26193621.nq.gz
│   ├── feb333bbab665aec64cb5372b7684d90b57eb1ea.nq.gz
│   └── ff5fb3fabb3a9b14fe6f5199c8541a1471ec7a8b.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 46454523802b4486f052421600c9e551bfb4f59c.nq.gz
└── tag
    └── tag.nq.gz

11 directories, 94 files
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

[NousResearch/iroh-blobs](https://github.com/NousResearch/iroh-blobs)

---
*Parsed on 2026-10-09 by [repolex](https://repolex.ai)*
