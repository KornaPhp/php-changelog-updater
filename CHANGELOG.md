# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased](https://github.com/stefanzweifel/php-changelog-updater/compare/v1.10.0...HEAD)

<!-- New Release notes will be placed here automatically -->
## [v1.10.0](https://github.com/stefanzweifel/php-changelog-updater/compare/v1.9.1...v1.10.0) - 2023-11-25

### Added

- Add Support for PHP 8.3 ([#47](https://github.com/stefanzweifel/php-changelog-updater/pull/47))

### Changed

- Remove outdated GitHubActions Output Syntax ([#46](https://github.com/stefanzweifel/php-changelog-updater/pull/46))
- Update README.md ([#48](https://github.com/stefanzweifel/php-changelog-updater/pull/48))

## [v1.9.1](https://github.com/stefanzweifel/php-changelog-updater/compare/v1.9.0...v1.9.1) - 2023-08-01

### Fixed

- Upgrade Dependencies to their latest versions ([#44](https://github.com/stefanzweifel/php-changelog-updater/pull/44))
- Fix GitHub Username pattern ([#43](https://github.com/stefanzweifel/php-changelog-updater/pull/43))

## [v1.9.0](https://github.com/stefanzweifel/php-changelog-updater/compare/v1.8.0...v1.9.0) - 2023-07-02

### Added

- Add new `--parse-github-usernames` option to parse and linkify GitHub Usernames ([#41](https://github.com/stefanzweifel/php-changelog-updater/pull/41))

## [v1.8.0](https://github.com/stefanzweifel/php-changelog-updater/compare/v1.7.0...v1.8.0) - 2023-05-29

### Added

- Add `--hide-release-date` option ([#39](https://github.com/stefanzweifel/php-changelog-updater/pull/39))

## [v1.7.0](https://github.com/stefanzweifel/php-changelog-updater/compare/v1.6.2...v1.7.0) - 2023-04-22

### Added

- Allow release-notes and latest-version options to be prompted ([#35](https://github.com/stefanzweifel/php-changelog-updater/pull/35))

### Changed

- Upgrade to Pest v2 ([#34](https://github.com/stefanzweifel/php-changelog-updater/pull/34))
- Upgrade to Laravel Zero v10 ([#33](https://github.com/stefanzweifel/php-changelog-updater/pull/33))

## [v1.6.2](https://github.com/stefanzweifel/php-changelog-updater/compare/v1.6.1...v1.6.2) - 2022-10-24

### Changed

- Build v1.6.2

## [v1.6.1](https://github.com/stefanzweifel/php-changelog-updater/compare/v1.6.0...v1.6.1) - 2022-10-24

### Changed

- Add Support for PHP 8.2 ([#31](https://github.com/stefanzweifel/php-changelog-updater/pull/31))
- Update CLI to use new GITHUB_OUTPUT environment ([#30](https://github.com/stefanzweifel/php-changelog-updater/pull/30))
- Bump min PHP version to 8.1 ([#28](https://github.com/stefanzweifel/php-changelog-updater/pull/28))

## [v1.6.0](https://github.com/stefanzweifel/php-changelog-updater/compare/v1.5.0...v1.6.0) - 2022-05-28

### Added

- Add `--heading-text` option to manipulate heading text ([#27](https://github.com/stefanzweifel/php-changelog-updater/pull/27))
- Shift Headings of Release Notes to always be at least level 3 headings ([#24](https://github.com/stefanzweifel/php-changelog-updater/pull/24))

### Changed

- Refactor Internals ([#26](https://github.com/stefanzweifel/php-changelog-updater/pull/26))

### Fixed

- Abort and show Error Message when Release Notes could not be placed ([#23](https://github.com/stefanzweifel/php-changelog-updater/pull/23))

## [v1.5.0](https://github.com/stefanzweifel/php-changelog-updater/compare/v1.4.1...v1.5.0) - 2022-03-20

## Added

- Add RELEASE_HEADING_FRAGMENT output ([#20](https://github.com/stefanzweifel/php-changelog-updater/pull/20))

## [v1.4.1](https://github.com/stefanzweifel/php-changelog-updater/compare/v1.4.0...v1.4.1) - 2022-03-20

## Fixed

- Fix detection of empty release notes ([#19](https://github.com/stefanzweifel/php-changelog-updater/pull/19))

## [v1.4.0](https://github.com/stefanzweifel/php-changelog-updater/compare/v1.3.0...v1.4.0) - 2022-03-19

## Added

- Output GitHub Actions Output Variables ([#18](https://github.com/stefanzweifel/php-changelog-updater/pull/18))
- Throw Warning if Release already exists in Changelog ([#16](https://github.com/stefanzweifel/php-changelog-updater/pull/16))

## Changed

- Make Release Notes Optional ([#17](https://github.com/stefanzweifel/php-changelog-updater/pull/17))

## [v1.3.0](https://github.com/stefanzweifel/php-changelog-updater/compare/v1.2.2...v1.3.0) - 2022-02-09

## Changed

- Upgrade to Laravel Zero 9 ([#15](https://github.com/stefanzweifel/php-changelog-updater/pull/15))

## [v1.2.2](https://github.com/stefanzweifel/php-changelog-updater/compare/v1.2.1...v1.2.2) - 2022-02-09

## Fixed

- Append release notes at the end if no previous heading can be found ([#14](https://github.com/stefanzweifel/php-changelog-updater/pull/14))

## [v1.2.1](https://github.com/stefanzweifel/php-changelog-updater/compare/v1.2.0...v1.2.1) - 2022-02-01

## Added

- New Build

## [v1.2.0](https://github.com/stefanzweifel/php-changelog-updater/compare/v1.1.1...v1.2.0) - 2022-02-01

## Added

- Add `--compare-url-target-revision` option ([#13](https://github.com/stefanzweifel/php-changelog-updater/pull/13))

## [v1.1.1](https://github.com/stefanzweifel/php-changelog-updater/compare/v1.1.0...v1.1.1) - 2021-11-25

## Changed

- Run Tests on PHP 8.1 ([#12](https://github.com/stefanzweifel/php-changelog-updater/pull/12))

## Fixed

- Upgrade commonmark-markdown-renderer to v1.0.2 ([#11](https://github.com/stefanzweifel/php-changelog-updater/pull/11))

## [v1.1.0](https://github.com/stefanzweifel/php-changelog-updater/compare/v1.0.0...v1.1.0) - 2021-11-07

## Added

- Validate Input Options [#10](https://github.com/stefanzweifel/php-changelog-updater/pull/10)
- Add Release Notes at the end if no heading was found [#9](https://github.com/stefanzweifel/php-changelog-updater/pull/9)
- Paste Release Notes at the top if no Unreleased Heading can be found [#7](https://github.com/stefanzweifel/php-changelog-updater/pull/7)

## Changed

- Refactor Internals (#8) @stefanzweifel

## [v1.0.0](https://github.com/stefanzweifel/php-changelog-updater/compare/v0.4.1...v1.0.0) - 2021-08-14

Release v1.0.0.

## [v0.4.1](https://github.com/stefanzweifel/php-changelog-updater/compare/v0.4.0...v0.4.1) - 2021-08-14

### Fixed

- Fallback to current date if `--release-date` is empty (empty string or null) [#5](https://github.com/stefanzweifel/php-changelog-updater/pull/5)

## [v0.4.0](https://github.com/stefanzweifel/php-changelog-updater/compare/v0.3.0...v0.4.0) - 2021-08-14

### Changed

- Make `--release-date` Option optional [#4](https://github.com/stefanzweifel/php-changelog-updater/pull/4)

## [v0.3.0](https://github.com/stefanzweifel/php-changelog-updater/compare/v0.2.1...v0.3.0) - 2021-08-12

### Removed

- Remove  option [#2](https://github.com/stefanzweifel/php-changelog-updater/pull/2)

## [v0.2.1](https://github.com/stefanzweifel/php-changelog-updater/compare/v0.2.0...v0.2.1) - 2021-08-07

### Changed

- Upgrade Dependencies

## [v0.2.0](https://github.com/stefanzweifel/php-changelog-updater/compare/v0.1.0...v0.2.0) - 2021-08-07

### Added

- Add  option

## [v0.1.0](https://github.com/stefanzweifel/php-changelog-updater/releases/tag/v0.1.0) - 2021-08-07

- Initial Release
