# Changelog

## [0.11.2](https://github.com/hugomods/images/compare/v0.11.1...v0.11.2) (2024-08-26)


### Bug Fixes 🐞

* do not generate warning messages for unsupported formats ([4e6b050](https://github.com/hugomods/images/commit/4e6b0508dcad15d179d1ca5273240c5a51eba76c))

## [0.11.1](https://github.com/hugomods/images/compare/v0.11.0...v0.11.1) (2024-08-26)


### Bug Fixes 🐞

* allow using SVG and Avif images, but do not apply any filters on them ([#59](https://github.com/hugomods/images/issues/59)) ([7b8dc1d](https://github.com/hugomods/images/commit/7b8dc1db124a8e4f6fc189c896a1fcaab7a3e25a))

## [0.11.0](https://github.com/hugomods/images/compare/v0.10.1...v0.11.0) (2024-06-18)


### Features ✨

* allow specifying quality for resize method ([#54](https://github.com/hugomods/images/issues/54)) ([c7524e3](https://github.com/hugomods/images/commit/c7524e3a196931d3962bdd06b45fc72aab34437b))

## [0.10.1](https://github.com/hugomods/images/compare/v0.10.0...v0.10.1) (2024-03-15)


### Bug Fixes 🐞

* check if the image resource media type is avif and print error when necessary ([8afe41e](https://github.com/hugomods/images/commit/8afe41efb8c510967227657ed0f56a9b653c7dce))
* do not apply imageConfig on avif and jxl images ([#48](https://github.com/hugomods/images/issues/48)) ([767df64](https://github.com/hugomods/images/commit/767df64ef1817eb789791318e232fc888778ef36))
* set the caption as title if present ([#50](https://github.com/hugomods/images/issues/50)) ([59b9b9f](https://github.com/hugomods/images/commit/59b9b9f0baf528b8fcd96ce920587c32cbd14717))

## [0.10.0](https://github.com/hugomods/images/compare/v0.9.3...v0.10.0) (2024-03-09)


### Features ✨

* add the naturalWidth and naturalHeight query parameters for external images ([465897a](https://github.com/hugomods/images/commit/465897a1710c052991347a04e3921600f03e63c4))


### Bug Fixes 🐞

* add unit for width and height inline style attributes ([461c269](https://github.com/hugomods/images/commit/461c269f8fd2f3db5c6aae37bf02191a05fedc25))
* remove unit from width and height attributes for public images ([#46](https://github.com/hugomods/images/issues/46)) ([461c269](https://github.com/hugomods/images/commit/461c269f8fd2f3db5c6aae37bf02191a05fedc25))

## [0.9.3](https://github.com/hugomods/images/compare/v0.9.2...v0.9.3) (2024-03-08)


### Bug Fixes 🐞

* use _funcs/get-page-images for getting thumbnail images ([742fc49](https://github.com/hugomods/images/commit/742fc491c2e3e119a7c58a6083f0536e6405ac47))

## [0.9.2](https://github.com/hugomods/images/compare/v0.9.1...v0.9.2) (2024-02-28)


### Bug Fixes 🐞

* use RelPermalink instead of Permalink ([#43](https://github.com/hugomods/images/issues/43)) ([99899b0](https://github.com/hugomods/images/commit/99899b063a025a4d7dfd49d089443386bbe855bb))

## [0.9.1](https://github.com/hugomods/images/compare/v0.9.0...v0.9.1) (2024-02-22)


### Bug Fixes 🐞

* use Permalink instead of RelPermalink for modern formatted images ([#41](https://github.com/hugomods/images/issues/41)) ([46d32ca](https://github.com/hugomods/images/commit/46d32ca383d2d4010c506dd5b3743dac86e73309))

## [0.9.0](https://github.com/hugomods/images/compare/v0.8.4...v0.9.0) (2024-01-13)


### Features ✨

* add more parameters for image partial, Height, Width and Alignment ([#39](https://github.com/hugomods/images/issues/39)) ([e0723aa](https://github.com/hugomods/images/commit/e0723aaac7bc20528f8ffc0fbf21ce87f9ca0cac))


### Bug Fixes 🐞

* broken width and height values ([#36](https://github.com/hugomods/images/issues/36)) ([e3bc1b6](https://github.com/hugomods/images/commit/e3bc1b64c38a827282b2c7e7efe3d3b4b7c8507a))
* remove unit from width and height attributes ([#38](https://github.com/hugomods/images/issues/38)) ([ddfe37b](https://github.com/hugomods/images/commit/ddfe37bffffbf010cecde200901b9d876a973120))

## [0.8.4](https://github.com/hugomods/images/compare/v0.8.3...v0.8.4) (2024-01-08)


### Bug Fixes 🐞

* remove invalid indentations and empty line break, so that the partial can be used in nested shortcode ([#33](https://github.com/hugomods/images/issues/33)) ([30f968b](https://github.com/hugomods/images/commit/30f968b65c67214c8937c76012455f8f4c515547))

## [0.8.3](https://github.com/hugomods/images/compare/v0.8.2...v0.8.3) (2023-11-08)


### Bug Fixes 🐞

* rename the images site parameter to hugomods.images ([#27](https://github.com/hugomods/images/issues/27)) ([6560be2](https://github.com/hugomods/images/commit/6560be2b3cc1c97bec805c19628db965062171ec)), closes [#26](https://github.com/hugomods/images/issues/26)

## [0.8.2](https://github.com/hugomods/images/compare/v0.8.1...v0.8.2) (2023-11-02)


### Bug Fixes 🐞

* correct broken fingerprint links on multihost ([#24](https://github.com/hugomods/images/issues/24)) ([3c7e24c](https://github.com/hugomods/images/commit/3c7e24c64e9c726a5c85e2d37d09e370fc19381a))

## [0.8.1](https://github.com/hugomods/images/compare/v0.8.0...v0.8.1) (2023-11-01)


### Bug Fixes 🐞

* do not format gif as webp ([#21](https://github.com/hugomods/images/issues/21)) ([bb86cf1](https://github.com/hugomods/images/commit/bb86cf1f28870e59e76818886abdd27ba69cd76d))

## [0.8.0](https://github.com/hugomods/images/compare/v0.7.0...v0.8.0) (2023-10-07)


### Features ✨

* add support for the opacity filter ([26371df](https://github.com/hugomods/images/commit/26371dfb3383c6e74505fb43121fa1d5cf6cf946))

## [0.7.0](https://github.com/hugomods/images/compare/v0.6.0...v0.7.0) (2023-07-03)


### Features

* add the page-thumbnail function ([44a4001](https://github.com/hugomods/images/commit/44a40016483b79128277f110009f0fcb11e6c360))
* add the Style parameter for additional inline style ([40e720d](https://github.com/hugomods/images/commit/40e720df8b92435634184f8c6a19d9e66e13c52f))

## [0.6.0](https://github.com/hugomods/images/compare/v0.5.1...v0.6.0) (2023-07-01)


### Features

* display the caption if present ([2e7d08d](https://github.com/hugomods/images/commit/2e7d08dbf620e4c0ef3d14d0de28773aa3a1195f))
