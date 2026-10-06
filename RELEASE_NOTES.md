## ZebPic v1.0.1b (beta)

Test version of the next release. It is published as a **pre-release**: version 1.0.0 does not offer it as an automatic update.
Install it over 1.0.0 with the installer; ratings, tags, albums and settings are kept.

### Download

- **ZebPic-Setup.exe** - installer (recommended).
- **ZebPic-Portable.zip** - portable version; unzip and run `ZebPic.exe`.

Windows 10 or 11, 64-bit. Nothing else needs to be installed.

The installer is not digitally signed yet. If Windows SmartScreen shows a warning, choose **More info**, then **Run anyway**.

### New

- **Albums**: named lists of photos from any folders. The files stay where they are.
- **Edit History**: every Save over the original keeps the previous version; any recorded edit can be undone later.
- **Look in**: search and filter this folder, the folder with its subfolders, or every organized photo on the computer - in Browse and in both Sort panels.
- **Faces filter**: photos without faces, with one face, with a group (detection only, on this computer).
- **Map**: "show on map" next to GPS coordinates opens a small OpenStreetMap window; the view can be saved as a picture.
- **Editor**: font choice for text and watermarks, a new **Engrave** look next to Emboss, strength slider, unfinished edits are kept as drafts.
- **Batch** resize and watermark: optional "Save over the original files"; resize by width, by height or both.
- **Duplicates**: similarity slider.
- Opening a single photo from Explorer starts much faster.
- Mouse wheel changes any slider under the pointer.

### Fixed

- Video playback uses the Windows media player engine: MP4 files that froze or stopped early now play.
- A video whose codec is missing in Windows now says which codec is needed (for example HEVC) instead of a black screen.
- The window no longer opens larger than the screen on small or scaled displays.
- Font list was unreadable in the dark theme.
- Folder tree showed an expand arrow for folders without subfolders.
- Albums and lists now notice files deleted by other programs.

### Known limitations

- HEVC (H.265) videos, such as .MOV files from recent phones and cameras, need "HEVC Video Extensions" from Microsoft Store.
- WEBP and HEIC/HEIF photos need the Windows image extensions from Microsoft Store; they cannot be saved in those formats.
- RAW camera formats are not supported yet.
- This is a beta: please report problems on the Issues page.

---

## ZebPic v1.0.0

First public release.

### Download

- **ZebPic-Setup.exe** - installer (recommended).
- **ZebPic-Portable.zip** - portable version; unzip and run `ZebPic.exe`.

Windows 10 or 11, 64-bit. Nothing else needs to be installed.

The installer is not digitally signed yet. If Windows SmartScreen shows a warning, choose **More info**, then **Run anyway**.

### What is in this version

- **Browse** large folders with a fast thumbnail grid; photos and videos together; filters and search.
- **View** photos with zoom and pan, and play videos.
- **Organize** with ratings, color labels and tags, stored without modifying your files.
- **Sort** between two folders side by side with drag and drop.
- **Find duplicates**: exact copies and visually similar photos, with review before removal.
- **Edit**: adjustments, crop, resize, rotate, pencil, text, text and picture watermarks with rotation and emboss.
- **Batch** resize and watermark into a separate subfolder.
- Dark and light themes, automatic update check.

### Known limitations

- WEBP and HEIC/HEIF photos need the Windows image extensions from Microsoft Store; they cannot be saved in those formats.
- Video playback depends on the codecs installed in Windows.
- RAW camera formats are not supported yet.
