:robot: I have created a release *beep* *boop*
---


<details><summary>2.0.0-alpha.4</summary>

## [2.0.0-alpha.4](https://github.com/jasonmacdonald/zenstack/compare/v2.0.0-alpha.3...v2.0.0-alpha.4) (2024-07-10)


### Features

* JetBrains plugin for ZModel ([#904](https://github.com/jasonmacdonald/zenstack/issues/904)) ([c79be9e](https://github.com/jasonmacdonald/zenstack/commit/c79be9eb7f6b602bc84214bded2b927935b6273a))
* make parameters of transactions configurable ([#988](https://github.com/jasonmacdonald/zenstack/issues/988)) ([d0745b1](https://github.com/jasonmacdonald/zenstack/commit/d0745b149a5ce6abfef546de0b9243ddc4f6e765))


### Bug Fixes

* disable textmate bundle when JetBrains plugin is uninstalled ([#918](https://github.com/jasonmacdonald/zenstack/issues/918)) ([7e9cc35](https://github.com/jasonmacdonald/zenstack/commit/7e9cc35a68ed31e25e7c7eac764528f55a18ac7b))
* incorrect cross-model comparision for && and || expressions ([#1512](https://github.com/jasonmacdonald/zenstack/issues/1512)) ([908048b](https://github.com/jasonmacdonald/zenstack/commit/908048b01430ff6552e8df558d5b5905136ea5cc))
* infinite recursion when injecting field selection for field-level permission check ([#1452](https://github.com/jasonmacdonald/zenstack/issues/1452)) ([29962e0](https://github.com/jasonmacdonald/zenstack/commit/29962e0b48a73ae6d42f43f2575048ba9cf6a953))
* issue 961, incorrect policy injection for nested `updateMany` ([#962](https://github.com/jasonmacdonald/zenstack/issues/962)) ([2b2bfcf](https://github.com/jasonmacdonald/zenstack/commit/2b2bfcff965f9a70ff2764e6fbc7613b6f061685))
* issues with cross-model comparison identification and injection ([#1508](https://github.com/jasonmacdonald/zenstack/issues/1508)) ([665f9b3](https://github.com/jasonmacdonald/zenstack/commit/665f9b33b58acc5170c4ccb8e73be525fbb89734))
* supports for complex usage of "@[@index](https://github.com/index)" in zmodel ([#995](https://github.com/jasonmacdonald/zenstack/issues/995)) ([541cd97](https://github.com/jasonmacdonald/zenstack/commit/541cd973081cbbf2d9e2e571ee8f971bc859150c))
* **tanstack:** incorrect InfiniteData import for vue-query ([#1498](https://github.com/jasonmacdonald/zenstack/issues/1498)) ([92f187f](https://github.com/jasonmacdonald/zenstack/commit/92f187f9190517df5baca795f12386c12c6694e9))
</details>

<details><summary>2.0.0-alpha.4</summary>

## [2.0.0-alpha.4](https://github.com/jasonmacdonald/zenstack/compare/v2.0.0-alpha.3...v2.0.0-alpha.4) (2024-07-10)


### Features

* a better "zod" plugin ([#521](https://github.com/jasonmacdonald/zenstack/issues/521)) ([2280f83](https://github.com/jasonmacdonald/zenstack/commit/2280f83cd7f1f597fddfd6ab0c99417200124452))
* JetBrains plugin for ZModel ([#904](https://github.com/jasonmacdonald/zenstack/issues/904)) ([c79be9e](https://github.com/jasonmacdonald/zenstack/commit/c79be9eb7f6b602bc84214bded2b927935b6273a))
* make parameters of transactions configurable ([#988](https://github.com/jasonmacdonald/zenstack/issues/988)) ([d0745b1](https://github.com/jasonmacdonald/zenstack/commit/d0745b149a5ce6abfef546de0b9243ddc4f6e765))
* support Prisma view ([#579](https://github.com/jasonmacdonald/zenstack/issues/579)) ([af151b7](https://github.com/jasonmacdonald/zenstack/commit/af151b7b311ee96b626376b8a17103b18c261f65))


### Bug Fixes

* add "exports" to generated package.json, make trpc code-gen compatible with vite ([#677](https://github.com/jasonmacdonald/zenstack/issues/677)) ([df67f30](https://github.com/jasonmacdonald/zenstack/commit/df67f301119db23e5048464de2f73bff1a2adffc))
* add `CheckSelect` type into code for Prisma version backward compatibility ([#619](https://github.com/jasonmacdonald/zenstack/issues/619)) ([3e09a3a](https://github.com/jasonmacdonald/zenstack/commit/3e09a3a6646ae0f6e393cc0f92991c9b5d0c4d29))
* allow "view" and "import" as identifier ([#750](https://github.com/jasonmacdonald/zenstack/issues/750)) ([2e15dfb](https://github.com/jasonmacdonald/zenstack/commit/2e15dfb747fa871a5b25661e3e320a1a5f3cc92a))
* allow models without field declarations ([#749](https://github.com/jasonmacdonald/zenstack/issues/749)) ([43322e1](https://github.com/jasonmacdonald/zenstack/commit/43322e111adfc7d888aa8dc04445a5b0f8c2dbcc))
* automatically enable "@core/zod" plugin when there're validation rules ([#535](https://github.com/jasonmacdonald/zenstack/issues/535)) ([0519421](https://github.com/jasonmacdonald/zenstack/commit/05194219f28e49ee11d1a1bd9a78146e9b76eada))
* build, lint and etc. ([#833](https://github.com/jasonmacdonald/zenstack/issues/833)) ([cccbc3c](https://github.com/jasonmacdonald/zenstack/commit/cccbc3c82ad522d40bc76ad7b84b1305d378b1db))
* change back to loading from literal ".zenstack" path otherwise Vercel breaks :( ([#701](https://github.com/jasonmacdonald/zenstack/issues/701)) ([2d41a9f](https://github.com/jasonmacdonald/zenstack/commit/2d41a9fcffab2fa228356a5cc45b4c2ecd62fd63))
* clean up zod generation ([#883](https://github.com/jasonmacdonald/zenstack/issues/883)) ([909281f](https://github.com/jasonmacdonald/zenstack/commit/909281f8090734322c0cab09d0187b6b5e813c9a))
* clean up zod generation ([#883](https://github.com/jasonmacdonald/zenstack/issues/883)) ([9d4a8ed](https://github.com/jasonmacdonald/zenstack/commit/9d4a8ede7d42d1966fd5a12d64a5992092f4bc7d))
* enable auto completion inside attribute ([#949](https://github.com/jasonmacdonald/zenstack/issues/949)) ([20d5bfc](https://github.com/jasonmacdonald/zenstack/commit/20d5bfc506a42b520eb1cf390149b7afc7c38701))
* enhanced client doesn't work with client extensions that add new model methods ([#851](https://github.com/jasonmacdonald/zenstack/issues/851)) ([ea564c9](https://github.com/jasonmacdonald/zenstack/commit/ea564c93e9ca2a888c0e53216633d66c733f6beb))
* hooks generation emits Provider export for backward compatibility ([#594](https://github.com/jasonmacdonald/zenstack/issues/594)) ([ca3ebda](https://github.com/jasonmacdonald/zenstack/commit/ca3ebdae4e213d3901bb5834fd9ebf1217da94a7))
* improve consistency of generated guard code ([#616](https://github.com/jasonmacdonald/zenstack/issues/616)) ([1b7b5bd](https://github.com/jasonmacdonald/zenstack/commit/1b7b5bda3f5106d31b7f5e70be27158fb8217600))
* incorrect cross-model comparision for && and || expressions ([#1512](https://github.com/jasonmacdonald/zenstack/issues/1512)) ([908048b](https://github.com/jasonmacdonald/zenstack/commit/908048b01430ff6552e8df558d5b5905136ea5cc))
* incorrect relation owner analysis ([#610](https://github.com/jasonmacdonald/zenstack/issues/610)) ([c89012b](https://github.com/jasonmacdonald/zenstack/commit/c89012bcb8d32588cc7f5a1df19088292e571cec))
* incorrect reverse query built for to-many relation ([#815](https://github.com/jasonmacdonald/zenstack/issues/815)) ([2c345e1](https://github.com/jasonmacdonald/zenstack/commit/2c345e1d4fe7274b7a08c1178afccede1d694327))
* infinite recursion when injecting field selection for field-level permission check ([#1452](https://github.com/jasonmacdonald/zenstack/issues/1452)) ([29962e0](https://github.com/jasonmacdonald/zenstack/commit/29962e0b48a73ae6d42f43f2575048ba9cf6a953))
* issue [#627](https://github.com/jasonmacdonald/zenstack/issues/627) ([#628](https://github.com/jasonmacdonald/zenstack/issues/628)) ([2ef93cb](https://github.com/jasonmacdonald/zenstack/commit/2ef93cb932e7aed6923cd3d7e69069d0c9ff161b))
* issue 961, incorrect policy injection for nested `updateMany` ([#962](https://github.com/jasonmacdonald/zenstack/issues/962)) ([2b2bfcf](https://github.com/jasonmacdonald/zenstack/commit/2b2bfcff965f9a70ff2764e6fbc7613b6f061685))
* issues with cross-model comparison identification and injection ([#1508](https://github.com/jasonmacdonald/zenstack/issues/1508)) ([665f9b3](https://github.com/jasonmacdonald/zenstack/commit/665f9b33b58acc5170c4ccb8e73be525fbb89734))
* make sure Buffer is imported ([#596](https://github.com/jasonmacdonald/zenstack/issues/596)) ([76a0bac](https://github.com/jasonmacdonald/zenstack/commit/76a0bac9c63707baf34a072e398b63156c1e0640))
* make sure zod schemas have type annotations ([#574](https://github.com/jasonmacdonald/zenstack/issues/574)) ([51985b1](https://github.com/jasonmacdonald/zenstack/commit/51985b1279dca8e82a7275330a7b6597f37d15a4))
* number literal precision issue ([#659](https://github.com/jasonmacdonald/zenstack/issues/659)) ([6275701](https://github.com/jasonmacdonald/zenstack/commit/627570166f858488aa7fb6a6291fccfadb0d9f9f))
* post-update rules incorrectly reject update ([#826](https://github.com/jasonmacdonald/zenstack/issues/826)) ([d921a7c](https://github.com/jasonmacdonald/zenstack/commit/d921a7ca6bef0341ccf5bc50e195156695129e7f))
* post-update rules incorrectly reject update ([#826](https://github.com/jasonmacdonald/zenstack/issues/826)) ([e85831e](https://github.com/jasonmacdonald/zenstack/commit/e85831e98d08a433febb5a8fecf8d539150ced08))
* support for string escaping in ZModel ([#668](https://github.com/jasonmacdonald/zenstack/issues/668)) ([f034839](https://github.com/jasonmacdonald/zenstack/commit/f034839867fa438da866bd87548b4a18246dee21))
* support postgres extensions ([#718](https://github.com/jasonmacdonald/zenstack/issues/718)) ([cdc98e0](https://github.com/jasonmacdonald/zenstack/commit/cdc98e08224a23ea3f6e5d620c11c90a34ed6435))
* support string literal keys for object expressions in ZModel ([#752](https://github.com/jasonmacdonald/zenstack/issues/752)) ([22b1bf9](https://github.com/jasonmacdonald/zenstack/commit/22b1bf9ddd4062000f2cd7d183e004dd3d5917c6))
* supporting using type names as reference target as well ([d17a85c](https://github.com/jasonmacdonald/zenstack/commit/d17a85c1020d616085e7957816c17d7481894169))
* supports for complex usage of "@[@index](https://github.com/index)" in zmodel ([#995](https://github.com/jasonmacdonald/zenstack/issues/995)) ([541cd97](https://github.com/jasonmacdonald/zenstack/commit/541cd973081cbbf2d9e2e571ee8f971bc859150c))
* **tanstack:** incorrect InfiniteData import for vue-query ([#1498](https://github.com/jasonmacdonald/zenstack/issues/1498)) ([92f187f](https://github.com/jasonmacdonald/zenstack/commit/92f187f9190517df5baca795f12386c12c6694e9))
* Validation errors when using true or false as prefix of id ([#530](https://github.com/jasonmacdonald/zenstack/issues/530)) ([551b33d](https://github.com/jasonmacdonald/zenstack/commit/551b33d8bec622e445b5635ae4a147774c91c0fe))
* vscode language accidentally bundles prisma packages  ([#625](https://github.com/jasonmacdonald/zenstack/issues/625)) ([f6b68da](https://github.com/jasonmacdonald/zenstack/commit/f6b68dabc9e089230bc6d8f8e802e8fbc43a8a69))
* **zmodel:** allow type names to be used as declaration names ([#1424](https://github.com/jasonmacdonald/zenstack/issues/1424)) ([5806a4d](https://github.com/jasonmacdonald/zenstack/commit/5806a4dc4585293e1da746bdc1485c54d7e993b7))
* **zmodel:** fix grammar ambiguity ([#1433](https://github.com/jasonmacdonald/zenstack/issues/1433)) ([2c7c82b](https://github.com/jasonmacdonald/zenstack/commit/2c7c82b29f54a7df4752aa74dfcda2c8f0a69a24))
</details>

<details><summary>2.0.0-alpha.4</summary>

## [2.0.0-alpha.4](https://github.com/jasonmacdonald/zenstack/compare/v2.0.0-alpha.3...v2.0.0-alpha.4) (2024-07-10)


### Features

* make parameters of transactions configurable ([#988](https://github.com/jasonmacdonald/zenstack/issues/988)) ([d0745b1](https://github.com/jasonmacdonald/zenstack/commit/d0745b149a5ce6abfef546de0b9243ddc4f6e765))
* RedwoodJS integration package ([#911](https://github.com/jasonmacdonald/zenstack/issues/911)) ([e4aeee3](https://github.com/jasonmacdonald/zenstack/commit/e4aeee32ae3a5ab1718fd1daa2f93043fb68a8d5))


### Bug Fixes

* incorrect cross-model comparision for && and || expressions ([#1512](https://github.com/jasonmacdonald/zenstack/issues/1512)) ([908048b](https://github.com/jasonmacdonald/zenstack/commit/908048b01430ff6552e8df558d5b5905136ea5cc))
* infinite recursion when injecting field selection for field-level permission check ([#1452](https://github.com/jasonmacdonald/zenstack/issues/1452)) ([29962e0](https://github.com/jasonmacdonald/zenstack/commit/29962e0b48a73ae6d42f43f2575048ba9cf6a953))
* issue 961, incorrect policy injection for nested `updateMany` ([#962](https://github.com/jasonmacdonald/zenstack/issues/962)) ([2b2bfcf](https://github.com/jasonmacdonald/zenstack/commit/2b2bfcff965f9a70ff2764e6fbc7613b6f061685))
* issues with cross-model comparison identification and injection ([#1508](https://github.com/jasonmacdonald/zenstack/issues/1508)) ([665f9b3](https://github.com/jasonmacdonald/zenstack/commit/665f9b33b58acc5170c4ccb8e73be525fbb89734))
* supports for complex usage of "@[@index](https://github.com/index)" in zmodel ([#995](https://github.com/jasonmacdonald/zenstack/issues/995)) ([541cd97](https://github.com/jasonmacdonald/zenstack/commit/541cd973081cbbf2d9e2e571ee8f971bc859150c))
* **tanstack:** incorrect InfiniteData import for vue-query ([#1498](https://github.com/jasonmacdonald/zenstack/issues/1498)) ([92f187f](https://github.com/jasonmacdonald/zenstack/commit/92f187f9190517df5baca795f12386c12c6694e9))
</details>

<details><summary>2.0.0-alpha.4</summary>

## [2.0.0-alpha.4](https://github.com/jasonmacdonald/zenstack/compare/v2.0.0-alpha.3...v2.0.0-alpha.4) (2024-07-10)


### Features

* a better "zod" plugin ([#521](https://github.com/jasonmacdonald/zenstack/issues/521)) ([2280f83](https://github.com/jasonmacdonald/zenstack/commit/2280f83cd7f1f597fddfd6ab0c99417200124452))
* always use superjson to serialize/deserialize in the api layer ([#585](https://github.com/jasonmacdonald/zenstack/issues/585)) ([46fec66](https://github.com/jasonmacdonald/zenstack/commit/46fec666c3af971010c69e467f08f55830655441))
* improved automatic query invalidation for tanstack-query ([#790](https://github.com/jasonmacdonald/zenstack/issues/790)) ([42d654f](https://github.com/jasonmacdonald/zenstack/commit/42d654fcfaa40b09fde578db79792c69e1e3b908))
* include raw zod errors in response ([#691](https://github.com/jasonmacdonald/zenstack/issues/691)) ([b5da998](https://github.com/jasonmacdonald/zenstack/commit/b5da998b7fa11c19b85cebd0956803d854332b4d))
* make parameters of transactions configurable ([#988](https://github.com/jasonmacdonald/zenstack/issues/988)) ([d0745b1](https://github.com/jasonmacdonald/zenstack/commit/d0745b149a5ce6abfef546de0b9243ddc4f6e765))
* support Prisma v5 ([#587](https://github.com/jasonmacdonald/zenstack/issues/587)) ([b0d9154](https://github.com/jasonmacdonald/zenstack/commit/b0d9154270a89c6c93c7a8f1aada85c413d16d6f))


### Bug Fixes

* add "exports" to generated package.json, make trpc code-gen compatible with vite ([#677](https://github.com/jasonmacdonald/zenstack/issues/677)) ([df67f30](https://github.com/jasonmacdonald/zenstack/commit/df67f301119db23e5048464de2f73bff1a2adffc))
* add `CheckSelect` type into code for Prisma version backward compatibility ([#619](https://github.com/jasonmacdonald/zenstack/issues/619)) ([3e09a3a](https://github.com/jasonmacdonald/zenstack/commit/3e09a3a6646ae0f6e393cc0f92991c9b5d0c4d29))
* avoid importing prisma-related code into language server ([#1441](https://github.com/jasonmacdonald/zenstack/issues/1441)) ([b22c6a3](https://github.com/jasonmacdonald/zenstack/commit/b22c6a3ce238ec766d910f23e83aea4e8f10c05d))
* bugs related to model name casing ([#645](https://github.com/jasonmacdonald/zenstack/issues/645)) ([32d5b26](https://github.com/jasonmacdonald/zenstack/commit/32d5b262cacdd03209a56027e4c2cbda1bc408c0))
* build, lint and etc. ([#833](https://github.com/jasonmacdonald/zenstack/issues/833)) ([cccbc3c](https://github.com/jasonmacdonald/zenstack/commit/cccbc3c82ad522d40bc76ad7b84b1305d378b1db))
* change back to loading from literal ".zenstack" path otherwise Vercel breaks :( ([#701](https://github.com/jasonmacdonald/zenstack/issues/701)) ([2d41a9f](https://github.com/jasonmacdonald/zenstack/commit/2d41a9fcffab2fa228356a5cc45b4c2ecd62fd63))
* clean up zod generation ([#883](https://github.com/jasonmacdonald/zenstack/issues/883)) ([909281f](https://github.com/jasonmacdonald/zenstack/commit/909281f8090734322c0cab09d0187b6b5e813c9a))
* clean up zod generation ([#883](https://github.com/jasonmacdonald/zenstack/issues/883)) ([9d4a8ed](https://github.com/jasonmacdonald/zenstack/commit/9d4a8ede7d42d1966fd5a12d64a5992092f4bc7d))
* compatibility with Prisma's "omit" feature ([#1432](https://github.com/jasonmacdonald/zenstack/issues/1432)) ([296ca25](https://github.com/jasonmacdonald/zenstack/commit/296ca259c8dd3e38fa988378df4a9e351a11b20b))
* enhanced client doesn't work with client extensions that add new model methods ([#851](https://github.com/jasonmacdonald/zenstack/issues/851)) ([ea564c9](https://github.com/jasonmacdonald/zenstack/commit/ea564c93e9ca2a888c0e53216633d66c733f6beb))
* hooks generation emits Provider export for backward compatibility ([#594](https://github.com/jasonmacdonald/zenstack/issues/594)) ([ca3ebda](https://github.com/jasonmacdonald/zenstack/commit/ca3ebdae4e213d3901bb5834fd9ebf1217da94a7))
* improve consistency of generated guard code ([#616](https://github.com/jasonmacdonald/zenstack/issues/616)) ([1b7b5bd](https://github.com/jasonmacdonald/zenstack/commit/1b7b5bda3f5106d31b7f5e70be27158fb8217600))
* incorrect cross-model comparision for && and || expressions ([#1512](https://github.com/jasonmacdonald/zenstack/issues/1512)) ([908048b](https://github.com/jasonmacdonald/zenstack/commit/908048b01430ff6552e8df558d5b5905136ea5cc))
* incorrect relation owner analysis ([#610](https://github.com/jasonmacdonald/zenstack/issues/610)) ([c89012b](https://github.com/jasonmacdonald/zenstack/commit/c89012bcb8d32588cc7f5a1df19088292e571cec))
* incorrect reverse query built for to-many relation ([#815](https://github.com/jasonmacdonald/zenstack/issues/815)) ([2c345e1](https://github.com/jasonmacdonald/zenstack/commit/2c345e1d4fe7274b7a08c1178afccede1d694327))
* infinite recursion when injecting field selection for field-level permission check ([#1452](https://github.com/jasonmacdonald/zenstack/issues/1452)) ([29962e0](https://github.com/jasonmacdonald/zenstack/commit/29962e0b48a73ae6d42f43f2575048ba9cf6a953))
* issue [#627](https://github.com/jasonmacdonald/zenstack/issues/627) ([#628](https://github.com/jasonmacdonald/zenstack/issues/628)) ([2ef93cb](https://github.com/jasonmacdonald/zenstack/commit/2ef93cb932e7aed6923cd3d7e69069d0c9ff161b))
* issue 961, incorrect policy injection for nested `updateMany` ([#962](https://github.com/jasonmacdonald/zenstack/issues/962)) ([2b2bfcf](https://github.com/jasonmacdonald/zenstack/commit/2b2bfcff965f9a70ff2764e6fbc7613b6f061685))
* issue with client typing generation in trpc plugin ([#673](https://github.com/jasonmacdonald/zenstack/issues/673)) ([576c4f7](https://github.com/jasonmacdonald/zenstack/commit/576c4f7a4858dfa2dcb9c1a7f75af8d1ca48a8ce))
* issues with cross-model comparison identification and injection ([#1508](https://github.com/jasonmacdonald/zenstack/issues/1508)) ([665f9b3](https://github.com/jasonmacdonald/zenstack/commit/665f9b33b58acc5170c4ccb8e73be525fbb89734))
* make sure Buffer is imported ([#596](https://github.com/jasonmacdonald/zenstack/issues/596)) ([76a0bac](https://github.com/jasonmacdonald/zenstack/commit/76a0bac9c63707baf34a072e398b63156c1e0640))
* make sure zod schemas have type annotations ([#574](https://github.com/jasonmacdonald/zenstack/issues/574)) ([51985b1](https://github.com/jasonmacdonald/zenstack/commit/51985b1279dca8e82a7275330a7b6597f37d15a4))
* openapi - do not generate "id" field in create input if the field has default value ([#758](https://github.com/jasonmacdonald/zenstack/issues/758)) ([787a244](https://github.com/jasonmacdonald/zenstack/commit/787a24453c3a32250260ebc138c26a829074ae8f))
* **openapi:** `CreateManyArgs` does not take array as input ([#1246](https://github.com/jasonmacdonald/zenstack/issues/1246)) ([8137481](https://github.com/jasonmacdonald/zenstack/commit/813748160e35913f5b26b79b81886ab9ddb02070))
* post-update rules incorrectly reject update ([#826](https://github.com/jasonmacdonald/zenstack/issues/826)) ([d921a7c](https://github.com/jasonmacdonald/zenstack/commit/d921a7ca6bef0341ccf5bc50e195156695129e7f))
* post-update rules incorrectly reject update ([#826](https://github.com/jasonmacdonald/zenstack/issues/826)) ([e85831e](https://github.com/jasonmacdonald/zenstack/commit/e85831e98d08a433febb5a8fecf8d539150ced08))
* properly handle nullable fields in openapi generator ([#906](https://github.com/jasonmacdonald/zenstack/issues/906)) ([0e422ad](https://github.com/jasonmacdonald/zenstack/commit/0e422adf1a7f274b850eeba09ef1781b13ce9f1b))
* supports for complex usage of "@[@index](https://github.com/index)" in zmodel ([#995](https://github.com/jasonmacdonald/zenstack/issues/995)) ([541cd97](https://github.com/jasonmacdonald/zenstack/commit/541cd973081cbbf2d9e2e571ee8f971bc859150c))
* **tanstack:** incorrect InfiniteData import for vue-query ([#1498](https://github.com/jasonmacdonald/zenstack/issues/1498)) ([92f187f](https://github.com/jasonmacdonald/zenstack/commit/92f187f9190517df5baca795f12386c12c6694e9))
* vscode language accidentally bundles prisma packages  ([#625](https://github.com/jasonmacdonald/zenstack/issues/625)) ([f6b68da](https://github.com/jasonmacdonald/zenstack/commit/f6b68dabc9e089230bc6d8f8e802e8fbc43a8a69))
* zod and openapi generation error when "fullTextSearch" is enabled ([#658](https://github.com/jasonmacdonald/zenstack/issues/658)) ([0cb7cd1](https://github.com/jasonmacdonald/zenstack/commit/0cb7cd1ae5e8c5d4a72d0891c9624291aafcbcd8))
</details>

<details><summary>2.0.0-alpha.4</summary>

## [2.0.0-alpha.4](https://github.com/jasonmacdonald/zenstack/compare/v2.0.0-alpha.3...v2.0.0-alpha.4) (2024-07-10)


### Features

* a better "zod" plugin ([#521](https://github.com/jasonmacdonald/zenstack/issues/521)) ([2280f83](https://github.com/jasonmacdonald/zenstack/commit/2280f83cd7f1f597fddfd6ab0c99417200124452))
* add "loadPath" options to runtime API and server adapter options ([#696](https://github.com/jasonmacdonald/zenstack/issues/696)) ([fc50deb](https://github.com/jasonmacdonald/zenstack/commit/fc50deb6e70acc78dcb66b17e564a6fc84475970))
* add `check` hooks generation to tanstack and swr plugins ([#1422](https://github.com/jasonmacdonald/zenstack/issues/1422)) ([1030770](https://github.com/jasonmacdonald/zenstack/commit/10307700c53bb015423b3125c3cdebe05dbc3821))
* allow to use custom fetch with generated hooks ([#556](https://github.com/jasonmacdonald/zenstack/issues/556)) ([2a6b31a](https://github.com/jasonmacdonald/zenstack/commit/2a6b31a29c71a786a27a0ddda5c64f8c973c7739))
* always use superjson to serialize/deserialize in the api layer ([#585](https://github.com/jasonmacdonald/zenstack/issues/585)) ([46fec66](https://github.com/jasonmacdonald/zenstack/commit/46fec666c3af971010c69e467f08f55830655441))
* improved automatic query invalidation for tanstack-query ([#790](https://github.com/jasonmacdonald/zenstack/issues/790)) ([42d654f](https://github.com/jasonmacdonald/zenstack/commit/42d654fcfaa40b09fde578db79792c69e1e3b908))
* infinite query for swr plugin ([#680](https://github.com/jasonmacdonald/zenstack/issues/680)) ([757ccb5](https://github.com/jasonmacdonald/zenstack/commit/757ccb54cbaecf2274159b83b256cfa46a517f89))
* make parameters of transactions configurable ([#988](https://github.com/jasonmacdonald/zenstack/issues/988)) ([d0745b1](https://github.com/jasonmacdonald/zenstack/commit/d0745b149a5ce6abfef546de0b9243ddc4f6e765))
* optimistic update support for SWR ([#860](https://github.com/jasonmacdonald/zenstack/issues/860)) ([0ca4670](https://github.com/jasonmacdonald/zenstack/commit/0ca46704f4c02b7d3e69470c68601835f426da59))
* support Prisma v5 ([#587](https://github.com/jasonmacdonald/zenstack/issues/587)) ([b0d9154](https://github.com/jasonmacdonald/zenstack/commit/b0d9154270a89c6c93c7a8f1aada85c413d16d6f))


### Bug Fixes

* add "exports" to generated package.json, make trpc code-gen compatible with vite ([#677](https://github.com/jasonmacdonald/zenstack/issues/677)) ([df67f30](https://github.com/jasonmacdonald/zenstack/commit/df67f301119db23e5048464de2f73bff1a2adffc))
* add `CheckSelect` type into code for Prisma version backward compatibility ([#619](https://github.com/jasonmacdonald/zenstack/issues/619)) ([3e09a3a](https://github.com/jasonmacdonald/zenstack/commit/3e09a3a6646ae0f6e393cc0f92991c9b5d0c4d29))
* avoid importing prisma-related code into language server ([#1441](https://github.com/jasonmacdonald/zenstack/issues/1441)) ([b22c6a3](https://github.com/jasonmacdonald/zenstack/commit/b22c6a3ce238ec766d910f23e83aea4e8f10c05d))
* bugs related to model name casing ([#645](https://github.com/jasonmacdonald/zenstack/issues/645)) ([32d5b26](https://github.com/jasonmacdonald/zenstack/commit/32d5b262cacdd03209a56027e4c2cbda1bc408c0))
* build, lint and etc. ([#833](https://github.com/jasonmacdonald/zenstack/issues/833)) ([cccbc3c](https://github.com/jasonmacdonald/zenstack/commit/cccbc3c82ad522d40bc76ad7b84b1305d378b1db))
* change back to loading from literal ".zenstack" path otherwise Vercel breaks :( ([#701](https://github.com/jasonmacdonald/zenstack/issues/701)) ([2d41a9f](https://github.com/jasonmacdonald/zenstack/commit/2d41a9fcffab2fa228356a5cc45b4c2ecd62fd63))
* clean up zod generation ([#883](https://github.com/jasonmacdonald/zenstack/issues/883)) ([909281f](https://github.com/jasonmacdonald/zenstack/commit/909281f8090734322c0cab09d0187b6b5e813c9a))
* clean up zod generation ([#883](https://github.com/jasonmacdonald/zenstack/issues/883)) ([9d4a8ed](https://github.com/jasonmacdonald/zenstack/commit/9d4a8ede7d42d1966fd5a12d64a5992092f4bc7d))
* compatibility with Prisma's "omit" feature ([#1432](https://github.com/jasonmacdonald/zenstack/issues/1432)) ([296ca25](https://github.com/jasonmacdonald/zenstack/commit/296ca259c8dd3e38fa988378df4a9e351a11b20b))
* enhanced client doesn't work with client extensions that add new model methods ([#851](https://github.com/jasonmacdonald/zenstack/issues/851)) ([ea564c9](https://github.com/jasonmacdonald/zenstack/commit/ea564c93e9ca2a888c0e53216633d66c733f6beb))
* generate both cjs and esm builds for swr plugin ([#892](https://github.com/jasonmacdonald/zenstack/issues/892)) ([385839f](https://github.com/jasonmacdonald/zenstack/commit/385839f101941234c5293d70d07e064c1c458387))
* hooks generation emits Provider export for backward compatibility ([#594](https://github.com/jasonmacdonald/zenstack/issues/594)) ([ca3ebda](https://github.com/jasonmacdonald/zenstack/commit/ca3ebdae4e213d3901bb5834fd9ebf1217da94a7))
* improve consistency of generated guard code ([#616](https://github.com/jasonmacdonald/zenstack/issues/616)) ([1b7b5bd](https://github.com/jasonmacdonald/zenstack/commit/1b7b5bda3f5106d31b7f5e70be27158fb8217600))
* incorrect cross-model comparision for && and || expressions ([#1512](https://github.com/jasonmacdonald/zenstack/issues/1512)) ([908048b](https://github.com/jasonmacdonald/zenstack/commit/908048b01430ff6552e8df558d5b5905136ea5cc))
* incorrect relation owner analysis ([#610](https://github.com/jasonmacdonald/zenstack/issues/610)) ([c89012b](https://github.com/jasonmacdonald/zenstack/commit/c89012bcb8d32588cc7f5a1df19088292e571cec))
* incorrect reverse query built for to-many relation ([#815](https://github.com/jasonmacdonald/zenstack/issues/815)) ([2c345e1](https://github.com/jasonmacdonald/zenstack/commit/2c345e1d4fe7274b7a08c1178afccede1d694327))
* infinite recursion when injecting field selection for field-level permission check ([#1452](https://github.com/jasonmacdonald/zenstack/issues/1452)) ([29962e0](https://github.com/jasonmacdonald/zenstack/commit/29962e0b48a73ae6d42f43f2575048ba9cf6a953))
* issue [#627](https://github.com/jasonmacdonald/zenstack/issues/627) ([#628](https://github.com/jasonmacdonald/zenstack/issues/628)) ([2ef93cb](https://github.com/jasonmacdonald/zenstack/commit/2ef93cb932e7aed6923cd3d7e69069d0c9ff161b))
* issue 961, incorrect policy injection for nested `updateMany` ([#962](https://github.com/jasonmacdonald/zenstack/issues/962)) ([2b2bfcf](https://github.com/jasonmacdonald/zenstack/commit/2b2bfcff965f9a70ff2764e6fbc7613b6f061685))
* issues with cross-model comparison identification and injection ([#1508](https://github.com/jasonmacdonald/zenstack/issues/1508)) ([665f9b3](https://github.com/jasonmacdonald/zenstack/commit/665f9b33b58acc5170c4ccb8e73be525fbb89734))
* lint issue in generated swr/tanstack hooks ([#877](https://github.com/jasonmacdonald/zenstack/issues/877)) ([4577232](https://github.com/jasonmacdonald/zenstack/commit/45772326c7980f5338452d4048c43f76a6b09bf0))
* make sure Buffer is imported ([#596](https://github.com/jasonmacdonald/zenstack/issues/596)) ([76a0bac](https://github.com/jasonmacdonald/zenstack/commit/76a0bac9c63707baf34a072e398b63156c1e0640))
* make sure zod schemas have type annotations ([#574](https://github.com/jasonmacdonald/zenstack/issues/574)) ([51985b1](https://github.com/jasonmacdonald/zenstack/commit/51985b1279dca8e82a7275330a7b6597f37d15a4))
* nullify field instead of reject when an optional relation field is not readable ([#588](https://github.com/jasonmacdonald/zenstack/issues/588)) ([fc16008](https://github.com/jasonmacdonald/zenstack/commit/fc16008ba20aba18f39948f3ff13ec3bc79729e3))
* optimize generated trpc typing and fix "select" issue ([#972](https://github.com/jasonmacdonald/zenstack/issues/972)) ([c0d60a0](https://github.com/jasonmacdonald/zenstack/commit/c0d60a00eac9392cb061927126a41a5287467289))
* post-update rules incorrectly reject update ([#826](https://github.com/jasonmacdonald/zenstack/issues/826)) ([d921a7c](https://github.com/jasonmacdonald/zenstack/commit/d921a7ca6bef0341ccf5bc50e195156695129e7f))
* post-update rules incorrectly reject update ([#826](https://github.com/jasonmacdonald/zenstack/issues/826)) ([e85831e](https://github.com/jasonmacdonald/zenstack/commit/e85831e98d08a433febb5a8fecf8d539150ced08))
* properly handle nullable fields in openapi generator ([#906](https://github.com/jasonmacdonald/zenstack/issues/906)) ([0e422ad](https://github.com/jasonmacdonald/zenstack/commit/0e422adf1a7f274b850eeba09ef1781b13ce9f1b))
* **runtime:** always use id fields to address existing entity during upsert ([#1273](https://github.com/jasonmacdonald/zenstack/issues/1273)) ([d8c1513](https://github.com/jasonmacdonald/zenstack/commit/d8c15135a7edb75b459b6f5f1736e5fa2d96a9fa))
* support for custom prisma client output path ([#514](https://github.com/jasonmacdonald/zenstack/issues/514)) ([5f3669e](https://github.com/jasonmacdonald/zenstack/commit/5f3669e53363bbfb035f100d0c6e2d14cef69c24))
* supports for complex usage of "@[@index](https://github.com/index)" in zmodel ([#995](https://github.com/jasonmacdonald/zenstack/issues/995)) ([541cd97](https://github.com/jasonmacdonald/zenstack/commit/541cd973081cbbf2d9e2e571ee8f971bc859150c))
* swr hooks support no revalidation ([#871](https://github.com/jasonmacdonald/zenstack/issues/871)) ([673bdd3](https://github.com/jasonmacdonald/zenstack/commit/673bdd3a4d54db72cdb0561669801b7be633c904))
* **tanstack:** incorrect InfiniteData import for vue-query ([#1498](https://github.com/jasonmacdonald/zenstack/issues/1498)) ([92f187f](https://github.com/jasonmacdonald/zenstack/commit/92f187f9190517df5baca795f12386c12c6694e9))
* vscode language accidentally bundles prisma packages  ([#625](https://github.com/jasonmacdonald/zenstack/issues/625)) ([f6b68da](https://github.com/jasonmacdonald/zenstack/commit/f6b68dabc9e089230bc6d8f8e802e8fbc43a8a69))
* wrong endpoint requested in generated SWR hooks ([#503](https://github.com/jasonmacdonald/zenstack/issues/503)) ([3078e12](https://github.com/jasonmacdonald/zenstack/commit/3078e1292d09b3f4b49bdea4ebbb50504fbc4c1b))
</details>

<details><summary>2.0.0-alpha.4</summary>

## [2.0.0-alpha.4](https://github.com/jasonmacdonald/zenstack/compare/v2.0.0-alpha.3...v2.0.0-alpha.4) (2024-07-10)


### Features

* a better "zod" plugin ([#521](https://github.com/jasonmacdonald/zenstack/issues/521)) ([2280f83](https://github.com/jasonmacdonald/zenstack/commit/2280f83cd7f1f597fddfd6ab0c99417200124452))
* add `check` hooks generation to tanstack and swr plugins ([#1422](https://github.com/jasonmacdonald/zenstack/issues/1422)) ([1030770](https://github.com/jasonmacdonald/zenstack/commit/10307700c53bb015423b3125c3cdebe05dbc3821))
* allow to use custom fetch with generated hooks ([#556](https://github.com/jasonmacdonald/zenstack/issues/556)) ([2a6b31a](https://github.com/jasonmacdonald/zenstack/commit/2a6b31a29c71a786a27a0ddda5c64f8c973c7739))
* always use superjson to serialize/deserialize in the api layer ([#585](https://github.com/jasonmacdonald/zenstack/issues/585)) ([46fec66](https://github.com/jasonmacdonald/zenstack/commit/46fec666c3af971010c69e467f08f55830655441))
* automatic optimistic update for tanstack hooks ([#830](https://github.com/jasonmacdonald/zenstack/issues/830)) ([93dc7df](https://github.com/jasonmacdonald/zenstack/commit/93dc7df472427a4546ba71ec3703135d2d638ded))
* improved automatic query invalidation for tanstack-query ([#790](https://github.com/jasonmacdonald/zenstack/issues/790)) ([42d654f](https://github.com/jasonmacdonald/zenstack/commit/42d654fcfaa40b09fde578db79792c69e1e3b908))
* infinite query support for tanstack-query ([#679](https://github.com/jasonmacdonald/zenstack/issues/679)) ([3300499](https://github.com/jasonmacdonald/zenstack/commit/330049949bfce7e8d463d7be8f1c8653df10203a))
* make parameters of transactions configurable ([#988](https://github.com/jasonmacdonald/zenstack/issues/988)) ([d0745b1](https://github.com/jasonmacdonald/zenstack/commit/d0745b149a5ce6abfef546de0b9243ddc4f6e765))
* Nuxt server adapter and tanstack-query for "vue" hooks generation ([#757](https://github.com/jasonmacdonald/zenstack/issues/757)) ([033d95d](https://github.com/jasonmacdonald/zenstack/commit/033d95dcdeef67bc8183d1daeb3172ec9ee02b9b))
* support Prisma v5 ([#587](https://github.com/jasonmacdonald/zenstack/issues/587)) ([b0d9154](https://github.com/jasonmacdonald/zenstack/commit/b0d9154270a89c6c93c7a8f1aada85c413d16d6f))
* tanstack-query v5 support ([#788](https://github.com/jasonmacdonald/zenstack/issues/788)) ([0d04d8e](https://github.com/jasonmacdonald/zenstack/commit/0d04d8e6dabd66ee06e98971cb4e1007c4ecd466))
* trpc plugin, generate client helpers to provide prisima-like typing ([#510](https://github.com/jasonmacdonald/zenstack/issues/510)) ([c41980d](https://github.com/jasonmacdonald/zenstack/commit/c41980dddbbeacd51c72d109e09a8c7b4c17617c))


### Bug Fixes

* add "exports" to generated package.json, make trpc code-gen compatible with vite ([#677](https://github.com/jasonmacdonald/zenstack/issues/677)) ([df67f30](https://github.com/jasonmacdonald/zenstack/commit/df67f301119db23e5048464de2f73bff1a2adffc))
* add `CheckSelect` type into code for Prisma version backward compatibility ([#619](https://github.com/jasonmacdonald/zenstack/issues/619)) ([3e09a3a](https://github.com/jasonmacdonald/zenstack/commit/3e09a3a6646ae0f6e393cc0f92991c9b5d0c4d29))
* add missing "/runtime" exports to tanstack-query ([#688](https://github.com/jasonmacdonald/zenstack/issues/688)) ([a3064dc](https://github.com/jasonmacdonald/zenstack/commit/a3064dc2ce9319977a01844fd0aac40bb92be7d9))
* add package.json exports ([#597](https://github.com/jasonmacdonald/zenstack/issues/597)) ([8ccfc93](https://github.com/jasonmacdonald/zenstack/commit/8ccfc93ba8135ced89754fbd912a02fe11962a53))
* avoid importing prisma-related code into language server ([#1441](https://github.com/jasonmacdonald/zenstack/issues/1441)) ([b22c6a3](https://github.com/jasonmacdonald/zenstack/commit/b22c6a3ce238ec766d910f23e83aea4e8f10c05d))
* bugs related to model name casing ([#645](https://github.com/jasonmacdonald/zenstack/issues/645)) ([32d5b26](https://github.com/jasonmacdonald/zenstack/commit/32d5b262cacdd03209a56027e4c2cbda1bc408c0))
* build, lint and etc. ([#833](https://github.com/jasonmacdonald/zenstack/issues/833)) ([cccbc3c](https://github.com/jasonmacdonald/zenstack/commit/cccbc3c82ad522d40bc76ad7b84b1305d378b1db))
* change back to loading from literal ".zenstack" path otherwise Vercel breaks :( ([#701](https://github.com/jasonmacdonald/zenstack/issues/701)) ([2d41a9f](https://github.com/jasonmacdonald/zenstack/commit/2d41a9fcffab2fa228356a5cc45b4c2ecd62fd63))
* clean up zod generation ([#883](https://github.com/jasonmacdonald/zenstack/issues/883)) ([909281f](https://github.com/jasonmacdonald/zenstack/commit/909281f8090734322c0cab09d0187b6b5e813c9a))
* clean up zod generation ([#883](https://github.com/jasonmacdonald/zenstack/issues/883)) ([9d4a8ed](https://github.com/jasonmacdonald/zenstack/commit/9d4a8ede7d42d1966fd5a12d64a5992092f4bc7d))
* compatibility with Prisma's "omit" feature ([#1432](https://github.com/jasonmacdonald/zenstack/issues/1432)) ([296ca25](https://github.com/jasonmacdonald/zenstack/commit/296ca259c8dd3e38fa988378df4a9e351a11b20b))
* enhanced client doesn't work with client extensions that add new model methods ([#851](https://github.com/jasonmacdonald/zenstack/issues/851)) ([ea564c9](https://github.com/jasonmacdonald/zenstack/commit/ea564c93e9ca2a888c0e53216633d66c733f6beb))
* generate suspense queries in tanstack-query plugin ([#996](https://github.com/jasonmacdonald/zenstack/issues/996)) ([43eb615](https://github.com/jasonmacdonald/zenstack/commit/43eb61508fbde4431831343566dd637dff7a6d49))
* hooks generation emits Provider export for backward compatibility ([#594](https://github.com/jasonmacdonald/zenstack/issues/594)) ([ca3ebda](https://github.com/jasonmacdonald/zenstack/commit/ca3ebdae4e213d3901bb5834fd9ebf1217da94a7))
* improve consistency of generated guard code ([#616](https://github.com/jasonmacdonald/zenstack/issues/616)) ([1b7b5bd](https://github.com/jasonmacdonald/zenstack/commit/1b7b5bda3f5106d31b7f5e70be27158fb8217600))
* incorrect cross-model comparision for && and || expressions ([#1512](https://github.com/jasonmacdonald/zenstack/issues/1512)) ([908048b](https://github.com/jasonmacdonald/zenstack/commit/908048b01430ff6552e8df558d5b5905136ea5cc))
* incorrect relation owner analysis ([#610](https://github.com/jasonmacdonald/zenstack/issues/610)) ([c89012b](https://github.com/jasonmacdonald/zenstack/commit/c89012bcb8d32588cc7f5a1df19088292e571cec))
* incorrect reverse query built for to-many relation ([#815](https://github.com/jasonmacdonald/zenstack/issues/815)) ([2c345e1](https://github.com/jasonmacdonald/zenstack/commit/2c345e1d4fe7274b7a08c1178afccede1d694327))
* infinite recursion when injecting field selection for field-level permission check ([#1452](https://github.com/jasonmacdonald/zenstack/issues/1452)) ([29962e0](https://github.com/jasonmacdonald/zenstack/commit/29962e0b48a73ae6d42f43f2575048ba9cf6a953))
* issue [#627](https://github.com/jasonmacdonald/zenstack/issues/627) ([#628](https://github.com/jasonmacdonald/zenstack/issues/628)) ([2ef93cb](https://github.com/jasonmacdonald/zenstack/commit/2ef93cb932e7aed6923cd3d7e69069d0c9ff161b))
* issue 961, incorrect policy injection for nested `updateMany` ([#962](https://github.com/jasonmacdonald/zenstack/issues/962)) ([2b2bfcf](https://github.com/jasonmacdonald/zenstack/commit/2b2bfcff965f9a70ff2764e6fbc7613b6f061685))
* issues with cross-model comparison identification and injection ([#1508](https://github.com/jasonmacdonald/zenstack/issues/1508)) ([665f9b3](https://github.com/jasonmacdonald/zenstack/commit/665f9b33b58acc5170c4ccb8e73be525fbb89734))
* lint issue in generated swr/tanstack hooks ([#877](https://github.com/jasonmacdonald/zenstack/issues/877)) ([4577232](https://github.com/jasonmacdonald/zenstack/commit/45772326c7980f5338452d4048c43f76a6b09bf0))
* make sure Buffer is imported ([#596](https://github.com/jasonmacdonald/zenstack/issues/596)) ([76a0bac](https://github.com/jasonmacdonald/zenstack/commit/76a0bac9c63707baf34a072e398b63156c1e0640))
* make sure zod schemas have type annotations ([#574](https://github.com/jasonmacdonald/zenstack/issues/574)) ([51985b1](https://github.com/jasonmacdonald/zenstack/commit/51985b1279dca8e82a7275330a7b6597f37d15a4))
* nullify field instead of reject when an optional relation field is not readable ([#588](https://github.com/jasonmacdonald/zenstack/issues/588)) ([fc16008](https://github.com/jasonmacdonald/zenstack/commit/fc16008ba20aba18f39948f3ff13ec3bc79729e3))
* post-update rules incorrectly reject update ([#826](https://github.com/jasonmacdonald/zenstack/issues/826)) ([d921a7c](https://github.com/jasonmacdonald/zenstack/commit/d921a7ca6bef0341ccf5bc50e195156695129e7f))
* post-update rules incorrectly reject update ([#826](https://github.com/jasonmacdonald/zenstack/issues/826)) ([e85831e](https://github.com/jasonmacdonald/zenstack/commit/e85831e98d08a433febb5a8fecf8d539150ced08))
* properly handle nullable fields in openapi generator ([#906](https://github.com/jasonmacdonald/zenstack/issues/906)) ([0e422ad](https://github.com/jasonmacdonald/zenstack/commit/0e422adf1a7f274b850eeba09ef1781b13ce9f1b))
* **runtime:** always use id fields to address existing entity during upsert ([#1273](https://github.com/jasonmacdonald/zenstack/issues/1273)) ([d8c1513](https://github.com/jasonmacdonald/zenstack/commit/d8c15135a7edb75b459b6f5f1736e5fa2d96a9fa))
* support for custom prisma client output path ([#514](https://github.com/jasonmacdonald/zenstack/issues/514)) ([5f3669e](https://github.com/jasonmacdonald/zenstack/commit/5f3669e53363bbfb035f100d0c6e2d14cef69c24))
* supports for complex usage of "@[@index](https://github.com/index)" in zmodel ([#995](https://github.com/jasonmacdonald/zenstack/issues/995)) ([541cd97](https://github.com/jasonmacdonald/zenstack/commit/541cd973081cbbf2d9e2e571ee8f971bc859150c))
* swr hooks support no revalidation ([#871](https://github.com/jasonmacdonald/zenstack/issues/871)) ([673bdd3](https://github.com/jasonmacdonald/zenstack/commit/673bdd3a4d54db72cdb0561669801b7be633c904))
* tanstack-query build issues and bugs in optimistic update ([#843](https://github.com/jasonmacdonald/zenstack/issues/843)) ([08d317d](https://github.com/jasonmacdonald/zenstack/commit/08d317d150b99fc38b8e5fb56bb4ab27fe1b4470))
* tanstack-query, fix the incorrect query typing when user provides a custom selector ([#967](https://github.com/jasonmacdonald/zenstack/issues/967)) ([cc98e30](https://github.com/jasonmacdonald/zenstack/commit/cc98e306559d7729d96d4ed77cda2815454fbb8f))
* **tanstack:** improve typing of mutation errors ([#1066](https://github.com/jasonmacdonald/zenstack/issues/1066)) ([a01065c](https://github.com/jasonmacdonald/zenstack/commit/a01065c0aa791d6591776b908f3e1e3c4d21424b))
* **tanstack:** incorrect InfiniteData import for vue-query ([#1498](https://github.com/jasonmacdonald/zenstack/issues/1498)) ([92f187f](https://github.com/jasonmacdonald/zenstack/commit/92f187f9190517df5baca795f12386c12c6694e9))
* **tanstack:** incorrect typing for svelte query hooks ([#1492](https://github.com/jasonmacdonald/zenstack/issues/1492)) ([ed5133c](https://github.com/jasonmacdonald/zenstack/commit/ed5133c0e8df96764a765c462863c0f9f3fb5735))
* **tanstack:** infinite query typing issues ([#1480](https://github.com/jasonmacdonald/zenstack/issues/1480)) ([e158372](https://github.com/jasonmacdonald/zenstack/commit/e15837285e6bb6de0bd229d3c81bb5e0e21d9e9f))
* **tanstack:** make sure vue-query hooks' input is reactive ([#1185](https://github.com/jasonmacdonald/zenstack/issues/1185)) ([f259d73](https://github.com/jasonmacdonald/zenstack/commit/f259d733b88b5bb310d49f0af8c3b78e4822c6bb))
* typing generated for options parameter in the hooks method ([#946](https://github.com/jasonmacdonald/zenstack/issues/946)) ([acb23d1](https://github.com/jasonmacdonald/zenstack/commit/acb23d1d1e3f5ff1ce3452971ac7103c6a38326c))
* vscode language accidentally bundles prisma packages  ([#625](https://github.com/jasonmacdonald/zenstack/issues/625)) ([f6b68da](https://github.com/jasonmacdonald/zenstack/commit/f6b68dabc9e089230bc6d8f8e802e8fbc43a8a69))
* vue-query typing issue ([#1009](https://github.com/jasonmacdonald/zenstack/issues/1009)) ([b2e1635](https://github.com/jasonmacdonald/zenstack/commit/b2e1635cb1857afebde286a0c077c0f561d0bbec))
</details>

<details><summary>2.0.0-alpha.4</summary>

## [2.0.0-alpha.4](https://github.com/jasonmacdonald/zenstack/compare/v2.0.0-alpha.3...v2.0.0-alpha.4) (2024-07-10)


### Features

* a better "zod" plugin ([#521](https://github.com/jasonmacdonald/zenstack/issues/521)) ([2280f83](https://github.com/jasonmacdonald/zenstack/commit/2280f83cd7f1f597fddfd6ab0c99417200124452))
* flexible 'createRouter' typings ([#654](https://github.com/jasonmacdonald/zenstack/issues/654)) ([e147412](https://github.com/jasonmacdonald/zenstack/commit/e14741231b37ef1430fa8a02446f5748a76a02d7))
* improved automatic query invalidation for tanstack-query ([#790](https://github.com/jasonmacdonald/zenstack/issues/790)) ([42d654f](https://github.com/jasonmacdonald/zenstack/commit/42d654fcfaa40b09fde578db79792c69e1e3b908))
* make parameters of transactions configurable ([#988](https://github.com/jasonmacdonald/zenstack/issues/988)) ([d0745b1](https://github.com/jasonmacdonald/zenstack/commit/d0745b149a5ce6abfef546de0b9243ddc4f6e765))
* more flexible "createRouter" typings ([#651](https://github.com/jasonmacdonald/zenstack/issues/651)) ([d2bffb6](https://github.com/jasonmacdonald/zenstack/commit/d2bffb62d48a550937ebe3c147f55b6fab55f172))
* support configuring what models to include for zod and trpc plugins ([#747](https://github.com/jasonmacdonald/zenstack/issues/747)) ([a5d15a3](https://github.com/jasonmacdonald/zenstack/commit/a5d15a30e7a22a3e875cc974391feb9ad6da7646))
* support Prisma v5 ([#587](https://github.com/jasonmacdonald/zenstack/issues/587)) ([b0d9154](https://github.com/jasonmacdonald/zenstack/commit/b0d9154270a89c6c93c7a8f1aada85c413d16d6f))
* trpc plugin, add "generateModelActions" option to control what operations to generate ([#482](https://github.com/jasonmacdonald/zenstack/issues/482)) ([8693852](https://github.com/jasonmacdonald/zenstack/commit/8693852a36522baf44ff7eb3a8c76d839c8a8081))
* trpc plugin, generate client helpers to provide prisima-like typing ([#510](https://github.com/jasonmacdonald/zenstack/issues/510)) ([c41980d](https://github.com/jasonmacdonald/zenstack/commit/c41980dddbbeacd51c72d109e09a8c7b4c17617c))


### Bug Fixes

* add "exports" to generated package.json, make trpc code-gen compatible with vite ([#677](https://github.com/jasonmacdonald/zenstack/issues/677)) ([df67f30](https://github.com/jasonmacdonald/zenstack/commit/df67f301119db23e5048464de2f73bff1a2adffc))
* add `CheckSelect` type into code for Prisma version backward compatibility ([#619](https://github.com/jasonmacdonald/zenstack/issues/619)) ([3e09a3a](https://github.com/jasonmacdonald/zenstack/commit/3e09a3a6646ae0f6e393cc0f92991c9b5d0c4d29))
* add eslint ignore to generated trpc helper source ([#759](https://github.com/jasonmacdonald/zenstack/issues/759)) ([f7e8a08](https://github.com/jasonmacdonald/zenstack/commit/f7e8a08987da4f6af3ad5058209cdc22720dce8f))
* add the missing "count" schema/router for zod/trpc ([#667](https://github.com/jasonmacdonald/zenstack/issues/667)) ([6e9a3b3](https://github.com/jasonmacdonald/zenstack/commit/6e9a3b3ce4f306716234a9598e4aac3c89e1e0be))
* avoid importing prisma-related code into language server ([#1441](https://github.com/jasonmacdonald/zenstack/issues/1441)) ([b22c6a3](https://github.com/jasonmacdonald/zenstack/commit/b22c6a3ce238ec766d910f23e83aea4e8f10c05d))
* bugs related to model name casing ([#645](https://github.com/jasonmacdonald/zenstack/issues/645)) ([32d5b26](https://github.com/jasonmacdonald/zenstack/commit/32d5b262cacdd03209a56027e4c2cbda1bc408c0))
* build, lint and etc. ([#833](https://github.com/jasonmacdonald/zenstack/issues/833)) ([cccbc3c](https://github.com/jasonmacdonald/zenstack/commit/cccbc3c82ad522d40bc76ad7b84b1305d378b1db))
* change back to loading from literal ".zenstack" path otherwise Vercel breaks :( ([#701](https://github.com/jasonmacdonald/zenstack/issues/701)) ([2d41a9f](https://github.com/jasonmacdonald/zenstack/commit/2d41a9fcffab2fa228356a5cc45b4c2ecd62fd63))
* clean up zod generation ([#883](https://github.com/jasonmacdonald/zenstack/issues/883)) ([909281f](https://github.com/jasonmacdonald/zenstack/commit/909281f8090734322c0cab09d0187b6b5e813c9a))
* clean up zod generation ([#883](https://github.com/jasonmacdonald/zenstack/issues/883)) ([9d4a8ed](https://github.com/jasonmacdonald/zenstack/commit/9d4a8ede7d42d1966fd5a12d64a5992092f4bc7d))
* compatibility with Prisma's "omit" feature ([#1432](https://github.com/jasonmacdonald/zenstack/issues/1432)) ([296ca25](https://github.com/jasonmacdonald/zenstack/commit/296ca259c8dd3e38fa988378df4a9e351a11b20b))
* enhanced client doesn't work with client extensions that add new model methods ([#851](https://github.com/jasonmacdonald/zenstack/issues/851)) ([ea564c9](https://github.com/jasonmacdonald/zenstack/commit/ea564c93e9ca2a888c0e53216633d66c733f6beb))
* hooks generation emits Provider export for backward compatibility ([#594](https://github.com/jasonmacdonald/zenstack/issues/594)) ([ca3ebda](https://github.com/jasonmacdonald/zenstack/commit/ca3ebdae4e213d3901bb5834fd9ebf1217da94a7))
* improve consistency of generated guard code ([#616](https://github.com/jasonmacdonald/zenstack/issues/616)) ([1b7b5bd](https://github.com/jasonmacdonald/zenstack/commit/1b7b5bda3f5106d31b7f5e70be27158fb8217600))
* incorrect cross-model comparision for && and || expressions ([#1512](https://github.com/jasonmacdonald/zenstack/issues/1512)) ([908048b](https://github.com/jasonmacdonald/zenstack/commit/908048b01430ff6552e8df558d5b5905136ea5cc))
* incorrect relation owner analysis ([#610](https://github.com/jasonmacdonald/zenstack/issues/610)) ([c89012b](https://github.com/jasonmacdonald/zenstack/commit/c89012bcb8d32588cc7f5a1df19088292e571cec))
* incorrect reverse query built for to-many relation ([#815](https://github.com/jasonmacdonald/zenstack/issues/815)) ([2c345e1](https://github.com/jasonmacdonald/zenstack/commit/2c345e1d4fe7274b7a08c1178afccede1d694327))
* infinite recursion when injecting field selection for field-level permission check ([#1452](https://github.com/jasonmacdonald/zenstack/issues/1452)) ([29962e0](https://github.com/jasonmacdonald/zenstack/commit/29962e0b48a73ae6d42f43f2575048ba9cf6a953))
* issue [#627](https://github.com/jasonmacdonald/zenstack/issues/627) ([#628](https://github.com/jasonmacdonald/zenstack/issues/628)) ([2ef93cb](https://github.com/jasonmacdonald/zenstack/commit/2ef93cb932e7aed6923cd3d7e69069d0c9ff161b))
* issue 961, incorrect policy injection for nested `updateMany` ([#962](https://github.com/jasonmacdonald/zenstack/issues/962)) ([2b2bfcf](https://github.com/jasonmacdonald/zenstack/commit/2b2bfcff965f9a70ff2764e6fbc7613b6f061685))
* issue with client typing generation in trpc plugin ([#673](https://github.com/jasonmacdonald/zenstack/issues/673)) ([576c4f7](https://github.com/jasonmacdonald/zenstack/commit/576c4f7a4858dfa2dcb9c1a7f75af8d1ca48a8ce))
* issues with cross-model comparison identification and injection ([#1508](https://github.com/jasonmacdonald/zenstack/issues/1508)) ([665f9b3](https://github.com/jasonmacdonald/zenstack/commit/665f9b33b58acc5170c4ccb8e73be525fbb89734))
* make sure Buffer is imported ([#596](https://github.com/jasonmacdonald/zenstack/issues/596)) ([76a0bac](https://github.com/jasonmacdonald/zenstack/commit/76a0bac9c63707baf34a072e398b63156c1e0640))
* make sure zod schemas have type annotations ([#574](https://github.com/jasonmacdonald/zenstack/issues/574)) ([51985b1](https://github.com/jasonmacdonald/zenstack/commit/51985b1279dca8e82a7275330a7b6597f37d15a4))
* nullify field instead of reject when an optional relation field is not readable ([#588](https://github.com/jasonmacdonald/zenstack/issues/588)) ([fc16008](https://github.com/jasonmacdonald/zenstack/commit/fc16008ba20aba18f39948f3ff13ec3bc79729e3))
* optimize generated trpc typing and fix "select" issue ([#972](https://github.com/jasonmacdonald/zenstack/issues/972)) ([c0d60a0](https://github.com/jasonmacdonald/zenstack/commit/c0d60a00eac9392cb061927126a41a5287467289))
* policy compilation error for deeply nested post-update rules ([#1382](https://github.com/jasonmacdonald/zenstack/issues/1382)) ([08471d5](https://github.com/jasonmacdonald/zenstack/commit/08471d5e0932bf696e8b6929c4490f191710060d))
* post-update rule for id field is not effective if id is updated ([#1237](https://github.com/jasonmacdonald/zenstack/issues/1237)) ([5fe85ff](https://github.com/jasonmacdonald/zenstack/commit/5fe85ffa50d012c65db542602448d5522b71ef9b))
* post-update rules incorrectly reject update ([#826](https://github.com/jasonmacdonald/zenstack/issues/826)) ([d921a7c](https://github.com/jasonmacdonald/zenstack/commit/d921a7ca6bef0341ccf5bc50e195156695129e7f))
* post-update rules incorrectly reject update ([#826](https://github.com/jasonmacdonald/zenstack/issues/826)) ([e85831e](https://github.com/jasonmacdonald/zenstack/commit/e85831e98d08a433febb5a8fecf8d539150ced08))
* properly handle nullable fields in openapi generator ([#906](https://github.com/jasonmacdonald/zenstack/issues/906)) ([0e422ad](https://github.com/jasonmacdonald/zenstack/commit/0e422adf1a7f274b850eeba09ef1781b13ce9f1b))
* support for custom prisma client output path ([#514](https://github.com/jasonmacdonald/zenstack/issues/514)) ([5f3669e](https://github.com/jasonmacdonald/zenstack/commit/5f3669e53363bbfb035f100d0c6e2d14cef69c24))
* supports for complex usage of "@[@index](https://github.com/index)" in zmodel ([#995](https://github.com/jasonmacdonald/zenstack/issues/995)) ([541cd97](https://github.com/jasonmacdonald/zenstack/commit/541cd973081cbbf2d9e2e571ee8f971bc859150c))
* **tanstack:** improve typing of mutation errors ([#1066](https://github.com/jasonmacdonald/zenstack/issues/1066)) ([a01065c](https://github.com/jasonmacdonald/zenstack/commit/a01065c0aa791d6591776b908f3e1e3c4d21424b))
* **tanstack:** incorrect InfiniteData import for vue-query ([#1498](https://github.com/jasonmacdonald/zenstack/issues/1498)) ([92f187f](https://github.com/jasonmacdonald/zenstack/commit/92f187f9190517df5baca795f12386c12c6694e9))
* trpc client helper bugs ([#532](https://github.com/jasonmacdonald/zenstack/issues/532)) ([4097915](https://github.com/jasonmacdonald/zenstack/commit/40979154c88d31d3891c361caf4ab16a4888b178))
* trpc plugin, generate schema for supporting unchecked input in mutation routes ([#512](https://github.com/jasonmacdonald/zenstack/issues/512)) ([304979f](https://github.com/jasonmacdonald/zenstack/commit/304979f4847258eff8b04675bc3e199ac0857173))
* **trpc:** make sure "import type" is used for type-only imports ([#1425](https://github.com/jasonmacdonald/zenstack/issues/1425)) ([3b38311](https://github.com/jasonmacdonald/zenstack/commit/3b38311e049761c226791224afab07fae21edd1f))
* **trpc:** temp workaround for Node.js importing from CJS module issue ([#1436](https://github.com/jasonmacdonald/zenstack/issues/1436)) ([d2709f6](https://github.com/jasonmacdonald/zenstack/commit/d2709f6a597c91015985188d435d26c799d514d1))
* vscode language accidentally bundles prisma packages  ([#625](https://github.com/jasonmacdonald/zenstack/issues/625)) ([f6b68da](https://github.com/jasonmacdonald/zenstack/commit/f6b68dabc9e089230bc6d8f8e802e8fbc43a8a69))
</details>

<details><summary>2.0.0-alpha.4</summary>

## [2.0.0-alpha.4](https://github.com/jasonmacdonald/zenstack/compare/v2.0.0-alpha.3...v2.0.0-alpha.4) (2024-07-10)


### Features

* a better "zod" plugin ([#521](https://github.com/jasonmacdonald/zenstack/issues/521)) ([2280f83](https://github.com/jasonmacdonald/zenstack/commit/2280f83cd7f1f597fddfd6ab0c99417200124452))
* add "loadPath" options to runtime API and server adapter options ([#696](https://github.com/jasonmacdonald/zenstack/issues/696)) ([fc50deb](https://github.com/jasonmacdonald/zenstack/commit/fc50deb6e70acc78dcb66b17e564a6fc84475970))
* add support for comparing fields in the same model ([#631](https://github.com/jasonmacdonald/zenstack/issues/631)) ([4776685](https://github.com/jasonmacdonald/zenstack/commit/477668579e3d95e7371ca752244ad2e319a96477))
* allow comparing fields from different models in mutation policies ([#1476](https://github.com/jasonmacdonald/zenstack/issues/1476)) ([6610bd0](https://github.com/jasonmacdonald/zenstack/commit/6610bd09f8d43b62b073044bb60a8a3cc40ef9e2))
* allow to pass in a custom `Prisma` module when calling `enhance` ([#1160](https://github.com/jasonmacdonald/zenstack/issues/1160)) ([018d59f](https://github.com/jasonmacdonald/zenstack/commit/018d59f58295cee4530b9650c49dc868251029dd))
* always use superjson to serialize/deserialize in the api layer ([#585](https://github.com/jasonmacdonald/zenstack/issues/585)) ([46fec66](https://github.com/jasonmacdonald/zenstack/commit/46fec666c3af971010c69e467f08f55830655441))
* automatic optimistic update for tanstack hooks ([#830](https://github.com/jasonmacdonald/zenstack/issues/830)) ([93dc7df](https://github.com/jasonmacdonald/zenstack/commit/93dc7df472427a4546ba71ec3703135d2d638ded))
* field-level access control ([#638](https://github.com/jasonmacdonald/zenstack/issues/638)) ([9a6f39b](https://github.com/jasonmacdonald/zenstack/commit/9a6f39bdb8940f7cef89fd7ee423658b8ed4c49f))
* field-level policy override ([#889](https://github.com/jasonmacdonald/zenstack/issues/889)) ([271d568](https://github.com/jasonmacdonald/zenstack/commit/271d568ad3695e85f216ad7a293d9b9e802e7aaa))
* fluent API support ([#666](https://github.com/jasonmacdonald/zenstack/issues/666)) ([4ae5a96](https://github.com/jasonmacdonald/zenstack/commit/4ae5a96ee2976dedbdb0b207f48c082c48b3f9ce))
* implementing access control for Prisma Pulse ([#643](https://github.com/jasonmacdonald/zenstack/issues/643)) ([d8c2e87](https://github.com/jasonmacdonald/zenstack/commit/d8c2e8717e5fd3facb177443c8ef1baec89a81d5))
* implementing permission checker ([#1411](https://github.com/jasonmacdonald/zenstack/issues/1411)) ([0aa6ee9](https://github.com/jasonmacdonald/zenstack/commit/0aa6ee961bab005705287184b670ae9a3a57f06d))
* improved automatic query invalidation for tanstack-query ([#790](https://github.com/jasonmacdonald/zenstack/issues/790)) ([42d654f](https://github.com/jasonmacdonald/zenstack/commit/42d654fcfaa40b09fde578db79792c69e1e3b908))
* include raw zod errors in response ([#691](https://github.com/jasonmacdonald/zenstack/issues/691)) ([b5da998](https://github.com/jasonmacdonald/zenstack/commit/b5da998b7fa11c19b85cebd0956803d854332b4d))
* make parameters of transactions configurable ([#988](https://github.com/jasonmacdonald/zenstack/issues/988)) ([d0745b1](https://github.com/jasonmacdonald/zenstack/commit/d0745b149a5ce6abfef546de0b9243ddc4f6e765))
* optimistic update support for SWR ([#860](https://github.com/jasonmacdonald/zenstack/issues/860)) ([0ca4670](https://github.com/jasonmacdonald/zenstack/commit/0ca46704f4c02b7d3e69470c68601835f426da59))
* options for logging queries sent to prisma ([#488](https://github.com/jasonmacdonald/zenstack/issues/488)) ([ccfb2b0](https://github.com/jasonmacdonald/zenstack/commit/ccfb2b088cf1ce14c78c1d1355db5cb4ebcdc957))
* RedwoodJS integration package ([#911](https://github.com/jasonmacdonald/zenstack/issues/911)) ([e4aeee3](https://github.com/jasonmacdonald/zenstack/commit/e4aeee32ae3a5ab1718fd1daa2f93043fb68a8d5))
* runtime support for custom `@[@auth](https://github.com/auth)` model ([#793](https://github.com/jasonmacdonald/zenstack/issues/793)) ([08b9677](https://github.com/jasonmacdonald/zenstack/commit/08b967735c938de1e770a2409c36c5a50173b01d))
* **runtime:** support for Prisma 5.14's `createManyAndReturn` ([#1479](https://github.com/jasonmacdonald/zenstack/issues/1479)) ([a783800](https://github.com/jasonmacdonald/zenstack/commit/a7838000ba509db6191c7ed93329eaaa02325692))
* support Prisma v5 ([#587](https://github.com/jasonmacdonald/zenstack/issues/587)) ([b0d9154](https://github.com/jasonmacdonald/zenstack/commit/b0d9154270a89c6c93c7a8f1aada85c413d16d6f))
* support using collection predicate expression with `auth()` ([#831](https://github.com/jasonmacdonald/zenstack/issues/831)) ([ff1e8a5](https://github.com/jasonmacdonald/zenstack/commit/ff1e8a5e98ec94337f08576a29ffbee07ba8fd88))


### Bug Fixes

* [@omit](https://github.com/omit) doesn't remove fields inside to-many relation ([#993](https://github.com/jasonmacdonald/zenstack/issues/993)) ([a4d3f15](https://github.com/jasonmacdonald/zenstack/commit/a4d3f15746269257bc7fb56332766e3f598e2996))
* add "exports" to generated package.json, make trpc code-gen compatible with vite ([#677](https://github.com/jasonmacdonald/zenstack/issues/677)) ([df67f30](https://github.com/jasonmacdonald/zenstack/commit/df67f301119db23e5048464de2f73bff1a2adffc))
* add `CheckSelect` type into code for Prisma version backward compatibility ([#619](https://github.com/jasonmacdonald/zenstack/issues/619)) ([3e09a3a](https://github.com/jasonmacdonald/zenstack/commit/3e09a3a6646ae0f6e393cc0f92991c9b5d0c4d29))
* add missing auth export ([#1449](https://github.com/jasonmacdonald/zenstack/issues/1449)) ([81a2adf](https://github.com/jasonmacdonald/zenstack/commit/81a2adfe43c958ffe1645d24bcfb119a3daf8edd))
* add package.json exports ([#597](https://github.com/jasonmacdonald/zenstack/issues/597)) ([8ccfc93](https://github.com/jasonmacdonald/zenstack/commit/8ccfc93ba8135ced89754fbd912a02fe11962a53))
* additional fixes for unique constraint conflict detection ([#1165](https://github.com/jasonmacdonald/zenstack/issues/1165)) ([9f89c7e](https://github.com/jasonmacdonald/zenstack/commit/9f89c7ea76adfa73406843e3c2f222ea0bfcb969))
* avoid return loaded prisma if undefined ([#461](https://github.com/jasonmacdonald/zenstack/issues/461)) ([cfca402](https://github.com/jasonmacdonald/zenstack/commit/cfca4022dcb79ccab47d7a5fe8bb8b5c9521295e))
* bug in enhancement proxy for detecting nested transactions ([#941](https://github.com/jasonmacdonald/zenstack/issues/941)) ([85a0525](https://github.com/jasonmacdonald/zenstack/commit/85a052594c447120ecc8123d30c7b098afcc8841))
* bug with NOT clause reduction when condition is an array ([#848](https://github.com/jasonmacdonald/zenstack/issues/848)) ([debd35b](https://github.com/jasonmacdonald/zenstack/commit/debd35b3531262c4df453653cbee10dc85baf222))
* bugs related to model name casing ([#645](https://github.com/jasonmacdonald/zenstack/issues/645)) ([32d5b26](https://github.com/jasonmacdonald/zenstack/commit/32d5b262cacdd03209a56027e4c2cbda1bc408c0))
* build, lint and etc. ([#833](https://github.com/jasonmacdonald/zenstack/issues/833)) ([cccbc3c](https://github.com/jasonmacdonald/zenstack/commit/cccbc3c82ad522d40bc76ad7b84b1305d378b1db))
* change back to loading from literal ".zenstack" path otherwise Vercel breaks :( ([#701](https://github.com/jasonmacdonald/zenstack/issues/701)) ([2d41a9f](https://github.com/jasonmacdonald/zenstack/commit/2d41a9fcffab2fa228356a5cc45b4c2ecd62fd63))
* clean up zod generation ([#883](https://github.com/jasonmacdonald/zenstack/issues/883)) ([909281f](https://github.com/jasonmacdonald/zenstack/commit/909281f8090734322c0cab09d0187b6b5e813c9a))
* clean up zod generation ([#883](https://github.com/jasonmacdonald/zenstack/issues/883)) ([9d4a8ed](https://github.com/jasonmacdonald/zenstack/commit/9d4a8ede7d42d1966fd5a12d64a5992092f4bc7d))
* compatibility with Prisma's "omit" feature ([#1432](https://github.com/jasonmacdonald/zenstack/issues/1432)) ([296ca25](https://github.com/jasonmacdonald/zenstack/commit/296ca259c8dd3e38fa988378df4a9e351a11b20b))
* conditions hoisted from nested read overwrites toplevel where conditions ([#635](https://github.com/jasonmacdonald/zenstack/issues/635)) ([9a35f88](https://github.com/jasonmacdonald/zenstack/commit/9a35f88c059ff4e616d1f54b1e0e01c3c5ce6e19))
* deal with payload field value with undefined ([#778](https://github.com/jasonmacdonald/zenstack/issues/778)) ([e41fc74](https://github.com/jasonmacdonald/zenstack/commit/e41fc747c5a8389d820820c5f8fd95ee13717160))
* **delegate:** avoid merging into object of Decimal, Date, etc. ([#1489](https://github.com/jasonmacdonald/zenstack/issues/1489)) ([ab9d27f](https://github.com/jasonmacdonald/zenstack/commit/ab9d27f669388764139eb42caeef1bb9f19c7524))
* **delegate:** fields from delegate models used in logical groups inside filter are not translated ([#1418](https://github.com/jasonmacdonald/zenstack/issues/1418)) ([1243422](https://github.com/jasonmacdonald/zenstack/commit/12434220a5328ec3885a35f7fc1481788fc536e2))
* **delegate:** make sure concrete fields are included when a polymorphic model field is included in deep nesting ([#1524](https://github.com/jasonmacdonald/zenstack/issues/1524)) ([b34531d](https://github.com/jasonmacdonald/zenstack/commit/b34531dcd47b875aae083d1a820aa896f3766c8b))
* **delegate:** make sure nested `createMany` is converted into regular `create` ([#1526](https://github.com/jasonmacdonald/zenstack/issues/1526)) ([3e77974](https://github.com/jasonmacdonald/zenstack/commit/3e77974c74cb33496d9568fa1d95727449e18522))
* **delegate:** null reference when reading an optional relation ([#1491](https://github.com/jasonmacdonald/zenstack/issues/1491)) ([41880f3](https://github.com/jasonmacdonald/zenstack/commit/41880f38d2ee71545aa2ce9f2e6ac8f5575c717d))
* **delegate:** push base-level id assignment to base payload when creating a concrete entity ([#1521](https://github.com/jasonmacdonald/zenstack/issues/1521)) ([a14bf29](https://github.com/jasonmacdonald/zenstack/commit/a14bf29de4d903c0a226a1604991dd760cbf8614))
* enhanced client doesn't work with client extensions that add new model methods ([7dec167](https://github.com/jasonmacdonald/zenstack/commit/7dec167b8c3bb03c3cae57e6566b223bfce57cca))
* enhanced client doesn't work with client extensions that add new model methods ([#851](https://github.com/jasonmacdonald/zenstack/issues/851)) ([ea564c9](https://github.com/jasonmacdonald/zenstack/commit/ea564c93e9ca2a888c0e53216633d66c733f6beb))
* fix the incorrect query args reduction when there're mixed boolean operators ([#690](https://github.com/jasonmacdonald/zenstack/issues/690)) ([c0c5a16](https://github.com/jasonmacdonald/zenstack/commit/c0c5a164c50c15c8d1982f331cbcac4eae5138b7))
* handle foreign key field-level access check during relation update ([#847](https://github.com/jasonmacdonald/zenstack/issues/847)) ([3c8cba7](https://github.com/jasonmacdonald/zenstack/commit/3c8cba71b283d6029087971fc3b160892d0d143e))
* hooks generation emits Provider export for backward compatibility ([#594](https://github.com/jasonmacdonald/zenstack/issues/594)) ([ca3ebda](https://github.com/jasonmacdonald/zenstack/commit/ca3ebdae4e213d3901bb5834fd9ebf1217da94a7))
* improve consistency of generated guard code ([#616](https://github.com/jasonmacdonald/zenstack/issues/616)) ([1b7b5bd](https://github.com/jasonmacdonald/zenstack/commit/1b7b5bda3f5106d31b7f5e70be27158fb8217600))
* improve error messages ([#502](https://github.com/jasonmacdonald/zenstack/issues/502)) ([c8e5724](https://github.com/jasonmacdonald/zenstack/commit/c8e572449b3ff464da0cb071cda40b9d27f8de53))
* improve stacktrace of errors generated by proxied Prisma methods ([#484](https://github.com/jasonmacdonald/zenstack/issues/484)) ([1b67eba](https://github.com/jasonmacdonald/zenstack/commit/1b67ebadb89c5c443eacb9cf0be9ad56dbc42de4))
* incorrect cross-model comparision for && and || expressions ([#1512](https://github.com/jasonmacdonald/zenstack/issues/1512)) ([908048b](https://github.com/jasonmacdonald/zenstack/commit/908048b01430ff6552e8df558d5b5905136ea5cc))
* incorrect policy injection for nested to-one relation inside a to-many parent ([#777](https://github.com/jasonmacdonald/zenstack/issues/777)) ([876e013](https://github.com/jasonmacdonald/zenstack/commit/876e01392112ed369cde37cb77ca983126f2d881))
* incorrect relation owner analysis ([#610](https://github.com/jasonmacdonald/zenstack/issues/610)) ([c89012b](https://github.com/jasonmacdonald/zenstack/commit/c89012bcb8d32588cc7f5a1df19088292e571cec))
* incorrect reverse query built for to-many relation ([d2ad3a5](https://github.com/jasonmacdonald/zenstack/commit/d2ad3a59f93a74189c29d3ee2960fc887b14851c))
* incorrect reverse query built for to-many relation ([#815](https://github.com/jasonmacdonald/zenstack/issues/815)) ([2c345e1](https://github.com/jasonmacdonald/zenstack/commit/2c345e1d4fe7274b7a08c1178afccede1d694327))
* infinite recursion when injecting field selection for field-level permission check ([#1452](https://github.com/jasonmacdonald/zenstack/issues/1452)) ([29962e0](https://github.com/jasonmacdonald/zenstack/commit/29962e0b48a73ae6d42f43f2575048ba9cf6a953))
* invalid query sent to Prisma when doing nested update with multi-id ([#553](https://github.com/jasonmacdonald/zenstack/issues/553)) ([24760be](https://github.com/jasonmacdonald/zenstack/commit/24760be0f6286089c58df893ec1ae9c192ba17e2))
* issue [#627](https://github.com/jasonmacdonald/zenstack/issues/627) ([#628](https://github.com/jasonmacdonald/zenstack/issues/628)) ([2ef93cb](https://github.com/jasonmacdonald/zenstack/commit/2ef93cb932e7aed6923cd3d7e69069d0c9ff161b))
* issue 599, throw error if the given user context doesn't contain full id fields ([#629](https://github.com/jasonmacdonald/zenstack/issues/629)) ([4bc72a8](https://github.com/jasonmacdonald/zenstack/commit/4bc72a8b93558059a80dc465dc408da33b0adba3))
* issue 961, incorrect policy injection for nested `updateMany` ([bf690a0](https://github.com/jasonmacdonald/zenstack/commit/bf690a072771ab95907a8f56079c4f6aaf655849))
* issue 961, incorrect policy injection for nested `updateMany` ([#962](https://github.com/jasonmacdonald/zenstack/issues/962)) ([2b2bfcf](https://github.com/jasonmacdonald/zenstack/commit/2b2bfcff965f9a70ff2764e6fbc7613b6f061685))
* issues with cross-model comparison identification and injection ([#1508](https://github.com/jasonmacdonald/zenstack/issues/1508)) ([665f9b3](https://github.com/jasonmacdonald/zenstack/commit/665f9b33b58acc5170c4ccb8e73be525fbb89734))
* make sure Buffer is imported ([#596](https://github.com/jasonmacdonald/zenstack/issues/596)) ([76a0bac](https://github.com/jasonmacdonald/zenstack/commit/76a0bac9c63707baf34a072e398b63156c1e0640))
* make sure zod schemas have type annotations ([#574](https://github.com/jasonmacdonald/zenstack/issues/574)) ([51985b1](https://github.com/jasonmacdonald/zenstack/commit/51985b1279dca8e82a7275330a7b6597f37d15a4))
* nested `createMany` with `skipDuplicates` option is not handled correctly ([#1163](https://github.com/jasonmacdonald/zenstack/issues/1163)) ([fef6e83](https://github.com/jasonmacdonald/zenstack/commit/fef6e83a36f451f671ac2b7db1bc06e2e29faf43))
* nullify field instead of reject when an optional relation field is not readable ([#588](https://github.com/jasonmacdonald/zenstack/issues/588)) ([fc16008](https://github.com/jasonmacdonald/zenstack/commit/fc16008ba20aba18f39948f3ff13ec3bc79729e3))
* optimize the way how generated packages are loaded in test environment ([#549](https://github.com/jasonmacdonald/zenstack/issues/549)) ([18267f6](https://github.com/jasonmacdonald/zenstack/commit/18267f6377a926cc332bedab6cf74e8a9b9f2343))
* policy generation error when field-level rules contain "this" expression ([#670](https://github.com/jasonmacdonald/zenstack/issues/670)) ([dc106a9](https://github.com/jasonmacdonald/zenstack/commit/dc106a905f732c90c70f7622df5a1207b442e1ff))
* **policy:** properly handle array-form of upsert payload ([#1101](https://github.com/jasonmacdonald/zenstack/issues/1101)) ([e7e1873](https://github.com/jasonmacdonald/zenstack/commit/e7e1873744ac2d48e118ae48b23e10723d16db44))
* **policy:** relation filter should respect field-level policies ([#1495](https://github.com/jasonmacdonald/zenstack/issues/1495)) ([54e1e02](https://github.com/jasonmacdonald/zenstack/commit/54e1e02839c4f010e21fa50c48289f872d8ae0eb))
* post-update rule for id field is not effective if id is updated ([#1237](https://github.com/jasonmacdonald/zenstack/issues/1237)) ([5fe85ff](https://github.com/jasonmacdonald/zenstack/commit/5fe85ffa50d012c65db542602448d5522b71ef9b))
* post-update rules incorrectly reject update ([#826](https://github.com/jasonmacdonald/zenstack/issues/826)) ([d921a7c](https://github.com/jasonmacdonald/zenstack/commit/d921a7ca6bef0341ccf5bc50e195156695129e7f))
* post-update rules incorrectly reject update ([#826](https://github.com/jasonmacdonald/zenstack/issues/826)) ([e85831e](https://github.com/jasonmacdonald/zenstack/commit/e85831e98d08a433febb5a8fecf8d539150ced08))
* query injection error when create (in array form) is nested inside an update ([#865](https://github.com/jasonmacdonald/zenstack/issues/865)) ([ca55bf6](https://github.com/jasonmacdonald/zenstack/commit/ca55bf61edff7a67765cd8a9eac2b97daaf33506))
* relation fields are included even if they are set `false` in select clause ([#1429](https://github.com/jasonmacdonald/zenstack/issues/1429)) ([6a71742](https://github.com/jasonmacdonald/zenstack/commit/6a717428d3d0176eb3651b488fe0660895dab14d))
* require with default ([#546](https://github.com/jasonmacdonald/zenstack/issues/546)) ([1e9fe1c](https://github.com/jasonmacdonald/zenstack/commit/1e9fe1cfcf50b691bf788021b8a460b1f3ecb29e))
* **runtime:** always use id fields to address existing entity during upsert ([#1273](https://github.com/jasonmacdonald/zenstack/issues/1273)) ([d8c1513](https://github.com/jasonmacdonald/zenstack/commit/d8c15135a7edb75b459b6f5f1736e5fa2d96a9fa))
* should not reject "update" when there's only field-level override but no model-level policy ([#1052](https://github.com/jasonmacdonald/zenstack/issues/1052)) ([912c831](https://github.com/jasonmacdonald/zenstack/commit/912c83176a57ae2e2397c0aab68c0299a6115025))
* supports for complex usage of "@[@index](https://github.com/index)" in zmodel ([#995](https://github.com/jasonmacdonald/zenstack/issues/995)) ([541cd97](https://github.com/jasonmacdonald/zenstack/commit/541cd973081cbbf2d9e2e571ee8f971bc859150c))
* tanstack-query build issues and bugs in optimistic update ([#843](https://github.com/jasonmacdonald/zenstack/issues/843)) ([08d317d](https://github.com/jasonmacdonald/zenstack/commit/08d317d150b99fc38b8e5fb56bb4ab27fe1b4470))
* **tanstack:** incorrect InfiniteData import for vue-query ([#1498](https://github.com/jasonmacdonald/zenstack/issues/1498)) ([92f187f](https://github.com/jasonmacdonald/zenstack/commit/92f187f9190517df5baca795f12386c12c6694e9))
* typing of policy definition ([#640](https://github.com/jasonmacdonald/zenstack/issues/640)) ([acd0753](https://github.com/jasonmacdonald/zenstack/commit/acd075392a2237e12ef88a55f13de701e172f57d))
* update rule check for connect with implicit many-to-many relation ([#565](https://github.com/jasonmacdonald/zenstack/issues/565)) ([ffdad27](https://github.com/jasonmacdonald/zenstack/commit/ffdad2713e71071b53ac3fd13b82b38673d7b6f6))
* use zod parse result data as mutation input ([#997](https://github.com/jasonmacdonald/zenstack/issues/997)) ([613ac8d](https://github.com/jasonmacdonald/zenstack/commit/613ac8d2cd638272bcc7b24e0fb96e60c0d43acc))
* validate zod schema before update operation is executed ([#1051](https://github.com/jasonmacdonald/zenstack/issues/1051)) ([9db52db](https://github.com/jasonmacdonald/zenstack/commit/9db52dbb77650d7c99380308803b7b4b4b7ae42d))
* vscode language accidentally bundles prisma packages  ([#625](https://github.com/jasonmacdonald/zenstack/issues/625)) ([f6b68da](https://github.com/jasonmacdonald/zenstack/commit/f6b68dabc9e089230bc6d8f8e802e8fbc43a8a69))
* when field policy only has deny rule, access should be allowed when the rule doesn't satisfy ([#818](https://github.com/jasonmacdonald/zenstack/issues/818)) ([62a8200](https://github.com/jasonmacdonald/zenstack/commit/62a82001cde1c8e0ac598035b8df77b9049fabaa))
* wrong payload injected for nested create in update ([#715](https://github.com/jasonmacdonald/zenstack/issues/715)) ([d8f0954](https://github.com/jasonmacdonald/zenstack/commit/d8f0954fc15b6ea3df033a7c5fea414ff4aba8c9))
* zod schema compilation errors in pnpm environment due to peer dependencies ([#568](https://github.com/jasonmacdonald/zenstack/issues/568)) ([858b075](https://github.com/jasonmacdonald/zenstack/commit/858b075ca193ae26673aaefc052cc7c029a26c08))
</details>

<details><summary>2.0.0-alpha.4</summary>

## [2.0.0-alpha.4](https://github.com/jasonmacdonald/zenstack/compare/v2.0.0-alpha.3...v2.0.0-alpha.4) (2024-07-10)


### Features

* a better "zod" plugin ([#521](https://github.com/jasonmacdonald/zenstack/issues/521)) ([2280f83](https://github.com/jasonmacdonald/zenstack/commit/2280f83cd7f1f597fddfd6ab0c99417200124452))
* add @[@auth](https://github.com/auth) option for declaring auth model ([#787](https://github.com/jasonmacdonald/zenstack/issues/787)) ([c390de1](https://github.com/jasonmacdonald/zenstack/commit/c390de10cfa91ae3f954404bc07e0905973b0898))
* add support for comparing fields in the same model ([#631](https://github.com/jasonmacdonald/zenstack/issues/631)) ([4776685](https://github.com/jasonmacdonald/zenstack/commit/477668579e3d95e7371ca752244ad2e319a96477))
* allow comparing fields from different models in mutation policies ([#1476](https://github.com/jasonmacdonald/zenstack/issues/1476)) ([6610bd0](https://github.com/jasonmacdonald/zenstack/commit/6610bd09f8d43b62b073044bb60a8a3cc40ef9e2))
* always use superjson to serialize/deserialize in the api layer ([#585](https://github.com/jasonmacdonald/zenstack/issues/585)) ([46fec66](https://github.com/jasonmacdonald/zenstack/commit/46fec666c3af971010c69e467f08f55830655441))
* automatic optimistic update for tanstack hooks ([#830](https://github.com/jasonmacdonald/zenstack/issues/830)) ([93dc7df](https://github.com/jasonmacdonald/zenstack/commit/93dc7df472427a4546ba71ec3703135d2d638ded))
* field-level access control ([#638](https://github.com/jasonmacdonald/zenstack/issues/638)) ([9a6f39b](https://github.com/jasonmacdonald/zenstack/commit/9a6f39bdb8940f7cef89fd7ee423658b8ed4c49f))
* implementing permission checker ([#1411](https://github.com/jasonmacdonald/zenstack/issues/1411)) ([0aa6ee9](https://github.com/jasonmacdonald/zenstack/commit/0aa6ee961bab005705287184b670ae9a3a57f06d))
* improved automatic query invalidation for tanstack-query ([#790](https://github.com/jasonmacdonald/zenstack/issues/790)) ([42d654f](https://github.com/jasonmacdonald/zenstack/commit/42d654fcfaa40b09fde578db79792c69e1e3b908))
* make parameters of transactions configurable ([#988](https://github.com/jasonmacdonald/zenstack/issues/988)) ([d0745b1](https://github.com/jasonmacdonald/zenstack/commit/d0745b149a5ce6abfef546de0b9243ddc4f6e765))
* runtime support for custom `@[@auth](https://github.com/auth)` model ([#793](https://github.com/jasonmacdonald/zenstack/issues/793)) ([08b9677](https://github.com/jasonmacdonald/zenstack/commit/08b967735c938de1e770a2409c36c5a50173b01d))
* support configuring what models to include for zod and trpc plugins ([#747](https://github.com/jasonmacdonald/zenstack/issues/747)) ([a5d15a3](https://github.com/jasonmacdonald/zenstack/commit/a5d15a30e7a22a3e875cc974391feb9ad6da7646))
* support Prisma v5 ([#587](https://github.com/jasonmacdonald/zenstack/issues/587)) ([b0d9154](https://github.com/jasonmacdonald/zenstack/commit/b0d9154270a89c6c93c7a8f1aada85c413d16d6f))
* support Prisma view ([#579](https://github.com/jasonmacdonald/zenstack/issues/579)) ([af151b7](https://github.com/jasonmacdonald/zenstack/commit/af151b7b311ee96b626376b8a17103b18c261f65))


### Bug Fixes

* [ZModelCodeGenerator] Remove the extra space between the collection predicate operator ([#839](https://github.com/jasonmacdonald/zenstack/issues/839)) ([9a0895b](https://github.com/jasonmacdonald/zenstack/commit/9a0895bedd82b429ddcc45db4cee0f9e82c54198))
* add "exports" to generated package.json, make trpc code-gen compatible with vite ([#677](https://github.com/jasonmacdonald/zenstack/issues/677)) ([df67f30](https://github.com/jasonmacdonald/zenstack/commit/df67f301119db23e5048464de2f73bff1a2adffc))
* add `CheckSelect` type into code for Prisma version backward compatibility ([#619](https://github.com/jasonmacdonald/zenstack/issues/619)) ([3e09a3a](https://github.com/jasonmacdonald/zenstack/commit/3e09a3a6646ae0f6e393cc0f92991c9b5d0c4d29))
* add enum import to zod generation ([#528](https://github.com/jasonmacdonald/zenstack/issues/528)) ([2a4b5cc](https://github.com/jasonmacdonald/zenstack/commit/2a4b5cc328645387a604f2fdf7c8855804306243))
* auth() cannot be resolved if the auth model is marked @[@ignore](https://github.com/ignore) ([#844](https://github.com/jasonmacdonald/zenstack/issues/844)) ([73f2cec](https://github.com/jasonmacdonald/zenstack/commit/73f2cec82fea64cea05f7306523f7c6f9ac91f84))
* automatically enable "@core/zod" plugin when there're validation rules ([#535](https://github.com/jasonmacdonald/zenstack/issues/535)) ([0519421](https://github.com/jasonmacdonald/zenstack/commit/05194219f28e49ee11d1a1bd9a78146e9b76eada))
* avoid importing prisma-related code into language server ([#1441](https://github.com/jasonmacdonald/zenstack/issues/1441)) ([b22c6a3](https://github.com/jasonmacdonald/zenstack/commit/b22c6a3ce238ec766d910f23e83aea4e8f10c05d))
* bugs related to model name casing ([#645](https://github.com/jasonmacdonald/zenstack/issues/645)) ([32d5b26](https://github.com/jasonmacdonald/zenstack/commit/32d5b262cacdd03209a56027e4c2cbda1bc408c0))
* build, lint and etc. ([#833](https://github.com/jasonmacdonald/zenstack/issues/833)) ([cccbc3c](https://github.com/jasonmacdonald/zenstack/commit/cccbc3c82ad522d40bc76ad7b84b1305d378b1db))
* change back to loading from literal ".zenstack" path otherwise Vercel breaks :( ([#701](https://github.com/jasonmacdonald/zenstack/issues/701)) ([2d41a9f](https://github.com/jasonmacdonald/zenstack/commit/2d41a9fcffab2fa228356a5cc45b4c2ecd62fd63))
* clean up zod generation ([#883](https://github.com/jasonmacdonald/zenstack/issues/883)) ([909281f](https://github.com/jasonmacdonald/zenstack/commit/909281f8090734322c0cab09d0187b6b5e813c9a))
* clean up zod generation ([#883](https://github.com/jasonmacdonald/zenstack/issues/883)) ([9d4a8ed](https://github.com/jasonmacdonald/zenstack/commit/9d4a8ede7d42d1966fd5a12d64a5992092f4bc7d))
* compatibility with Prisma's "omit" feature ([#1432](https://github.com/jasonmacdonald/zenstack/issues/1432)) ([296ca25](https://github.com/jasonmacdonald/zenstack/commit/296ca259c8dd3e38fa988378df4a9e351a11b20b))
* enable auto completion inside attribute ([#949](https://github.com/jasonmacdonald/zenstack/issues/949)) ([20d5bfc](https://github.com/jasonmacdonald/zenstack/commit/20d5bfc506a42b520eb1cf390149b7afc7c38701))
* enhanced client doesn't work with client extensions that add new model methods ([#851](https://github.com/jasonmacdonald/zenstack/issues/851)) ([ea564c9](https://github.com/jasonmacdonald/zenstack/commit/ea564c93e9ca2a888c0e53216633d66c733f6beb))
* expression context check issue on initial loading ([#544](https://github.com/jasonmacdonald/zenstack/issues/544)) ([05b5554](https://github.com/jasonmacdonald/zenstack/commit/05b55541f3ae55214318db4f0de20b8ba97bb2f8))
* hooks generation emits Provider export for backward compatibility ([#594](https://github.com/jasonmacdonald/zenstack/issues/594)) ([ca3ebda](https://github.com/jasonmacdonald/zenstack/commit/ca3ebdae4e213d3901bb5834fd9ebf1217da94a7))
* improve consistency of generated guard code ([#616](https://github.com/jasonmacdonald/zenstack/issues/616)) ([1b7b5bd](https://github.com/jasonmacdonald/zenstack/commit/1b7b5bda3f5106d31b7f5e70be27158fb8217600))
* incorrect cross-model comparision for && and || expressions ([#1512](https://github.com/jasonmacdonald/zenstack/issues/1512)) ([908048b](https://github.com/jasonmacdonald/zenstack/commit/908048b01430ff6552e8df558d5b5905136ea5cc))
* incorrect relation owner analysis ([#610](https://github.com/jasonmacdonald/zenstack/issues/610)) ([c89012b](https://github.com/jasonmacdonald/zenstack/commit/c89012bcb8d32588cc7f5a1df19088292e571cec))
* incorrect reverse query built for to-many relation ([#815](https://github.com/jasonmacdonald/zenstack/issues/815)) ([2c345e1](https://github.com/jasonmacdonald/zenstack/commit/2c345e1d4fe7274b7a08c1178afccede1d694327))
* infinite recursion when injecting field selection for field-level permission check ([#1452](https://github.com/jasonmacdonald/zenstack/issues/1452)) ([29962e0](https://github.com/jasonmacdonald/zenstack/commit/29962e0b48a73ae6d42f43f2575048ba9cf6a953))
* issue [#627](https://github.com/jasonmacdonald/zenstack/issues/627) ([#628](https://github.com/jasonmacdonald/zenstack/issues/628)) ([2ef93cb](https://github.com/jasonmacdonald/zenstack/commit/2ef93cb932e7aed6923cd3d7e69069d0c9ff161b))
* issue 961, incorrect policy injection for nested `updateMany` ([bf690a0](https://github.com/jasonmacdonald/zenstack/commit/bf690a072771ab95907a8f56079c4f6aaf655849))
* issue 961, incorrect policy injection for nested `updateMany` ([#962](https://github.com/jasonmacdonald/zenstack/issues/962)) ([2b2bfcf](https://github.com/jasonmacdonald/zenstack/commit/2b2bfcff965f9a70ff2764e6fbc7613b6f061685))
* issues with cross-model comparison identification and injection ([#1508](https://github.com/jasonmacdonald/zenstack/issues/1508)) ([665f9b3](https://github.com/jasonmacdonald/zenstack/commit/665f9b33b58acc5170c4ccb8e73be525fbb89734))
* make sure Buffer is imported ([#596](https://github.com/jasonmacdonald/zenstack/issues/596)) ([76a0bac](https://github.com/jasonmacdonald/zenstack/commit/76a0bac9c63707baf34a072e398b63156c1e0640))
* make sure fields inherited from  abstract base models are properly recognized as id ([#1130](https://github.com/jasonmacdonald/zenstack/issues/1130)) ([4d9d093](https://github.com/jasonmacdonald/zenstack/commit/4d9d09338ae88eac331ec06ec908ca1256f5b8a5))
* make sure zod schemas have type annotations ([#574](https://github.com/jasonmacdonald/zenstack/issues/574)) ([51985b1](https://github.com/jasonmacdonald/zenstack/commit/51985b1279dca8e82a7275330a7b6597f37d15a4))
* model meta generator doesn't correctly identify relation names ([#1244](https://github.com/jasonmacdonald/zenstack/issues/1244)) ([4c7fbd4](https://github.com/jasonmacdonald/zenstack/commit/4c7fbd480214f1e2508fc9a520c571f6274dce8f))
* policy generator fails on Windows for custom output path ([#583](https://github.com/jasonmacdonald/zenstack/issues/583)) ([32c7279](https://github.com/jasonmacdonald/zenstack/commit/32c727934456127470a53ed13ad65d33ff94e97d))
* post-update rules incorrectly reject update ([#826](https://github.com/jasonmacdonald/zenstack/issues/826)) ([d921a7c](https://github.com/jasonmacdonald/zenstack/commit/d921a7ca6bef0341ccf5bc50e195156695129e7f))
* post-update rules incorrectly reject update ([#826](https://github.com/jasonmacdonald/zenstack/issues/826)) ([e85831e](https://github.com/jasonmacdonald/zenstack/commit/e85831e98d08a433febb5a8fecf8d539150ced08))
* prisma schema generation issue with calling attribute function with literal ([#930](https://github.com/jasonmacdonald/zenstack/issues/930)) ([91fe8e7](https://github.com/jasonmacdonald/zenstack/commit/91fe8e71b513804de36d08b03c37b0c175580906))
* **runtime:** always use id fields to address existing entity during upsert ([#1273](https://github.com/jasonmacdonald/zenstack/issues/1273)) ([d8c1513](https://github.com/jasonmacdonald/zenstack/commit/d8c15135a7edb75b459b6f5f1736e5fa2d96a9fa))
* support for custom prisma client output path ([#514](https://github.com/jasonmacdonald/zenstack/issues/514)) ([5f3669e](https://github.com/jasonmacdonald/zenstack/commit/5f3669e53363bbfb035f100d0c6e2d14cef69c24))
* support postgres extensions ([#718](https://github.com/jasonmacdonald/zenstack/issues/718)) ([cdc98e0](https://github.com/jasonmacdonald/zenstack/commit/cdc98e08224a23ea3f6e5d620c11c90a34ed6435))
* support string literal keys for object expressions in ZModel ([#752](https://github.com/jasonmacdonald/zenstack/issues/752)) ([22b1bf9](https://github.com/jasonmacdonald/zenstack/commit/22b1bf9ddd4062000f2cd7d183e004dd3d5917c6))
* supports for complex usage of "@[@index](https://github.com/index)" in zmodel ([#995](https://github.com/jasonmacdonald/zenstack/issues/995)) ([541cd97](https://github.com/jasonmacdonald/zenstack/commit/541cd973081cbbf2d9e2e571ee8f971bc859150c))
* **tanstack:** incorrect InfiniteData import for vue-query ([#1498](https://github.com/jasonmacdonald/zenstack/issues/1498)) ([92f187f](https://github.com/jasonmacdonald/zenstack/commit/92f187f9190517df5baca795f12386c12c6694e9))
* vscode language accidentally bundles prisma packages  ([#625](https://github.com/jasonmacdonald/zenstack/issues/625)) ([f6b68da](https://github.com/jasonmacdonald/zenstack/commit/f6b68dabc9e089230bc6d8f8e802e8fbc43a8a69))
* vscode language accidentally bundles prisma packages ([#623](https://github.com/jasonmacdonald/zenstack/issues/623)) ([a81913e](https://github.com/jasonmacdonald/zenstack/commit/a81913e69d3533874c038279d1d4d226ad685d8d))
* **zmodel:** enum is resolved to wrong element after merging base models ([#1437](https://github.com/jasonmacdonald/zenstack/issues/1437)) ([6852958](https://github.com/jasonmacdonald/zenstack/commit/68529580028dfcfce50cb9af78a9b67d72e2a6a5))
* zod and openapi generation error when "fullTextSearch" is enabled ([#658](https://github.com/jasonmacdonald/zenstack/issues/658)) ([0cb7cd1](https://github.com/jasonmacdonald/zenstack/commit/0cb7cd1ae5e8c5d4a72d0891c9624291aafcbcd8))
</details>

<details><summary>2.0.0-alpha.4</summary>

## [2.0.0-alpha.4](https://github.com/jasonmacdonald/zenstack/compare/v2.0.0-alpha.3...v2.0.0-alpha.4) (2024-07-10)


### Features

* a better "zod" plugin ([#521](https://github.com/jasonmacdonald/zenstack/issues/521)) ([2280f83](https://github.com/jasonmacdonald/zenstack/commit/2280f83cd7f1f597fddfd6ab0c99417200124452))
* add "loadPath" options to runtime API and server adapter options ([#696](https://github.com/jasonmacdonald/zenstack/issues/696)) ([fc50deb](https://github.com/jasonmacdonald/zenstack/commit/fc50deb6e70acc78dcb66b17e564a6fc84475970))
* add switch to zod plugin to control whether unchecked input types are generated ([#693](https://github.com/jasonmacdonald/zenstack/issues/693)) ([cea2019](https://github.com/jasonmacdonald/zenstack/commit/cea2019aee4f27ff4bf12677906a48daa91aa854))
* always use superjson to serialize/deserialize in the api layer ([#585](https://github.com/jasonmacdonald/zenstack/issues/585)) ([46fec66](https://github.com/jasonmacdonald/zenstack/commit/46fec666c3af971010c69e467f08f55830655441))
* automatic optimistic update for tanstack hooks ([#830](https://github.com/jasonmacdonald/zenstack/issues/830)) ([93dc7df](https://github.com/jasonmacdonald/zenstack/commit/93dc7df472427a4546ba71ec3703135d2d638ded))
* fluent API support ([#666](https://github.com/jasonmacdonald/zenstack/issues/666)) ([4ae5a96](https://github.com/jasonmacdonald/zenstack/commit/4ae5a96ee2976dedbdb0b207f48c082c48b3f9ce))
* implementing permission checker ([#1411](https://github.com/jasonmacdonald/zenstack/issues/1411)) ([0aa6ee9](https://github.com/jasonmacdonald/zenstack/commit/0aa6ee961bab005705287184b670ae9a3a57f06d))
* include raw zod errors in response ([#691](https://github.com/jasonmacdonald/zenstack/issues/691)) ([b5da998](https://github.com/jasonmacdonald/zenstack/commit/b5da998b7fa11c19b85cebd0956803d854332b4d))
* JetBrains plugin for ZModel ([#904](https://github.com/jasonmacdonald/zenstack/issues/904)) ([c79be9e](https://github.com/jasonmacdonald/zenstack/commit/c79be9eb7f6b602bc84214bded2b927935b6273a))
* make nextjs adapter support next 13 app dir ([#483](https://github.com/jasonmacdonald/zenstack/issues/483)) ([a078b23](https://github.com/jasonmacdonald/zenstack/commit/a078b23a1afd799ba9aba50b82d497851160ef24))
* make parameters of transactions configurable ([#988](https://github.com/jasonmacdonald/zenstack/issues/988)) ([d0745b1](https://github.com/jasonmacdonald/zenstack/commit/d0745b149a5ce6abfef546de0b9243ddc4f6e765))
* Nuxt server adapter and tanstack-query for "vue" hooks generation ([#757](https://github.com/jasonmacdonald/zenstack/issues/757)) ([033d95d](https://github.com/jasonmacdonald/zenstack/commit/033d95dcdeef67bc8183d1daeb3172ec9ee02b9b))
* options for logging queries sent to prisma ([#488](https://github.com/jasonmacdonald/zenstack/issues/488)) ([ccfb2b0](https://github.com/jasonmacdonald/zenstack/commit/ccfb2b088cf1ce14c78c1d1355db5cb4ebcdc957))
* support Prisma v5 ([#587](https://github.com/jasonmacdonald/zenstack/issues/587)) ([b0d9154](https://github.com/jasonmacdonald/zenstack/commit/b0d9154270a89c6c93c7a8f1aada85c413d16d6f))


### Bug Fixes

* add "exports" to generated package.json, make trpc code-gen compatible with vite ([#677](https://github.com/jasonmacdonald/zenstack/issues/677)) ([df67f30](https://github.com/jasonmacdonald/zenstack/commit/df67f301119db23e5048464de2f73bff1a2adffc))
* add `CheckSelect` type into code for Prisma version backward compatibility ([#619](https://github.com/jasonmacdonald/zenstack/issues/619)) ([3e09a3a](https://github.com/jasonmacdonald/zenstack/commit/3e09a3a6646ae0f6e393cc0f92991c9b5d0c4d29))
* build, lint and etc. ([#833](https://github.com/jasonmacdonald/zenstack/issues/833)) ([cccbc3c](https://github.com/jasonmacdonald/zenstack/commit/cccbc3c82ad522d40bc76ad7b84b1305d378b1db))
* change back to loading from literal ".zenstack" path otherwise Vercel breaks :( ([#701](https://github.com/jasonmacdonald/zenstack/issues/701)) ([2d41a9f](https://github.com/jasonmacdonald/zenstack/commit/2d41a9fcffab2fa228356a5cc45b4c2ecd62fd63))
* clean up zod generation ([#883](https://github.com/jasonmacdonald/zenstack/issues/883)) ([909281f](https://github.com/jasonmacdonald/zenstack/commit/909281f8090734322c0cab09d0187b6b5e813c9a))
* clean up zod generation ([#883](https://github.com/jasonmacdonald/zenstack/issues/883)) ([9d4a8ed](https://github.com/jasonmacdonald/zenstack/commit/9d4a8ede7d42d1966fd5a12d64a5992092f4bc7d))
* enhanced client doesn't work with client extensions that add new model methods ([#851](https://github.com/jasonmacdonald/zenstack/issues/851)) ([ea564c9](https://github.com/jasonmacdonald/zenstack/commit/ea564c93e9ca2a888c0e53216633d66c733f6beb))
* fastify plugin correctly returning the reply [#684](https://github.com/jasonmacdonald/zenstack/issues/684) ([#685](https://github.com/jasonmacdonald/zenstack/issues/685)) ([7a04ce5](https://github.com/jasonmacdonald/zenstack/commit/7a04ce5ad0a208fb05887198b8b598742834a15b))
* generate both cjs and esm builds for swr plugin ([#892](https://github.com/jasonmacdonald/zenstack/issues/892)) ([385839f](https://github.com/jasonmacdonald/zenstack/commit/385839f101941234c5293d70d07e064c1c458387))
* hooks generation emits Provider export for backward compatibility ([#594](https://github.com/jasonmacdonald/zenstack/issues/594)) ([ca3ebda](https://github.com/jasonmacdonald/zenstack/commit/ca3ebdae4e213d3901bb5834fd9ebf1217da94a7))
* improve consistency of generated guard code ([#616](https://github.com/jasonmacdonald/zenstack/issues/616)) ([1b7b5bd](https://github.com/jasonmacdonald/zenstack/commit/1b7b5bda3f5106d31b7f5e70be27158fb8217600))
* incorrect cross-model comparision for && and || expressions ([#1512](https://github.com/jasonmacdonald/zenstack/issues/1512)) ([908048b](https://github.com/jasonmacdonald/zenstack/commit/908048b01430ff6552e8df558d5b5905136ea5cc))
* incorrect relation owner analysis ([#610](https://github.com/jasonmacdonald/zenstack/issues/610)) ([c89012b](https://github.com/jasonmacdonald/zenstack/commit/c89012bcb8d32588cc7f5a1df19088292e571cec))
* incorrect reverse query built for to-many relation ([#815](https://github.com/jasonmacdonald/zenstack/issues/815)) ([2c345e1](https://github.com/jasonmacdonald/zenstack/commit/2c345e1d4fe7274b7a08c1178afccede1d694327))
* infinite recursion when injecting field selection for field-level permission check ([#1452](https://github.com/jasonmacdonald/zenstack/issues/1452)) ([29962e0](https://github.com/jasonmacdonald/zenstack/commit/29962e0b48a73ae6d42f43f2575048ba9cf6a953))
* issue [#627](https://github.com/jasonmacdonald/zenstack/issues/627) ([#628](https://github.com/jasonmacdonald/zenstack/issues/628)) ([2ef93cb](https://github.com/jasonmacdonald/zenstack/commit/2ef93cb932e7aed6923cd3d7e69069d0c9ff161b))
* issue 961, incorrect policy injection for nested `updateMany` ([#962](https://github.com/jasonmacdonald/zenstack/issues/962)) ([2b2bfcf](https://github.com/jasonmacdonald/zenstack/commit/2b2bfcff965f9a70ff2764e6fbc7613b6f061685))
* issue with client typing generation in trpc plugin ([#673](https://github.com/jasonmacdonald/zenstack/issues/673)) ([576c4f7](https://github.com/jasonmacdonald/zenstack/commit/576c4f7a4858dfa2dcb9c1a7f75af8d1ca48a8ce))
* issues with cross-model comparison identification and injection ([#1508](https://github.com/jasonmacdonald/zenstack/issues/1508)) ([665f9b3](https://github.com/jasonmacdonald/zenstack/commit/665f9b33b58acc5170c4ccb8e73be525fbb89734))
* make sure Buffer is imported ([#596](https://github.com/jasonmacdonald/zenstack/issues/596)) ([76a0bac](https://github.com/jasonmacdonald/zenstack/commit/76a0bac9c63707baf34a072e398b63156c1e0640))
* make sure zod schemas have type annotations ([#574](https://github.com/jasonmacdonald/zenstack/issues/574)) ([51985b1](https://github.com/jasonmacdonald/zenstack/commit/51985b1279dca8e82a7275330a7b6597f37d15a4))
* nullify field instead of reject when an optional relation field is not readable ([#588](https://github.com/jasonmacdonald/zenstack/issues/588)) ([fc16008](https://github.com/jasonmacdonald/zenstack/commit/fc16008ba20aba18f39948f3ff13ec3bc79729e3))
* post-update rules incorrectly reject update ([#826](https://github.com/jasonmacdonald/zenstack/issues/826)) ([d921a7c](https://github.com/jasonmacdonald/zenstack/commit/d921a7ca6bef0341ccf5bc50e195156695129e7f))
* post-update rules incorrectly reject update ([#826](https://github.com/jasonmacdonald/zenstack/issues/826)) ([e85831e](https://github.com/jasonmacdonald/zenstack/commit/e85831e98d08a433febb5a8fecf8d539150ced08))
* rest api should return error reason ([#507](https://github.com/jasonmacdonald/zenstack/issues/507)) ([4b389fb](https://github.com/jasonmacdonald/zenstack/commit/4b389fb648cc42a88c3a7628efebd7f438d110e7))
* rest-api, wrong links generated for to-one relationship ([#481](https://github.com/jasonmacdonald/zenstack/issues/481)) ([21affec](https://github.com/jasonmacdonald/zenstack/commit/21affec12da5b8bb31b774791405d2773dec9072))
* supports for complex usage of "@[@index](https://github.com/index)" in zmodel ([#995](https://github.com/jasonmacdonald/zenstack/issues/995)) ([541cd97](https://github.com/jasonmacdonald/zenstack/commit/541cd973081cbbf2d9e2e571ee8f971bc859150c))
* **tanstack:** incorrect InfiniteData import for vue-query ([#1498](https://github.com/jasonmacdonald/zenstack/issues/1498)) ([92f187f](https://github.com/jasonmacdonald/zenstack/commit/92f187f9190517df5baca795f12386c12c6694e9))
* vscode language accidentally bundles prisma packages  ([#625](https://github.com/jasonmacdonald/zenstack/issues/625)) ([f6b68da](https://github.com/jasonmacdonald/zenstack/commit/f6b68dabc9e089230bc6d8f8e802e8fbc43a8a69))
* **zod:** add coercion call when generating schema for DateTime field ([#1068](https://github.com/jasonmacdonald/zenstack/issues/1068)) ([b60627c](https://github.com/jasonmacdonald/zenstack/commit/b60627c167706728ac232ce06366d914e3dde23f))
</details>

<details><summary>2.0.0-alpha.4</summary>

## [2.0.0-alpha.4](https://github.com/jasonmacdonald/zenstack/compare/v2.0.0-alpha.3...v2.0.0-alpha.4) (2024-07-10)


### Features

* a better "zod" plugin ([#521](https://github.com/jasonmacdonald/zenstack/issues/521)) ([2280f83](https://github.com/jasonmacdonald/zenstack/commit/2280f83cd7f1f597fddfd6ab0c99417200124452))
* add "loadPath" options to runtime API and server adapter options ([#696](https://github.com/jasonmacdonald/zenstack/issues/696)) ([fc50deb](https://github.com/jasonmacdonald/zenstack/commit/fc50deb6e70acc78dcb66b17e564a6fc84475970))
* fluent API support ([#666](https://github.com/jasonmacdonald/zenstack/issues/666)) ([4ae5a96](https://github.com/jasonmacdonald/zenstack/commit/4ae5a96ee2976dedbdb0b207f48c082c48b3f9ce))
* implementing access control for Prisma Pulse ([#643](https://github.com/jasonmacdonald/zenstack/issues/643)) ([d8c2e87](https://github.com/jasonmacdonald/zenstack/commit/d8c2e8717e5fd3facb177443c8ef1baec89a81d5))
* implementing permission checker ([#1411](https://github.com/jasonmacdonald/zenstack/issues/1411)) ([0aa6ee9](https://github.com/jasonmacdonald/zenstack/commit/0aa6ee961bab005705287184b670ae9a3a57f06d))
* make parameters of transactions configurable ([#988](https://github.com/jasonmacdonald/zenstack/issues/988)) ([d0745b1](https://github.com/jasonmacdonald/zenstack/commit/d0745b149a5ce6abfef546de0b9243ddc4f6e765))
* options for logging queries sent to prisma ([#488](https://github.com/jasonmacdonald/zenstack/issues/488)) ([ccfb2b0](https://github.com/jasonmacdonald/zenstack/commit/ccfb2b088cf1ce14c78c1d1355db5cb4ebcdc957))
* support Prisma v5 ([#587](https://github.com/jasonmacdonald/zenstack/issues/587)) ([b0d9154](https://github.com/jasonmacdonald/zenstack/commit/b0d9154270a89c6c93c7a8f1aada85c413d16d6f))
* tanstack-query v5 support ([#788](https://github.com/jasonmacdonald/zenstack/issues/788)) ([0d04d8e](https://github.com/jasonmacdonald/zenstack/commit/0d04d8e6dabd66ee06e98971cb4e1007c4ecd466))


### Bug Fixes

* add "exports" to generated package.json, make trpc code-gen compatible with vite ([#677](https://github.com/jasonmacdonald/zenstack/issues/677)) ([df67f30](https://github.com/jasonmacdonald/zenstack/commit/df67f301119db23e5048464de2f73bff1a2adffc))
* add `CheckSelect` type into code for Prisma version backward compatibility ([#619](https://github.com/jasonmacdonald/zenstack/issues/619)) ([3e09a3a](https://github.com/jasonmacdonald/zenstack/commit/3e09a3a6646ae0f6e393cc0f92991c9b5d0c4d29))
* change back to loading from literal ".zenstack" path otherwise Vercel breaks :( ([#701](https://github.com/jasonmacdonald/zenstack/issues/701)) ([2d41a9f](https://github.com/jasonmacdonald/zenstack/commit/2d41a9fcffab2fa228356a5cc45b4c2ecd62fd63))
* clean up zod generation ([#883](https://github.com/jasonmacdonald/zenstack/issues/883)) ([909281f](https://github.com/jasonmacdonald/zenstack/commit/909281f8090734322c0cab09d0187b6b5e813c9a))
* clean up zod generation ([#883](https://github.com/jasonmacdonald/zenstack/issues/883)) ([9d4a8ed](https://github.com/jasonmacdonald/zenstack/commit/9d4a8ede7d42d1966fd5a12d64a5992092f4bc7d))
* client-extension test failures ([#874](https://github.com/jasonmacdonald/zenstack/issues/874)) ([f2ab6a5](https://github.com/jasonmacdonald/zenstack/commit/f2ab6a521195c4981fd89a5d4094e4130c5b336c))
* compatibility with Prisma's "omit" feature ([#1432](https://github.com/jasonmacdonald/zenstack/issues/1432)) ([296ca25](https://github.com/jasonmacdonald/zenstack/commit/296ca259c8dd3e38fa988378df4a9e351a11b20b))
* decimal field zod validation ([#660](https://github.com/jasonmacdonald/zenstack/issues/660)) ([522df7a](https://github.com/jasonmacdonald/zenstack/commit/522df7ac0d42aee1dbc29b42e8acfa431771bb3b))
* duplicated zod schema imported when there're multiple fields with an enum type ([#633](https://github.com/jasonmacdonald/zenstack/issues/633)) ([4b70853](https://github.com/jasonmacdonald/zenstack/commit/4b70853868c8f456ed1fd3dd836f0f2e36ed3e11))
* enhanced client doesn't work with client extensions that add new model methods ([#851](https://github.com/jasonmacdonald/zenstack/issues/851)) ([ea564c9](https://github.com/jasonmacdonald/zenstack/commit/ea564c93e9ca2a888c0e53216633d66c733f6beb))
* hooks generation emits Provider export for backward compatibility ([#594](https://github.com/jasonmacdonald/zenstack/issues/594)) ([ca3ebda](https://github.com/jasonmacdonald/zenstack/commit/ca3ebdae4e213d3901bb5834fd9ebf1217da94a7))
* improve consistency of generated guard code ([#616](https://github.com/jasonmacdonald/zenstack/issues/616)) ([1b7b5bd](https://github.com/jasonmacdonald/zenstack/commit/1b7b5bda3f5106d31b7f5e70be27158fb8217600))
* incorrect cross-model comparision for && and || expressions ([#1512](https://github.com/jasonmacdonald/zenstack/issues/1512)) ([908048b](https://github.com/jasonmacdonald/zenstack/commit/908048b01430ff6552e8df558d5b5905136ea5cc))
* incorrect relation owner analysis ([#610](https://github.com/jasonmacdonald/zenstack/issues/610)) ([c89012b](https://github.com/jasonmacdonald/zenstack/commit/c89012bcb8d32588cc7f5a1df19088292e571cec))
* incorrect reverse query built for to-many relation ([#815](https://github.com/jasonmacdonald/zenstack/issues/815)) ([2c345e1](https://github.com/jasonmacdonald/zenstack/commit/2c345e1d4fe7274b7a08c1178afccede1d694327))
* infinite recursion when injecting field selection for field-level permission check ([#1452](https://github.com/jasonmacdonald/zenstack/issues/1452)) ([29962e0](https://github.com/jasonmacdonald/zenstack/commit/29962e0b48a73ae6d42f43f2575048ba9cf6a953))
* issue [#627](https://github.com/jasonmacdonald/zenstack/issues/627) ([#628](https://github.com/jasonmacdonald/zenstack/issues/628)) ([2ef93cb](https://github.com/jasonmacdonald/zenstack/commit/2ef93cb932e7aed6923cd3d7e69069d0c9ff161b))
* issue 961, incorrect policy injection for nested `updateMany` ([#962](https://github.com/jasonmacdonald/zenstack/issues/962)) ([2b2bfcf](https://github.com/jasonmacdonald/zenstack/commit/2b2bfcff965f9a70ff2764e6fbc7613b6f061685))
* issues with cross-model comparison identification and injection ([#1508](https://github.com/jasonmacdonald/zenstack/issues/1508)) ([665f9b3](https://github.com/jasonmacdonald/zenstack/commit/665f9b33b58acc5170c4ccb8e73be525fbb89734))
* make sure Buffer is imported ([#596](https://github.com/jasonmacdonald/zenstack/issues/596)) ([76a0bac](https://github.com/jasonmacdonald/zenstack/commit/76a0bac9c63707baf34a072e398b63156c1e0640))
* make sure zod schemas have type annotations ([#574](https://github.com/jasonmacdonald/zenstack/issues/574)) ([51985b1](https://github.com/jasonmacdonald/zenstack/commit/51985b1279dca8e82a7275330a7b6597f37d15a4))
* nullify field instead of reject when an optional relation field is not readable ([#588](https://github.com/jasonmacdonald/zenstack/issues/588)) ([fc16008](https://github.com/jasonmacdonald/zenstack/commit/fc16008ba20aba18f39948f3ff13ec3bc79729e3))
* post-update rules incorrectly reject update ([#826](https://github.com/jasonmacdonald/zenstack/issues/826)) ([d921a7c](https://github.com/jasonmacdonald/zenstack/commit/d921a7ca6bef0341ccf5bc50e195156695129e7f))
* post-update rules incorrectly reject update ([#826](https://github.com/jasonmacdonald/zenstack/issues/826)) ([e85831e](https://github.com/jasonmacdonald/zenstack/commit/e85831e98d08a433febb5a8fecf8d539150ced08))
* properly handle missing fields when evaluating `@[@validate](https://github.com/validate)` model-level rules ([#1097](https://github.com/jasonmacdonald/zenstack/issues/1097)) ([e8268d0](https://github.com/jasonmacdonald/zenstack/commit/e8268d03ae12f3ccbcf1bb1c531a2816b22f6da8))
* support for string escaping in ZModel ([#668](https://github.com/jasonmacdonald/zenstack/issues/668)) ([f034839](https://github.com/jasonmacdonald/zenstack/commit/f034839867fa438da866bd87548b4a18246dee21))
* support string literal keys for object expressions in ZModel ([#752](https://github.com/jasonmacdonald/zenstack/issues/752)) ([22b1bf9](https://github.com/jasonmacdonald/zenstack/commit/22b1bf9ddd4062000f2cd7d183e004dd3d5917c6))
* supports for complex usage of "@[@index](https://github.com/index)" in zmodel ([#995](https://github.com/jasonmacdonald/zenstack/issues/995)) ([541cd97](https://github.com/jasonmacdonald/zenstack/commit/541cd973081cbbf2d9e2e571ee8f971bc859150c))
* **tanstack:** incorrect InfiniteData import for vue-query ([#1498](https://github.com/jasonmacdonald/zenstack/issues/1498)) ([92f187f](https://github.com/jasonmacdonald/zenstack/commit/92f187f9190517df5baca795f12386c12c6694e9))
* vscode language accidentally bundles prisma packages  ([#625](https://github.com/jasonmacdonald/zenstack/issues/625)) ([f6b68da](https://github.com/jasonmacdonald/zenstack/commit/f6b68dabc9e089230bc6d8f8e802e8fbc43a8a69))
* **zmodel:** enum is resolved to wrong element after merging base models ([#1437](https://github.com/jasonmacdonald/zenstack/issues/1437)) ([6852958](https://github.com/jasonmacdonald/zenstack/commit/68529580028dfcfce50cb9af78a9b67d72e2a6a5))
</details>

---
This PR was generated by [Release-Please](https://github.com/googleapis/release-please).