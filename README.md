# 💫 About Me

<div align="center">

👋 **Hi, I'm Aman Kumar Singh**  
🚀 **Full-Stack Engineer | React · TypeScript · NestJS · AI/LLM Integration**

✨ Building fast, scalable & maintainable systems — from pixel-perfect UIs to production-grade backends ✨

</div>

---

## 👨‍💻 About Me

I'm a **Full-Stack Software Engineer with 4+ years of experience** building high-performance web applications and production-grade backend systems using **React.js**, **TypeScript**, **NestJS**, and **PostgreSQL**.

I started as a frontend engineer and have grown into owning entire systems end-to-end — from component libraries and micro-frontends to real-time WebSocket gateways, multi-provider AI pipelines, and published npm packages.

Recent highlights:
- **40% performance boost** on a 5-lakh-record supply chain dashboard via virtualization + code splitting
- **60% build time reduction** by migrating CRA → Vite + TypeScript
- **90%+ unit test coverage** enabling high-confidence releases
- Built a **multi-tenant AI-powered customer support platform** (Meridian) solo — dual React SPAs, NestJS REST API, 10+ shared packages
- Published an **open-source npm CLI** (`@bug-intelligence/sourcemap-upload`) used in CI/CD pipelines

---

## 🧠 Technical Skills

### Frontend
![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![Next.js](https://img.shields.io/badge/Next-black?style=for-the-badge&logo=next.js&logoColor=white)
![Redux](https://img.shields.io/badge/redux-%23593d88.svg?style=for-the-badge&logo=redux&logoColor=white)
![React Router](https://img.shields.io/badge/React_Router-CA4245?style=for-the-badge&logo=react-router&logoColor=white)
![MUI](https://img.shields.io/badge/MUI-%230081CB.svg?style=for-the-badge&logo=mui&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white)
![SASS](https://img.shields.io/badge/SASS-hotpink.svg?style=for-the-badge&logo=SASS&logoColor=white)
![Framer Motion](https://img.shields.io/badge/Framer_Motion-black?style=for-the-badge&logo=framer&logoColor=white)

### Backend & Runtime
![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)
![NestJS](https://img.shields.io/badge/nestjs-%23E0234E.svg?style=for-the-badge&logo=nestjs&logoColor=white)
![Socket.io](https://img.shields.io/badge/Socket.io-black?style=for-the-badge&logo=socket.io&badgeColor=010101)
![.NET](https://img.shields.io/badge/.NET-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)

### Databases & Storage
![PostgreSQL](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/redis-%23DD0031.svg?style=for-the-badge&logo=redis&logoColor=white)
![SQL Server](https://img.shields.io/badge/SQL_Server-%23CC2927.svg?style=for-the-badge&logo=microsoftsqlserver&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white)

### AI / LLM
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)
![Anthropic](https://img.shields.io/badge/Anthropic_Claude-CC785C?style=for-the-badge&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logoColor=white)

### Tooling & DevOps
![Vite](https://img.shields.io/badge/vite-%23646CFF.svg?style=for-the-badge&logo=vite&logoColor=white)
![Webpack](https://img.shields.io/badge/webpack-%238DD6F9.svg?style=for-the-badge&logo=webpack&logoColor=black)
![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)
![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)
![NPM](https://img.shields.io/badge/npm-%23CB3837.svg?style=for-the-badge&logo=npm&logoColor=white)
![Jest](https://img.shields.io/badge/-jest-%23C21325?style=for-the-badge&logo=jest&logoColor=white)
![Vitest](https://img.shields.io/badge/-Vitest-252529?style=for-the-badge&logo=vitest&logoColor=FCC72B)
![Azure](https://img.shields.io/badge/azure-%230072C6.svg?style=for-the-badge&logo=microsoftazure&logoColor=white)

---

## 📌 Featured Projects

### [Meridian — Customer Support Platform](https://github.com/AmanSingh544/meridian)
> React · TypeScript · Redux Toolkit · Socket.io · NestJS · PostgreSQL · pgvector · BullMQ · Redis

A **multi-tenant AI-powered customer support platform** built end-to-end as a solo project.

- Dual React SPAs (customer portal + agent console) backed by a single NestJS REST API
- Monorepo with **10+ shared internal packages** — design system (`@3sc/ui`), RBAC engine, RTK Query API layer
- **Multi-provider LLM gateway** (OpenRouter, Anthropic, OpenAI, Groq) with automatic fallback chains for ticket classification, priority suggestion, and AI reply generation
- **Real-time** Socket.io WebSocket gateway with polling fallback — instant ticket events across both portals
- **Semantic search** via pgvector embeddings in PostgreSQL
- Role-based access control across 5 roles enforced on both frontend routes and backend guards

---

### [JinAi — Bug Intelligence Platform](https://github.com/AmanSingh544/JinAi-BugIntelligence)
> TypeScript · React · NestJS · BullMQ · PostgreSQL · pgvector · Redis · Chrome Extensions API · Anthropic Claude SDK

A **full-stack AI-powered browser observability system** built solo.

- Chrome extension captures JS errors, unhandled Promise rejections, and network failures in real time — batching events via a service worker to a NestJS ingest API
- **6-stage BullMQ pipeline**: ingest → error detection → AI analysis → semantic clustering → rule evaluation → dispatch — with fingerprint-based deduplication at the DB constraint level
- **Anthropic Claude (Haiku)** generates structured bug summaries; pgvector KNN cosine similarity auto-clusters related errors across sessions
- React + Vite dashboard with **real-time SSE-driven live updates**, bulk triage, severity badges, and Framer Motion animations

---

### [@bug-intelligence/sourcemap-upload — npm CLI Package](https://www.npmjs.com/package/@bug-intelligence/sourcemap-upload)
> Node.js · TypeScript · CLI · npm

An **open-source npm CLI** for the JinAi ecosystem — automates sourcemap uploads in CI/CD pipelines.

- Discovers all `*.map` files post-build, creates versioned releases on the Bug Intelligence API
- **Auto-detects commit SHA** from Vercel, GitHub Actions, Cloudflare Pages, and Netlify — with a git/timestamp fallback
- Supports `--dry-run`, `--quiet`, full flag/env-var parity — zero config for most setups
- Works with **Vite, Webpack, Next.js, and Rollup** builds

---

## 🔭 Currently Working On
- AI-integrated full-stack systems with multi-provider LLM gateways
- Real-time WebSocket architectures
- Vector embeddings and semantic search with pgvector

---

## 🌱 Currently Learning
- Advanced LLM patterns (RAG, tool use, agent loops)
- Data Structures & Algorithms
- System design at scale

---

## 💬 Ask Me About
- React + TypeScript architecture & performance
- Full-stack NestJS + Prisma + PostgreSQL systems
- Multi-provider AI/LLM integration
- Real-time systems with WebSockets
- Micro-frontend architecture
- Open-source npm package development

---

## 📫 Connect With Me

[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/aman-singh-kumar/)
[![Email](https://img.shields.io/badge/Email-D14836?logo=gmail&logoColor=white)](mailto:amankumarsinghamar@gmail.com)
[![GitHub](https://img.shields.io/badge/github-%23121011.svg?logo=github&logoColor=white)](https://github.com/AmanSingh544)

---

## ✍️ Random Dev Quote
![](https://quotes-github-readme.vercel.app/api?type=horizontal&theme=radical)

---

## ⚡ Fun Fact
I'm a **writer & shayar** — I enjoy expressing ideas through words as much as through code 😊

<div align="center">

✨ **Clean code. Fast interfaces. Meaningful systems.** ✨

</div>

---

[![](https://visitcount.itsvg.in/api?id=AmanSingh544&icon=0&color=0)](https://visitcount.itsvg.in)
