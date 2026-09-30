# Getting started

Download the package for your operating system from the official website or a published GitHub release. Do not use GitHub's automatically generated **Source code** archives.

## Windows

1. Download `SFXCatalog-Windows-v1.2.0.zip`.
2. Extract the complete archive to a folder you can write to.
3. Open `SFXCatalog.exe`. Keep it together with the accompanying files.

Catalog data is stored under `%LOCALAPPDATA%\SoundEffectsCatalog`. Copying the application folder is not a backup of the catalog or a transfer of a Pro activation.

## Linux

1. Download `SFXCatalog-Linux-v1.2.0.tar.gz`.
2. Extract the complete archive.
3. Read `README-Linux.txt`, then run `install.sh` and start SFX Catalog from the application menu.

The Linux package is built for x86-64 systems compatible with glibc 2.28 or newer. The installer checks required desktop libraries and explains any missing system package.

Install **FFmpeg and ffprobe** using your distribution's package manager; both commands must be available in PATH. These are required on the computer running SFX Catalog, not only on the build computer. Follow the archive's `README-Linux.txt` for desktop dependencies, including `xcb-util-cursor` where required.

## First use

Select a local sound folder and let the application scan it. Search, filter and preview sounds with the waveform player. Python does not need to be installed separately for either packaged version.

To use downloaded online sounds offline, extract the sound-library ZIP and select that sound folder for scanning.

To activate Pro, use **Help → Activate SFX Catalog Pro**. Keep your license key private. Contact support@digdescript.com if you need help.

If Windows displays a security warning, verify the download source and package hash before deciding whether to run it. Do not disable antivirus protection.

## Optional DaVinci Resolve Studio panel

Install the panel from SFX Catalog's Resolve menu. On Windows, open **Workspace → Workflow Integrations → Sound Effects Catalog** in DaVinci Resolve Studio. On Linux, open **Workspace → Scripts → SFX Catalog**; the panel runs in a separate window. DaVinci Resolve Free does not support this integration.

A macOS version is planned but is not available yet.
