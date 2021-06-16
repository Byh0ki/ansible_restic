# Changelog

All notable changes to this project will be documented in this file.

## [unreleased] - since 1.4.1

## [1.4.1] - 2021-06-16

### Changed

- Allow hostname change per backup

### Fixed

- Fix typo in restore post hooks

## [1.4.0] - 2021-06-05

### Added

- Add compatibility for other CPU arch (arm, etc)

## [1.3.0] - 2021-05-17

### Changed

- Change `KO` tag for `FAIL` in mail alerting

## [1.2.0] - 2021-05-13

### Added

- Add option to disable logrotate if needed
- Add libnotify alerting for systemd desktops

### Changed

- Enhance default vars handling

### Fixed

- Add missing backup name in node exported metrics

## [1.1.0] - 2021-04-05

### Added

- Add compatibility for other distros

### Fixed

- Output was not sanitized for JSON based alerting

## [1.0.0] - 2021-04-01

### Added

- Checks for backend config
- Ability to disable pruning
- Ability to disable cron jobs

### Changed

- Update doc

## [0.2.0] - 2021-04-01

### Added

- Full alerting rework
- New alerting backends:
    - discord
    - healthchecks.io
    - mail
    - mattermost
    - node
    - rocketchat
    - slack
    - telegram
- This CHANGELOG file

## [0.1.0] - 2021-03-08

### Added

- All project:
    - multiple backup per host
    - multiple backends supported

[unreleased]: https://gitlab.cri.epita.fr/cri/iac/ansible/roles/restic/-/compare/1.4.1...master
[1.4.1]: https://gitlab.cri.epita.fr/cri/iac/ansible/roles/restic/-/compare/1.4.0...1.4.1
[1.4.0]: https://gitlab.cri.epita.fr/cri/iac/ansible/roles/restic/-/compare/1.3.0...1.4.0
[1.3.0]: https://gitlab.cri.epita.fr/cri/iac/ansible/roles/restic/-/compare/1.2.0...1.3.0
[1.2.0]: https://gitlab.cri.epita.fr/cri/iac/ansible/roles/restic/-/compare/1.1.0...1.2.0
[1.1.0]: https://gitlab.cri.epita.fr/cri/iac/ansible/roles/restic/-/compare/1.0.0...1.1.0
[1.0.0]: https://gitlab.cri.epita.fr/cri/iac/ansible/roles/restic/-/compare/0.2.0...1.0.0
[0.2.0]: https://gitlab.cri.epita.fr/cri/iac/ansible/roles/restic/-/compare/0.1.0...0.2.0
[0.1.0]: https://gitlab.cri.epita.fr/cri/iac/ansible/roles/restic/-/releases/0.1.0
