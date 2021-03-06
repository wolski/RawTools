# Changelog
All notable changes to RawTools will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.2.0] 2018-09-24
### Added
- Added support for X! Tandem as a search engine.
- Chromatograms of raw files can be exported as tab-delimited text files using `--chro` as an argument. See `RawTools.exe parse --help` for more info.

### Deprecated
- The `-i` argument for invoking an IdentiPy search has been deprecated and will not be available in future releases. Instead, please use `-s identipy` to
invoke an IdentiPy search. Other IdentiPy-related arguments will remain as-is.

### Changed
- The code for parsing IdentiPy results and calculating identification-based metrics has been reworked to facilitate compatibility with X!Tandem results files.
This should have no impact upon end-users, but will make it easier to add support for other search engines in the future if it is desired.

## [1.1.1] 2018-09-14
### Fixed
- Fixed a bug which occurs when no variable modifications are specified.

## [1.1.0] 2018-09-13
### Added
- Everything! But that isn't very informative, so check out the [wiki page](https://github.com/kevinkovalchik/RawTools/wiki) to learn about RawTools.
