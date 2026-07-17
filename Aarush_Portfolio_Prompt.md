# PORTFOLIO WEBSITE — AARUSH WALI
## Complete Content & Build Prompt for Antigravity + Claude

---

## 🎯 WHAT TO BUILD

Build a **stunning, modern, single-page portfolio website** for Aarush Wali — a final-year B.Tech (CSE AI/ML) student and software engineer. The site should feel like a **premium developer portfolio** — dark theme, sleek animations, glassmorphism cards, smooth scroll, and fully responsive.

---

## 🎨 DESIGN DIRECTION

- **Theme:** Dark (background: #0A0F1E), with electric blue (#2563EB) as primary accent
- **Style:** Glassmorphism cards, subtle gradients, smooth entrance animations, floating particles or grid background on hero
- **Font:** Inter or Geist for body, space grader or similar for name/headings
- **Feel:** Senior engineer at a top tech company — not a student template
- **Sections order:** Hero → About → Experience → Projects → Publications → Skills → Education & Certifications → Contact
- **Nav:** Sticky top navbar with smooth scroll links + mobile hamburger menu
- **Animations:** Fade-in on scroll (Intersection Observer), typed text effect on hero subtitle, hover effects on cards

---

## 👤 PERSONAL INFO

- **Name:** Aarush Wali
- **Location:** Jammu, J&K, India
- **Email:** work.aarushwali@gmail.com
- **Phone:** +91 70067 49768
- **LinkedIn:** https://www.linkedin.com/in/aarush-wali-a93b60249
- **GitHub:** https://github.com/AARUSH-WALI

---

## 🦸 HERO SECTION

**Headline:** `Aarush Wali`
**Typed/animated subtitle** (cycle through these):
- `AI/ML Engineer`
- `Full-Stack Developer`
- `Cloud & MLOps Engineer`
- `Open Source Builder`

**Tagline (static below subtitle):**
> Building production AI systems, full-stack products, and cloud infrastructure — end to end.

**CTA Buttons:**
- Primary: `View My Work` → scrolls to Projects
- Secondary: `Download Resume` → links to resume PDF (placeholder: `/resume.pdf`)
- Icon links: GitHub icon → https://github.com/AARUSH-WALI | LinkedIn icon → https://www.linkedin.com/in/aarush-wali-a93b60249 | Email icon → mailto:work.aarushwali@gmail.com

---

## 🧑 ABOUT SECTION

**Section title:** About Me

**Content:**
> I'm a final-year B.Tech student in Computer Science (AI/ML) at MIET Jammu, graduating in 2026 with a CGPA of 8.8/10. I design and ship technology solutions end-to-end — from React/Next.js frontends and Node.js backends to Python ML pipelines, GCP cloud infrastructure, and MLOps automation.
>
> I've contributed to a **patented AI system** (People.ai), published **two peer-reviewed research papers** (IEEE & Taylor & Francis), and built a live AI-powered product (EditoDoc) used by real users.
>
> I'm at my best when I'm working across the full stack — owning a problem from architecture to deployment, and making things that actually work in production.

**Stats row (display as highlight cards):**
- 🏢 2 Internships
- 📄 2 Research Papers
- 🚀 Live AI Product
- ☁️ GCP + AWS
- 🎓 CGPA: 8.8/10

---

## 💼 EXPERIENCE SECTION

**Section title:** Experience

### Job 1
- **Role:** Software Engineer Intern (AI/ML, Full-Stack & Cloud)
- **Company:** Straatix Partners Labs Pvt. Ltd.
- **Duration:** Jan 2026 – Present
- **Type:** Remote
- **Stack badge tags:** React · Next.js · TypeScript · Node.js · Python · GCP Vertex AI · Terraform · Supabase · PostgreSQL · Docker · GitHub Actions
- **Bullets:**
  - Deployed and monitored production ML pipelines on **GCP Vertex AI**, integrating AI models into scalable cloud infrastructure using Cloud Run and GKE
  - Built **MLOps-ready CI/CD pipelines** via GitHub Actions and GCP Workload Identity Federation, automating model deployment and eliminating long-lived credentials
  - Architected the full **Supabase/PostgreSQL backend** — schema design, RBAC, SSO, and email-verification workflows — powering dual HR and candidate-facing portals
  - Authored **serverless TypeScript edge functions** for automated referral-email and data pipelines handling production traffic
  - Provisioned **Terraform IaC** with strict IAM roles, security policies, and observability for repeatable, zero-downtime deployments
  - Built dual **React/Next.js portals** with real-time notifications, interactive scheduling tiles, and role-based dashboards

---

### Job 2
- **Role:** Director's Internship — Applied AI
- **Company:** MIET, Jammu
- **Duration:** Feb 2025 – Jan 2026
- **Type:** On-site
- **Stack badge tags:** Python · Scikit-learn · Random Forest · Feature Engineering · Supabase · PostgreSQL · REST APIs · RBAC
- **Bullets:**
  - Core ML engineer for **People.ai** — a **patented AI recruitment system** — building candidate profile parsers, Big Five personality trait feature integration, and predictive fitment/retention scoring models
  - Trained and validated **multi-class fitment and binary retention-prediction classifiers** using 5-fold cross-validation and ROC-based threshold tuning
  - Performed complete **data preprocessing pipeline**: cleaning, feature engineering, and structuring candidate data for model ingestion
  - Designed the **prediction-serving REST API** (Supabase + PostgreSQL, RBAC) and peer-comparison scoring model reducing manual evaluation time by **60%**

---

## 🚀 PROJECTS SECTION

**Section title:** Projects

### Project 1 — EditoDoc
- **Name:** EditoDoc — Privacy-First AI Document & Photo Processor
- **Live Demo:** https://editodoc.vercel.app/
- **GitHub:** https://github.com/AARUSH-WALI
- **Year:** 2025
- **Status badge:** 🟢 Live in Production
- **Stack badge tags:** React · Vite · TypeScript · Hugging Face Transformers.js · WebAssembly · HTML5 Canvas · pdf-lib · pdfjs-dist · Vercel
- **Short description (card):**
  > A 100% client-side, zero-backend AI application — neural network inference, PDF processing, and image manipulation run entirely in-browser. No server, no data ever leaves your device.
- **Full description (expanded/modal):**
  - Engineered a **100% client-side, zero-backend architecture** — all AI inference, PDF processing, and image manipulation runs in-browser via WebAssembly
  - Integrated **Hugging Face Transformers.js** to run a 13 MB neural network (MODNet) directly in-browser for **instant AI background removal** with zero server API calls
  - Built a **canvas-based PDF engine** (pdfjs-dist + pdf-lib) hitting exact KB/pixel constraints for UPSC, SSC, NEET, and JEE exam portals
  - Implemented **iterative compression algorithm** and batch processing of 50+ high-resolution images with custom React hook for automatic Blob garbage collection
  - Guarantees **full data privacy** — eliminates all server compute and storage costs entirely

---

### Project 2 — Thyroid Disease Detection System
- **Name:** Thyroid Disease Detection System
- **GitHub:** https://github.com/AARUSH-WALI
- **Year:** 2024
- **Status badge:** ⚙️ Research Project
- **Stack badge tags:** Python · Scikit-learn · Pandas · NumPy · EDA · Feature Engineering · Model Benchmarking
- **Short description (card):**
  > ML classification system detecting thyroid disorders — benchmarked Logistic Regression, SVM, and Random Forest achieving 95% accuracy.
- **Full description (expanded/modal):**
  - Trained and benchmarked **Logistic Regression, SVM, and Random Forest** models on clinical thyroid data
  - Achieved **95% classification accuracy** through thorough EDA, data cleaning, and feature engineering
  - Conducted performance benchmarking across algorithms using precision, recall, F1-score, and ROC-AUC
  - Complete pipeline: data ingestion → cleaning → EDA → feature engineering → model training → evaluation

---

### Project 3 — People.ai (Patented AI System)
- **Name:** People.ai — AI Recruitment Intelligence System
- **GitHub:** https://github.com/AARUSH-WALI
- **Year:** 2025
- **Status badge:** 🔒 Patented
- **Stack badge tags:** Python · Scikit-learn · Random Forest · Supabase · PostgreSQL · REST APIs · Feature Engineering · Cross-Validation
- **Short description (card):**
  > Patented AI system for faculty recruitment — predicts candidate fitment and retention scores using ML, reducing manual evaluation time by 60%.
- **Full description:**
  - Contributor to a **patented AI recruitment system** processing candidate profiles to produce predictive fitment and retention scores
  - Engineered the core ML pipeline: data parsing, **Big Five trait integration**, multi-class fitment and binary retention-prediction models
  - Validated using **5-fold cross-validation and ROC-based threshold tuning**
  - Designed **prediction-serving architecture** (Supabase + REST APIs, RBAC) reducing manual evaluation time by **60%**

---

## 📄 PUBLICATIONS SECTION

**Section title:** Research & Publications

### Paper 1
- **Title:** Diabetes Detection and Prediction Using the Machine Learning Paradigm
- **Publisher:** IEEE (ieeexplore.ieee.org)
- **Link:** https://ieeexplore.ieee.org/document/11011335
- **Year:** 2025
- **Badge:** IEEE
- **Description:**
  > Benchmarked seven classification algorithms on clinical diabetes data. Random Forest delivered the best F1-score and recall, balancing accuracy with minimized false negatives for healthcare use.
- **Key highlight:** 7 ML algorithms benchmarked · Random Forest winner · Healthcare focus · F1 + Recall optimized

---

### Paper 2
- **Title:** Evaluating the Accuracy and Computational Load of Booth's Algorithm and Vedic Multiplication in Digital Systems
- **Publisher:** Taylor & Francis
- **Link:** https://www.taylorfrancis.com/chapters/edit/10.1201/9781003637530-29/evaluating-accuracy-computational-load-booth-algorithm-vedic-multiplication-digital-systems-veena-tripathi-saksham-gupta-aarush-wali-archit-bali-aradhika-gandotra-ayushman-vohra
- **Year:** 2024
- **Badge:** Taylor & Francis
- **Description:**
  > Analyzed Booth's and Vedic multiplication algorithms, defining optimal hardware contexts — signed-number handling versus speed and simplicity — for digital systems design.
- **Key highlight:** Algorithm benchmarking · Hardware optimization · Digital systems

---

## 🛠 SKILLS SECTION

**Section title:** Technical Skills

Display as animated skill bars or grouped tag clouds:

### Languages
Python · JavaScript · TypeScript · Java · C++ · SQL · HTML · CSS

### Frontend
React · Next.js · WebAssembly · Hugging Face Transformers.js · HTML5 Canvas · Vite

### Backend & APIs
Node.js · REST APIs · Serverless Edge Functions · Supabase · PostgreSQL · MySQL · RBAC · JWT

### AI / ML
TensorFlow · Scikit-learn · PyTorch (familiar) · Pandas · NumPy · Feature Engineering · Model Evaluation · MLOps · LLMs · Prompt Engineering · RAG

### Cloud & DevOps
GCP (Vertex AI · Cloud Run · GKE) · AWS · Vercel · Terraform · Docker · CI/CD · GitHub Actions · GCP Workload Identity Federation

### Tools & Concepts
Git · VS Code · Docker · DSA · OOP · DBMS · OS · System Design · REST API Design · IAM

---

## 🎓 EDUCATION & CERTIFICATIONS SECTION

**Section title:** Education & Certifications

### Education
- **Degree:** B.Tech, Computer Science Engineering (AI/ML)
- **Institution:** Model Institute of Engineering and Technology, Jammu
- **Duration:** 2022 – 2026
- **CGPA:** 8.8 / 10

### Certifications (all clickable, open links in new tab)
1. **Neural Networks & Deep Learning** → https://drive.google.com/file/d/1_QgY5e2FAHoXl_AMSCNIOs6VAk6CnlbG/view?usp=sharing
2. **Feature Engineering** → https://drive.google.com/file/d/13kaCshGn_y4g95_NV66f6LFmv2Eh56uY/view?usp=sharing
3. **TensorFlow on GCP** → https://drive.google.com/file/d/11PHuE5vRxgcF_H3xmzruTLbQw2O_rung/view?usp=sharing
4. **AI Chatbots (No-Code)** → https://drive.google.com/file/d/1mwK7q2IxH0XXe37HIKp9Puv_NaPQjp5E/view?usp=sharing

---

## 📬 CONTACT SECTION

**Section title:** Let's Build Something

**Tagline:**
> Open to internships, remote roles, and collaboration. Reach out anytime.

**Contact methods (display as cards with icons):**
- 📧 Email: work.aarushwali@gmail.com → mailto:work.aarushwali@gmail.com
- 💼 LinkedIn: linkedin.com/in/aarush-wali-a93b60249 → https://www.linkedin.com/in/aarush-wali-a93b60249
- 🐙 GitHub: github.com/AARUSH-WALI → https://github.com/AARUSH-WALI

**Optional contact form fields:** Name · Email · Message · Send button

---

## ⚙️ TECHNICAL REQUIREMENTS

- **Stack:** Single HTML file (vanilla JS + CSS) OR React/Next.js — whichever Antigravity supports best
- **Responsive:** Mobile-first, works on 320px → 4K
- **Performance:** Lazy load images, minimal dependencies
- **Animations:**
  - Hero: typed text effect cycling through roles
  - Sections: fade-in + slide-up on scroll (Intersection Observer)
  - Cards: hover lift + glow effect
  - Skills: animated progress bars or tag cloud
- **Nav:** Sticky with active section highlighting
- **Dark mode only** (no toggle needed)
- **All external links** open in new tab (`target="_blank" rel="noopener"`)
- **Smooth scroll** between sections

---

## 🎨 COLOR PALETTE

```
Background:     #0A0F1E  (deep navy)
Surface/Card:   #111827  (dark card)
Card border:    rgba(255,255,255,0.08)  (glassmorphism)
Primary accent: #2563EB  (electric blue)
Accent glow:    #3B82F6
Text primary:   #F9FAFB
Text secondary: #9CA3AF
Success green:  #10B981  (for "Live" badges)
Warning amber:  #F59E0B  (for "Patented" badges)
```

---

## 📝 FOOTER

> © 2026 Aarush Wali · Built with passion · work.aarushwali@gmail.com

Social icons: GitHub · LinkedIn · Email

---

## ✅ CHECKLIST FOR ANTIGRAVITY

Build the portfolio with ALL of the following:
- [x] Sticky nav with smooth scroll
- [x] Hero with typed animation and CTA buttons
- [x] About with stats cards
- [x] Experience timeline with stack tags and bullet points
- [x] Projects section with 3 project cards (all links clickable)
- [x] Publications section with IEEE + Taylor & Francis badges
- [x] Skills section with grouped tags
- [x] Education card + 4 certification cards (all links clickable)
- [x] Contact section with email/LinkedIn/GitHub links
- [x] Footer
- [x] All links open in new tab
- [x] Fully responsive (mobile + desktop)
- [x] Dark theme throughout
- [x] Scroll animations (fade-in)
- [x] Hover effects on all interactive elements

