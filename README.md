<div align="center">

# Hi there, I'm Takwa Hafyen 👋

### 🚀 Software Engineer & AI Architect | Full-Stack • Agentic AI • DevOps • QA

<p align="center">
  <a href="https://linkedin.com/in/takwa-hafyen-472264282"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:takwa.hafyen@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail" /></a>
  <a href="https://github.com/takwahafyen"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" /></a>
</p>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=20&duration=3000&pause=1000&color=2E86AB&center=true&vCenter=true&width=700&lines=Production-Grade+Agentic+AI+Architectures;Multi-Agent+CrewAI+%26+Voice+AI+Systems;Cloud-Native+Full-Stack+Engineering;DevOps+%2B+CI%2FCD+%2B+Container+Security;End-to-End+QA+Automation+%26+Security+Hardening;Enterprise+PowerApps+%26+Industry+4.0+ML" alt="Typing SVG" />

</div>

---

## 💡 About Me

- 🤖 **Agentic AI Architect:** Designing production-grade multi-agent systems with **CrewAI**, real-time voice AI pipelines (**LiveKit**, **Deepgram**, **Silero VAD**), hybrid RAG with `pgvector`, and **MCP**-standardized tooling.
- 🏭 **Industry 4.0 & ML:** Building Computer Vision + NLP microservices deployed on **Hugging Face**, integrated with **Power Apps** for real-world factory diagnostics.
- 💻 **Full-Stack Craftsman:** From **Laravel 11 + Elasticsearch** to **MERN + TypeScript + RBAC**, I architect scalable, secure, and resilient platforms.
- ⚙️ **DevOps & Security First:** Automated CI/CD with **GitHub Actions**, containerization with **Docker**, SAST with **CodeQL**, vulnerability scanning with **Trivy**, and **OWASP Top 10** hardening.
- 🧪 **QA-Driven:** E2E testing with **Cypress**, integration testing with **Jest/Supertest**, static analysis with **PHPStan Level 8**.
- ⚡ **Low-Code Power:** Streamlining enterprise workflows using **Microsoft Power Apps** & **Power Automate**.

---

## 🌟 Featured Projects

### 1. 🤖 [Pilot — Agentic AI Architecture](https://github.com/takwahafyen/Pilot-agentic-ai-architecture)
> **Production-Grade Multi-Agent Orchestration powering an enterprise EdTech platform in Tunisia**

A complete architectural design and implementation of the Agentic AI system behind **Pilot TN**, featuring a real-time streaming voice agent and a 3-tier CrewAI multi-agent cluster.

**Highlights:**
- 🎙️ **Real-Time Voice Agent**: LiveKit SFU + Silero VAD with barge-in interruption in **<350ms**, Deepgram STT streaming, OpenAI TTS
- 🧠 **3-Tier CrewAI Cluster**: *Pedagogical Tutor Agent* (RAG-grounded) → *Fact-Checker Anti-Hallucination Agent* → *Adaptive Quiz Generator Agent*
- 🔍 **Hybrid RAG**: `Score = 0.75 × CosineSimilarity + 0.25 × BM25Boost` on `pgvector`, markdown-preserving semantic chunking
- 🛡️ **MCP Tools with Pydantic v2**: `KnowledgeSearchInput` (prompt-injection sanitized), `CalendarToolInput`, `HandoffToolInput` (HITL escalation)
- 📊 **Observability**: Langfuse full tracing (tokens, cost, latency) + Ragas evaluation harness (Faithfulness & Answer Relevance)

`CrewAI` `LiveKit` `Deepgram` `Silero VAD` `Gemini Flash` `pgvector` `FastAPI` `Next.js 16` `Payload CMS` `Langfuse` `Ragas` `MCP` `Pydantic v2`

---

### 2. 🏭 [Lessons Learned Smart Application](https://github.com/takwahafyen/Lessons-Learned-Smart-Application)
> **Industry 4.0 AI Diagnostic Platform — PFE Graduation Project**

End-to-end solution combining **Microsoft Power Apps** and a **Computer Vision / NLP microservice** deployed on Hugging Face, automating machine error diagnostics on factory shop floors.

**Highlights:**
- 📸 **Multi-Strategy CV OCR**: Central 50% ROI bounding box, bilateral filtering, adaptive Gaussian thresholding vs. Otsu binarization cascade (confidence threshold `>25.0` + industrial regex validation)
- 🤖 **Multi-Output NLP Classifier**: TF-IDF + Random Forest `MultiOutputClassifier` predicting **Root Cause** AND **Corrective Action** simultaneously
- ⚡ **Sub-15ms ML inference** per prediction — from 10 minutes of manual lookup to under 5 seconds MTTR
- 🔗 **Dual Integration**: Interactive Gradio launch from Power Apps + headless JSON API (`/api/diagnose`) via Power Automate
- 🌐 [Live Demo on Hugging Face](https://huggingface.co/spaces/takwahafyen/Lessons_Learned_Smart_App) | [YouTube Walkthrough](https://www.youtube.com/watch?v=2GDLJ0Q30o0)

`Python 3.10` `OpenCV` `Tesseract OCR` `Scikit-Learn` `Gradio` `Hugging Face Spaces` `Power Apps` `Power Automate` `Git LFS`

---

### 3. 🏥 [Clinic Management System](https://github.com/takwahafyen/Clinic-management-system)
> **Production MERN Platform with RBAC, Security Hardening & Full CI/CD**

Full-stack clinic platform for Doctors, Nurses, Pharmacists, Patients — covering registration, consultation reports, vital signs, and medication records. Built to production security standards.

**Highlights:**
- 🔐 **Multi-Role RBAC**: JWT cookie-auth (`sameSite: none`), Mongoose discriminator inheritance (single `users` collection → 3 role models)
- 🛡️ **Security Stack**: Helmet, `express-rate-limit`, `express-mongo-sanitize`, CodeQL SAST, Aquasec Trivy container scanning
- 🧪 **Full Test Coverage**: Jest + Supertest + `mongodb-memory-server`, React Testing Library, **Cypress E2E** (auth, route guards, patient flows)
- 🎨 **UX**: Animated dark/dark mode, zero-dependency bilingual i18n (EN/FR), React ErrorBoundary, Toast system
- 🌐 [Live Frontend](https://clinic-management-system-um8a-rose.vercel.app/) | [Live API](https://clinic-management-backend-lpki.onrender.com/)

`React 18` `TypeScript` `Node.js` `Express` `MongoDB` `Mongoose` `JWT` `Docker` `GitHub Actions` `CodeQL` `Trivy` `Cypress` `Jest` `Vercel` `Render`

---

### 4. 🏠 [UniStay — Student Housing Platform](https://github.com/takwahafyen/UniStay)
> **Cloud-Native Booking Platform with Elasticsearch & OWASP Top 10 Hardening**

Modern Laravel 11 platform for student accommodation featuring advanced geospatial search, full-text fuzzy search, trilingual UI, and strict security engineering.

**Highlights:**
- 🔍 **Elasticsearch 8**: French linguistic analyzer, `Fuzziness AUTO`, geospatial `geo_distance` campus proximity filtering, real-time pricing aggregations
- 🔒 **OWASP Top 10**: Argon2id/Bcrypt hashing, anti-CSRF/XSS, Anti-IDOR resource policies, pessimistic DB locking (`lockForUpdate`) against double-booking race conditions
- 🌍 **Trilingual UI**: English, French, Arabic with full RTL layout support
- 🐳 **6-Container Orchestration**: Nginx + PHP 8.3 FPM + PostgreSQL + Redis + Elasticsearch + Mailpit via Docker Compose
- 📐 **Code Quality**: PHPStan Level 8 static analysis, Laravel Pint PSR-12
- 🌐 [Live App](https://student-housing-zvgu.onrender.com/)

`PHP 8.3` `Laravel 11` `Elasticsearch 8` `PostgreSQL` `Redis` `Docker Compose` `PHPUnit` `PHPStan` `GitHub Actions` `Render`

---

### 5. 🛍️ [NovaMart Platform](https://github.com/takwahafyen/Novamart-platform)
> **Full-Stack E-Commerce Monorepo with Hardened Container CI/CD**

Modular monorepo with a customer storefront, merchant analytics dashboard, and a containerized Express REST API — with automated Docker releases to GitHub Container Registry.

**Highlights:**
- 🏗️ **Monorepo Architecture**: Decoupled `frontend/` (storefront), `admin-dash/` (merchant analytics), `backend/` (REST API)
- 🐳 **Hardened Containers**: Multi-stage Dockerfile, non-root `appuser` (UID 1001), automated healthcheck (`/api/health`)
- 🚀 **Automated Releases**: GitHub Actions → GHCR Docker image publish on `main` push
- 🌐 [Live Storefront](https://novamart-platform.vercel.app/)

`Next.js` `React` `Node.js` `Express` `MongoDB` `Docker` `GitHub Actions` `GHCR` `Vercel` `Vitest`

---

### 6. 😊 [Facial Emotion Recognition](https://github.com/takwahafyen/Facial-emotion-recognition)
> **Real-Time CNN Emotion Detector with Psychological Conseil System**

Real-time facial emotion detection using a Convolutional Neural Network, enhanced with a live **psychological conseil sidebar panel** that renders 3 actionable tips + a mindset quote for every detected emotion — turning a classic CV project into a human-aware AI application.

**Highlights:**
- 🎭 **7-Class Emotion Detection**: Angry, Disgust, Fear, Happy, Neutral, Sad, Surprise — real-time via OpenCV webcam loop with per-face confidence score overlay
- 🧠 **Psychological Conseil Engine**: For every detected emotion, a color-coded sidebar panel renders 3 actionable psychological tips + a mindset quote in real-time
- 🏗️ **CNN Architecture**: 3× Conv2D + BatchNorm + MaxPool + Dropout blocks → Dense(256) → Softmax(7), trained on FER2013 (35,887 × 48×48 grayscale images)
- 🔍 **Multi-Face Support**: Haar Cascade detector handles multiple faces simultaneously, each with independent emotion classification
- 📐 **Clean Module Design**: Separated `src/emotions_advice.py` conseil engine + `src/realtime.py` inference pipeline

`Python` `TensorFlow` `Keras` `OpenCV` `scikit-learn` `NumPy` `FER2013` `Jupyter Notebook`

---

## 🛠️ Full Technology Stack

<details open>
<summary><b>🤖 Agentic AI & Machine Learning</b></summary>
<br>

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![CrewAI](https://img.shields.io/badge/CrewAI-000000?style=flat-square&logo=crewai&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white)
![Google Gemini](https://img.shields.io/badge/Gemini-8E75B2?style=flat-square&logo=googlegemini&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![Scikit-Learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)

**CrewAI multi-agent orchestration** • Real-time Voice AI (LiveKit + Silero VAD) • Hybrid RAG (pgvector + BM25) • Computer Vision (OpenCV) • NLP (TF-IDF + RandomForest) • MCP tooling • Langfuse observability • Ragas evaluation

</details>

<details open>
<summary><b>💻 Full-Stack Development</b></summary>
<br>

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![PHP](https://img.shields.io/badge/PHP_8.3-777BB4?style=flat-square&logo=php&logoColor=white)
![Laravel](https://img.shields.io/badge/Laravel_11-FF2D20?style=flat-square&logo=laravel&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white)
![Elasticsearch](https://img.shields.io/badge/Elasticsearch_8-005571?style=flat-square&logo=elasticsearch&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)

</details>

<details open>
<summary><b>🚀 DevOps, Cloud & Security</b></summary>
<br>

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)
![Render](https://img.shields.io/badge/Render-46E3B7?style=flat-square&logo=render&logoColor=black)
![Hugging Face](https://img.shields.io/badge/HuggingFace_Spaces-FFD21E?style=flat-square&logo=huggingface&logoColor=black)

CI/CD pipelines • Multi-container orchestration • CodeQL SAST • Trivy container scanning • OWASP Top 10 hardening • Non-root containers • GitHub Container Registry (GHCR)

</details>

<details open>
<summary><b>🧪 Quality Assurance & Testing</b></summary>
<br>

![Cypress](https://img.shields.io/badge/Cypress-69D3A7?style=flat-square&logo=cypress&logoColor=black)
![Jest](https://img.shields.io/badge/Jest-C21325?style=flat-square&logo=jest&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white)

E2E (Cypress) • Unit & Integration (Jest / PHPUnit) • API (Supertest) • Static Analysis (PHPStan Level 8) • In-memory DB testing (`mongodb-memory-server`) • AI Eval (Ragas)

</details>

<details open>
<summary><b>⚡ Low-Code & Enterprise (Microsoft Power Platform)</b></summary>
<br>

![Power Apps](https://img.shields.io/badge/Power_Apps-742774?style=flat-square&logo=microsoftpowerapps&logoColor=white)
![Power Automate](https://img.shields.io/badge/Power_Automate-0066FF?style=flat-square&logo=powerautomate&logoColor=white)

Canvas & Model-Driven Apps • HTTP connector headless API integration • Enterprise business process automation • Industry 4.0 shop-floor solutions

</details>

---

## 📊 GitHub Analytics

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=takwahafyen&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" width="48%" alt="Takwa's GitHub Stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=takwahafyen&layout=compact&theme=tokyonight&hide_border=true" width="48%" alt="Top Languages" />
</div>

<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=takwahafyen&theme=tokyonight&hide_border=true" width="97%" alt="GitHub Streak" />
</div>

---

## 📬 Connect With Me

- 💼 **LinkedIn:** [linkedin.com/in/takwa-hafyen-472264282](https://linkedin.com/in/takwa-hafyen-472264282)
- ✉️ **Email:** [takwa.hafyen@gmail.com](mailto:takwa.hafyen@gmail.com)
- 🌐 **GitHub:** [@takwahafyen](https://github.com/takwahafyen)

<div align="center">
  <sub>⭐ Built with precision, deployed with confidence, evaluated with rigor.</sub>
</div>
