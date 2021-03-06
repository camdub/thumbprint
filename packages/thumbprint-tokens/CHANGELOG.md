# Changelog

## Unreleased

### Changed

-   [Patch] Temporarily bring back removed Tokens to make it easier to migrate to `8.0.0`.

## 8.0.0 - 2019-05-24

### Changed

-   [Major] Rename [a handful of SCSS and JavaScipt tokens](https://github.com/thumbtack/thumbprint/pull/242).
-   [Patch] Change the internals of how tokens are stored and generated. This does not affect the outputted code.

## 7.0.0 - 2019-05-17

### Removed

-   [Major] Remove all deprecated tokens. Old values can be found on [a previous version of the Thumbprint site](https://5cdc5c977a1bb7000855f899--thumbprint.netlify.com/tokens/scss/).

## 6.3.4 - 2019-05-15

### Changed

-   [Patch] Remove the "name" field from tokens in their source files. This does not affect the outputted code.

## 6.3.3 - 2019-04-08

### Changed

-   [Minor] Add supported platforms to each token (#198)

## 6.3.2 - 2019-04-02

### Changed

-   [Patch] Simplify script that generates tokens.
-   [Patch] Under-the-hood changes that will allow for future tokens without a `tp` prefix.

## 6.3.1 - 2019-03-11

### Changed

-   [Patch] Remove notion of "private" tokens. They now all documented and can be used. (#145)

## 6.3.0 - 2019-02-07

### Added

-   [Minor] Add title type styles for sizes 6, 7, and 8. (#70)

## 6.2.4 - 2019-01-30

### Changed

-   [Patch] Use Apache License 2.0.

## 6.2.3 - 2018-11-27

### Changed

-   [Patch] Publish package to public NPM.

### Deprecated

-   [Patch] Deprecate the tokens in the "Avatar" section.
