# Changelog

All notable changes to the "Universal Image Resizer & Downloader" script will be documented in this file.

## [1.7] - 2025-12-16
### Added
- **Global Fast Click (⚡ 9:16):** Added a quick-action button to the hover chip for *all* images.
    - Click to instantly preset 1080x1920 (Cover) and open the panel.
    - **Alt+Click** to instantly download the resized image.
- **Suno Support:** Added dedicated presets for Suno (including minimum video requirements).
- **New Presets:** Added "Spotify / DistroKid" to the platform list for easier album cover resizing.

### Changed
- **Optimization:** Added debouncing to scroll and resize event listeners. This significantly reduces CPU usage on pages with many images.
- **UI:** Updated the preset dropdown order to prioritize common content creation platforms (Suno, YouTube, TikTok).
- **Style:** Improved chip layout stability to prevent display issues on some sites.

### Fixed
- Code cleanup and minor linting fixes for better stability.

---

## [1.6] - Previous Release
### Added
- Initial "Platform Presets" dropdown.
- Sticky format (remembers last used extension).
- Timestamped tokens support.
