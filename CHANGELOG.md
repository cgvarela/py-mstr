# Change Log
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/)
and this project adheres to [Semantic Versioning](http://semver.org/).

## [0.2.0] - 2017-12-08

### Added
- Miscellaneous repo quality improvements:
  - Added monitoring of code coverage using CodeCov
  - Fixed various linting errors
  - Added more classifiers to `setup.py`

### Changed
- FIX: Updated `install_requires` to require `pyquery` < 1.3.0 since 1.3.0 is not compatible with `py-mstr`
- FIX: Updated `maxCols` in tests to reflect update in 0.1.1

### Removed
- Dropped Python 2.6 support

## [0.1.1] - 2015-07-27

### Changed
- Increased report execute `max_cols` from 10 to 255
- Loosened `install_requires` to allow newer versions of `pyquery` and `requests`

## [0.1.0] - 2014-07-31

### Added
- Ability to connect to MicroStrategy Web Task API
  - Most critical methods available through the API have been implemented, including the ability to execute a report with or without prompts
- Initial tests
- Initial documentation