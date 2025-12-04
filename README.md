# MetaMind-Unified-AI-Search-Engine-Web-App

![Build Status](https://img.shields.io/github/actions/workflow/user/chirag127/MetaMind-Unified-AI-Search-Engine-Web-App/ci.yml?style=flat-square&logo=githubactions)
![Code Coverage](https://img.shields.io/codecov/c/github/chirag127/MetaMind-Unified-AI-Search-Engine-Web-App?style=flat-square&logo=codecov)
![Tech Stack](https://img.shields.io/badge/TechStack-TypeScript%7CVite%7CTailwindCSS%7CReact-blue?style=flat-square&logo=javascript)
![Linting](https://img.shields.io/badge/Lint--Formatting-Biome-critical?style=flat-square&logo=biome)
![License](https://img.shields.io/badge/License-CC%20BY--NC%204.0-orange?style=flat-square&logo=creativecommons)
![GitHub Stars](https://img.shields.io/github/stars/chirag127/MetaMind-Unified-AI-Search-Engine-Web-App?style=flat-square&logo=github)

### Star ⭐ this Repo

## Unified AI Search Interface

MetaMind aggregates AI-powered search results from multiple engines into a single, intuitive interface. Maximize search efficiency and discover comprehensive, cross-platform insights with a single query.

## Architecture Overview

mermaid
graph TD
    A[User Interface (React/TypeScript)] --> B(API Gateway / Backend Service)
    B --> C{Search Engine Orchestrator}
    C --> D1[AI Search Engine 1 API]
    C --> D2[AI Search Engine 2 API]
    C --> D3[AI Search Engine N API]
    D1 --> C
    D2 --> C
    D3 --> C
    C --> B
    B --> A

    subgraph Backend Services
        C
        D1
        D2
        D3
    end

    subgraph Frontend
        A
    end


## Table of Contents

*   [Architecture Overview](#architecture-overview)
*   [AI Agent Directives](#ai-agent-directives-critical)
*   [Development Standards](#development-standards)
    *   [Project Setup](#project-setup)
    *   [Scripts](#scripts)
    *   [Core Principles](#core-principles)
*   [Contributing](#contributing)
*   [License](#license)

---

## 🤖 AI Agent Directives (Critical)

<details>
<summary>View Agent Directives</summary>

This repository is managed by the **Apex Technical Authority** (December 2025 Edition), operating under the Prime Directive: "Zero-Defect, High-Velocity, Future-Proof." The following directives ensure AI alignment, architectural integrity, and adherence to late 2025 standards.

### **1. Identity & Prime Directive**

*   **Role:** Senior Principal Software Architect and Master Technical Copywriter (40+ years experience).
*   **Context:** December 2025. Building for 2026 standards.
*   **Output Standard:** **EXECUTION-ONLY**. No plans, only executed code, updated docs, and applied fixes.
*   **Philosophy:** "Zero-Defect, High-Velocity, Future-Proof."

### **2. Input Processing & Cognition**

*   **Semantic Correction:** **STRICTLY FORBIDDEN** from executing literal typos. Must infer technical intent based on project context. `README.md` is the Single Source of Truth (SSOT).
*   **Mandatory MCP Instrumentation:** No guessing APIs. Use `linkup`/`brave` for December 2025 industry standards, security threats, and 2026 UI trends. Verify external API signatures with `docfork`. Architect complex flows with `clear-thought-two` before coding.

### **3. Context-Aware Apex Tech Stacks (Late 2025 Standards)**

*   **Scenario:** WEB / APP / EXTENSION (TypeScript)
    *   **Stack:** **TypeScript 6.x (Strict)**, **Vite 7 (Rolldown)**, **TailwindCSS v4**, **React 19**, **Tauri v2.x (for potential desktop expansion)**, **WXT (for browser extensions)**.
    *   **State Management:** Signals (Standardized).
    *   **Linting/Formatting:** **Biome** (speed and comprehensive coverage).
    *   **Testing:** **Vitest** (Unit/Integration), **Playwright** (E2E).
    *   **Architecture:** **Feature-Sliced Design (FSD)**.

### **4. Verification Commands (Apex Standard)**

*   **Lint & Format:** `npx @biomejs/biome format --write .`
*   **Lint Check:** `npx @biomejs/biome check --apply .`
*   **Unit Tests:** `npx vitest run`
*   **E2E Tests:** `npx playwright test`
*   **Build:** `npx vite build`
*   **Local Dev Server:** `npx vite`

### **5. Core Principles Enforcement**

*   **SOLID:** Strict adherence to Single Responsibility, Open/Closed, Liskov Substitution, Interface Segregation, Dependency Inversion.
*   **DRY:** Do Not Repeat Yourself. Abstract common logic.
*   **YAGNI:** You Ain't Gonna Need It. Build for current needs, not speculative future requirements.
*   **KISS:** Keep It Simple, Stupid. Favor clarity and simplicity.

</details>

---

## Development Standards

### Project Setup

1.  **Clone the Repository:**
    bash
    git clone https://github.com/chirag127/MetaMind-Unified-AI-Search-Engine-Web-App.git
    cd MetaMind-Unified-AI-Search-Engine-Web-App
    

2.  **Install Dependencies:**
    bash
    # Using npm (default for Vite)
    npm install
    

### Scripts

| Script Name         | Description                                     |
| :------------------ | :---------------------------------------------- |
| `npm run dev`       | Starts the development server.                  |
| `npm run build`     | Builds the application for production.          |
| `npm run lint`      | Runs Biome linter and formatter checks.         |
| `npm run test:unit` | Runs Vitest unit and integration tests.         |
| `npm run test:e2e`  | Runs Playwright end-to-end tests.               |

### Core Principles

*   **SOLID:** We adhere to SOLID design principles for maintainable and scalable code.
*   **DRY:** Logic duplication is actively refactored into reusable modules.
*   **YAGNI:** Features are implemented only when they are strictly required.
*   **KISS:** Simplicity and clarity are prioritized in all architectural decisions.

---

## Contributing

We welcome contributions! Please see the [CONTRIBUTING.md](https://github.com/chirag127/MetaMind-Unified-AI-Search-Engine-Web-App/blob/main/.github/CONTRIBUTING.md) file for detailed guidelines on how to submit your pull requests.

---

## License

This project is licensed under the Creative Commons Attribution-NonCommercial 4.0 International License (CC BY-NC 4.0). See the [LICENSE](https://github.com/chirag127/MetaMind-Unified-AI-Search-Engine-Web-App/blob/main/LICENSE) file for more details.
