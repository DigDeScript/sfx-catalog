# Getting started

Download the package for your operating system from the official website or a published GitHub release. Do not use GitHub's automatically generated **Source code** archives.

## Windows

1. Download the Windows package from the latest published release.
2. Extract the complete archive to a folder you can write to.
3. Open `SFXCatalog.exe`. Keep it together with the accompanying files.

Catalog data is stored under `%LOCALAPPDATA%\SoundEffectsCatalog`. Copying the application folder is not a backup of the catalog or a transfer of a Pro activation.

## Linux

1. Download the Linux package from the latest published release.
2. Extract the complete archive.
3. Read `README-Linux.txt`, then run `install.sh` and start SFX Catalog from the application menu.

The Linux package is built for x86-64 systems compatible with glibc 2.28 or newer. The installer checks required desktop libraries and explains any missing system package.

Install **FFmpeg and ffprobe** using your distribution's package manager; both commands must be available in PATH. These are required on the computer running SFX Catalog, not only on the build computer. Follow the archive's `README-Linux.txt` for desktop dependencies, including `xcb-util-cursor` where required.

## Updating SFX Catalog

Use **Help → Check for updates**. When an update is available, follow the download link to the official website and download the full package for your operating system from GitHub Releases. Updates are not installed automatically; there is no separate patch package.

Close SFX Catalog and DaVinci Resolve before replacing application files. On Windows, extract the complete ZIP into a new folder and run `SFXCatalog.exe`. On Linux, extract the archive and run `install.sh`, then launch from the applications menu; this replaces the installed application without removing its separate user data.

If the application path changes, update your shortcuts and reinstall the Resolve plugin from the new SFX Catalog version. The Linux panel launcher needs the application path; on Windows, only the audio-conversion helper needs it, not catalog browsing.

Once the new version works, **you can safely delete the old application folder and all its bundled files**. First move out any personal files or sound libraries you placed there. Do not delete the currently used installation or the separate user-data folder. Catalog data and saved activation remain under `%LOCALAPPDATA%\SoundEffectsCatalog` on Windows and `${XDG_DATA_HOME:-~/.local/share}/SoundEffectsCatalog` on Linux. Updating on the same computer under the same user account does not require deactivation.

## First use

Select a local sound folder and let the application scan it. Search, filter and preview sounds with the waveform player. Python does not need to be installed separately for either packaged version.

To use downloaded online sounds offline, extract the sound-library ZIP and select that sound folder for scanning.

To activate Pro, use **Help → Activate SFX Catalog Pro**. Keep your license key private. Contact support@digdescript.com if you need help.

If Windows displays a security warning, verify the download source and package hash before deciding whether to run it. Do not disable antivirus protection.

## Optional DaVinci Resolve Studio panel

Install the panel from SFX Catalog's Resolve menu. On Windows, open **Workspace → Workflow Integrations → Sound Effects Catalog** in DaVinci Resolve Studio. On Linux, open **Workspace → Scripts → SFX Catalog**; the panel runs in a separate window. DaVinci Resolve Free does not support this integration.

See [macOS availability and instructions](https://digdescript.com/support/sfx-catalog/resolve-panel#macos).
