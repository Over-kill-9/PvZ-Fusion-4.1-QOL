# PvZ Fusion 4.1 English + QOL Patch (MelonLoader + Blooms QOL Port)

A lightweight drop-in **MelonLoader + Quality-of-Life (QOL)** patch updated for **Plants vs. Zombies: Fusion 4.1 (English PC)**.

## Features
* **Forced Pumpkin Fusions (`Left Shift`):** Hold **Left Shift** while placing a plant to prioritize fusing with a Pumpkin on that tile.
* **Forced Flower Pot Fusions (`Left Alt`):** Hold **Left Alt** while placing a plant to prioritize fusing with a Flower Pot on that tile.
* **Hide Metal Objects (`F10`):** Press **F10** to toggle hiding newly spawned metal objects/buckets (automatically re-enables visibility when attracted by a Magnet-shroom).
* **Full 4.1 Compatibility:** Patched `CreatePlant.SetPlant` and `CreatePlant.CheckMix` Harmony hooks to support 4.1's `TravelRoguePlantData` parameter without breaking normal plant fusions.

## How to Install
1. Download and extract **Tproplay's PvZ Fusion 4.1 English PC** build from [Tproplay/Pvz-Fusion-Translation-Lite Releases](https://github.com).
2. Download **`PvZ-Fusion-4.1-QOL-Patch.zip`** from the [Releases](../../releases) page.
3. Extract all contents of `PvZ-Fusion-4.1-QOL-Patch.zip` directly into your `PvZ-Fusion-4.1-English-PC` folder (where `PlantsVsZombiesRH.exe` is located).
4. Run **`PlantsVsZombiesRH.exe`**. *(First launch takes ~30-60 seconds while MelonLoader generates `Il2CppAssemblies` for 4.1; subsequent launches are instant).*

## Credits & License
Shared strictly non-commercially under **CC BY-NC 4.0** in accordance with upstream community licenses. Full credit goes to:
* **LanPiaoPiao / LanPiaoPiaoFly** - Original *Plants vs. Zombies: Fusion* developers.
* **Tproplay** - Base 4.1 English translation patch: https://github.com/Tproplay/Pvz-Fusion-Translation-Lite
* **cassidy (SillyStar-Github)** - Original `Blooms_QOL` C# mod source: https://github.com
* **Blooms / Teyliu & the PC Translation Community** - Original translation terminology and MelonLoader runtime setup: https://github.com/Teyliu/PVZF-Translation
