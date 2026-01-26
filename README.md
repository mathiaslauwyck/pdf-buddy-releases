# PDF Buddy (Releases)

This repository contains **public release builds** of **PDF Buddy** (Windows `.exe`).
The **source code is kept private** in a separate repository.

PDF Buddy is a small desktop tool to:
- **Merge** multiple PDF files into one
- **Split** a PDF into separate files (page-by-page or custom ranges)
- Use **drag & drop** for quick input

---

## Download (Windows)

1. Open the **Releases** section of this repository.
2. Download the latest **`PDF-Buddy.exe`**
3. Run it (no installation required)

> Tip: You can keep the EXE anywhere, but PDF Buddy may copy itself to a user folder on first run to make updates work smoothly.

---

## Features

### Merge PDFs
- Add PDF files (or a folder)
- Choose **custom order** (drag to reorder) or **alphabetical order**
- Export a single merged PDF

### Split PDFs
- Split **page-by-page**
- Split using **custom ranges** (example: `1-3,5,7-9`)
- Outputs multiple PDF files into a chosen folder

### Drag & Drop
- Drag one or more PDFs onto the merge list
- Drag a single PDF onto the split area
- Drag a folder to automatically add all PDFs inside

---

## Auto-Update

PDF Buddy can check for updates via:
**Help → Check for updates…**

How it works:
- The app checks the **latest GitHub Release tag** (e.g. `v1.0.3`)
- If a newer version exists, it downloads the new **`PDF-Buddy.exe`**
- It restarts and replaces the old EXE automatically

**Important**
- Releases must include a version **tag** like `v1.0.0`, `v1.0.1`, …
- The release asset must be named exactly: **`PDF-Buddy.exe`**

---
## License
PDF Buddy is provided as **freeware**.
Use is free, but redistribution, modification, and resale are not permitted.
See `LICENSE.txt` for details.

---

## Notes / Requirements
- Windows 10/11
- If Windows SmartScreen warns you, click **More info → Run anyway**
  (this is common for unsigned EXE files)

---

## Changelog
See the GitHub **Releases** page for version history and notes.

---

## Disclaimer
This tool is provided “as-is”. Always keep backups of important PDFs.

---

## Contact
Created by **Mathias Lauwyck**  
If you find a bug or want a feature, open an issue or contact the author.
