# 📁 RecodeX - File Combiner & Reverse Split Utility

![License](https://img.shields.io/badge/license-MIT-green.svg)
![Status](https://img.shields.io/badge/status-active-success.svg)
![Frontend](https://img.shields.io/badge/frontend-vanilla%20JS-blue.svg)
![Tailwind](https://img.shields.io/badge/styled%20with-tailwindcss-38B2AC.svg)
![JSZip](https://img.shields.io/badge/zip-jszip-orange.svg)

A powerful **100% browser-based developer utility** to combine multiple text/code files into a single structured file and reverse it back into original files when needed.

No backend. No uploads. Everything runs locally in your browser.

---

## 🚀 Live Features

### 📦 File Combination
- Drag & drop or select multiple files
- Supports: `.js, .vue, .html, .css, .json, .ts, .tsx, .jsx, .md, .txt`
- Generates a structured compiled output with file markers

### 🔄 Reverse Split Engine
- Upload compiled file and reconstruct original files
- Automatic parsing using start/end markers
- Download files individually or as ZIP

### 🔍 Smart File Viewer
- Modal-based preview system
- Search with highlighted matches
- Copy-to-clipboard support
- Keyboard-friendly UI

### 📥 Export System
- Download compiled file
- Export full package as ZIP (original + compiled)
- Export extracted files as ZIP

---

## 🖼️ Screenshots

> Replace these paths with actual screenshots in your repo (`/screenshots` folder recommended)

### 📌 Main Interface
![Main UI](./screenshots/01-main.png)

### 📂 File Upload & List View
![File List](./screenshots/02-uploadfiles.png)

### 🧠 Compiled Output Viewer
![Compiled Viewer](./screenshots/03-compile-view.png)

### 🔎 Download All Files Into a Single Text File
![Search Highlight](./screenshots/04-download-compiled.png)

### 🔄 Reverse Split File Upload
![Reverse Split](./screenshots/05-upload-compiledfile-to-split-original-files.png)

### 🔄 Reverse Split Output
![Reverse Split](./screenshots/06-split-download-zip.png)

---

## 🧠 How It Works

Each file is wrapped using structured markers:

```txt
/* --- Start of file: example.js --- */
...file content...
/* --- End of file: example.js --- */

The reverse engine parses these markers and reconstructs original files with full accuracy.

🛠️ Tech Stack
HTML5
Tailwind CSS (CDN)
Vanilla JavaScript (ES6+)
JSZip (ZIP generation)

📂 Project Use Cases
🔧 Developer file bundling tool
📦 Code sharing in a single file
🗂️ Backup & restore file sets
🧪 Learning client-side parsing logic
⚡ Offline developer utility tool

⚠️ Limitations
❌ Binary files not supported
❌ Requires correct marker format for reverse split
❌ No syntax highlighting (optional enhancement)

📦 Installation
No installation required.

Simply open:
index.html

or run using any local server:
npx serve .

📸 Suggested Folder Structure
project-root/
│── index.html
│── /screenshots
│     ├── main-ui.png
│     ├── file-list.png
│     ├── compiled-viewer.png
│     ├── search.png
│     ├── reverse-split.png

📈 Future Improvements
Syntax highlighting (Monaco / Prism.js)
File tree view UI
Drag reorder before compile
Partial file extraction mode
Export as project folder structure ZIP

👨‍💻 Author
zKamali

📄 License
&nbsp;
---

If you want next level upgrade, I can also:
- Convert this into a **landing-page style README (Apple-level UI presentation)**
- Or turn it into a **React + backend SaaS version with authentication + cloud storage*
