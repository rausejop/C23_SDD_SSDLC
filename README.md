<div align="center">
  <img src="assets/images/Logo_CONFIANZA23.png" alt="Confianza23 Logo" width="300" />

# 🛡️ C23_SDD_SSDLC: The Spec-Driven Development Framework

![Version](https://img.shields.io/badge/version-v2026.03-blue?style=for-the-badge&logo=semver&logoColor=white)
![Framework](https://img.shields.io/badge/framework-C23_SDD_SSDLC-orange?style=for-the-badge)
![Security Standard](https://img.shields.io/badge/security-OWASP%202025%20%7C%20NIST%20CSF%202.0-red?style=for-the-badge&logo=owasp&logoColor=white)
![License](https://img.shields.io/badge/license-Apache_2.0-green?style=for-the-badge&logo=apache&logoColor=white)
![Platform](https://img.shields.io/badge/platform-Windows%2011-blue?style=for-the-badge&logo=windows&logoColor=white)
![Python](https://img.shields.io/badge/python-3.14.3-blue?style=for-the-badge&logo=python&logoColor=white)
![AI Ops](https://img.shields.io/badge/AI_Ops-Antigravity%20%7C%20Claude_Code-purple?style=for-the-badge&logo=google-gemini)

> *"Security by Design through Deterministric Spec-Driven AI Orchestration."*

</div>

---

## 🏛️ 1. Introduction: The Genesis of Governance

### 📜 The History of Architectural Decision Records (ADR)
The concept of **Architectural Decision Records (ADR)** was first proposed by **Michael Nygard** in 2011. Nygard recognized that the "why" behind architectural choices was often lost over time, leading to "architectural drift" and "technical debt." By capturing decisions in a lightweight, version-controlled format, teams could maintain a collective memory of the system's evolution.

The practice was later popularized by **Thoughtworks** in their Technology Radar, elevating ADRs from a niche blogging concept to a global standard for modern software engineering.

### 🎯 Spec-Driven Development (SDD): From Specs to AI
**Spec-Driven Development** traces its roots back to formal methods and the "Cleanroom Software Engineering" approach initiated by **Harlan Mills**. However, it was made famous in the web era by figures like **Joel Spolsky**, who advocated for "Functional Specifications" as a prerequisite for any code.

In 2026, C23_SDD_SSDLC evolves this paradigm for the **AI-Agentic Era**. With **Google Antigravity** and **Anthropic Claude Code**, SDD is no longer just about human documentation—it is about providing a **deterministic constraint system** that prevents AI "hallucinations" and ensures that every line of code adheres to a predefined "Source of Truth."

### 📈 Market Trends & Future Evolution (2026+)
Current trends in 2026 show a massive shift towards **"Self-Healing Architectures"** and **"GRC-as-Code"** (Governance, Risk, and Compliance). The market is moving away from manual prompts toward **Agentic Skills**—modular, reusable blocks of deterministic knowledge.

The future of C23_SDD_SSDLC lies in **Multi-Agent Orchestration**, where specialized agents (Security Guard, App Architect, QA Lead) negotiate within an SDD-constrained environment to produce zero-vulnerability code.

```mermaid
timeline
    title Evolution of Architectural Governance
    2011 : ADR Concept (Michael Nygard) : Origin of lightweight decision tracking.
    2015 : Thoughtworks Popularity : ADRs become a standard in Agile teams.
    2020 : Early AI Assistants : Documentation starts assisting coding.
    2024 : Agentic Workflows : AI begins to take autonomous actions.
    2026 : SDD 2.0 (C23_SDD_SSDLC) : Deterministic constraints for Google Antigravity & Claude Code.
    Future : Autonomous GRC : Self-healing, zero-trust AI architecture.
```

---

## 🧬 2. The SDD Operational Engine

C23_SDD_SSDLC employs a **Bottom-Up Sequential Flow**. AI operations are governed by a hierarchy of constraints where security and legal mandates (*Asimov’s Constraints*) take precedence over implementation speed.

```mermaid
mindmap
  root((C23_SDD_SSDLC))
    Methodology
      Spec-Driven Development
      Security by Design
      Bottom-Up Workflow
    AI Ops
      Google Antigravity
      Anthropic Claude Code
    Governance
      NIST CSF 2.0
      OWASP 2025
      eIDAS Compliance
```

---

## 🏗️ 3. The Skills Ecosystem (Layered Architecture)

### 🧠 LAYER 1: SDD (The Orchestrator)
This layer defines the core policies of the SDD engine. It is the "Brain" that ensures all other skills are executed in the correct order and under the right constraints.

*   **Skill:** [`skill000_orchestrator.txt`](./skills/skill000_orchestrator.txt)
*   **Role:** System Architect
*   **Key Function:** Orchestrates the multi-agent workflow and resolves conflicts.

```mermaid
graph TD
    A[User Request] --> B{Orchestrator}
    B --> C[Layer 2: GRC Check]
    C --> D[Layer 3: Structural Spec]
    D --> E[Layer 4: Code Guidelines]
    E --> F[Execution]
    F --> G[Layer 6: QA Validation]
    G -- Pass --> H[Success]
    G -- Fail --> B
```

### ⚖️ LAYER 2: GRC (Governance, Risk, & Compliance)
Ensures the software is legally compliant and architecturally secure. It leverages **NIST CSF 2.0** and **ISO 27001:2022** frameworks.

*   **Skills:** 
    *   [`skill011_license.txt`](./skills/skill011_license.txt) (Legal Sentinel)
    *   [`skill012_security.txt`](./skills/skill012_security.txt) (SecOps Guard)

```mermaid
pie title Compliance Distribution
    "Security (OWASP/NIST)" : 45
    "Legal (Apache 2.0/eIDAS)" : 30
    "Privacy (GDPR/SD-JWT)" : 25
```

| Security Domain | Maturity Level |
| :--- | :---: |
| Injection | 0.9 |
| Authentication | 0.85 |
| Data Integrity | 0.95 |
| Logging | 0.8 |
| Encryption | 0.9 |

### 🛠️ LAYER 3: STRUCT (Architecture & Core Stack)
Maps the physical and logical structure of the application. It defines the TRL 7 (Technology Readiness Level) path.

*   **Skills:**
    *   [`skill022_app_manifest.txt`](./skills/skill022_app_manifest.txt) (App Architect)
    *   [`skill023_fslayout.txt`](./skills/skill023_fslayout.txt) (System Structurer)
    *   [`skill024_tech_stack.txt`](./skills/skill024_tech_stack.txt) (Stack Specialist)
    *   [`skill025_libraries.txt`](./skills/skill025_libraries.txt) (DevOps Dependency)

```mermaid
C4Context
    title C4 System Architecture
    Person(user, "Developer", "Uses the framework to build apps.")
    System(c23, "C23_SDD_SSDLC", "Orchestrates AI agents and enforces specs.")
    System_Ext(ga, "Google Antigravity", "AI Ops Execution.")
    System_Ext(cc, "Claude Code", "Advanced Reasoning Agent.")

    Rel(user, c23, "Provides Specs")
    Rel(c23, ga, "Triggers Commands")
    Rel(c23, cc, "Requests Reasoning")
```

```mermaid
erDiagram
    PROJECT ||--o{ LAYER : contains
    LAYER ||--o{ SKILL : defines
    SKILL ||--|| AGENT : governs
    AGENT ||--o{ ARTIFACT : produces
```

### 💻 LAYER 4: CODE (Standards & Guidelines)
Enforces "Senior Engineer" level code quality. Focuses on **PEP 484**, **SOLID** principles, and **Safe types**.

*   **Skill:** [`skill031_python_style.txt`](./skills/skill031_python_style.txt)
*   **Role:** Senior Engineer

```mermaid
classDiagram
    class BaseSkill {
        +String name
        +Integer priority
        +validate()
    }
    class SecuritySkill {
        +Level risk
        +monitor()
    }
    BaseSkill <|-- SecuritySkill
```

### 🏭 LAYER 5: IMPLEMENT (Development Specifics)
The actual implementation of Backend (FastAPI/Hono), Frontend (Next.js/HTMX), and Database (PostgreSQL/Prisma).

*   **Skills:**
    *   [`skill041_backend_spec.txt`](./skills/skill041_backend_spec.txt)
    *   [`skill042_db_schema.txt`](./skills/skill042_db_schema.txt)
    *   [`skill043_frontend_spec.txt`](./skills/skill043_frontend_spec.txt)

```mermaid
sequenceDiagram
    participant User
    participant Frontend
    participant Backend
    participant DB

    User->>Frontend: Interaction
    Frontend->>Backend: API Call (Hono/FastAPI)
    Backend->>DB: Query (Prisma/SQLModel)
    DB-->>Backend: Results
    Backend-->>Frontend: JSON Response
    Frontend-->>User: Update View
```

### 🧪 LAYER 6: QA & OPS
Focuses on testing (Pytest, Playwright) and Operating System tuning for Windows 11.

*   **Skills:**
    *   [`skill051_test_suite.txt`](./skills/skill051_test_suite.txt) (QA Lead)
    *   [`skill052_os_tuning.txt`](./skills/skill052_os_tuning.txt) (Ops Ninja)

```mermaid
gantt
    title Development Lifecycle (QA Focused)
    dateFormat  YYYY-MM-DD
    section Implementation
    Core Coding           :a1, 2026-03-01, 10d
    section Testing
    Unit Tests            :after a1, 5d
    E2E Playwright        : 5d
    section GRC Validation
    Security Audit        : 2026-03-16, 3d
```

### 📚 LAYER 7: DOCS
Automates the generation of documentation and project metadata.

*   **Skills:**
    *   [`skill061_readme.txt`](./skills/skill061_readme.txt)
    *   [`skill062_docs_engine.txt`](./skills/skill062_docs_engine.txt)

```mermaid
gitGraph
    commit id: "Initial Spec"
    branch develop
    commit id: "Add Orchestrator"
    branch feature/security
    commit id: "Compliance Check"
    checkout develop
    merge feature/security
    commit id: "Final Delivery"
    checkout main
    merge develop tag: "v2026.03"
```

### 🌍 LAYER 8: DOCS_CUSTOM (Per-App Documentation)
Custom documentation layers for specific industry standards or RFIs.

*   **Feature:** Allows tailoring the documentation engine to specific organizational needs.
*   **Skills:**
    *   [`skill063_docs_NATO_NCIA_RFI.txt`](./skills/skill063_docs_NATO_NCIA_RFI.txt)
    *   [`skill064_docs_NATO_UKR_UNITE_Brave1_RFI.txt`](./skills/skill064_docs_NATO_UKR_UNITE_Brave1_RFI.txt)

### 🎨 LAYER 9: APP_CUSTOM (UI & Design Systems)
Custom UI/UX layers for specific application branding and design frameworks.

*   **Feature:** Switch between NATO guidelines, MISTICA (Telefónica), or custom design systems.
*   **Skills:**
    *   [`skill044_ux_ui_MISTICA.txt`](./skills/skill044_ux_ui_MISTICA.txt)
    *   [`skill044_ux_ui_NATO.txt`](./skills/skill044_ux_ui_NATO.txt)

---

## 📊 4. Miscellaneous Framework Visualizations

```mermaid
graph LR
    Input["User Input (100)"] --> Orchestrator["Orchestrator"]
    Orchestrator --> Security["Security Layer (30)"]
    Orchestrator --> Dev["Dev Layer (70)"]
    Security --> PassedS["Passed"]
    Dev --> PassedD["Passed (60)"]
    Dev --> FailedD["Failed/Retry (10)"]
```

```mermaid
quadrantChart
    title Skill Priority vs Complexity
    x-axis Low Complexity --> High Complexity
    y-axis Low Priority --> High Priority
    "Orchestrator": [0.2, 0.9]
    "Security Guard": [0.4, 0.95]
    "UI/UX Design": [0.8, 0.5]
    "Docs Engine": [0.6, 0.4]
    "OS Tuning": [0.7, 0.3]
```

| Status | Task |
| :---: | :--- |
| [ ] | Integrity Check |
| [ ] | License Alignment |
| [x] | SDD Layer Mapping |
| [x] | Framework Renaming |

```mermaid
journey
    title Developer Journey with C23_SDD_SSDLC
    section Setup
      Initialize Framework: 5: Developer
      Load Orchestrator: 4: AI
    section Design
      Define Specs: 5: Developer
      Generate Architecture: 4: AI
    section Validation
      QA Testing: 5: AI
      Release: 5: Developer
```

```mermaid
requirementDiagram
    requirement test_req {
    id: 1
    text: the system shall validate all inputs.
    risk: high
    verifymethod: test
    }

    element test_suit {
    type: testing
    }

    test_suit - satisfies -> test_req
```

```mermaid
flowchart TD
  title["System Architecture Layout"]
  UI["Frontend (Next.js)"]
  API["Backend API (Hono)"]
  Logic["SDD Orchestrator"]
  DB["Storage (PostgreSQL)"]
  UI --> API
  API --> Logic
  Logic --> DB
```

```mermaid
sequenceDiagram
    title Skill Initialization
    Orchestrator ->> Layer2: Request Compliance (GRC)
    Layer2 ->> SecuritySkill: Validate
    SecuritySkill -->> Layer2: Done
    Layer2 -->> Orchestrator: Approved
```

```mermaid
stateDiagram-v2
    [*] --> Idle
    Idle --> Processing: New Spec
    Processing --> Validating: Code Generated
    Validating --> Idle: Success
    Validating --> Processing: Failure (Re-prompt)
```

---

<div align="center">
  <i>Written in British Oxford English | Formatted with C23_SDD_SSDLC | AI Ops: Google Antigravity & Claude Code</i>
  <br/>
  <b>Last Update: March 2026</b>
</div>
