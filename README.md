# Dolphin GraphicsMagick Actions

WORK IN PROGRESS

The "Dolpin GraphicsMagick Actions" Extension adds various image editing functionalities to the right-click menu of the KDE Dolphin File manager.

To use it, you need to have [GraphicsMagick](http://www.graphicsmagick.org/) installed on your system (accessible in your `$PATH`). GraphicsMagick is a fork of ImageMagick, with a smaller codebase, and additional features. The fork is pretty long ago and both projects are active.

Actions

 * Compress and resize
    * Advanced optimization for web
    * Compress in % (change quality)
    * Resize in % or square

 * Convert and rotate
    * Convert to all formats supported by ImageMagick
    * Convert to PDF or PDF/A*1
    * Generate favicons for browser/android/apple/ms
    * Rotate
    * Overturn vertically/horizontally

 * Metadata
    * Set file's datetime from Exif date.
    * Set file date from file's name
    * Set Exif datetime from file's date.
    * Set Exif datetime from file's name.
    * Add comment
    * View metadata
    * Extract metadata to file
    * Remove all metadata

 * Tools
    * Create animated GIF/APNG/WEBP
    * Append to right, Append to bottom
    * GrayScale
    * Change transparent to color
    * Change color to transparent
    * Replace color
    * Drop shadow

## Installation

To install or uninstall the extension, run:

```bash
./install.sh
./uninstall.sh
```

When running it as root (with `sudo`, `run0` or `pkexec`) the extension gets installed for all users.
