# 🎨 ZEUSosX_044 - Windows 11 File Explorer Styler Theme

> **100% Verified Universal 44px Single-Row Layout for Windows 11 File Explorer**

An elegant, minimal single-row configuration optimized to completely remove cluttered stock borders and resolve common layout bugs across modern Windows builds (24H2/25H2).

---

## 📸 Preview



*Windows 11 File Explorer with ZEUSosX_044 theme applied - Ultra-compact 44px single-row layout*

---

## ✨ Key Features

### 📏 **44px Height - Ultra-Compact Layout**
A beautifully compressed single-row design that maximizes content viewing space while maintaining perfect visual balance.

### 🎯 **100% Verified Universal Scale**
Rigorously tested and calibrated across **ALL DPI Scaling factors**:
- ✅ 100%
- ✅ 125%
- ✅ 150%
- ✅ 175%
- ✅ 200%
- ✅ 225%

Remains flawlessly functional without shifting or breaking at any scale.

### 📐 **True Geometric Centering**
- Strict `-30` margin offset on the `CommandBarControlRootGrid`
- Typography bounding boxes perfectly balanced
- "Details" element identically aligned within the vertical center axis of Address Bar items
- Verified via exact baseline pixel-matching at integer scale steps (100%, 125%, 150%, 200%)

### 🔽 **Stable Drop-Down Behavior**
The exact geometric calculation guarantees that the 3-dots overflow menu reliably opens downwards across all tested DPI scales instead of glitching upwards.

### 🎭 **Mica Translucent Effect**
Leverages Windows 11's modern Mica material design for a premium, contemporary appearance.

---

## 🚀 Installation Guide

### Prerequisites
1. **Windhawk** installed on your system
   - Download: https://windhawk.net/

### Step-by-Step Installation

#### 1. Install Windhawk
- Download and install from https://windhawk.net/

#### 2. Install the Windows 11 File Explorer Styler Mod
- Launch the Windhawk app
- Click the **"Explore"** button
- Search for **"windows-11 File Explorer styler"**
- Click **Install**

#### 3. Open the Mod Settings
- Go to the Windhawk **Home** page
- Find and open **"windows-11 File Explorer styler"**
- Click the **"Settings"** tab

#### 4. Switch to Textual Mode
- In the settings panel, locate and click **"Textual mode"**

#### 5. Backup Current Settings (Optional but Recommended)
- Copy all text in the text editor
- Save it to a Notepad file for safekeeping

#### 6. Clear & Paste YAML Code
- Clear everything in the text editor
- Copy the YAML code from `ZEUSosX_044.yaml` in this repository
- Paste it into the mod settings' text editor

#### 7. Apply Changes
- Click **"Save settings"**
- Changes take effect instantly! ✅

---

## 📋 YAML Configuration

The complete YAML configuration is available in: **[ZEUSosX_044.yaml](./ZEUSosX_044.yaml)**

Key configuration highlights:
```yaml
theme: ZEUSosX_044
backgroundTranslucentEffect: mica
explorerFrameContainerHeight: 44
```

---

## ⚠️ Known Bugs & Limitations

This ultra-compressed 1-row layout achieves its minimalism via negative XAML bounds inside the compiled window chrome. Certain native behaviors require manual handling:

### 🖱️ **Window Dragging (Mouse & Touch)**
- **Issue:** Cannot click blindly on the top bar to drag the window
- **Solution:** Target either:
  - The **Search Box icon area**, or
  - The **empty gap** between Close/Caption buttons and Search Box

### 📑 **No Tab Strip UI / Context Warning**
- **Issue:** Tab strip region is completely collapsed
- **Warning:** Never select "Open in new tab" from context menus (new tab created but invisible/inaccessible)
- **Solution:** Always use **"Open in new window"** instead

### 🖥️ **Desktop Launch Focus Glitch**
- **Issue:** Opening a folder directly from Windows Desktop may trigger a native focus bug, causing Address Bar background to lock into solid white
- **Solution:** Launch File Explorer via:
  - This PC (My PC), or
  - Standard pinned shortcut

### 🔤 **High-DPI Font Behavior**
- **Expected:** Minor UI font shifts (e.g., search text jumping up by 2px at extreme scales like 225%)
- **Cause:** WinUI accessibility overrides
- **Status:** This is expected and normal behavior

---

## 📜 Terms of Use & Copyright

### ✅ You CAN:
- Use it for free
- Apply it to your File Explorer
- Share this link with others

### ❌ You CANNOT:
- ~~Modify or alter the code~~
- ~~Use it commercially or for profit~~
- ~~Sell it~~
- ~~Take credit for creating it~~

**License:** Custom - All Rights Reserved by ZEUSosX

For complete license terms, see [LICENSE.txt](./LICENSE.txt)

---

## 💬 Feedback & Support

If you encounter issues or have suggestions:
1. Check the **Known Bugs & Limitations** section above
2. Verify you're using the latest Windows 11 build (24H2/25H2)
3. Test at your specific DPI scaling level

---

## 📌 Version Info

- **Theme Name:** ZEUSosX_044
- **Type:** Windows 11 File Explorer Styler (Windhawk Mod)
- **Height:** 44px (Single-Row)
- **DPI Support:** 100%, 125%, 150%, 175%, 200%, 225%
- **Windows Builds:** 24H2, 25H2
- **Status:** Fully Verified & Stable ✅

---

## 🙏 Credits

Created by **ZEUSosX**

Special thanks to the Windhawk community for this powerful theming platform.

---

**Made in Greece, by ZEUSosX, June 2026.**

---

**Enjoy your minimalist File Explorer! 🎨**
