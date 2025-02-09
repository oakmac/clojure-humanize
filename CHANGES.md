# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),

## 0.3 - UNRELEASED

### Added
- Tools build building and deployment
- Github actions CI
### Changed
- Update dependencies to the most recent versions.
- Switched to deps.edn
### Fixed
- Code cleanup (warnings generated by clj-kondo).
- Eliminate "already refers to" compiler warnings with Clojure 1.11.x.

[Closed Issues](https://github.com/trhura/clojure-humanize/milestone/3?closed=1)

## 0.2.2 - 15 Oct 2016

`clojure.contrib.inflect/datetime` now supports diffs that represent a 
time in the future, as well as _centuries_ and _millennia_ diffs.

Fix pluralizing nouns that end in _ff_.


## 0.2.1

`clojure.contrib.inflect/pluralize-noun` now pluralizes a count of zero; previously any count less
than or equal to 1 was considered singular.

Added `clojure.contrib.humanize/duration` and `duration-terms` to format a duration, in
milliseconds, as a string.
