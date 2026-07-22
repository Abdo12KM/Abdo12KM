<div align="center">

<!-- Commas inside srcset URLs are percent-encoded so browsers do not treat them as separate image candidates. -->
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://capsule-render.vercel.app/api?type=waving&amp;color=0%3A0f172a%2C100%3A2563eb&amp;height=158&amp;section=header&amp;text=Abdelrahman%20Khaled&amp;fontSize=34&amp;fontColor=f8fafc&amp;animation=fadeIn&amp;fontAlignY=30&amp;desc=Full-stack%20systems%20%7C%20Applied%20AI%20%7C%20Developer%20tools&amp;descAlignY=50&amp;descSize=15&amp;descColor=cbd5e1">
  <source media="(prefers-color-scheme: light)" srcset="https://capsule-render.vercel.app/api?type=waving&amp;color=0%3Adbeafe%2C100%3A93c5fd&amp;height=158&amp;section=header&amp;text=Abdelrahman%20Khaled&amp;fontSize=34&amp;fontColor=0f172a&amp;animation=fadeIn&amp;fontAlignY=30&amp;desc=Full-stack%20systems%20%7C%20Applied%20AI%20%7C%20Developer%20tools&amp;descAlignY=50&amp;descSize=15&amp;descColor=334155">
  <img src="https://capsule-render.vercel.app/api?type=waving&amp;color=0%3Adbeafe%2C100%3A93c5fd&amp;height=158&amp;section=header&amp;text=Abdelrahman%20Khaled&amp;fontSize=34&amp;fontColor=0f172a&amp;animation=fadeIn&amp;fontAlignY=30&amp;desc=Full-stack%20systems%20%7C%20Applied%20AI%20%7C%20Developer%20tools&amp;descAlignY=50&amp;descSize=15&amp;descColor=334155" alt="Abdelrahman Khaled, Full-stack systems, applied AI, and developer tools" width="100%">
</picture>

### Production systems that explain themselves.

**Full-stack engineering** · **Applied AI** · **Developer tooling** · **Research**

[![Portfolio](https://img.shields.io/badge/Portfolio-abdok.dev-111111?style=for-the-badge&logo=vercel&logoColor=white)](https://abdok.dev)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/abdo12k)
[![Email](https://img.shields.io/badge/Email-contact%40abdok.dev-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:contact@abdok.dev)
[![Resume](https://img.shields.io/badge/Resume-View-2E7D32?style=for-the-badge&logo=readthedocs&logoColor=white)](https://drive.google.com/file/d/1qgQ2StAQjO3qxvWbqQyrGxJQuC3LiUk6/view?usp=sharing)

<sub>B.Sc. Computer Science · 3.84/4.0 CGPA · New Cairo, Egypt</sub>

**[Selected work](#selected-work) · [Proof](#proof-in-numbers) · [Capabilities](#capabilities) · [Journey](#journey) · [Contact](#contact)**

</div>

---

## About

Before Computer Science, I studied medicine for four years at Kasr Al Ainy. The domain changed; the method did not: inspect the evidence, isolate the cause, test the hypothesis, and fix the underlying system rather than its most visible symptom.

Today, I design and ship systems across authorization, databases, durable jobs, AI tool calling, evaluation, testing, and deployment. I care about interfaces that make complex behavior understandable, not merely functional.

> **Operating principle:** schema → product → evidence → production

**Currently open to:** full-stack, backend, product-engineering, and applied-AI opportunities.

### Explore by interest

- Building secure, production-grade product systems → **[Automart](https://abdok.dev/projects/automart)**
- Turning repositories into verified execution knowledge → **[Mitos](https://abdok.dev/projects/mitos)**
- Designing AI interfaces with explicit trust boundaries → **[Ask Abdo](https://abdok.dev/projects/ask-abdo)**
- Researching learned compiler optimization → **[AutoCompile](https://abdok.dev/projects/autocompile)**
- Combining search, graphics, and media systems → **[Photography](https://abdok.dev/projects/photography)**

## Proof in numbers

| Evidence                                                                  |                         Result |
| ------------------------------------------------------------------------- | -----------------------------: |
| [Automart authorization model](https://abdok.dev/projects/automart)       |    **65 granular permissions** |
| [Automart full-stack test suite](https://abdok.dev/projects/automart)     | **662 tests across 168 files** |
| [Mitos AI-system test suite](https://abdok.dev/projects/mitos)            |  **288 tests across 66 files** |
| [AutoCompile optimization result](https://abdok.dev/projects/autocompile) |      **+4.08% guarded OverOz** |
| [Photography hybrid discovery](https://abdok.dev/projects/photography)    |   **170+ indexed photographs** |
| Academic foundation                                                       |              **3.84/4.0 CGPA** |

## Selected work

<details open>
<summary><strong>🚗 Automart</strong>: dealership operations platform · public case study</summary>

<br>

A full-stack operations platform spanning staff, customers, vehicles, inventory, communication, reporting, and AI-assisted workflows.

**[Case study](https://abdok.dev/projects/automart) · [Public site](https://automart.vercel.app) · Repository private**

**What it demonstrates**

- **Authorization:** 65 database-synchronized permissions, role defaults, member-level allow/deny overrides, contextual server checks, and audit logs.
- **Reliability:** Redis caching with 250 ms racing timeouts, a 60-second circuit breaker, PostgreSQL fallback paths, and cross-instance outage coordination.
- **Applied AI:** a streaming assistant with sandboxed tools, structured sources, permission-aware SQL reporting, and field-level redaction.
- **Quality:** JOSE-signed sessions, PBKDF2 password hashing, AES-GCM credential encryption, strict TypeScript, and **662 passing tests across 168 files**.

`Next.js 16` · `React 19` · `TypeScript` · `PostgreSQL` · `Drizzle` · `Redis` · `AI SDK` · `Gemini` · `Vitest`

</details>

<details>
<summary><strong>⚡ Mitos</strong>: repository questions → verified execution traces · live</summary>

<br>

An AI developer tool that converts natural-language questions about GitHub repositories into commit-pinned, shareable execution knowledge.

**[Case study](https://abdok.dev/projects/mitos) · [Live product](https://mitos.abdok.dev) · Repository private**

**What it demonstrates**

- Builds synchronized FlowBoard and Mermaid diagrams, Monaco source views, timelines, and narrative steps.
- Uses bounded repository exploration, evidence extraction, trace planning, structured drafting, and symbol-graph fallback.
- Verifies paths, line ranges, snippets, graph connections, prompt coverage, and semantic quality before publishing a trace.
- Runs through durable Inngest stages with cancellation, concurrency controls, retry-safe guards, artifact offloading, optional Redis locks, SSE progress, and **288 passing tests across 66 files**.

`Next.js 16` · `ElysiaJS` · `Better Auth` · `PostgreSQL` · `Inngest` · `Monaco` · `Mermaid` · `Gemini` · `DeepSeek`

</details>

<details>
<summary><strong>🦇 Ask Abdo</strong>: evidence-backed portfolio assistant · live</summary>

<br>

A correctness-first assistant embedded in abdok.dev, designed around a strict trust boundary rather than generic chat behavior.

**[Case study](https://abdok.dev/projects/ask-abdo) · [Live product](https://abdok.dev)**

**What it demonstrates**

- Rebuilds trusted public evidence for every request instead of trusting browser history or client-produced facts.
- Keeps canonical project, article, photo, resume, social, and contact data server-owned while models select bounded stable keys.
- Releases model output only after links, schema, terminal plan, and completion state pass validation.
- Adds route-aware starters, local history, inline actions, follow-up suggestions, recruiter shortcuts, a resource library, and real-model production-path evaluations.

`Next.js 16` · `React 19` · `TypeScript` · `Vercel AI SDK` · `Gemini` · `Zod` · `node:test`

</details>

<details>
<summary><strong>🧠 AutoCompile</strong>: LLVM optimization-pass prediction · research and demo</summary>

<br>

Graduation research on learning LLVM optimization-pass sequences from IR, targeting one-shot inference without iterative compiler feedback.

**[Case study](https://abdok.dev/projects/autocompile) · [Demo](https://autocompile-demo.vercel.app/) · [GitHub](https://github.com/Abdo12KM/autocompile) · [Research paper](https://drive.google.com/file/d/1b4XttPmvhX6YfApg33042AL6i74VC7rH/view?usp=sharing)**

**What it demonstrates**

- Built a five-stage pipeline across **3,000 IR programs**, including size-biased collection, bounded-search supervision, fingerprint deduplication, stratified splitting, and response-only LoRA fine-tuning.
- Compared model scale, compiler-specialized pretraining, GRPO reinforcement learning, and conditioning variants.
- Reached **+1.15% guarded OverOz** with greedy one-shot inference and **+4.08%** with compiler-selected best-of-40 sampling, against a **+3.92% bounded-search teacher reference**.
- Added strict parsing, `-Oz` regression guards, LLVM verification, and Alive2 translation validation.

`Python` · `LLVM 19` · `PyTorch` · `Transformers` · `Unsloth` · `LoRA` · `vLLM` · `GRPO` · `Alive2`

</details>

<details>
<summary><strong>📸 Photography</strong>: searchable, cinematic media archive · live</summary>

<br>

A full-stack photography system for publishing, discovering, curating, and animating a catalog of more than 170 photographs.

**[Case study](https://abdok.dev/projects/photography) · [Live gallery](https://abdok.dev/photography)**

**What it demonstrates**

- Combines Vertex AI embeddings, PostgreSQL full-text search, and Gemini reranking for hybrid discovery.
- Turns selected stills into loopable Veo cinemagraphs delivered through Cloudinary and orchestrated with Inngest.
- Presents the collection in a React Three Fiber cylindrical gallery with optimized texture loading, GPU cache warming, focus interactions, and video playback.
- Includes EXIF-aware uploads, secure administration, visibility controls, rate-limited engagement, and a timezone-aware daily spotlight with Redis locking.

`Next.js 16` · `PostgreSQL` · `Gemini` · `Vertex AI` · `Veo` · `React Three Fiber` · `Cloudinary` · `Inngest`

</details>

<details>
<summary><strong>✍️ AI Publishing</strong>: repository-aware technical writing · case study</summary>

<br>

A writing system built around the idea that generated technical content should remain inspectable after publication.

**[Case study](https://abdok.dev/projects/ai-blog-generator) · [Published articles](https://abdok.dev/blog)**

**What it demonstrates**

- Coordinates Writer, Reviewer, Refiner, and Prompt Refiner agents with bounded repository-aware tool access.
- Stores file SHAs and classifies references as verified, modified, deleted, or moved as repositories change.
- Preserves AI images and Mermaid assets during refinement through diagram tokenization.
- Combines Monaco editing, live Markdown preview, code-reference drawers, diff views, autosave recovery, versioning, atomic writes, Inngest jobs, and Redis-backed progress.

`Next.js 16` · `TypeScript` · `AI SDK 7` · `Gemini` · `GitHub API` · `Monaco` · `Mermaid` · `Inngest` · `Redis`

</details>

## Capabilities

The stack changes by problem; these are the tools I repeatedly use to ship and verify systems.

<div align="center">

<!-- Keep commas encoded in srcset; raw commas break the icon list. -->
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://skillicons.dev/icons?i=nextjs%2Creact%2Cts%2Ctailwind%2Cnodejs%2Cpostgres%2Credis%2Cpython%2Cpytorch%2Cdocker%2Cgit%2Cgithub&amp;perline=6&amp;theme=dark">
  <source media="(prefers-color-scheme: light)" srcset="https://skillicons.dev/icons?i=nextjs%2Creact%2Cts%2Ctailwind%2Cnodejs%2Cpostgres%2Credis%2Cpython%2Cpytorch%2Cdocker%2Cgit%2Cgithub&amp;perline=6&amp;theme=light">
  <img src="https://skillicons.dev/icons?i=nextjs%2Creact%2Cts%2Ctailwind%2Cnodejs%2Cpostgres%2Credis%2Cpython%2Cpytorch%2Cdocker%2Cgit%2Cgithub&amp;perline=6&amp;theme=light" alt="Next.js, React, TypeScript, Tailwind CSS, Node.js, PostgreSQL, Redis, Python, PyTorch, Docker, Git, and GitHub" loading="lazy">
</picture>

</div>

- **Product UI:** Next.js, React, TypeScript, Tailwind CSS, Motion, TanStack Query, Monaco, React Three Fiber
- **Backend and data:** Node.js, ElysiaJS, PostgreSQL, Drizzle ORM, Redis, Server-Sent Events, Docker
- **AI systems:** Vercel AI SDK, Gemini, Vertex AI, tool calling, structured generation, evaluation, RAG
- **Research:** Python, PyTorch, Hugging Face, LLVM, LoRA, vLLM, Alive2
- **Quality:** Vitest, Playwright, Zod, strict TypeScript, protocol validation, deterministic checks

## Writing, experiments, and visual work

[Technical notes](https://abdok.dev/blog) · [Project case studies](https://abdok.dev/projects) · [Photography archive](https://abdok.dev/photography) · [Ask Abdo](https://abdok.dev)

## Journey

```text
2018  Medicine at Kasr Al Ainy
  │
2022  Transitioned to Computer Science
  │
2023  ECPC: 35th of 183 teams
  │
2025  SolveTHE17: 2nd of 400+ participants
  │     GDG AI Finance Hackathon: 5th of 100 teams
  │     RoboCup@Home: 3rd place
  │
2026  B.Sc. Computer Science: 3.84/4.0 CGPA
       RoboCup@Home: back-to-back 3rd place
       AutoCompile research completed
```

## Recent coding activity

<!--START_SECTION:waka-->

```txt
From: 09 July 2026 - To: 16 July 2026

Total Time: 54 hrs 31 mins

TypeScript   39 hrs 35 mins        ██████████████████░░░░░░░   71.78 %
Markdown     11 hrs 27 mins        █████▒░░░░░░░░░░░░░░░░░░░   20.77 %
CSS          1 hr 1 min            ▒░░░░░░░░░░░░░░░░░░░░░░░░   01.86 %
Bash         39 mins               ▒░░░░░░░░░░░░░░░░░░░░░░░░   01.21 %
Other        38 mins               ▒░░░░░░░░░░░░░░░░░░░░░░░░   01.16 %
```

<!--END_SECTION:waka-->

## GitHub activity

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://abdo-readme.vercel.app/api?username=abdo12km&amp;show_icons=true&amp;theme=github_dark&amp;hide_border=true&amp;count_private=true&amp;bg_color=00000000">
  <source media="(prefers-color-scheme: light)" srcset="https://abdo-readme.vercel.app/api?username=abdo12km&amp;show_icons=true&amp;theme=default&amp;hide_border=true&amp;count_private=true&amp;bg_color=00000000">
  <img src="https://abdo-readme.vercel.app/api?username=abdo12km&amp;show_icons=true&amp;theme=default&amp;hide_border=true&amp;count_private=true&amp;bg_color=00000000" alt="Abdo12KM GitHub statistics" width="495" loading="lazy">
</picture>

<br>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://streak-stats.demolab.com?user=Abdo12KM&amp;theme=github-dark-blue&amp;hide_border=true&amp;background=00000000">
  <source media="(prefers-color-scheme: light)" srcset="https://streak-stats.demolab.com?user=Abdo12KM&amp;theme=default&amp;hide_border=true&amp;background=00000000">
  <img src="https://streak-stats.demolab.com?user=Abdo12KM&amp;theme=default&amp;hide_border=true&amp;background=00000000" alt="Abdo12KM contribution streak" width="495" loading="lazy">
</picture>

<br>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-activity-graph.vercel.app/graph?username=Abdo12KM&amp;bg_color=0d1117&amp;color=c9d1d9&amp;line=58a6ff&amp;point=79c0ff&amp;area_color=58a6ff&amp;area=true&amp;hide_border=true&amp;custom_title=Contribution%20activity">
  <source media="(prefers-color-scheme: light)" srcset="https://github-readme-activity-graph.vercel.app/graph?username=Abdo12KM&amp;bg_color=ffffff&amp;color=24292f&amp;line=0969da&amp;point=54aeff&amp;area_color=0969da&amp;area=true&amp;hide_border=true&amp;custom_title=Contribution%20activity">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=Abdo12KM&amp;bg_color=ffffff&amp;color=24292f&amp;line=0969da&amp;point=54aeff&amp;area_color=0969da&amp;area=true&amp;hide_border=true&amp;custom_title=Contribution%20activity" alt="Abdo12KM contribution activity graph" width="100%" loading="lazy">
</picture>

</div>

---

## Contact

<div align="center">

### Let’s build something difficult and make it understandable.

[![Explore my work](https://img.shields.io/badge/Explore_my_work-abdok.dev-111111?style=for-the-badge&logo=vercel&logoColor=white)](https://abdok.dev/projects)
[![Start a conversation](https://img.shields.io/badge/Start_a_conversation-Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:contact@abdok.dev)

<sub>Open to full-stack, backend, product-engineering, and applied-AI opportunities.</sub>

</div>
