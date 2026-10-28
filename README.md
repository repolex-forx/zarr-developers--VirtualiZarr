# Repolex Knowledge Graph of zarr-developers/VirtualiZarr

RDF knowledge graph data for [zarr-developers/VirtualiZarr](https://github.com/zarr-developers/VirtualiZarr), parsed by [repolex](https://repolex.ai).

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
rlex download zarr-developers/VirtualiZarr
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 4fc1bc54e628bcfea86e8cc0be144ea2a5ae173b
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 4fc1bc54e628bcfea86e8cc0be144ea2a5ae173b
│           └── chunk-001.nq.gz
├── blob
│   ├── 01e9000f7571e69a87c5e20034dccfe963b5295e.nq.gz
│   ├── 026b7c66c84073c45529e7c24b1196bca2559020.nq.gz
│   ├── 032bf5688c597e9cf5aafded58a915f0b7b4df3c.nq.gz
│   ├── 052cce614aabd15f3784a757aa414febff47c651.nq.gz
│   ├── 05847ad7d869c7d2bfbd2fbcb146c899878fcd9c.nq.gz
│   ├── 0637bcdecae5f662f11706871ef58840588705a4.nq.gz
│   ├── 07050a6742e50c18cd9397a557059f4a4e0e765e.nq.gz
│   ├── 070a0cda6d32ec4494bf42ec13da49d81a0ac005.nq.gz
│   ├── 097e5225d34279b16de9273732ad4e4f853028c3.nq.gz
│   ├── 0afb1c2f149d42a1efd93a3f0ca1fe628d323bf5.nq.gz
│   ├── 0b0f5279cc092ab7620698293688e8e150510f77.nq.gz
│   ├── 0b7f27060889aba9b5239dbbe9316ad484d7a7c9.nq.gz
│   ├── 0d655a7483ac03edb694c175446c9338001f40a1.nq.gz
│   ├── 0ea5afe3ff0703ddd7c1917f924dbccf3b161a09.nq.gz
│   ├── 0eca1309f9be46c8b1ee6cf23a7c0efc4fb098ce.nq.gz
│   ├── 1126045a46d5fdf26a96a72e1bbe17ee87580fc2.nq.gz
│   ├── 1147278577b6636ff465ed66cb834b8301ccf683.nq.gz
│   ├── 13521c2292cebf9503eb1ccaca12b669e7769fbd.nq.gz
│   ├── 137eefa5187fdfc829c5904212f02fee8d15e40a.nq.gz
│   ├── 13c1ce301e84855da67b12ce3a6d7044e7136298.nq.gz
│   ├── 151bb483545bc0dd8d14ba25ea23903d4bed4306.nq.gz
│   ├── 160ea00c3a336096895f3eea0b0a9600ddd9c342.nq.gz
│   ├── 1720b3c79dd29d52cf12b79f6f65c4a093317ea6.nq.gz
│   ├── 19106f066432bc846bc1888f31fff516e282d511.nq.gz
│   ├── 1aa51d2daf7e90e49d4e45a7cd0d1dae810cc81d.nq.gz
│   ├── 1b3ef0489f6c55feac139e20c9a6a63af8a7fded.nq.gz
│   ├── 1fae5dda733dbab67eeb0f8ff6259d1c5888272d.nq.gz
│   ├── 1fb5d11c366c21d30eae0a57cea1c309dc8337dc.nq.gz
│   ├── 251e1739c54313b18f758745986e587719e99620.nq.gz
│   ├── 2525a57421f0cdd5beaadd4ba1662ac91357e8b8.nq.gz
│   ├── 25a094f746fd60db3c643e6faa349e5f8b81266a.nq.gz
│   ├── 2602a6c27ea00d4ed17fb06d9b82ad28d43e8ff7.nq.gz
│   ├── 261eeb9e9f8b2b4b0d119366dda99c6fd7d35c64.nq.gz
│   ├── 2a593f6a4940717372cf83018ec9875c39bf6248.nq.gz
│   ├── 2abcf94c44b18d655d31c4f85a5f66c73e67fa21.nq.gz
│   ├── 2cbd1ac85da8c7f961fe7f1689f44072c9f62b1a.nq.gz
│   ├── 2e83bf6a858fb922b5cd7114611b03a31d5633b1.nq.gz
│   ├── 2f66d0664f94a184d1caa4b878bb2605979e5dfc.nq.gz
│   ├── 308758a0bdf5e9cfcc4b2b208bbf8b0ecd0085cf.nq.gz
│   ├── 32d261c77ef215093ef664bf4044d5081fb61694.nq.gz
│   ├── 337ff7f0105d2fa033f69fa28ce0adf8f19e6456.nq.gz
│   ├── 3490618df0a7961a1dcf13b921a3e4128fc46edd.nq.gz
│   ├── 34cd4bde406f68c98701a12a447395343688e2cb.nq.gz
│   ├── 36125eb79a3287945437b3d1159739f9e2a22b37.nq.gz
│   ├── 369b94672b5efefd837e9b3b40cf197e9a092170.nq.gz
│   ├── 379fcd297cd63695d04bdded1475d064d8d6ee74.nq.gz
│   ├── 393d33422e42b87fd68a2c0dc3add12e5f6f24ac.nq.gz
│   ├── 39b927bdafc6a162277fcb2b66c00e5d99075994.nq.gz
│   ├── 3ac3713836f02d30048ab16dafc5e066325a5949.nq.gz
│   ├── 3c41d72121b03d5d3d1acdcd5256707940ddf2fd.nq.gz
│   ├── 3e3e45bfb94d4721e22b9fcf1acd60a82ca394f1.nq.gz
│   ├── 3fcc1d6af23e1a321d79522ff233ea33781fb449.nq.gz
│   ├── 4428c271a4ed1b030035bb68e9b43cc58795fe63.nq.gz
│   ├── 44ad322ffa484e18318382d134576e14f15e1f36.nq.gz
│   ├── 45cea697bb44d1977d5bc93590e36b6c8ba3f1d9.nq.gz
│   ├── 4679679ba23a639cd85948e2995160daa618e437.nq.gz
│   ├── 4969593906d806e29db875f56653851a8a398ff4.nq.gz
│   ├── 49adac17213e777932f55530fbf4ac4d80f48224.nq.gz
│   ├── 49b2a2301628d55deacc4ae2e0ad47c90fee38a5.nq.gz
│   ├── 4c905211943c4649c7b67e065a62b27f02be7fe4.nq.gz
│   ├── 4e43c1e3ba80e93fa7e475ed77b0a077b87b4613.nq.gz
│   ├── 527869c816b0908a7dc86606470978ff389af645.nq.gz
│   ├── 537e03ac579dc6b27ddd2cf95751e0bef21cefb3.nq.gz
│   ├── 54d81048995dfdefd04d698a68d3f5c275bf1007.nq.gz
│   ├── 550f3132e650899c16310f5ee44a4bf514b18ee1.nq.gz
│   ├── 58c95561c798ce09393e742676572e2a649eb1ca.nq.gz
│   ├── 5902619a7fea3452ac7f655824b13e4f5e762a57.nq.gz
│   ├── 5bc870bdf31c7d691cbe6be9aaf9a6e60f31a628.nq.gz
│   ├── 5bff6d9318f2903df521f9ce9d870b3e7e19f16b.nq.gz
│   ├── 5c24c136f784c45dc38b2d44efb75f94b4c69c01.nq.gz
│   ├── 5ca1400cf01eea026e6b37329ba0156df32813a4.nq.gz
│   ├── 5d38730a406b182a5ca7f1340877e236991cdc85.nq.gz
│   ├── 5ec5a77169fa1a594ee2d706104d0d2d3f306c15.nq.gz
│   ├── 5f6c394fe4303c097f933fbeca95e7a4674f17ac.nq.gz
│   ├── 5f6d377cb282163025af39500a78122bcaeaa99a.nq.gz
│   ├── 5fc0eb4f56835d6ee35e94417773c2f9bb44434d.nq.gz
│   ├── 6062fd3089b5dcfef1ca0f6f48f7d4ee202d0eb0.nq.gz
│   ├── 60de83e1f1628247e132f37c9037b7e1831ddf5f.nq.gz
│   ├── 627424a286f774f9b30741117292077c000733f4.nq.gz
│   ├── 665fcb664f5a2e73e5ced00272da90ad94c21771.nq.gz
│   ├── 672cdecdf270cc4d9ba3fbadd75a3ce4436ec231.nq.gz
│   ├── 6a2b3ee286d9a787ab2bac52e2dbcf1db6dbe157.nq.gz
│   ├── 6c2fef71da27e4754439e28a77c9768d4d60fd88.nq.gz
│   ├── 6f56acd0aedb017e6afe9093c28658c847c4fb4a.nq.gz
│   ├── 6fda393dc6d1ac318e448e6c219d47d0ddf4cbb3.nq.gz
│   ├── 700e9822437e3c98f233a67444c05da960a9ca0e.nq.gz
│   ├── 75cae8625a625e3ced5fea2903ec161906f051ba.nq.gz
│   ├── 76bba4a8b4472383eba80b77d6d0a178534950ed.nq.gz
│   ├── 76d9ba1db59d80ac9e5b18936a7f9d862ae59524.nq.gz
│   ├── 774933d4814b2dbc6517a3718f6e1c966d701324.nq.gz
│   ├── 79ec0ed686c1acb556d61e2133d1efbdd928cc7b.nq.gz
│   ├── 7cabe3ab0db6d0e172f33f5eb1696885e0772c78.nq.gz
│   ├── 7ed7d1d516fa4eab416e8da5cbebfc37df0a8fd7.nq.gz
│   ├── 7eda77f1c304cfa5f9ec759b9c94cdb119ea8da2.nq.gz
│   ├── 801047926a6481356d7cf099aec2c75530926930.nq.gz
│   ├── 80601f67c60b8101ade84a66d58283e86ae39e1a.nq.gz
│   ├── 820e272f506da2061e524afe875a148683858a7d.nq.gz
│   ├── 838901c6b7f8029653443bc35e338bb8086017bc.nq.gz
│   ├── 838c0eef597fa78675e13b6e86886aa4a6e2321c.nq.gz
│   ├── 84993aada770c1b52a52ced673d4756bcfceb119.nq.gz
│   ├── 86694022c1b4fec0f8f670b8cf6a181c348e61c8.nq.gz
│   ├── 8afe50f2f60217f7b9a3bb04e4a88b4f3cc44c94.nq.gz
│   ├── 8ffc6e7112d3f33bc3649b48d8a4f2490f5b69d7.nq.gz
│   ├── 932b2a8955620dec6037d44e012e9159be279166.nq.gz
│   ├── 961e3787415344c78a48439826828df1ddfb6b8b.nq.gz
│   ├── 9656f7d357edc874e2981b7e1fd3eb4caab25723.nq.gz
│   ├── 97336a9ce67a26be2fd226124c80c16847bae980.nq.gz
│   ├── 9a65fb894d1947f226d29aa5a9cc1a552077642e.nq.gz
│   ├── 9ba0aa534586aad54058db213a64e6615df948ee.nq.gz
│   ├── 9c9b48fc558eeddef86f0e480dd55d13f6c60d4b.nq.gz
│   ├── 9d410c17ad68826015051bcb73418805bd7952f2.nq.gz
│   ├── 9e2ee6e1cd8105a5ba211f2e88568bba81757a8a.nq.gz
│   ├── 9eaf92888f6963ff481971932e18698cb1f2eac2.nq.gz
│   ├── a0150b3993026814cf41a6684ef8aca6cd40f437.nq.gz
│   ├── a0855f113a2b2f57997cf693818855837e7db354.nq.gz
│   ├── a0aa8b12930e285c17cd7ea5946c69b8d6196d84.nq.gz
│   ├── a2f6a3e3ce207bc20671c876b3f84f31bb579d1d.nq.gz
│   ├── a4c6d969a3848ddfdbff1fd1de3462673360cad0.nq.gz
│   ├── a9355f483a2f4c77ff5e7d4c5a7a14021350e9e7.nq.gz
│   ├── a9ea84063c2e204709a8bfd08e3d67a7b9278478.nq.gz
│   ├── ac749cd1a74a0ddf96de97f76691eb56070bef98.nq.gz
│   ├── af2981f1bc8193002e1502b6765e9eca432a2271.nq.gz
│   ├── afee919e0c93af78037e886833aa3712190cfe9c.nq.gz
│   ├── aff9d23c5eee4ad20285a0f2138a25bca48c69ae.nq.gz
│   ├── b142b48059b48dafd4f211c8ff67d2ee5edafa72.nq.gz
│   ├── b1edd8e2277f39236b67516bc6b710a765bb302e.nq.gz
│   ├── b3f5bdccfe43263f2239bc51c8e07ebd7ad71df9.nq.gz
│   ├── b748f706955c22dcb0d818ebce2585e2af88f2e2.nq.gz
│   ├── b95ccbb71623d678fc6af78bb96a9842ee2645ad.nq.gz
│   ├── ba6938f870cdc68bb77fb7aaf9ad945d5326b10b.nq.gz
│   ├── beabbf5ae8bb5ec9bdd82d3b460afae2a732388e.nq.gz
│   ├── c2d3559d0591b8d46b1273a0c8e6c5848352ad4d.nq.gz
│   ├── c471ed62f6b45e75ab6b59fab4fa0ce557c214bb.nq.gz
│   ├── c4826ff94ef6eaf89fd9f23b43554b61bd410b03.nq.gz
│   ├── c5ff6a25c757174f18cd09efed5fc31573e8698b.nq.gz
│   ├── c6b7b3aa4a413ee2410761e0969fafbb6b1901a1.nq.gz
│   ├── c7db025e0a25faa49712bb6f22d600c23bc0753e.nq.gz
│   ├── c89408aaa3b9d3112600bb7f612490fdd664a90a.nq.gz
│   ├── cbc36fce2cfb62d79825fdc19e793444a17d3f48.nq.gz
│   ├── cd4905392a11339a9a6130964a7f11ede5d5964d.nq.gz
│   ├── cdffed1e38d4e2fe08422cceec24612409a7dad0.nq.gz
│   ├── cf0e110c63f5c49ca874bda5500b2e014e18b69a.nq.gz
│   ├── d051012e167b55503beda2c07c42e07befa4745e.nq.gz
│   ├── d0f90b56aa8b4f899ac834537fc954875b195a68.nq.gz
│   ├── d124cca3a0c015c0723d126198520e41316da477.nq.gz
│   ├── d1793c6a79ef0b1f5a689a88ff999ce4d26fd814.nq.gz
│   ├── d1b688d0f63e7eec2a678159cfba0adeda995f38.nq.gz
│   ├── d6d7addb705ec352c355d3433b467304469ac6a2.nq.gz
│   ├── d71e04c151d22d0d524d23eec5cd28b6d292a0a8.nq.gz
│   ├── d785f08646f8b6b74af2125c9e4b0e1955fce829.nq.gz
│   ├── d831200c89a95a0bc3e371d42363e142428fae78.nq.gz
│   ├── d954cf0675842ea8f4a3b06062bdfed51eb9690e.nq.gz
│   ├── da461c49c62f79d632d873dbd89b56dde030e718.nq.gz
│   ├── dbbcc4fa0fc8705cba86f0db377db8dafe742b74.nq.gz
│   ├── df996c03f6cd202c7e00aa124cdd27d13f7e482b.nq.gz
│   ├── e04d6833d83093750fa2538affb78e700b49e930.nq.gz
│   ├── e090dd8d1fa295fb3d4ba8d916eb26e0fc27b2c0.nq.gz
│   ├── e0eced794d8a98a3a340ea2d6e4ce635a24006e9.nq.gz
│   ├── e221da42f5eb8b3240bc7df8456cba752a1184d8.nq.gz
│   ├── e3d3f0c22118a29eba4e897fd539d2901f95ccaa.nq.gz
│   ├── e5d803864004ba885351619b8b0b6a635c32bc4c.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e779317ca9838c2569acce156b2ba53dc5286740.nq.gz
│   ├── e865abd102b3f76fd730556fdecbb0950df47a69.nq.gz
│   ├── ec85374d0bb1099ea2c13a0fd3657a8c22e57b27.nq.gz
│   ├── ee3cafbdb6a8f689201625950cb6161adcef57e4.nq.gz
│   ├── f0c5160390665db5234bcd8cd6d6334f72cafebc.nq.gz
│   ├── f48413b7ee5a15a971710ca842beb0e3036bfe0c.nq.gz
│   ├── f5fa6e9fac1160246315eec614b84e4cd135229c.nq.gz
│   ├── f651de879675f73e074db16f6ce7b3f5e517d7f7.nq.gz
│   ├── f6d942b8afccb5098c4baa7b5906a369ccbe2054.nq.gz
│   ├── f8956f1c1bf83a872d8f3742160ba8fb72133a03.nq.gz
│   ├── fa2852750d36f198e764a6e7ad2ac9e807a5061b.nq.gz
│   ├── fba4c0f42455cd14a0da18161ca421163dd63d1c.nq.gz
│   ├── fc59bfebefdaf9f98035f1acbd83d0a765b3b1fc.nq.gz
│   ├── fce6d26123846422365a63b6404e6b51b4f429c8.nq.gz
│   ├── fdac2dcb278fb9ad5535dcf78846af1bfc9de0c5.nq.gz
│   └── ff757bfbadc55ebc701e383fd2c66701b8d5b212.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 4fc1bc54e628bcfea86e8cc0be144ea2a5ae173b.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 186 files
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

[zarr-developers/VirtualiZarr](https://github.com/zarr-developers/VirtualiZarr)

---
*Parsed on 2026-10-28 by [repolex](https://repolex.ai)*
