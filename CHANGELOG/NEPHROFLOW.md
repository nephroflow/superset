<!--
Licensed to the Apache Software Foundation (ASF) under one
or more contributor license agreements.  See the NOTICE file
distributed with this work for additional information
regarding copyright ownership.  The ASF licenses this file
to you under the Apache License, Version 2.0 (the
"License"); you may not use this file except in compliance
with the License.  You may obtain a copy of the License at

  http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing,
software distributed under the License is distributed on an
"AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY
KIND, either express or implied.  See the License for the
specific language governing permissions and limitations
under the License.
-->

# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

### Breaking changes

### Added

- Added a flag to ignore certain columns in xlsx & csv exports. (Key: TABLE_EXPORT_IGNORE_COLS) [NF-5220](https://www.notion.so/nipro-digital/Remove-the-link-to-the-patient-s-file-from-the-data-exports-1a444b771c6c8063a7fce88ef0f3968c)

### Changed

- Xlsx exports start counting from 1 instead of 0. [NF-5221](https://www.notion.so/nipro-digital/Start-exports-starting-from-1-in-stead-of-0-1a444b771c6c8012a29bc0e12f5e9df4)

### Removed

### Fixed

- Allow decimal steps in range sliders for smaller values. [NF-5295](https://www.notion.so/nipro-digital/PHM-QI-does-not-filter-on-float-numbers-1ab44b771c6c80c2b93ad50cf3d78fcb) [NF-5218](https://www.notion.so/nipro-digital/Adjust-the-slider-min-max-values-to-allow-for-0-1-steps-1a444b771c6c80b9b8d1d96abac08827)
