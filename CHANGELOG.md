# Changelog

All notable changes to this project will be documented in this file. The format
is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/). This
project adheres to [Semantic Versioning](https://semver.org/).

## [Unreleased]

## [0.3.1] - 2026-04-29

### Changed

- Migrated `hjkl-buffer` from the `kryptic-sh/hjkl` monorepo into its own
  repository
  ([kryptic-sh/hjkl-buffer](https://github.com/kryptic-sh/hjkl-buffer)) with
  full git history preserved.
- Relaxed inter-crate dependency requirements from `=0.3.0` to `0.3` (caret),
  matching the standard SemVer pattern for library dependencies.
- Bumped `ratatui` to 0.30 (was 0.29) and `criterion` to 0.8 (was 0.5).

### Added

- Standalone `LICENSE`, `.gitignore`, and `ci.yml` workflow at the repo root.
