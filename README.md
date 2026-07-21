<div align="center">

# Abdelrahman Khaled

### I build systems that explain themselves.

`Full-Stack TypeScript` · `Applied AI` · `Developer Tools` · `Research`

[![Portfolio](https://img.shields.io/badge/abdok.dev-111111?style=for-the-badge&logo=vercel&logoColor=white)](https://abdok.dev)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/abdo12k)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:contact@abdok.dev)
[![Resume](https://img.shields.io/badge/Resume-2E7D32?style=for-the-badge&logo=readthedocs&logoColor=white)](https://drive.google.com/file/d/1qgQ2StAQjO3qxvWbqQyrGxJQuC3LiUk6/view?usp=sharing)

<sub>Computer Science graduate · 3.84/4.0 CGPA · New Cairo, Egypt</sub>

</div>

---

```ts
const abdok = {
  builds: ["production web systems", "grounded AI", "developer tools"],
  caresAbout: ["correctness", "clarity", "resilience", "useful products"],
  workingStyle: "own the full path from schema to production",
  rule: "evidence > adjectives",
};
```

Before Computer Science, I studied medicine for four years at Kasr Al Ainy. The domain changed; the method did not: inspect the evidence, isolate the cause, test the hypothesis, and fix the underlying system rather than its most visible symptom.

Today, I work across product architecture, authorization, databases, durable jobs, AI tool calling, evaluation, testing, and deployment.

<div align="center">

[Proof](#proof-not-adjectives) · [Projects](#project-constellation) · [Engineering Palette](#engineering-palette) · [Timeline](#the-path-here)

</div>

## Proof, not adjectives

| Signal                       |                                 Evidence | Project                                               |
| ---------------------------- | ---------------------------------------: | ----------------------------------------------------- |
| Authorization depth          |              **65 granular permissions** | [Automart](https://abdok.dev/projects/automart)       |
| Full-stack test suite        | **662 passing Vitest tests / 168 files** | [Automart](https://abdok.dev/projects/automart)       |
| AI-system test suite         |  **263 passing Vitest tests / 61 files** | [Mitos](https://abdok.dev/projects/mitos)             |
| Compiler optimization result |                **+4.08% guarded OverOz** | [AutoCompile](https://abdok.dev/projects/autocompile) |
| Hybrid media discovery       |             **170+ indexed photographs** | [Photography](https://abdok.dev/projects/photography) |
| Academic foundation          |                        **3.84/4.0 CGPA** | B.Sc. Computer Science                                |

## Project constellation

| System                                                            | What it does                              | Defining engineering idea                                |
| ----------------------------------------------------------------- | ----------------------------------------- | -------------------------------------------------------- |
| **[Automart](https://abdok.dev/projects/automart)**               | Runs dealership operations                | Hybrid authorization and resilient infrastructure        |
| **[Mitos](https://abdok.dev/projects/mitos)**                     | Explains unfamiliar repositories          | Evidence-grounded execution tracing                      |
| **[Ask Abdo](https://abdok.dev/projects/ask-abdo)**               | Answers questions about my work           | Server-owned evidence and validated output               |
| **[AutoCompile](https://abdok.dev/projects/autocompile)**         | Predicts LLVM optimization passes         | One-shot pass prediction from bounded-search supervision |
| **[Photography](https://abdok.dev/projects/photography)**         | Publishes and discovers visual work       | Semantic search and cinematic 3D presentation            |
| **[AI Publishing](https://abdok.dev/projects/ai-blog-generator)** | Turns repositories into technical writing | Context-first generation and SHA drift detection         |

<details open>
<summary><strong>🚗 <a href="https://abdok.dev/projects/automart">Automart</a>: dealership operations under real constraints</strong></summary>

<br>

> A full-stack operations platform spanning staff, customers, vehicles, inventory, communication, reporting, and AI-assisted workflows.

[Case study](https://abdok.dev/projects/automart) · [Public site](https://automart.vercel.app) · Repository private

- **Authorization:** 65 database-synchronized permissions with role defaults, per-member allow/deny overrides, contextual server checks, and audit logs.
- **AI:** Streaming assistant with sandboxed tools, structured sources, permission-aware SQL reporting, and field-level redaction.
- **Reliability:** Redis caching with 250 ms racing timeouts, a 60-second circuit breaker, PostgreSQL fallback paths, and cross-instance coordination during Redis outages.
- **Domain engineering:** Ledger-based stock adjustments, reorder alerts, a local Land Rover VIN decoder with NHTSA fallback, and bilingual AI-assisted announcements.
- **Security and quality:** JOSE-signed JWT sessions in HttpOnly cookies, PBKDF2 password hashing with SHA-256, AES-GCM credential encryption, strict TypeScript checks, and **662 passing tests across 168 files**.

`Next.js 16` `React 19` `TypeScript` `PostgreSQL` `Drizzle` `Redis` `AI SDK` `Gemini` `Vitest`

</details>

<details>
<summary><strong>⚡ <a href="https://abdok.dev/projects/mitos">Mitos</a>: from repository question to verified execution trace</strong></summary>

<br>

> An AI developer tool that converts natural-language questions about GitHub repositories into commit-pinned, shareable execution knowledge.

[Case study](https://abdok.dev/projects/mitos) · [Live](https://mitos.abdok.dev) · Repository private

- Builds synchronized **FlowBoard and Mermaid diagrams**, Monaco source views, timelines, and narrative steps.
- Uses bounded repository exploration, evidence extraction, trace planning, and structured drafting, falling back to a symbol graph when direct exploration is insufficient.
- Verifies file paths, line ranges, snippets, graph connections, prompt coverage, and semantic quality before finalizing a trace.
- Runs through durable Inngest stages with cancellation, concurrency control, retry-safe execution guards, artifact offloading, optional Redis locks, and SSE progress.
- Protects repositories with trace-scoped access, encrypted OAuth tokens, archived source access, binary rejection, and Mermaid/SVG sanitization.
- Backed by **263 passing Vitest tests across 61 files**, plus Playwright coverage for the landing page and workspace demo.

`Next.js 16` `ElysiaJS` `Better Auth` `PostgreSQL` `Inngest` `Monaco` `Mermaid` `Gemini` `DeepSeek`

</details>

<details>
<summary><strong>🦇 <a href="https://abdok.dev/projects/ask-abdo">Ask Abdo</a>: a portfolio assistant with a trust boundary</strong></summary>

<br>

> A correctness-first assistant embedded in abdok.dev, not a generic chatbot placed beside a portfolio.

[Case study](https://abdok.dev/projects/ask-abdo) · [Live](https://abdok.dev)

- Rebuilds trusted public evidence for every request instead of trusting browser history or client-produced facts.
- Lets the model select bounded stable keys while the server owns canonical project, article, photo, resume, social, and contact data.
- Buffers complete model attempts and releases them only after links, schema, terminal plan, and completion state pass validation.
- Rehydrates saved resources from fresh public data rather than preserving stale snapshots.
- Includes the **Batwick** interface with route-aware starters, local history, inline actions, follow-up suggestions, recruiter shortcuts, and a conversation-level resource library.
- Runs real-model production-path evaluations with prompt traces, provenance hashes, protocol invariants, and catalog-coverage checks.

`Next.js 16` `React 19` `TypeScript` `Vercel AI SDK` `Gemini` `Zod` `node:test`

</details>

<details>
<summary><strong>🧠 <a href="https://abdok.dev/projects/autocompile">AutoCompile</a>: can an LLM learn a compiler optimizer?</strong></summary>

<br>

> Graduation research on learning LLVM optimization pass sequences from IR, targeting one-shot inference without iterative compiler feedback.

[Case study](https://abdok.dev/projects/autocompile) · [Demo](https://autocompile-demo.vercel.app/) · [GitHub](https://github.com/Abdo12KM/autocompile) · [Research paper](https://drive.google.com/file/d/1b4XttPmvhX6YfApg33042AL6i74VC7rH/view?usp=sharing)

- Built a five-stage pipeline covering size-biased collection, bounded-search supervision, exact-IR fingerprint deduplication, stratified splitting, and response-only LoRA fine-tuning across **3,000 IR programs**.
- Compared model scale, compiler-specialized pretraining, GRPO reinforcement learning, and conditioning variants.
- Used held-out evaluation with **zero cross-split exact-IR fingerprint overlap**.
- Reached **+1.15% guarded OverOz** with greedy one-shot inference and **+4.08%** with compiler-selected best-of-40 sampling, against a **+3.92% bounded-search teacher reference**.
- Found that strong candidate sequences existed in the learned distribution, while deterministic decoding repeatedly collapsed to a small template set.
- Added strict parsing, `-Oz` regression guards, LLVM verification, and Alive2 translation validation.

`Python` `LLVM 19` `PyTorch` `Transformers` `Unsloth` `LoRA` `vLLM` `GRPO` `Alive2`

</details>

<details>
<summary><strong>📸 <a href="https://abdok.dev/projects/photography">Photography</a>: an archive that can search, move, and remember</strong></summary>

<br>

> A full-stack photography system for publishing, discovering, curating, and animating a personal catalog of 170+ photographs.

[Case study](https://abdok.dev/projects/photography) · [Live gallery](https://abdok.dev/photography)

- Combines Vertex AI embeddings, PostgreSQL full-text search, and Gemini reranking for hybrid discovery.
- Uses Gemini for titles, descriptions, tags, and metadata enrichment.
- Turns selected stills into loopable Veo cinemagraphs delivered through Cloudinary and orchestrated with Inngest.
- Presents the collection in a React Three Fiber cylindrical gallery with optimized texture loading, GPU cache warming, focus interactions, and video playback.
- Runs a timezone-aware daily spotlight with fair rotation, AI-generated themes, overrides, and Redis distributed locking.
- Includes EXIF-aware uploads, secure administration, visibility controls, loves, views, and rate-limited anonymous engagement.

`Next.js 16` `PostgreSQL` `Gemini` `Vertex AI` `Veo` `React Three Fiber` `Cloudinary` `Inngest`

</details>

<details>
<summary><strong>✍️ <a href="https://abdok.dev/projects/ai-blog-generator">AI Publishing</a>: technical writing that stays attached to the code</strong></summary>

<br>

> A repository-aware writing system built around the idea that generated technical content should remain inspectable after publication.

[Case study](https://abdok.dev/projects/ai-blog-generator) · [Published articles](https://abdok.dev/blog)

- Coordinates Writer, Reviewer, Refiner, and Prompt Refiner agents with repository-aware tool access.
- Loads the repository tree and selected source files before generation, then allows bounded retrieval of additional files.
- Stores file SHAs and classifies references as verified, modified, deleted, or moved when the repository changes.
- Preserves AI-image and Mermaid assets during refinement through diagram tokenization.
- Pairs Monaco editing, live Markdown preview, code-reference drawers, diff views, autosave recovery, and visibility controls.
- Supports version pinning and pruning, atomic writes, Inngest jobs, Redis-backed progress, and double-opt-in notifications.

`Next.js 16` `TypeScript` `AI SDK 7` `Gemini` `GitHub API` `Monaco` `Mermaid` `Inngest` `Redis`

</details>

## Engineering palette

| Layer                | Tools I reach for                                                                                  |
| -------------------- | -------------------------------------------------------------------------------------------------- |
| **Product UI**       | Next.js · React · TypeScript · Tailwind CSS · Motion · TanStack Query · Monaco · React Three Fiber |
| **Backend and data** | Node.js · ElysiaJS · PostgreSQL · Drizzle ORM · Redis · Server-Sent Events · Docker                |
| **AI systems**       | Vercel AI SDK · Gemini · Vertex AI · tool calling · structured generation · evaluation · RAG       |
| **Research**         | Python · PyTorch · Hugging Face · LLVM · LoRA · vLLM · Alive2                                      |
| **Quality**          | Vitest · Playwright · Zod · strict TypeScript · protocol validation · deterministic checks         |

## The path here

```text
2018  Medicine at Kasr Al Ainy
  |
2022  Transition to Computer Science
  |
2023  ECPC: 35th / 183 teams
  |
2025  SolveTHE17: 2nd / 400+ participants
  |     GDG AI Finance Hackathon: 5th / 100 teams
  |     RoboCup@Home: 3rd place
  |
2026  B.Sc. Computer Science: 3.84/4.0 CGPA
       RoboCup@Home: back-to-back 3rd place
       AutoCompile research completed
```

<!-- ## Development signal

<div align="center">
  <img height="180em" src="https://abdo-readme.vercel.app/api?username=abdo12km&show_icons=true&theme=dark&hide_border=true&count_private=true" alt="Abdelrahman's GitHub statistics">
</div> -->

<!--START_SECTION:waka-->

```txt
From: 13 July 2026 - To: 20 July 2026

Total Time: 55 hrs 55 mins

TypeScript   41 hrs 41 mins        ██████████████████▒░░░░░░   73.94 %
Markdown     9 hrs 16 mins         ████░░░░░░░░░░░░░░░░░░░░░   16.45 %
CSS          2 hrs 25 mins         █░░░░░░░░░░░░░░░░░░░░░░░░   04.32 %
Text         1 hr 13 mins          ▓░░░░░░░░░░░░░░░░░░░░░░░░   02.17 %
JavaScript   28 mins               ▒░░░░░░░░░░░░░░░░░░░░░░░░   00.83 %
```

<!--END_SECTION:waka-->

---

<div align="center">

### Let’s build something difficult, and make it understandable.

[![Explore my work](https://img.shields.io/badge/Explore_my_work-111111?style=for-the-badge&logo=vercel&logoColor=white)](https://abdok.dev/projects)
[![Connect](https://img.shields.io/badge/Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/abdo12k)
[![Start a conversation](https://img.shields.io/badge/Start_a_conversation-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:contact@abdok.dev)

<sub>Open to full-stack, backend, product-engineering, and applied-AI opportunities.</sub>

</div>
