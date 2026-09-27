# Autonomous Agent Skills Portal

> **The definitive interactive directory, pipeline simulator, and bundle compiler for 448 verified autonomous agent skills across 10 engineering domains.**  
> *Engineered to the Antigravity & Claude Code Operational Standard.*

---

## ⚡ Overview

The **Autonomous Agent Skills Portal** is an Apple-inspired, high-performance web directory and deployment workbench for autonomous AI coding agents (Antigravity, Claude Code, Cursor, Windsurf, Cline, and Codex). 

It houses **448 production-grade skills** across **10 engineering domains** and **43 granular subgroups**—ranging from full-stack architecture, 3D WebGL graphics, and automated end-to-end QA, to multi-agent boardrooms, cybersecurity red-teaming, and regulatory compliance (EU AI Act, ISO 42001, FDA QSR).

All skills are embedded with complete markdown specifications, executable instructions, prompt templates, and zero-hallucination execution contracts.

---

## ✨ Key Capabilities

### 1. 🔍 Comprehensive Skills Catalog (448 Skills)
- **Instant Search & Fuzzy Filter:** Filter skills instantaneously by slash command (`/3d-website-architect`, `/playwright-pro`, `/a11y-audit`), title, description, or keyword.
- **Granular Taxonomy:** Filter across 10 core domains and 43 sub-disciplines.
- **Dual View Modes:** Toggle between rich **Spotlight Grid** view and dense **Compact Specification List** view.
- **In-Depth Spec Reader:** Click any skill to read its complete `SKILL.md` specification, YAML frontmatter, execution workflows, and companion scripts.

### 2. 📦 Client-Side Zero-Dependency Bundle Compiler
- **In-Browser ZIP Generation:** Uses `JSZip` to compile individual skills or custom multi-skill packages directly in the browser—no backend or server processing required.
- **Instant Curated Kits:**
  - **All 448 Skills:** The full autonomous intelligence library.
  - **Engineering Kit (61):** Architecture, backend, DevOps, refactoring, and database systems.
  - **UI/UX & 3D Kit (59):** Three.js/R3F, design tokens, micro-animations, and accessibility.
  - **QA & Playwright Kit (17):** E2E testing, flaky test repair, test matrix, and performance audits.
  - **Executive C-Suite Kit (55):** Boardroom deliberation, financial modeling, legal counsel, and go-to-market strategy.
- **Interactive Cart & Floating Action Dock:** Select skills dynamically from cards or list rows; inspect your bundle in the slide-out drawer or download immediately from the floating action dock.

### 3. 📊 11 Interactive Architectural Pipelines & Flowchart Simulators
- **Mermaid.js Flowchart Engine:** Interactive architecture diagrams modeling complex agent pipelines (Engineering, Design, QA, Deep Reasoning, Executive Deliberation, AI Swarms, and Cybersecurity).
- **Step-by-Step Live Simulation:** Click any pipeline node to inspect connected commands, simulate step-by-step agent execution, and observe real-time status transitions.

### 4. 📄 Prompt Stacker & Instruction Compiler
- Select any combination of complementary skills (e.g., `senior-frontend` + `a11y-audit` + `pw`).
- Compile them into a single, unified system prompt block ready to copy and paste directly into chat sessions with Claude Code, Antigravity, or Cursor.

### 5. ⌘K Command Palette & Keyboard First Navigation
- Press <kbd>⌘K</kbd> or <kbd>Ctrl+K</kbd> anywhere to summon the floating Apple-style command palette.
- Press <kbd>/</kbd> to jump straight to the search bar.
- Full keyboard navigation with arrow keys and shortcut tags.

### 6. 🎨 Apple White Gallery Design & Motion Physics
- Clean studio white gallery surfaces (`#ffffff` / `#f5f5f7`) with ambient aurora mesh glow.
- 3D magnetic card tilt responding to pointer coordinates.
- Interactive canvas constellation particles in the hero stage.
- Built-in **Tweaks Panel** (⚙) allowing real-time customization of primary accents (`#0071e3`), motion curves, 3D tilt physics, and background particle animation.

---

## 🏛️ Domain Architecture & Taxonomy

| Domain Icon | Domain Name | Skills | Key Subgroups & Capability Highlights |
| :---: | :--- | :---: | :--- |
| 💻 | **Engineering & Architecture** | **61** | Full-Stack, Distributed Systems, Cloud Architecture (AWS/GCP/Azure), DevOps & CI/CD, Database Design, Refactoring, Tech Debt Tracker |
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

## 📂 Project Structure

```
claude-designs/
├── index.html          # Core single-page application markup & modal templates
├── app.js              # State manager, search engine, JSZip compiler, simulation runner
├── skills-data.js      # 5.1 MB self-contained database of 448 skills with full markdown
├── styles.css          # Apple Pro Keynote design system, motion physics & responsive CSS
├── server.js           # Lightweight Node.js Express static server
├── metadata.json       # Application capability and manifest metadata
├── package.json        # Project metadata and start scripts
├── CONTEXT.md          # Ground-truth project context and architectural specification
├── AGENTS.md           # Autonomous agent operating protocol & behavioral guidelines
└── brag-output/        # Keynote launch film storyboard and video production plan
```

---

## 🚀 Getting Started

### Prerequisites
- [Node.js](https://nodejs.org/) v18 or later (v20+ / v24+ recommended)

### Quick Run
1. **Clone or navigate to the repository directory:**
   ```bash
   cd claude-designs
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Start the local server:**
   ```bash
   npm run dev
   ```

4. **Open your browser:**
   Navigate to [http://localhost:3000](http://localhost:3000) (or `http://localhost:8080`).

---

## 🔌 How to Deploy Skills to Your Coding Agents

Downloaded skill bundles can be dropped into any agent environment supporting markdown-based skill systems:

### 1. Antigravity IDE / Global Gemini Config
Extract the downloaded ZIP into your central skills directory:
```bash
# Windows
C:\Users\<username>\.gemini\config\skills\<skill-name>\SKILL.md

# macOS / Linux
~/.gemini/config/skills/<skill-name>/SKILL.md
```

### 2. Claude Code
Install per-project or globally:
```bash
# In your project root
mkdir -p .claude/skills
unzip <skill-name>.zip -d .claude/skills/
```

### 3. Cursor & Windsurf
Place into your workspace configuration:
```bash
# Cursor
.cursor/skills/<skill-name>/SKILL.md

# Windsurf
.windsurf/skills/<skill-name>/SKILL.md
```

---

## 🛡️ Protocol & Safety Non-Negotiables

All skills within this directory operate under the **AGENTS.md Autonomous Agent Protocol**:
- **Zero Hallucination Standard:** Factual grounding with verified APIs and explicit source attribution.
- **No Displacive Summaries:** Full code fidelity without placeholder comments or truncations.
- **Privacy & Security First:** Zero tolerance for credential leakage or malicious exploit generation.

---

## 📄 License

Distributed under the Apache-2.0 License. See individual skills for upstream author attribution and companion documentation.