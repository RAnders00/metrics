# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

<!-- next-header -->

## [Unreleased] - ReleaseDate

## [0.13.0] - 2021-01-22
### Added
- Support for specifying the unit of a measurement during registration. ([#107](https://github.com/metrics-rs/metrics/pull/107))

## [0.12.1] - 2019-11-21
### Changed
- Cost for macros dropped to almost zero when no recorder is installed. ([#55](https://github.com/metrics-rs/metrics/pull/55))

## [0.12.0] - 2019-10-18
### Changed
- Improved documentation. (#44, #45, #46)
- Renamed `Recorder::record_counter` to `increment_counter` and `Recorder::record_gauge` to `update_gauge`. ([#47](https://github.com/metrics-rs/metrics/pull/47))

## [0.11.1] - 2019-08-09
### Changed
- Fixed a bug with macros calling inner macros without a fully qualified name.

## [0.11.0] - 2019-07-29
### Added
- Life begins at 0.11.0 for this crate, after being renamed from `metrics-facade` to `metrics` to
  reflect the duality of `metrics` to the `log` crate. (#27)
