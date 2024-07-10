# Changelog

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

## [2.0.0-alpha.3](https://github.com/jasonmacdonald/zenstack/compare/v2.0.0-alpha.2...v2.0.0-alpha.3) (2024-06-27)


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

## [2.0.0-alpha.2](https://github.com/zenstackhq/zenstack/compare/v2.0.0-alpha.1...v2.0.0-alpha.2) (2024-02-21)


### Miscellaneous Chores

* release 2.0.0-alpha.2 ([f40d7e3](https://github.com/zenstackhq/zenstack/commit/f40d7e3718d4210137a2e131d28b5491d065b914))
