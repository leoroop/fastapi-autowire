# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [0.1.0] - 2025-12-26

### Added
- Initial release of fastapi-autowire
- Spring-like dependency injection and autowiring for FastAPI applications
- Core dependency injection container with automatic dependency resolution
- Support for singleton and transient bean scopes
- Lifecycle management with startup and shutdown hooks
- Type-safe dependency resolution using Python type hints
- Application context management for organizing and accessing beans
- Comprehensive test suite covering integration, lifecycle, and resolver functionality
- Full type annotations with `py.typed` marker for type checking support
- Support for Python 3.9, 3.10, 3.11, and 3.12
- Documentation in README.md with usage examples

### Features
- **Dependency Registry**: Central registry for managing application dependencies
- **Automatic Resolution**: Resolves dependencies automatically based on type annotations
- **Lifecycle Hooks**: Support for initialization and cleanup operations
- **FastAPI Integration**: Seamless integration with FastAPI's dependency injection system
- **Type Safety**: Full type hints and mypy compatibility

[Unreleased]: https://github.com/yourusername/fastapi-autowire/compare/v0.1.0...HEAD
[0.1.0]: https://github.com/yourusername/fastapi-autowire/releases/tag/v0.1.0