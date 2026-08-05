# Keqing Bot Changelog

_Label:_ [_`Keqing`_](https://github.com/Otaku-senpai/ASC-Bugs/issues?q=label%3A%22Keqing%22)

## [6.7.0] - 2026-08-5

## 🛠️ Bug Fixes & Improvements

- **Search & Display Limits: (Issue #44)**
  - Enforced a result limit of **5 items** for smart searches.
  - Restricted `extra_names` outputs to a maximum of **3 items**.
- **Localization & Formatting (Arabic - AR): (Issue #46)**
  - Fixed broken Vision emojis across character profiles.
  - Corrected Electro Vision Arabic text to **"إليكترو"**.
  - Fixed **Mavuika's** main `extra_name` translation lookup.
  - Resolved issue where character story descriptions and nation details defaulted to English instead of displaying in Arabic.
- **HSR Search Routing: (Issue #46)**
  - Fixed **Trailblazer** search logic to prevent incorrectly routing results to Kafka, ensuring proper prompts for element selection.

## 🌟 Constellation Database Updates

- **Total Character Builds Refreshed:** 98
- **New Constellation Datasets:** 5 Characters (Xianyun, Wriothesley, Tighnari, Neuvillette, Mika)

---

## [6.6.0] - 2026-07-16

### Added / Updated

- **Search System:** Smarter Talent & Character searching system (handles lore names, typos, etc.).
- **Localization:** Updated Arabic Character names.
- **Game Version 6.7:** Added new Domains and Characters for builds/materials.
- **Commands:** Updated `=domain` and `=book` to display book info, daily availability, and characters using the book.

### Fixed

- Fixed issue where talent book daily status showed incorrect availability for Keqing due to domain overlap.
- Fixed character searches requiring dashes (e.g., "Hu-Tao" now works as natural space: `=talent hu tao`).
- Re-engineered backend clock synchronization for accurate banner tracking and reset times.

---

## [8.4.3] - 2026-03-24

### Fixed

- Fixed `=news` command successfully.

---

## [6.5.0] - 2026-03-02

### Added

- **New Characters:** Columbina (5★), Durin (5★), Illuga (5★), Jahoda (4★), Linnea (5★), Lohen (5★), Nicole (5★), Prune (4★), Varka (5★), Zibai (5★).
- **Character Builds:** Arlecchino, Chiori, Clorinde, Dahlia, Emilie, Kachina, Kinich, Mualani, Sigewinne, Skirk.
- **Constellations:** Gaming.
- **Artifact Sets:** A Day Carved From Rising Winds, Aubade of Morningstar and Moon, Celestial Gift, Disenchantment in Deep Shadow.
- **Weapons:** A Teaspoon of Transcendence, Angelos’ Heptades, Dawning Frost, Disaster and Remorse, Gest of the Mighty Wolf, Golden Frostbound Oath, Nocturne’s Curtain Call, Reliquary of Truth, The Daybreak Chronicles.

---

## [6.0.1] - 2025-10-09

### Updated

- Banners updated to version 6.0.0.
- Domain command updated to 6.0.
- Fixed bugs and resolved outdated data.

---

## [6.0.0] - 2025-10-09

### Added

- **Characters:** Flins, Lauma, Lneffa, Aino.
- **Weapons:** Prospector’s Shovel, Blackmarrow Lantern, Master Key, Serenity’s Call, Nightweaver’s Looking Glass, Snare Hook, Moonweaver’s Dawn, Bloodsoaked Ruins, Etherlight Spindlelute, Fractured Halo, Flame-Forged Insight.
- **Artifacts:** Silken Moon’s Serenade, Night of the Sky’s Unveiling.
- **Domain:** Lightless Capital.

---

## [5.7.0] - 2025-06-17

### Added

- **Characters:** Escoffier, Ifa, Skirk, Dahlia.
- **Weapon:** Azurelight.

---

## [5.6.7] - 2025-05-11

### Note

- Maintenance note regarding Arabic translations status.

---

## [5.6.6] - 2025-05-11

### Updated

- Updated Banner details and banner timers.

---

## [5.6.5] - 2025-05-11

### Fixed

- Fixed unknown gender and blank affiliation for characters (4.3 - 5.0).
- Fixed mobile image display issues for characters (4.4 - 4.8).

---

## [5.6.4] - 2025-05-11

### Added

- **4★ Weapons:** Calamity of Eshu, Waveriding Whirl, Flower-Wreathed Feathers, Mountain-Bracing Bolt, Fruitful Hook, Sturdy Bone, Tamayuratei no Ohanashi, Sequence of Solitude.
- **5★ Weapons:** Astral Vulture's Crimson Plumage, Peak Patrol Song, Starcaller’s Watch, A Thousand Blazing Suns, Sunny Morning Sleep-In, Vivid Notions, Symphonist of Scents.

---

## [5.6.3] - 2025-05-11

### Added

- **Artifacts:** Finale of the Deep Galleries, Long Night's Oath, Unfinished Reverie, Fragment of Harmonic Whimsy.

---

## [5.6.2] - 2025-05-11

### Added

- **4★ Characters:** Xilonen, Ororon, Lan Yan, Iansan.
- **5★ Characters:** Mavuika, Yumemizuki Mizuki, Chasca, Citlali, Varesa.

---

## [5.6.1] - 2025-05-11

### Added

- **Talent Domains:** Blazing Ruins, Pale Forgotten Glory, Steeple of Ignorance, Taishan Mansion.

---

## [5.6.0] - 2025-05-11

### Added

- Builds & materials for Arlecchino, Sethos, Clorinde, Sigewinne, Kachina, Mualani, Kinich, Mavuika, Yumemizuki Mizuki, Chasca, Citlali, Varesa, Xilonen, Ororon, Lan Yan, Iansan.

---

## [5.5.1] - 2025-03-28

### Fixed

- Fixed character profile cards with missing images, nations, or weapon types.

---

## [5.0.2] - 2024-11-30

### Updated

- Genshin Impact banners updated.

---

## [5.0.1] - 2024-11-02

### Known Issue

- Missing character builds to be added in future patches.

---

## [5.0.0] - 2024-11-02

### Added

- **Characters:** Emilie, Mualani, Kachina, Kinich, Clorinde, Sethos, Sigewinne.
- **Artifacts:** Scroll of the Hero of Cinder City, Obsidian Codex, Fang of the Mountain King, Surf's Up, Ring of Yaxche, Footprint of the Rainbow, Flute of Ezpitzal, Earth Shaker, Chain Breaker, Ash-Graven Drinking Horn.
- **Weapons:** Lumidouce Elegy, Surf's Up, Ring of Yaxche, Footprint of the Rainbow, Flute of Ezpitzal, Fang of the Mountain King, Earth Shaker, Chain Breaker, Ash Graven Drinking Horn, Silvershower Heartstrings, Cloudforged, Absolution.

---

## [4.4.5] - 2024-03-04

### Fixed

- Fixed Ruan Mei and Dr. Ratio characters (Honkai Star Rail).

---

## [4.4.4] - 2024-02-29

### Added

- **Characters:** Navia (Genshin).
- **Weapons:** Key of Khaj-Nisut, Haran Geppaku Futsu, Splendor of Tranquil Waters, Uraku Misugiri, Forest Regalia, Mailed Flower, Talking Stick, Tidal Shadow, Song of Broken Pines, The Unforged, Redhorn Stonethresher, Wolf's Gravestone, Portable Power Saw, Verdict, Aqua Simulacra, Thundering Pulse, The First Great Magic, Hunter's Path.
- **Artifacts:** Desert Pavilion Chronicle, Flower of Paradise Lost, Golden Troupe, Marechaussee Hunter, Nighttime Whispers in the Echoing Woods, Nymph's Dream, Song of Days Past, Vourukasha's Glow.

---

## [4.4.3] - 2024-02-29

### Added

- **Genshin Characters:** Xianyun, Gaming.
- **HSR Characters:** Sparkle, Black Swan, Huohuo, Hanya, Ruan Mei, Xueyi, Argenti.

---

## [4.4.2] - 2024-02-07

### Fixed

- Fixed allegiance display issues in Genshin character profiles.
- Fixed Chevreuse image asset.

---

## [4.4.1] - 2024-02-07

### Added

- Gaming and Xianyun added to available character lists.

---

## [4.4.0] - 2024-02-07

### Changed

- Banner data updated.

---

## [4.3.5] - 2024-01-04

### Added

- Info command (`=info`) added to Keqing.

---

## [4.3.4] - 2023-12-21

### Fixed

- Fixed character listing output in Arabic.
- Fixed broken weapon images.

---

## [4.3.3] - 2023-12-21

### Added

- Added missing Arabic translations.
