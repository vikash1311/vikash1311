<div align="center">

<img width="100%" src="https://raw.githubusercontent.com/vikash1311/vikash1311/main/banner.svg" />

<br/><br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-vikash2808-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/vikash2808)
[![Portfolio](https://img.shields.io/badge/Portfolio-vikash--gautam.netlify.app-0F6E56?style=for-the-badge&logo=netlify&logoColor=white)](https://vikash-gautam.netlify.app)
[![Resume](https://img.shields.io/badge/Resume-View%20Now-C2410C?style=for-the-badge&logo=googledrive&logoColor=white)](https://drive.google.com/file/d/1sF_pvUooZJb4fP3Hn4KTeSx5IjWDkchz/view)
[![Email](https://img.shields.io/badge/gautam7.ven%40gmail.com-B91C1C?style=for-the-badge&logo=gmail&logoColor=white)](mailto:gautam7.ven@gmail.com)

<br/>

![Open to Work](https://img.shields.io/badge/🟢%20Open%20to%20Work-Immediate%20Joiner-00c6ff?style=flat-square)
&nbsp;
![Location](https://img.shields.io/badge/📍%20Nagpur%2C%20India-Relocation%20%2B%20Remote%20OK-7c6af7?style=flat-square)

</div>


---

## I build production systems that scale.

Not tutorial apps. Not sandboxes. Real systems — running right now, serving real people.

- 🚆 **Production Vendor Platform** — cut login 12× (60s → 5s) and data fetch 12× (2min → 10s). Joined as bug fixer; resolved issues faster than the existing team — manager handed full ownership across 4 railway divisions.
- 🎓 **Identity Verification System** — QR generation, face detection, multi-role workflow; serving **10,000+ users across 20+ institutes**. Built entire backend solo.
- 🏛️ **Government of India Copyright holder** — Reg. L-151429/2024 for an AI image forgery detection system built with CNN + ELA.
- 📄 **3 published research papers** in Computer Vision and NLP.

> I move fast, write clean code, and take full ownership of what I build.

---

## Impact

<div align="center">

| 10,000+ | 12× | 8 Live | 7 | 4 | 3 | 1 |
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| Users on systems I built | Performance gain on production backend | Production apps delivered | OSS contributors led | Railway divisions deployed | Published research papers | Govt. of India copyright |

</div>

---

## 🚧 Currently Building

### CareerOS — AI Career Operating System &nbsp; [![Org](https://img.shields.io/badge/GitHub-Careers--Os-21262d?style=flat-square&logo=github)](https://github.com/Careers-Os) [![Status](https://img.shields.io/badge/Status-Phase%201%20Active-00c6ff?style=flat-square)]()

Open-source AI platform consolidating resume analysis, mock interviews, job tracking, and skill gap detection — **7 active contributors, Phase 1 backend + AI layer complete.**

- **Backend** — 6 Spring Boot microservices: API Gateway · User · Resume · Analysis · Interview · Job Tracker; RabbitMQ async AI queue, Redis caching, Apache Tika resume parsing
- **AI Layer** — 5 LangGraph stateful agents: ResumeAnalysisGraph · RecruiterSimGraph · InterviewGraph · SkillGapGraph · RoadmapGraph; exposed via FastAPI with Qdrant vector search
- **Leading** — authored full PRD, raised 20+ structured GitHub issues, reviewing PRs, coordinating contributors across frontend, backend, and AI modules

`Next.js 14` · `Spring Boot 3.2` · `LangGraph` · `FastAPI` · `Qdrant` · `PostgreSQL` · `Redis` · `RabbitMQ` · `Docker`

---

## Projects

### 🐞 AI Bug Tracker &nbsp; [![Live](https://img.shields.io/badge/Live-00c6ff?style=flat-square)](https://bugtrackerai.netlify.app) [![API](https://img.shields.io/badge/API-7c6af7?style=flat-square)](https://bugtracker-ai.onrender.com) [![Code](https://img.shields.io/badge/Code-21262d?style=flat-square&logo=github)](https://github.com/vikash1311/bugtracker-ai-frontend)

Multi-tenant SaaS bug tracking with AI-powered triage — production-grade from the ground up.

- **RBAC** with Admin, Developer, and Tester roles — scoped data access at every layer
- **AI triage** — auto-assigns severity, detects semantic duplicates, generates reproduction steps via Groq LLaMA 3.3 70B
- **Auth** — JWT + BCrypt + Spring Security 7, containerized with Docker
- **Architecture** — Controller–Service–Repository + DTO, @Transactional on service layer
- `Java 21` · `Spring Boot 3` · `Spring Security 7` · `MySQL 8` · `React` · `Redux` · `Groq API (LLaMA 3.3 70B)` · `Docker`

---

### 🔍 CodeLens — AI Code Review &nbsp; [![Live](https://img.shields.io/badge/Live-00c6ff?style=flat-square)](https://code-tester-ai.netlify.app) [![API](https://img.shields.io/badge/API-7c6af7?style=flat-square)](https://ai-code-review-kukl.onrender.com/api/health) [![Code](https://img.shields.io/badge/Code-21262d?style=flat-square&logo=github)](https://github.com/vikash1311/ai-code-review)

Real static analysis — not just LLM opinions.

- **AST parsing** via `acorn` — structural analysis, not surface-level feedback
- **Cyclomatic complexity scoring** + maintainability metrics across 10 languages
- **GitHub URL mode** — paste any public file URL and review it directly
- **Chose Groq over OpenAI** — 14,400 free req/day, same SDK, zero cost; stateless backend
- `Node.js` · `Express` · `React 18` · `Vite` · `Groq API (llama-3.3-70b)` · `acorn AST`

---

### 🖼️ Image Forgery Detection &nbsp; [![Copyright](https://img.shields.io/badge/Govt.%20of%20India%20Copyright-L--151429%2F2024-ffb547?style=flat-square)](https://drive.google.com/file/d/1sF_pvUooZJb4fP3Hn4KTeSx5IjWDkchz/view) [![Code](https://img.shields.io/badge/Code-21262d?style=flat-square&logo=github)](https://github.com/vikash1311/Image-Forgery-Detection)

AI system for detecting image manipulation — backed by a government copyright and 3 research papers.

- **CNN + ELA (Error Level Analysis)** to detect JPEG artifact manipulation with high accuracy
- REST API with **heatmap overlay** showing exactly where tampering occurred
- Model not publicly hosted due to size — **demo available on request**
- `Python` · `TensorFlow` · `OpenCV` · `Flask` · `CNN` · `ELA`

---

## Research Publications

| # | Title | Domain |
|:---|:---|:---|
| 1 | AI-Based Image Forgery Detection using CNN + ELA — *Govt. Copyright Registered* | Computer Vision · Security |
| 2 | AI Image Enhancement using Deep Learning | Computer Vision |
| 3 | AI Mock Interview & NLP-based Feedback Analysis | NLP · EdTech |

---

## Tech Stack

<div align="center">

**Backend**
&nbsp;
<img src="https://skillicons.dev/icons?i=java,spring,nodejs,express&theme=dark" />
&nbsp;
![Spring Security](https://img.shields.io/badge/Spring%20Security-6DB33F?style=flat-square&logo=springsecurity&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white)
![REST APIs](https://img.shields.io/badge/REST%20APIs-FF6C37?style=flat-square)

**Frontend**
&nbsp;
<img src="https://skillicons.dev/icons?i=react,typescript,vite,redux,tailwind,nextjs&theme=dark" />

**Databases**
&nbsp;
<img src="https://skillicons.dev/icons?i=mysql,mongodb,postgresql,redis,firebase&theme=dark" />

**AI / ML**
&nbsp;
<img src="https://skillicons.dev/icons?i=tensorflow,opencv,flask,python&theme=dark" />
&nbsp;
![Groq AI](https://img.shields.io/badge/Groq%20AI-F55036?style=flat-square)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square)
![Qdrant](https://img.shields.io/badge/Qdrant-DC244C?style=flat-square)

**DevOps**
&nbsp;
<img src="https://skillicons.dev/icons?i=docker,git,github,postman,netlify&theme=dark" />
&nbsp;
![Render](https://img.shields.io/badge/Render-46E3B7?style=flat-square&logo=render&logoColor=black)

</div>

---

## GitHub Activity

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/vikash1311/vikash1311/output/github-contribution-grid-snake-dark.svg"/>
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/vikash1311/vikash1311/output/github-contribution-grid-snake.svg"/>
  <img alt="GitHub contribution snake" src="https://raw.githubusercontent.com/vikash1311/vikash1311/output/github-contribution-grid-snake-dark.svg" width="100%"/>
</picture>

<br/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=vikash1311&theme=react-dark&bg_color=0d1117&color=00c6ff&line=7c6af7&point=ffb547&area=true&hide_border=true" width="100%"/>

</div>

---

## Let's talk.

I'm looking for **SDE-1 / Backend / Full Stack** roles. Immediate joiner — open to relocation and remote.

If you need someone who ships real software and takes ownership, I'd love to connect.

<div align="center">

[![Email](https://img.shields.io/badge/gautam7.ven%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:gautam7.ven@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-vikash2808-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/vikash2808)
[![Portfolio](https://img.shields.io/badge/Portfolio-vikash--gautam.netlify.app-00C7B7?style=for-the-badge&logo=netlify&logoColor=white)](https://vikash-gautam.netlify.app)
[![Resume](https://img.shields.io/badge/Resume-View%20%2F%20Download-FF6C37?style=for-the-badge&logo=googledrive&logoColor=white)](https://drive.google.com/file/d/1sF_pvUooZJb4fP3Hn4KTeSx5IjWDkchz/view)

![Profile Views](https://komarev.com/ghpvc/?username=vikash1311&color=00c6ff&style=flat-square&label=Profile+Views)

</div>

<img width="100%" src="https://raw.githubusercontent.com/vikash1311/vikash1311/main/footer.svg" />
