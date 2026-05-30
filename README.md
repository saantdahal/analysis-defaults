# analysis_defaults

Shared analysis and linting defaults for Flutter sample projects.

## Overview

This package provides a centralized set of analysis options and linting rules used across Flutter sample applications. It helps maintain consistent code quality, style, and best practices throughout the workspace.

## Package Information

- **Name:** `analysis_defaults`
- **Description:** Analysis defaults for flutter/samples
- **Publish:** Private (`publish_to: none`)
- **SDK:** Dart `^3.9.0-0`

## Dependencies

| Package | Version |
|----------|----------|
| flutter_lints | ^6.0.0 |

> **Note:** This package is intended only for analysis configuration and lint rules. Production code should not be added to this package.

## Usage

Add this package as an analysis configuration dependency in projects within the workspace and include its analysis options as needed.

Example:

```yaml
include: package:analysis_defaults/flutter.yaml
```

## Purpose

The goals of this package are:

- Enforce consistent coding standards.
- Reduce duplicated analysis configuration.
- Simplify maintenance of lint rules across multiple projects.
- Align Flutter sample projects with recommended best practices.

## Restrictions

- Do not add application or library code.
- Do not introduce additional dependencies unless required for analysis configuration.
- Keep the package focused on linting and static analysis settings only.

## License

Internal workspace package for Flutter sample projects.
