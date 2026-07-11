# PDFZero

> **Your files never leave your browser. Zero uploads. Zero servers. Zero nonsense.**

[![Made with ❤️](https://img.shields.io/badge/Made%20with-%E2%9D%A4%EF%B8%8F-red.svg)](https://github.com/)
[![No Server](https://img.shields.io/badge/Server-None-brightgreen.svg)]()
[![Privacy First](https://img.shields.io/badge/Privacy-100%25%20Local-blueviolet.svg)]()
[![Works Offline](https://img.shields.io/badge/Works-Offline-success.svg)]()

A full-featured PDF toolkit that lives in a single HTML file. Open it, use it, close it. No installs, no accounts, no data leaving your machine.

---

## What can it do?

### Organize
| Tool | What it does |
|------|-------------|
| Merge PDF | Combine multiple PDFs — drag to reorder, drop to add. |
| Split PDF | Split into single pages or extract a range. |
| Compare PDF | Pick two PDFs and see them side-by-side instantly. |

### Optimize
| Tool | What it does |
|------|-------------|
| Compress PDF | Shrinks files by re-rendering pages as images. Three levels: Smallest / Balanced / Higher Quality. |
| Batch Process | Run compress, rotate, or extract on dozens of files at once. |

### Convert
| Tool | What it does |
|------|-------------|
| PDF to Word | Extracts text into a clean `.doc` file. |
| PDF to Text | Raw text extraction with or without page markers. |
| PDF to Images | Every page as PNG or JPG. Zips multi-page PDFs. |
| Images to PDF | Turn JPG, PNG, WebP, BMP, or GIF into a single PDF. |
| PDF to Excel | Text lines into an `.xls` spreadsheet. |
| PDF to PowerPoint | Pages rendered as slides in a `.pptx` deck. |
| PDF to Markdown | Clean Markdown with smart heading detection. |
| OCR PDF | Reads text from scanned docs (English, Bengali, or both). |

### Edit
| Tool | What it does |
|------|-------------|
| Rotate PDF | Spin pages left or right by 90°, 180°, or 270°. |
| Delete Pages | Remove pages by number or range (`1, 3-5, 8`). |
| Rearrange Pages | Reorder however you like (`3, 1, 2`). |
| Watermark | Diagonal text stamp on every page. |
| Page Numbers | Add numbers anywhere — top, bottom, left, right. |
| Crop PDF | Trim margins by exact amounts. |
| Metadata | Edit title, author, subject, keywords, and more. |
| Fill Forms | Detect and fill text fields, checkboxes, radio buttons, and dropdowns. |

### Security
| Tool | What it does |
|------|-------------|
| Protect PDF | Lock with a user/owner password (standard PDF encryption). |
| Unlock PDF | Strip editable restrictions from readable PDFs. |
| Sign PDF | Draw a signature with mouse or touch and stamp it on any page. |

---

## Why PDFZero?

**No backend.** There is no server. The entire app is a single `index.html` file you can open from your desktop, a USB drive, or a local network share.

**No uploads.** The file you pick never travels over the network. PDF.js renders it, PDF-lib edits it, and the result is downloaded straight to your downloads folder.

**No setup.** Clone it, double-click it, done.

**Works offline.** Once loaded, the Service Worker caches everything. You can disconnect from the internet and keep working.

---

## Tech Stack

| Library | Job |
|---------|-----|
| [PDF.js](https://mozilla.github.io/pdf.js/) | Renders and extracts text from PDFs |
| [PDF-lib](https://pdf-lib.js.org/) | Creates, edits, and encrypts PDFs |
| [JSZip](https://stuk.github.io/jszip/) | Bundles multi-file results into ZIP archives |
| [Tesseract.js](https://tesseract.projectnaptha.com/) | Runs OCR on scanned documents |
| [PptxGenJS](https://gitbrent.github.io/PptxGenJS/) | Generates PowerPoint decks |

---

## One-click start

```bash
git clone https://github.com/your-username/pdfzero.git
cd pdfzero
start index.html     # Windows
open index.html      # macOS
xdg-open index.html  # Linux
```

That's it. No `npm install`, no build step, no Docker.

---

## Privacy Guarantee

**We mean it.** Zero data leaves your browser. Not a single byte of your PDF is sent to any server. No cookies, no tracking, no analytics. What happens in your tab stays in your tab.

---

## Made by

Built by [@Tanim](https://www.linkedin.com/in/ishtiaque2/). Contributions and ideas are always welcome — open an issue or send a PR.

---

<p align="center">
  <sub>MIT License. Use it, fork it, share it.</sub>
</p>
