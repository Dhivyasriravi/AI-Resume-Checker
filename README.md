# 🎯 AI Resume Analyzer & ATS Checker

> Upload your resume + paste a job description — get an ATS score, keyword gap analysis, strengths/weaknesses, and an AI-rewritten professional summary. 100% free, no backend needed.

**Built by:** Dhivyasri Ravi | CSE Graduate 2026

---

## 🚀 Live Demo
[View Live](https://yourusername.github.io/ai-resume-analyzer)

---

## 📌 About the Project
An intelligent ATS (Applicant Tracking System) resume analyzer that helps job seekers understand how well their resume matches a job description. It scores the resume across 6 dimensions, identifies missing keywords, highlights strengths and weaknesses, and rewrites the professional summary — all powered by a free AI API.

---

## ✨ Features
- 📄 Upload resume as .txt or paste directly
- 💼 Paste any job description to compare against
- 🎯 ATS Score (0–100) with animated donut chart
- 📊 Radar chart breakdown across 6 dimensions
- 🔑 Keyword gap analysis — found vs missing keywords
- 💪 Strengths and weaknesses detection
- 🛠️ Top 5 specific improvement suggestions
- ✨ AI-rewritten professional summary tailored to the JD
- 🆓 100% free — powered by Groq API (no credit card needed)

---

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| HTML5 / CSS3 / JavaScript | Frontend |
| Chart.js | ATS donut + radar chart visualization |
| Groq API (LLaMA 3.3 70B) | AI analysis and insights (free) |

---

## 📊 Score Dimensions

| Dimension | What it measures |
|---|---|
| 🔑 Keywords | How many JD keywords appear in resume |
| 💼 Experience | Relevance of work experience |
| 🛠️ Skills | Technical skills match |
| 🎓 Education | Education qualification match |
| 📋 Formatting | Resume structure and readability |
| ⚡ Impact | Quantified achievements and action verbs |

---

## ⚙️ How to Run

### Step 1 — Get Free Groq API Key
```
1. Go to https://console.groq.com
2. Sign up with Gmail (free, no credit card)
3. Click "API Keys" → "Create API Key"
4. Copy the key (starts with gsk_...)
```

### Step 2 — Add API Key to Code
```javascript
// Open ai_resume_analyzer.html in VS Code
// Find line 251 and replace:
const API_KEY = 'YOUR_GROQ_API_KEY_HERE';
// With your real key:
const API_KEY = 'gsk_yourrealkeyhere';
```

### Step 3 — Run
```
Option A: Open in VS Code → Right-click → Open with Live Server
Option B: Deploy on GitHub Pages (see below)
```

---

## 🌐 Deploy on GitHub Pages (Free Hosting)
```
1. Create GitHub repo: ai-resume-analyzer
2. Upload file → rename to index.html
3. Go to Settings → Pages → select main branch → Save
4. Live at: https://yourusername.github.io/ai-resume-analyzer
```

---

## 📁 Project Structure
```
ai-resume-analyzer/
│
├── index.html        ← Complete project (single file)
└── README.md         ← Documentation
```

---

## 🧠 How It Works
1. User pastes resume text and job description
2. A structured prompt is sent to Groq API (LLaMA 3.3 70B model)
3. AI returns a JSON object with scores, keywords, strengths, improvements
4. Chart.js renders the donut score and radar breakdown charts
5. Results are displayed with keyword pills, feedback lists, and rewritten summary

---

## 💡 Use Cases
- 🎓 Fresh graduates checking resume-JD fit before applying
- 💼 Job seekers optimizing resume for specific roles
- 🔍 Understanding what keywords ATS systems look for
- ✍️ Getting a professionally rewritten summary instantly

---

## 🔮 Future Improvements
- [ ] Support PDF resume upload directly
- [ ] Save and compare multiple resume versions
- [ ] Add industry-specific keyword suggestions
- [ ] Export full analysis report as PDF

---

## 👩‍💻 Author
**Dhivyasri Ravi**
- 📧 dhivyasriravi5@gmail.com
- 🔗 [LinkedIn](https://linkedin.com/in/dhivyasri)
- 💻 [GitHub](https://github.com/dhivyasri)

---

## 📄 License
MIT License — free to use and modify.
