# Universal Image Resizer & Downloader

**Instantly resize and download any image you see on the web — 100% client-side.**

Hover over any image to see a "Resize" chip, or use **Alt + Right-Click**. Select a preset, type custom dimensions, or use the **Fast Click** button for instant results.

---

## ✨ Features

*   **⚡ Global Fast Click:** A **"⚡ 9:16"** button now appears on the hover chip for *every* image.
    *   **Click:** Instantly sets the size to **1080×1920** (Vertical HD), mode to **Cover**, and opens the panel for crop adjustment.
    *   **Alt + Click:** Instantly **downloads** the resized/cropped image without opening the panel.
*   **🎨 Smart Resizing:**
    *   **Contain:** Adds letterboxing (customizable color) to fit usage (e.g., 1:1 square).
    *   **Cover:** Crops the image to fill the target aspect ratio (perfect for full-screen backgrounds/phone wallpapers).
    *   **Stretch:** Forces exact dimensions.
*   **📱 Platform Presets:** Built-in sizes for **Suno**, **Spotify**, **YouTube**, **TikTok**, and **Instagram**.
*   **🔒 Private & Fast:** All processing happens **locally in your browser**. Images are never uploaded to any server.
*   **💾 Formats & Quality:** Save as **JPG**, **PNG**, or **WEBP**. The script remembers your last-used format (Sticky Format).
*   **📝 Smart Filenames:** Custom templates with tokens like `{name}`, `{w}`, `{h}`, `{YYYY}`, `{site}`, and `{title}`.

---

## 🚀 How to Use

1.  **Install** the script in a userscript manager like Tampermonkey or Violentmonkey.
2.  **Hover** over any image on a webpage.
3.  **Click "Resize"** to open the full panel.
4.  **Click "⚡ 9:16"** for instant vertical crop (or **Alt+Click** to quick download).

### ⌨️ Shortcuts & Tricks
*   **Alt + Right-Click** on an image: Opens the resize panel directly.
*   **r key**: Press `r` while an image is focused or being hovered to open the panel.
*   **Alt + Click "⚡ 9:16"**: Instant download (bypasses preview).

---

## 📋 Included Presets

### 🎵 Suno / Spotify / Music
*   **Fast Click:** 1080×1920 (Vertical Video Cover)
*   **Suno Video:** 1080×1920, 720×1280 (Min)
*   **Album Covers:** 3000×3000, 1600×1600

### 📺 YouTube
*   **Thumbnail:** 1280×720
*   **Channel Banner:** 2560×1440
*   **Shorts:** 1080×1920

### 📱 TikTok & Instagram
*   **TikTok Video:** 1080×1920
*   **Instagram Post:** 1080×1080 (Square), 1080×1350 (Portrait)
*   **Story / Reel:** 1080×1920

---

## ⚙️ Configuration

Open the panel to tweak settings:
*   **Filename Template:** Customize how files are named.
*   **Chip Corner:** Move the hover chip to a different corner.
*   **Min Image Size:** Prevent the chip from showing on tiny icons.
*   **Trigger:** Choose between Alt+Right-Click or standard Right-Click replacement.

---

## 🔒 Permissions

This script uses `GM_xmlhttpRequest` solely to bypass CORS restrictions when fetching the image data *for the image you selected*. No data is sent to me or any third party.

---

**Author:** Eliminater74
**License:** MIT
