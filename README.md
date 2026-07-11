# PDFZero

**Zero uploads, zero server cost, zero waiting.**

A free, open-source PDF toolkit that runs entirely in your browser. Your files never leave your device — every operation is performed client-side using PDF.js, PDF-lib, and other browser-native libraries.

## Features

### Organize PDF
- **Merge PDF** — Combine multiple PDFs into one in the order you want
- **Split PDF** — Separate pages into individual files or extract a specific range

### Optimize PDF
- **Compress PDF** — Reduce file size by re-rendering pages as optimized images (Smallest / Balanced / Higher Quality)

### Convert
- **PDF to Word** — Extract text into an editable `.doc` file
- **PDF to Text** — Extract raw text with optional page markers
- **PDF to Images** — Export every page as PNG or JPG (multi-page → ZIP)
- **Images to PDF** — Convert JPG, PNG, WebP, BMP, GIF images into a single PDF with page size and orientation options
- **PDF to Excel** — Extract text lines into a spreadsheet `.xls` workbook
- **PDF to PowerPoint** — Render each page as a slide in a `.pptx` deck
- **OCR PDF** — Recognize text from scanned/image-only PDFs (English, Bengali, or both)

### Edit PDF
- **Rotate PDF** — Rotate all pages 90°, 180°, or 270°
- **Delete Pages** — Remove specific pages by number or range (e.g. `1, 3-5, 8`)
- **Rearrange Pages** — Reorder pages in any sequence (e.g. `3, 1, 2`)
- **Watermark PDF** — Stamp transparent text diagonally across every page

### Security
- **Protect PDF** — Encrypt with AES-256-GCM password protection using browser crypto
- **Unlock PDF** — Remove editable restrictions from readable PDFs

## Tech Stack

| Library | Purpose |
|---------|---------|
| [PDF.js](https://mozilla.github.io/pdf.js/) | PDF rendering and text extraction |
| [PDF-lib](https://pdf-lib.js.org/) | PDF creation, editing, and manipulation |
| [JSZip](https://stuk.github.io/jszip/) | ZIP file generation for multi-file outputs |
| [Tesseract.js](https://tesseract.projectnaptha.com/) | Client-side OCR |
| [PptxGenJS](https://gitbrent.github.io/PptxGenJS/) | PowerPoint file generation |

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/pdfzero.git
   ```
2. Open `index.html` in any modern browser — no build step, no server required.

## Privacy

All processing happens in your browser. No files are uploaded to any server. No data is collected. Your documents stay on your machine.

## Upcoming Features

- [ ] **PDF to Markdown** — Convert PDF content to Markdown format
- [ ] **PDF Forms** — Fill out interactive PDF form fields
- [ ] **Page Numbers** — Add customizable page numbers to every page
- [ ] **Crop PDF** — Trim margins and crop pages to custom dimensions
- [ ] **Compare PDF** — Side-by-side diff of two PDF documents
- [ ] **Digital Signatures** — Sign PDFs with a drawn or typed signature
- [ ] **Redact PDF** — Black out sensitive text and images permanently
- [ ] **PDF Metadata Editor** — View and edit title, author, and other properties
- [ ] **Batch Processing** — Apply the same operation to multiple files at once
- [ ] **Dark Mode Improvements** — Enhanced contrast and accessibility in dark theme
- [ ] **Mobile Optimization** — Touch-friendly UI and offline support via Service Worker
- [ ] **Drag & Drop Reordering** — Sort merge files with drag-and-drop

## Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request.

## Credits

Built by [@Tanim](https://www.linkedin.com/in/ishtiaque2/)
