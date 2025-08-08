# Portfolio Roadmap — Detailed Plan

This document describes each milestone in detail:  
- **Goals** — what I want to demonstrate in this phase  
- **Scope** — the features and deliverables  
- **Definition of Done** — when I consider it complete  
- **Links** — to related repositories, issues, and milestones

---

## ✅ Milestone 0 — Meta repo & Project setup

**Goal**
- Set up a public, transparent structure to track and present all portfolio work.
- Demonstrate project planning skills before coding.

**Scope**
- Create `portfolio-roadmap` repo (this one)
- Add README.md and ROADMAP.md
- Create GitHub Project (public) with Board & Roadmap views
- Add issue templates & PR template
- Create milestones for Demo 1–4
- WIP limit: max 1 item in “In progress”

**Definition of Done**
- Public repo & project exist
- At least 1 milestone + linked issues
- README shows progress checklist
- Project Board is publicly accessible

---

## ⏳ Milestone 1 — Weather Data Explorer *(Laravel API + Nuxt)*

**Goal**
- Show API design skills, caching, and frontend data visualization.
- Demonstrate clean code structure and documentation.

**Scope**
- Laravel API:  
  - `GET /api/weather?city=&from=&to=`  
  - 24h caching with Laravel cache or Redis  
  - Filtering & pagination  
- Nuxt 3 frontend:  
  - Search/filter form  
  - Chart.js graphs  
  - Responsive & accessible layout  
- Docker/Sail or simple `make up` dev setup
- README with install steps, screenshots, and short demo video/GIF

**Definition of Done**
- API & web run locally within 5 minutes using README instructions
- Caching verified (e.g., via log or response headers)
- 3–5 meaningful commits + 1 PR with description
- Demo GIF embedded in README

---

## ⏳ Milestone 2 — Project Tracker *(Laravel + Nuxt)*

**Goal**
- Demonstrate full-stack CRUD, authentication, and role-based access.
- Showcase relational database design and accessibility in UI.

**Scope**
- Auth with Laravel Fortify/Breeze
- Roles: Admin, Member
- Models: Project, Task (status, assignee, due date)
- Activity log (events/observers)
- Tailwind UI with keyboard navigation & ARIA attributes
- CRUD operations with policies and FormRequests
- README includes ERD diagram and screenshots

**Definition of Done**
- Role-based permissions work (verified in tests)
- ERD diagram in README
- Screenshots + short demo video

---

## ⏳ Milestone 3 — Recipe Finder *(Nuxt + Algolia/Meilisearch)*

**Goal**
- Demonstrate fast, relevant search with a modern search-as-you-type experience.

**Scope**
- Seeder + indexer script (Laravel or Node)
- Faceted search (category, tags, prep time)
- Debounced search in frontend
- SSR-enabled Nuxt pages
- README includes performance notes and Lighthouse report

**Definition of Done**
- Search results update <200ms after input
- Lighthouse score ≥90 for performance and accessibility
- Live demo hosted (Vercel/Netlify) or reproducible locally

---

## ⏳ Milestone 4 — Boilerplate CLI *(PHP/Node + GitHub Actions)*

**Goal**
- Show automation and tooling skills to bootstrap projects quickly.

**Scope**
- CLI tool: `create-project` (Laravel/Nuxt skeleton with pre-configured setup)
- Scaffold `.editorconfig`, linting, Prettier, CI workflow
- Optional flags: `--with-docker`, `--with-pest`, `--with-tailwind`
- README with usage examples and GIF demo
- GitHub Actions for CI (lint + tests)

**Definition of Done**
- Running the CLI produces a working starter project
- CI badge is green in README
- At least one successful release tag (v1.0)

---

## 📌 Workflow Notes

- **One milestone at a time** — no starting a new demo until the current one is complete.
- All repos are public, with clear commit history and PRs.
- Each demo repo links back to this roadmap.

---

## 🔗 Links

- **Main Project Board:** [Public GitHub Project](https://github.com/users/<YOUR_USERNAME>/projects/1)
- **Milestones:**  
  - [Milestone 1 — Weather Data Explorer](https://github.com/<YOUR_USERNAME>/portfolio-roadmap/milestone/1)  
  - [Milestone 2 — Project Tracker](https://github.com/<YOUR_USERNAME>/portfolio-roadmap/milestone/2)  
  - [Milestone 3 — Recipe Finder](https://github.com/<YOUR_USERNAME>/portfolio-roadmap/milestone/3)  
  - [Milestone 4 — Boilerplate CLI](https://github.com/<YOUR_USERNAME>/portfolio-roadmap/milestone/4)

---
