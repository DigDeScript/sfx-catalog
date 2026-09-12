# Release notes

## 1.1.3 — 2026-09-12

- Publishes supported Windows and Linux user packages from the same unified Free/Pro codebase.
- Adds Linux packaging, application-menu integration, icons and system compatibility checks.
- Uses a stable Linux machine identity for activation while keeping activation and deactivation compatible with the shared licensing service.
- Adds automatic discovery and indexing of installed DaVinci Resolve Fairlight sound libraries, including supported custom locations.
- Corrects waveform-cache invalidation after palette or style changes, preventing `QListView::changeEvent()` errors.
- Keeps the player compact in every supported panel position.
- Includes current search scope, filtered-results, library navigation and update-check behavior.
- Includes the matched SFX Catalog panel for DaVinci Resolve.

The Windows package passed the project test suite and packaged checks. The Linux package was built and launch-tested on Rocky Linux 8.10. This is not a guarantee of compatibility with every computer or Linux distribution.

The macOS package is not yet available.
