A cross-platform desktop application for browsing, organizing, and previewing local media collections — built from scratch in Java and JavaFX.


# Why I built this
Normal gallery applications tend lower the quality of images, force you behind a cloud subscription, or simply don't provide a visual way of organizing your files. Not to mention, the privacy of your files! This project was built for people like you, me, and my beloved mother, who need a fast, private, and fully local gallery manager.

# Features:
- **Multithreaded Thumbnail Caching:** A cache system that works in parallel to the UI thread to generate smaller quality image with a faster file format, of the existing media for thumbnails; Then it saves that thumbnails in an invisible folder for future use. The first launch may be slow, but every subsequent launch is near-instant.
- **Live Directory Switching:** Choose a custom gallery directory or use a default one. Gallery directories are saved via the Windows Registry (macOS Plist). You can also switch galleries mid-session and watch the changes take effect in real time.
- **Gallery Controls:** Items can be sorted alphabetically (A–Z, Z–A), by file size (largest-first or smallest-first), and randomly - to help you rediscover forgotten files!
- **Rich Media View:** Full-resolution image preview with zoom and pan. Video playback includes play/pause, volume control, and click-to-seek on the progress bar.

## Supported formats:
- PNG
- JPG (JPEG)
- WebP
- GIF
- MP4

## Planned Features:
- Mac Compatibility (currently app only runs on windows)
- Cell Uniformity (Visual aspect of each cell)
- Folder / sections view
- Drag-and-drop reorder
- Rename & delete items
- Live cache & gallery updates (for items added while gallery is running)
- Gallery search
- Support for formats:
  - WebM
  - MKV
  - MOV
  - HEIC
  - HEVC
