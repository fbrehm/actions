# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [2.4.0] - 2025-11-25

### Added

* Adding tests with Python 3.14.

### Changed

* Disabling a possible pointless data directory in workflow `pyproject-deploy-pypi`.

### Fixed

* Fixing workflow `pyproject-deploy-pypi`.

## [2.3.0] - 2025-11-24

### Changed

* Updating cleaning up data dir.

## [2.2.0] - 2025-11-24

### Fixed

* Fixing compilation of eventually existing localisation files.

## [2.1.0] - 2025-10-30

### Changed

* Changing generating of man pages from click-man to help2man.
* Show current locale in workflow `pyproject-python-tests`.
* Set correct locale on Python tests.
* Compiling locales in workflows `pyproject-build-debian-pkgs` and `pyproject-build-rpm-pkgs`.

### Fixed

* Fixing workflow `pyproject-check-env`.
* Fixing workflow `pyproject-build-rpm-pkgs` for installing help2man.
* Fixing workflow `pyproject-build-debian-pkgs` for installing help2man.

## [2.0.0] - 2025-09-24

### Added

* Adding actions  `compile-locales`, `deploy-pypi`, `prepare-debian-container`,
  `pyproject-get-entrypoints` and `pyproject-install-pip-modules`.
* Adding workflows `pyproject-build-debian-pkgs`, `pyproject-build-packages`, `pyproject-build-rpm-pkgs`,
  `pyproject-check-env`, `pyproject-deploy-pypi`, `pyproject-linter-tests` and `pyproject-python-tests`.

## [1.5.0] - 2025-04-17

### Fixed

* Fixed typo in workflow `build-python-debian-packages`.

## [1.4.0] - 2025-04-17

### Changed

* Renaming job titles.
* Updating the list of Python versions to test for.

## [1.3.0] - 2024-06-30

### Changed

* Uploading Python packages only for branches main, master, test* or on tags.
* Disabling forced linting of package __init__.py.

## [1.2.0] - 2024-06-23

### Changed

* Fixing workflow `exec-python-tests`.

### Removed

* Deleting languages in the Python test matrix
* Removing input `languages` from workflow exec-python-tests.

## [1.1.0] - 2024-06-19

### Changed

* Limiting job `deploy_to_repo` to execute only on tags.

## [1.0.0] - 2024-06-19

### Added

* Adding .yamllint.yaml.
* Adding action `add-own-yum-repo`.
* Adding workflows `build-python-debian-packages`, `build-python-packages`, `build-python-rpm-packages`,
  `deploy-to-pypi`, `deploy-to-reposerver`, `exec-python-tests`, `python-linter-tests` and `test`.

### Removed

* Removing actions `install-pip-modules` and `prepare-debian-container`.
* Removing workflow `pytest`.

## [0.1.0] - 2022-12-28

### Added

* Initial commit.

[2.4.0]: https://github.com/fbrehm/actions/compare/v2.3...v2.4
[2.3.0]: https://github.com/fbrehm/actions/compare/v2.2...v2.3
[2.2.0]: https://github.com/fbrehm/actions/compare/v2.1...v2.2
[2.1.0]: https://github.com/fbrehm/actions/compare/v2.0...v2.1
[2.0.0]: https://github.com/fbrehm/actions/compare/v1.5...v2.0
[1.5.0]: https://github.com/fbrehm/actions/compare/v1.4...v1.5
[1.4.0]: https://github.com/fbrehm/actions/compare/v1.3...v1.4
[1.3.0]: https://github.com/fbrehm/actions/compare/v1.2...v1.3
[1.2.0]: https://github.com/fbrehm/actions/compare/v1.1...v1.2
[1.1.0]: https://github.com/fbrehm/actions/compare/v1.0...v1.1
[1.0.0]: https://github.com/fbrehm/actions/compare/v0.1...v1.0
[0.1.0]: https://github.com/fbrehm/actions/tree/v0.1

