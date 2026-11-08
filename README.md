# Repolex Knowledge Graph of argilla-io/argilla

RDF knowledge graph data for [argilla-io/argilla](https://github.com/argilla-io/argilla), parsed by [repolex](https://repolex.ai).

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
rlex download argilla-io/argilla
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 5338519accb13ae422f8bf9c0642651c249c49af
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 5338519accb13ae422f8bf9c0642651c249c49af
│           └── chunk-001.nq.gz
└── blob
    ├── 0021c688ffd8a1cec934703cc3475fe2439bad46.nq.gz
    ├── 003e97905e14a6830cd2d37ccc042084528691db.nq.gz
    ├── 0084cd1108a784eaaa542311e51d89b799134f5c.nq.gz
    ├── 00d87e2be5733fce3abe84699391fba9886a09cd.nq.gz
    ├── 0139b82b8a8f05a028d6866becd048c164bae2e9.nq.gz
    ├── 02b88ab367b478436146cd75886d5b868443aa27.nq.gz
    ├── 02bf8e7f15abaae5abed1d4f093113fba6471a0a.nq.gz
    ├── 02f629e5d4705880ae375a2f4a8d0b85c534ce78.nq.gz
    ├── 0370b6a308eff4fb023922a3d9089bc462b48916.nq.gz
    ├── 039116e820e97a2793a11781e0d88348013aea04.nq.gz
    ├── 04672ec50a05fd24dee43eb4d11e718dc9a896b1.nq.gz
    ├── 04af1f82795d79407c3e31f466bbcc50679bfc1b.nq.gz
    ├── 0509db0de409925e0a85e2db39eade635c1318db.nq.gz
    ├── 057af871cf81e62aff75aee9fa202d9076c24909.nq.gz
    ├── 05d3eca8c87509dde943120555434afc11cab8c5.nq.gz
    ├── 05f975766b3221a44ecf8184935f7dcaafa8eec2.nq.gz
    ├── 06437b9e687f30e9fa13380a1ff39ee22d8ca7ec.nq.gz
    ├── 068faa08c7d1f1fbf887d0a8848ada75b52d8c50.nq.gz
    ├── 06dd1b33167f64aef14435e40336e9e140fc0363.nq.gz
    ├── 06e227b050e632efd0bf58f3edba4c7f2052b3e3.nq.gz
    ├── 08866d76d4abc6439cd255a93ab08f5b914adca1.nq.gz
    ├── 08d30202405d0fc51d55d58a2be9f3010fa8f782.nq.gz
    ├── 097424feb1b6985e2e6f111e2a8453d5be26d761.nq.gz
    ├── 0977c7488e54774e5f46dc6edf71865d03216c54.nq.gz
    ├── 09b80851a94cffa04ceae91cf3c1cb8ebfe59ed7.nq.gz
    ├── 09b9a4e0d634d0524d370a6421fc0dc2dc373f4e.nq.gz
    ├── 0a1d5569b765ee83b56361adf88a8808edcd9b15.nq.gz
    ├── 0a679e196b74b647e1b3eeb9b48ceb053a4fcad5.nq.gz
    ├── 0b3a0eab359ba13edbf41c5420421ec88d47e3d1.nq.gz
    ├── 0b89409e6925cb529223b499f28ede6298e452c1.nq.gz
    ├── 0bdb1ad0cd6dfabaaa43a071dbd001e10180bdc8.nq.gz
    ├── 0bef2d1b12a84bf455bfa1f020c449dc40835a0d.nq.gz
    ├── 0d7333e8784738bec67ebcfee77769cad62cfc9f.nq.gz
    ├── 0dba5e1dd3f4f4343251c6dcfbaa8cadc57e6b6e.nq.gz
    ├── 0dc7f4099d4f26b5f07f9c8ec1e74219cd214b6e.nq.gz
    ├── 0f6160092a0ae3be80f9dba2a8172591e9be9933.nq.gz
    ├── 104a65f6fe9898abadc5d248bf2ddd46aa1f82dd.nq.gz
    ├── 106b89db70fc9f0fe605795d0ae7862bf44047d1.nq.gz
    ├── 10f45b47ffd9fc1773d4dc07f9f53e98c78f7354.nq.gz
    ├── 11586633f9e053c6855a26dfaddd64c4e3eb4cc2.nq.gz
    ├── 12d660f63e39c7f92b3e8ef1855b195135bc5a5d.nq.gz
    ├── 12ede392783a62db7fd0bd1fef41823863f33f00.nq.gz
    ├── 130fc671da6b19cd2570f8f075ebde1dac732c4d.nq.gz
    ├── 13627433737113ed719fec230ad870968a41fa31.nq.gz
    ├── 13a05e29c32cfb8b7abe47b0e004a3d7335e3751.nq.gz
    ├── 15f0f0e484dabb8d37a441d5733822858caa6370.nq.gz
    ├── 1616c18e3009fba06c35c1c43e6164c872af273a.nq.gz
    ├── 161d3fd2169a82b37916661d5541d74db9dc4153.nq.gz
    ├── 168dce9eb1a664530789ca5075c34f082f3ed8f3.nq.gz
    ├── 170bb76fbd3fc83b1c324018fee8b41cca18ee18.nq.gz
    ├── 17399a10c4ce1d305a744446f73194daa374c0b3.nq.gz
    ├── 1762f66bc4c3f02f4b5464da0246fd8d78ad72ae.nq.gz
    ├── 17d85903fc5d13d026175e63310fd9beb86b864c.nq.gz
    ├── 180d9a0e28036da5f6ee68dff78c95bd115d6f86.nq.gz
    ├── 191e59ca44800e5c7068101d38f0ea764cbb2a35.nq.gz
    ├── 1920437989f3fa4ed1ffb8998e7fe2ebc4e61b5b.nq.gz
    ├── 19d5e6c84dab7cf05824bb9ef5575c931dd5ebba.nq.gz
    ├── 1a319833eacc7c217825ed7b64a40cb8ff5ff670.nq.gz
    ├── 1a481887e6fddedd06e629985d4e30a0f00d69fd.nq.gz
    ├── 1b545dbfe59e4ff57931b5678f07edf32da78b4b.nq.gz
    ├── 1b8ff9d1b86cafff0df05365f2b08f93024b113f.nq.gz
    ├── 1b9e381e4422eeb6ee258f37c1ebe6595e4ac75d.nq.gz
    ├── 1d41f341fc03ddb75ec50c1b88971d5764c11384.nq.gz
    ├── 1d48eb87cbfcc74fdc1ed7075a727c89298e2fe1.nq.gz
    ├── 1d7a5b4b4d0d0b6aefcdca60b4a28020b08bbfde.nq.gz
    ├── 1db734ad0a1094a7fe21cf7ed587e6e10ec6e682.nq.gz
    ├── 1ea0037d0ea83167eda29cabdb975d5bf592aeba.nq.gz
    ├── 1f8e57714395eb98dfcce420e0fd89468a406e77.nq.gz
    ├── 20542d78f0ceac708b0d2997ec362f96acfc11cf.nq.gz
    ├── 20f230cdd5d0ab8a7f22e46373bb6a624bb2e66a.nq.gz
    ├── 2109513cba184c56b112647fcda3491efe5dd0bc.nq.gz
    ├── 21153a4e6542a8b522c2872b9bc71f726efe5b8b.nq.gz
    ├── 21959c209a9b58b9fe10ad8f2fec8e33ac794f1f.nq.gz
    ├── 22912a02bc492b9d6cf44ee1860d96d2b4120b66.nq.gz
    ├── 22b32afe8a4c6c3f6e63ddcabcee091bfd36dfea.nq.gz
    ├── 23aa796c00ae95413921e1e80472442e14660c80.nq.gz
    ├── 24dfc197550488543a45bf27ff9cd75cd43a819d.nq.gz
    ├── 2536105a28edfe0e0bc4a8c78489cb35068bf861.nq.gz
    ├── 255b52608751a5f74228fad71b87df3e9f5965a3.nq.gz
    ├── 26014b11d6f177b0d2b178dce028a88b79255e30.nq.gz
    ├── 262ffeb9c581e5c47f04a7c0b239e761773a6e50.nq.gz
    ├── 266a88c7949a117cf88230a6b203ac2fda7cd288.nq.gz
    ├── 274dc64b8b69acb20554bf314aa3dc267c57ed11.nq.gz
    ├── 276e14f102433736645288674eed126d53fb960d.nq.gz
    ├── 27adae75dc5a9de60450b9053704417962bc0e0d.nq.gz
    ├── 27edfe83f6f2dc75981775c05e5ec81446dbd18c.nq.gz
    ├── 28ec352092017416e27361eefd5961b7171a2867.nq.gz
    ├── 2925cad2340c85d1cc23bc9a5103617519d5cd48.nq.gz
    ├── 29a8cd4915814ac179797294f9c19b58c0feb738.nq.gz
    ├── 2a4275504cb54e68b610c7984d81552fe62ae570.nq.gz
    ├── 2ad43d20bf793d25349f0c30e4fa15ba60cfef4e.nq.gz
    ├── 2b8d1442728c6e8c44d86b3203878ebe405cdde7.nq.gz
    ├── 2bdad308175fcc0fa3d5f1a3bf8e91194dfa2954.nq.gz
    ├── 2c686f5935c6a058744fbc489014ef5dcbd1d2d2.nq.gz
    ├── 2cf15099e18cae740f49793e84b90d0635074cf3.nq.gz
    ├── 2d86a3004eedbe2d94ce6d5093faf4f1b7bcee07.nq.gz
    ├── 2dc8972899bad1f438ade0378b30fb7271435d68.nq.gz
    ├── 2dddc4bd41ea95b2171548e662cceed1d9e2026f.nq.gz
    ├── 2ec0e9b16e75615c411f86308e0be98dacc82c80.nq.gz
    ├── 2ff58a5c864eecab1de97c42b5c2686dae60e27e.nq.gz
    ├── 301b284d356513c8a7a9f284b20c6aa7973d30ae.nq.gz
    ├── 306efc0b6941b70abd9bbe125aa7cfaf83605606.nq.gz
    ├── 30b14423a2674ee83ddf3a8f7e1b69a28218557b.nq.gz
    ├── 314eb552e5a19790c1cc45cf63712a2f7254c286.nq.gz
    ├── 31c3be6ca2ee53216c28a21801d5a350bf030a4f.nq.gz
    ├── 3253c9104e869a3a91104a923df976c5a2ae1de6.nq.gz
    ├── 3352892e3fd8009dd8e54792c46ae5c5e6e15b50.nq.gz
    ├── 33651aae2201a9c2e3b74163ac1c6e95ef267e26.nq.gz
    ├── 33df22025b0791be65940f65fad3865083c90326.nq.gz
    ├── 341590b1185db908ad9e8a6fb30a4b336be75290.nq.gz
    ├── 35acda2fa1196aad98c2adf4378a7611dd713aa3.nq.gz
    ├── 36dc52aa8c2020b79f281ba65e8e79a9c47220b0.nq.gz
    ├── 38745d09b0aece9b2a00d6aeb459659a87efae83.nq.gz
    ├── 38c9991c9165d098bd2a616277832e462ab5ab77.nq.gz
    ├── 38fd57fa100be683b5b35092da5981eb4b561410.nq.gz
    ├── 3a14318939ebb425cc9f21c4f79242077a7313d3.nq.gz
    ├── 3a33cdc9ab63dffcf63f29248fe9d7d1d4df487a.nq.gz
    ├── 3ac82829b8a1816341c794fbb107be1aaa1b7570.nq.gz
    ├── 3b108e94c33f1cfccf4c58dfe7778a0f18b0c799.nq.gz
    ├── 3cdbeda14ead93b94653a54dbdf93dd80f0a58c6.nq.gz
    ├── 3ce5e1356ad007a46c96382b9057a6b24a896f09.nq.gz
    ├── 3dc3546d2962ab8c3b5d0c2869bc0ef411965d18.nq.gz
    ├── 3f3fa7d5155b77f938e32da8d1a4c48550430794.nq.gz
    ├── 3f8760b4385fad1d87a7e35954258d4d3509a6db.nq.gz
    ├── 400014a4b06eee3d0c0d54402a47ab2601b2862b.nq.gz
    ├── 401ec0f36e4f73b8efa40bd6f604fe80d286db70.nq.gz
    ├── 40d8f97fc23ce7e7ac70e84cfa815ac5d57b7c6c.nq.gz
    ├── 432835e1731ac13c89a0d6a45c229415d7bf19f1.nq.gz
    ├── 434b31c5a8c5c92cc9654c7a8cd2821917f2c0c3.nq.gz
    ├── 43f03a94188f9d6436ae37505cd87f5d92deeb9d.nq.gz
    ├── 445141984c1a958e2be4e8ed6c82a040a15f09ec.nq.gz
    ├── 44587722482bf833727d7ae79916fba2b35257d5.nq.gz
    ├── 446a17164ffb69dd1057d9f9a7c54cdfefea7de5.nq.gz
    ├── 45e807154162393c0e7fad31527fdad2fd3c734b.nq.gz
    ├── 4663147fa245ca54fc35c1359cbe03046aab2ead.nq.gz
    ├── 4710ee0eb7484305224570e47dfca0e5781da6f4.nq.gz
    ├── 4775471da1047bc67b968467ee37b6e464927267.nq.gz
    ├── 491dd72e8dbc4a3d0dcd120cf934cb484935e6a3.nq.gz
    ├── 495e98784eed793b689e2ae4d97661603209bcf0.nq.gz
    ├── 497341ccb88e543bd44733e5d5ccee25baeec95e.nq.gz
    ├── 4a91845321a5d0ee93bf7f6da9b81d8938bb95e0.nq.gz
    ├── 4ae0842870f810d0809854d738fba7b2da6b0fb1.nq.gz
    ├── 4af6ce86aba2be2cff1722ad411e310584b84709.nq.gz
    ├── 4b5083871b921e1c0012992f9ecdeabaffc65cf9.nq.gz
    ├── 4b6cecae7f1ca59ffd7b8027a0e286ae24474c07.nq.gz
    ├── 4c9313f1c2243aaeb667592afa005cf718428e0b.nq.gz
    ├── 4cd246993ac016cce20744225f50976205d96e55.nq.gz
    ├── 4d8066e8ad58ca13abb625e3adda800473920aa2.nq.gz
    ├── 4e39419e1c59a9bcecc5b7234a9d7d2ab13db8fe.nq.gz
    ├── 4f358362f93468b774c928d10c8314c81f0c1d6e.nq.gz
    ├── 4f7c4101367fe9f18a79cc6b338129a4536ae2a4.nq.gz
    ├── 4f7fe48f66bc60f390a4eb23722b97a747f07e60.nq.gz
    ├── 4fa17ecd67493b2a1b972fe8276585ec44e60ee0.nq.gz
    ├── 5056ab45a4efea1d5c6f3400383aae0726812404.nq.gz
    ├── 5072afd5ec5a4732adaa701f719f04ac616cda60.nq.gz
    ├── 508f94ce48f88cae7b72ddb2ebe5d552c4356adc.nq.gz
    ├── 5255b6c1b2e5473ecdd8167d2e097e1b273987cb.nq.gz
    ├── 52a5e5219169c712426422f77b93d23c61d1cd52.nq.gz
    ├── 530ad81a301f07f94458f813e9344a51a2765e0a.nq.gz
    ├── 53c758a6b22340b09cb4a43ae9550fcbb45b65b1.nq.gz
    ├── 547e6faef4baa09c1d5f55ab889086b766472b02.nq.gz
    ├── 54b7156b4969ab5335a5f46c73e593cf762c73cf.nq.gz
    ├── 55b99bd3d02ea474e888d901f04cea4b7d21edd0.nq.gz
    ├── 55be41799b73a23a42e6a157a1429a681e81d8f0.nq.gz
    ├── 563ec3ac663d775a2af660f6977c9c3e852d5a5d.nq.gz
    ├── 56b3fef687facb7cd141d9afec586701d95e1d48.nq.gz
    ├── 56b866376e6cce22282b17b95dfb8aa69742f88e.nq.gz
    ├── 56c1e266f4afdf45256a47ccef51919ba7541a1f.nq.gz
    ├── 56d69af76ed774f26c3536296d371e7b4b4e04f3.nq.gz
    ├── 571605ad121edbe9f25e06261acba2521bc97f15.nq.gz
    ├── 57335460ad1871963dc0c39135a1715a6e23b875.nq.gz
    ├── 5776290b952c7b739f0029f0114934f1588722f7.nq.gz
    ├── 57ecb0cde84733b233088d020f334bf56cfbe4a4.nq.gz
    ├── 5862d94fc9d7ac2574c2fbd2a308c9383ef8cbec.nq.gz
    ├── 58b3215dae6cc2013f605cd87bc85cc5e09f38e1.nq.gz
    ├── 5938bbfff0d3953931d9a8c2868f97feaa9ee469.nq.gz
    ├── 5a3af1e316e841c4dfeac9b2ae1a9e045b1149a0.nq.gz
    ├── 5a9f7aa0cab3abf08cbaba1154af5fc7c13403aa.nq.gz
    ├── 5ae7b4ed60fa5d6c8526798b11bade0a52168fc8.nq.gz
    ├── 5ced12fb7bceaeab023c73542e5b30fd5bf901f4.nq.gz
    ├── 5d707233585e02ca42aa3dcaa0d9b702d2f45aca.nq.gz
    ├── 5db87f6ad80a33f2b45e2883e9578a185671e28e.nq.gz
    ├── 5e0796db4b57edd369c1277cfcacd061376e9b5a.nq.gz
    ├── 5e29c1703a66b0aaa33460b9386f668a384e1deb.nq.gz
    ├── 5eb34d0c54e5953aa7b255fdd85665e1bc08e250.nq.gz
    ├── 5fb045da4acc98682c64d9d53eeef8012b460ad3.nq.gz
    ├── 61c8302b4cd728db18c2261b797401e0e3ff4a27.nq.gz
    ├── 6281388bf5d2bf49fb2cc53eaf558c70f38e2bbd.nq.gz
    ├── 62a2a9f79f412ac070790104744b081a20b017c4.nq.gz
    ├── 630fff8b3cdf665aa2333873a1ec776a5b70b917.nq.gz
    ├── 632b09fa840ea8d9a0126b2fc62afcd8f3d91b4c.nq.gz
    ├── 63c7d6bd931bf5934276806f0bbc4e2d0f2d087e.nq.gz
    ├── 63e00a552b67fac008c202f74cc35d1d4211cbf0.nq.gz
    ├── 64b310b948e24d3f1dcd77a489a76227a58f61ee.nq.gz
    ├── 64f5f3cc31956d8b2f8581f4d723bbc536e3aa60.nq.gz
    ├── 6835bc618662a057434a55cb00ec6d814de523d5.nq.gz
    ├── 683cbc5b696dd70992297dd81ae7bb82fdd0b362.nq.gz
    └── 684906d5d13fe4be25961a688637dfc698e0d418.nq.gz

7 directories, 200 files
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

[argilla-io/argilla](https://github.com/argilla-io/argilla)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
