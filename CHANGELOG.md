# Changelog

All notable changes to this project will be documented in this file. See [standard-version](https://github.com/conventional-changelog/standard-version) for commit guidelines.

### [1.1.1](https://github.com/unjs/pathe/compare/v1.1.0...v1.1.1) (2023-06-01)


### Bug Fixes

* move `types` condition to the front ([#134](https://github.com/unjs/pathe/issues/134)) ([78715ee](https://github.com/unjs/pathe/commit/78715ee7886270cb6a86c6b6c5bbc6f8c83908a4))

## [1.1.0](https://github.com/unjs/pathe/compare/v1.0.1...v1.1.0) (2023-01-20)


### Features

* provide default export for node compatibility (resolves [#115](https://github.com/unjs/pathe/issues/115)) ([1ff01d1](https://github.com/unjs/pathe/commit/1ff01d10212c9a9558a23151586c9a3c85d2b5aa))

### [1.0.1](https://github.com/unjs/pathe/compare/v1.0.0...v1.0.1) (2023-01-20)


### Bug Fixes

* `process.cwd` fallback on non-node env ([#114](https://github.com/unjs/pathe/issues/114)) ([14714c1](https://github.com/unjs/pathe/commit/14714c144e0409e4877312c74d16c1e517b01f38))

## [1.0.0](https://github.com/unjs/pathe/compare/v0.3.9...v1.0.0) (2022-11-14)

### [0.3.9](https://github.com/unjs/pathe/compare/v0.3.8...v0.3.9) (2022-10-07)


### Bug Fixes

* respect path separators when resolving aliases ([#67](https://github.com/unjs/pathe/issues/67)) ([a718ebe](https://github.com/unjs/pathe/commit/a718ebeefc5d3a1b6ae264e356735add1db6142c))

### [0.3.8](https://github.com/unjs/pathe/compare/v0.3.7...v0.3.8) (2022-09-19)


### Bug Fixes

* **basename:** handle empty extensions ([#61](https://github.com/unjs/pathe/issues/61)) ([b0661cb](https://github.com/unjs/pathe/commit/b0661cbe62d249cf02e12982011ca987373c628f))

### [0.3.7](https://github.com/unjs/pathe/compare/v0.3.6...v0.3.7) (2022-09-06)


### Bug Fixes

* **resolveAlias:** preserve relative paths as is ([f3e5bcc](https://github.com/unjs/pathe/commit/f3e5bcc9c277ff4c9e6aeebdbdb19f9f26e1f62b))

### [0.3.6](https://github.com/unjs/pathe/compare/v0.3.5...v0.3.6) (2022-09-06)


### Features

* `resolveAlias` utility ([f8b3c83](https://github.com/unjs/pathe/commit/f8b3c8334b43f222a637bb2ee922f2d10815b35d))

### [0.3.5](https://github.com/unjs/pathe/compare/v0.3.4...v0.3.5) (2022-08-18)


### Bug Fixes

* **extname:** avoid regex look-behinds for safari support ([#42](https://github.com/unjs/pathe/issues/42)) ([c0cec97](https://github.com/unjs/pathe/commit/c0cec976375514bc4b2239b7fde1314e5c83583e))

### [0.3.4](https://github.com/unjs/pathe/compare/v0.3.3...v0.3.4) (2022-08-10)


### Features

* add `normalizeAliases` and `filename` in `/utils` subpath ([#34](https://github.com/unjs/pathe/issues/34)) ([1ece780](https://github.com/unjs/pathe/commit/1ece780a7568d2151c4f839481759997101a0e93))


### Bug Fixes

* improve windows path handling and improve coverage ([#36](https://github.com/unjs/pathe/issues/36)) ([34a55cf](https://github.com/unjs/pathe/commit/34a55cf41c9da75d63bff9abc3d5b0b50068b6ac))

### [0.3.3](https://github.com/unjs/pathe/compare/v0.3.2...v0.3.3) (2022-08-01)


### Bug Fixes

* normalize `process.cwd` on windows ([#31](https://github.com/unjs/pathe/issues/31)) ([a7b0f7b](https://github.com/unjs/pathe/commit/a7b0f7bcf150f82bc9e98109fb52bf394dfdc7ae))

### [0.3.2](https://github.com/unjs/pathe/compare/v0.3.1...v0.3.2) (2022-06-29)


### Bug Fixes

* **extname:** handle edge cases wirth leading dot ([dfe46d7](https://github.com/unjs/pathe/commit/dfe46d79035dd7302bb55b84cc445db07e8dde7f)), closes [#21](https://github.com/unjs/pathe/issues/21)

### [0.3.1](https://github.com/unjs/pathe/compare/v0.3.0...v0.3.1) (2022-06-27)


### Bug Fixes

* replace double-slashes in `join` calls ([#17](https://github.com/unjs/pathe/issues/17)) ([fd57079](https://github.com/unjs/pathe/commit/fd57079ac8ac597b31c4e5f3dd56a2d39eae20a6))
* return `.` as dirname fallback for non-absolute paths ([#19](https://github.com/unjs/pathe/issues/19)) ([e15d5da](https://github.com/unjs/pathe/commit/e15d5da0efba221209190deb2f3f98466f135d78))

## [0.3.0](https://github.com/unjs/pathe/compare/v0.2.0...v0.3.0) (2022-05-05)


### ⚠ BREAKING CHANGES

* `import pathe from 'pathe` should be changes to `import * as pathe from 'pathe'`
* implement rest of `path` minimally  (#10)

### Features

* implement rest of `path` minimally  ([#10](https://github.com/unjs/pathe/issues/10)) ([6136b3c](https://github.com/unjs/pathe/commit/6136b3ca9c1c26ec2a0002b24f08f8dcf28a78af))


### Bug Fixes

* avoid mixed named and default exports ([89e35ad](https://github.com/unjs/pathe/commit/89e35adbdc6921b362cad6b67bbff30fb58ce73e))

## [0.2.0](https://github.com/unjs/pathe/compare/v0.1.0...v0.2.0) (2021-09-27)


### ⚠ BREAKING CHANGES

* improved implementation with tests (#3)

### Features

* improved implementation with tests ([#3](https://github.com/unjs/pathe/issues/3)) ([d8d0cb5](https://github.com/unjs/pathe/commit/d8d0cb51dbca7295248c36f93510738057f2828d))

## [0.1.0](https://github.com/unjs/pathe/compare/v0.0.3...v0.1.0) (2021-09-24)

### [0.0.3](https://github.com/unjs/pathe/compare/v0.0.2...v0.0.3) (2021-09-24)


### Bug Fixes

* add hotfix for resolve ([a221d34](https://github.com/unjs/pathe/commit/a221d3468c81802da03823bd606de70a524a7b55))

### [0.0.2](https://github.com/unjs/pathe/compare/v0.0.1...v0.0.2) (2021-09-22)


### Bug Fixes

* **pkg:** expose types ([77000b1](https://github.com/unjs/pathe/commit/77000b1a45780fd62c93dc71d8264f10d97af864))

### 0.0.1 (2021-09-22)
