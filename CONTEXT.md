# CONTEXT.md — Autonomous Agent Skills Portal Ground-Truth Context

> **Status:** Canonical Project Context & Operational Ground Truth  
> **Repository:** `claude-design-studio`  
> **Core Mission:** The definitive interactive directory, pipeline simulator, and bundle compiler for 448 verified autonomous agent skills across 10 engineering domains.  
> **Anti-Hallucination Directive:** All autonomous agents interacting with this repository MUST ground their assumptions, file structures, schemas, and design constraints in this document.

---

## 1. Project Overview & System Vision

The **Autonomous Agent Skills Portal** is an Apple-inspired, high-performance web directory and deployment workbench engineered for modern autonomous AI coding agents (Antigravity, Claude Code, Cursor, Windsurf, Cline, and Codex).

It centralizes **448 production-grade skills** organized across **10 engineering domains** and **43 granular sub-disciplines**—ranging from full-stack architecture, 3D WebGL graphics, and automated end-to-end QA, to multi-agent boardrooms, cybersecurity red-teaming, and regulatory compliance (EU AI Act, ISO 42001, FDA QSR).

All skills are backed by complete markdown specifications (`SKILL.md`), YAML frontmatter, execution workflows, prompt templates, companion scripts, and zero-hallucination execution contracts.

---

## 2. Core Capabilities & Architectural Pillars

### 2.1 🔍 Comprehensive Skills Catalog (448 Skills)
- **Instant Search & Fuzzy Filter:** Real-time query matching by slash command (e.g., `/3d-website-architect`, `/playwright-pro`, `/a11y-audit`), title, keywords, or domain tags.
- **Granular Taxonomy Filtering:** Instant narrowing across 10 primary domains and 43 sub-disciplines.
- **Dual View Modes:**
  - **Spotlight Grid View:** Visual card layout with metadata tags, domain badges, and interactive action buttons.
  - **Compact Specification List View:** High-density data table for rapid exploration and bulk selection.
- **In-Depth Spec Reader:** Modal reader displaying full `SKILL.md` content, execution instructions, companion code, and prompt parameters.

### 2.2 📦 Client-Side Zero-Dependency Bundle Compiler
- **In-Browser ZIP Generation:** Uses `JSZip` client-side to package selected skills or entire curated bundles into downloadable `.zip` archives with zero backend dependencies.
- **Pre-Packaged Curated Kits:**
  - **All 448 Skills:** The entire autonomous intelligence library.
  - **Engineering & Architecture Kit (61 skills):** Architecture, backend systems, DevOps, refactoring, database design.
  - **UI/UX & 3D Kit (59 skills):** Three.js/R3F, design tokens, micro-interactions, WCAG 2.2 accessibility.
  - **QA & Playwright Kit (17 skills):** E2E testing, flaky test repair, test matrix, BrowserStack/TestRail integration.
  - **Executive C-Suite Kit (55 skills):** Multi-role boardroom deliberation, financial modeling, legal MSA review, GTM strategy.
- **Interactive Cart & Floating Action Dock:** Real-time cart drawer with badge counters and instant single-click bundle export.

### 2.3 📊 11 Interactive Architectural Pipelines & Flowchart Simulators
- **Mermaid.js Flowchart Engine:** Renders dynamic architecture diagrams modeling multi-step agent workflows (Engineering, Design Systems, E2E QA, Deep Reasoning, Executive Deliberation, AI Swarms, and Cybersecurity).
- **Step-by-Step Live Simulation:** Interactive node selection to inspect connected agent commands, simulate step-by-step state transitions, and observe live status updates.

### 2.4 📄 Prompt Stacker & Instruction Compiler
- Combines complementary skills (e.g., `senior-frontend` + `a11y-audit` + `pw`) into a consolidated, conflict-free system prompt ready to copy directly into agent session prompts.

### 2.5 ⌘K Command Palette & Keyboard Navigation
- Global keyboard shortcut `<kbd>⌘K</kbd>` / `<kbd>Ctrl+K</kbd>` launches the floating Apple-style command palette.
- Quick navigation shortcuts: `/` to jump to search, `Esc` to close overlays, arrow keys for navigation.

### 2.6 🎨 Apple White Gallery Design & Motion Physics
- Clean studio white aesthetic (`#ffffff` / `#f5f5f7`) with ambient aurora mesh glow.
- 3D magnetic card tilt with cursor physics.
- Interactive canvas constellation particles in the hero stage.
- Built-in **Tweaks Panel** (⚙) allowing real-time runtime adjustments of theme accents (`#0071e3`), animation physics, tilt parameters, and particle density.

---

## 3. Domain Architecture & Taxonomy (10 Domains, 448 Skills)

| Icon | Domain Name | Skills Count | Key Subgroups & Representative Capabilities |
| :---: | :--- | :---: | :--- |
| 💻 | **Engineering & Architecture** | **61** | Full-Stack, Distributed Systems, Cloud Architecture (AWS / GCP / Azure), DevOps & CI/CD, Database Design, Tech Debt Tracker |
| 🎨 | **UI/UX, 3D & Design Systems** | **59** | Three.js & WebGL, Design Tokens, Tailwind/CSS Architecture, Micro-Interactions, WCAG 2.2 Accessibility (`a11y-audit`), Screenshot-to-Code |
| 🧪 | **QA & Playwright Automation** | **17** | End-to-End Testing (`playwright-pro`), Flaky Test Repair, Test Coverage Gaps, BrowserStack Matrix, TestRail Synchronization |
| 👔 | **Executive & C-Suite Advisors** | **55** | Multi-Role Boardroom (`/cs:boardroom`), Founder Mode, CFO Financial Runway, CPO Roadmap Discovery, General Counsel MSA Review |
| 🛡️ | **Cybersecurity & Red Team** | **38** | Threat Modeling, Red Teaming, Cloud Posture Assessment, Incident Response (SEV1-4), SOC 2 Compliance, Secrets Management |
| 🧠 | **Deep Reasoning & Strategy** | **42** | Evidence-First Deep Reading (`/deepread`), Scenario War Room, Hard Call Regret Minimization, First-Principles Stress Testing |
| 📈 | **Growth, Marketing & Product** | **64** | Multi-Touch Attribution, A/B Testing, Technical SEO Audit, SaaS Metrics Coaching, Copywriting, International Expansion |
| 🤖 | **AI Swarms & Autoresearch** | **36** | Autonomous Experiment Loops (`/ar:loop`), Worktree Swarm Orchestration (`hivemind`), Multi-Model Cross-Eval, AgentHub |
| 📊 | **Data Engineering & Cloud** | **44** | Snowflake Pipelines, BigQuery Warehousing, RAG Architectures, dbt Transformations, Observability & SLI/SLO Design |
| ⚖️ | **Regulatory & QMS Compliance** | **32** | EU AI Act Readiness (`ai-act-readiness`), ISO 42001 AIMS Audit, ISO 13485 QMS, FDA 21 CFR 820 QSR, GDPR Audit |

---

## 4. Target Project Layout & File Mapping

```
claude-designs/ (or repo root)
├── index.html          # Core single-page application markup & modal templates
├── app.js              # State manager, search engine, JSZip compiler, simulation runner
├── skills-data.js      # Self-contained database of 448 skills with full markdown content
├── styles.css          # Apple Pro Keynote design system, motion physics & responsive CSS
├── server.js           # Lightweight Node.js Express static server
├── metadata.json       # Application capability and manifest metadata
├── package.json        # Project metadata and start scripts
├── CONTEXT.md          # Ground-truth project context and architectural specification
├── AGENTS.md           # Autonomous agent operating protocol & behavioral guidelines
└── brag-output/        # Keynote launch film storyboard and video production plan
```

---

## 5. Agent Operational Standards & Ground-Truth Rules

1. **Strict Context Adherence:** Do not invent skills, domains, or capabilities outside the 10 domains and 448 skills cataloged in this project.
2. **Zero-Hallucination API Design:** When modifying or writing code for the portal, use standard Web APIs, JSZip, and Mermaid.js without assuming non-existent dependencies or unverified endpoints.
3. **No Displacive Summaries or Code Truncation:** Preserve complete markdown specifications and complete source code implementations.
4. **Git Protocol:** Never commit changes (`git commit`) without explicit user instruction.
5. **Storage Constraints:** Use in-memory state or `window.storage` where applicable; avoid unhandled `localStorage` calls in sandboxed environments.
