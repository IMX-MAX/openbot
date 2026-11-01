### Changed

- The Windows installer is now built for ARM64 only: the release ships `OpenBot-<VERSION>-arm64.exe` instead of the x64 installer. The Computer Use driver is the ARM64 build; the remote desktop runtime stays x64-only, so the ARM64 installer does not include it.
