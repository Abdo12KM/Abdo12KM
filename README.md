# 👋 Hello, I'm Abdelrahman Khaled (@Abdo12KM)

[![Portfolio](https://img.shields.io/badge/Portfolio-%23000000.svg?style=for-the-badge&logo=vercel&logoColor=white)](https://abdok.dev)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/abdo12k)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:contact@abdok.dev)
[![Download CV](https://img.shields.io/badge/CV-4CAF50?style=for-the-badge&logo=googleDrive&logoColor=white)](https://drive.google.com/file/d/1qgQ2StAQjO3qxvWbqQyrGxJQuC3LiUk6/view?usp=sharing)

**💻 Full-Stack Developer** | **🎓 Senior CS Student (3.83/4.0 GPA)** | **⚕️ Former Med Student**  
📍 New Cairo, Egypt

---

## 🚀 Professional Overview

High-performing CS Senior and Hackathon Winner specializing in modern Full-Stack architecture (Next.js 16, TypeScript, SQL). Proven track record of building secure, enterprise-grade systems featuring custom permission engines, AI tool-calling integrations, and fault-tolerant cache layers. Transitioned from medical studies with a strong foundation in diagnostic problem-solving.

---

## 🛠️ Featured Projects

### 🚗 Automart – Enterprise Land Rover Dealership Management System

- **Status:** Production-Ready (Complete SDLC, 1000+ Hours)
- **Live:** [automart.vercel.app](https://automart.vercel.app)
- **Highlights:**
  - 🛡️ **Granular Authorization:** Hybrid authorization engine with a code-defined 56-permission catalog synced to the database, supporting per-member overrides and a server-authoritative resolver—replacing legacy role-threshold RBAC.
  - 🤖 **Sandboxed AI Assistant:** Tool-based streaming AI assistant using Vercel AI SDK 6 and Google Gemini. Executes queries through tightly-scoped server tools with field-level permission redaction. Features an advanced dynamic SQL report builder.
  - ⚡ **Fault-Tolerant Cache Architecture:** Upstash Redis + Drizzle ORM caching backed by 250ms racing timeouts, a 60s circuit breaker, and cross-instance PostgreSQL coordination for automated Redis-down failovers.
  - 🔐 **Compliance & Sessions:** Custom JWT authentication with HttpOnly cookies, PBKDF2/AES-GCM encryption, full system audit logging, and a real-time active session termination dashboard with device tracking.
  - 👥 **Staff Management:** Full CRUD with an AI-enhanced warning system, OTP password resets, and a session management dashboard with per-device tracking.
  - 📦 **Inventory & Reg Systems:** Complete parts management with ledger-based adjustments, stock transfers, reorder alerts, and Gemini-powered translation. CRM-style registry integrated with a local Land Rover VIN decoder and NHTSA fallbacks.
  - 📢 **Communications Hub:** Message board with PDF export, announcements system with AI translation and version rollback.
  - 🌍 **Public Portal & i18n:** Full EN/AR localization with dynamic RTL/LTR layout handling (next-intl). Public landing page optimized with coordinate binning, route caching, and rate limits to minimize Google API costs.
- **Tech Stack:**  
  Next.js 16 (App Router), React 19, TypeScript, PostgreSQL (Neon), Drizzle ORM, Upstash Redis, Tailwind CSS v4, TanStack Query, Vercel AI SDK 6, Vitest (403 tests)

### 📸 AI Photography Gallery

- **Live:** [abdok.dev/photography](https://abdok.dev/photography)
- **Highlights:**
  - 🤖 **AI Photo Analysis:** Automatic tagging, caption generation & content enrichment using Google Gemini 3 Flash.
  - 🔍 **Hybrid Search:** Semantic vector search (Vertex AI embeddings) + Gemini 2.5 Flash Lite re-ranking for intelligent retrieval.
  - 🎬 **Living Portfolio:** Static photos transformed into 8-second loopable cinemagraphs using Google Veo 3.1, streamed from Cloudinary.
  - 🌐 **Immersive 3D Gallery:** React Three Fiber/Three.js cylindrical layout with mouse-controlled camera navigation.
  - 🌟 **Daily Photo Spotlight:** 3-tier priority system with AI-generated themes & cron orchestration.
  - 💖 **Engagement Tracking:** Anonymous love system with browser fingerprinting & rate limiting.
  - 🔐 **Admin CMS:** Session-based auth with Redis+DB hybrid caching and full gallery CRUD.
- **Tech Stack:**  
  Next.js 16, React 19, TypeScript, PostgreSQL (Neon), Google Gemini, Vertex AI Embeddings, Google Veo 3.1, React Three Fiber, Tailwind CSS v4, Framer Motion, Upstash Redis

### ✍️ AI Blog Generator – Technical Writing Platform

- **Live:** [abdok.dev/blog](https://abdok.dev/blog)
- **Highlights:**
  - 🤖 **Multi-Agent AI Pipeline:** Writer, Reviewer, and Refiner agents using AI SDK 6 ToolLoop for dynamic file reading and diagram creation.
  - 🗺️ **Context-First Architecture:** Pre-loads repository file tree ("The Map") and user-selected files before generation for full codebase awareness.
  - 🔍 **Drift Detection (Experimental):** Stores file SHAs at generation time, compares against live GitHub state to alert when referenced code changes.
  - 🎨 **Diagram Modes:** AI-generated images (Gemini), Mermaid.js syntax, or hybrid selection — with a full tokenization pipeline for context management.
  - 📝 **Rich Editing:** Monaco split-pane editor with live Markdown preview, diff viewing, and auto-save drafts.
  - 🔄 **Version Control:** Auto-pruning at 50 versions with protected change types and version pinning.
  - ⚡ **Background Processing:** Inngest-powered async generation with Redis-backed progress tracking.
- **Tech Stack:**  
  Next.js 16, AI SDK 6, Google Gemini, Inngest, Monaco Editor, Mermaid.js, GitHub API, Upstash Redis, Drizzle ORM

---

## 🏆 Activities & Awards

- 🥈 **2nd Place** @ SolveTHE17 Hackathon (400+ participants) - AI literacy app ([Nour Al Maarifa](https://nour-alma3refa.vercel.app))
- 🥉 **3rd Place (Back-to-Back)** @ RoboCup@Home AAST (2026, 2025)
- 🏅 **Finalist** @ Google Developers Groups AI Finance Hackathon (Top 5/100 teams)
- 🧠 **35th Place** @ Egyptian Collegiate Programming Contest (ECPC)

---

## ⚙️ Tech Stack

**Languages:**
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![Java](https://img.shields.io/badge/Java-007396?style=flat&logo=openjdk&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat&logo=cplusplus&logoColor=white)
![C#](https://custom-icon-badges.demolab.com/badge/C%23-%23239120.svg?logo=cshrp&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)

**Frontend:**
![Next.js 16](https://img.shields.io/badge/Next%2Ejs_16-000000?style=flat&logo=nextdotjs&logoColor=white)
![React 19](https://img.shields.io/badge/React_19-61DAFB?style=flat&logo=react&logoColor=black)
![TailwindCSS v4](https://img.shields.io/badge/TailwindCSS_v4-06B6D4?style=flat&logo=tailwindcss&logoColor=white)
![Framer Motion](https://img.shields.io/badge/Framer%20Motion-0055FF?style=flat&logo=framer&logoColor=white)
![React Three Fiber](https://img.shields.io/badge/React_Three_Fiber-000000?style=flat&logo=threedotjs&logoColor=white)
![Three.js](https://img.shields.io/badge/Three%2Ejs-000000?style=flat&logo=threedotjs&logoColor=white)
![HeroUI](https://img.shields.io/badge/HeroUI-000000?style=flat&logo=heroui&logoColor=white)
![Shadcn/ui](https://img.shields.io/badge/shadcn%2Fui-000000?style=flat&logo=shadcnui&logoColor=white)
![Recharts](https://img.shields.io/badge/Recharts-22B5BF?style=flat&logo=recharts&logoColor=white)

**Backend, DB & Core Infrastructure:**
![Node.js](https://img.shields.io/badge/Node%2Ejs-339933?style=flat&logo=nodedotjs&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![Drizzle ORM](https://img.shields.io/badge/Drizzle_ORM-C5F74F?style=flat&logo=drizzle&logoColor=black)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white)
![Inngest](https://img.shields.io/badge/Inngest-060C1A?style=flat&logo=inngest&logoColor=white)
![TanStack Query](https://img.shields.io/badge/TanStack_Query-FF4154?style=flat&logo=reactquery&logoColor=white)
![Zod](https://img.shields.io/badge/Zod-1A365D?style=flat&logo=zod&logoColor=white)
![next-intl](https://img.shields.io/badge/next--intl-000000?style=flat)
![UploadThing](https://img.shields.io/badge/UploadThing-EB4F27?style=flat&logo=uploadthing&logoColor=white)
![Resend](https://img.shields.io/badge/Resend-000000?style=flat&logo=resend&logoColor=white)

**AI & ML:**
![Vercel AI SDK 6](https://img.shields.io/badge/Vercel_AI_SDK_6-000000?style=flat&logo=vercel&logoColor=white)
![Google Gemini](https://img.shields.io/badge/Google_Gemini-8E75B2?style=flat&logo=googlegemini&logoColor=white)
![Vertex AI](https://img.shields.io/badge/Vertex_AI-4285F4?style=flat&logo=googlecloud&logoColor=white)
![Deepseek](https://img.shields.io/badge/Deepseek-0066FF?style=flat)

---

## 📊 Development Activity

<div align="center">
  <img height="180em" src="https://abdo-readme.vercel.app/api?username=abdo12km&show_icons=true&theme=dark&hide_border=true&count_private=true">
  <img height="180em" src="https://abdo-readme.vercel.app/api/top-langs/?username=abdo12km&layout=compact&theme=dark&hide_border=true">
</div>

<!--START_SECTION:waka-->

```txt
From: 22 May 2026 - To: 29 May 2026

Total Time: 22 hrs 17 mins

TypeScript   12 hrs 48 mins        █████████████▓░░░░░░░░░░░   55.29 %
Markdown     7 hrs 29 mins         ████████░░░░░░░░░░░░░░░░░   32.33 %
Other        52 mins               █░░░░░░░░░░░░░░░░░░░░░░░░   03.75 %
JSON         47 mins               █░░░░░░░░░░░░░░░░░░░░░░░░   03.43 %
JavaScript   24 mins               ▒░░░░░░░░░░░░░░░░░░░░░░░░   01.79 %
```

<!--END_SECTION:waka-->

---

## 📫 Let's Connect!

I am actively seeking new opportunities and collaborations. Reach out to discuss innovative engineering or potential roles!

[![Portfolio](https://img.shields.io/badge/Portfolio-%23000000.svg?style=for-the-badge&logo=vercel&logoColor=white)](https://abdok.dev)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/abdo12k)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:contact@abdok.dev)
