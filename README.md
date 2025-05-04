# Angkor Support

**Angkor common** support helpers, contracts, and traits required by various Angkor packages. Validator functionality, and basic controller included out-of-the-box.

[![Packagist](https://img.shields.io/packagist/v/angkor/laravel-support.svg?label=Packagist&style=flat-square)](https://packagist.org/packages/angkor/laravel-support)
[![License](https://img.shields.io/packagist/l/angkor/laravel-support.svg?label=License&style=flat-square)](https://github.com/angkor/laravel-support/blob/develop/LICENSE)

This package is a fork of the excellent [rinvex/laravel-support](https://github.com/rinvex/laravel-support) package by Rinvex. We are grateful for their work which serves as the foundation for this package.

> **Note:** this package is just a support package for other Angkor packages, which may not be useful on its own, but contains some complementary generic functionality and also may not respect SemVer and break backward compatibility.

## Installation

Install via `composer require angkor/laravel-support`

## Usage

### `mimetypes()` helper

The `mimetypes` method gets valid mime types:
```php
$mimetypes = mimetypes();
```

### `timezones()` helper

The `timezones` method gets valid timezones:
```php
$timezones = timezones();
```

### unique_with Validator Rule

This feature contains a variant of the `validateUnique` rule for Laravel, that allows for validation of multi-column UNIQUE indexes.

It was forked and merged from the awesome [felixkiss/uniquewith-validator](https://github.com/felixkiss/uniquewith-validator) package, which at the time been outdated and un-maintained for a long time. Many thanks to core contributors for developing this.

## Changelog

Refer to the [Changelog](CHANGELOG.md) for a full history of the project.

## Support

The following support channels are available at your fingertips:

- [Issues on GitHub](https://github.com/angkordotdev/laravel-support/issues)
- [Email Support](mailto:khmer@angkor.dev)

## Contributing & Protocols

Thank you for considering contributing to this project! The contribution guide can be found in [CONTRIBUTING.md](CONTRIBUTING.md).

Bug reports, feature requests, and pull requests are very welcome.

- [Versioning](CONTRIBUTING.md#versioning)
- [Pull Requests](CONTRIBUTING.md#pull-requests)
- [Coding Standards](CONTRIBUTING.md#coding-standards)
- [Feature Requests](CONTRIBUTING.md#feature-requests)
- [Git Flow](CONTRIBUTING.md#git-flow)

## Security Vulnerabilities

If you discover a security vulnerability within this project, please send an e-mail to [khmer@angkor.dev](mailto:khmer@angkor.dev). All security vulnerabilities will be promptly addressed.

## Credits

This package is a fork of [rinvex/laravel-support](https://github.com/rinvex/laravel-support) by [Rinvex](https://rinvex.com). Rinvex is a software solutions startup, specialized in integrated enterprise solutions for SMEs established in Alexandria, Egypt since June 2016. We extend our gratitude to the Rinvex team for their excellent work on the original package.

## License

This software is released under [The MIT License (MIT)](LICENSE).

(c) 2023-present Angkor Dev
(c) 2016-2022 Rinvex LLC

Some rights reserved.