# PvZ Fusion 4.1 English + QOL Patch (MelonLoader + Blooms QOL Port)

A lightweight drop-in **MelonLoader + Quality-of-Life (QOL)** patch updated for **Plants vs. Zombies: Fusion 4.1 (English PC)**.

## Features

* **Forced Pumpkin Fusions (`Left Shift`):** Hold **Left Shift** while placing a plant to prioritize fusing with a Pumpkin on that tile.
* **Forced Flower Pot Fusions (`Left Alt`):** Hold **Left Alt** while placing a plant to prioritize fusing with a Flower Pot on that tile.
* **Hide Metal Objects (`F10`):** Press **F10** to toggle hiding newly spawned metal objects/buckets (automatically re-enables visibility when attracted by a Magnet-shroom).
* **Full 4.1 Compatibility:** Patched `CreatePlant.SetPlant` and `CreatePlant.CheckMix` Harmony hooks to support 4.1's `TravelRoguePlantData` parameter without breaking normal plant fusions.

## How to Install

1. Download and extract **Tproplay's PvZ Fusion 4.1 English PC** build from [Tproplay/Pvz-Fusion-Translation-Lite Releases](https://github.com/Tproplay/Pvz-Fusion-Translation-Lite/releases).
2. Download **`PvZ-Fusion-4.1-QOL-Patch.zip`** from the [Releases](../../releases) page.
3. Extract all contents of `PvZ-Fusion-4.1-QOL-Patch.zip` directly into your `PvZ-Fusion-4.1-English-PC` folder (where `PlantsVsZombiesRH.exe` is located).
4. Run **`PlantsVsZombiesRH.exe`**. *(The first launch may take approximately 30–60 seconds while MelonLoader generates `Il2CppAssemblies` for 4.1. Subsequent launches should be faster.)*

**Note:** This patch was developed for Tproplay's English PC build of PvZ Fusion 4.1. Compatibility with other versions is not guaranteed.

## Credits & Acknowledgments

This is an unofficial, non-commercial community compatibility project. Full credit goes to:

* **LanPiaoPiao / LanPiaoPiaoFly** — Original *Plants vs. Zombies: Fusion* developers.
* **Tproplay** — Base 4.1 English translation patch: https://github.com/Tproplay/Pvz-Fusion-Translation-Lite
* **cassidy (SillyStar-Github)** — Original `Blooms_QOL` C# mod source: https://github.com/SillyStar-Github/Blooms-QOL
* **Blooms / Teyliu & the PC Translation Community** — Original translation terminology and MelonLoader runtime setup: https://github.com/Teyliu/PVZF-Translation
* **Over-kill-9** — Ported the original QOL mod to PvZ Fusion 4.1, updated incompatible method signatures, resolved compilation errors, and packaged the compatibility patch.

## Disclaimer

This is an unofficial community project and is not affiliated with or endorsed by the original PvZ Fusion developers, Tproplay, Blooms, or other contributors.

All original game content, translations, and third-party modifications belong to their respective creators and remain subject to their applicable licenses and permissions.
