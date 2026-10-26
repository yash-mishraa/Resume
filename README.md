# Yash Mishra — Resume

Live deployment of Yash Mishra's resume with high-fidelity rendering, interactive hyperlinks, zoom controls, download, and print capabilities.

🔗 **Live Link:** [https://yash-mishraa.github.io/Resume/](https://yash-mishraa.github.io/Resume/)  
📄 **Direct PDF Link:** [https://yash-mishraa.github.io/Resume/Yash_Mishra_Resume.pdf](https://yash-mishraa.github.io/Resume/Yash_Mishra_Resume.pdf)

---

## ✨ Features

- **100% Visual Fidelity:** Powered by Mozilla PDF.js vector canvas rendering, ensuring the PDF renders identically across all devices and browsers without missing fonts or formatting glitches.
- **Interactive Hyperlinks:** All external links (GitHub repos, Hugging Face spaces, LinkedIn, published papers, live demo links) are interactive and open directly in a new tab.
- **Selectable & Searchable Text:** Full text layer enabled — recruiters can copy text and search with <kbd>Ctrl</kbd>/<kbd>Cmd</kbd> + <kbd>F</kbd>.
- **High-DPI / Retina Ready:** Crisp rendering on 2x/3x Retina screens and 4K displays.
- **One-Click Actions:**
  - 📥 **Download PDF:** Instantly downloads the original `Yash_Mishra_Resume.pdf`.
  - 🖨️ **Print:** Dedicated print mode stripped of toolbars for exact page-by-page printing.
  - ↗️ **Open Raw:** Direct link to native PDF stream.
- **Zero External Downtime Risk:** All viewer libraries (`pdf.js`, `pdf.worker.js`, and `cmaps`) are bundled locally within the repository — no reliance on external CDNs.
- **Global High Availability:** Hosted on GitHub Pages backed by global Fastly CDN edge caching (free, 99.99%+ uptime).

---

## 🚀 Updating Your Resume

Whenever you want to update your resume in the future:
1. Replace `Yash_Mishra_Resume.pdf` (and `resume.pdf`) with your new PDF file.
2. Commit and push to `main`:
   ```bash
   git add Yash_Mishra_Resume.pdf resume.pdf
   git commit -m "Update resume PDF"
   git push origin main
   ```
GitHub Pages will automatically serve the updated version within a few seconds!
