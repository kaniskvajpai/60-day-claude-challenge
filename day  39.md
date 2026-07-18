# Day 39 – PDF Splitter & Merger 📄✂️➕

## 60 Day Claude AI Challenge

### Objective

Built a browser-based **PDF Splitter & Merger** application using Claude AI. The application enables users to split PDF files into selected page ranges, merge multiple PDFs into one document, preview pages before processing, and download the processed PDFs—all locally in the browser without uploading files.

---

# Deliverables

## ✅ Generated HTML Application

**File Included**

- `pdf_splitter_merger.html`

---

# Features

### PDF Splitter

- Upload PDF files
- Preview document pages
- Split by page range
- Split individual pages
- Download generated PDFs
- Preserve original quality

### PDF Merger

- Upload multiple PDF files
- Rearrange file order
- Merge into a single PDF
- Preview merged output
- Download merged PDF

### Additional Features

- Drag-and-drop file upload
- Progress indicators
- Responsive UI
- Dark & Light theme
- Client-side processing
- Fast PDF rendering
- Error handling
- No server required

---

# Processed PDF Examples

### Example 1

Original:
- 15 Pages

Output:
- Pages 1–5

---

### Example 2

Original:
- Pages 6–10

Output:
- New PDF generated

---

### Example 3

Merged PDFs

Input:
- report.pdf
- assignment.pdf
- notes.pdf

Output:
- merged_document.pdf

---

# Key Learnings

- Learned how browser-based PDF manipulation works.
- Understood page extraction and PDF merging logic.
- Explored client-side document processing.
- Improved JavaScript file handling skills.
- Learned how PDF preview rendering works.
- Implemented drag-and-drop uploads.
- Understood Blob downloads.
- Enhanced UI responsiveness.
- Improved error handling for invalid PDFs.
- Built a complete utility application without any backend.

---

# Technologies Used

- Claude AI
- HTML5
- CSS3
- JavaScript (ES6)
- PDF.js
- PDF-Lib
- Browser File APIs

---

# Folder Structure

Day39/

├── pdf_splitter_merger.html

├── day39.md

├── processed_pdfs/

│   ├── split_example.pdf

│   ├── merged_example.pdf

│   └── extracted_pages.pdf

└── screenshots/

    ├── home.png

    ├── pdf_splitter.png

    ├── pdf_merger.png

    ├── preview.png

    └── download_result.png

---

# Reflection

Building this application demonstrated the power of browser-based document processing. The project showed that advanced PDF operations such as splitting, merging, previewing, and downloading can be performed entirely on the client side, ensuring faster performance and improved privacy since files never leave the user's device.

---

**#60DayClaudeChallenge**
