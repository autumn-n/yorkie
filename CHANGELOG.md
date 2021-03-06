# Changelog

All notable changes to Yorkie will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and Yorkie adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [0.1.1] - 2021-01-01

### Added
 - Add version tag when pushing image: #102
 - Add garbage collection for TextElement: #104

### Changed
 - Use multi-stage build for docker image: #107
 - Wrap additional information to sentinel errors: #129
 - Use status for one-dimensional value: #131
 - Remove panics in the converter: #132, #135
 
### Fixed
 - Fix check already attached document: #111
 - Delete removed elements from the clone while running GC: #103
 - Fix to use internal document when pulling snapshot from agent: #120

## [0.1.0] - 2020-11-07

First public release

### Added
 - Add basic structure of Yorkie such as `Document`, `Client`, and Agent(`yorkie`)
 - Add Custom CRDT data type `Text` for code editor: #2
 - Add Snapshot API to reduce payload: #9
 - Add Garbage Collection to clean CRDT meta: #3
 - Add Custom CRDT data type `RichText` for WYSIWYG editor: #7
 - Add Peer Awareness API: #48
 - Add Prometheus metrics: #76
 - Add Custom CRDT data type `Counter`: #82

### Changed

### Removed
 
### Deprecated

[Unreleased]: https://github.com/yorkie-team/yorkie/compare/v0.1.0...HEAD
[0.1.0]: https://github.com/yorkie-team/yorkie/releases/tag/v0.1.0# 
