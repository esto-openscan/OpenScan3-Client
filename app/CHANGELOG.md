# Changelog

All notable user-facing changes to OpenScan3 Client are documented here.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/2.0.0/), and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## Unreleased

### Added

- Added a camera orientation dialog that can be opened from the camera settings and scan page, allowing camera orientation to be adjusted outside the setup wizard.

### Changed

- Improved the focus stacking and hq preview by removing the loading overlay while keeping the spinner visible, making focus changes easier to judge visually. (Thanks agryson!)

### Fixed

- Focus stacking now allows setting a focus value of 0 in the frontend.
