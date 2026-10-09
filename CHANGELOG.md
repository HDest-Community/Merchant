# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [v3.0.1] - 2026-10-09

### Changed

-   Updated Build Scripts to include HDCINFO file.

## [v3.0.0] - 2026-10-09

### Added

-   Added Wallet.
-   Added support for various other addons.
-   Added more ways to earn currency (#8, #9).
-   Added CVAR to allow MercBucks to be flagged as `SHOOTABLE` primarily to allow bills to be burned.
-   Added CVAR so dropped currency can instead be instantly deposited into players' inventories (#10).
-   Implement HDCoreLib, extracting Store Entries into commands for addons to define and provide support for (#11).

### Changed

-   Refined bounty target selection logic.
-   Reduced generic `HDHumanoid` bounty value.
-   Updated build scripts.
-   Non-Bounty targets dropping "human levels" of cash drop wallets.
-   Fixed Tiberium Crystals dropping absurd amounts of chunks when telefragged.
-   Merchant Menu Scrollbar widened to hopefully help with mobile users.
-   Refined SNDINFO definitions (#12).

### Removed

-   Removed store entries for now-deprecated .50 AE rounds.

## [v2.0.1] - 2023-12-19

### Changed

-   Added Keyboard Navigation Support back to new ZForms Menus.
-   Cleaned up Focus Grid logic

## [v2.0.0] - 2023-12-18

### Added

-   Added Requisition Kit Store Entries.
-   Added Velvet Adhesive Store Entries.
-   Added Gearbox Backpack Store Entries.
-   Added Altis O/U Shotgun Store Entries.
-   Added Cozi's Offworld Wares Musket & Flintlock Pistol Store Entries.
-   Added Universal Reloader Store Entries.
-   Added UaS Sling & Gyro Stabilizer Store Entries.
-   Added Vanilla Pistol Store Entries.
-   Added ZikShadow's UMS Automag Store Entries.
-   Added Armour Patch Kit Store Entries.

### Changed

-   Updated ZForms to v2.
-   Redesigned the Shop Menu layout to leverage new ZForms upgrade, now with scrolling panels and collapsible sections.
-   Allow more possible bounty target classes.

## [v1.0.2] - 2023-08-06

### Changed

-   Subdivide HDBulletLib's shop entries.

## [v1.0.1] - 2023-08-05

### Changed

-   Fixed Build Script.

## [v1.0.0] - 2023-08-05

### Added

-   Initial Release.  Originally made by Accensus, now maintained by the community

[Unreleased]: https://github.com/HDest-Community/Merchant/compare/v3.0.1...HEAD

[v3.0.1]: https://github.com/HDest-Community/Merchant/compare/v3.0.0...v3.0.1

[v3.0.0]: https://github.com/HDest-Community/Merchant/compare/v2.0.1...v3.0.0

[v2.0.1]: https://github.com/HDest-Community/merchant/compare/v2.0.0..v2.0.1

[v2.0.0]: https://github.com/HDest-Community/merchant/compare/v1.0.2..v2.0.0

[v1.0.2]: https://github.com/HDest-Community/merchant/compare/v1.0.1..v1.0.2

[v1.0.1]: https://github.com/HDest-Community/merchant/compare/v1.0.0..v1.0.1

[v1.0.0]: https://github.com/HDest-Community/merchant/releases/tag/v1.0.0
