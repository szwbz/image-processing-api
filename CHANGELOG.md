# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

### Added
- Initial project setup
- Basic image processing API structure

## [v2.5.0] - 2024-10-25

### Added
- Support for new image formats (WebP, AVIF)
- Batch processing capabilities
- Advanced filtering options
- AI-powered image upscaling via the new `/upscale` endpoint

### Changed
- Improved image compression algorithms
- Updated API documentation
- Updated Pillow dependency to version 10.2.0

### Fixed
- Memory leak in image resizing operations
- Color space conversion issues

## [v2.4.1] - 2024-09-15

### Added
- Basic image resizing functionality
- Format conversion support (JPEG, PNG, GIF)
- Simple filtering operations

### Fixed
- Initial release bugs and stability issues