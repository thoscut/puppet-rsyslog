# Changelog

All notable changes to this project will be documented in this file.
Each new release typically also includes the latest modulesync defaults.
These should not affect the functionality of the module.

## [v4.0.0](https://github.com/voxpupuli/puppet-rsyslog/tree/v4.0.0) (2019-10-20)

[Full Changelog](https://github.com/voxpupuli/puppet-rsyslog/compare/v3.3.0...v4.0.0)

**Breaking changes:**

- modulesync 2.7.0 and drop puppet 4 [\#115](https://github.com/voxpupuli/puppet-rsyslog/pull/115) ([bastelfreak](https://github.com/bastelfreak))

**Implemented enhancements:**

- Add remaining rsyslog module types [\#111](https://github.com/voxpupuli/puppet-rsyslog/pull/111) ([dhollinger](https://github.com/dhollinger))
- Rsyslog Action Data Types and Queue Options [\#106](https://github.com/voxpupuli/puppet-rsyslog/pull/106) ([dhollinger](https://github.com/dhollinger))

**Fixed bugs:**

- Ruleset expression filter: problem with documention [\#112](https://github.com/voxpupuli/puppet-rsyslog/issues/112)
- Allow puppetlabs/concat 6.x, puppetlabs/stdlib 6.x [\#120](https://github.com/voxpupuli/puppet-rsyslog/pull/120) ([dhoppe](https://github.com/dhoppe))

**Closed issues:**

- How to use conditions ? [\#117](https://github.com/voxpupuli/puppet-rsyslog/issues/117)
- /etc/rsyslog.d/50\_rsyslog.conf doesn't have a puppet header [\#92](https://github.com/voxpupuli/puppet-rsyslog/issues/92)

**Merged pull requests:**

- Clean up acceptance spec helper [\#132](https://github.com/voxpupuli/puppet-rsyslog/pull/132) ([ekohl](https://github.com/ekohl))
- Add EL 8 support [\#129](https://github.com/voxpupuli/puppet-rsyslog/pull/129) ([dhollinger](https://github.com/dhollinger))
- Generate REFERENCE.md [\#128](https://github.com/voxpupuli/puppet-rsyslog/pull/128) ([bastelfreak](https://github.com/bastelfreak))
- Add Input module data types [\#125](https://github.com/voxpupuli/puppet-rsyslog/pull/125) ([dhollinger](https://github.com/dhollinger))
- types updates [\#124](https://github.com/voxpupuli/puppet-rsyslog/pull/124) ([kenyon](https://github.com/kenyon))
- base.pp: add final newline to rsyslog.conf [\#123](https://github.com/voxpupuli/puppet-rsyslog/pull/123) ([kenyon](https://github.com/kenyon))
- More input module data types [\#119](https://github.com/voxpupuli/puppet-rsyslog/pull/119) ([dhollinger](https://github.com/dhollinger))
- Fix template output if value is array [\#118](https://github.com/voxpupuli/puppet-rsyslog/pull/118) ([waipeng](https://github.com/waipeng))
- Allow puppetlabs/apt 7.x [\#116](https://github.com/voxpupuli/puppet-rsyslog/pull/116) ([dhoppe](https://github.com/dhoppe))
- Add imfile and im3195 input types [\#114](https://github.com/voxpupuli/puppet-rsyslog/pull/114) ([dhollinger](https://github.com/dhollinger))
- \#112 Fix ruleset expression filter examples [\#113](https://github.com/voxpupuli/puppet-rsyslog/pull/113) ([dhollinger](https://github.com/dhollinger))
- README.md: correct default of rsyslog::confdir [\#105](https://github.com/voxpupuli/puppet-rsyslog/pull/105) ([kenyon](https://github.com/kenyon))

## [v3.3.0](https://github.com/voxpupuli/puppet-rsyslog/tree/v3.3.0) (2018-10-14)

[Full Changelog](https://github.com/voxpupuli/puppet-rsyslog/compare/v3.2.0...v3.3.0)

**Implemented enhancements:**

- warning with recent puppet [\#95](https://github.com/voxpupuli/puppet-rsyslog/issues/95)
- Add '^' \(execute program\) rsyslog feature to ruleset tasks [\#80](https://github.com/voxpupuli/puppet-rsyslog/issues/80)
- Allow puppetlabs/stdlib 5.x and puppetlabs/concat 5.x [\#94](https://github.com/voxpupuli/puppet-rsyslog/pull/94) ([bastelfreak](https://github.com/bastelfreak))
- Add Feature: Allow 'execute program' \(^\) as a task in in rulesets [\#81](https://github.com/voxpupuli/puppet-rsyslog/pull/81) ([itbane](https://github.com/itbane))

**Closed issues:**

- imfile to send apache logs to remote syslog not working [\#102](https://github.com/voxpupuli/puppet-rsyslog/issues/102)
-  Error: Evaluation Error: Resource type not found: PrivDropToUser \(file: /tmp/kitchen/manifests/site.pp, line: 141, column: 9\) on node 21a40dd4ec00 [\#93](https://github.com/voxpupuli/puppet-rsyslog/issues/93)
- check fedora support [\#84](https://github.com/voxpupuli/puppet-rsyslog/issues/84)
- No clue how to configure a client with this module [\#64](https://github.com/voxpupuli/puppet-rsyslog/issues/64)

**Merged pull requests:**

- Add support to use upstream repos in Ubuntu and EL [\#101](https://github.com/voxpupuli/puppet-rsyslog/pull/101) ([dhollinger](https://github.com/dhollinger))
- Add support for puppet 6 [\#100](https://github.com/voxpupuli/puppet-rsyslog/pull/100) ([dhollinger](https://github.com/dhollinger))
- Update metadata.json to remove hiera 4 and support Fedora, drop Ubuntu 14.04 support and add 18.04 [\#99](https://github.com/voxpupuli/puppet-rsyslog/pull/99) ([dhollinger](https://github.com/dhollinger))
- Add a Debian 9 hiera exemple [\#96](https://github.com/voxpupuli/puppet-rsyslog/pull/96) ([hdep](https://github.com/hdep))

## [v3.2.0](https://github.com/voxpupuli/puppet-rsyslog/tree/v3.2.0) (2018-06-14)

[Full Changelog](https://github.com/voxpupuli/puppet-rsyslog/compare/v3.1.1...v3.2.0)

**Implemented enhancements:**

- Add the ability to create custom properties with 'set' [\#86](https://github.com/voxpupuli/puppet-rsyslog/pull/86) ([dhollinger](https://github.com/dhollinger))
- Add support to rsyslog::client for providing property\_filters and exp… [\#78](https://github.com/voxpupuli/puppet-rsyslog/pull/78) ([fatmcgav](https://github.com/fatmcgav))

**Merged pull requests:**

- Update code to more cleanly format nested configuration [\#85](https://github.com/voxpupuli/puppet-rsyslog/pull/85) ([dhollinger](https://github.com/dhollinger))
- drop EOL OSs; fix puppet version range [\#83](https://github.com/voxpupuli/puppet-rsyslog/pull/83) ([bastelfreak](https://github.com/bastelfreak))
- use gitrepos in .fixtures.yml [\#82](https://github.com/voxpupuli/puppet-rsyslog/pull/82) ([bastelfreak](https://github.com/bastelfreak))
- Rely on beaker-hostgenerator for docker nodesets [\#79](https://github.com/voxpupuli/puppet-rsyslog/pull/79) ([ekohl](https://github.com/ekohl))

## [v3.1.1](https://github.com/voxpupuli/puppet-rsyslog/tree/v3.1.1) (2018-03-29)

[Full Changelog](https://github.com/voxpupuli/puppet-rsyslog/compare/v3.1.0...v3.1.1)

**Fixed bugs:**

- Fix action template issue that causes an error when an empty config hash is passed [\#76](https://github.com/voxpupuli/puppet-rsyslog/pull/76) ([dhollinger](https://github.com/dhollinger))

**Merged pull requests:**

- Use docker\_sets in travis.yml [\#75](https://github.com/voxpupuli/puppet-rsyslog/pull/75) ([ekohl](https://github.com/ekohl))

## [v3.1.0](https://github.com/voxpupuli/puppet-rsyslog/tree/v3.1.0) (2018-03-22)

[Full Changelog](https://github.com/voxpupuli/puppet-rsyslog/compare/v3.0.0...v3.1.0)

**Implemented enhancements:**

- Add docker support for lookup\_tables [\#73](https://github.com/voxpupuli/puppet-rsyslog/pull/73) ([dhollinger](https://github.com/dhollinger))

## [v3.0.0](https://github.com/voxpupuli/puppet-rsyslog/tree/v3.0.0) (2018-03-21)

[Full Changelog](https://github.com/voxpupuli/puppet-rsyslog/compare/v2.3.2...v3.0.0)

**Breaking changes:**

- Switch datatype from Hash to array fo task param [\#71](https://github.com/voxpupuli/puppet-rsyslog/pull/71) ([dhollinger](https://github.com/dhollinger))

**Fixed bugs:**

- Lookup table fix [\#70](https://github.com/voxpupuli/puppet-rsyslog/pull/70) ([dhollinger](https://github.com/dhollinger))

## [v2.3.2](https://github.com/voxpupuli/puppet-rsyslog/tree/v2.3.2) (2018-03-12)

[Full Changelog](https://github.com/voxpupuli/puppet-rsyslog/compare/v2.3.1...v2.3.2)

**Implemented enhancements:**

- Filters require a unique name when used in rulesets. [\#65](https://github.com/voxpupuli/puppet-rsyslog/issues/65)
- Test travis release fix [\#68](https://github.com/voxpupuli/puppet-rsyslog/pull/68) ([dhollinger](https://github.com/dhollinger))
- Remove unique name requirement for Filters inside of a Ruleset resource [\#66](https://github.com/voxpupuli/puppet-rsyslog/pull/66) ([dhollinger](https://github.com/dhollinger))

**Merged pull requests:**

- Release 2.3.2 [\#67](https://github.com/voxpupuli/puppet-rsyslog/pull/67) ([dhollinger](https://github.com/dhollinger))

## [v2.3.1](https://github.com/voxpupuli/puppet-rsyslog/tree/v2.3.1) (2018-02-24)

[Full Changelog](https://github.com/voxpupuli/puppet-rsyslog/compare/v2.3.0...v2.3.1)

**Fixed bugs:**

- facility not present in out put of rulsets when using - action [\#59](https://github.com/voxpupuli/puppet-rsyslog/issues/59)
- \#59 Fix action facility bug [\#61](https://github.com/voxpupuli/puppet-rsyslog/pull/61) ([dhollinger](https://github.com/dhollinger))

## [v2.3.0](https://github.com/voxpupuli/puppet-rsyslog/tree/v2.3.0) (2018-01-24)

[Full Changelog](https://github.com/voxpupuli/puppet-rsyslog/compare/v2.2.1...v2.3.0)

**Implemented enhancements:**

- Add new data type for property filter operators [\#54](https://github.com/voxpupuli/puppet-rsyslog/pull/54) ([dhollinger](https://github.com/dhollinger))

**Fixed bugs:**

- Remove invalid property filter operators [\#55](https://github.com/voxpupuli/puppet-rsyslog/pull/55) ([dhollinger](https://github.com/dhollinger))

**Merged pull requests:**

- Update documentation around filters [\#56](https://github.com/voxpupuli/puppet-rsyslog/pull/56) ([dhollinger](https://github.com/dhollinger))
- Property filter operators [\#53](https://github.com/voxpupuli/puppet-rsyslog/pull/53) ([dhollinger](https://github.com/dhollinger))

## [v2.2.1](https://github.com/voxpupuli/puppet-rsyslog/tree/v2.2.1) (2018-01-05)

[Full Changelog](https://github.com/voxpupuli/puppet-rsyslog/compare/v2.2.0...v2.2.1)

**Closed issues:**

- Dependency circle with action class [\#47](https://github.com/voxpupuli/puppet-rsyslog/issues/47)
- Document ordering / sort algorithm [\#45](https://github.com/voxpupuli/puppet-rsyslog/issues/45)

**Merged pull requests:**

- Set concat order numeric [\#51](https://github.com/voxpupuli/puppet-rsyslog/pull/51) ([dhollinger](https://github.com/dhollinger))
- Updated docs to correctly reflect the priority functionality [\#50](https://github.com/voxpupuli/puppet-rsyslog/pull/50) ([dhollinger](https://github.com/dhollinger))

## [v2.2.0](https://github.com/voxpupuli/puppet-rsyslog/tree/v2.2.0) (2018-01-04)

[Full Changelog](https://github.com/voxpupuli/puppet-rsyslog/compare/v2.1.0...v2.2.0)

**Implemented enhancements:**

- Refactor rulesets [\#40](https://github.com/voxpupuli/puppet-rsyslog/pull/40) ([dhollinger](https://github.com/dhollinger))
- Add filters [\#39](https://github.com/voxpupuli/puppet-rsyslog/pull/39) ([dhollinger](https://github.com/dhollinger))

**Closed issues:**

- Add acceptance tests [\#43](https://github.com/voxpupuli/puppet-rsyslog/issues/43)
- Add OS Compatibility matrix  [\#42](https://github.com/voxpupuli/puppet-rsyslog/issues/42)
- Add acceptance test config and helpers [\#41](https://github.com/voxpupuli/puppet-rsyslog/issues/41)
- Refactor Rulesets and Filters [\#32](https://github.com/voxpupuli/puppet-rsyslog/issues/32)

**Merged pull requests:**

- bump lowest puppet version 4.4.0-\>4.10.9 [\#48](https://github.com/voxpupuli/puppet-rsyslog/pull/48) ([bastelfreak](https://github.com/bastelfreak))
- Add unit and acceptance tests [\#44](https://github.com/voxpupuli/puppet-rsyslog/pull/44) ([dhollinger](https://github.com/dhollinger))

## [v2.1.0](https://github.com/voxpupuli/puppet-rsyslog/tree/v2.1.0) (2017-12-06)

[Full Changelog](https://github.com/voxpupuli/puppet-rsyslog/compare/v2.0.0...v2.1.0)

**Implemented enhancements:**

- Add basic support for rsyslog filters in rulesets [\#31](https://github.com/voxpupuli/puppet-rsyslog/pull/31) ([dhollinger](https://github.com/dhollinger))

**Closed issues:**

- Support Filters [\#30](https://github.com/voxpupuli/puppet-rsyslog/issues/30)

**Merged pull requests:**

- Fix up README markdown and LICENSE file [\#37](https://github.com/voxpupuli/puppet-rsyslog/pull/37) ([alexjfisher](https://github.com/alexjfisher))

## [v2.0.0](https://github.com/voxpupuli/puppet-rsyslog/tree/v2.0.0) (2017-12-06)

[Full Changelog](https://github.com/voxpupuli/puppet-rsyslog/compare/1.1.0...v2.0.0)

**Merged pull requests:**

- Add additional README.md shields [\#35](https://github.com/voxpupuli/puppet-rsyslog/pull/35) ([dhollinger](https://github.com/dhollinger))
- modulesync 1.5.0 [\#34](https://github.com/voxpupuli/puppet-rsyslog/pull/34) ([dhollinger](https://github.com/dhollinger))

## 1.1.0 (2017-10-17)

* Feature: Added an `external_service` boolean parameter for allowing puppet-rsyslog to manage configs/logs shared with other processes that may be managed by other modules. (https://github.com/crayfishx/puppet-rsyslog/pull/28)

# 1.0.0

This release contains many new enhancements and features, and brings the module to a 1.0.0 release.  Many thanks to @dhollinger for the many contributions to this release.

* Enhancement: [Added flag to enable/disable service management](https://github.com/crayfishx/puppet-rsyslog/issues/17)
* Enhancement: [Add custom config dirs and target files](https://github.com/crayfishx/puppet-rsyslog/issues/19)
* Feature: [Rsyslog 8.x lookup table support](s://github.com/crayfishx/puppet-rsyslog/issues/15)
* Feature: [Support for the rsyslog parser() function](https://github.com/crayfishx/puppet-rsyslog/issues/21)
* Feature: [Support for multi ruleset generation](https://github.com/crayfishx/puppet-rsyslog/issues/22)
* Feature: [Support for ruleset stops](https://github.com/crayfishx/puppet-rsyslog/pull/26)
* Bugfix: [Solve the lack of errors when a component concat::fragment doesn't generate content due to a missing parent concat resource](https://github.com/crayfishx/puppet-rsyslog/issues/19)


### 0.2.0

* [Fixed variable scoping styling and rake validation fixes](https://github.com/crayfishx/puppet-rsyslog/pull/2)
* [Support for legacy options](https://github.com/crayfishx/puppet-rsyslog/pull/4)
* [README fixes](https://github.com/crayfishx/puppet-rsyslog/pull/5)
* [Option support for modules](https://github.com/crayfishx/puppet-rsyslog/pull/6)
* [Updated the action component to support logger facility](9)
* [Added more tests for the legacy_config / main_queue class](https://github.com/crayfishx/puppet-rsyslog/pull/10)
* [Documentation Updates](https://github.com/crayfishx/puppet-rsyslog/pull/12)
* [Fixed the global params config styling](https://github.com/crayfishx/puppet-rsyslog/pull/13)


\* *This Changelog was automatically generated by [github_changelog_generator](https://github.com/github-changelog-generator/github-changelog-generator)*
