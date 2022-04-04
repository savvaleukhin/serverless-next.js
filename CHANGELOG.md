# Change Log

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

# [3.7.0](https://github.com/sleukhin/serverless-next.js/compare/v3.7.0-alpha.12...v3.7.0) (2022-03-31)

**Note:** Version bump only for package serverless-nextjs-monorepo

# [3.7.0-alpha.12](https://github.com/sleukhin/serverless-next.js/compare/v3.7.0-alpha.11...v3.7.0-alpha.12) (2022-03-15)

### Bug Fixes

- fix e2e static regeneration test code ([#2398](https://github.com/sleukhin/serverless-next.js/issues/2398)) ([e13e821](https://github.com/sleukhin/serverless-next.js/commit/e13e82184ab678b194a25cb7f80093c4e50c2736))

# [3.7.0-alpha.11](https://github.com/sleukhin/serverless-next.js/compare/v3.7.0-alpha.10...v3.7.0-alpha.11) (2022-03-10)

### Bug Fixes

- fix yarn.lock. ([#2395](https://github.com/sleukhin/serverless-next.js/issues/2395)) ([ec98072](https://github.com/sleukhin/serverless-next.js/commit/ec98072907e00ba9e9811720e7cf82086a322efc))
- redirect in getStaticProps ([#2393](https://github.com/sleukhin/serverless-next.js/issues/2393)) ([21283ab](https://github.com/sleukhin/serverless-next.js/commit/21283abd8c2754284264cdf516d2250e9f107cf5))
- wrong replace causing "on" files on S3 ([#2392](https://github.com/sleukhin/serverless-next.js/issues/2392)) ([f6b7efb](https://github.com/sleukhin/serverless-next.js/commit/f6b7efb1fa6ecf44d9041a6b73fcf3578267e9b5))

# [3.7.0-alpha.10](https://github.com/sleukhin/serverless-next.js/compare/v3.7.0-alpha.9...v3.7.0-alpha.10) (2022-02-23)

### Bug Fixes

- **core:** add getter to event req & res object in default handler. ([#2381](https://github.com/sleukhin/serverless-next.js/issues/2381)) ([31eff47](https://github.com/sleukhin/serverless-next.js/commit/31eff477b0ca792e87541125c9ebd18fe23c0065))

# [3.7.0-alpha.9](https://github.com/sleukhin/serverless-next.js/compare/v3.7.0-alpha.8...v3.7.0-alpha.9) (2022-02-18)

### Bug Fixes

- **core:** getter function for http base class in api handler ([#2344](https://github.com/sleukhin/serverless-next.js/issues/2344)) ([e819e1d](https://github.com/sleukhin/serverless-next.js/commit/e819e1dcf9a1ec52715c77b1b4f376b44ec95976))

### Features

- **nextjs-cdk-construct:** allow cache policies to be provided as props ([#2350](https://github.com/sleukhin/serverless-next.js/issues/2350)) ([68b7717](https://github.com/sleukhin/serverless-next.js/commit/68b7717c78a133fcb54318785e39b9d1239cb32e))
- update cdktf and use prebuilt providers ([#2328](https://github.com/sleukhin/serverless-next.js/issues/2328)) ([47642bf](https://github.com/sleukhin/serverless-next.js/commit/47642bf194097df5315e768a18ea32797f6b8b6e))

# [3.7.0-alpha.8](https://github.com/sleukhin/serverless-next.js/compare/v3.7.0-alpha.7...v3.7.0-alpha.8) (2022-02-02)

### Bug Fixes

- **core:** use existing upstream `Cache-Control` if present on upstream response ([#2322](https://github.com/sleukhin/serverless-next.js/issues/2322)) ([4f93ea7](https://github.com/sleukhin/serverless-next.js/commit/4f93ea7193018d70f171e3f8fca536da563c71da))

### Features

- **nextjs-cdk-construct:** Allow to whitelist headers ([#2325](https://github.com/sleukhin/serverless-next.js/issues/2325)) ([b975aed](https://github.com/sleukhin/serverless-next.js/commit/b975aed9a13f132750a707862242ca81f5e32cc7))

### Reverts

- revert "Experimental Next.js 12 Output File Tracing ([#2169](https://github.com/sleukhin/serverless-next.js/issues/2169))" ([#2324](https://github.com/sleukhin/serverless-next.js/issues/2324)) ([ca7f7f7](https://github.com/sleukhin/serverless-next.js/commit/ca7f7f72e3b1e5fcb49ffc4a3f6d6f629e644b20))

# [3.7.0-alpha.7](https://github.com/sleukhin/serverless-next.js/compare/v3.7.0-alpha.6...v3.7.0-alpha.7) (2022-01-27)

### Features

- **cloudfront:** add ability to set RealtimeLogConfigARN ([#2301](https://github.com/sleukhin/serverless-next.js/issues/2301)) ([04fec27](https://github.com/sleukhin/serverless-next.js/commit/04fec27ca99994acf98ccfb4ac6ead933cfb4dde))

# [3.7.0-alpha.6](https://github.com/sleukhin/serverless-next.js/compare/v3.7.0-alpha.5...v3.7.0-alpha.6) (2022-01-25)

### Features

- **cloudfront:** add ability to set ResponseHeadersPolicyId ([#2285](https://github.com/sleukhin/serverless-next.js/issues/2285)) ([15b282d](https://github.com/sleukhin/serverless-next.js/commit/15b282d91a4960c72e31eae56fd6bcc9a6d0d0fd))

# [3.7.0-alpha.5](https://github.com/sleukhin/serverless-next.js/compare/v3.7.0-alpha.4...v3.7.0-alpha.5) (2022-01-20)

### Bug Fixes

- **nextjs-cdk-construct:** use basepath in s3 assets ([#2265](https://github.com/sleukhin/serverless-next.js/issues/2265)) ([cf780e9](https://github.com/sleukhin/serverless-next.js/commit/cf780e983e8e8e367d891b1d365d3b2782bae9cb))

# [3.7.0-alpha.4](https://github.com/sleukhin/serverless-next.js/compare/v3.7.0-alpha.3...v3.7.0-alpha.4) (2022-01-05)

**Note:** Version bump only for package serverless-nextjs-monorepo

# [3.7.0-alpha.3](https://github.com/sleukhin/serverless-next.js/compare/v3.7.0-alpha.2...v3.7.0-alpha.3) (2021-12-22)

### Bug Fixes

- **core:** resolve invalid syntax on etag ([#2218](https://github.com/sleukhin/serverless-next.js/issues/2218)) ([a1c1877](https://github.com/sleukhin/serverless-next.js/commit/a1c18777655063fca837a42ae3a1649cccd4877f))

### Features

- **nextjs-cdk-construct:** support AWS CDK V2 ([#2187](https://github.com/sleukhin/serverless-next.js/issues/2187)) ([b329326](https://github.com/sleukhin/serverless-next.js/commit/b329326ec0f78eeb7dfbc2bbe105904931cfffb2))

# [3.7.0-alpha.2](https://github.com/sleukhin/serverless-next.js/compare/v3.7.0-alpha.1...v3.7.0-alpha.2) (2021-11-29)

### Bug Fixes

- **core:** check for 3rd party packages properly when 'dependencies' is not defined ([#2094](https://github.com/sleukhin/serverless-next.js/issues/2094)) ([ce293b7](https://github.com/sleukhin/serverless-next.js/commit/ce293b71344e85e062512afb8af1531e5eb3e06d))

### Features

- **core:** enabling avif support ([#2126](https://github.com/sleukhin/serverless-next.js/issues/2126)) ([9f9ab5b](https://github.com/sleukhin/serverless-next.js/commit/9f9ab5b2c79e9c85c4ab1d2f0c492cba43f90b7d))

# [3.7.0-alpha.1](https://github.com/sleukhin/serverless-next.js/compare/v3.7.0-alpha.0...v3.7.0-alpha.1) (2021-11-21)

### Bug Fixes

- **core:** check for 3rd party packages properly when 'dependencies' is not defined ([5006439](https://github.com/sleukhin/serverless-next.js/commit/50064394106205c45f8e943f05d41d1222cc34f3))

# [3.7.0-alpha.0](https://github.com/sleukhin/serverless-next.js/compare/v3.6.1-alpha.2...v3.7.0-alpha.0) (2021-11-21)

### Features

- **nextjs-cdk-construct:** add runtime options to regeneration ([#2050](https://github.com/sleukhin/serverless-next.js/issues/2050)) ([dd69323](https://github.com/sleukhin/serverless-next.js/commit/dd693238f6433cf1d12a4778dbdd6f65a1872458))

## [3.6.1-alpha.2](https://github.com/sleukhin/serverless-next.js/compare/v3.6.1-alpha.1...v3.6.1-alpha.2) (2021-11-15)

### Bug Fixes

- **aws-cloudfront, nextjs-component:** specify s3 client's region in aws-cloudfront the same as the bucket region ([#2042](https://github.com/sleukhin/serverless-next.js/issues/2042)) ([a676d03](https://github.com/sleukhin/serverless-next.js/commit/a676d0375b3a86150cf2672f82be86a3a94cc5d3))

## [3.6.1-alpha.1](https://github.com/sleukhin/serverless-next.js/compare/v3.6.1-alpha.0...v3.6.1-alpha.1) (2021-11-14)

### Bug Fixes

- **core:** handle encoded ISR url in data request ([#2039](https://github.com/sleukhin/serverless-next.js/issues/2039)) ([fe236c8](https://github.com/sleukhin/serverless-next.js/commit/fe236c8af464abb508f7bf15aaad3104264d788a))

## [3.6.1-alpha.0](https://github.com/sleukhin/serverless-next.js/compare/v3.6.0...v3.6.1-alpha.0) (2021-11-14)

### Bug Fixes

- **core, lambda-at-edge:** properly encoded URIs for ISR ([#2038](https://github.com/sleukhin/serverless-next.js/issues/2038)) ([d345aca](https://github.com/sleukhin/serverless-next.js/commit/d345acaa001a94d75fd02e87b07549f67c0696b6))

# [3.6.0](https://github.com/sleukhin/serverless-next.js/compare/v3.6.0-alpha.0...v3.6.0) (2021-11-14)

**Note:** Version bump only for package serverless-nextjs-monorepo

# [3.6.0-alpha.0](https://github.com/sleukhin/serverless-next.js/compare/v3.5.4-alpha.0...v3.6.0-alpha.0) (2021-11-14)

### Features

- **core:** add `x-forwarded-host` as precedence over `host` header ([#1999](https://github.com/sleukhin/serverless-next.js/issues/1999)) ([8258122](https://github.com/sleukhin/serverless-next.js/commit/825812287fe8f1740cf5368acea2ec35e89dd26c))

## [3.5.4-alpha.0](https://github.com/sleukhin/serverless-next.js/compare/v3.5.3...v3.5.4-alpha.0) (2021-11-10)

### Bug Fixes

- **core:** fix image optimizer for images with basepath in /\_next/static or /static/ ([#2033](https://github.com/sleukhin/serverless-next.js/issues/2033)) ([163c95a](https://github.com/sleukhin/serverless-next.js/commit/163c95a6556b7bf0a58eca419b292fc1a612510c))

## [3.5.3](https://github.com/sleukhin/serverless-next.js/compare/v3.5.3-alpha.6...v3.5.3) (2021-11-09)

**Note:** Version bump only for package serverless-nextjs-monorepo

## [3.5.3-alpha.6](https://github.com/sleukhin/serverless-next.js/compare/v3.5.3-alpha.5...v3.5.3-alpha.6) (2021-11-09)

### Bug Fixes

- **core:** add url normalization to image optimizer URL ([#2015](https://github.com/sleukhin/serverless-next.js/issues/2015)) ([5c4f841](https://github.com/sleukhin/serverless-next.js/commit/5c4f8411268e4b874fe296bd2ac5b880bd9addc1))
- **core:** render static pages for all http methods, for options methods return allowed methods ([#2024](https://github.com/sleukhin/serverless-next.js/issues/2024)) ([9fe3216](https://github.com/sleukhin/serverless-next.js/commit/9fe32167064f5a220ba1d55d8400673286752efc))

## [3.5.3-alpha.5](https://github.com/sleukhin/serverless-next.js/compare/v3.5.3-alpha.4...v3.5.3-alpha.5) (2021-11-08)

### Bug Fixes

- **core:** fix lookup for \_next/static files (used in lambda only right now) ([#2001](https://github.com/sleukhin/serverless-next.js/issues/2001)) ([09ea1c0](https://github.com/sleukhin/serverless-next.js/commit/09ea1c02f6ef7846a68e85893f9d707312aacdc6))
- **lambda, core:** build lambda properly with api/page routes in one single manifest ([#2010](https://github.com/sleukhin/serverless-next.js/issues/2010)) ([bc3668d](https://github.com/sleukhin/serverless-next.js/commit/bc3668d0013881276415a5dc09817c80cd4f32b8))
- **lambda:** fix apigw compat layer to properly handle binary data ([#2002](https://github.com/sleukhin/serverless-next.js/issues/2002)) ([e65c023](https://github.com/sleukhin/serverless-next.js/commit/e65c0234289cf0909fe4107e63aaccbf7e44354b))
- **lambda:** fix typo in lambda builder manifest for queueRegion ([#2008](https://github.com/sleukhin/serverless-next.js/issues/2008)) ([fdfa467](https://github.com/sleukhin/serverless-next.js/commit/fdfa467330bd27a1b537128b1533ec934f044777))

## [3.5.3-alpha.4](https://github.com/sleukhin/serverless-next.js/compare/v3.5.3-alpha.3...v3.5.3-alpha.4) (2021-10-30)

### Bug Fixes

- **lambda-at-edge:** properly include pages that start with pages/api (but are not api pages) ([#1994](https://github.com/sleukhin/serverless-next.js/issues/1994)) ([26a756c](https://github.com/sleukhin/serverless-next.js/commit/26a756cb413771bca7e649a1210b7a983ec569d0))

## [3.5.3-alpha.3](https://github.com/sleukhin/serverless-next.js/compare/v3.5.3-alpha.2...v3.5.3-alpha.3) (2021-10-30)

### Bug Fixes

- **aws-lambda:** add another wait after updating lambda config ([#1992](https://github.com/sleukhin/serverless-next.js/issues/1992)) ([67add7e](https://github.com/sleukhin/serverless-next.js/commit/67add7e430b944c2d732134e324663238a52f9d1))

## [3.5.3-alpha.2](https://github.com/sleukhin/serverless-next.js/compare/v3.5.3-alpha.1...v3.5.3-alpha.2) (2021-10-29)

### Bug Fixes

- **aws-lambda:** wait for lambda to be ready right after creation/updating of code ([#1985](https://github.com/sleukhin/serverless-next.js/issues/1985)) ([016fee0](https://github.com/sleukhin/serverless-next.js/commit/016fee081f25bf23e0bfc128ceb95f657b85b30f))
- **domain:** add missing pieces to 'domainMinimumProtocolVersion' input use ([#1983](https://github.com/sleukhin/serverless-next.js/issues/1983)) ([dff22ba](https://github.com/sleukhin/serverless-next.js/commit/dff22ba230e8cc3047d67cfbb82bc93a2e4edfe0))

## [3.5.3-alpha.1](https://github.com/sleukhin/serverless-next.js/compare/v3.5.3-alpha.0...v3.5.3-alpha.1) (2021-10-29)

### Bug Fixes

- **aws-lambda, nextjs-component:** ensure we wait until lambda functions are ready before using them ([#1982](https://github.com/sleukhin/serverless-next.js/issues/1982)) ([a0a22ab](https://github.com/sleukhin/serverless-next.js/commit/a0a22abbafe055e7868d8c621671b314bcb35dde))

## [3.5.3-alpha.0](https://github.com/sleukhin/serverless-next.js/compare/v3.5.2...v3.5.3-alpha.0) (2021-10-29)

**Note:** Version bump only for package serverless-nextjs-monorepo

## [3.5.2](https://github.com/sleukhin/serverless-next.js/compare/v3.5.1...v3.5.2) (2021-10-28)

### Bug Fixes

- **lerna:** fix publish command for stable versions ([ebcabb2](https://github.com/sleukhin/serverless-next.js/commit/ebcabb2a3eec64dfad538a7525de343d0bed230c))

## [3.5.1](https://github.com/sleukhin/serverless-next.js/compare/v3.5.0...v3.5.1) (2021-10-28)

### Bug Fixes

- **core:** only ignore publishing sharp_node_modules from root ([a33b7d5](https://github.com/sleukhin/serverless-next.js/commit/a33b7d556104e5336c7e3c466254b38f7ef23f06))

# [3.5.0](https://github.com/sleukhin/serverless-next.js/compare/v3.5.0-alpha.11...v3.5.0) (2021-10-28)

**Note:** Version bump only for package serverless-nextjs-monorepo

# [3.5.0-alpha.11](https://github.com/sleukhin/serverless-next.js/compare/v3.5.0-alpha.10...v3.5.0-alpha.11) (2021-10-27)

### Bug Fixes

- **core:** fix renderReqToHtml function for next.js 12 ([#1971](https://github.com/sleukhin/serverless-next.js/issues/1971)) ([c9980d8](https://github.com/sleukhin/serverless-next.js/commit/c9980d82cb06bb3dcc4aaef0ecc164c3819c6b23))

### Features

- **lambda-at-edge:** copy additional JS files to handlers ([#1970](https://github.com/sleukhin/serverless-next.js/issues/1970)) ([e7c81ef](https://github.com/sleukhin/serverless-next.js/commit/e7c81efde360bf7921c5aef088479154fa94280d))

# [3.5.0-alpha.10](https://github.com/sleukhin/serverless-next.js/compare/v3.5.0-alpha.9...v3.5.0-alpha.10) (2021-10-25)

**Note:** Version bump only for package serverless-nextjs-monorepo

# [3.5.0-alpha.9](https://github.com/sleukhin/serverless-next.js/compare/v3.5.0-alpha.8...v3.5.0-alpha.9) (2021-10-25)

### Bug Fixes

- **domain:** add domain input domainMinimumProtocolVersion ([#1916](https://github.com/sleukhin/serverless-next.js/issues/1916)) ([b49d2fe](https://github.com/sleukhin/serverless-next.js/commit/b49d2fe734690f88b29ed8ebab5befa49c529ea5))

# [3.5.0-alpha.8](https://github.com/sleukhin/serverless-next.js/compare/v3.5.0-alpha.7...v3.5.0-alpha.8) (2021-10-23)

### Features

- **nextjs-component, aws-lambda:** allow removing old lambda versions ([#1884](https://github.com/sleukhin/serverless-next.js/issues/1884)) ([0110f0a](https://github.com/sleukhin/serverless-next.js/commit/0110f0ade8c98b28fb0017255a3f56db80882c8e))

# [3.5.0-alpha.7](https://github.com/sleukhin/serverless-next.js/compare/v3.5.0-alpha.6...v3.5.0-alpha.7) (2021-10-19)

**Note:** Version bump only for package serverless-nextjs-monorepo

# [3.5.0-alpha.6](https://github.com/sleukhin/serverless-next.js/compare/v3.5.0-alpha.5...v3.5.0-alpha.6) (2021-10-19)

**Note:** Version bump only for package serverless-nextjs-monorepo

# [3.5.0-alpha.5](https://github.com/sleukhin/serverless-next.js/compare/v3.5.0-alpha.4...v3.5.0-alpha.5) (2021-10-18)

**Note:** Version bump only for package serverless-nextjs-monorepo

# [3.5.0-alpha.4](https://github.com/sleukhin/serverless-next.js/compare/v3.5.0-alpha.3...v3.5.0-alpha.4) (2021-10-18)

### Bug Fixes

- **core:** fix 'basePath: false' external rewrites ([#1859](https://github.com/sleukhin/serverless-next.js/issues/1859)) ([f60ff4a](https://github.com/sleukhin/serverless-next.js/commit/f60ff4ab33d6b710a53291803b19244e1cef5adc))

# [3.5.0-alpha.3](https://github.com/sleukhin/serverless-next.js/compare/v3.5.0-alpha.2...v3.5.0-alpha.3) (2021-10-16)

**Note:** Version bump only for package serverless-nextjs-monorepo

# [3.5.0-alpha.2](https://github.com/sleukhin/serverless-next.js/compare/v3.5.0-alpha.1...v3.5.0-alpha.2) (2021-10-16)

### Bug Fixes

- **aws-cloudfront:** handle bucket names with dots correctly ([#1844](https://github.com/sleukhin/serverless-next.js/issues/1844)) ([918a19e](https://github.com/sleukhin/serverless-next.js/commit/918a19e7834c49794706d9901a21605141ead99a))

# [3.5.0-alpha.1](https://github.com/sleukhin/serverless-next.js/compare/v3.5.0-alpha.0...v3.5.0-alpha.1) (2021-10-13)

### Bug Fixes

- **lambda-at-edge:** handle trailing slash index.html page in reconstructOriginalRequestUri ([#1832](https://github.com/sleukhin/serverless-next.js/issues/1832)) ([1926eb2](https://github.com/sleukhin/serverless-next.js/commit/1926eb20cb00a17763c4c79f3bdbef96d7181969))

# [3.5.0-alpha.0](https://github.com/sleukhin/serverless-next.js/compare/v3.4.0...v3.5.0-alpha.0) (2021-10-06)

### Features

- **core, lambda-at-edge:** handle Redirects in uncached SSG Requests ([#1786](https://github.com/sleukhin/serverless-next.js/issues/1786)) ([2a7cf73](https://github.com/sleukhin/serverless-next.js/commit/2a7cf738d1fab0e73b5a39c2702e721af4884e29))

# [3.4.0](https://github.com/sleukhin/serverless-next.js/compare/v3.4.0-alpha.14...v3.4.0) (2021-10-02)

**Note:** Version bump only for package serverless-nextjs-monorepo

# [3.4.0-alpha.14](https://github.com/sleukhin/serverless-next.js/compare/v3.4.0-alpha.13...v3.4.0-alpha.14) (2021-10-02)

**Note:** Version bump only for package serverless-nextjs-monorepo

# [3.4.0-alpha.13](https://github.com/sleukhin/serverless-next.js/compare/v3.4.0-alpha.12...v3.4.0-alpha.13) (2021-09-28)

### Bug Fixes

- **nextjs-cdk-construct:** disable public read access of s3 bucket and allow all methods in default behavior ([#1758](https://github.com/sleukhin/serverless-next.js/issues/1758)) ([770641c](https://github.com/sleukhin/serverless-next.js/commit/770641cefabcfbc088f59979342f55d366991777))

# [3.4.0-alpha.12](https://github.com/sleukhin/serverless-next.js/compare/v3.4.0-alpha.11...v3.4.0-alpha.12) (2021-09-27)

### Features

- **nextjs-component, core, lambda-at-edge:** experimental - add build.useV2Handler option to enable using genericized default/regeneration handlers ([#1747](https://github.com/sleukhin/serverless-next.js/issues/1747)) ([afd8a79](https://github.com/sleukhin/serverless-next.js/commit/afd8a79a5a19adb631f627198a9e7d904bbf34c6))

# [3.4.0-alpha.11](https://github.com/sleukhin/serverless-next.js/compare/v3.4.0-alpha.10...v3.4.0-alpha.11) (2021-09-25)

### Bug Fixes

- **core:** handle external redirect destinations with query parameters correctly ([#1744](https://github.com/sleukhin/serverless-next.js/issues/1744)) ([58001fc](https://github.com/sleukhin/serverless-next.js/commit/58001fc993c432af0309ccbbe4541a6bd1d00d08))

# [3.4.0-alpha.10](https://github.com/sleukhin/serverless-next.js/compare/v3.4.0-alpha.9...v3.4.0-alpha.10) (2021-09-24)

### Bug Fixes

- **lambda-at-edge:** fix static regeneration while running in ISR mode [#1729](https://github.com/sleukhin/serverless-next.js/issues/1729) ([#1731](https://github.com/sleukhin/serverless-next.js/issues/1731)) ([b32c0e8](https://github.com/sleukhin/serverless-next.js/commit/b32c0e82128ce5356a8249cc5a4246cd480bd484))

# [3.4.0-alpha.9](https://github.com/sleukhin/serverless-next.js/compare/v3.4.0-alpha.8...v3.4.0-alpha.9) (2021-09-17)

### Features

- **core, lambda-at-edge, nextjs-component:** experimental - allow serving static pages/data from origin request handler only (and disable origin response handler) ([#1696](https://github.com/sleukhin/serverless-next.js/issues/1696)) ([7fcdc7f](https://github.com/sleukhin/serverless-next.js/commit/7fcdc7fd4970402c7f19e09a7fa90d22a82804e4))

# [3.4.0-alpha.8](https://github.com/sleukhin/serverless-next.js/compare/v3.4.0-alpha.7...v3.4.0-alpha.8) (2021-09-15)

### Features

- **core, nextjs-component:** improve routing and support cross rewrites for consolidated API pages in default lambda ([#1693](https://github.com/sleukhin/serverless-next.js/issues/1693)) ([f058d51](https://github.com/sleukhin/serverless-next.js/commit/f058d5111d8ba1bcb02cc81cd4d52b43fd4d52ee))

# [3.4.0-alpha.7](https://github.com/sleukhin/serverless-next.js/compare/v3.4.0-alpha.6...v3.4.0-alpha.7) (2021-09-15)

### Features

- **nextjs-component:** experimental - allow serving API pages from default lambda ([#1632](https://github.com/sleukhin/serverless-next.js/issues/1632)) ([b7fe7a9](https://github.com/sleukhin/serverless-next.js/commit/b7fe7a9f37ee33e09536f48690ea516d12151af6))

# [3.4.0-alpha.6](https://github.com/sleukhin/serverless-next.js/compare/v3.4.0-alpha.5...v3.4.0-alpha.6) (2021-09-13)

### Bug Fixes

- **core:** fallback to using page's html render function when html is empty ([#1680](https://github.com/sleukhin/serverless-next.js/issues/1680)) ([ef38698](https://github.com/sleukhin/serverless-next.js/commit/ef38698dff32778904df7902fb51952256f43bd4))

# [3.4.0-alpha.5](https://github.com/sleukhin/serverless-next.js/compare/v3.4.0-alpha.4...v3.4.0-alpha.5) (2021-09-09)

### Bug Fixes

- **nextjs-component:** serverless-patched binary should include @serverless/cli and find serverless binary in closest node_modules ([#1661](https://github.com/sleukhin/serverless-next.js/issues/1661)) ([d7057ba](https://github.com/sleukhin/serverless-next.js/commit/d7057ba966a5825f575dab01010ee9ad97ed2ff3))

# [3.4.0-alpha.4](https://github.com/sleukhin/serverless-next.js/compare/v3.4.0-alpha.3...v3.4.0-alpha.4) (2021-09-09)

### Features

- **nextjs-component:** forward common headers such as authorization and host by default ([#1660](https://github.com/sleukhin/serverless-next.js/issues/1660)) ([793f0a2](https://github.com/sleukhin/serverless-next.js/commit/793f0a205bc066c72b614c2821143c76d839500f))

# [3.4.0-alpha.3](https://github.com/sleukhin/serverless-next.js/compare/v3.4.0-alpha.2...v3.4.0-alpha.3) (2021-09-09)

### Bug Fixes

- **nextjs-component:** fix broken install since patch-package is required as dependency, not dev-dependency ([79af0e8](https://github.com/sleukhin/serverless-next.js/commit/79af0e80afe36a03d8383786237df2c31503fbf8))

# [3.4.0-alpha.2](https://github.com/sleukhin/serverless-next.js/compare/v3.4.0-alpha.1...v3.4.0-alpha.2) (2021-09-09)

### Features

- **nextjs-component:** introduce serverless-patched binary ([#1658](https://github.com/sleukhin/serverless-next.js/issues/1658)) ([6ee24ca](https://github.com/sleukhin/serverless-next.js/commit/6ee24ca4e48db799dec8fe80873a03df25b84508))

# [3.4.0-alpha.1](https://github.com/sleukhin/serverless-next.js/compare/v3.4.0-alpha.0...v3.4.0-alpha.1) (2021-09-08)

### Bug Fixes

- **lambda-at-edge:** copy next-i18next files to regeneration handler ([#1653](https://github.com/sleukhin/serverless-next.js/issues/1653)) ([1c14f38](https://github.com/sleukhin/serverless-next.js/commit/1c14f38a8991824730574b93aff779ec42a892ef))

### Features

- **core:** add domain locale detection for rewrites and non default locales ([#1640](https://github.com/sleukhin/serverless-next.js/issues/1640)) ([#1641](https://github.com/sleukhin/serverless-next.js/issues/1641)) ([cbab741](https://github.com/sleukhin/serverless-next.js/commit/cbab7419e8bddfbde8b97104d0229307fc5694d8))

# [3.4.0-alpha.0](https://github.com/sleukhin/serverless-next.js/compare/v3.3.1-alpha.1...v3.4.0-alpha.0) (2021-09-03)

### Features

- **nextjs-component:** allow other path patterns in cloudfront inputs ([#1631](https://github.com/sleukhin/serverless-next.js/issues/1631)) ([c97808f](https://github.com/sleukhin/serverless-next.js/commit/c97808f1d85a1f048e83c5ad7e95b25b826cf418))

## [3.3.1-alpha.1](https://github.com/sleukhin/serverless-next.js/compare/v3.3.1-alpha.0...v3.3.1-alpha.1) (2021-09-02)

### Bug Fixes

- **lambda-at-edge, e2e-tests:** fix and add e2e tests for ISR pages when locales are used ([#1622](https://github.com/sleukhin/serverless-next.js/issues/1622)) ([6acc057](https://github.com/sleukhin/serverless-next.js/commit/6acc057aad85b4caab1e2f71db8f8a90b3b54fc1))

## [3.3.1-alpha.0](https://github.com/sleukhin/serverless-next.js/compare/v3.3.0...v3.3.1-alpha.0) (2021-09-02)

### Bug Fixes

- **lambda-at-edge:** sqs messageGroupId should be a hash to allow for long URIs ([#1621](https://github.com/sleukhin/serverless-next.js/issues/1621)) ([1b758c8](https://github.com/sleukhin/serverless-next.js/commit/1b758c87dfa2059aa13a94c730c5bd5fb24fae1a))

# [3.3.0](https://github.com/sleukhin/serverless-next.js/compare/v3.3.0-alpha.6...v3.3.0) (2021-09-01)

**Note:** Version bump only for package serverless-nextjs-monorepo

# [3.3.0-alpha.6](https://github.com/sleukhin/serverless-next.js/compare/v3.3.0-alpha.5...v3.3.0-alpha.6) (2021-08-31)

### Bug Fixes

- **core:** fix renderPageToHtml for work for all next.js versions ([#1611](https://github.com/sleukhin/serverless-next.js/issues/1611)) ([d3a10b2](https://github.com/sleukhin/serverless-next.js/commit/d3a10b2d7ed9d14afd1a09436f9fbf911fde001e))

# [3.3.0-alpha.5](https://github.com/sleukhin/serverless-next.js/compare/v3.3.0-alpha.4...v3.3.0-alpha.5) (2021-08-27)

### Bug Fixes

- **core, lambda-at-edge:** render page to HTML properly for next.js 11.1+ versions ([#1596](https://github.com/sleukhin/serverless-next.js/issues/1596)) ([ee88a68](https://github.com/sleukhin/serverless-next.js/commit/ee88a683792b972760067821e21f78654562c1ec))

# [3.3.0-alpha.4](https://github.com/sleukhin/serverless-next.js/compare/v3.3.0-alpha.3...v3.3.0-alpha.4) (2021-08-26)

### Bug Fixes

- **lambda-at-edge, nextjs-component:** fix triggering regeneration when sqs queue has custom name ([#1595](https://github.com/sleukhin/serverless-next.js/issues/1595)) ([396b8dc](https://github.com/sleukhin/serverless-next.js/commit/396b8dc0a09a8372f339c1cef49a601155008c94))

# [3.3.0-alpha.3](https://github.com/sleukhin/serverless-next.js/compare/v3.3.0-alpha.2...v3.3.0-alpha.3) (2021-08-25)

### Bug Fixes

- **core:** fix preview mode with a dynamic route is used ([#1585](https://github.com/sleukhin/serverless-next.js/issues/1585)) ([316bd2a](https://github.com/sleukhin/serverless-next.js/commit/316bd2a348f726bf8fc116b8b759acd9103d5037)), closes [#1527](https://github.com/sleukhin/serverless-next.js/issues/1527)
- **lambda-at-edge:** fix ISR issue with index.ts ([#1563](https://github.com/sleukhin/serverless-next.js/issues/1563)) ([d327ddf](https://github.com/sleukhin/serverless-next.js/commit/d327ddf1f6d3d662cd6efd6a99aec976a430696d))
- **nextjs-component:** add webpack dependency ([3aa0b6d](https://github.com/sleukhin/serverless-next.js/commit/3aa0b6d097bbdc5b978c1bff73db671e082c61a8))

# [3.3.0-alpha.2](https://github.com/sleukhin/serverless-next.js/compare/v3.3.0-alpha.1...v3.3.0-alpha.2) (2021-08-21)

### Bug Fixes

- **nextjs-component:** do not allow same name to be specified across all lambdas([#1569](https://github.com/sleukhin/serverless-next.js/issues/1569)) ([d7efc6c](https://github.com/sleukhin/serverless-next.js/commit/d7efc6c5f4269884555409f0822ec9c1144868a6))

# [3.3.0-alpha.1](https://github.com/sleukhin/serverless-next.js/compare/v3.3.0-alpha.0...v3.3.0-alpha.1) (2021-08-21)

### Bug Fixes

- **aws-cloudfront:** set tags when creating distribution ([#1562](https://github.com/sleukhin/serverless-next.js/issues/1562)) ([e5ddcf5](https://github.com/sleukhin/serverless-next.js/commit/e5ddcf51bdaa35ea9d7756807b5674e14614bab9))

# [3.3.0-alpha.0](https://github.com/sleukhin/serverless-next.js/compare/v3.2.1-alpha.0...v3.3.0-alpha.0) (2021-08-19)

### Features

- **aws-sqs:** support sqs tags/naming ([#1543](https://github.com/sleukhin/serverless-next.js/issues/1543)) ([7bf2c67](https://github.com/sleukhin/serverless-next.js/commit/7bf2c67e2ad9cf188284c9eb160f9a5251bb5fc2))
- **CI:** add cache to ci workflow ([#1512](https://github.com/sleukhin/serverless-next.js/issues/1512)) ([25351dc](https://github.com/sleukhin/serverless-next.js/commit/25351dcfef9c83c8b8e7acca9809089f53e85743))

## [3.2.1-alpha.0](https://github.com/sleukhin/serverless-next.js/compare/v3.2.0...v3.2.1-alpha.0) (2021-08-04)

### Bug Fixes

- **core:** allow lowercase locale prefixes by standardizing locale casing on server-side, update locale redirect casing ([#1496](https://github.com/sleukhin/serverless-next.js/issues/1496)) ([a8765d1](https://github.com/sleukhin/serverless-next.js/commit/a8765d1ff0e34b2e8d5f185e3aea84afed59b009))

# [3.2.0](https://github.com/sleukhin/serverless-next.js/compare/v3.2.0-alpha.29...v3.2.0) (2021-08-03)

**Note:** Version bump only for package serverless-nextjs-monorepo

# [3.2.0-alpha.29](https://github.com/sleukhin/serverless-next.js/compare/v3.2.0-alpha.28...v3.2.0-alpha.29) (2021-08-03)

### Bug Fixes

- **nextjs-component:** allow setting custom regeneration lambda name ([#1491](https://github.com/sleukhin/serverless-next.js/issues/1491)) ([b1b3534](https://github.com/sleukhin/serverless-next.js/commit/b1b35345eea821a2e068a1a02a06ddf3f8c00f4d))

# [3.2.0-alpha.28](https://github.com/sleukhin/serverless-next.js/compare/v3.2.0-alpha.27...v3.2.0-alpha.28) (2021-08-03)

### Bug Fixes

- **nextjs-component, nextjs-cdk-construct:** create AWS resources for dynamic SSG ([#1476](https://github.com/sleukhin/serverless-next.js/issues/1476)) ([#1477](https://github.com/sleukhin/serverless-next.js/issues/1477)) ([7e9c923](https://github.com/sleukhin/serverless-next.js/commit/7e9c923d62c1573fa6fca51f6d62854297d0d09d))

# [3.2.0-alpha.27](https://github.com/sleukhin/serverless-next.js/compare/v3.2.0-alpha.26...v3.2.0-alpha.27) (2021-08-02)

### Features

- **lambda-at-edge:** couple build-related changes: ([#1485](https://github.com/sleukhin/serverless-next.js/issues/1485)) ([a863dbf](https://github.com/sleukhin/serverless-next.js/commit/a863dbf8b251818f3c2efc74af0634bf84d099cb))

# [3.2.0-alpha.26](https://github.com/sleukhin/serverless-next.js/compare/v3.2.0-alpha.25...v3.2.0-alpha.26) (2021-08-02)

### Bug Fixes

- **lambda-at-edge:** handle 404 status code returned by S3 in origin response handler ([#1487](https://github.com/sleukhin/serverless-next.js/issues/1487)) ([6a3c5b0](https://github.com/sleukhin/serverless-next.js/commit/6a3c5b0d657cff2ca40af87772122d8fade5d4f8))

# [3.2.0-alpha.25](https://github.com/sleukhin/serverless-next.js/compare/v3.2.0-alpha.24...v3.2.0-alpha.25) (2021-08-02)

### Bug Fixes

- **core:** locale redirect should not be lowercased ([#1484](https://github.com/sleukhin/serverless-next.js/issues/1484)) ([f4ea8f5](https://github.com/sleukhin/serverless-next.js/commit/f4ea8f58c2d104b287d7e5342cbf794bd6689f31))

# [3.2.0-alpha.24](https://github.com/sleukhin/serverless-next.js/compare/v3.2.0-alpha.23...v3.2.0-alpha.24) (2021-07-31)

### Bug Fixes

- **s3-static-assets:** ensure fast-glob is reading dot entries when f… ([#1475](https://github.com/sleukhin/serverless-next.js/issues/1475)) ([efb3c93](https://github.com/sleukhin/serverless-next.js/commit/efb3c93b527fc480c08ec1af5923bc159810926b))

# [3.2.0-alpha.23](https://github.com/sleukhin/serverless-next.js/compare/v3.2.0-alpha.22...v3.2.0-alpha.23) (2021-07-31)

### Bug Fixes

- **core, lambda-at-edge:** do not replace .html for public files in r… ([#1473](https://github.com/sleukhin/serverless-next.js/issues/1473)) ([62c0fe2](https://github.com/sleukhin/serverless-next.js/commit/62c0fe2e0c9d6341831d496bf143369d8df0a93e))

# [3.2.0-alpha.22](https://github.com/sleukhin/serverless-next.js/compare/v3.2.0-alpha.21...v3.2.0-alpha.22) (2021-07-31)

### Features

- **lambda-at-edge:** detect and copy next-i18next files ([#1472](https://github.com/sleukhin/serverless-next.js/issues/1472)) ([3ffc938](https://github.com/sleukhin/serverless-next.js/commit/3ffc938ee463866692b1b5919566d9ea18438693))

# [3.2.0-alpha.21](https://github.com/sleukhin/serverless-next.js/compare/v3.2.0-alpha.20...v3.2.0-alpha.21) (2021-07-27)

### Bug Fixes

- **aws-lambda:** fix test failure due to init() ([cde5af9](https://github.com/sleukhin/serverless-next.js/commit/cde5af9e730f730eea6d074d440d37d2b00a379f))

### Features

- **aws-cloudfront:** add support for custom headers in custom origins ([#1448](https://github.com/sleukhin/serverless-next.js/issues/1448)) ([dd2fa6e](https://github.com/sleukhin/serverless-next.js/commit/dd2fa6e60180a71bc96bcf5325647414bc9e74cb))

# [3.2.0-alpha.20](https://github.com/sleukhin/serverless-next.js/compare/v3.2.0-alpha.19...v3.2.0-alpha.20) (2021-07-09)

### Bug Fixes

- **lambda-at-edge:** fix reconstruction of basepath index uri ([#1398](https://github.com/sleukhin/serverless-next.js/issues/1398)) ([3483a48](https://github.com/sleukhin/serverless-next.js/commit/3483a48a0341fd0ba882b5b58a4571ea96f6d238))

# [3.2.0-alpha.19](https://github.com/sleukhin/serverless-next.js/compare/v3.2.0-alpha.18...v3.2.0-alpha.19) (2021-07-09)

### Bug Fixes

- **lambda-at-edge:** fix extraction of s3 bucket name ([#1382](https://github.com/sleukhin/serverless-next.js/issues/1382)) ([72df9ad](https://github.com/sleukhin/serverless-next.js/commit/72df9add8585727b278279bc0c5f9be8ad27cd7d))

# [3.2.0-alpha.18](https://github.com/sleukhin/serverless-next.js/compare/v3.2.0-alpha.17...v3.2.0-alpha.18) (2021-07-08)

**Note:** Version bump only for package serverless-nextjs-monorepo

# [3.2.0-alpha.17](https://github.com/sleukhin/serverless-next.js/compare/v3.2.0-alpha.16...v3.2.0-alpha.17) (2021-07-07)

**Note:** Version bump only for package serverless-nextjs-monorepo

# [3.2.0-alpha.16](https://github.com/sleukhin/serverless-next.js/compare/v3.2.0-alpha.15...v3.2.0-alpha.16) (2021-07-03)

### Bug Fixes

- **aws-cloudfront:** fix cloudfront origin merging ([623c168](https://github.com/sleukhin/serverless-next.js/commit/623c1684c41995341a5543de9f0e802bbd864b0e))

# [3.2.0-alpha.15](https://github.com/sleukhin/serverless-next.js/compare/v3.2.0-alpha.14...v3.2.0-alpha.15) (2021-07-02)

### Features

- **aws-cloudfront:** allow configurable trustedSigners ([#1351](https://github.com/sleukhin/serverless-next.js/issues/1351)) ([5ee78a6](https://github.com/sleukhin/serverless-next.js/commit/5ee78a682497ee21fcd65057661f938e9de813f1))

# [3.2.0-alpha.14](https://github.com/sleukhin/serverless-next.js/compare/v3.2.0-alpha.13...v3.2.0-alpha.14) (2021-07-02)

### Features

- **aws-cloudfront, nextjs-component:** support cloudfront tags ([#1350](https://github.com/sleukhin/serverless-next.js/issues/1350)) ([b5d03b1](https://github.com/sleukhin/serverless-next.js/commit/b5d03b1dce9851c31d3dca144c66ae32f83060c0))

# [3.2.0-alpha.13](https://github.com/sleukhin/serverless-next.js/compare/v3.2.0-alpha.12...v3.2.0-alpha.13) (2021-07-02)

**Note:** Version bump only for package serverless-nextjs-monorepo

# [3.2.0-alpha.12](https://github.com/sleukhin/serverless-next.js/compare/v3.2.0-alpha.11...v3.2.0-alpha.12) (2021-07-01)

**Note:** Version bump only for package serverless-nextjs-monorepo

# [3.2.0-alpha.11](https://github.com/sleukhin/serverless-next.js/compare/v3.2.0-alpha.10...v3.2.0-alpha.11) (2021-06-30)

### Bug Fixes

- **core:** support no-op rewrites ([#1329](https://github.com/sleukhin/serverless-next.js/issues/1329)) ([27d1943](https://github.com/sleukhin/serverless-next.js/commit/27d1943f2d193eecba7c8cb99d33ffcccb463e41))

# [3.2.0-alpha.10](https://github.com/sleukhin/serverless-next.js/compare/v3.2.0-alpha.9...v3.2.0-alpha.10) (2021-06-29)

### Features

- **aws-s3, nextjs-component:** support s3 bucket tags ([#1326](https://github.com/sleukhin/serverless-next.js/issues/1326)) ([c924c22](https://github.com/sleukhin/serverless-next.js/commit/c924c222f64ed2056e314aaedfa99449831a55cd))

# [3.2.0-alpha.9](https://github.com/sleukhin/serverless-next.js/compare/v3.2.0-alpha.8...v3.2.0-alpha.9) (2021-06-29)

**Note:** Version bump only for package serverless-nextjs-monorepo

# [3.2.0-alpha.8](https://github.com/sleukhin/serverless-next.js/compare/v3.2.0-alpha.7...v3.2.0-alpha.8) (2021-06-28)

### Bug Fixes

- **lambda-at-edge:** properly copy node_modules in serverless-trace mode for regeneration lambda ([#1319](https://github.com/sleukhin/serverless-next.js/issues/1319)) ([0eee571](https://github.com/sleukhin/serverless-next.js/commit/0eee571549e85f66bdc3bed0c907c36d03332fa3))

# [3.2.0-alpha.7](https://github.com/sleukhin/serverless-next.js/compare/v3.2.0-alpha.6...v3.2.0-alpha.7) (2021-06-28)

### Features

- **core:** support locale-based domain redirects [wip] ([#1299](https://github.com/sleukhin/serverless-next.js/issues/1299)) ([5836142](https://github.com/sleukhin/serverless-next.js/commit/58361424be8e6f4fcfa69f6b5956d3cf1b55cd97))

# [3.2.0-alpha.6](https://github.com/sleukhin/serverless-next.js/compare/v3.2.0-alpha.5...v3.2.0-alpha.6) (2021-06-27)

**Note:** Version bump only for package serverless-nextjs-monorepo

# [3.2.0-alpha.5](https://github.com/sleukhin/serverless-next.js/compare/v3.2.0-alpha.4...v3.2.0-alpha.5) (2021-06-27)

**Note:** Version bump only for package serverless-nextjs-monorepo

# [3.2.0-alpha.4](https://github.com/sleukhin/serverless-next.js/compare/v3.2.0-alpha.3...v3.2.0-alpha.4) (2021-06-27)

### Bug Fixes

- update aws retry logic and fix dependencies ([#1306](https://github.com/sleukhin/serverless-next.js/issues/1306)) ([e0cee9c](https://github.com/sleukhin/serverless-next.js/commit/e0cee9c0d5d79314a7239c37e55438b5200d8bb2))

# [3.2.0-alpha.3](https://github.com/sleukhin/serverless-next.js/compare/v3.2.0-alpha.2...v3.2.0-alpha.3) (2021-06-27)

**Note:** Version bump only for package serverless-nextjs-monorepo

# [3.2.0-alpha.2](https://github.com/sleukhin/serverless-next.js/compare/v3.2.0-alpha.1...v3.2.0-alpha.2) (2021-06-26)

**Note:** Version bump only for package serverless-nextjs-monorepo

# [3.2.0-alpha.1](https://github.com/sleukhin/serverless-next.js/compare/v3.2.0-alpha.0...v3.2.0-alpha.1) (2021-06-26)

### Features

- **nextjs-component:** update default runtime to nodejs14.x ([#1301](https://github.com/sleukhin/serverless-next.js/issues/1301)) ([52b902f](https://github.com/sleukhin/serverless-next.js/commit/52b902f6035992d14ddd05195ffa1f35505bc7d6))

# [3.2.0-alpha.0](https://github.com/sleukhin/serverless-next.js/compare/v3.1.1-alpha.0...v3.2.0-alpha.0) (2021-06-26)

### Features

- **nextjs-component, aws-lambda:** support adding tags to lambdas ([#1300](https://github.com/sleukhin/serverless-next.js/issues/1300)) ([74721c2](https://github.com/sleukhin/serverless-next.js/commit/74721c28097ec3bb4227ad50e9d9c3db48848fb8))

## [3.1.1-alpha.0](https://github.com/sleukhin/serverless-next.js/compare/v3.1.0...v3.1.1-alpha.0) (2021-06-26)

### Bug Fixes

- **core:** add s-maxage=0 cache-control headers to redirect responses ([#1298](https://github.com/sleukhin/serverless-next.js/issues/1298)) ([6220078](https://github.com/sleukhin/serverless-next.js/commit/6220078cedac2c56ed0c314e0416890fab4aa891))

# [3.1.0](https://github.com/sleukhin/serverless-next.js/compare/v3.1.0-alpha.16...v3.1.0) (2021-06-25)

**Note:** Version bump only for package serverless-nextjs-monorepo

# [3.1.0-alpha.16](https://github.com/sleukhin/serverless-next.js/compare/v3.1.0-alpha.15...v3.1.0-alpha.16) (2021-06-25)

### Features

- **core:** add domain locale detection ([#1283](https://github.com/sleukhin/serverless-next.js/issues/1283)) ([#1296](https://github.com/sleukhin/serverless-next.js/issues/1296)) ([b331695](https://github.com/sleukhin/serverless-next.js/commit/b33169526eb30aeffd5f1b95a781709019f00248))

# [3.1.0-alpha.15](https://github.com/sleukhin/serverless-next.js/compare/v3.1.0-alpha.14...v3.1.0-alpha.15) (2021-06-25)

**Note:** Version bump only for package serverless-nextjs-monorepo

# [3.1.0-alpha.14](https://github.com/sleukhin/serverless-next.js/compare/v3.1.0-alpha.13...v3.1.0-alpha.14) (2021-06-24)

### Bug Fixes

- **core, e2e-tests:** fix ISR, make e2e tests retryable ([#1290](https://github.com/sleukhin/serverless-next.js/issues/1290)) ([83d19f0](https://github.com/sleukhin/serverless-next.js/commit/83d19f0b607441a76746fa8cf4dacddd52d8b20a))

# [3.1.0-alpha.13](https://github.com/sleukhin/serverless-next.js/compare/v3.1.0-alpha.12...v3.1.0-alpha.13) (2021-06-24)

**Note:** Version bump only for package serverless-nextjs-monorepo

# [3.1.0-alpha.12](https://github.com/sleukhin/serverless-next.js/compare/v3.1.0-alpha.11...v3.1.0-alpha.12) (2021-06-23)

### Bug Fixes

- **lambda-at-edge:** handle /\_next/static image requests and minor improvements to image error logging ([#1288](https://github.com/sleukhin/serverless-next.js/issues/1288)) ([b64effe](https://github.com/sleukhin/serverless-next.js/commit/b64effedaecfbe789ad7134b4bcba0c57b17019b))
- **lambda-at-edge:** improve error logging when s3 fails in image optimizer ([#1287](https://github.com/sleukhin/serverless-next.js/issues/1287)) ([9af3a37](https://github.com/sleukhin/serverless-next.js/commit/9af3a37352ee704424dd90691b3832e9cf8b721c))

# [3.1.0-alpha.11](https://github.com/sleukhin/serverless-next.js/compare/v3.1.0-alpha.10...v3.1.0-alpha.11) (2021-06-23)

### Bug Fixes

- **nextjs-component, cloudfront:** wait for distribution to be ready before creating invalidations ([#1281](https://github.com/sleukhin/serverless-next.js/issues/1281)) ([3091c7c](https://github.com/sleukhin/serverless-next.js/commit/3091c7c634986121c4943931c7ffd6303732c957))

# [3.1.0-alpha.10](https://github.com/sleukhin/serverless-next.js/compare/v3.1.0-alpha.9...v3.1.0-alpha.10) (2021-06-22)

**Note:** Version bump only for package serverless-nextjs-monorepo

# [3.1.0-alpha.9](https://github.com/sleukhin/serverless-next.js/compare/v3.1.0-alpha.8...v3.1.0-alpha.9) (2021-06-22)

### Bug Fixes

- **s3-static-assets:** cover regional cn endpoints ([#1279](https://github.com/sleukhin/serverless-next.js/issues/1279)) ([a47b761](https://github.com/sleukhin/serverless-next.js/commit/a47b7613d9b084f6f1aaff266648f91a631abe04))

# [3.1.0-alpha.8](https://github.com/sleukhin/serverless-next.js/compare/v3.1.0-alpha.7...v3.1.0-alpha.8) (2021-06-22)

### Bug Fixes

- **lambda-at-edge:** fix reconstruction of uri for "index.html" -> "/" instead of "/index" in origin response handler ([#1278](https://github.com/sleukhin/serverless-next.js/issues/1278)) ([48d6735](https://github.com/sleukhin/serverless-next.js/commit/48d6735c5c298fa2575f34860072388c1cf16d89))

# [3.1.0-alpha.7](https://github.com/sleukhin/serverless-next.js/compare/v3.1.0-alpha.6...v3.1.0-alpha.7) (2021-06-22)

### Bug Fixes

- **lambda-at-edge, nextjs-component:** add option to disable cleaning up .next directory before builds ([#1273](https://github.com/sleukhin/serverless-next.js/issues/1273)) ([51bffdd](https://github.com/sleukhin/serverless-next.js/commit/51bffdd1511d68377148534020d28513a3fda4cd))

# [3.1.0-alpha.6](https://github.com/sleukhin/serverless-next.js/compare/v3.1.0-alpha.5...v3.1.0-alpha.6) (2021-06-21)

### Bug Fixes

- **core:** fix data route locales ([#1268](https://github.com/sleukhin/serverless-next.js/issues/1268)) ([e1c8cd8](https://github.com/sleukhin/serverless-next.js/commit/e1c8cd8e5cc36a20ec4363911a501f232f51bd04))

# [3.1.0-alpha.5](https://github.com/sleukhin/serverless-next.js/compare/v3.1.0-alpha.4...v3.1.0-alpha.5) (2021-06-19)

### Bug Fixes

- **s3-static-assets:** use regional endpoint for s3 buckets ([#1263](https://github.com/sleukhin/serverless-next.js/issues/1263)) ([3a1d5d5](https://github.com/sleukhin/serverless-next.js/commit/3a1d5d569f36759c1e709f31cbb98060abd1957a))

# [3.1.0-alpha.4](https://github.com/sleukhin/serverless-next.js/compare/v3.1.0-alpha.3...v3.1.0-alpha.4) (2021-06-18)

### Bug Fixes

- **s3-static-assets:** when initializing s3 client, pass in bucket region to ensure correct s3 endpoints ([#1262](https://github.com/sleukhin/serverless-next.js/issues/1262)) ([83805bb](https://github.com/sleukhin/serverless-next.js/commit/83805bb56d824ff3777e3da6591078ffd7053f48))

# [3.1.0-alpha.3](https://github.com/sleukhin/serverless-next.js/compare/v3.1.0-alpha.2...v3.1.0-alpha.3) (2021-06-18)

**Note:** Version bump only for package serverless-nextjs-monorepo

# [3.1.0-alpha.2](https://github.com/sleukhin/serverless-next.js/compare/v3.1.0-alpha.1...v3.1.0-alpha.2) (2021-06-18)

### Bug Fixes

- **nextjs-component:** fix aws config update ([#1248](https://github.com/sleukhin/serverless-next.js/issues/1248)) ([eae2f4e](https://github.com/sleukhin/serverless-next.js/commit/eae2f4e4030006135b0e62ac880997307f499a03))

# [3.1.0-alpha.1](https://github.com/sleukhin/serverless-next.js/compare/v3.1.0-alpha.0...v3.1.0-alpha.1) (2021-06-17)

### Bug Fixes

- tweak aws retry policy ([#1247](https://github.com/sleukhin/serverless-next.js/issues/1247)) ([00e5730](https://github.com/sleukhin/serverless-next.js/commit/00e57300b78e4b628d65f002dbf018760cf38763))

# [3.1.0-alpha.0](https://github.com/sleukhin/serverless-next.js/compare/v2.3.4...v3.1.0-alpha.0) (2021-06-17)

### Bug Fixes

- **aws-cloudfront:** add 200 status code to custom error pages ([#774](https://github.com/sleukhin/serverless-next.js/issues/774)) ([bc17565](https://github.com/sleukhin/serverless-next.js/commit/bc17565f60eaef21985ffa0352f375e6faa5f806))
- **cdk:** resources should not be assigned names ([#912](https://github.com/sleukhin/serverless-next.js/issues/912)) ([81d9d18](https://github.com/sleukhin/serverless-next.js/commit/81d9d18f0bd82c36be47c4bda8fa51d1b7e422b0))
- **cdk-construct:** [#943](https://github.com/sleukhin/serverless-next.js/issues/943) give access to underlying resources and enable custom s3 props ([#955](https://github.com/sleukhin/serverless-next.js/issues/955)) ([026901b](https://github.com/sleukhin/serverless-next.js/commit/026901b1b5008d11e35de0f710c484e60941ef08))
- **cdk-construct:** fix build error in cdk-construct ([d708265](https://github.com/sleukhin/serverless-next.js/commit/d708265ddda808f7340e1257390097e8c1f2663d))
- **cdk-construct:** unique construct id for each domain name ([#1013](https://github.com/sleukhin/serverless-next.js/issues/1013)) ([19ec092](https://github.com/sleukhin/serverless-next.js/commit/19ec0928723d5611be839b2daf5df827cf9dcbd4))
- **core:** add logging of path when pathToRegexStr fails ([#1082](https://github.com/sleukhin/serverless-next.js/issues/1082)) ([31cc4b1](https://github.com/sleukhin/serverless-next.js/commit/31cc4b15eace8797c2d4f8595122a03b077bd7d1))
- **core:** check for explicitly disabled locale detection ([#1129](https://github.com/sleukhin/serverless-next.js/issues/1129)) ([0a39211](https://github.com/sleukhin/serverless-next.js/commit/0a3921159513a927c5f8606e8550c12a5641396f))
- **core:** data request page JS path should use the one from the manifest ([#1241](https://github.com/sleukhin/serverless-next.js/issues/1241)) ([f774a30](https://github.com/sleukhin/serverless-next.js/commit/f774a30e1fa07d7f0d755106c68b50442d0c0d7f))
- **core:** extend locale matching to secondary languages ([#1040](https://github.com/sleukhin/serverless-next.js/issues/1040)) ([a2c476c](https://github.com/sleukhin/serverless-next.js/commit/a2c476cb923b3a2a382541c7ff9327c0861bfd1c))
- **core:** fix accept language redirect condition ([#1110](https://github.com/sleukhin/serverless-next.js/issues/1110)) ([f05ccbc](https://github.com/sleukhin/serverless-next.js/commit/f05ccbcbb8e57c6281d542fea20ff9b4b5d5efa7))
- **core:** fix infinite redirects on NEXT_LOCALE cookie ([#1128](https://github.com/sleukhin/serverless-next.js/issues/1128)) ([01d4d88](https://github.com/sleukhin/serverless-next.js/commit/01d4d88afe2ca4e164ce12e5ac8ea2b75dbfe96c))
- **core:** redirect based on NEXT_LOCALE cookie and add e2e test for … ([#1116](https://github.com/sleukhin/serverless-next.js/issues/1116)) ([48773f4](https://github.com/sleukhin/serverless-next.js/commit/48773f4fd1aa13896981b7ce3c9462d8429e6f86))
- **core:** use JS page path from manifest instead of manually constru… ([#1238](https://github.com/sleukhin/serverless-next.js/issues/1238)) ([cac8918](https://github.com/sleukhin/serverless-next.js/commit/cac89183546770363a56f0ad61ae6834ff5e4310))
- **core, lambda-at-edge:** fix page inclusion logic in default-handler build ([#1126](https://github.com/sleukhin/serverless-next.js/issues/1126)) ([5fdf3fe](https://github.com/sleukhin/serverless-next.js/commit/5fdf3fe04146e60a01681b0bfe21c1147fea6fd4))
- **core, lambda-at-edge:** set error status codes in core, refactor error handling ([#1153](https://github.com/sleukhin/serverless-next.js/issues/1153)) ([6d4ae93](https://github.com/sleukhin/serverless-next.js/commit/6d4ae936d64d0dda1d4b077ddc402b6f1afae88b))
- **core, lambda-at-edge:** support static 500 page and localized stat… ([#1135](https://github.com/sleukhin/serverless-next.js/issues/1135)) ([c0573c1](https://github.com/sleukhin/serverless-next.js/commit/c0573c193e8a148277244ef93b4250f28b27f840))
- **core, lambda-at-edge, e2e-tests:** fix locale rewrites to dynamic ssr ([#1132](https://github.com/sleukhin/serverless-next.js/issues/1132)) ([91c1ddf](https://github.com/sleukhin/serverless-next.js/commit/91c1ddf91dd97abe70079b2dd2a3be4861b70208))
- **domain:** pass certificateArn to domain component ([#826](https://github.com/sleukhin/serverless-next.js/issues/826)) ([b7cf083](https://github.com/sleukhin/serverless-next.js/commit/b7cf0834c6bbfaa178f0836fd2c92b80c1182b46))
- **e2e-tests:** fix small issue causing running e2e tests only on windows ([448d663](https://github.com/sleukhin/serverless-next.js/commit/448d663cb47d40dffd3d8392b614eaf80af7d371))
- **lambda-at-edge:** add new defaults trailingSlash=true redirect regex formats to remove to prevent redirect loop ([#868](https://github.com/sleukhin/serverless-next.js/issues/868)) ([5dd836e](https://github.com/sleukhin/serverless-next.js/commit/5dd836e8277466543c927c4040ccc5ca4389dafc))
- **lambda-at-edge:** also copy chunks for the revalidate lambda ([#1099](https://github.com/sleukhin/serverless-next.js/issues/1099)) ([704b866](https://github.com/sleukhin/serverless-next.js/commit/704b8662d4820c83c848a09c8000d176265bf5eb))
- **lambda-at-edge:** await external API rewrite ([#1232](https://github.com/sleukhin/serverless-next.js/issues/1232)) ([9f777d7](https://github.com/sleukhin/serverless-next.js/commit/9f777d73eab583121d44a712c4ef18eecf784380))
- **lambda-at-edge:** copy js chunks from .next/serverless/chunks to api/default lambdas if present ([#1095](https://github.com/sleukhin/serverless-next.js/issues/1095)) ([f04fe34](https://github.com/sleukhin/serverless-next.js/commit/f04fe3419915fddb2c1c898922ade859b42acbcb))
- **lambda-at-edge:** do not follow redirect in fetch during rewrite ([#942](https://github.com/sleukhin/serverless-next.js/issues/942)) ([0383cf2](https://github.com/sleukhin/serverless-next.js/commit/0383cf20673cf354f24ce7d607a2d93193574e87))
- **lambda-at-edge:** downgrade @rollup/plugin-commonjs to 18.1.0 to fix bundling issue of decodeHTML functions in SQS client ([#1227](https://github.com/sleukhin/serverless-next.js/issues/1227)) ([5dc04e1](https://github.com/sleukhin/serverless-next.js/commit/5dc04e149a3404be22fa14c481a1fe11f437bbcd))
- **lambda-at-edge:** ensure dist/sharp_node_modules empty before copying ([#980](https://github.com/sleukhin/serverless-next.js/issues/980)) ([c43b2f8](https://github.com/sleukhin/serverless-next.js/commit/c43b2f86e0fb8923114bd71fb94545afd5861405))
- **lambda-at-edge:** external rewrites should use method, header, body from cloudfront request ([#864](https://github.com/sleukhin/serverless-next.js/issues/864)) ([f7dd42a](https://github.com/sleukhin/serverless-next.js/commit/f7dd42a4ece5dd69fe15747d76bc75756e56d43b))
- **lambda-at-edge:** fix dynamic vs. catch-all route precedence ([#974](https://github.com/sleukhin/serverless-next.js/issues/974)) ([2a3140a](https://github.com/sleukhin/serverless-next.js/commit/2a3140a7fc68d40840e65a1af85b79c8da9e3a31))
- **lambda-at-edge:** fix fallback (non-prerendered) SSG requests not … ([#800](https://github.com/sleukhin/serverless-next.js/issues/800)) ([29719f5](https://github.com/sleukhin/serverless-next.js/commit/29719f59e5468a2815ec87171a456e4dfff5ef35))
- **lambda-at-edge:** fix language detection ([#963](https://github.com/sleukhin/serverless-next.js/issues/963)) ([72d14e8](https://github.com/sleukhin/serverless-next.js/commit/72d14e82b9c1e210ae5a68d80ece6b1ae7228d1c))
- **lambda-at-edge:** fix locale rewrites, enable rewrite tests for lo… ([#916](https://github.com/sleukhin/serverless-next.js/issues/916)) ([6c34aa4](https://github.com/sleukhin/serverless-next.js/commit/6c34aa4711a38038280a7de9e47c6433e95bb396))
- **lambda-at-edge:** fix not found for public files with encoded characters in path ([#825](https://github.com/sleukhin/serverless-next.js/issues/825)) ([b63f199](https://github.com/sleukhin/serverless-next.js/commit/b63f199e1c80f018eab1b0efabc1b337088e0aa0))
- **lambda-at-edge:** fix redirect loop in Next 10.0.4 and up due to new internal redirect regexes ([#879](https://github.com/sleukhin/serverless-next.js/issues/879)) ([36e5716](https://github.com/sleukhin/serverless-next.js/commit/36e5716344efbc8ac163b5964b8139b811dad29e))
- **lambda-at-edge:** fix router path in fallback SSG ([#1026](https://github.com/sleukhin/serverless-next.js/issues/1026)) ([9772397](https://github.com/sleukhin/serverless-next.js/commit/9772397fb15c2cf87ee45797aa52c92cd6b6c485))
- **lambda-at-edge:** fix SSG fallback with basepath ([#992](https://github.com/sleukhin/serverless-next.js/issues/992)) ([dff598b](https://github.com/sleukhin/serverless-next.js/commit/dff598bfc26e6c56e95d87a6dbb7e6bdd19f4227))
- **lambda-at-edge:** fix vulnerability in trailing slash redirect ([#1018](https://github.com/sleukhin/serverless-next.js/issues/1018)) ([f31931c](https://github.com/sleukhin/serverless-next.js/commit/f31931c4903a1ae87092745beb42047597b4dcad))
- **lambda-at-edge:** handle prerender-manifest v3 locales properly ([#910](https://github.com/sleukhin/serverless-next.js/issues/910)) ([5200d74](https://github.com/sleukhin/serverless-next.js/commit/5200d74a0d6b33b746fbea1d69ea3f1653bd74ba))
- **lambda-at-edge:** handle preview request gracefully ([#780](https://github.com/sleukhin/serverless-next.js/issues/780)) ([93b36a7](https://github.com/sleukhin/serverless-next.js/commit/93b36a73a3cfd1426d8f252d663302299efb640f))
- **lambda-at-edge:** handle/merge query params in redirect/rewrite destinat… ([#816](https://github.com/sleukhin/serverless-next.js/issues/816)) ([cd03658](https://github.com/sleukhin/serverless-next.js/commit/cd03658191182207d09a2c1c132d60971aac572c))
- **lambda-at-edge:** include all build files in sharp package.json ([7256ab9](https://github.com/sleukhin/serverless-next.js/commit/7256ab9bbd090dc1503dfebf5c93fb0b3cb452bd))
- **lambda-at-edge:** include all vendor files in sharp package.json so npm publish will copy all vendor libs correctly ([#842](https://github.com/sleukhin/serverless-next.js/issues/842)) ([0f3c417](https://github.com/sleukhin/serverless-next.js/commit/0f3c41730752ee3423a47d8c06fe34f4fe7b29b8))
- **lambda-at-edge:** locale subpath bug fixes ([#888](https://github.com/sleukhin/serverless-next.js/issues/888)) ([f9a6787](https://github.com/sleukhin/serverless-next.js/commit/f9a6787ba5eea86aa1911163e11f5e6d488483ff))
- **lambda-at-edge:** minor fix to optional catch-all base route at root level ([#820](https://github.com/sleukhin/serverless-next.js/issues/820)) ([60cee0d](https://github.com/sleukhin/serverless-next.js/commit/60cee0d76b8593d38308e57f0feea02cb18905e1))
- **lambda-at-edge:** move uuid to be a dependency of lambda-at-edge to fix bundling issues ([b9d1395](https://github.com/sleukhin/serverless-next.js/commit/b9d13953b63bc67655890ffcf9f0ddcb8865508f))
- **lambda-at-edge:** pass body correctly into external rewrite ([#867](https://github.com/sleukhin/serverless-next.js/issues/867)) ([5fb175f](https://github.com/sleukhin/serverless-next.js/commit/5fb175fed515dec2ebcd7396f03f27a0114e73be))
- **lambda-at-edge:** remove blacklisted CloudFront headers before returning api/default/image handler response ([#923](https://github.com/sleukhin/serverless-next.js/issues/923)) ([3fcb59d](https://github.com/sleukhin/serverless-next.js/commit/3fcb59d72d91e4aba8eb01bef24f67a01c93272b))
- **lambda-at-edge:** remove uuid and use datetime milliseconds to fix bundling issue ([8e003ae](https://github.com/sleukhin/serverless-next.js/commit/8e003ae93e476ea95e05c13f340678348848af06))
- **lambda-at-edge:** render 404 SSR page when there is no static 404 page during fallback response ([9f430dc](https://github.com/sleukhin/serverless-next.js/commit/9f430dca6e88c7c99d560fbb78704de8a97acd16))
- **lambda-at-edge:** revert @rollup/plugin-node-resolve to v10 to fix bundling issue ([#1189](https://github.com/sleukhin/serverless-next.js/issues/1189)) ([74f8aef](https://github.com/sleukhin/serverless-next.js/commit/74f8aef06e45dbb70e02287e429e6e5dbbaa31bf))
- **lambda-at-edge:** try to copy all files in sharp_node_modules ([#841](https://github.com/sleukhin/serverless-next.js/issues/841)) ([9234c1a](https://github.com/sleukhin/serverless-next.js/commit/9234c1a980010745153218c2ffcd6f286ad32c11))
- **lambda-at-edge:** use 307 redirect for root -> locale URI instead … ([#886](https://github.com/sleukhin/serverless-next.js/issues/886)) ([98e963b](https://github.com/sleukhin/serverless-next.js/commit/98e963b614f4be708156aada08654e115e43dc69))
- **lambda-at-edge:** use posix relative path when determining JS files to exclude/include in default handler ([#1201](https://github.com/sleukhin/serverless-next.js/issues/1201)) ([3e74ff0](https://github.com/sleukhin/serverless-next.js/commit/3e74ff075ce71cf2f277aea7a482ecd496bd1a8c))
- **lambda-at-edge:** various 404 page fixes: ([#1001](https://github.com/sleukhin/serverless-next.js/issues/1001)) ([719f767](https://github.com/sleukhin/serverless-next.js/commit/719f767f504e5ecfc1a4be7b74daa2205acef6a1))
- **lambda-at-edge, e2e-test:** fixes for fallback and fallback e2e tests ([#997](https://github.com/sleukhin/serverless-next.js/issues/997)) ([aad8536](https://github.com/sleukhin/serverless-next.js/commit/aad8536f21cc45a9ddb33a48cb2750d6265a8de1))
- **lambda-at-edge, nextjs-cdk-construct:** fix several posix path normalizations ([313c600](https://github.com/sleukhin/serverless-next.js/commit/313c6004d009df23b8356e03d19466d9ea393eac))
- **nextjs-cdk-construct:** match dynamic route segments with square bracket ([#1235](https://github.com/sleukhin/serverless-next.js/issues/1235)) ([979a633](https://github.com/sleukhin/serverless-next.js/commit/979a633cf42e9896406216e351e209c88106b344))
- **nextjs-cdk-construct:** update default memory and timeout to be mo… ([#1167](https://github.com/sleukhin/serverless-next.js/issues/1167)) ([10a16b6](https://github.com/sleukhin/serverless-next.js/commit/10a16b6e16bf235feabdac71721d8c5c5b18a20a))
- **nextjs-cdk-construct:** use posix paths for s3 assets and invalidations ([#1025](https://github.com/sleukhin/serverless-next.js/issues/1025)) ([b8b4393](https://github.com/sleukhin/serverless-next.js/commit/b8b439348ffd4f8e526645801df101f715e53797))
- **nextjs-component:** allow custom cache behavior for \_next/image\* ([#1046](https://github.com/sleukhin/serverless-next.js/issues/1046)) ([a6325c2](https://github.com/sleukhin/serverless-next.js/commit/a6325c2462a1351eecb1c533d922767799d3f2f8))
- **nextjs-component:** allow specifying role arn for all lambdas ([#1125](https://github.com/sleukhin/serverless-next.js/issues/1125)) ([6496f26](https://github.com/sleukhin/serverless-next.js/commit/6496f2653638d7bd83f90a00f8d046ab2b38dc7d))
- **nextjs-component:** don't override \_next/image* and \_next/static/* origin request lambda with the default lambda ([#859](https://github.com/sleukhin/serverless-next.js/issues/859)) ([20e513c](https://github.com/sleukhin/serverless-next.js/commit/20e513cb736c1aada5dd670c13a366626a9d4f22))
- **nextjs-component:** fixes error when removing domain from cloudfront, cannot read property debug of undefined ([#793](https://github.com/sleukhin/serverless-next.js/issues/793)) ([aca72d9](https://github.com/sleukhin/serverless-next.js/commit/aca72d923eda9f2898c52aad5a315b41d2efdfe4))
- **nextjs-component:** image lambda role should also use inputs.roleArn if it exists ([#903](https://github.com/sleukhin/serverless-next.js/issues/903)) ([93f2562](https://github.com/sleukhin/serverless-next.js/commit/93f2562919827fed6881da5134fc695e4d992e0b))
- **nextjs-component:** sqs region should be same as regeneration lambda region (using s3 bucket region) ([#1155](https://github.com/sleukhin/serverless-next.js/issues/1155)) ([41b6be1](https://github.com/sleukhin/serverless-next.js/commit/41b6be1943bca70a1e2e6f919b5ee6fecc56389f))
- only delete the sqs queue if it already exists in the state ([#1147](https://github.com/sleukhin/serverless-next.js/issues/1147)) ([c072437](https://github.com/sleukhin/serverless-next.js/commit/c072437f6620d7e1f323355ebd108201c64ffdd7))
- **aws-cloudfront:** do not override aliases when not specified in serverless.yml inputs ([#704](https://github.com/sleukhin/serverless-next.js/issues/704)) ([2188d26](https://github.com/sleukhin/serverless-next.js/commit/2188d2628fb6f1c8f982acdb4ad99da1760d0cd7))
- **aws-cloudfront:** IncludeBody option only with viewer-request or origin-request ([#533](https://github.com/sleukhin/serverless-next.js/issues/533)) ([5c4b2c4](https://github.com/sleukhin/serverless-next.js/commit/5c4b2c47ae235014dc723bf0515f3d025c67d726))
- **aws-cloudfront, nextjs-component:** fix aliases updating when domain is used ([#731](https://github.com/sleukhin/serverless-next.js/issues/731)) ([d41a6a9](https://github.com/sleukhin/serverless-next.js/commit/d41a6a919c2427e8feb104bde0cde18b315d2da0))
- **aws-cloudfront, nextjs-component:** fix inability to set cloudfront comment input ([#695](https://github.com/sleukhin/serverless-next.js/issues/695)) ([6803378](https://github.com/sleukhin/serverless-next.js/commit/68033783a407ba58b48b08664fcc52430a70010b))
- **domain, nextjs-component:** set aliases correctly with domainType of apex and domain starting with www ([#723](https://github.com/sleukhin/serverless-next.js/issues/723)) ([c68a4fc](https://github.com/sleukhin/serverless-next.js/commit/c68a4fccfdf755db3e857fdfa5049a2fe63bd58b))
- **lambda-at-edge:** add retries for s3 calls ([#720](https://github.com/sleukhin/serverless-next.js/issues/720)) ([72252fc](https://github.com/sleukhin/serverless-next.js/commit/72252fc08dbc90a7c487cbceb5d61a696594676c))
- **lambda-at-edge:** don't rewrite data requests ([#719](https://github.com/sleukhin/serverless-next.js/issues/719)) ([5b6f848](https://github.com/sleukhin/serverless-next.js/commit/5b6f84891724c7d2b83d8ee6c2708bb3874f0ccd))
- **lambda-at-edge:** dont throw when no prev .next dir ([8dfd19d](https://github.com/sleukhin/serverless-next.js/commit/8dfd19dc3b479edd43862051de756e895b56c88e))
- **lambda-at-edge:** exclude prerender js files from default handler if no API routes are used ([#600](https://github.com/sleukhin/serverless-next.js/issues/600)) ([73d0f48](https://github.com/sleukhin/serverless-next.js/commit/73d0f4821212ae7b3d0a46d3ca34fef6425277ab))
- **lambda-at-edge:** explicitly set host header for s3 origin ([#412](https://github.com/sleukhin/serverless-next.js/issues/412)) ([2f44795](https://github.com/sleukhin/serverless-next.js/commit/2f44795aed0579acb5f1fea90370b0066c170bcb))
- **lambda-at-edge:** fail build when "public/static" folder exists as this conflicts with static/\* cache behavior ([#709](https://github.com/sleukhin/serverless-next.js/issues/709)) ([187bbc8](https://github.com/sleukhin/serverless-next.js/commit/187bbc8bd3b4c5284db155dced94c8d857b7f68a))
- **lambda-at-edge:** fix broken npm install by changing src/command.js -> dist/command.js ([fde41ee](https://github.com/sleukhin/serverless-next.js/commit/fde41ee098c06759b3b71e9dc489a6aef98baff2))
- **lambda-at-edge:** fix broken redirects with full URLs as destinations ([#638](https://github.com/sleukhin/serverless-next.js/issues/638)) ([ee95e54](https://github.com/sleukhin/serverless-next.js/commit/ee95e549cdb620865d536435e74e1ea3026ecd20))
- **lambda-at-edge:** fix compilation of query strings in redirect des… ([#647](https://github.com/sleukhin/serverless-next.js/issues/647)) ([9ed7159](https://github.com/sleukhin/serverless-next.js/commit/9ed7159a759eccedd5cf6ee98a261c1cbcab1d90))
- **lambda-at-edge:** fix data request routing / client-side navigation for SSR index page ([#574](https://github.com/sleukhin/serverless-next.js/issues/574)) ([f580786](https://github.com/sleukhin/serverless-next.js/commit/f580786e5859f217e5ce79824cdaa0ef17ef0e42))
- **lambda-at-edge:** fix dynamic route precedence conflicting with fallback pages ([#714](https://github.com/sleukhin/serverless-next.js/issues/714)) ([e667e76](https://github.com/sleukhin/serverless-next.js/commit/e667e76cef137d68ef215e91a72490dba7f7199f))
- **lambda-at-edge:** fix dynamic routes with getStaticPaths interfering with public files ([#679](https://github.com/sleukhin/serverless-next.js/issues/679)) ([17beb1f](https://github.com/sleukhin/serverless-next.js/commit/17beb1f7a994ec17d3e378bee931237b2b5cc54f))
- **lambda-at-edge:** fix for 404s on public files ([#577](https://github.com/sleukhin/serverless-next.js/issues/577)) ([a854139](https://github.com/sleukhin/serverless-next.js/commit/a854139f4344530de1a42268828231a4d38c7c91))
- **lambda-at-edge:** fix next 9.5 root uri problem ([#528](https://github.com/sleukhin/serverless-next.js/issues/528)) ([ceb9218](https://github.com/sleukhin/serverless-next.js/commit/ceb9218dcdd15e1b36228fc3752e2f5e4b4082c0))
- **lambda-at-edge:** fix possible redirect loop in API handler ([#671](https://github.com/sleukhin/serverless-next.js/issues/671)) ([ed92ebc](https://github.com/sleukhin/serverless-next.js/commit/ed92ebce73720c46fdb5c7c9065127d7f8a51078))
- **lambda-at-edge:** fix reading next.config.js in build step when it exports a function ([#569](https://github.com/sleukhin/serverless-next.js/issues/569)) ([16272b4](https://github.com/sleukhin/serverless-next.js/commit/16272b43b8d1cfcdebe1eddad91a8bae7bcc890c))
- **lambda-at-edge:** fix routing for pages with basePath ([#572](https://github.com/sleukhin/serverless-next.js/issues/572)) ([b185a7a](https://github.com/sleukhin/serverless-next.js/commit/b185a7a088b58651780542d1539660c951cd63a6))
- **lambda-at-edge:** fix routing issue when looking up root / path in prerender-manifest ([7eedd69](https://github.com/sleukhin/serverless-next.js/commit/7eedd6931923cb0c5ed87255075a401345505bc7))
- **lambda-at-edge:** fix s3 bucket not being normalized for public assets ([#497](https://github.com/sleukhin/serverless-next.js/issues/497)) ([7e39902](https://github.com/sleukhin/serverless-next.js/commit/7e399022ebf9c45aa782c6bc9104c55192bb3af7))
- **lambda-at-edge:** for serverless-trace target, exclude files that are not in node-modules folder ([#758](https://github.com/sleukhin/serverless-next.js/issues/758)) ([2d72f4f](https://github.com/sleukhin/serverless-next.js/commit/2d72f4f7932124d136eb3cfc6c1134682ca36ef0))
- **lambda-at-edge:** for serverless-trace, don't copy when source and destination are the same ([#760](https://github.com/sleukhin/serverless-next.js/issues/760)) ([29ef6a6](https://github.com/sleukhin/serverless-next.js/commit/29ef6a6f2e7ee4ef2c8b10f068d10707a9a90416))
- **lambda-at-edge:** ignore package.json during serverless-trace ([#552](https://github.com/sleukhin/serverless-next.js/issues/552)) ([d21f1d5](https://github.com/sleukhin/serverless-next.js/commit/d21f1d56b8b21bad38b86ec91ae5f26c8c9472bc))
- **lambda-at-edge:** move path-to-regexp to prod deps ([e4d9dbd](https://github.com/sleukhin/serverless-next.js/commit/e4d9dbd3f12b12cd5f10936d0daf511134c70ae7))
- **lambda-at-edge:** non-dynamic pages (SSG, SSR) should be prioritized over dynamic fallback pages ([#685](https://github.com/sleukhin/serverless-next.js/issues/685)) ([71b61e7](https://github.com/sleukhin/serverless-next.js/commit/71b61e7644874da15715c6ec9af60cdc3746f71a))
- **lambda-at-edge:** non-dynamic routes for rewrite should not include routes in prerender manifest ([#700](https://github.com/sleukhin/serverless-next.js/issues/700)) ([06d4edb](https://github.com/sleukhin/serverless-next.js/commit/06d4edb72da2662affc9ad25a2e4eb5550d415e9))
- **lambda-at-edge:** render Next 500 page when SSR render fails, and ensure 404 pages return 404 status codes ([#570](https://github.com/sleukhin/serverless-next.js/issues/570)) ([bdd1e3f](https://github.com/sleukhin/serverless-next.js/commit/bdd1e3f9feb7e0c9eec42de7298882dce084aa67))
- **lambda-at-edge:** resolve dependencies using .next/serverless as base path ([#425](https://github.com/sleukhin/serverless-next.js/issues/425)) ([d60982f](https://github.com/sleukhin/serverless-next.js/commit/d60982f10e85f716badd1676c3f89a57a6c04019))
- **lambda-at-edge:** serve HTML pages with no props (i.e static pages) properly on preview mode enabled ([#701](https://github.com/sleukhin/serverless-next.js/issues/701)) ([57cd668](https://github.com/sleukhin/serverless-next.js/commit/57cd6689152530064635eb9d53c5201d580c9b61))
- **lambda-at-edge, e2e-tests:** don't rewrite non-dynamic api routes ([#698](https://github.com/sleukhin/serverless-next.js/issues/698)) ([27526e7](https://github.com/sleukhin/serverless-next.js/commit/27526e70c57d3bab016f734a0672d62c9d43bcca))
- **lambda-at-edge, e2e-tests:** fix issue where SSR data request should be directly rendered in Lambda, not retrieved from S3 ([2fa8910](https://github.com/sleukhin/serverless-next.js/commit/2fa8910aea85626a5ae37efd4c8a2e6ece86c4ce))
- **lambda-at-edge, e2e-tests:** non-dynamic routes should never be rewritten ([#697](https://github.com/sleukhin/serverless-next.js/issues/697)) ([f16c9a0](https://github.com/sleukhin/serverless-next.js/commit/f16c9a0811e80bb5d45d9ebd517c2ae8f3b35316))
- **lambda-at-edge, e2e-tests:** PUT or DELETE S3 methods should just … ([#680](https://github.com/sleukhin/serverless-next.js/issues/680)) ([f9910a0](https://github.com/sleukhin/serverless-next.js/commit/f9910a023511240337ee62251a169f9504ffbfec))
- **next-aws-cloudfront:** ignore calls to res.end() after the first one ([#526](https://github.com/sleukhin/serverless-next.js/issues/526)) ([c4c9f6f](https://github.com/sleukhin/serverless-next.js/commit/c4c9f6fe7e07a2f1f4820e82907bad346cd9df87))
- **nextjs-component:** allow all CloudFront HTTP methods for default caching behavior ([#609](https://github.com/sleukhin/serverless-next.js/issues/609)) ([6066fa1](https://github.com/sleukhin/serverless-next.js/commit/6066fa1bf4e1fb823039108158a42f7af69a90d6))
- **nextjs-component:** fix inability to set custom behavior for \_next/data/\* ([#684](https://github.com/sleukhin/serverless-next.js/issues/684)) ([326acc8](https://github.com/sleukhin/serverless-next.js/commit/326acc859dc20bb59b89bcbcbf4095d6db7c9dc2))
- **nextjs-component:** make execa point directly at next .bin ([3ffbc17](https://github.com/sleukhin/serverless-next.js/commit/3ffbc17aa2cd5c696080935f81c1dd7e431e00be))
- **nextjs-component:** parse cloudfront headers correctly ([9a22f5b](https://github.com/sleukhin/serverless-next.js/commit/9a22f5b6687e18ea10b9048768a712b64f72165b))
- **nextjs-component:** remove domain on component removal ([e478ffc](https://github.com/sleukhin/serverless-next.js/commit/e478ffccdf50f22f491a635da08601a74e017d7a))
- **nextjs-component:** route / requests to index.html correctly ([ed3cace](https://github.com/sleukhin/serverless-next.js/commit/ed3cace0e70524ac12bac49f8be8a161b143f39a))
- **plugin:** move config referencing out of plugin constructor ([#248](https://github.com/sleukhin/serverless-next.js/issues/248)) ([16d66a2](https://github.com/sleukhin/serverless-next.js/commit/16d66a209a47adf799f8ac1ca8efb6cc7a38e68f))
- **s3-static-assets:** always use posix path join for fast-glob in re… ([#940](https://github.com/sleukhin/serverless-next.js/issues/940)) ([d513192](https://github.com/sleukhin/serverless-next.js/commit/d5131922c2bef84d6298229dfa434128df334ccc))
- **s3-static-assets:** fix s3 directory read for fast-glob on windows ([#986](https://github.com/sleukhin/serverless-next.js/issues/986)) ([7218008](https://github.com/sleukhin/serverless-next.js/commit/72180085642b260df459bdb715d2cb446860a79e))
- **s3-static-assets:** Fixed missing posix conversion in s3 uploads. ([#551](https://github.com/sleukhin/serverless-next.js/issues/551)) ([296d1b0](https://github.com/sleukhin/serverless-next.js/commit/296d1b087999610f025928e77f3c4b2d6b461c1b))
- **s3-static-assets:** prevent client cache of static pages ([#421](https://github.com/sleukhin/serverless-next.js/issues/421)) ([647d74a](https://github.com/sleukhin/serverless-next.js/commit/647d74a0687f251bb6671d96c0c668b3749db7a1))
- **serverless-component:** bump aws-lambda with fix for catch all routes ([a09b469](https://github.com/sleukhin/serverless-next.js/commit/a09b469ffb70f07ff255067a7b4975b2d69eefa8))
- **serverless-component:** create the DNS record only when hosted zone exists ([#635](https://github.com/sleukhin/serverless-next.js/issues/635)) ([3bbac6b](https://github.com/sleukhin/serverless-next.js/commit/3bbac6bee43b64a062a4c095199c4baa16d44f4e))
- **serverless-component:** custom cloudfront configuration bug fixes ([#407](https://github.com/sleukhin/serverless-next.js/issues/407)) ([093edec](https://github.com/sleukhin/serverless-next.js/commit/093edecfb242a013024418725cd68a6981b87dea))
- **serverless-component:** don't overwrite the cloudfront default.forward config ([#460](https://github.com/sleukhin/serverless-next.js/issues/460)) ([12da1de](https://github.com/sleukhin/serverless-next.js/commit/12da1de31855b68b9addef801ec21dffd3202a21))
- **serverless-component:** enforce compression for the default cloudfront behaviour ([#462](https://github.com/sleukhin/serverless-next.js/issues/462)) ([7e8f0d4](https://github.com/sleukhin/serverless-next.js/commit/7e8f0d486ac07f56e97500e48f9b54ed14038b16))
- **serverless-component:** fix "main" package.json property ([96d510d](https://github.com/sleukhin/serverless-next.js/commit/96d510d3e21f6fe84c02425f2c8c6f311b90665f))
- **serverless-component:** fix for AWS accounts with more than 100 domains ([69574c7](https://github.com/sleukhin/serverless-next.js/commit/69574c7d82bee01817bceb0f9bb7e8b9cae53faf))
- **serverless-component:** fixes 307 errors when using bucket region outside us-east-1 ([#495](https://github.com/sleukhin/serverless-next.js/issues/495)) ([561e05f](https://github.com/sleukhin/serverless-next.js/commit/561e05f9ba9763fab4185b34adcde61dfcbb0a21))
- **serverless-component:** upload whole .next/static folder and dont clear cache between builds ([4406ebb](https://github.com/sleukhin/serverless-next.js/commit/4406ebbb8937c75dfbc5644913b7c0d05ff3a52f))
- **serverless-component:** wait sequentially for resources to be removed, so as to avoid race conditions ([#588](https://github.com/sleukhin/serverless-next.js/issues/588)) ([7bcb032](https://github.com/sleukhin/serverless-next.js/commit/7bcb032f3199f245643fab91e8b671083a857cc3))
- **serverless-component:** when adding primary domain name to CloudFront distribution aliases, don't replace other aliases ([#658](https://github.com/sleukhin/serverless-next.js/issues/658)) ([4428d5c](https://github.com/sleukhin/serverless-next.js/commit/4428d5c84470808c4afcb6e8c109602518c854f9))
- **serverless-next.js:** fix API Lambda description input ([b1b6cdf](https://github.com/sleukhin/serverless-next.js/commit/b1b6cdf515f3bb25593c8be9c0a7b2ee4a1ab8bc))
- **serverless-next.js:** fix resolution of next-aws-cloudfront ([0c22c85](https://github.com/sleukhin/serverless-next.js/commit/0c22c858f77932d0215d2768bdea0cd9ff44a1f5))
- **serverless-next.js:** Fix the issue with TypeError hasHeader is not a function ([#342](https://github.com/sleukhin/serverless-next.js/issues/342)) ([20f42fd](https://github.com/sleukhin/serverless-next.js/commit/20f42fddb9fd80238dfd1e700bba1afa459126a6)), closes [/github.com/zeit/next.js/blob/v9.3.1/packages/next/next-server/server/send-payload.ts#L25](https://github.com//github.com/zeit/next.js/blob/v9.3.1/packages/next/next-server/server/send-payload.ts/issues/L25) [zeit/next.js#11223](https://github.com/zeit/next.js/issues/11223) [#329](https://github.com/sleukhin/serverless-next.js/issues/329) [#331](https://github.com/sleukhin/serverless-next.js/issues/331)
- **serverless-nextjs-component:** fix require of next-aws-cloudfront compat in edge fn handlers ([e6a8336](https://github.com/sleukhin/serverless-next.js/commit/e6a8336b0d489b4fecac48ff8bcfbd1a7b111b55))
- **sls-next/cdk-construct:** defaultBehavior.edgeLambdas only applied to defaultBehavior ([#1031](https://github.com/sleukhin/serverless-next.js/issues/1031)) ([a5a0ccd](https://github.com/sleukhin/serverless-next.js/commit/a5a0ccd0d3d8c90d0cf221eb5dfaa6598625e1b9))
- cache header for s3 files ([#241](https://github.com/sleukhin/serverless-next.js/issues/241)) ([311747a](https://github.com/sleukhin/serverless-next.js/commit/311747a22fa3c112225e82943de099250ad6ceb5))
- change default TTL to 0 seconds ([#264](https://github.com/sleukhin/serverless-next.js/issues/264)) ([0362b2c](https://github.com/sleukhin/serverless-next.js/commit/0362b2c207f3c27da44f80090bb750e4fb53802a))
- dont throw when public dir doesnt exist ([3580b8c](https://github.com/sleukhin/serverless-next.js/commit/3580b8c939d3cc2a56936e7ed8da3d557f3de1b1))
- handle empty req url ([#315](https://github.com/sleukhin/serverless-next.js/issues/315)) ([ad7bec1](https://github.com/sleukhin/serverless-next.js/commit/ad7bec1827ad3b6074c6f1a085a57a2d906334ba))
- recursively read assets inside public folder ([#245](https://github.com/sleukhin/serverless-next.js/issues/245)) ([5f93912](https://github.com/sleukhin/serverless-next.js/commit/5f939126843c8204bc899f692e4a3162056afac3))
- Throw friendly error if next app target is not set to serverless ([#204](https://github.com/sleukhin/serverless-next.js/issues/204)) ([83c31e2](https://github.com/sleukhin/serverless-next.js/commit/83c31e230099bb60f6a267e925b5c6171809a832))

### Features

- **aws-cloudfront:** adding new input (distributionId) to aws-cloudfront ([#508](https://github.com/sleukhin/serverless-next.js/issues/508)) ([8fa5a10](https://github.com/sleukhin/serverless-next.js/commit/8fa5a104ee914a90ffdc643d45881a626651583b))
- **nextjs-cdk-construct:** support override props for CloudFront distribution ([#1236](https://github.com/sleukhin/serverless-next.js/issues/1236)) ([783b888](https://github.com/sleukhin/serverless-next.js/commit/783b8889eef31796c0935e836962a7a329fd47fa))
- use high throughput mode for regeneration SQS ([#1148](https://github.com/sleukhin/serverless-next.js/issues/1148)) ([f3d033c](https://github.com/sleukhin/serverless-next.js/commit/f3d033c08164a7681572ad7fa1aedc78bbf23ed6))
- **aws-cloudfront:** add ability to persist cache behaviors not set in serverless ([#809](https://github.com/sleukhin/serverless-next.js/issues/809)) ([b339bf5](https://github.com/sleukhin/serverless-next.js/commit/b339bf5b6905a7e93aaf18622adc0b88c854b7b2))
- **aws-cloudfront:** allow predefined originAccessIdentityId ([#811](https://github.com/sleukhin/serverless-next.js/issues/811)) ([8785727](https://github.com/sleukhin/serverless-next.js/commit/878572769397428e08349982079001a8b94d977e))
- **aws-cloudfront:** allow setting CloudFront distribution aliases ([#654](https://github.com/sleukhin/serverless-next.js/issues/654)) ([ea180e6](https://github.com/sleukhin/serverless-next.js/commit/ea180e67515ee5dceed1c3e19731291615a7cbbb))
- **aws-cloudfront:** allow setting configuration for custom origins ([#657](https://github.com/sleukhin/serverless-next.js/issues/657)) ([5f97683](https://github.com/sleukhin/serverless-next.js/commit/5f97683f37dc3d81092aa3e16c9c8057680ec62e))
- **aws-cloudfront, nextjs-component:** support setting certificate input in cloudfront ([#727](https://github.com/sleukhin/serverless-next.js/issues/727)) ([6f68bf1](https://github.com/sleukhin/serverless-next.js/commit/6f68bf1910d80cc69b09f6529081e6ccad74552e))
- **aws-cloudfront, nextjs-component:** support setting geo restrictions ([#726](https://github.com/sleukhin/serverless-next.js/issues/726)) ([964b936](https://github.com/sleukhin/serverless-next.js/commit/964b9360484a6a9ad3f69a593dc2f26547c15eb2))
- **aws-cloudfront, nextjs-component:** support setting WAF web ACL id ([#724](https://github.com/sleukhin/serverless-next.js/issues/724)) ([1a11594](https://github.com/sleukhin/serverless-next.js/commit/1a1159472621e91191f1f41a39fe75a0ed9897b1))
- **aws-cloudfront, s3-static-assets:** support setting individual min, max, default CloudFront TTLs, update Cache-Control headers and TTLs for \_next/data files ([#593](https://github.com/sleukhin/serverless-next.js/issues/593)) ([fb8e61d](https://github.com/sleukhin/serverless-next.js/commit/fb8e61dc50b11c0e5966548a8c84b58e495ea748))
- **aws-cloudfront, serverless-component:** add cloudfront custom error responses ([#590](https://github.com/sleukhin/serverless-next.js/issues/590)) ([f3d2a17](https://github.com/sleukhin/serverless-next.js/commit/f3d2a17b2fac5e9bb67b1f6ed5201c8128600314))
- **cdk-construct:** adding support for multiple domainNames ([#1009](https://github.com/sleukhin/serverless-next.js/issues/1009)) ([c9e87fc](https://github.com/sleukhin/serverless-next.js/commit/c9e87fc5b4bfb7207895f81557533f6eaf401208))
- **cdk-construct:** Support for outside hosted domain ([#1037](https://github.com/sleukhin/serverless-next.js/issues/1037)) ([dcc6bd2](https://github.com/sleukhin/serverless-next.js/commit/dcc6bd24481ac31e1b9c6012d2365b62bf0cafad)), closes [#1027](https://github.com/sleukhin/serverless-next.js/issues/1027)
- **cloudfront, serverless-component:** add optional invalidation paths configuration ([#814](https://github.com/sleukhin/serverless-next.js/issues/814)) ([088d0c0](https://github.com/sleukhin/serverless-next.js/commit/088d0c05dc1b278f8387a5a8eaf36d9725cf9740))
- **component:** dynamic routes rendered from static pages ([#239](https://github.com/sleukhin/serverless-next.js/issues/239)) ([af17d71](https://github.com/sleukhin/serverless-next.js/commit/af17d7101164fae6eb24cb3ec2d51ebb890a221f))
- **experimental:** CDK Construct ([#878](https://github.com/sleukhin/serverless-next.js/issues/878)) ([d38e2aa](https://github.com/sleukhin/serverless-next.js/commit/d38e2aa70816c3204727fda4c9e379c73e1b2f2e))
- **lambda-at-edge:** add a binary to allow use without copying example ([#688](https://github.com/sleukhin/serverless-next.js/issues/688)) ([0c138a2](https://github.com/sleukhin/serverless-next.js/commit/0c138a2d63b230b3c0ec5a37080b8987bfcc86ff))
- **lambda-at-edge:** add baseDir and resolve build options to serverless-trace ([#779](https://github.com/sleukhin/serverless-next.js/issues/779)) ([8f978bb](https://github.com/sleukhin/serverless-next.js/commit/8f978bb1f8117d1c1a81d965be3aa23b9c14798c)), closes [vercel/nft#153](https://github.com/vercel/nft/issues/153)
- **lambda-at-edge:** add minifyHandlers input to minify handler code using Terser ([#659](https://github.com/sleukhin/serverless-next.js/issues/659)) ([1b33e72](https://github.com/sleukhin/serverless-next.js/commit/1b33e72bf1e578e1a8bd6c7a77aeb99db412471a))
- **lambda-at-edge:** add opt in lambda execution times logging ([#549](https://github.com/sleukhin/serverless-next.js/issues/549)) ([066bd27](https://github.com/sleukhin/serverless-next.js/commit/066bd270ce8b8f915298b7bac51c2aeb3ab27126))
- **lambda-at-edge:** add serverless trace target support ([#405](https://github.com/sleukhin/serverless-next.js/issues/405)) ([d800951](https://github.com/sleukhin/serverless-next.js/commit/d800951673474965c386ab94b2d8db18790099f7))
- **lambda-at-edge:** autogenerate serverless config ([#418](https://github.com/sleukhin/serverless-next.js/issues/418)) ([0f9a176](https://github.com/sleukhin/serverless-next.js/commit/0f9a176f65207d31d0b66a11d6fbceafe27fade5))
- **lambda-at-edge:** create new package with Lambda@Edge builder and handlers ([94f0a29](https://github.com/sleukhin/serverless-next.js/commit/94f0a29f0654f51d60653c8218c15802b2abb476))
- **lambda-at-edge:** fallback: "blocking" ([#1007](https://github.com/sleukhin/serverless-next.js/issues/1007)) ([ef3c9ad](https://github.com/sleukhin/serverless-next.js/commit/ef3c9adf4e991d23b6b13e550a757747790a55f2))
- **lambda-at-edge:** incremental static regeneration ([#1028](https://github.com/sleukhin/serverless-next.js/issues/1028)) ([d5bbdc6](https://github.com/sleukhin/serverless-next.js/commit/d5bbdc6d395ae732ec0757744482bf8bc25e820f))
- **lambda-at-edge:** initial support for routing to locale-specific … ([#884](https://github.com/sleukhin/serverless-next.js/issues/884)) ([b4666d3](https://github.com/sleukhin/serverless-next.js/commit/b4666d331e6dd84e3409d4ef2351ab31afd96953))
- **lambda-at-edge:** no-op rewrite support ([#759](https://github.com/sleukhin/serverless-next.js/issues/759)) ([2107ab1](https://github.com/sleukhin/serverless-next.js/commit/2107ab1f3c0213dcfbd54521ff10811a2d58ca51))
- **lambda-at-edge:** start copying locale-specific page/data files t… ([#883](https://github.com/sleukhin/serverless-next.js/issues/883)) ([8bc889c](https://github.com/sleukhin/serverless-next.js/commit/8bc889cb3242e27057bc5f1260faad4e42ea0cfe))
- **lambda-at-edge:** support custom headers (with caveats) ([#662](https://github.com/sleukhin/serverless-next.js/issues/662)) ([8b9e822](https://github.com/sleukhin/serverless-next.js/commit/8b9e822a7071fc3277711ed476860564577e0af3))
- **lambda-at-edge:** support custom redirects ([#627](https://github.com/sleukhin/serverless-next.js/issues/627)) ([d2f9679](https://github.com/sleukhin/serverless-next.js/commit/d2f9679a5074285cb8a5111d4c1e34f8bbde0b0f))
- **lambda-at-edge:** support custom redirects from API routes ([#640](https://github.com/sleukhin/serverless-next.js/issues/640)) ([b68d46a](https://github.com/sleukhin/serverless-next.js/commit/b68d46a4592a48ee55a35e089e4d8554edadaa17))
- **lambda-at-edge:** support external rewrites ([#839](https://github.com/sleukhin/serverless-next.js/issues/839)) ([d57f75f](https://github.com/sleukhin/serverless-next.js/commit/d57f75fdcb9129bff9d9812cc0af937e8cb0bd3c))
- **lambda-at-edge:** support fallback: false for getStaticPaths and fix cache-control header ([#681](https://github.com/sleukhin/serverless-next.js/issues/681)) ([3ef5c17](https://github.com/sleukhin/serverless-next.js/commit/3ef5c17032bd206f706323b9a85e940b594cfc38))
- **lambda-at-edge:** support image optimization ([#829](https://github.com/sleukhin/serverless-next.js/issues/829)) ([f6c5156](https://github.com/sleukhin/serverless-next.js/commit/f6c5156bf8bb4912528dfb3723227cca0790218a))
- **lambda-at-edge:** support optional catch-all ([#791](https://github.com/sleukhin/serverless-next.js/issues/791)) ([ba9d409](https://github.com/sleukhin/serverless-next.js/commit/ba9d4093ab9d1173b904f72146d0fa161d10b01e))
- **lambda-at-edge:** support page and API rewrites ([#653](https://github.com/sleukhin/serverless-next.js/issues/653)) ([f187b91](https://github.com/sleukhin/serverless-next.js/commit/f187b91dd40012810cb96308d416736f2e032222))
- **lambda-at-edge:** support trailing slash / non-trailing slash redirects ([#556](https://github.com/sleukhin/serverless-next.js/issues/556)) ([ca63b80](https://github.com/sleukhin/serverless-next.js/commit/ca63b80d4bf784ebfdc5a32352a53dde85b4b4d9))
- **lambda-at-edge:** use new aws s3 client for faster require time ([#583](https://github.com/sleukhin/serverless-next.js/issues/583)) ([f9eef45](https://github.com/sleukhin/serverless-next.js/commit/f9eef458552e5ff5ee60e9b43df7ccf221a2ec0c))
- **lambda-at-edge:** use S3 regional endpoint when not in us-east-1 ([#474](https://github.com/sleukhin/serverless-next.js/issues/474)) ([5ecff1a](https://github.com/sleukhin/serverless-next.js/commit/5ecff1a50e26c22f7de9ec9da3cf2cba4390d77d))
- **lambda-at-edge-compat, lambda-at-edge, nextjs-component:** let CloudFront do the Gzipping ([#692](https://github.com/sleukhin/serverless-next.js/issues/692)) ([05fb0eb](https://github.com/sleukhin/serverless-next.js/commit/05fb0ebdf38096fb7e0427956c4747e782c680a8))
- **lambda-at-edge, next-aws-cloudfront:** support Preview Mode ([#562](https://github.com/sleukhin/serverless-next.js/issues/562)) ([5e1ea38](https://github.com/sleukhin/serverless-next.js/commit/5e1ea3891e48d75de5973902a014b67f14c8380a))
- **lambda-at-edge, nextjs-commponent:** rewrite from root using accept-language header, other minor bugfixes for locales ([#885](https://github.com/sleukhin/serverless-next.js/issues/885)) ([828b9dd](https://github.com/sleukhin/serverless-next.js/commit/828b9dde89a9cb2559c58ab4e798ee7cbcbdd5e6))
- **lambda-at-edge, nextjs-component:** add new input domainRedirects ([#639](https://github.com/sleukhin/serverless-next.js/issues/639)) ([a12e31a](https://github.com/sleukhin/serverless-next.js/commit/a12e31ac06378f9fe26189b95a9b032942656380))
- **lambda-at-edge, nextjs-component:** allow `handler` input for custom handler code ([#649](https://github.com/sleukhin/serverless-next.js/issues/649)) ([cecd327](https://github.com/sleukhin/serverless-next.js/commit/cecd327993d593c582eeb140538b271b2eef509a))
- **lambda-at-edge, nextjs-component, s3-static-assets:** support ver… ([#803](https://github.com/sleukhin/serverless-next.js/issues/803)) ([015065d](https://github.com/sleukhin/serverless-next.js/commit/015065d02c1d06659dc1d1a7258b89f9415c3721))
- **lambda-at-edge,serverless-component:** basePath support ([#510](https://github.com/sleukhin/serverless-next.js/issues/510)) ([b17ce30](https://github.com/sleukhin/serverless-next.js/commit/b17ce30b1f18f994f1d2e9ebfe833a74aae6676b))
- **next-aws-lambda,next-aws-cloudfront:** fix status code and body bugs ([#437](https://github.com/sleukhin/serverless-next.js/issues/437)) ([7291f83](https://github.com/sleukhin/serverless-next.js/commit/7291f83f58eaa09733e3ce2df494afc2c0e04f9a))
- **nextjs-component:** add baseDir from [#779](https://github.com/sleukhin/serverless-next.js/issues/779) to component to facilitate usage in monorepos ([#953](https://github.com/sleukhin/serverless-next.js/issues/953)) ([86844e6](https://github.com/sleukhin/serverless-next.js/commit/86844e60cdb46b64315abab76d03b24d8c8c770d))
- **nextjs-component:** add build.postBuildCommands input to execute any command or script post-build ([#772](https://github.com/sleukhin/serverless-next.js/issues/772)) ([b2cc97f](https://github.com/sleukhin/serverless-next.js/commit/b2cc97f35adfa7364c3d708cd84ac9efeb7be68e))
- **nextjs-component:** add deploy input which can be set to false to skip deployment ([#691](https://github.com/sleukhin/serverless-next.js/issues/691)) ([5adaf2b](https://github.com/sleukhin/serverless-next.js/commit/5adaf2bacae6f8647ac7fc90f910eefb97d8f229))
- **nextjs-component:** add inputs.roleArn for existing lambda role ([#827](https://github.com/sleukhin/serverless-next.js/issues/827)) ([f63bc76](https://github.com/sleukhin/serverless-next.js/commit/f63bc763fcc224b3a0c49637ad58129c3143351c))
- **nextjs-component:** allow disabling s3 transfer acceleration ([#926](https://github.com/sleukhin/serverless-next.js/issues/926)) ([9aaeec7](https://github.com/sleukhin/serverless-next.js/commit/9aaeec7c3e9ab6c6c70389801c155477ae7cd456))
- **nextjs-component:** allow setting custom API cache behavior ([#623](https://github.com/sleukhin/serverless-next.js/issues/623)) ([ca8094b](https://github.com/sleukhin/serverless-next.js/commit/ca8094b4d9b9541493410dd830a3c85f54250448))
- **nextjs-component:** change ServerlessComponentInputs.deploy and BuildOptions.enabled to a union type ([#999](https://github.com/sleukhin/serverless-next.js/issues/999)) ([#1000](https://github.com/sleukhin/serverless-next.js/issues/1000)) ([3896b12](https://github.com/sleukhin/serverless-next.js/commit/3896b12d7cc85ac44ab4b680c0efe096f7238f8b))
- **nextjs-component:** enable custom domain names ([d8c3f97](https://github.com/sleukhin/serverless-next.js/commit/d8c3f97aedcfd8d8dcdda1a5174696aa3eea02ed))
- **nextjs-component, lambda-at-edge:** support single username/password basic authen… ([#773](https://github.com/sleukhin/serverless-next.js/issues/773)) ([220da4a](https://github.com/sleukhin/serverless-next.js/commit/220da4a7274bc43408803bb831c2221a95a7d435))
- **serverless-component:** add manual ACM SSL ARN specification ([#655](https://github.com/sleukhin/serverless-next.js/issues/655)) ([6bb1443](https://github.com/sleukhin/serverless-next.js/commit/6bb144385c6621c4c5c00443259df538a185f4f2))
- **serverless-component:** add support for custom s3 region ([#451](https://github.com/sleukhin/serverless-next.js/issues/451)) ([ffef4ad](https://github.com/sleukhin/serverless-next.js/commit/ffef4ad21525d54489a158f98b638f9c2b00c57a))
- **serverless-component:** allow CloudFront PriceClass to be set ([#515](https://github.com/sleukhin/serverless-next.js/issues/515)) ([943958a](https://github.com/sleukhin/serverless-next.js/commit/943958a823d602db35ca2b789e6d8b455ef5f499))
- **serverless-component:** allow custom configuration for Cloudfront ([#282](https://github.com/sleukhin/serverless-next.js/issues/282)) ([e7bed6a](https://github.com/sleukhin/serverless-next.js/commit/e7bed6aa8d0a8f7fd332e1d0c37d8dc67ec3aa65))
- **serverless-component:** allow passing an inline policy ([#575](https://github.com/sleukhin/serverless-next.js/issues/575)) ([05ddcc9](https://github.com/sleukhin/serverless-next.js/commit/05ddcc98c03e642b8ab9fda3e20334215a8cb017))
- **serverless-component:** allow users to set the node.js runtime for the lambda functions ([#422](https://github.com/sleukhin/serverless-next.js/issues/422)) ([a0534ab](https://github.com/sleukhin/serverless-next.js/commit/a0534ab7db8d4ebcdbad7719c16ad8eaee96eb71))
- **serverless-component:** cache static pages and invalidate distribution after deploy ([#435](https://github.com/sleukhin/serverless-next.js/issues/435)) ([5d75936](https://github.com/sleukhin/serverless-next.js/commit/5d759367be5a1c835b093f2713bc0b8cf1d92a82))
- **serverless-component:** custom cloudfront.origins input ([#376](https://github.com/sleukhin/serverless-next.js/issues/376)) ([69beb5a](https://github.com/sleukhin/serverless-next.js/commit/69beb5af20c5c3b4435b3b7a3de08265848c3692))
- **serverless-component:** implement getStaticProps / getStaticPaths [fallback: false] ([#390](https://github.com/sleukhin/serverless-next.js/issues/390)) ([5185649](https://github.com/sleukhin/serverless-next.js/commit/518564944435767759fae8ae5978baf3afc49d7a))
- **serverless-component, lambda-at-edge:** add support for static 404.html page ([#432](https://github.com/sleukhin/serverless-next.js/issues/432)) ([0ba8931](https://github.com/sleukhin/serverless-next.js/commit/0ba8931807258de58eeaccf449a7b714fc66e15c))
- **serverless-component, lambda-at-edge, lambda-at-edge-compat, s3-static-assets:** add support for getStaticPaths fallback true ([#544](https://github.com/sleukhin/serverless-next.js/issues/544)) ([a08217b](https://github.com/sleukhin/serverless-next.js/commit/a08217ba26ea90f67c562fe4ae9510b617d14d08))
- **serverless-component,lambda-at-edge:** getServerSideProps support ([#429](https://github.com/sleukhin/serverless-next.js/issues/429)) ([7aeb26e](https://github.com/sleukhin/serverless-next.js/commit/7aeb26e5052498c580baf7db38e63fefafc38ea4))
- **sls-next/cdk-construct:** edgeLambdas concatenated with default edge lambdas ([#1024](https://github.com/sleukhin/serverless-next.js/issues/1024)) ([32772c0](https://github.com/sleukhin/serverless-next.js/commit/32772c00f03147b4dbeb3602dc947a488476fc4f))
- add custom input for lambda(s) timeout ([#275](https://github.com/sleukhin/serverless-next.js/issues/275)) ([236231e](https://github.com/sleukhin/serverless-next.js/commit/236231e83e5d82ca1061dddab4106961883bbda1))
- add custom inputs for lambda name ([#283](https://github.com/sleukhin/serverless-next.js/issues/283)) ([704120b](https://github.com/sleukhin/serverless-next.js/commit/704120b28f0747efec9490ab5bcd3a161a9c7253)), closes [#232](https://github.com/sleukhin/serverless-next.js/issues/232)
- ignore subdomain if not present ([#231](https://github.com/sleukhin/serverless-next.js/issues/231)) ([ac2f819](https://github.com/sleukhin/serverless-next.js/commit/ac2f819d57e361f6bd5241383eb83ecb6ec776d9))
- memory input for lambdas ([#255](https://github.com/sleukhin/serverless-next.js/issues/255)) ([54dfaa2](https://github.com/sleukhin/serverless-next.js/commit/54dfaa2762f6e809d064880973948eb2b2ccc82c))

### Performance Improvements

- **core, lambda-at-edge:** cold start improvements ([#1044](https://github.com/sleukhin/serverless-next.js/issues/1044)) ([0ee1394](https://github.com/sleukhin/serverless-next.js/commit/0ee1394d83141332d594010d6e2550daac30d245))
- **lambda-at-edge:** do not decompress content from fetch in external rewrite ([#871](https://github.com/sleukhin/serverless-next.js/issues/871)) ([f0a9b86](https://github.com/sleukhin/serverless-next.js/commit/f0a9b860433bfb1a82a2373d16b0db4835e13274))
- **lambda-at-edge:** fix rollup bundling for dynamic imports perf ([#1029](https://github.com/sleukhin/serverless-next.js/issues/1029)) ([f8f694c](https://github.com/sleukhin/serverless-next.js/commit/f8f694c55458309eac3dda50d4002970a578074c))

### Reverts

- Revert "test: remove flaky test" ([86f1ced](https://github.com/sleukhin/serverless-next.js/commit/86f1ced270d724c6235702540084d272ee0b1211))
