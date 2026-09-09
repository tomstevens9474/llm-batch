# Changelog

All notable changes are documented here.
Format follows keepachangelog.com, versions are semver-ish.

## [0.4.7] - 2026-06-27

### Fixed
- crash on paths containing spaces
- edge case when the input list is empty

### Changed
- progress output now goes to stderr

## [0.3.0] - 2026-06-24

### Added
- 4xx fails fast; 429 and 5xx retry with jittered backoff

## [0.2.0] - 2026-04-15

### Added
- 4xx fails fast; 429 and 5xx retry with jittered backoff

## [0.1.0] - 2026-04-16

### Added
- first working version
