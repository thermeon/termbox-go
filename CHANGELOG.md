# Change Log
All notable changes to this project will be documented in this file.
This project adheres to [Semantic Versioning](http://semver.org/).

## [UNRELEASED] - 0000-00-00
### Added
- GrabTtyInput() to allow applications to read from the TTY without termbox processing events

## [0.2.0] - 2018-02-27
### Changed
- Reset the last used foreground and background colours in Sync() so they are re-sent to the terminal

## [0.1.0] - 2018-02-12
### Added
- Fork from [github.com/nsf/termbox-go](https://github.com/nsf/termbox-go/commit/88b7b944be8bc8d8ec6195fca97c5869ba20f99d)
- Add `ResetTerm()` function to allow re-initialisation of the terminal after Init()
