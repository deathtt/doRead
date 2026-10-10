# doRead ✦

**Tasks · File editor · Portfolio** — one beautiful local-first page.

Live demo (after GitHub Pages is enabled):  
**https://deathtt.github.io/doRead/**

---

## Features

### ✅ Tasks
- Inbox → Now → Next → Someday lists
- Habits with weekly dots + time
- Turn any image into 1-bit black & white sticker
- Max 15 items, export as text, reset anytime
- Fully offline (localStorage)

### 📄 Files
Open, edit and re-save almost anything:
- **Read**: PDF, Word (.docx), Excel/CSV, Markdown, HTML, JSON, code, plain text…
- **Edit** with live preview (Markdown & HTML)
- **Save as**: MD, TXT, HTML, JSON, CSV, SVG, PDF, Word, Excel, EPUB, ZIP, PNG, JPG, WebP

Drag & drop or pick a file. Everything stays in your browser.

### 🎨 Portfolio
- Fill name, role, about, contacts
- Add photo + sticker / mono style
- Save up to 6 cards in your showcase
- Download as a ready-to-share HTML page

---

## How to use (local)

Just open `index.html` in any modern browser.  
No build step, no server required for basic use.

For the live version on GitHub Pages:
1. Go to the repository **Settings → Pages**
2. Source: **Deploy from a branch**
3. Branch: `main` / folder `/ (root)`
4. Save → wait ~30–60 seconds
5. Visit `https://deathtt.github.io/doRead/`

---

## Technical notes

- Pure static HTML + CSS + vanilla JS
- Libraries loaded from CDN (pdf.js, mammoth, SheetJS, jsPDF, JSZip, marked, DOMPurify)
- All data stays on-device (localStorage)
- Download works with the normal browser download dialog
- Optimized text extraction for PDF / Word / spreadsheets
- Dark / light theme follows system or manual toggle

---

## License

MIT — do whatever you want with it.
