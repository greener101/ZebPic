## ZebPic v2.0.0b1 (beta)

First test version of ZebPic 2.0. It is published as a **pre-release**: version 1.1.0 does not offer it as an automatic
update. Install it over 1.1.0 with the installer; ratings, tags, albums and settings are kept.

### Download

- **ZebPic-Setup.exe** - installer (recommended).
- **ZebPic-Portable.zip** - portable version; unzip and run `ZebPic.exe`.

Windows 10 or 11, 64-bit. Nothing else needs to be installed.

The installer is not digitally signed yet. If Windows SmartScreen shows a warning, choose **More info**, then **Run anyway**.

### New: Smart Search

Optional, off until you turn it on in Settings > Smart Search (or with the sparkles button next to the search box).
Turning it on downloads its components once, about 254 MB. All analysis runs on your computer; photos are not sent anywhere.

- **Search by what is on the photo.** Type a description in English or Russian - "sunset over the sea", "dog on a sofa",
  "people on stage" - and the closest photos come first. It can be combined with `tag:`, `rating:` and `label:`.
- **Library.** Smart search covers the folders you put into the Library: in Settings, or by right-clicking a folder and
  choosing Add to Library. System and program folders are skipped, so a whole drive can be added. Photos smaller than a
  chosen size (100 KB by default) are left out.
- **Indexing** starts with the Start Indexing button and can be paused. The time left is shown in Settings and next to the
  search box. New photos in the Library folders are picked up by themselves; indexing can be limited to the time the
  computer is not in use.
- **People.** Faces found in the Library are grouped into persons, listed in the left panel as a list or as round
  portraits. Give a person a name and type it into the search box, alone, with other names or with a description
  ("Anna on the beach"). Corrections: Merge Into, Move to Person, Not This Person, Not a Person, Ignore (can be undone).
- **External disks.** A Library folder on a disk that is disconnected keeps its index. The disk is recognized when it
  comes back, also under another drive letter, and nothing is indexed again. Clean Up Index removes entries of photos
  that are really gone.
- **Look in** has four choices now: this folder, this folder and subfolders, Library, whole computer (photos with a
  rating, label or tag). Smart search and People work in the Library.

### Also new since 1.1.0

- **Editor, crop**: the frame can be moved, resized by its corners (keeping the chosen proportions) and applied with a
  double click inside it.
- **Duplicates**: the photo window has zoom buttons and zooms with the mouse wheel.
- **Map**: a button opens the place on openstreetmap.org in the web browser.
- **Settings > Updates**: when Check for Updates finds a new version, an Update Now button appears there.
- **Left panel**: scrolls as a whole when it does not fit a low screen; the folder chosen under Recent Folders or
  Favorites stays marked.

### Known limitations of this beta

- A search for something no photo shows still lists the closest photos; there is no "nothing found" yet.
- Indexing takes about a third of a second per photo on an older laptop; large libraries (tens of thousands of photos)
  and real external disks have had little testing. Reports are welcome.
- Faces are grouped automatically and sometimes one human is split into two persons: use Merge Into.
- Videos are not covered by smart search.
- HEVC (H.265) videos, such as .MOV files from recent phones and cameras, need "HEVC Video Extensions" from Microsoft Store.
- WEBP and HEIC/HEIF photos need the Windows image extensions from Microsoft Store; they cannot be saved in those formats.
- RAW camera formats are not supported yet.

### License

Personal, non-commercial use only, as for 1.1.0; see LICENSE.txt. The smart search components are made by other authors
under the MIT and Apache-2.0 licenses; see THIRD-PARTY-NOTICES.txt.

---

## ZebPic v1.1.0

The second stable release. It contains everything from the two 1.0.1 beta versions. Version 1.0.0 offers it as an update;
the beta versions do as well.

### Download

- **ZebPic-Setup.exe** - installer (recommended).
- **ZebPic-Portable.zip** - portable version; unzip and run `ZebPic.exe`.

Windows 10 or 11, 64-bit. Nothing else needs to be installed.

The installer is not digitally signed yet. If Windows SmartScreen shows a warning, choose **More info**, then **Run anyway**.

### License

ZebPic is now licensed for **personal, non-commercial use only**. Use at work or in an organization is not permitted.
See LICENSE.txt. Copies of earlier versions stay under the license they were released with.

### New since 1.0.0

- **Russian interface.** The language is chosen in Settings > General (English, Russian, or the language of Windows) and
  changes after a restart. Each language is one file in the `lang` folder.
- **Albums**: named lists of photos from any folders. The files stay where they are.
- **Edit History**: every Save over the original keeps the previous version; any recorded edit can be undone later.
- **Look in**: search and filter this folder, the folder with its subfolders, or every organized photo on the computer -
  in Browse and in both Sort panels.
- **Faces filter**: photos without faces, with one face, with a group (detection only, on this computer).
- **Map**: "show on map" next to GPS coordinates opens a small OpenStreetMap window; the view can be saved as a picture.
- **Editor**: font choice for text and watermarks, an **Engrave** look next to Emboss, strength slider, unfinished edits
  are kept as drafts, mirror icons for the flip buttons.
- **Batch** resize and watermark: optional "Save over the original files"; resize by width, by height or both.
- **Duplicates**: similarity slider; double-click opens the photo in a separate window with its name, folder, size and date.
- Opening a single photo from Explorer starts much faster.
- Mouse wheel changes any slider under the pointer.

### Fixed

- Video playback uses the Windows media player engine: MP4 files that froze or stopped early now play.
- A video whose codec is missing in Windows says which extension is needed (for example HEVC) instead of a black screen.
- The window no longer opens larger than the screen on small or scaled displays.
- Font list was unreadable in the dark theme.
- Folder tree showed an expand arrow for folders without subfolders.
- Albums and lists notice files deleted by other programs; album counters count only the photos that exist.

### Known limitations

- HEVC (H.265) videos, such as .MOV files from recent phones and cameras, need "HEVC Video Extensions" from Microsoft Store.
- WEBP and HEIC/HEIF photos need the Windows image extensions from Microsoft Store; they cannot be saved in those formats.
- RAW camera formats are not supported yet.
- Metadata field names (EXIF, IPTC, XMP) and the license texts are in English in every language.

---

## ZebPic v1.0.1b2 (beta)

Second test version of the next release. It is published as a **pre-release**: earlier versions do not offer it as an
automatic update. Install it over 1.0.0 or over beta 1 with the installer; ratings, tags, albums and settings are kept.

### Download

- **ZebPic-Setup.exe** - installer (recommended).
- **ZebPic-Portable.zip** - portable version; unzip and run `ZebPic.exe`.

Windows 10 or 11, 64-bit. Nothing else needs to be installed.

The installer is not digitally signed yet. If Windows SmartScreen shows a warning, choose **More info**, then **Run anyway**.

### New in beta 2

- **Russian interface.** The language is chosen in Settings > General (English, Russian, or the language of Windows) and
  changes after a restart. Each language is one file in the `lang` folder, so more languages can be added without a new build.
- **Duplicates**: double-click opens the photo in a separate window with its name, folder, size and date; Esc closes it.
- Flip buttons in the editor are icons now.

Everything else is as in beta 1.

### Known limitations

- HEVC (H.265) videos, such as .MOV files from recent phones and cameras, need "HEVC Video Extensions" from Microsoft Store.
- WEBP and HEIC/HEIF photos need the Windows image extensions from Microsoft Store; they cannot be saved in those formats.
- RAW camera formats are not supported yet.
- Metadata field names (EXIF, IPTC, XMP) and the license texts are in English in every language.
- This is a beta: please report problems on the Issues page.

---

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
