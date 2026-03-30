# 📇 CardScan — 100% Free Visiting Card Scanner

Scan visiting cards → auto-extract contacts → export to Excel.  
**Zero cost. No API key. No account. No payment. Ever.**

---

## ✨ How it works

| Step | What happens | Technology |
|------|-------------|------------|
| 📷 Tap Scan | Take photo or pick from gallery | Browser File API |
| 🔍 Extract Info | OCR reads text from card | **Tesseract.js** (runs in browser) |
| ✏️ Review | Edit any field before saving | — |
| 📊 Export | Downloads `.xlsx` file | **SheetJS** (runs in browser) |

Everything happens **on your device**. No data is uploaded anywhere.

---

## 🚀 Deploy FREE on GitHub Pages (5 minutes)

### 1. Create a GitHub account
→ [github.com/signup](https://github.com/signup) — free

### 2. Create a new repository
- Click **+** → **New repository**
- Name: `cardscan`
- Visibility: **Public**
- Click **Create repository**

### 3. Upload the files
On the empty repo page, click **"uploading an existing file"**  
Drag and drop:
- `index.html`
- `manifest.json`

Click **Commit changes**

### 4. Enable GitHub Pages
- Go to repo → **Settings** → **Pages** (left sidebar)
- Source: **Deploy from a branch**
- Branch: **main** / folder: **/ (root)**
- Click **Save**

### 5. Open your app
After ~1 minute, your app is live at:
```
https://YOUR_USERNAME.github.io/cardscan/
```

---

## 📱 Install as App on Phone (PWA)

**iPhone/iPad — Safari:**
1. Open your app URL in Safari
2. Tap the **Share** button (□↑)
3. Tap **"Add to Home Screen"**

**Android — Chrome:**
1. Open your app URL in Chrome
2. Tap ⋮ menu → **"Add to Home Screen"**

---

## 💡 Tips for Best OCR Results

- 📸 Use **good lighting** — avoid shadows on the card
- 🔲 Keep card **flat and straight** in frame
- 🔍 Fill the camera frame with the card
- ✏️ Always **review the extracted fields** — OCR can make mistakes on stylized fonts
- The first scan takes ~10 sec to load the OCR engine (downloads once, then cached)

---

## 💰 Cost Breakdown

| Item | Cost |
|------|------|
| GitHub Pages hosting | **Free** |
| Tesseract.js OCR | **Free** (open source, MIT) |
| SheetJS Excel export | **Free** (open source) |
| Google Fonts | **Free** |
| **Total** | **₹0 / $0 forever** |

---

## 🛠 Tech Stack
- **Tesseract.js v5** — OCR engine compiled to WebAssembly, runs in-browser
- **SheetJS (xlsx.js)** — generates `.xlsx` files client-side
- **Vanilla HTML/CSS/JS** — no framework, no build step
- **PWA** — installable, works offline after first load

---

MIT License — free to use, modify, and share.
