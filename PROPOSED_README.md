# ⚛️ AtomicPulse: Interactive Counter React Native Application

This repository hosts **AtomicPulse**, a foundational mobile application built on React Native and Expo, engineered to serve as a best-practice template for cross-platform state management and responsive UI development. It demonstrates disciplined state encapsulation and high-performance native interaction.

---

## 🧭 Project Vision & Architecture

**AtomicPulse** is designed not just as a simple counter, but as a robust, reusable module demonstrating clean separation of concerns using established mobile development patterns. It enforces modern TypeScript strictness and leverages the high-velocity development provided by Expo.

### Core Technology Stack (Late 2025 Standard)

| Component | Technology | Rationale |
| :--- | :--- | :--- |
| **Framework** | React Native (via Expo SDK 54+) | Cross-platform native performance and rapid iteration. |
| **Language** | TypeScript 6.x (Strict Mode) | Enforced type safety and compile-time error detection. |
| **State Management** | Zustand/Jotai (Inferred/Recommended) | Lightweight, signal-based state for atomic updates, aligning with 2026 trends. |
| **Styling** | StyleSheet API / Custom Theme Provider | Native performance focus over heavy external CSS-in-JS solutions. |
| **Linting/Formatting** | Biome | Unified, high-speed toolchain for linting and formatting enforcement. |

### Structural Blueprint (Feature-Sliced Design Inferred)

The architecture follows principles akin to Feature-Sliced Design (FSD) adapted for Mobile, separating logic into distinct layers for scalability:

mermaid
graph TD
    A[App Entry] --> B(App/AppEntry);
    B --> C{Features/Counter}; 
    C --> D[Domain/StateCore];
    C --> E[Shared/Components];
    D --> F(Services/Storage); 
    E --> G[UI/Primitives];
    style C fill:#f9f,stroke:#333,stroke-width:2px
    style D fill:#ccf,stroke:#333,stroke-width:2px


---

## 🤖 AI AGENT DIRECTIVES (DECEMBER 2025 EDITION)

<details>
<summary>Click to Review Apex Authority Directives for Future Maintenance</summary>

# SYSTEM: APEX TECHNICAL AUTHORITY & ELITE ARCHITECT (DECEMBER 2025 EDITION)

## 1. IDENTITY & PRIME DIRECTIVE
**Role:** You are a Senior Principal Software Architect and Master Technical Copywriter with **40+ years of elite industry experience**. You operate with absolute precision, enforcing FAANG-level standards and the wisdom of "Managing the Unmanageable."
**Context:** Current Date is **December 2025**. You are building for the 2026 standard.
**Output Standard:** Deliver **EXECUTION-ONLY** results. No plans, no "reporting"—only executed code, updated docs, and applied fixes.
**Philosophy:** "Zero-Defect, High-Velocity, Future-Proof."

--- 

## 2. INPUT PROCESSING & COGNITION
*   **SPEECH-TO-TEXT INTERPRETATION PROTOCOL:**
    *   **Context:** User inputs may contain phonetic errors (homophones, typos).
    *   **Semantic Correction:** **STRICTLY FORBIDDEN** from executing literal typos. You must **INFER** technical intent based on the project context.
    *   **Logic Anchor:** Treat the `README.md` as the **Single Source of Truth (SSOT)**.
*   **MANDATORY MCP INSTRUMENTATION:**
    *   **No Guessing:** Do not hallucinate APIs. 
    *   **Research First:** Use `linkup`/`brave` to search for **December 2025 Industry Standards**, **Security Threats**, and **2026 UI Trends**. 
    *   **Validation:** Use `docfork` to verify *every* external API signature. 
    *   **Reasoning:** Engage `clear-thought-two` to architect complex flows *before* writing code.

--- 

## 3. CONTEXT-AWARE APEX TECH STACKS (LATE 2025 STANDARDS)
**Directives:** Detect the project type and apply the corresponding **Apex Toolchain**. This repository, `AtomicPulse-Interactive-Counter-React-Native-App`, is a **TypeScript/React Native** project.

*   **PRIMARY SCENARIO: WEB / APP / GUI (Modern Frontend/Mobile)**
    *   **Stack:** **TypeScript 6.x (Strict)**, **Vite 7/Metro (via Expo)**, **TailwindCSS v4 (via Nativewind)** (if applicable, though pure RN Styling preferred here), **React Native Reanimated v3/v4** for high-fidelity animations.
    *   **Lint/Test:** **Biome** (Speed & Formatting) + **Vitest** (Unit) + **Playwright** (E2E, targeting specific mobile simulators/web views if necessary, or Detox for pure RN).
    *   **Architecture:** **Feature-Sliced Design (FSD)** principles adapted for component/feature segregation in React Native.

---

## 4. DEVELOPMENT & ARCHITECTURAL PRINCIPLES (ENFORCED STANDARDS)

*   **SOLID Compliance:** Critical for all state abstractions and data fetching layers.
*   **DRY Enforcement:** Logic duplication across screen components is penalized. Utilize shared hooks and state stores.
*   **YAGNI & KISS:** Maintain simplicity. Over-engineering state for future features is forbidden unless explicitly documented in the scope.
*   **Verification Commands:** To ensure immediate alignment with these standards, the agent must verify the following:
    1.  `npm run lint -- --staged` (Ensure Biome compliance).
    2.  `npm run test` (Verify unit test coverage minimum of 85%).
    3.  Run application deployment via Expo CLI to confirm environment stability.

</details>

---

## 🚀 Development & Execution

This project requires a modern Node.js environment (v20+ recommended) and the Expo CLI installed globally or locally.

### Prerequisites

1.  Node.js (v20.x or higher)
2.  Expo CLI (`npm install -g expo-cli`)
3.  Watchman (Recommended for macOS/Linux)

### Setup

bash
# 1. Clone the repository
git clone https://github.com/chirag127/AtomicPulse-Interactive-Counter-React-Native-App.git
cd AtomicPulse-Interactive-Counter-React-Native-App

# 2. Install dependencies using uv/npm (npm used for standard RN setup)
npm install
# or if using uv for python dependencies (not applicable here, but standard practice):
# uv sync

# 3. Verify environment stability (Running Biome check)
npm run lint


### Available Scripts

| Script Name | Command | Description |
| :--- | :--- | :--- |
| `start` | `npx expo start` | Starts the Metro bundler and launches the app interface. |
| `android` | `npx expo run:android` | Builds and runs on an Android emulator/device. |
| `ios` | `npx expo run:ios` | Builds and runs on an iOS simulator/device. |
| `test` | `npm run test` | Executes Vitest unit tests. |
| `format` | `npx @biomejs/biome check --apply` | Formats all code according to strict Biome rules. |

---

## ✨ Contributing & Governance

We welcome contributions that uphold the high technical standards defined in the `AGENTS.md` and adhere strictly to the **Standard 11 Compliance** files located in `.github/`. Please review `.github/CONTRIBUTING.md` before submitting Pull Requests.

## 🛡️ Security

All security advisories must be reported responsibly via `.github/SECURITY.md` guidelines. We maintain zero tolerance for known vulnerabilities in core dependencies. Dependency auditing is integrated into the CI pipeline (`ci.yml`).
