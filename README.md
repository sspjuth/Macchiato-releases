# Macchiato releases

This public repository contains Macchiato desktop release downloads.

Macchiato itself is developed in a private repository. Published releases may
include macOS DMG files, Windows installers, Linux AppImages, portable archives,
the static PWA package, and SHA-256 checksums.

Windows and Linux packages require CPython 3.10 or newer on `PATH`, or
`MACCHIATO_PYTHON` pointing to a compatible Python executable. On first launch,
Macchiato creates a local runtime environment and installs its Python runtime
dependencies.

The macOS package is ad-hoc signed and is not Apple-notarized.
