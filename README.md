# CollMan desktop updates

Public macOS and Windows binaries and signed update feeds for CollMan. Application source remains private. No personal collections are stored here.

[Download CollMan](https://github.com/AntoninoFulci/CollMan-updates/releases/latest)

macOS: download the universal DMG, move CollMan to Applications, then launch it. Windows: use Setup.exe for a per-user installation. Older builds need one manual installation of alpha.4 to enable app updates.

From alpha.4, CollMan checks for app updates at startup and daily. Profile includes a manual check. Native update dialogs request installation and restart; save unfinished edits first. Sparkle verifies EdDSA-signed macOS updates; the bundled WinSparkle verifies DSA-signed Windows installers.

The alpha macOS app is Apple Development signed, not notarized. Windows installers lack Authenticode signing. First-install OS trust warnings may occur; update signatures do not replace platform signing.

Stable feeds:

- [macOS](https://raw.githubusercontent.com/AntoninoFulci/CollMan-updates/main/appcast-macos.xml)
- [Windows](https://raw.githubusercontent.com/AntoninoFulci/CollMan-updates/main/appcast-windows.xml)

Catalog data updates independently through [CollMan-catalog](https://github.com/AntoninoFulci/CollMan-catalog): automatic checks and downloads, with activation at next launch. Card images download on demand. Reference data and application binaries contain no personal workspace data.

CollMan is an unofficial Yu-Gi-Oh! collection manager and is not affiliated with KONAMI or other card rights holders. See the separate catalog release notices for reference-data attribution.
