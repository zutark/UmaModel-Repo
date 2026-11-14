# UmaModel-Repo

External model & animation content pack repository for the **UmaModel** Minecraft NeoForge (`1.21.1`) mod.

> [!NOTE]
> The **UmaModel** mod on Modrinth/CurseForge is a clean client-side PMX/VMD rendering engine with **no third-party character assets bundled inside the JAR**. All character models and motion packs live here as optional external packs.

---

## Quick Installation

1. Download the latest **`umamodel-content-pack-*.zip`** from [**Releases**](https://github.com/zutark/UmaModel-Repo/releases).
2. Launch Minecraft with **UmaModel** installed and open the mod menu (default key or `/umamodel`).
3. Click **`Packs Folder`** — this opens `.minecraft/config/umamodel/packs/`.
4. Drop the downloaded `.zip` archive directly into `config/umamodel/packs/` (**no need to extract it**).
5. Click **`Reload`** in the mod menu and pick your character & outfit style.

### Supported Pack Locations
- **Recommended (Zip or Extracted Pack):** `.minecraft/config/umamodel/packs/`
- **Loose custom `.pmx` models:** `.minecraft/config/umamodel/models/` or `packs/`
- **Loose custom `.vmd` animations:** `.minecraft/config/umamodel/vmd/` or `packs/`

---

## Content Pack `v0.1.0` — What's Included

- **24 characters / 52 outfit styles** (`.pmx` + textures, lazy-loaded with GPU texture deduplication and LRU cache eviction)
- **7 motion presets** (`.vmd`): `idle1`–`idle5`, `walk`, `run`
- **Dynamic facial expressions & reactive ears/tails** per character personality
- **Multiplayer sync compatible** — works seamlessly between users on the public engine build (with this pack) and the standalone build

<details>
<summary>Full Character & Outfit List (24 characters, 52 styles)</summary>

| Character | Outfits | Included Styles |
| --- | :---: | --- |
| Mejiro McQueen | 4 | Frontline Elegance, End of the Skies, Fair Lady of the Waves, Casual Wear |
| Oguri Cap | 2 | Starlight Beat, Ashen Miracle |
| Special Week | 3 | Special Dreamer, Ruler of Japan, Hopp'n♪Happy Heart |
| Tokai Teio | 3 | Peak Joy, Beyond the Horizon, Casual Wear |
| Agnes Tachyon | 3 | Tach-nology, Lunatic Lab, Casual Wear |
| Manhattan Cafe | 2 | Creeping Shadow, Casual Wear |
| Rice Shower | 2 | Rosy Dreams, Vampire Makeover! |
| Wonder Acute | 2 | Butterfly Sting, Casual Wear |
| Narita Taishin | 1 | Nevertheless |
| Agnes Digital | 2 | Full-Color Fangirling, Fanatic♡Jiangshi |
| Kitasan Black | 3 | Gilded Shrine to Glory, Crane's Ambition, Casual Wear |
| Satono Diamond | 3 | Natural Brilliance, Jade's Prosperity, Casual Wear |
| Sweep Tosho | 1 | Platanus Witch |
| T.M. Opera O | 3 | O Sole Suo!, New Year, Same Radiance!, Casual Wear |
| Tamamo Cross | 1 | Fast as Lightning |
| Daiwa Scarlet | 2 | Peak Blue, Nuit Étoilée de Scarlet |
| Symboli Rudolf | 2 | Emperor's Path, Archer by Moonlight |
| Admire Vega | 2 | Starry Nocturne, Casual Wear |
| Curren Chan | 3 | Fille Éclair, Ma Chérie of the New Moon, Casual Wear |
| Nakayama Festa | 1 | Desperate Measures |
| Haru Urara | 2 | Bestest Prize ♪, New Year ♪ New Urara! |
| Meisho Doto | 1 | Turbulent Blue |
| Nice Nature | 2 | Poinsettia Ribbon, Run & Win |
| Daitaku Helios | 2 | Fun☆Fun☆Party Night, Casual Wear |

</details>

---

## Pack Format (For Custom Packs)

You can drop any `.zip` / `.umapk` archive (or folder) into `config/umamodel/packs/`:
- **Structured packs:** contain `models/catalog.json` (or `catalog.json`) and/or `vmd/index.json` (or `index.json`).
- **Loose packs:** any `.pmx` and `.vmd` files inside a zip archive are automatically discovered along with nearby textures (`textures/`, `Texture2D/`, or relative paths).

---

## Disclaimer & Rights

This is an unofficial, non-commercial fan-made content repository.
All rights to **Umamusume: Pretty Derby**, its characters, designs, and original game assets belong to **Cygames, Inc.**
If you are a rights holder and wish to request removal of any content, please open an issue in this repository and it will be removed promptly.
