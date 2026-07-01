# 👋 Hello, I'm Abdelrahman Khaled (@Abdo12KM)

[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://abdok.dev)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/abdo12k)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:contact@abdok.dev)
[![Download CV](https://img.shields.io/badge/CV-4CAF50?style=for-the-badge&logo=googledrive&logoColor=white)](https://drive.google.com/file/d/1qgQ2StAQjO3qxvWbqQyrGxJQuC3LiUk6/view?usp=sharing)

**💻 Full-Stack & Applied AI Engineer** | **🎓 Computer Science Graduate (3.84/4.0 CGPA)** | **⚕️ Former Medical Student**  
📍 New Cairo, Egypt

---

## 🚀 Professional Overview

I build full-stack TypeScript and applied-AI systems end to end—from product architecture, databases, and authorization to background workflows, reliability, testing, and deployment.

Before transitioning to Computer Science, I studied medicine for four years at Kasr Al Ainy. That background still shapes how I approach engineering: investigate symptoms, isolate root causes, test assumptions, and avoid treating only surface-level problems.

My work spans secure authorization systems, fault-tolerant caching, AI tool-calling workflows, repository intelligence, compiler optimization research, semantic search, and interactive 3D experiences.

---

## 🛠️ Featured Projects

### 🚗 Automart — Automotive Dealership Management System

- **Status:** Active development; core infrastructure and major operational modules implemented
- **Project Site:** [automart.vercel.app](https://automart.vercel.app)
- **Repository:** Private
- **Highlights:**
  - 🛡️ **Hybrid Authorization:** 56 code-defined permissions synced to the database with role defaults, per-member allow/deny overrides, contextual server-side resolution, and audit logging.
  - 🤖 **Streaming AI Assistant:** Sandboxed server tools, structured source references, and permission-aware SQL reporting with field-level redaction.
  - ⚡ **Fault-Tolerant Cache Architecture:** Upstash Redis with 250 ms racing timeouts, a 60-second circuit breaker, and cross-instance PostgreSQL coordination for Redis failover.
  - 🔐 **Security & Sessions:** HttpOnly JWT sessions, PBKDF2/AES-GCM encryption, device-session management, account recovery, and active-session termination.
  - 📦 **Business Operations:** CRM, vehicle, and inventory modules with ledger-based stock adjustments, reorder alerts, a local Land Rover VIN decoder with NHTSA fallback, media workflows, and bilingual AI-assisted content.
  - 🧪 **Quality:** 403 passing Vitest tests across 87 test files with strict TypeScript checks.
- **Tech Stack:**  
  Next.js 16, React 19, TypeScript, PostgreSQL, Drizzle ORM, Upstash Redis, Tailwind CSS v4, TanStack Query, Vercel AI SDK 6, Google Gemini, Vitest

---

### ⚡ Mitos — AI Code Flow Tracing Platform

- **Status:** Functional prototype in active development
- **Repository:** Private
- **Highlights:**
  - 🧭 **Interactive Execution Traces:** Converts natural-language questions about GitHub repositories into commit-pinned traces with synchronized Monaco code views, Mermaid diagrams, narrative explanations, and timeline navigation.
  - 🧠 **Two-Phase AI Pipeline:** Tool-based repository exploration followed by structured trace synthesis, backed by symbol indexing, deterministic verification, rule-based quality scoring, and conditional self-correction.
  - 🔄 **Durable Orchestration:** Inngest workflows with attempt-scoped idempotency, transactional result persistence, Redis worker locks, and SSE status streaming with polling fallback.
  - 🔐 **Security:** Trace-scoped access controls and AES-256-GCM encryption of GitHub OAuth tokens.
  - 🗂️ **Repository Intelligence:** Commit-pinned file access, import-map analysis, symbol lookup, behavioral evidence extraction, and archived trace files for durable public sharing.
- **Tech Stack:**  
  Next.js 16, TypeScript, ElysiaJS, Better Auth, PostgreSQL, Drizzle ORM, Inngest, Upstash Redis, Monaco Editor, Mermaid.js, Vercel AI SDK, Gemini, DeepSeek

---

### 🧠 AutoCompile — LLM-Based LLVM Optimization Pass-Sequence Prediction

- **Type:** Graduation Research Project, 2026
- **Research Paper:** [Google Drive](https://drive.google.com/file/d/1b4XttPmvhX6YfApg33042AL6i74VC7rH/view?usp=sharing)
- **Highlights:**
  - 🧪 **Research Pipeline:** Co-developed a five-stage workflow covering bounded-search label generation, exact-IR deduplication, stratified dataset splitting, LoRA fine-tuning, and LLVM-based evaluation over 3,000 IR programs.
  - 🧬 **Model Evaluation:** Evaluated Qwen2.5-Coder 3B/7B/14B, Meta LLM Compiler 7B, GRPO reinforcement learning, and win-focused conditioning.
  - 📈 **Results:** Compiler-selected best-of-40 sampling reached **+4.08% guarded OverOz** versus a **+3.92% bounded-search reference** on the held-out test set.
  - 🔍 **Key Finding:** Greedy one-shot inference reached only **+1.15%**, revealing persistent template collapse despite scaling, compiler-specific pretraining, reinforcement learning, and conditioning.
  - ✅ **Methodological Controls:** Response-only SFT, strict protocol parsing, instruction-count guards, held-out evaluation, and zero cross-split exact-IR fingerprint overlap.
- **Tech Stack:**  
  Python, LLVM 19, PyTorch, Hugging Face Transformers, Unsloth, TRL, vLLM, LoRA, GRPO, Alive2

---

### 📸 AI Photography Gallery

- **Live:** [abdok.dev/photography](https://abdok.dev/photography)
- **Highlights:**
  - 🤖 **AI Photo Analysis:** Automatic tagging, caption generation, metadata enhancement, and content enrichment with Google Gemini.
  - 🔍 **Hybrid Discovery:** Vertex AI embeddings, PostgreSQL full-text search, and Gemini reranking.
  - 🎬 **Living Portfolio:** Static photos transformed into loopable cinemagraphs using Google Veo 3.1 and delivered through Cloudinary.
  - 🌐 **Immersive 3D Gallery:** React Three Fiber cylindrical layouts with concurrency-limited texture preloading, GPU cache warming, and video playback.
  - 🌟 **Daily Photo Spotlight:** Timezone-aware orchestration with fair rotation, AI-generated themes, override cascades, and Redis distributed locking.
  - 💖 **Engagement & CMS:** Rate-limited anonymous engagement tracking, secure administration, upload workflows, metadata editing, and visibility controls.
- **Tech Stack:**  
  Next.js 16, React 19, TypeScript, PostgreSQL, Drizzle ORM, Google Gemini, Vertex AI Embeddings, Google Veo 3.1, React Three Fiber, Three.js, Cloudinary, Inngest, Upstash Redis

---

### ✍️ AI Technical Publishing Platform

- **Live:** [abdok.dev/blog](https://abdok.dev/blog)
- **Highlights:**
  - 🤖 **AI Writing Workflows:** Writer, Reviewer, Refiner, and Prompt Refiner agents with repository-aware file access and structured output.
  - 🗺️ **Context-First Architecture:** Preloads repository structure and selected files before generation for stronger codebase grounding.
  - 🔍 **Drift Detection:** Stores file SHAs, compares them against live GitHub state, surfaces commit history, and identifies modified, deleted, or moved references.
  - 🎨 **Diagram Workflows:** AI-image, Mermaid, and hybrid modes with diagram-preserving tokenization during refinement.
  - 📝 **Rich Editing:** Monaco split-pane editing, live Markdown preview, diff views, autosave, and recoverable drafts.
  - 🔄 **Version History:** Protected checkpoints, version pinning, and automatic pruning.
  - ⚡ **Background Processing:** Inngest-powered generation with Redis-backed progress tracking and atomic database writes.
- **Tech Stack:**  
  Next.js 16, TypeScript, Vercel AI SDK 6, Google Gemini, Inngest, Monaco Editor, Mermaid.js, GitHub API, Upstash Redis, PostgreSQL, Drizzle ORM

---

## 🏆 Activities & Awards

- 🥈 **2nd Place / 400+ Participants** — SolveTHE17 Hackathon  
  Co-developed [Nour Al Maarifa](https://nour-alma3refa.vercel.app), an AI-powered application promoting Arabic literacy in Egypt.
- 🥉 **Back-to-Back 3rd Place Finishes** — RoboCup@Home AAST, 2025 and 2026
- 🏅 **5th Place / 100 Teams** — Google Developer Groups AI Finance Hackathon
- 🧠 **35th Place / 183 Teams** — Egyptian Collegiate Programming Contest (ECPC)

---

## ⚙️ Tech Stack

### Languages

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-007396?style=flat&logo=openjdk&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat&logo=cplusplus&logoColor=white)
![C#](https://custom-icon-badges.demolab.com/badge/C%23-239120.svg?logo=cshrp&logoColor=white)

### Frontend

![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat&logo=tailwindcss&logoColor=white)
![Framer Motion](https://img.shields.io/badge/Framer_Motion-0055FF?style=flat&logo=framer&logoColor=white)
![React Three Fiber](https://img.shields.io/badge/React_Three_Fiber-000000?style=flat&logo=threedotjs&logoColor=white)
![Three.js](https://img.shields.io/badge/Three.js-000000?style=flat&logo=threedotjs&logoColor=white)
![TanStack Query](https://img.shields.io/badge/TanStack_Query-FF4154?style=flat&logo=reactquery&logoColor=white)
![HeroUI](https://img.shields.io/badge/HeroUI-000000?style=flat&logo=heroui&logoColor=white)
![shadcn/ui](https://img.shields.io/badge/shadcn%2Fui-000000?style=flat&logo=shadcnui&logoColor=white)

### Backend, Data & Infrastructure

![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=nodedotjs&logoColor=white)
![ElysiaJS](https://img.shields.io/badge/ElysiaJS-7C3AED?style=flat&logo=bun&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-000000?style=flat&logo=express&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat&logo=mongodb&logoColor=white)
![Drizzle ORM](https://img.shields.io/badge/Drizzle_ORM-C5F74F?style=flat&logo=drizzle&logoColor=black)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white)
![Inngest](https://img.shields.io/badge/Inngest-060C1A?style=flat&logo=inngest&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat&logo=vercel&logoColor=white)

### AI, ML & Developer Tools

![Vercel AI SDK](https://img.shields.io/badge/Vercel_AI_SDK-000000?style=flat&logo=vercel&logoColor=white)
![Google Gemini](https://img.shields.io/badge/Google_Gemini-8E75B2?style=flat&logo=googlegemini&logoColor=white)
![Vertex AI](https://img.shields.io/badge/Vertex_AI-4285F4?style=flat&logo=googlecloud&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging_Face-FFD21E?style=flat&logo=huggingface&logoColor=black)
![LLVM](https://img.shields.io/badge/LLVM-262D3A?style=flat&logo=llvm&logoColor=white)
![Monaco Editor](https://img.shields.io/badge/Monaco_Editor-007ACC?style=flat&logo=visualstudiocode&logoColor=white)
![Mermaid.js](https://img.shields.io/badge/Mermaid.js-FF3670?style=flat&logo=mermaid&logoColor=white)

### Testing & Quality

![Vitest](https://img.shields.io/badge/Vitest-6E9F18?style=flat&logo=vitest&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat&logo=playwright&logoColor=white)
![Zod](https://img.shields.io/badge/Zod-1A365D?style=flat&logo=zod&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)

---

## 📊 Development Activity

<div align="center">
  <img height="180em" src="https://abdo-readme.vercel.app/api?username=abdo12km&show_icons=true&theme=dark&hide_border=true&count_private=true" alt="Abdelrahman's GitHub statistics">
  <img height="180em" src="https://abdo-readme.vercel.app/api/top-langs/?username=abdo12km&layout=compact&theme=dark&hide_border=true" alt="Most used languages">
</div>

<!--START_SECTION:waka-->

```txt
From: 23 June 2026 - To: 30 June 2026

Total Time: 18 hrs 10 mins

TypeScript   10 hrs 33 mins        ██████████████▒░░░░░░░░░░   57.20 %
Markdown     4 hrs 23 mins         ██████░░░░░░░░░░░░░░░░░░░   23.78 %
JSON         1 hr 54 mins          ██▓░░░░░░░░░░░░░░░░░░░░░░   10.30 %
TeX          1 hr 5 mins           █▒░░░░░░░░░░░░░░░░░░░░░░░   05.89 %
Other        17 mins               ▒░░░░░░░░░░░░░░░░░░░░░░░░   01.56 %
```

<!--END_SECTION:waka-->

---

## 📫 Let's Connect!

I am interested in full-stack, backend, product-engineering, and applied-AI opportunities where I can own complex systems, solve ambiguous technical problems, and contribute beyond a narrowly defined layer.

[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://abdok.dev)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/abdo12k)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:contact@abdok.dev)
