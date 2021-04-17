# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](http://semver.org/spec/v2.0.0.html).

## Unreleased

### Fixed

- something else

## [1.3.1] - 2021-04-17

### Dependencies

- no longer depend upon [got](https://www.npmjs.com/package/got)

## [1.3.0] - 2021-04-17

### Fixed

- `civicplus` entry point not using CivicPlus tenant

### Dependencies

- depend upon [got](https://www.npmjs.com/package/got) [11.8.2](https://github.com/sindresorhus/got/releases/tag/v11.8.2)

## [1.2.0] - 2021-04-17

### Added

- `api teardown` command to delete a single API hosting environment

### Changed

- `api serve` command to use `express` instead of `hapi`
- API deployment process to be synchronous

### Dependencies

- depend upon [node-fetch](https://www.npmjs.com/package/node-fetch) [2.6.1](https://github.com/node-fetch/node-fetch/releases/tag/v2.6.1)

## [1.1.0] - 2021-04-17

### Changed

- documentation for sending emails from Hosted APIs

### Fixed

- `api serve` command not handling request payload and response payload correctly if they are not JSON

## [1.0.0] - 2021-04-17

Initial release
