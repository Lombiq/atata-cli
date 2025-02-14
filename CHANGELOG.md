# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.3.0] - 2021-07-23

### Added

- Add `string WorkingDirectory` property to `CliCommandResult`.

### Changed

- Change the format of `CliCommandException` message.
  Add "Working directory" to message.

## [1.2.0] - 2021-07-21

### Added

- Add `HasError` property to `CliCommandResult`.
- Add `WithWorkingDirectory(string)` method to `ProgramCli` and `ProgramCli<TCli>`.
- Add `ExecuteRawAsync(string)` method to `ProgramCli`.

### Changed

- Change access modifier of `ProgramCli.ExecuteRaw(string)` method from `protected` to `public`.

## [1.1.0] - 2021-06-24

### Fixed

- Fix `bash` commands execution

## [1.0.0] - 2021-06-24

Initial version release.