# Repolex Knowledge Graph of vispy/test-data

RDF knowledge graph data for [vispy/test-data](https://github.com/vispy/test-data), parsed by [repolex](https://repolex.ai).

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
rlex download vispy/test-data
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── c324adbeb3d75f0dfd52d93eaa8ad8c08b39babe
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── c324adbeb3d75f0dfd52d93eaa8ad8c08b39babe
│           └── chunk-001.nq.gz
├── blob
│   ├── 009025ebd975c331ad3dd02aaa3a7e6deb81a397.nq.gz
│   ├── 017c3e805d212d15e013effb99ea663bc415b220.nq.gz
│   ├── 144f5d3ebfa4bca4a58de048931f122b33dfc991.nq.gz
│   ├── 15ee04ce9a2672f4e3ab6d8b56f2a747933bc639.nq.gz
│   ├── 1ab0617f73065384c88b9a74d205d4a6f9c14e3b.nq.gz
│   ├── 1ca108790c8ca47727a214246ca9119bc7ee28a3.nq.gz
│   ├── 1e616b4c02d5380c739a3be4868d4973e13020bf.nq.gz
│   ├── 219cd7f0845934919fffdc5a425755ecff80d7de.nq.gz
│   ├── 227cb5e842fe2cc3fbf0773d29fb542458de92b5.nq.gz
│   ├── 22ed2d915f7972bef004623d7da3108a53d45732.nq.gz
│   ├── 27bb364dde2d74532b3e85bcdd3f7536bb0e5c4e.nq.gz
│   ├── 2aac74ffb24b050e10d640107b7a81a17a13079a.nq.gz
│   ├── 2df21e677d7fb55e5a53e2f6ccc72ce9a5e6e001.nq.gz
│   ├── 2f60a0999946901e69d62ac515a64033e0d30d21.nq.gz
│   ├── 30ba31c419df7898bef1ee68d21cb995ae3222f0.nq.gz
│   ├── 3635d4b6c4828a8df5e41ddeb8e14014430f75eb.nq.gz
│   ├── 3dbd1116d4ff6789fe916ece99ad14ee19a80cd8.nq.gz
│   ├── 3e3bbbe81e2a1ba861a7d545fedb2a4f5b0067af.nq.gz
│   ├── 413a945c9f593afff6814b48cd8a86f9e0347ff8.nq.gz
│   ├── 41fb89cf9f767fc612c81b902021cd82260586c7.nq.gz
│   ├── 425a16f4e1be64a1fa8da53eb049c05a3d7f39ef.nq.gz
│   ├── 45723da43d6e401507a8a4c0532aa3ad3fea4b9c.nq.gz
│   ├── 4d0a9c8812ddd30eb34d60c76382f2b0f50cef73.nq.gz
│   ├── 4e5ac972952fc87256c75408c9b2d6728d3cf14e.nq.gz
│   ├── 507ccdfc192d0579a66e090ceb85e1730486d400.nq.gz
│   ├── 526cd92b4bc86fa1ca0e7c573c76094e56d4ec17.nq.gz
│   ├── 52b5fbb64f494d0f4e419ba8747f6ea9d7f57130.nq.gz
│   ├── 535f3fd5a9fd0d76d61dc667316e4b6b4b120c5a.nq.gz
│   ├── 54e85966dc060198d82f0b664541ccdc9df35ad0.nq.gz
│   ├── 55589b4cf076a750487bfd85e188379eaa23cf0a.nq.gz
│   ├── 55b88c4633266e1cfca3e84f9e84a3e3d14ff8f6.nq.gz
│   ├── 57662fa59a4b6d3fe97e7d95a8110108fd3bc051.nq.gz
│   ├── 57a6e7bdf48c971b776bdbfcfd323c35644f9088.nq.gz
│   ├── 58e9d80fc25103f13d5ef40cbbe4aa9279f57d0d.nq.gz
│   ├── 5ad0da53ab7a3ed81d2608f44907736cce4d9670.nq.gz
│   ├── 5fc03514d88bc8c9ee44ca806e52763e7ba9bcd8.nq.gz
│   ├── 620b3b106f54ce97c3914f1bccab83eb8f209a0c.nq.gz
│   ├── 63d9ccacd518f005364b08d3c3033855fe60c731.nq.gz
│   ├── 6654e426d524d513b2df3d9d84001715ae8f60c8.nq.gz
│   ├── 6b2d7c0ceebb8284b28560ed88b62ea91d67ba5c.nq.gz
│   ├── 6cd06f359c4698d292fa47a82f78de587a20d15e.nq.gz
│   ├── 6d4f54ad418f87c7fd2f1b00b2f7375471a1cb7d.nq.gz
│   ├── 6fc2c69b6b5aec116bacf00995b0a8691440661e.nq.gz
│   ├── 7068821446b3fbeff6ffc1ab6f66fed25ec605da.nq.gz
│   ├── 713a6e6a79cabf475286ca6fe9b7cb31af3e01e3.nq.gz
│   ├── 7562708871b6cd77b33049746a1ccb5fe4435ead.nq.gz
│   ├── 79356164dea9a2d0eefee51dfabc307dd2951622.nq.gz
│   ├── 798ffed56254fea4490218d5c7db5eab09b9df26.nq.gz
│   ├── 823c1289b4859ae36251d533e5f453fe95fd54f2.nq.gz
│   ├── 82d20399aa2f6c57d550aa353e29a9ba1cdb76c9.nq.gz
│   ├── 85783d3ea1cf7ea5849496f7c851434538e99b23.nq.gz
│   ├── 8940c09d1d2e432d59e0373bece333b5d29255c9.nq.gz
│   ├── 89fe53e7cf2c0b6940300b45d9a44553dcdb03a9.nq.gz
│   ├── 8bd2fb49b9049bbaa2386e95225e7c7969ba6888.nq.gz
│   ├── 8da5ace8be677e199997aade653db9e84794f6ae.nq.gz
│   ├── 8fa6ca1a336ea0fbc122790e26de32b5df875175.nq.gz
│   ├── 9001b17034238ef51b8d80568765174cac45a7f1.nq.gz
│   ├── 91e2c32dcec477a6be296ad1a8fef443dbaa13b6.nq.gz
│   ├── 93a2d5fc841d8088f975b7e67b6ff8457eee634f.nq.gz
│   ├── 978005df4a62c48fbc793a5bd6e917f8bde6d6ea.nq.gz
│   ├── 988642746e453d346b4c6bf37543ca458041946a.nq.gz
│   ├── 9fad517f6001b3dc5b512487c56cc92bde400d07.nq.gz
│   ├── a1d3285b0fce0cd04f4d62d1b6c0c46d95fff2f0.nq.gz
│   ├── a4cd0ad8632415b11f76dc92f4340e8b22cb16e7.nq.gz
│   ├── a52db0fff83b43ff981e302c4d9c300962d44519.nq.gz
│   ├── aec3f3aaa62e80bfd193dd746a6ee344720b89a2.nq.gz
│   ├── b236105c9f3e588183fad0ac79b9ac09dcf3df59.nq.gz
│   ├── b51fbe454f253e122228d7f72817c31730a91cab.nq.gz
│   ├── b7d3abb2bb7b034e9a0c4685b6dacbe9663f293b.nq.gz
│   ├── bae898493f145e6f0b192af40f828ec28d9ab27c.nq.gz
│   ├── bc2ada3a538072acb465b63c926df7ed3d208244.nq.gz
│   ├── c2a32e93eab20c61aee56abea2f65ca13cedb224.nq.gz
│   ├── c60c9a6e1439a316a4934a4d24b0575ec5dd5859.nq.gz
│   ├── cd3e3cec57f314748d0a89f303bf288b67427048.nq.gz
│   ├── d1f21d8fbe0ee4c4f7dd7dd35ba77b62677715f3.nq.gz
│   ├── d4350ddfd452560c778a5572388e2f96d8712307.nq.gz
│   ├── d4b6f5804c1de9988e3ebc537ce7845af0ed34ce.nq.gz
│   ├── d521bb6c93b86191b974732d1ef43acdb6f5917f.nq.gz
│   ├── d6a6cc66f51c43142846812bbf23f3586c7a2025.nq.gz
│   ├── d6cfbcabad8c18d6a0ce73e279e329d975069713.nq.gz
│   ├── d90557aeeb1555f8ee1aab07f10c74ece46ab934.nq.gz
│   ├── da60f154ee62c0f931fce28cd0c911e41e794c3c.nq.gz
│   ├── daaa0f206d2d3a27fb9a510e7462c15d7bc7db00.nq.gz
│   ├── db53c742f4e241e5d864b467057f72c94be077a2.nq.gz
│   ├── df85d490ccdf7fa405445faba92a99ccc0790b51.nq.gz
│   ├── e09a234744b604bb6e7c0c7c39d0c68d41d20922.nq.gz
│   ├── e185b71e6b7d467efd0741be13bd2a175a9333b2.nq.gz
│   ├── e2d122e10fb119dabd0991e97ef725d16bcf961d.nq.gz
│   ├── e3697d61065ab078144139632a6fcdc70858862c.nq.gz
│   ├── ea085d19efda09809f266f5d730e11403fd947c0.nq.gz
│   ├── ea49a684f44a326a67c41dbc778078e30e74161a.nq.gz
│   ├── eadcbe97cb2b71958759611ab2dc44f7b255ca0d.nq.gz
│   ├── ebd814db474e43ed1056ddec0e01915090ef35f3.nq.gz
│   ├── ebed2daf8bffab877c0ad363eb9eda5cc2e8a093.nq.gz
│   ├── ec6415e4378bd152ff58560a8f89a5e113f0510f.nq.gz
│   ├── ed28a3ae37d63a9c40d9c4070787b7f660c821a8.nq.gz
│   ├── edc63f7846f50ea6441fa5e6e7f1e6294baab18b.nq.gz
│   ├── ef96693deebfe7082349d42d89481ac44ab1b47b.nq.gz
│   ├── f43e08d051ff046199a80ad42fc2848b00a61c2b.nq.gz
│   ├── f86a7dad07fe7db58216d065fa9ec8cb19fdc262.nq.gz
│   ├── fd06f5b0a35775fb63f01edec87092e1c92329e3.nq.gz
│   └── fd0ba1fc4c8aa47ac5fa20d70c7232bdaf072512.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── c324adbeb3d75f0dfd52d93eaa8ad8c08b39babe.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

12 directories, 109 files
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

[vispy/test-data](https://github.com/vispy/test-data)

---
*Parsed on 2026-10-21 by [repolex](https://repolex.ai)*
