# Meridian Front - official mods

Downloadable official mods for **Meridian Front**. The game reads `catalog.json` from this repository
(`https://raw.githubusercontent.com/hasanlior/rts-mods/main/`) and downloads a mod when a player presses
**DOWNLOAD** on the MODS > OFFICIAL MODS screen.

| Mod | Version | Price |
|---|---|---|
| The Great War 1914-1918 (`ww1_great_war`) - Ottoman Empire, Britain, Germany, France and Russia, Money and Oil, seven battlefields | 1.0.0 | Free |

Packages are data only (JSON). The game checks each download's size and SHA-256 against `catalog.json` before it
installs it.

## Publishing

This repository is generated: the sources and tools live in the game repository (`OfficialMods/src`,
`tools/official_mods`). There, run `python3 tools/official_mods/pack.py`, then copy `OfficialMods/catalog.json`
and the `*.zip` packages here and push to `main`.
