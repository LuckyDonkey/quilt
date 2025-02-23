# Changelog

## 4.1.1

### Patch Changes

- [`0b3737b7d`](https://github.com/Shopify/quilt/commit/0b3737b7dc7531055b5cba7239a8210bb5e95f22) Thanks [@BPScott](https://github.com/BPScott)! - No changes, this release is to test the new release process

## 4.1.0 - 2022-05-27

### Changed

- Move Atlas clients to atlas.shopifysvc.com [[#2271](https://github.com/Shopify/quilt/pull/2271)]

## 4.0.0 - 2022-05-19

### Breaking Change

- Drop support for node 12 and Safari 10, 11 and 12. Remove wildcard export in exports field. [[#2277](https://github.com/Shopify/quilt/pull/2277)]

## 3.0.10 - 2022-03-09

### Changed

- Correct wildcard export to `./*` [[#2209](https://github.com/Shopify/quilt/pull/2209)]

## 3.0.9 - 2022-02-25

### Changed

- Use `./*` instead of `./` in package.json exports to fix deprecation warning. [[#2184](https://github.com/Shopify/quilt/pull/2184)]

## 3.0.8 - 2022-02-01

### Changed

- Rerelease after failed publish. No code changes.

## 3.0.7 - 2022-02-01

### Changed

- Reorder exports map to prioritize the `esnext` condition. [[#2148](https://github.com/Shopify/quilt/pull/2148)]
- Update Loom build config. [[#2150](https://github.com/Shopify/quilt/pull/2150)]

## 3.0.6 - 2021-09-24

### Changed

- Migrate from `sewing-kit-next` to `loom` for building - package build output remains identical. [[#2039](https://github.com/Shopify/quilt/pull/2039)]

## 3.0.5 - 2021-08-24

### Changed

- Updated build tooling, types are now compiled with TypeScript 4.3. [[#1997](https://github.com/Shopify/quilt/pull/1997)]
- Added file exclusion for tests to package.json and enable type checking for tests. [[#2005](https://github.com/Shopify/quilt/pull/2005)]

## 3.0.4 - 2021-08-04

### Changed

- Ensure `tsconfig.tsbuildinfo` file is not uploaded to the npm registry. [[#1982](https://github.com/Shopify/quilt/pull/1982)]

## 3.0.3 - 2021-08-03

### Changed

- Update to latest sewing-kit-next for build. Update `types`/`typesVersions` fields to point directly into the build folder [[#1980](https://github.com/Shopify/quilt/pull/1980)]

## 3.0.2 - 2021-07-15

### Changed

- Replace [country-service](https://github.com/Shopify/country-service) with [atlas](https://github.com/Shopify/atlas) address service's GraphQL endpoint [#1965](https://github.com/Shopify/quilt/pull/1965)

## 3.0.0 - 2021-05-21

### Breaking Change

- Update minimum supported node version to 12.14.0. Add engines field to help enforce usage of this version. [#1906](https://github.com/Shopify/quilt/pull/1906)

## 2.2.4 - 2021-04-13

### Changed

- Removed dependency on tslib, as we no-longer compile with `tsc`. [#1829](https://github.com/Shopify/quilt/pull/1829)

## 2.2.2 - 2021-03-03

### Fixed

- Updated multi-build outputs to include mandatory extensions to fix "Module not found" issues reported by ESM supported bundlers [#1759](https://github.com/Shopify/quilt/pull/1759)

## 2.2.0 - 2020-12-18

### Added

- Add new build outputs (CommonJS, ESM, esnext, Node) for greater tree-shakability [#1698](https://github.com/Shopify/quilt/pull/1698)

## 2.1.1 - 2020-10-20

- Added `tslib@^1.14.1` in the list of dependencies. [#1657](https://github.com/Shopify/quilt/pull/1657)

## 2.1.0 - 2020-09-02

- Add `optionalLabels` to `Country` interface. [#1610](https://github.com/Shopify/quilt/pull/1610)

## 2.0.0 - 2020-03-10

- Add `errors` to `LoadCountriesResponse` and `LoadCountryResponse`. [#1301](https://github.com/Shopify/quilt/pull/1301)
- [⚠️Breaking Change] Update `ResponseError` to match GraphQl specification for Errors. [#1301](https://github.com/Shopify/quilt/pull/1301)

## 1.0.0 - 2019-08-29

### Added

- `@shopify/address-consts` package
