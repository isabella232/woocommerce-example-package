# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [0.0.6] - 2019-03-11
### Added
- White flag `wc_esc_json()` on `WordPress.Security.EscapeOutput`.

## [0.0.5] - 2018-11-20
### Changed
- Replaced "phpcompatibility/php-compatibility" to "phpcompatibility/phpcompatibility-wp".

## [0.0.4] - 2018-11-19
### Changed
- Updated "wp-coding-standards/wpcs" to version 1.2.

### Fixed
- Coding standards.

## [0.0.3] - 2018-11-06
### Added
- Included "phpcompatibility/php-compatibility" 9.0 as a dependency.
- Included "dealerdirect/phpcodesniffer-composer-installer" 0.5 as dependency.
- New custom message for `@category`.

### Changes
- Updated ruleset.xml with default validate and escape functions, also including default rules.

## [0.0.2] - 2018-03-22
### Added
- `@access` tag is prohibited now.

## 0.0.1 - 2017-12-21
### Added
- Initial code to throw warnings when using `@author`, `@category`, `@license` and `@copyright` tags.

[Unreleased]: https://github.com/woocommerce/woocommerce-sniffs/compare/0.0.6...HEAD
[0.0.6]: https://github.com/woocommerce/woocommerce-sniffs/compare/0.0.5...0.0.6
[0.0.5]: https://github.com/woocommerce/woocommerce-sniffs/compare/0.0.4...0.0.5
[0.0.4]: https://github.com/woocommerce/woocommerce-sniffs/compare/0.0.3...0.0.4
[0.0.3]: https://github.com/woocommerce/woocommerce-sniffs/compare/0.0.2...0.0.3
[0.0.2]: https://github.com/woocommerce/woocommerce-sniffs/compare/0.0.1...0.0.2
