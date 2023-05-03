# BlizzardBags_ItemLevel Change Log
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/)
and this project adheres to [Semantic Versioning](http://semver.org/).

## [1.0.19-Release] 2023-05-03
- Updated for WoW 10.1.0.

## [1.0.18-Release] 2023-03-25
- Updated for WoW 10.0.7.

## [1.0.17-Release] 2023-01-26
- Updated for WoW 10.0.5.

## [1.0.16-Release] 2023-01-18
- Updated for WoW 3.4.1.

## [1.0.15-Release] 2022-12-08
### Fixed
- Fixed an issue where items relying on tooltipData sometimes would bug out in retail.

## [1.0.14-Release] 2022-12-06
### Fixed
- Fixed an issue with the retail combined frame updates that would cause only the update function of the last loaded of my bag addons to remain registered in memory, causing updates to fail.

## [1.0.13-Release] 2022-11-25
### Changed
- Now utilizes the C_TooltipInfo and TooltipUtil APIs in retail.

## [1.0.12-Release] 2022-11-16
- Bump to retail client patch 10.0.2.

## [1.0.11-Release] 2022-11-02
- Code cleanup.

## [1.0.10-Release] 2022-10-25
- Bumped retail version to the 10.0.0 patch.

## [1.0.9-Release] 2022-10-23
### Fixed
- Updated the API used in Dragonflight.

## [1.0.8-Release] 2022-10-06
### Changed
- Now shows the total number of slots instead of item level on containers.

## [1.0.7-Release] 2022-09-28
- Added Dragonflight support.

## [1.0.6-Release] 2022-09-07
### Added
- Added proper Wrath Classic support.

## [1.0.5-Release] 2022-08-17
- Bump to client patch 9.2.7.

## [1.0.4-Release] 2022-08-04
### Changed
- Move upgrade arrow on each display.

## [1.0.3-Release] 2022-07-28
### Fixed
- Fixed an incompatibility issue with BlizzardBags_BoE, which is soon to be released.

## [1.0.2-Release] 2022-07-28
### Changed
- Fixed the slightly faulty TOC addon description.
- Tweaked the performance slightly by removing some redundant function calls.

### Removed
- Removed no longer needed debug code to keep the performance as high as possible.

## [1.0.1-Release] 2022-07-27
- Initial commit.
