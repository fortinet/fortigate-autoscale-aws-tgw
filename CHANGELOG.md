# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.1.3] - 2020-01-23
### Changed
- Fix error related to updating the AutoscaleRole tag

## [1.1.2] - 2020-01-09
### Added
- Tag the current master FortiGate with AutoscaleRole whenever master role has changed.

### Changed
- update lambda function runtime version from 8.10 to 12.x

## [1.1.1] - 2019-11-01
### Changed
- Rename the label for S3KeyPrefix to S3ResourceFolder.
- Disabled source / destination checking on FortiGate instance & eni by default.

## [1.1.0] - 2019-10-07
### Added
- A link to the official documentation site to README.md
- Support for FortiOS 6.2.1

### Changed
- Template improvement and minor bugfix on template.
- To allow slave nodes to initially start without a master-ip and automatically get the master-ip
  later.

### Removed
- Temporarily removed support for FortiOS 6.0.x until a further version.
