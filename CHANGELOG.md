# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [0.2.0]
### Uncategorized
- chore: format changelog
- chore: add .nvmrc set to v12
- devDeps: remove unused ethjs-contract
- npm audit fix; npm dedupe
- devDeps: update mocha@3.1.2 -> ^6.2.3
- devDeps: cross-env@1.0.7->6.0.3
- rename package from ethjs-provider-http to @metamask/ethjs-provider-http
- deps: xhr2@0.1.3 -> 0.2.1
- npm v5 compat: rename prepublish script to prepare
- deprecate nodejs <8.17, npm<6
- devDeps: update web3@0.17.0-beta -> 0.20.7
- devDeps/test: ethereumjs-testrpc->ganache-cli
- devDeps: remove legacy check-es3-syntax-cli
- Remove Travis and coveralls.io integrations
- ci: Add GitHub Actions workflows
- update dist
- add package-lock.json

## [0.1.6]
### Changed
- Better handling of Errors like 405 etc..

## [0.1.3]
### Changed
- Config fix
- More docs

## [0.0.1]
### Added
- ethjs-provider-http
  - Basic testing
  - Basic docs
  - License

[Unreleased]: https://github.com/MetaMask/ethjs-provider-http/compare/v0.2.0...HEAD
[0.2.0]: https://github.com/MetaMask/ethjs-provider-http/compare/v0.1.6...v0.2.0
[0.1.6]: https://github.com/MetaMask/ethjs-provider-http/compare/v0.1.3...v0.1.6
[0.1.3]: https://github.com/MetaMask/ethjs-provider-http/compare/v0.0.1...v0.1.3
[0.0.1]: https://github.com/MetaMask/ethjs-provider-http/releases/tag/v0.0.1
