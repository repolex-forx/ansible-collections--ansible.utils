# Repolex Knowledge Graph of ansible-collections/ansible.utils

RDF knowledge graph data for [ansible-collections/ansible.utils](https://github.com/ansible-collections/ansible.utils), parsed by [repolex](https://repolex.ai).

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
rlex download ansible-collections/ansible.utils
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 1f3e1bdfe2ba8904d397222dd6f90911d6f2402b
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 1f3e1bdfe2ba8904d397222dd6f90911d6f2402b
│           └── chunk-001.nq.gz
└── blob
    ├── 02adbf8006fc07a40a7f77fd0df98300680a3ed4.nq.gz
    ├── 02e7202ade9a37c88c7f68a27e5a0508ab34d3ac.nq.gz
    ├── 02fbc2edccdb811cdeff57135b546bb02f35531b.nq.gz
    ├── 033451b03e407f6d741d880da07f9095835a7589.nq.gz
    ├── 04d29c17145ad5cb8a2b6f12aa2b14ff58f928cf.nq.gz
    ├── 06a59b02d622fcee87d549b126242f2b7e35cc90.nq.gz
    ├── 06fb92b559a963262a054f36d3fa6bc43038e6c1.nq.gz
    ├── 07c41da7828d654abda8018408557808d354527a.nq.gz
    ├── 07c6fe92bfebe763d812f1df52a9e7a963c98c30.nq.gz
    ├── 0849320bfe012865d340d222541ad4b3111b031d.nq.gz
    ├── 08836ac4fec4461db69c5ab6402fd7f53fbeb303.nq.gz
    ├── 09885e6715ddf5e102f5de379baef89701156c2e.nq.gz
    ├── 0a429cb368f797edd9812042ed0952dbed152160.nq.gz
    ├── 0aaa47b5640dbafa14fff8eff4514ae7730b48a6.nq.gz
    ├── 0c6e8261e27ab4d5db4464c1c2d06aff8c466a88.nq.gz
    ├── 0cef1356723672613da23eaf44c9b4c80a7898c4.nq.gz
    ├── 0cfe70c8ae54adcc92380954e87d7abe6c39693a.nq.gz
    ├── 0d497c9f23b6b2a256cce369f215fde3961ddce0.nq.gz
    ├── 0d6d96d1746e232ed662686454c4a85a577cce75.nq.gz
    ├── 0ec17466ddeaf685a7a6706c4d6960f9d7dd3219.nq.gz
    ├── 0ee8fe9e6a9cadac698638f76c75234ddd210ead.nq.gz
    ├── 0f5a21221f65952d11487c7a60b03cfea26e9e31.nq.gz
    ├── 0f9c88464bd2dcd78554fbbdd1302aeef2ca6703.nq.gz
    ├── 0fb4345f129dcf5b18291fb613918351ff56ecfe.nq.gz
    ├── 1039a070bc29338f667a2f3ce8862a0948d0fcb0.nq.gz
    ├── 10bc2461a8c0d85b226c00663af6874e7cc760bf.nq.gz
    ├── 114f75051689db0ba5e6cd09506ffbb132c5b6cf.nq.gz
    ├── 117e15d098f3e15141d43fd544c3b533205c4144.nq.gz
    ├── 11d156efb226ed3d871c70f72fd9611c6d5c9489.nq.gz
    ├── 1275969bb54517faeb86fbd0c11de7f00e2c5e7a.nq.gz
    ├── 1342a7db81c768ba4bc8dabf2d06fb0d90922323.nq.gz
    ├── 1582ec3bb662dd242ee902baaba7e8123b4c107c.nq.gz
    ├── 164231678aa692f2e69774efb0ce1df007a4d472.nq.gz
    ├── 164aa2ccea3b6ef8682be7888a3e73f8e3defb64.nq.gz
    ├── 16abe7db98272fc515257c9bacb891553bdda40b.nq.gz
    ├── 1702b561dd1c68514150b910c117024a103445f4.nq.gz
    ├── 18028fb84276a324897bc3c129f3a21761010abb.nq.gz
    ├── 18c2b0aa3e233af91815e7f9a833693794103caf.nq.gz
    ├── 19aa57d3f0741cf460577726af7b64d58a350239.nq.gz
    ├── 19f0324db6a6aed460bfdea0395ff982f7aa2883.nq.gz
    ├── 1a1e80225d4b421a569a03b3f39e637b8c90fa7c.nq.gz
    ├── 1ba2a700a4a7037764f0588fd6514e1b2afc13fa.nq.gz
    ├── 1cd28d6851a90fb2739aed0b07b3bfcd4ff77f00.nq.gz
    ├── 1d82816a4a9801d3128dd92aaa14137a73697544.nq.gz
    ├── 1d9d0061adee97ec6286f3ae74b6723aa9dafe8a.nq.gz
    ├── 1f1974e84ebb168248de892ab85d81297afa1511.nq.gz
    ├── 20e7d8842f7cab32b9110155ffab8b3f651c6dd9.nq.gz
    ├── 2241c4fe5498bbaf97587375f06374597b91e3b3.nq.gz
    ├── 227ea4ed511954cf19b92f4524df1c8a457d07ad.nq.gz
    ├── 22c911c5e0e86c5e2c9bca641194c4aea3628ca0.nq.gz
    ├── 2533bb77a6ae74303c3b6d016c0da1d1281e921a.nq.gz
    ├── 2559e98ce4feb60c486cb05356b7eadd73daa702.nq.gz
    ├── 264a61641f86deb92d86c99ac818211dc5d6f5bf.nq.gz
    ├── 271e667e1a3f711bf7c9b2f610477f8f4a77347c.nq.gz
    ├── 27b1b7fb589b15f35d1dbd7230fba93ffd4f1967.nq.gz
    ├── 29dd386283b24d62330097746294f8b99cd9ddd9.nq.gz
    ├── 2c4128868073e21f5fde27927af617455009f29a.nq.gz
    ├── 2cfd7d655770d11c88b51adf235f19289a7006c0.nq.gz
    ├── 2de60bf1b11002af3abbcb696b63c46f5f982bbd.nq.gz
    ├── 2df84f6b1b6e9ef86b3dd99e9486627e193c323c.nq.gz
    ├── 2dfb1674d3f02e48eec3d1f6e781460b47eb99a5.nq.gz
    ├── 2e9e4c9eb7ae2fedc38b6b22255b24de0debe552.nq.gz
    ├── 2f5716a09a5d5c8833f96e3f437425b6dbee911e.nq.gz
    ├── 302bf583ad10a7c5231e26bdd0cb2fd407309378.nq.gz
    ├── 30f5eb6a45aaab2cba2815b81dc7c487875448e7.nq.gz
    ├── 3104719657e581bb5b91ecae8dd2da46aa163b3c.nq.gz
    ├── 318210f3eb90d14a304d5d6273683378b93c75f4.nq.gz
    ├── 321fc1a8502f4cbd9b1c2879e9be995c5c3ca149.nq.gz
    ├── 3248b49e52c44deb26d5301cc88fa23f99bbe683.nq.gz
    ├── 333bee8c378ebf86ba1044cadc138d0f51d1af91.nq.gz
    ├── 3370c3912771f36e7060644e67a76ac7d79491fa.nq.gz
    ├── 339fccf9be3f320299e8436c1294cd7b8043ee9d.nq.gz
    ├── 33eae0099f69141947c53aef24f57b4fecd74802.nq.gz
    ├── 345adba6f8c8e0cc54c10847f0b1129ff3f62fc8.nq.gz
    ├── 34d88e9da49dc8be9e5dde1782d257b06be1d5cc.nq.gz
    ├── 363cede31de2165eb7fe4772323b605f8463596b.nq.gz
    ├── 36746fbb682c47bc3d72089969051cf509cbd0a8.nq.gz
    ├── 37936ae5a7b6e45385d623d0da528dd9c6729f6d.nq.gz
    ├── 37c2dcd50b5eba6188a236c064f3695f5c621804.nq.gz
    ├── 37e5861ae53afa8c48c993ea8c4b3a931d4b0d90.nq.gz
    ├── 39835feec7d6875d67c929af8e5a3348f7a37827.nq.gz
    ├── 3adaf90cf207b547be00163de2d9479bad14bf00.nq.gz
    ├── 3c53b61da54349ed7baf4e07e70e0c84a4f514ff.nq.gz
    ├── 3c756a2303f90bcf35d1cf5bbdfedc7beb5c6220.nq.gz
    ├── 3d3c3838a3e65c4f7ce6a8efdfe7a46d29b5b2b6.nq.gz
    ├── 3d5c86ed90f026837af9b2322d9a74f162b05ed0.nq.gz
    ├── 3de1af9ccd7b10bc646eafd37146c8aee2640935.nq.gz
    ├── 3e1dea25de40a92687d05241c6ebc6f88ab91226.nq.gz
    ├── 4056c1f68cfe27969d5c7c251be773e6e573994d.nq.gz
    ├── 4068cf104a0816fea1a4504d49d0a66881706938.nq.gz
    ├── 40f29f15978877731968c5e28653be9b40e64203.nq.gz
    ├── 4102be8dbcae6ca4e28a4d950055b5c263b855d1.nq.gz
    ├── 41aed8e6de4670c2727746bce2bc4ad1cbb0cb31.nq.gz
    ├── 41fa503060235407cad5a22a17a97b4259c67d8e.nq.gz
    ├── 42141a97bfe2ce1920e69dca0d53c44cb8a83973.nq.gz
    ├── 42576913630834945baa4210dd5f5e7b8a789ffd.nq.gz
    ├── 4526359debe23c979127d33e7ef766c461e6d874.nq.gz
    ├── 457d6e9929d1121f5f2f33a5aad202d4baa79356.nq.gz
    ├── 4581506251d04c653fbf44790a41a961b53545c5.nq.gz
    ├── 46b6e9029f2908a7313a4f42613a21b1958292d2.nq.gz
    ├── 47ade78bc173a31c12a4e2dca30aedcea1cc70d4.nq.gz
    ├── 48547b8ec6127fdf781b4e19657ef85b9f3675f3.nq.gz
    ├── 49271487190328bdbb4d98051847345c6a93cebd.nq.gz
    ├── 49869c152ca88c5d53e89fe9d53197e525bceede.nq.gz
    ├── 499c07fdf7c15de899986170e0285004f35efe56.nq.gz
    ├── 49a0469b369c8d7da5eaf34112e8d53b7016acec.nq.gz
    ├── 49c7554d4b2efff8e88120c51a2ac96526c1dba7.nq.gz
    ├── 4a2ed729bb6eb3d9b9a6809af5a87998d24afadd.nq.gz
    ├── 4a668789203d71d4680fd8edfc29a71cbb6bf7b4.nq.gz
    ├── 4ad39479b5e0bd1f4619c0c799d3ba656e72aa28.nq.gz
    ├── 4afac7040d385e0efb4139de0b79a4928f2a7a40.nq.gz
    ├── 4c1f07f6d33cc46923b030a334a920045905d0b1.nq.gz
    ├── 4d0e085ce13638869c3e42dbe4bf939803449d1b.nq.gz
    ├── 4d3652338a96a44926f8f92d78e04b1da89312fa.nq.gz
    ├── 4d4455b75d42245d64fdfff88e0a292a9233b8be.nq.gz
    ├── 4dab4383a2ca29e0fb6440c19e8071eb90f0575d.nq.gz
    ├── 4dc2a4c50ffa5dd0c7717d2d80731409aeb8cb0c.nq.gz
    ├── 4dcedfb0869b25d1cf5fd4fc68870458fcb0d8ed.nq.gz
    ├── 4ddc78d3726425c64a435ca7bcb43a41b6533355.nq.gz
    ├── 4e4a8635ccf1cdc47d707d24699792a4620073ce.nq.gz
    ├── 4e70a9f05200ebd1209f861f2a21e81191c65a1d.nq.gz
    ├── 4ecac3ff93ee264ff7264119a7bd4ff4d864a114.nq.gz
    ├── 4f7f18da228f0f6fcfbc0a2c30e91346f43b2379.nq.gz
    ├── 4f818e7f40348046bc1900b807dd685696e8c389.nq.gz
    ├── 4fe4b299bb4a1713e82a9639f41d22453afe7077.nq.gz
    ├── 50f034b1d3c35a3a24ba5562d36ee9ea702649eb.nq.gz
    ├── 51320effaaa771022b0630e5886c10ffc97dfa34.nq.gz
    ├── 51f8725a726dfa71af558d2dda635dcd42c20f5e.nq.gz
    ├── 5284ed19877427b29c86299a3e419a4a27eb45f3.nq.gz
    ├── 5324d86745cb9e04f57d1fd30f9113bcc93b36f6.nq.gz
    ├── 53fed8440b3571898415869c71b21a57ddff47ac.nq.gz
    ├── 540172c5e8e2aa82655e4c29cc1b022df62d0322.nq.gz
    ├── 548347e880ad00050343c509854b43ae1b48ff86.nq.gz
    ├── 55c57699ca5e0437d3f6d7cdd8d6b1da2a20406a.nq.gz
    ├── 56ce0b586663de46a8c991f930921038d78d65c4.nq.gz
    ├── 577166e1e169d7512960eca3f3728c20d0256715.nq.gz
    ├── 57a9045f2767e960d33db206dd3db4f34f1418ee.nq.gz
    ├── 5a0e112bb335ee9388892e2a591472931063ca5a.nq.gz
    ├── 5b6603dc9af7f204e6ae172d9a941df2dc746407.nq.gz
    ├── 5c7b1fdf946e6d8f4f4e99ba57c7b0430e3e48b9.nq.gz
    ├── 5dfcbb52f6fd4d72467a19e71fc3ade533eb0afe.nq.gz
    ├── 5e7616ff4bed8d70a31afea0899cf744c81daacc.nq.gz
    ├── 60b2012b694cbfef410fc72219a97592c6457a9f.nq.gz
    ├── 6145fb2c3ea279fb48fe65552b908e64512405f5.nq.gz
    ├── 61b9a6b903242ad49dfa1bf26801efcf6168fa1a.nq.gz
    ├── 62018ee3fc11cab190fd3b67d843a9a7546210d0.nq.gz
    ├── 626acca64a56cd82d24faa76cf7d3d56da266b66.nq.gz
    ├── 63355336b08d650630933dbf7c9fcf5e2b710b26.nq.gz
    ├── 640bf2d14457d10a1090c0cf92eb58baddb7a225.nq.gz
    ├── 64845681b22014a31458dd1520983829013aea57.nq.gz
    ├── 6505ab23a4a45e3605599f016f793ca57d194eeb.nq.gz
    ├── 6554b9a64b63f610201ec410bb6db655cd08cc40.nq.gz
    ├── 6622ed37881538c4b8a9b78838283f4f8edc656a.nq.gz
    ├── 664ba006f616e25f54ae6ae767c0efcf8e4876fc.nq.gz
    ├── 66950112054b03c3bd170d0580916636536c18f9.nq.gz
    ├── 67707411c63a2aac5693d45c727000f78aa6a668.nq.gz
    ├── 67976932ce66316c067b4b6178e7664b7ccc62f3.nq.gz
    ├── 6868d4f43be6ad05c2740186556a6a8da85a29d1.nq.gz
    ├── 6948e39e1174a419cdae74e76029563497f38aa0.nq.gz
    ├── 69523266ac0dd54098ab0b39a1a6897bed805d17.nq.gz
    ├── 6959f2707767696693ec664820b4d0879d2564a1.nq.gz
    ├── 696f3b47b385af7c3186d49d69efcf7249898a80.nq.gz
    ├── 6a41f894380fc545af6cb88b34718a628c88f874.nq.gz
    ├── 6ac965d6bf1434b2c332048741e39223b9190030.nq.gz
    ├── 6c717033a928c85a7e1a4a69b5dd607ffcae268c.nq.gz
    ├── 6cb008729117cdeaca740344aa1020c647a7e99c.nq.gz
    ├── 6d632c99e730643d599ce0d5f63a5183004e513d.nq.gz
    ├── 6d7f3280003b7c036f0f528ba9683e25a5684813.nq.gz
    ├── 6e4d8a41681ba636a98b6607983a15fb1f450b55.nq.gz
    ├── 6f0c8ae5cc962d9a94fbe9547e22bc758a51394f.nq.gz
    ├── 6fe2c43ad80ed3695917f9155b12d97ba5afda5c.nq.gz
    ├── 6fe37c0805f7c4ce63e3f3699d930ace3f571b40.nq.gz
    ├── 70fd8dfa50fd36306a2e18bd35cb6216dc18e746.nq.gz
    ├── 72942a56c53de2edd60d8e304aa20ad97b04e629.nq.gz
    ├── 72d6a1b3c1d94ad8b50b8d9cd1ac2f2238a9fe0d.nq.gz
    ├── 73a8cb18c4975b7f62ebaa6c405b0f4e5dc0b097.nq.gz
    ├── 73ed2d9dce0725cccfc193731344cdc9d9acb8ec.nq.gz
    ├── 7441b9ba6c81593e83f239e1741c3efe594634eb.nq.gz
    ├── 749f8ce09e4727cf788930b4cc468e3322a62320.nq.gz
    ├── 7526c3014d84ed642579a60db79babbcb48f05c7.nq.gz
    ├── 75b4875a295b78c46f4132ef4fbafcc21ffd1530.nq.gz
    ├── 7606e8179f5b0b09d23f022de43a620687afdb89.nq.gz
    ├── 76984670db9bb6bf176a4f3b18fdbfa270f8f05b.nq.gz
    ├── 76cf550ee30038ce989938bdef37df750b8037e2.nq.gz
    ├── 7866eb886a89d18a5a9b26070686f5349ce034fc.nq.gz
    ├── 7875f17a1096f70b18f50e2288ebf18d6bb9018f.nq.gz
    ├── 7a68a7961f4d28cfcecc2be2ef24e354a36710d9.nq.gz
    ├── 7bb6df03dbf5a414ea677546d7f0b8ec16b203c9.nq.gz
    ├── 7bbbdaf1210b8d059df515ce7b201d70558e0a24.nq.gz
    ├── 7c4cfbdfafa4cd00bd00b6239dc03670845ef48b.nq.gz
    ├── 7c9fed1e6d8afa19badbf7a3ccf47379d429917f.nq.gz
    ├── 7cde99df4b5bd4ba28ef1c2c514865c90db96a68.nq.gz
    ├── 7ce805fb90cb86fde609fb7d905c87d4cf62fc92.nq.gz
    ├── 7ce971a183532362fd0448ae1823aafcdb1bd9c2.nq.gz
    ├── 7d1276661511d1bd52ab218385ab893b90a00f5f.nq.gz
    ├── 7e1a8404d3c0355f94c2ba5c5ecec884c2f78bdf.nq.gz
    ├── 7eb25016bba29d2175e5210c7c232026fe07e6d8.nq.gz
    └── 7ec545d72b7a8afb1f79271d08d58353fb056986.nq.gz

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

[ansible-collections/ansible.utils](https://github.com/ansible-collections/ansible.utils)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
