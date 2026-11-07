# Repolex Knowledge Graph of huggingface/hf-serve

RDF knowledge graph data for [huggingface/hf-serve](https://github.com/huggingface/hf-serve), parsed by [repolex](https://repolex.ai).

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
rlex download huggingface/hf-serve
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── b3ec975552e2db3e087d7bb5696ae6d1afd21c35
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── b3ec975552e2db3e087d7bb5696ae6d1afd21c35
│           └── chunk-001.nq.gz
├── blob
│   ├── 0438fc3706f666013b8638dd1dbe6c79c7107bb3.nq.gz
│   ├── 045746bc14bf243d8a05b49799e74054715a9060.nq.gz
│   ├── 05121b85bcc7ba99ddbace4d630b88338558e712.nq.gz
│   ├── 0b5c0c217ef8de44ae2f17ae41f354388adec2e1.nq.gz
│   ├── 0b73ca506518a133b434054768964e97769230c6.nq.gz
│   ├── 0bd3e39bf97a5b66a2e48454b1c887d9a66d53b4.nq.gz
│   ├── 1168d496ed751568fa62c69d4f8805959e6f078e.nq.gz
│   ├── 13ff3b30e07b8751f67c72e70785dba47a239546.nq.gz
│   ├── 153d12e440c6c30b3be5b53ead753e733bfc89d7.nq.gz
│   ├── 15f7bdd7916ac5fca2274ad5d1239bafe0f0f5a2.nq.gz
│   ├── 1633f18991fd431f6ca6f79e6c9df9cc69ca8676.nq.gz
│   ├── 186be0c2555425a6659eba46d852973dcdda8131.nq.gz
│   ├── 18815e13c86112c9d4c5528a1e2b4144b9d5caa9.nq.gz
│   ├── 1d403786eedc4eefc6af353f04474c74e53c8ad9.nq.gz
│   ├── 249dd595b5b965d234d2dfae496ea099f012dec9.nq.gz
│   ├── 28baaea9e2e4a54be28c4fb21a76cccf0e38ef0a.nq.gz
│   ├── 2ac9ea5988f96e82e40dc3de9dad2877ae562965.nq.gz
│   ├── 2dae3a83326a2536295001859707604593297e6b.nq.gz
│   ├── 329b12925a7f8a4a5d7c9881f090d21025b8526d.nq.gz
│   ├── 3391cb48beebe3b563720fe71bb5f770e0d55264.nq.gz
│   ├── 36672494489a46bf9b1fd9f89d8452a671a712c7.nq.gz
│   ├── 3a0450791da9881b8f86ad9b99f1f327983682a4.nq.gz
│   ├── 3b267521754c2daad724529c1cc2c29c5c6a84bb.nq.gz
│   ├── 3bf8704436eaa167d60085aab051cf397ea70b30.nq.gz
│   ├── 4022f6884b0b39ac297ad7964583effb2c1df53e.nq.gz
│   ├── 407cd58f2a193e7ff6f52693896dfce4124df2bb.nq.gz
│   ├── 43df3f2457a79d638e1f5feacc55debb58e2a0f1.nq.gz
│   ├── 44e7325f6ac7d416339f711eefd5a8265158d986.nq.gz
│   ├── 4778cf41e1904b8c80e8c6374edcda9fc7484925.nq.gz
│   ├── 47a9e2ac48c52699331c80622af87c684baa027f.nq.gz
│   ├── 4a14ae5ed82b88deabbee39d5976b88ab83e067d.nq.gz
│   ├── 4c70a99bd580004185752fcc293482037cddbf75.nq.gz
│   ├── 4e9dbcb09d0556476b8363619d9276c3f696aa3e.nq.gz
│   ├── 4f760c7b9eebf3ff53698ad97883916859149b5d.nq.gz
│   ├── 53c8a948beaf3aac2bb77861db1cb87474beee3e.nq.gz
│   ├── 5482ffbee0f313f15bdd89b1a34c7330fea77739.nq.gz
│   ├── 55051bc1c81b7f68efb3df1af17d1779278f51f5.nq.gz
│   ├── 587b791c7430084ce770467ef628a5caa2875fa5.nq.gz
│   ├── 5a95d213a1b832acc14e5e6c0694b5a1dcfd6646.nq.gz
│   ├── 5c0506c8ef42e3a0d68c3eb5ca1cd8e3735a0509.nq.gz
│   ├── 5e0bf28a7c3e611c6bda807a7f65c8b003983dfe.nq.gz
│   ├── 5ef7b7399a28b7b3392957863fa280fed3dde80a.nq.gz
│   ├── 604c8ae688e223846e9ab9351dcaf89cd65ee3a7.nq.gz
│   ├── 60663590af49077380136bd1c74e380634f63bac.nq.gz
│   ├── 70ab8648363884375a9be0484c81b76624c0a3da.nq.gz
│   ├── 710c3cc22d46b5d105f181d840e0ad06597a6dfb.nq.gz
│   ├── 74c80ac26fefd358324ed11170a8bb869e4c4a05.nq.gz
│   ├── 75b0483881d039b9af0cf124f52ddf06393e8886.nq.gz
│   ├── 8202444458d3dff6e4f74e159a56329340df1696.nq.gz
│   ├── 85aaa10f6e82f74c9a3d2a7ae8fd92e0f7fa5971.nq.gz
│   ├── 89f44a280f4cb482291522eb7d06ec014c8bf526.nq.gz
│   ├── 8a4ce01f050bbd84ebe1f0ca986dd9d35c4cb236.nq.gz
│   ├── 8a6051ede2c4c335bc67e731611c504559556dcc.nq.gz
│   ├── 8f63f7a13a56c7da575221c8397dfe30e6ad6f6c.nq.gz
│   ├── 903f58c126e02917509797dbd054a42a7341ab01.nq.gz
│   ├── 9114528436479b9570f16c2401ca3d795c31221e.nq.gz
│   ├── 9460513e00cba7a4d333e6deb04e7dd8ae9060f5.nq.gz
│   ├── 96706bc32cc2b83c90cb3a206c0dc84a32cb34ff.nq.gz
│   ├── 9bb0a233b0e2ee90fdb06c6dd372ac39f438b5b1.nq.gz
│   ├── 9c079e24f624acc4e43a0c905ee43c7e614c37d2.nq.gz
│   ├── 9ec58808d57ec04beb433bb683257587a9379467.nq.gz
│   ├── a08b7362db04abb9b55b0e5814917f1156955073.nq.gz
│   ├── a411e329741e2cb78394ff967e011e7d787e55ee.nq.gz
│   ├── a51bf94a1d1a68c56b664a16a49888e452ac96cf.nq.gz
│   ├── a6360d382cfdb37556e2a1843e25bb54ae9f33c8.nq.gz
│   ├── a922d020e3e7328db7acc3c998cb397d0dcc8b80.nq.gz
│   ├── acd5edc07f55c61029dec4b4fc42712154ba0cde.nq.gz
│   ├── b063745c9750c1cfa08f3072f5002b97611017d8.nq.gz
│   ├── b0713df665ada17e5fd3187362f4d533653f7dc9.nq.gz
│   ├── b4e4f6c7688558cd796a129f6e33bf37c03b6f31.nq.gz
│   ├── b56912ba6d06050d8bdfc6ad94fe32098973be4e.nq.gz
│   ├── b5746a19e0c25a57a595c136e59d9718db4a84f1.nq.gz
│   ├── ba8462c3ca04f272cf6c258ca5e21aa2f3fdcef7.nq.gz
│   ├── bec38c01ff4e6246118e793027264c71940ee9d7.nq.gz
│   ├── c1d8631250b299032778025493cf90510b0c9087.nq.gz
│   ├── c4723d09d3c9ceaf05f8a0a129f76283f6095d3b.nq.gz
│   ├── c583bfd64c0f462148a0f030268cdea049dee15d.nq.gz
│   ├── c6289c7c48513b3572b94599ebd7503f58b16acc.nq.gz
│   ├── c6ab41767d68f23f5b1b4054ac0ba3b174814ad2.nq.gz
│   ├── c806f25e5bd61f07228716bf47048aaf20442877.nq.gz
│   ├── cbbcb3ddd33f7f5c0ad58c0d283874040846b1a5.nq.gz
│   ├── cbd1b1d7da7e03eafba3927ab7435881c281d938.nq.gz
│   ├── ce0f511e0dd2545a1417301fb61c82c3b4066390.nq.gz
│   ├── ce50594321824ecad1cbb6bbb4f8027d985cb575.nq.gz
│   ├── d43b1ce655c30dc08f82c4f51ae40a96da596d2f.nq.gz
│   ├── d4de9b7fdc1443f32447fd65ad1a77d41cadf88b.nq.gz
│   ├── d580bf874abfaa8201c5893fa7d1315f4661d6c3.nq.gz
│   ├── d59c009b2dc50f6eeb75a6849150954a4a51407c.nq.gz
│   ├── d75778f517b9c8efab5fb9eed154b0d337f3818f.nq.gz
│   ├── d7e08abbb48f9f3583de16c87adbd756ca4d160b.nq.gz
│   ├── d89712e738cea40467c8c3c9918e5afb9a0c48f6.nq.gz
│   ├── dc27342b186f17a71973336437d7a4b8a5f2d0d4.nq.gz
│   ├── dc6cb34eae6d804ba029e3ed1fe9c6c6356daa6a.nq.gz
│   ├── dc97ca7529bdfd9cd95b13f60d6d18c13cffe258.nq.gz
│   ├── de34c4cc0f20fecad7bef2979260a3a3a8625c4c.nq.gz
│   ├── e43934b19ee66afcf50d975ecd5895e78ddab719.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── eabc1fe6a3bf689889019afcf814686751916857.nq.gz
│   ├── ebba604b2eea85834a07be40428a7d5f9b7675fe.nq.gz
│   ├── ecc00446e77330c523b7cc6fda16fcd6660fd808.nq.gz
│   ├── f4329f8f53bab450ac714f68565e60462fd47820.nq.gz
│   ├── f5e605bd5ea140d6b679dd83126d2474b361c7c3.nq.gz
│   ├── f79f254f8b6572475e0fc12878e4ee44faf39e94.nq.gz
│   ├── f92c808a0446b2991d60dd9d7368c534b4783a1d.nq.gz
│   ├── fce6ddd32dbd40bf74965c0fc8813a5da07302ee.nq.gz
│   ├── fd12b052b899c74055a9128a7bbeec8085638635.nq.gz
│   └── fda6da269f6ffd46fd4de349eb1afa3db792e63e.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── b3ec975552e2db3e087d7bb5696ae6d1afd21c35.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 115 files
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

[huggingface/hf-serve](https://github.com/huggingface/hf-serve)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
