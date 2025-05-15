# Changelog

## [3.0.0](https://github.com/genesiscz/laravel-openapi/compare/v2.1.2...v3.0.0) (2025-05-15)


### ⚠ BREAKING CHANGES

* requires Laravel 11

### Features

* allow overriding global servers in Operations ([0b8e62e](https://github.com/genesiscz/laravel-openapi/commit/0b8e62efa5988331f8f7a6453d3c5200e87bb4f9))
* **deps:** support laravel 11 ([#6](https://github.com/genesiscz/laravel-openapi/issues/6)) ([278031d](https://github.com/genesiscz/laravel-openapi/commit/278031da0d02bcc6b204ab61390e7e4c91de391d))
* move security requirements to a dedicated attribute ([#34](https://github.com/genesiscz/laravel-openapi/issues/34)) ([033c354](https://github.com/genesiscz/laravel-openapi/commit/033c354c47cab100d0bbb0354d4f0709e0484379))


### Bug Fixes

* 27 ([c794448](https://github.com/genesiscz/laravel-openapi/commit/c7944483c6a4d03e238b0e04ca6e7098bcd88ef2))
* 30 ([ace1e0e](https://github.com/genesiscz/laravel-openapi/commit/ace1e0e90b5345c98d2c985a4e284ead5760720d))
* 31 ([b246145](https://github.com/genesiscz/laravel-openapi/commit/b246145ec5cc91a18abea37f29f6bbf8da8a4cd1))
* check if 'actionDocBlock' is null  ([#43](https://github.com/genesiscz/laravel-openapi/issues/43)) ([033d21c](https://github.com/genesiscz/laravel-openapi/commit/033d21ccb221f45ee55d8ec0599d64bb28fff8f0))
* Corrected SchemaFactoryMakeCommand.php to work with Laravel 11 ([#15](https://github.com/genesiscz/laravel-openapi/issues/15)) ([b0f57cf](https://github.com/genesiscz/laravel-openapi/commit/b0f57cf0b56a0edbe686a0202631e9cfc9b8283a))
* deprecation warning with Str::lower() ([#36](https://github.com/genesiscz/laravel-openapi/issues/36)) ([a92b4ce](https://github.com/genesiscz/laravel-openapi/commit/a92b4ce171daa721c94da23e42bf02c4f5896951))
* security schema example ([fb0ff44](https://github.com/genesiscz/laravel-openapi/commit/fb0ff4455041a9b79232dfbc84794cde2323cb50))
* styleci ([a15a2de](https://github.com/genesiscz/laravel-openapi/commit/a15a2de03f3373f80bc8cfb8c0102e6e7d035b13))
* styleci ([695de97](https://github.com/genesiscz/laravel-openapi/commit/695de97810d5b0880c40c5ec558f3507abb94e6e))


### Performance Improvements

* **memoization:** add memoization for build referencable schemas ([#30](https://github.com/genesiscz/laravel-openapi/issues/30)) ([7657892](https://github.com/genesiscz/laravel-openapi/commit/765789290c4b43dedf3f7e4f96ef32cbe82a9087))


### Miscellaneous Chores

* **deps:** Support PHP 8.4 and Laravel 12 ([#39](https://github.com/genesiscz/laravel-openapi/issues/39)) ([c1eae1d](https://github.com/genesiscz/laravel-openapi/commit/c1eae1d680b1f36579f8a3c416dd6adf7883f3f9))
* **deps:** update actions/checkout action to v4 ([#3](https://github.com/genesiscz/laravel-openapi/issues/3)) ([c4b4794](https://github.com/genesiscz/laravel-openapi/commit/c4b479401102b88bd6e6ea06ba2610288dbb292d))
* **deps:** update actions/setup-node action to v4 ([#7](https://github.com/genesiscz/laravel-openapi/issues/7)) ([e53fc5e](https://github.com/genesiscz/laravel-openapi/commit/e53fc5e09aadbbc40f63cfa236155e57a23630a6))
* **deps:** update dependency vuepress to v1.9.10 ([#2](https://github.com/genesiscz/laravel-openapi/issues/2)) ([9d80e06](https://github.com/genesiscz/laravel-openapi/commit/9d80e069c75cb65fe73a5fcd6f994e3c453a15f7))
* **main:** release 1.13.0 ([#5](https://github.com/genesiscz/laravel-openapi/issues/5)) ([6ea0005](https://github.com/genesiscz/laravel-openapi/commit/6ea0005c1183cf645c88b361db816c9e5b33f6be))
* **main:** release 1.13.1 ([#9](https://github.com/genesiscz/laravel-openapi/issues/9)) ([ee541c2](https://github.com/genesiscz/laravel-openapi/commit/ee541c236aaf052d49a64442f3c3fbd8c8812977))
* **main:** release 2.0.0 ([#19](https://github.com/genesiscz/laravel-openapi/issues/19)) ([ea03e44](https://github.com/genesiscz/laravel-openapi/commit/ea03e44ce69241cd9f3d3eaf91f74105b6ce1653))
* **main:** release 2.0.1 ([#31](https://github.com/genesiscz/laravel-openapi/issues/31)) ([2856adf](https://github.com/genesiscz/laravel-openapi/commit/2856adfb18158fcc964b029ecb61be58c0675f80))
* **main:** release 2.1.0 ([#37](https://github.com/genesiscz/laravel-openapi/issues/37)) ([e931f85](https://github.com/genesiscz/laravel-openapi/commit/e931f859718cdb73473b0105fe1138a243224e20))
* **main:** release 2.1.1 ([#42](https://github.com/genesiscz/laravel-openapi/issues/42)) ([58760a8](https://github.com/genesiscz/laravel-openapi/commit/58760a870dabc49e55f2c5c1235df18447b45006))
* **main:** release 2.1.2 ([#44](https://github.com/genesiscz/laravel-openapi/issues/44)) ([64c2098](https://github.com/genesiscz/laravel-openapi/commit/64c20987ffcdadf2b4034c565349c0341c14af29))
* remove doctrine ([#17](https://github.com/genesiscz/laravel-openapi/issues/17)) ([ae4695e](https://github.com/genesiscz/laravel-openapi/commit/ae4695e9973fe6b9e70c4c132bdc324c57075635))

## [2.1.2](https://github.com/Nova-Edge/laravel-openapi/compare/v2.1.1...v2.1.2) (2025-03-31)


### Bug Fixes

* check if 'actionDocBlock' is null  ([#43](https://github.com/Nova-Edge/laravel-openapi/issues/43)) ([033d21c](https://github.com/Nova-Edge/laravel-openapi/commit/033d21ccb221f45ee55d8ec0599d64bb28fff8f0))

## [2.1.1](https://github.com/Nova-Edge/laravel-openapi/compare/v2.1.0...v2.1.1) (2025-02-24)


### Miscellaneous Chores

* **deps:** Support PHP 8.4 and Laravel 12 ([#39](https://github.com/Nova-Edge/laravel-openapi/issues/39)) ([c1eae1d](https://github.com/Nova-Edge/laravel-openapi/commit/c1eae1d680b1f36579f8a3c416dd6adf7883f3f9))

## [2.1.0](https://github.com/Nova-Edge/laravel-openapi/compare/v2.0.1...v2.1.0) (2025-02-03)


### Features

* move security requirements to a dedicated attribute ([#34](https://github.com/Nova-Edge/laravel-openapi/issues/34)) ([033c354](https://github.com/Nova-Edge/laravel-openapi/commit/033c354c47cab100d0bbb0354d4f0709e0484379))


### Bug Fixes

* deprecation warning with Str::lower() ([#36](https://github.com/Nova-Edge/laravel-openapi/issues/36)) ([a92b4ce](https://github.com/Nova-Edge/laravel-openapi/commit/a92b4ce171daa721c94da23e42bf02c4f5896951))

## [2.0.1](https://github.com/Nova-Edge/laravel-openapi/compare/v2.0.0...v2.0.1) (2024-12-09)


### Performance Improvements

* **memoization:** add memoization for build referencable schemas ([#30](https://github.com/Nova-Edge/laravel-openapi/issues/30)) ([7657892](https://github.com/Nova-Edge/laravel-openapi/commit/765789290c4b43dedf3f7e4f96ef32cbe82a9087))

## [2.0.0](https://github.com/Nova-Edge/laravel-openapi/compare/v1.13.1...v2.0.0) (2024-08-02)


### ⚠ BREAKING CHANGES

* requires Laravel 11

### Miscellaneous Chores

* remove doctrine ([#17](https://github.com/Nova-Edge/laravel-openapi/issues/17)) ([ae4695e](https://github.com/Nova-Edge/laravel-openapi/commit/ae4695e9973fe6b9e70c4c132bdc324c57075635))

## [1.13.1](https://github.com/Nova-Edge/laravel-openapi/compare/v1.13.0...v1.13.1) (2024-07-13)


### Bug Fixes

* Corrected SchemaFactoryMakeCommand.php to work with Laravel 11 ([#15](https://github.com/Nova-Edge/laravel-openapi/issues/15)) ([b0f57cf](https://github.com/Nova-Edge/laravel-openapi/commit/b0f57cf0b56a0edbe686a0202631e9cfc9b8283a))


### Miscellaneous Chores

* **deps:** update actions/setup-node action to v4 ([#7](https://github.com/Nova-Edge/laravel-openapi/issues/7)) ([e53fc5e](https://github.com/Nova-Edge/laravel-openapi/commit/e53fc5e09aadbbc40f63cfa236155e57a23630a6))
* **deps:** update dependency vuepress to v1.9.10 ([#2](https://github.com/Nova-Edge/laravel-openapi/issues/2)) ([9d80e06](https://github.com/Nova-Edge/laravel-openapi/commit/9d80e069c75cb65fe73a5fcd6f994e3c453a15f7))

## [1.13.0](https://github.com/Nova-Edge/laravel-openapi/compare/v1.12.0...v1.13.0) (2024-04-12)


### Features

* **deps:** support laravel 11 ([#6](https://github.com/Nova-Edge/laravel-openapi/issues/6)) ([278031d](https://github.com/Nova-Edge/laravel-openapi/commit/278031da0d02bcc6b204ab61390e7e4c91de391d))


### Miscellaneous Chores

* **deps:** update actions/checkout action to v4 ([#3](https://github.com/Nova-Edge/laravel-openapi/issues/3)) ([c4b4794](https://github.com/Nova-Edge/laravel-openapi/commit/c4b479401102b88bd6e6ea06ba2610288dbb292d))
