# ACUUltraPlus

**No more NPC and clothing LOD popping in Assassin's Creed Unity (PC).**

In AC Unity, NPCs and their clothes often change to low-detail models near you. ACUUltraPlus stops this. It also increases the detail of the world, the crowds and the shadows above the Ultra preset.

ACUUltraPlus is a plugin for [ACUFixes](https://github.com/NameTaken3125/ACUFixes) by NameTaken3125. It does not change game files. To remove it, you delete one file.

> **Beta (v0.1).** Expect some glitches. Crashes can also occur. Your crash reports help me fix them.

**[Download the latest release](https://github.com/breakwinz/ACUUltraPlus/releases/latest)**

VirusTotal scan of `ACUUltraPlus-0.1.zip`: [results](https://www.virustotal.com/gui/file/3288c39e434630b9e82ab005cce5c8b9102f498baa6876d74424a6da18068df5)

## Features

- **NPC LOD pop-in fixed.** NPCs and their clothes stay at full detail.
- **Bigger full-detail crowds.** More NPCs around you have full detail.
- **2× building LOD loading distance.** Less low-detail pop-in on buildings.
- **Maximum world detail.** World objects always use their best models.
- **4× sharper sun shadows.** Shadows also reach 4× farther.

## Performance

This mod is for high-end PCs. The extra detail decreases your frame rate.

| Test PC | |
|---|---|
| CPU | Ryzen 7 7800X3D |
| GPU | RTX 4090 24 GB |
| RAM | 32 GB DDR5-6000 |
| Resolution | 3440×1440 |

At the same busy location, the test PC gets approximately 150 fps with ACUFixes only. With ACUUltraPlus, it gets approximately 100 fps. That is a decrease of approximately 33 %.

Most of the load is on the GPU and the video memory. On a less powerful GPU, the decrease can be larger.

## Requirements

- Assassin's Creed Unity for PC, version 1.5.0 (the last patch)
- [ACUFixes v0.9.2](https://github.com/NameTaken3125/ACUFixes/releases), which includes the plugin loader

## Installation

1. Close the game.
2. If you do not have ACUFixes v0.9.2, install it. Put its files in the same folder as `ACU.exe`.
3. Download `ACUUltraPlus-0.1.zip` from [Releases](https://github.com/breakwinz/ACUUltraPlus/releases/latest) and extract it.
4. Copy `ACUUltraPlus.dll` into `Assassin's Creed Unity\ACUFixes\plugins\`.
5. Start the game.
6. Open `ACUFixes\plugins\ACUUltraPlus.log`. Make sure that it contains the line **ACUUltraPlus Loaded**.

We recommend the in-game Shadow Quality setting **High**. Set it, then restart the game. Do not change the shadow quality during play. In tests, this caused a crash one time.

**To remove the mod:** Delete `ACUUltraPlus.dll`. The mod changes nothing else.

## Known limitations

- This is a beta. Glitches and crashes can occur.
- Tested in single player on one PC, with ReShade.
- Not tested with other mods. Please report problems.
- The settings are fixed. This release has no settings menu.

## If the game crashes

When the game crashes, the mod writes two files into `ACUFixes\plugins`:

- `ACUUltraPlus_crash_<date>_<time>.txt`
- `ACUUltraPlus_crash_<date>_<time>.dmp`

While the game runs normally, the mod writes nothing. Please [open an issue](https://github.com/breakwinz/ACUUltraPlus/issues) and attach these two files and `ACUFixes\ACUFixes-PluginLoader.log` (zip them if GitHub refuses a file type). Also tell us what you did when the crash occurred.

The crash files can contain file paths from your PC. In the `.txt` file, your user folder is shortened to `%USERPROFILE%`.

## Disclaimer

This is an unofficial fan mod. Ubisoft did not make or approve it. The download contains no Ubisoft files. Use it at your own risk.

Thanks to NameTaken3125 for ACUFixes and the plugin loader.
