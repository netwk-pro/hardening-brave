<!-- =====================================================================
CHANGELOG.md

Copyright © 2025 Network Pro Strategies (Network Pro™)
SPDX-License-Identifier: CC-BY-4.0 OR GPL-3.0-or-later
This file is part of Network Pro.
====================================================================== -->

# Changelog

<!-- markdownlint-disable -->

All notable changes to this project will be documented in this file.

This project follows [Keep a Changelog](https://keepachangelog.com/en/1.1.0/).
Version numbers use a **SemVer-inspired** `MAJOR.MINOR.PATCH` format, with
version increments reflecting both user-visible and operational impact.

---

## [Unreleased]

---

## [1.1.1] - 2026-03-04

### Changed

- Bumped project version to `v1.1.1`.
- Updated front-end tooling dependencies:
  - `autoprefixer` `^10.4.23` → `^10.4.27`
  - `postcss` `^8.5.6` → `^8.5.8`
  - `stylelint-order` `^7.0.0` → `^7.0.1`
  - `prettier` `^3.7.4` → `^3.8.1`
  - `@eslint/js` `^9.39.2` → `^10.0.1`
  - `eslint` `^9.39.2` → `^10.0.2`
  - `globals` `^16.5.0` → `^17.4.0`
  - `stylelint` `^16.26.1` → `^17.4.0`
  - `stylelint-config-recommended` `^17.0.0` → `^18.0.0`
  - `markdownlint-cli2` `^0.20.0` → `^0.21.0`
- Updated Python dependencies:
  - `material-mkdocs` `9.7.0` → `9.7.4`

---

## [1.1.0] – 2025-12-17

### Added

- Added `vercel.json` to define Vercel build configuration and security headers.
- Added Vercel as a supported deployment target for this site.
- Added `VERSIONING.md` for clarity regarding how we implement versioning.

### Changed

- Updated `check:updates` and `upgrade` scripts in `package.json`.
- Added `simple-git-hooks` as a devDependency and added configuration to `package.json`.
- Updated GitHub Actions workflows to use `actions/checkout@v6`:
  - `.github/workflows/backup-branch.yml`
  - `.github/workflows/dependency-review.yml`
- Migrated static site deployment from Netlify to Vercel.
- Converted Netlify build configuration (`netlify.toml`) to Vercel-equivalent settings.
- Updated MkDocs build invocation to use `python -m mkdocs` for improved compatibility in CI environments.
- Explicitly configured the build output directory as `build/`.
- Preserved existing Content Security Policy (CSP), reporting endpoints, and security headers under Vercel.
- Bumped project version to `v1.1.0`.
- Updated frontend tooling dependencies:
  - `@eslint/js` `^9.39.1` → `^9.39.2`
  - `autoprefixer` `^10.4.22` → `^10.4.23`
  - `browserslist` `^4.28.0` → `^4.28.1`
  - `eslint` `^9.39.1` → `^9.39.2`
  - `prettier` `^3.6.2` → `^3.7.4`
  - `stylelint` `^16.25.0` → `^16.26.1`
  - `markdownlint` `^0.39.0` → `^0.40.0`
  - `markdownlint-cli2` `^0.19.0` → `^0.20.0`

### Removed

- Removed `netlify.toml`, as Netlify is no longer the active deployment platform.
- Removed reliance on Netlify-specific header configuration in favor of Vercel headers.

---

<!-- Link references -->

[Unreleased]: https://github.com/netwk-pro/privacy-apps/compare/v1.1.1...HEAD
[1.1.1]: https://github.com/netwk-pro/privacy-apps/releases/tag/v1.1.1
[1.1.0]: https://github.com/netwk-pro/privacy-apps/releases/tag/v1.1.0
