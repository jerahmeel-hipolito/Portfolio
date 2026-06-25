# Jerahmeel Hipolito — Portfolio

**Instructional Designer · Statistician**  
Magna Cum Laude, BS Mathematics (Applied Statistics) · Bulacan State University, 2025  
MS Statistics (Ongoing) · University of the Philippines Diliman, 2026–Present

> Live site: [jerahmeel-hipolito.github.io/Portfolio](https://jerahmeel-hipolito.github.io/Portfolio)

---

## About This Repository

This repository hosts my personal portfolio website, sample instructional design coursework, and undergraduate research paper. The portfolio showcases my background in e-learning development, curriculum design, applied statistics, and academic research.

---

## Repository Structure

```
/
├── index.html                              ← Main portfolio page
├── Jerahmeel_Hipolito_CV.pdf               ← Downloadable CV
├── README.md
├── certificates/
│   ├── advancing-ld-professional.pdf
│   ├── build-skills-instructional-designer.pdf
│   ├── analytical-skills-statistical-analysis.pdf
│   ├── complete-guide-r.pdf
│   └── statistics-foundations-wolfram.pdf
│   └── genAI-for-data-analysis-and-data-science.pdf
│   └── advance-your-skills-in-r.pdf
├── courses/
│   ├── intro-to-rise360/                   ← Introduction to Articulate Rise 360
│   │   └── index.html
│   ├── what-is-gamification/               ← What is Gamification?
│   │   └── index.html
│   ├── html-css-js-basics/                 ← HTML, CSS, and JavaScript Basics
│   │   └── index.html
│   └── navigation-tutorial-rise360/        ← Navigation Tutorial on Rise 360
│       └── index.html
└── research/
    └── GenAI_Usage_Paper.pdf               ← Undergraduate thesis (IMRAD format)
```

---

## Portfolio Sections

| # | Section | Description |
|---|---------|-------------|
| 01 | About | Background, bio, and key stats |
| 02 | Skills | 10 core competencies + tools & platforms |
| 03 | Experience | Work history and conference presentations |
| 04 | Sample Coursework | 4 Rise 360 e-learning course demos |
| 05 | Education & Honors | Academic background and awards |
| 06 | Research | Undergraduate thesis and published study |
| 07 | Certificates | 5 LinkedIn Learning professional certificates |
| 08 | Contact | Email, GitHub, LinkedIn |

---

## Sample Courses

Each course was built with **Articulate Rise 360** and exported as HTML5. They are hosted as standalone folders and launch directly in the browser.

| # | Course | Content Type | Level |
|---|--------|-------------|-------|
| 01 | [Introduction to Articulate Rise 360](./courses/intro-to-rise360/) | Tool Proficiency | Beginner |
| 02 | [What is Gamification?](./courses/what-is-gamification/) | Instructional Strategy | Intermediate |
| 03 | [HTML, CSS, and JavaScript Basics](./courses/html-css-js-basics/) | Technical Content | Beginner |
| 04 | [Navigation Tutorial on Rise 360](./courses/navigation-tutorial-rise360/) | Learner Onboarding | Beginner |

---

## LinkedIn Learning Certificates

All 5 certificates are stored as PDFs in the `/certificates/` folder and linked from the portfolio's Certificates section.

| # | Certificate | Duration | File |
|---|-------------|----------|------|
| 01 | Advancing Your Skills as an L&D Professional | 5 hr 20 min | `advancing-ld-professional.pdf` |
| 02 | Build Your Skills as an Instructional Designer | 7 hr 43 min | `build-skills-instructional-designer.pdf` |
| 03 | Build Your Analytical Skills with Statistical Analysis | 5 hr 10 min | `analytical-skills-statistical-analysis.pdf` |
| 04 | Complete Guide to R: Wrangling, Visualizing, and Modeling Data | 8 hr 15 min | `complete-guide-r.pdf` |
| 05 | Statistics Foundations Professional Certificate — Wolfram Research | 13 hr 50 min | `statistics-foundations-wolfram.pdf` |
| 06 | Complete Guide to Generative AI for Data Analysis and Data Science | 10 hr 21 min | `genAI-for-data-analysis-and-data-science.pdf` |
| 07 | Advance Your Skills in R | 26 hr 6 min | `advance-your-skills-in-r.pdf` |

**Total: 76 hours 45 minutes of continuing education**

---

## Undergraduate Research

**Zero-Inflated Beta, Tobit, and Latent Growth Mixture Models for Analyzing GenAI Usage Trends and Trajectories**

*Jerahmeel S. Hipolito, Angeli D. Bergonio, Carina Jean A. Damasco, Lance Aron O. Javier, Dr. Marco C. Mandap*  
Bulacan State University — College of Science, 2025  
Presented at the **16th National Convention on Statistics**, Philippine Statistics Authority

- Analyzed 6,343 research papers from BulSU (2013–2023)
- Detected 262 AI-flagged papers using Quillbot Premium
- Applied Zero-Inflated Beta, Tobit, and LGMM models
- Awarded **Best Thesis 2025**, College of Science, Bulacan State University

The full paper is available as a PDF at [`./research/GenAI_Usage_Paper.pdf`](./research/GenAI_Usage_Paper.pdf).

---

## How to Upload Course Folders

For each Rise 360 course:

1. Export from Rise 360 → **Export for Web** → download the ZIP
2. Unzip the file
3. Rename the extracted folder to match the names above (e.g., `intro-to-rise360`)
4. Place the folder inside `/courses/` in this repository
5. Commit and push — GitHub Pages will serve it automatically

> **Note:** Rise 360 HTML5 exports contain an `index.html` at the root of each folder. GitHub Pages serves this automatically when you visit `https://yourusername.github.io/Portfolio/courses/intro-to-rise360/`.

---

## How to Add the Research Paper

1. Export or save your thesis as a PDF
2. Rename the file to `GenAI_Usage_Paper.pdf`
3. Place it inside the `/research/` folder (create the folder if it doesn't exist)
4. Commit and push — the "Read Full Paper" button on the portfolio will link to it automatically

---

## How to Add Certificates

1. Download each certificate PDF from LinkedIn Learning
2. Rename each file to match the filenames listed in the table above
3. Create a `/certificates/` folder in the repository root (if it doesn't exist)
4. Upload all 5 PDFs into `/certificates/`
5. Commit and push — the "View Certificate" links on the portfolio will work automatically

---

## Deploying to GitHub Pages

1. Go to your repository on GitHub
2. Click **Settings** → **Pages** (in the left sidebar)
3. Under **Source**, select `main` branch and `/ (root)` folder
4. Click **Save**
5. Your site will be live at `https://yourusername.github.io/Portfolio` within a few minutes

---

## Tech Stack

- **Portfolio:** Vanilla HTML, CSS, and JavaScript — no frameworks, no build step
- **Font:** [Outfit](https://fonts.google.com/specimen/Outfit) via Google Fonts
- **Courses:** Articulate Rise 360 → HTML5 export
- **Course images:** [Unsplash](https://unsplash.com) (free for commercial use)
- **Hosting:** GitHub Pages

---

## Skills Covered

10 core competencies across instructional design and data science:

E-Learning Development · Curriculum & Course Design · Needs Analysis · Storyboarding · Statistical Analysis · Accessible Content Design · Research & Technical Writing · GenAI in Learning · Data Visualization · Learning Analytics

**Tools & Platforms:** Articulate Rise 360, Articulate Storyline, Thinkific, R, SPSS, Microsoft Office, Google Workspace, Canva, Notion, HTML/CSS/JS, Python

---

## Contact

- **Email:** hipolitojerahmeel12@gmail.com
- **LinkedIn:** [linkedin.com/in/jerahmeel-hipolito-304241369](https://linkedin.com/in/jerahmeel-hipolito-304241369)
- **Facebook:** [wa.me/qr/VHKKI6MWM4P2D1](https://wa.me/qr/VHKKI6MWM4P2D1)

---

*Portfolio designed and built by Jerahmeel Hipolito · 2026*
