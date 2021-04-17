# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](http://semver.org/spec/v2.0.0.html).

## Unreleased

### Added

- `api teardown` command to delete a single API hosting environment

### Changed

- `api serve` command to use `express` instead of `hapi`
- API deployment process to be synchronous

## [1.1.0] - 2021-04-17

### Changed

- documentation for sending emails from Hosted APIs

### Fixed

- `api serve` command not handling request payload and response payload correctly if they are not JSON

## [1.0.0] - 2021-04-17

Initial release
