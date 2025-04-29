# Changelog

All notable changes to this project will be documented in this file. See [standard-version](https://github.com/conventional-changelog/standard-version) for commit guidelines.

## [1.4.1](https://github.com/le-phare/ansible-db-pull/compare/v1.4.0...v1.4.1) (2025-04-29)


### Bug Fixes

* **anonymization:** skip when restoring local dumps ([#10](https://github.com/le-phare/ansible-db-pull/issues/10)) ([f6b7d7e](https://github.com/le-phare/ansible-db-pull/commit/f6b7d7e50647934e427d633fc5a1a6acb9a67a77))

## [1.4.0](https://github.com/le-phare/ansible-db-pull/compare/v1.3.0...v1.4.0) (2025-03-28)


### Features

* anonymization using DbToolsBundle ([#4](https://github.com/le-phare/ansible-db-pull/issues/4)) ([b0bb627](https://github.com/le-phare/ansible-db-pull/commit/b0bb6275115f0964ccff88350233dab18d24615e))

## [1.3.0](https://github.com/le-phare/ansible-db-pull/compare/v1.2.1...v1.3.0) (2025-02-24)


### Features

* **postgresql:** allow binary paths overriding ([e7a6ea6](https://github.com/le-phare/ansible-db-pull/commit/e7a6ea66b0e791d5e08382af67236f4b414f5ca1))

## [1.2.1](https://github.com/le-phare/ansible-db-pull/compare/v1.2.0...v1.2.1) (2023-11-06)


### Fixes

* **dump:** drop task skipped if `db_pull_skip_restore` set to `true` ([87ce3763ffdb0579fadd083afd9d6f145804101a](https://github.com/le-phare/ansible-db-pull/commit/87ce3763ffdb0579fadd083afd9d6f145804101a))


## [1.2.0](https://github.com/le-phare/ansible-db-pull/compare/v1.1.0...v1.2.0) (2022-11-07)


### Features

* **dump:** add db_pull_excluded_tables ([0c65cb4](https://github.com/le-phare/ansible-db-pull/commit/0c65cb4676148f6f028e83a4b0d4329c4adb85d6))


## 1.1.0 (2021-11-18)


### Features

* add editorconfig ([e396db1](https://github.com/le-phare/ansible-db-pull/commit/e396db14aa0b95f7a8ec9ed6042852333d21ffcf))
* explicitly set `become: false` for localhost delegation ([ee4d6e7](https://github.com/le-phare/ansible-db-pull/commit/ee4d6e70f6c72e5a931620b4436997fcedaaabd5))


### Bug Fixes

* handle port variable in both dump and restore ([a17149b](https://github.com/le-phare/ansible-db-pull/commit/a17149b0d54e53793138f8cdd85a816503c7b2c7))
* **postgres:** fix a typo on the port parameter ([b24bd3d](https://github.com/le-phare/ansible-db-pull/commit/b24bd3def29a1cdd7f15bef1349db691949e0dff))
