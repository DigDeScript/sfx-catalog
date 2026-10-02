# Release notes

## 1.2.0 — 2026-09-30

- Publishes updated Windows and Linux packages with unified Free and Pro modes.
- Adds the SFX Catalog panel for DaVinci Resolve Studio on Linux, launched from Workspace → Scripts → SFX Catalog in a separate window.
- Adds optional WAV conversion from the Resolve panel, preserving originals and keeping converted files outside the catalog database.
- Improves library switching, context menus and Linux menu/hover stability.
- Improves metadata display, descriptive-metadata search, multi-selection filters and handling of unavailable files in virtual libraries.
- Includes clearer device labels for activation management, using computer and user names.

Linux requires system-installed FFmpeg and ffprobe. Reinstalling Linux can change its device identity; use license self-service to deactivate an obsolete activation if necessary. A macOS package is not available yet.

## 1.1.3 — 2026-09-12

- Publishes supported Windows and Linux user packages from the same unified Free/Pro codebase.
- Adds Linux packaging, application-menu integration, icons and system compatibility checks.
- Uses a stable Linux machine identity for activation while keeping activation and deactivation compatible with the shared licensing service.
- Adds automatic discovery and indexing of installed DaVinci Resolve Fairlight sound libraries, including supported custom locations.
- Corrects waveform-cache invalidation after palette or style changes, preventing `QListView::changeEvent()` errors.
- Keeps the player compact in every supported panel position.
- Includes current search scope, filtered-results, library navigation and update-check behavior.
- Includes the matched SFX Catalog panel for DaVinci Resolve Studio on Windows.

The Windows package passed the project test suite and packaged checks. The Linux package was built and launch-tested on Rocky Linux 8.10. This is not a guarantee of compatibility with every computer or Linux distribution.

The macOS package is not yet available.
