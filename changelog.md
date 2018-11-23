﻿# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
    and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [0.9.525] - 2018-11-23
### Added
- CROSS PLATFORM SUPPORT INCLUDING MACOS AND LINUX 🎉

![image](https://user-images.githubusercontent.com/8278033/48960127-ac3c3980-ef6a-11e8-90ca-1e8e56df8ee0.png)

## [0.9.524] - 2018-11-23
### Added
- $script:core for easy core detection in functions

### Fixed
- Resolve-Path added to core import routine

## [0.9.523] - 2018-11-23
### Added
- Support for Dacfx for core 🎉

### Fixed
- Weird thing in Core where a string comparison didn't work so it tried to copy dbatools.dll onto itself
- Get-DbaDbFile now works for CS collation

## [0.9.522] - 2018-11-23
### Added
- Support for PS Core on Windows 🎉
- SMO core DLLs from the SqlServer module

### Fixed
- AG versioning bugs

## [0.9.521] - 2018-11-22
### Added
- This changelog.md! 🎉

### Removed
- Extra DLLs that did not seem necessary

### Changed
- Updated Glen Berry's scripts


## changelog info for now becauese i forget

### Types of changes
* Added for new features.
* Changed for changes in existing functionality.
* Deprecated for soon-to-be removed features.
* Removed for now removed features.
* Fixed for any bug fixes.
* Security in case of vulnerabilities.

### Guiding Principles
* Changelogs are for humans, not machines.
* There should be an entry for every single version.
* The same types of changes should be grouped.
* Versions and sections should be linkable.
* The latest version comes first.
* The release date of each version is displayed.
* Mention whether you follow Semantic Versioning.