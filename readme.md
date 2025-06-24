# Unofficial crDroid 11.0 for Redmi Note 11 (`spes`)

**Maintainer:** Jingexz01  
**Status:** Unofficial  
**Build Date:** 2025-06-24

---

## 📱 Device-side changes:
- Initial unofficial crDroid 11.0 build for spes
- Removed unused and broken WFD/Miracast blobs
- Cleaned up proprietary blobs and fixed prebuilt library inconsistencies
- Resolved Soong build errors (AIDL interfaces, missing arch variants)
- Fixed missing variants for key prebuilt libraries
- Removed unused broken HALs
- Synced with latest Lineage blobs for vendor setup

---

## 💡 ROM-side changes (from crDroid 11.0 base):
- June 2025 Android security patch
- Thermal and performance optimizations
- SystemUI: heap memory cleanup on screen off
- SystemUI Boost Framework introduced
- ActivityManager: improved compaction logic
- LineageParts: prevent key disabler restore on boot
- QS Animator: crash fix and cleanup
- WallpaperManagerService: crash fix
- Fixed splash screen and observer callback issues
- AppLock, Smart Charging, and Launcher3 improvements

---

## ⚠️ Known Issues:
- WFD/Miracast is not supported (SD680 limitation)
- FM Radio may not work on some regional variants
- Clean flash **recommended**

---

## 🔧 Installation Notes:
- Use **crDroid Recovery** (recommended)
- Format `data` before flashing
- GApps optional *(NikGApps / MindTheGapps recommended)*

---

## 📲 Installation Guide:
- [Wiki](https://github.com/Jingexz01/Unoffical_Redmi_Note_11_crDroid/wiki)

---

## 👤 Credits:
- crDroid
- Lineage OS

---

**This is an unofficial build. Flash at your own risk. I'm not responsible for bricked devices or lost data.**
