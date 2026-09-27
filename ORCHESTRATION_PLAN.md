# Multi-Agent Parallel Execution Plan & Prompt Roster

> **Target Project:** Autonomous Agent Skills Portal (`claude-design-studio`)  
> **Ground Truth Document:** [`CONTEXT.md`](file:///C:/Users/hp/.coord/repos/bdabd89a-ddbb-46f9-b241-4888bce22a24/claude-design-studio/CONTEXT.md) & [`AGENTS.md`](file:///C:/Users/hp/.coord/repos/bdabd89a-ddbb-46f9-b241-4888bce22a24/claude-design-studio/AGENTS.md)  
> **Zero-Conflict Principle:** Strict file ownership and modular API boundaries. No two agents write to the same file.

---

## 🗺️ Parallel Workload Matrix & Ownership

| Agent ID | Role | Exclusive File Ownership | Assigned Global Skills |
| :--- | :--- | :--- | :--- |
| **Agent 1** | **Data & Skills Extraction Architect** | `skills-data.js`, `scripts/extract-skills.js` | `write-a-skill`, `data-quality-auditor`, `universal-scraping-architect` |
| **Agent 2** | **Design System & Motion Physics (CSS)** | `styles.css` | `ui-ux-pro-max`, `ui-design-system`, `brand`, `design-system` |
| **Agent 3** | **Core UI Markup & Modals (HTML)** | `index.html` | `senior-frontend`, `a11y-audit` |
| **Agent 4** | **Client Core, Search & Zip Compiler (JS)** | `app.js` | `senior-frontend`, `minimalist`, `playwright-pro` |
| **Agent 5** | **Pipeline Diagrams & Simulation Engine** | `pipelines-data.js`, `pipeline-simulator.js` | `agent-protocol`, `workflow-builder`, `boardroom`, `hivemind` |
| **Agent 6** | **Server, Manifests & Launch Packaging** | `package.json`, `server.js`, `metadata.json`, `brag-output/storyboard.json` | `ci-cd-pipeline-builder`, `brag`, `senior-devops` |

---

## 📋 Individual Agent Task Briefings & Prompts

---

### 🤖 Agent 1: Data & Skills Extraction Architect

- **Assigned Local Skills:**
  - `C:\Users\hp\.gemini\config\skills\write-a-skill\SKILL.md`
  - `C:\Users\hp\.gemini\config\skills\data-quality-auditor\SKILL.md`
  - `C:\Users\hp\.gemini\config\skills\universal-scraping-architect\SKILL.md`
- **Exclusive File Ownership:** `skills-data.js`, `scripts/extract-skills.js`
- **Non-Conflicting Boundary:** Produces only global data object `window.SKILLS_DATA = [...]` and extraction scripts.

#### 📝 Agent 1 Prompt:
```markdown
You are Agent 1: Data & Skills Extraction Architect for the Autonomous Agent Skills Portal.
Your task is to build `scripts/extract-skills.js` and generate the comprehensive `skills-data.js` database.

Ground-Truth Context: Refer to CONTEXT.md and AGENTS.md.
Global Skills Reference: C:\Users\hp\.gemini\config\skills\

Requirements:
1. Scan all 400+ skill folders in C:\Users\hp\.gemini\config\skills\ and builtin skills.
2. For each skill, parse YAML frontmatter (name, description) and full SKILL.md body.
3. Categorize each skill into one of the 10 canonical domains and 43 subgroups defined in CONTEXT.md:
   - Engineering & Architecture (61)
   - UI/UX, 3D & Design Systems (59)
   - QA & Playwright Automation (17)
   - Executive & C-Suite Advisors (55)
   - Cybersecurity & Red Team (38)
   - Deep Reasoning & Strategy (42)
   - Growth, Marketing & Product (64)
   - AI Swarms & Autoresearch (36)
   - Data Engineering & Cloud (44)
   - Regulatory & QMS Compliance (32)
4. Tag curated kit memberships: 'all', 'engineering', 'ui-3d', 'qa-playwright', 'c-suite'.
5. Output window.SKILLS_DATA = [ { id, name, slug, domain, domainIcon, subgroup, description, triggers: [], markdownContent, kitTags: [] }, ... ] in `skills-data.js`.
6. Ensure zero missing fields and zero syntax errors. Do not edit any other file.
```

---

### 🎨 Agent 2: Design System & Motion Physics Engineer

- **Assigned Local Skills:**
  - `C:\Users\hp\.gemini\config\skills\ui-ux-pro-max\SKILL.md`
  - `C:\Users\hp\.gemini\config\skills\ui-design-system\SKILL.md`
  - `C:\Users\hp\.gemini\config\skills\design-system\SKILL.md`
  - `C:\Users\hp\.gemini\config\skills\brand\SKILL.md`
- **Exclusive File Ownership:** `styles.css`
- **Non-Conflicting Boundary:** Exclusive owner of styling, CSS variables, keyframe animations, responsive grid/table media queries.

#### 📝 Agent 2 Prompt:
```markdown
You are Agent 2: Design System & Motion Physics Engineer for the Autonomous Agent Skills Portal.
Your task is to build `styles.css` implementing the Apple Pro Keynote aesthetic.

Ground-Truth Context: Refer to CONTEXT.md and AGENTS.md (Section 6: No AI slop, no generic gradients).

Design Directives:
1. Palette: Apple Pro Studio White (#ffffff, #f5f5f7, #e8e8ed, text #1d1d1f, muted #86868b, accent #0071e3, success #34c759, border #d2d2d7).
2. Typography: SF Pro Display / Inter font stack, crisp tracking, balanced visual hierarchy.
3. Motion & Physics: 3D magnetic card tilt on hover, smooth spring bezier curves (cubic-bezier(0.16, 1, 0.3, 1)), ambient aurora mesh backdrop glow.
4. Component Styles:
   - Hero constellation canvas wrapper and animated title gradient (subtle metallic/slate).
   - Sticky frosted glass navigation & search bar (backdrop-filter: blur(20px)).
   - Domain filter pills with active state indicators.
   - Dual view modes: Spotlight Grid (3D cards) and Compact Specification Table (dense, zebra-striped, clean borders).
   - Slide-out Cart Drawer with badge counter & floating bottom action dock.
   - Modals: ⌘K Command Palette, In-Depth Spec Reader, Prompt Stacker, Pipeline Simulator, and Tweaks Panel (⚙).
5. Accessibility: Minimum 44px touch targets, high contrast ratios, reduced motion media queries.
Do not edit any file other than `styles.css`.
```

---

### 🖥️ Agent 3: Core UI Markup & Modal Architecture (HTML)

- **Assigned Local Skills:**
  - `C:\Users\hp\.gemini\config\skills\senior-frontend\SKILL.md`
  - `C:\Users\hp\.gemini\config\skills\a11y-audit\SKILL.md`
- **Exclusive File Ownership:** `index.html`
- **Non-Conflicting Boundary:** Exclusive owner of HTML5 markup structure and CDN script loading.

#### 📝 Agent 3 Prompt:
```markdown
You are Agent 3: Core UI Markup & Modal Architect for the Autonomous Agent Skills Portal.
Your task is to build `index.html` as a single-page application.

Ground-Truth Context: Refer to CONTEXT.md and AGENTS.md.

Markup Requirements:
1. CDN Script Includes:
   - JSZip (v3.10.1)
   - Mermaid.js (v10+)
   - Marked.js (for markdown spec rendering)
   - Lucide Icons
   - Canvas-Confetti
2. Header & Hero Stage:
   - Constellation particle `<canvas id="hero-canvas">`.
   - Title, badge counter ("448 Verified Skills", "10 Domains"), quick action CTAs (Curated Kits, ⌘K trigger, Pipeline Simulator).
3. Filter & Search Control Bar (Sticky Frosted Bar):
   - Search input with slash command badge and keyboard hint (<kbd>/</kbd> or <kbd>⌘K</kbd>).
   - View mode toggle buttons (Spotlight Grid vs. Compact Spec List).
   - Domain horizontal scrolling pill bar with icons.
4. Main Content Area:
   - Grid container `<div id="skills-grid">`
   - Table container `<div id="skills-table">`
   - Empty state illustration and loading skeletons.
5. Interactive Overlays & Modals:
   - `<div id="cart-drawer">`: Slide-out bundle compiler drawer with kit shortcuts.
   - `<div id="floating-dock">`: Floating quick-download bar when items are selected.
   - `<div id="spec-modal">`: Detailed SKILL.md reader with copy buttons and companion scripts tab.
   - `<div id="prompt-stacker-modal">`: Merged system prompt builder.
   - `<div id="pipeline-modal">`: Interactive Mermaid.js diagram viewer and step simulator.
   - `<div id="command-palette">`: ⌘K quick switcher.
   - `<div id="tweaks-modal">`: Real-time style/motion configurator.
6. Script Links: `skills-data.js`, `pipelines-data.js`, `pipeline-simulator.js`, `app.js`.
Do not edit any file other than `index.html`.
```

---

### ⚡ Agent 4: Client Core, Search & Zip Compiler (JS)

- **Assigned Local Skills:**
  - `C:\Users\hp\.gemini\config\skills\senior-frontend\SKILL.md`
  - `C:\Users\hp\.gemini\config\skills\minimalist\SKILL.md`
  - `C:\Users\hp\.gemini\config\skills\playwright-pro\SKILL.md`
- **Exclusive File Ownership:** `app.js`
- **Non-Conflicting Boundary:** State management, search indexing, DOM rendering, JSZip file compiler, cart logic, ⌘K handler.

#### 📝 Agent 4 Prompt:
```markdown
You are Agent 4: Client Application Logic & Zip Compiler Engineer for the Autonomous Agent Skills Portal.
Your task is to build `app.js`.

Ground-Truth Context: Refer to CONTEXT.md and AGENTS.md (Section 6.4 Tweaks protocol, Section 7 Storage).

Functional Requirements:
1. State Management:
   - Active search query, active domain filter, active view mode ('grid' | 'table'), selected skill IDs in bundle cart.
2. Search & Filter Engine:
   - Instant search across name, slash command, description, and keywords.
   - Domain filter pills update view instantaneously.
3. DOM Renderers:
   - `renderGrid(skills)`: Generates 3D tilt cards with domain badges, trigger commands, action buttons (Read Spec, Add to Bundle, Stack Prompt).
   - `renderTable(skills)`: Dense data table view with multi-select checkboxes.
4. Client-Side Bundle Compiler (JSZip):
   - `downloadSkill(skillId)`: Generates a standalone ZIP with `<skill-name>/SKILL.md` and metadata.
   - `downloadBundle(skillIds)`: Generates a custom ZIP containing all selected skills in subfolders.
   - `downloadCuratedKit(kitTag)`: Instantly bundles predefined collections (All 448, Engineering 61, UI/UX 59, QA 17, C-Suite 55).
5. Prompt Stacker:
   - Merges multiple selected skills into a single markdown system prompt block with zero duplication.
6. Command Palette (⌘K) & Keyboard Navigation:
   - Listens for ⌘K / Ctrl+K and '/' shortcut to focus search or trigger modal commands.
7. Hero Constellation Canvas:
   - Lightweight interactive particle canvas responding to pointer movement.
8. Tweaks Panel Integration:
   - Live CSS variable update for primary color, animation speed, and 3D card tilt toggle.
Do not edit any file other than `app.js`.
```

---

### 📊 Agent 5: Architectural Pipeline & Flowchart Simulation Engine

- **Assigned Local Skills:**
  - `C:\Users\hp\.gemini\config\skills\agent-protocol\SKILL.md`
  - `C:\Users\hp\.gemini\config\skills\workflow-builder\SKILL.md`
  - `C:\Users\hp\.gemini\config\skills\boardroom\SKILL.md`
  - `C:\Users\hp\.gemini\config\skills\hivemind\SKILL.md`
- **Exclusive File Ownership:** `pipelines-data.js`, `pipeline-simulator.js`
- **Non-Conflicting Boundary:** Mermaid flowchart definitions and execution simulator engine.

#### 📝 Agent 5 Prompt:
```markdown
You are Agent 5: Pipeline & Simulation Engine Architect for the Autonomous Agent Skills Portal.
Your task is to create `pipelines-data.js` and `pipeline-simulator.js`.

Ground-Truth Context: Refer to CONTEXT.md and AGENTS.md.

Requirements:
1. `pipelines-data.js`:
   - Define 11 production-grade multi-agent Mermaid.js workflows:
     1. Full-Stack Engineering Lifecycle (spec -> tdd -> code -> review -> e2e -> ci)
     2. Design System & UI Prototyping (tokens -> components -> a11y -> screenshot-to-code)
     3. Autonomous QA & Flaky Test Repair (generate -> run -> fix -> testrail -> browserstack)
     4. Executive C-Suite Multi-Role Boardroom (/cs:boardroom: Founder -> CFO -> CTO -> CPO -> GC -> Decision Memo)
     5. Deep Reasoning & Assumption Stress Testing (/deepread -> scenario-war-room -> hard-call)
     6. AI Swarm & Autoresearch Optimization Loop (/ar:setup -> hivemind swarm -> eval -> merge)
     7. Cybersecurity Threat Modeling & Red Team (threat-detection -> red-team -> ciso-review -> soc2)
     8. Growth Marketing & Multi-Touch Attribution (campaign-analytics -> copywriting -> seo-audit -> ab-test)
     9. Data Architecture & Snowflake Pipelines (database-designer -> dbt -> snowflake-development -> data-quality)
     10. Regulatory Compliance Certification (ai-act-readiness -> iso42001 -> iso13485 -> audit-prep)
     11. Zero-Hallucination Migration & Refactoring (tech-debt-tracker -> migration-architect -> strict-api -> canary)
2. `pipeline-simulator.js`:
   - `renderPipeline(pipelineId, container)`: Renders Mermaid SVG via mermaid.render().
   - `startSimulation(pipelineId)`: Runs step-by-step node illumination, simulating agent actions with real-time log output, state transitions (Pending -> Running -> Verified), and interactive node click inspections.
   - Attach to global `window.PipelineSimulator`.
Do not edit any other files.
```

---

### 🚀 Agent 6: Server, Infrastructure & Launch Packaging

- **Assigned Local Skills:**
  - `C:\Users\hp\.gemini\config\skills\ci-cd-pipeline-builder\SKILL.md`
  - `C:\Users\hp\.gemini\config\skills\brag\SKILL.md`
  - `C:\Users\hp\.gemini\config\skills\senior-devops\SKILL.md`
- **Exclusive File Ownership:** `package.json`, `server.js`, `metadata.json`, `brag-output/storyboard.json`
- **Non-Conflicting Boundary:** Express web server, package scripts, metadata descriptors, video launch assets.

#### 📝 Agent 6 Prompt:
```markdown
You are Agent 6: Infrastructure & Launch Packaging Engineer for the Autonomous Agent Skills Portal.
Your task is to create `package.json`, `server.js`, `metadata.json`, and `brag-output/storyboard.json`.

Ground-Truth Context: Refer to CONTEXT.md and AGENTS.md.

Requirements:
1. `package.json`:
   - Dependencies: `express` (lightweight static file server).
   - Scripts: `start`: "node server.js", `dev`: "node server.js", `extract`: "node scripts/extract-skills.js".
2. `server.js`:
   - Express server serving static files from repo root with proper MIME types, gzip/brotli compression, CORS headers, and port fallback (3000 / 8080).
3. `metadata.json`:
   - Application manifest, domain breakdown summary, feature flags, version 1.0.0.
4. `brag-output/storyboard.json`:
   - Keynote launch film storyboard capturing the 10 domains, 448 skills, bundle compiler, and pipeline simulators.
Do not edit any front-end UI or data files.
```
