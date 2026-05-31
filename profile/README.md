# CPS Linux

**A Linux distribution designed to be understood.**

CPS Linux is an experimental Linux distribution built around a modern, understandable package ecosystem.

The project focuses on simplicity, transparency, maintainability, and a packaging system that can be understood from top to bottom.

## Philosophy

Many Linux distributions have accumulated decades of historical decisions, compatibility layers, and complex packaging infrastructure.

CPS Linux takes a different approach:

* Simple package formats
* Simple dependency resolution
* Transparent repository metadata
* Lightweight cryptographic verification
* Clear separation between building and installing packages

The goal is not to create the smallest or fastest Linux distribution.

The goal is to create a distribution whose internals can be understood.

## Components

The CPS ecosystem currently consists of several projects:

| Project  | Description          |
| -------- | -------------------- |
| cpsi     | Package manager      |
| cpsbuild | Package build system |
| .clos    | Package format       |
| .cpsb    | Build recipe format  |

## Package Workflow

```text
.cpsb
 ↓
cpsbuild
 ↓
.clos
 ↓
Repository
 ↓
cpsi
 ↓
Installed System
```

## Current Status

CPS Linux is currently under active development.

Specifications, formats, and internal implementations may change significantly before the first stable release.

## Design Goals

* Understandable architecture
* Self-contained packages
* Predictable dependency resolution
* Simple repository structure
* Modern implementation in Rust
* Minimal system complexity

## License

See individual repositories for licensing information.
Unless otherwise specified, Apache 2.0 is used.
