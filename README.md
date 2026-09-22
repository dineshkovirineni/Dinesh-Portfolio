# Dinesh Kovirineni — Portfolio Website

Professional portfolio for Dinesh Kovirineni, AI Software Engineer. A static site built with plain HTML, CSS and JavaScript: no build step and no dependencies.

---

## 🧭 Sections

- **Hero:** Headshot, intro and six production metrics, set over an animated neural network canvas
- **Experience:** Roles at JPMC and Sam's Club
- **Projects:** Includes the [Text-to-SQL Analytics Agent](https://github.com/dineshkovirineni/Text-to-SQL-Analytics-Agent) and the [Automated Document Summarization & Extraction Tool](https://github.com/dineshkovirineni/Automated-Document-Summarization-Extraction-Tool)
- **Skills**
- **Education**
- **Contact:** Email, LinkedIn, GitHub and a resume download

---

## 📁 Folder Structure

```
Dinesh-Portfolio/
├── index.html                          ← Main portfolio (photo embedded as base64)
├── assets/
│   ├── css/style.css                   ← All styles
│   ├── js/main.js                      ← Neural canvas, animations, nav
│   ├── images/
│   │   └── profile.jpg                 ← Headshot (also embedded in HTML)
│   └── resume/
│       └── Dinesh_Kovirineni_Resume.pdf ← Linked from the site's resume button
└── README.md
```

---

## 🚀 Running Locally

Open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

To update the resume, replace `assets/resume/Dinesh_Kovirineni_Resume.pdf` and keep the same filename.

---

## ✅ Publishing Checklist

| Item | Status |
|---|---|
| Profile photo | ✓ Embedded directly in `index.html` (base64) |
| Resume PDF | ✓ Added at `assets/resume/Dinesh_Kovirineni_Resume.pdf` |

---

## 🎨 Design Notes

- **Palette:** Deep violet-black · Vivid violet (#7C3AED) · Electric lime (#A3E635)
- **Typography:** Space Grotesk (headings), Inter (body) and Fira Code (code accents), loaded from Google Fonts
- **Signature element:** An animated neural network canvas in the hero. Violet and lime nodes connect and pulse, a nod to Dinesh's RAG and vector embedding work
- **Photo ring:** A conic gradient (violet → lime → violet) spins around the headshot
- **Stat cards:** Six production metrics from JPMC, Sam's Club and project work animate in one after another on load

---

## 📬 Contact

- Email: [dineshkovirineni0924@gmail.com](mailto:dineshkovirineni0924@gmail.com)
- LinkedIn: [dinesh-kovirineni](https://www.linkedin.com/in/dinesh-kovirineni-1a04a4193/)
- GitHub: [@dineshkovirineni](https://github.com/dineshkovirineni)
