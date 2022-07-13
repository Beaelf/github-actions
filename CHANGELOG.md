# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [2.0.2] - Unreleased

## [2.0.1] - 2021-05-06
### Fixed
- https://github.com/AfterShip/aftership-sdk-go/pull/32 `ShipmentWeights` changed to float64
 
## [2.0.0] - 2020-07-29
### Breaking Changes
- Go >= 1.13
- Completely reorganized the SDK, see [Migrations](https://github.com/AfterShip/aftership-sdk-go#migrations)
- Removed `auto retry` feature, consumers need to retry the request by themselves.
### Added
- Support latest features in v4 API
- Use `go mod` to organize the Go modules
- Error handling

[2.0.2]: https://github.com/AfterShip/aftership-sdk-go/compare/v2.0.2...HEAD
[2.0.1]: https://github.com/AfterShip/aftership-sdk-go/compare/v2.0.0...v2.0.1
[2.0.0]: https://github.com/AfterShip/aftership-sdk-go/releases/tag/v2.0.0
