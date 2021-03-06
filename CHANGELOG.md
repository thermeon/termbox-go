# Change Log
All notable changes to this project will be documented in this file.
This project adheres to [Semantic Versioning](http://semver.org/).

## [Unreleased] - 0000-00-00
## [0.8.0] - 2018-03-29
### Added
- Add context to unsupported terminal error

## [0.7.0] - 2018-03-27
### Fixed
- Fix deadlock in goroutine that processed input when the input was grabbed

## [0.6.0] - 2018-03-26
### Fixed
- Further input block fix

## [0.5.0] - 2018-03-20
### Fixed
- Fix blocking of input when the input has been grabbed and data comes in too fast

## [0.4.0] - 2018-03-09
### Fixed
- Fixed cursor showing when it should be hidden

## [0.3.0] - 2018-03-02
### Added
- GrabTtyInput() to allow applications to read from the TTY without termbox processing events

## [0.2.0] - 2018-02-27
### Changed
- Reset the last used foreground and background colours in Sync() so they are re-sent to the terminal

## [0.1.0] - 2018-02-12
### Added
- Fork from [github.com/nsf/termbox-go](https://github.com/nsf/termbox-go/commit/88b7b944be8bc8d8ec6195fca97c5869ba20f99d)
- Add `ResetTerm()` function to allow re-initialisation of the terminal after Init()
