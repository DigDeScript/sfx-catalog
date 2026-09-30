---
schema_version: 1
id: sfx-catalog
title: SFX Catalog
category: software
status: published
platform: windows and linux
summary: Organize, search and preview your sound effects in one desktop application.
release_repository: DigDeScript/sfx-catalog
website: https://digdescript.com/software?product=sfx-catalog
image_dark: sfx-catalog-pro-interface-dark.webp
image_light: sfx-catalog-pro-interface-light.webp
---

## Your sound effects, organized and ready to audition

SFX Catalog turns local folders of sound effects into a searchable library. Keep your original files where they are, scan them, then search filenames and supported descriptive metadata, and filter audio properties. Choose the selected folder or the entire library as the search scope. Listen with waveform previews, pause playback and jump to the part you need.

**One download, two modes.** Start in Free mode without a Pro key. Activate a license in the same application to unlock Pro tools while keeping your catalog.

### Browse local and online libraries

Use your own sound collection or browse the OpenGameArt CC0 Sound Library online. Download individual sounds or the whole library, extract the archive and scan the downloaded folder for offline use. Online libraries are read-only.

SFX Catalog supports Windows and Linux and can discover an installed DaVinci Resolve Fairlight Sound Library, including supported custom installation locations. The sounds must already exist on your computer; they are not supplied with SFX Catalog. This read-only library is separate from the Pro panel for DaVinci Resolve Studio.

### Organize with Pro

Create virtual collections without moving original files. Use Favorites, file-management operations, duplicate-finding tools and audio-based similar-sound search. Similarity results are suggestions to audition, not a guarantee that sounds are interchangeable.

### Continue in DaVinci Resolve

The Pro panel requires **DaVinci Resolve Studio**. On Windows it opens as a Workflow Integration; on Linux it opens from the Scripts menu in a separate window. Browse prepared libraries and import sounds without keeping the SFX Catalog desktop application open. Prepared libraries remain usable after desktop license deactivation, provided the exported catalog snapshot and sound files remain accessible.

The panel can convert files to WAV for import when needed. Converted files are saved separately, leaving originals unchanged; they are not added to the SFX Catalog database.

## Free and Pro

| Feature | Free | Pro |
|---|---|---|
| Local folder indexing and browsing | Included | Included |
| Filename and descriptive-metadata search; audio-property filters | Included | Included |
| Waveform playback, pause and seeking | Included | Included |
| Online OpenGameArt library browsing and downloads | Included | Included |
| Installed Fairlight library discovery | Included | Included |
| Light/dark themes and adjustable panel positions | Included | Included |
| Favorites and custom virtual libraries | Not included | Included |
| Rename, move, delete and bulk local-file workflows | Not included | Included |
| Audio analysis and similar-sound search | Not included | Included |
| Duplicate-finding tools | Not included | Included |
| SFX Catalog panel for DaVinci Resolve Studio | Not included | Included |

## Pro activation

A one-time license supports up to three active computers. Deactivate one device to free a place for another. Deactivation returns the desktop application to Free mode.

Activation and deactivation require internet access. Local work does not require a continuous connection. When online, the application checks for updates and activation status in the background at startup, no more than once per day. A connection failure does not disable saved Pro access. Pro activation requires a supported system identity.

Use **Help → Check for updates** for an immediate manual check. **Help → Export diagnostic log** saves local update-check times, status and failure codes for support without including a license key, activation certificate or catalog data. The log is not sent automatically.

Enter an existing key through **Help → Activate SFX Catalog Pro**, or the activation button under **Learn about Pro**. [License recovery](https://digdescript.com/license-recovery) is available for existing licenses.

## Getting started

For Windows, download and extract the complete ZIP, then run `SFXCatalog.exe`. For Linux, extract the `.tar.gz`, run `install.sh`, and start SFX Catalog from the application menu. Follow `README-Linux.txt` included in the archive for system requirements. No separate Python installation is required to run either packaged version.

Linux also requires **FFmpeg and ffprobe** installed on the computer and available in PATH.

**A macOS version is planned but is not available yet.**

Catalog information and playback caches are stored locally. Audio preview caches can require additional disk space, particularly for long recordings. SFX Catalog is primarily intended for sound effects.

The OpenGameArt collection's CC0 designation is separate from the SFX Catalog software license.
