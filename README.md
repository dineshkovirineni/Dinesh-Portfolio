# Dinesh Kovirineni — Portfolio Website

Professional portfolio for Dinesh Kovirineni, AI Software Engineer (Backend & Cloud Engineering). A static site built with plain HTML, CSS and JavaScript: no build step and no dependencies.

**Live site:** [dineshkovirineni.github.io/Dinesh-Portfolio](https://dineshkovirineni.github.io/Dinesh-Portfolio/)

---

## 👤 About

AI Software Engineer with 3+ years of experience building AI-powered applications, Generative AI solutions, scalable backend services and cloud-native systems. Focus areas include LLM applications, RAG, semantic search and vector embeddings, built with Python, FastAPI, Vertex AI, Pinecone, LangChain and GCP.

---

## 🧭 Sections

- **Hero:** Headshot, intro and six stat cards, set over an animated neural network canvas
- **Experience:**
  - **Sam's Club (Walmart)**, Software Engineer, AI & Merchandising (Contract), May 2024 – Present: Catalog AI, Pricing RT and In-Club Checkout Modernization
  - **EPSoft**, Software Engineer, May 2023 – May 2024: Python/FastAPI microservices on AWS, CI/CD, Docker and Kubernetes
- **Projects:**
  - [Text-to-SQL Analytics Agent](https://github.com/dineshkovirineni/Text-to-SQL-Analytics-Agent): A LangGraph agent that turns natural-language questions into validated BigQuery SQL
  - [Automated Document Summarization & Extraction Tool](https://github.com/dineshkovirineni/Automated-Document-Summarization-Extraction-Tool): A RAG pipeline over Pinecone for structured field extraction and summaries
- **Skills:** Languages, AI & ML, backend, databases, and cloud & DevOps
- **Education:**
  - M.S. in Computer Science, George Mason University (May 2023)
  - B.Tech. in Information Technology, Gokaraju Rangaraju Institute of Engineering and Technology (August 2021)
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
- **Stat cards:** Six metrics from Sam's Club and project work animate in one after another on load:

  | Metric | Source |
  |---|---|
  | 600+ club locations migrated | Sam's Club: In-Club Checkout Modernization |
  | 50% pricing latency reduction | Sam's Club: Pricing RT |
  | <100ms POS API query latency | Sam's Club: In-Club Checkout Modernization |
  | 35% GraphQL retrieval efficiency | Sam's Club: In-Club Checkout Modernization |
  | 85% Text-to-SQL first-try success | Text-to-SQL Analytics Agent |
  | 92% RAG field-extraction accuracy | Document Summarization & Extraction Tool |

---

## 📬 Contact

- Email: [dineshkovirineni0924@gmail.com](mailto:dineshkovirineni0924@gmail.com)
- LinkedIn: [dinesh-kovirineni](https://www.linkedin.com/in/dinesh-kovirineni-1a04a4193/)
- GitHub: [@dineshkovirineni](https://github.com/dineshkovirineni)
