# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [3.1.2
### Fixed
- Installing with NC21

## [3.1.1] - 2021-03-01
### Changes
- Made Doctrine 3.0 compatible for PHP8 support in Nextcloud 21

## [3.1.0] - 2020-12-21
### Added
- Made 21 Compatible

## Changes
- Dependency updates
- Translation updates

## [3.0.0] - 2020-08-28
### Added
- Made 20 compatible

### Changes
- Moved to IBootstrap
- Dependency updates
- Translation updates

### Removed
- Removed 17, 18 and 19 comptatiblilty

## [2.3.0] - 2020-04-03
### Added
- Made 19 compatible
- Made activatable by admin

## [2.2.0] - 2019-12-05
### Added
- Made 18 compatible

## [2.1.1] - 2019-09-07
### Fixed
- Undefined index warning fixes

### Changes
- Updated dependencies
- Updated translations

## [2.1.0] - 2019-08-23
### Added
- Logout on rejecting the login

### Fixed
- Login on NC 17 due to missing cast

### Changed
- Updated dependencies
- Updated translations
- Use proper initial state API

## [2.0.0] - 2019-08-15
### Added
- Made compatible with NC17 notifier registration

### Changed
- Updated dependencies
- Updated translations
- Fixed translatable strings

### Removed
- Removed Nextcloud 15 support
- Removed Nextcloud 16 support

## [1.1.2] - 2019-07-11
### Added
- Make 17 compatible

### Fixed
- Updated dependencies
- Updated translations

## [1.1.1] - 2019-04-02
### Fixed
- Use an up to date git to tag

## [1.1.0] - 2019-04-02
### Added
- Deactivatable by admin

### Changed
- Updated translations
- Updated dependencies

## [1.0.3] - 2019-01-29
### Fixed
- Should really be IE11 compatible now

## [1.0.2] - 2019-01-07
### Changed
- Use the public interface for background jobs
- Updated translations
- Set supported databases (sqlite, mysql/mariadb, postgres)

### Fixed
- Should be compatible with IE now

## [1.0.1] - 2018-12-07
### Fixed
- Use provided user so the provider can always load

## [1.0.0] - 2018-12-07
### Added
- Nextcloud 16 support

### Changed
- App is now part of the 2FA settings like a 1st class citizen
- New and updated translations

### Removed
- Nextcloud 14 support

## [0.2.4] - 2018-10-23
### Added
- Added Notification Manager [#28](https://github.com/nickv-nextcloud/twofactor_nextcloud_notification/pull/28)
- Feedback when the login is approved on waiting screen [#29](https://github.com/nickv-nextcloud/twofactor_nextcloud_notification/issues/29)

## [0.2.3] - 2018-10-21
### Fixed
- Allow to disable provider properly as well [#27](https://github.com/nickv-nextcloud/twofactor_nextcloud_notification/pull/27)

## [0.2.2] - 2018-10-19
### Added
- Screenshots added [#15](https://github.com/nickv-nextcloud/twofactor_nextcloud_notification/issues/15)
- Prepare for translations [#20](https://github.com/nickv-nextcloud/twofactor_nextcloud_notification/issues/20)
- Added CHANGELOG.md

### Fixed
- Notifications expired attempts are cleaned up [#8](https://github.com/nickv-nextcloud/twofactor_nextcloud_notification/issues/8)

## [0.2.1] - 2018-10-18
### Fixed
- Made info.xml compliant

## [0.2.0] - 2018-10-18
### Added
- Basic provider implementation
