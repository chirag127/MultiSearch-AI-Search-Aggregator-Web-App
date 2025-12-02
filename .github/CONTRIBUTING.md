# Contributing to MultiSearch AI Search Aggregator

First, thank you for considering contributing to this project. We adhere to the highest industry standards to maintain a clean, scalable, and resilient codebase. This document outlines the contribution workflow and the principles we follow.

## 🚀 Contribution Philosophy

We operate on a "Zero-Defect, High-Velocity" model. Every contribution must enhance the project's value and align with its long-term architectural vision. We expect professional conduct and a commitment to quality from all contributors.

All contributors are expected to abide by our [Code of Conduct](./CODE_OF_CONDUCT.md).

## 🛠️ Core Development Principles

- **Feature-Sliced Design (FSD):** We use FSD for a scalable and maintainable frontend architecture. Ensure your contributions are organized correctly within this structure.
- **SOLID, DRY, YAGNI:** Adhere strictly to these foundational software design principles.
- **Static Typing:** TypeScript is used with `strict` mode enabled. All contributions must be strongly typed.

## Workflow & Setup

### 1. Initial Setup

1.  **Fork the Repository:** Create your own fork of the repository at `https://github.com/chirag127/MultiSearch-AI-Search-Aggregator-Web-App`.
2.  **Clone Your Fork:**
    bash
    git clone https://github.com/<YOUR_USERNAME>/MultiSearch-AI-Search-Aggregator-Web-App.git
    cd MultiSearch-AI-Search-Aggregator-Web-App
    
3.  **Install Dependencies:** We use `pnpm` for efficient package management.
    bash
    pnpm install
    

### 2. Branching Strategy

All work must be done in a feature branch created from the `main` branch. Use the following naming convention:

-   `feature/<description>` for new features (e.g., `feature/add-perplexity-integration`)
-   `bugfix/<issue-number>-<description>` for bug fixes (e.g., `bugfix/112-fix-result-parsing`)
-   `chore/<description>` for maintenance tasks (e.g., `chore/update-dependencies`)

### 3. Making Changes & Ensuring Quality

1.  **Write Code:** Implement your feature or fix, adhering to the architectural principles.
2.  **Format & Lint:** We use **Biome** for instantaneous formatting and linting. Run it before every commit.
    bash
    # Format and apply safe linting fixes
    pnpm format

    # Check for remaining linting issues
    pnpm lint
    
3.  **Run Tests:** All contributions must be accompanied by relevant unit and integration tests using **Vitest**. Ensure all tests pass.
    bash
    pnpm test
    

### 4. Commit Convention

We enforce **Conventional Commits**. This is critical for automated versioning and changelog generation. Your commit messages must be structured as follows:


<type>[optional scope]: <description>

[optional body]

[optional footer]


**Example:** `feat(api): add support for new search provider`

### 5. Submitting a Pull Request

1.  Push your feature branch to your fork.
2.  Open a Pull Request against the `main` branch of the upstream repository.
3.  Fill out the [Pull Request Template](./PULL_REQUEST_TEMPLATE.md) completely.
4.  Link the PR to any relevant issues.
5.  Ensure all CI checks pass. A maintainer will review your PR after all checks are green.

## 🐛 Reporting Bugs and Suggesting Features

-   **Bug Reports:** Use the [Bug Report Template](https://github.com/chirag127/MultiSearch-AI-Search-Aggregator-Web-App/issues/new?template=bug_report.md) to file a bug. Provide detailed steps to reproduce the issue.
-   **Feature Requests:** Use the [Feature Request Template](https://github.com/chirag127/MultiSearch-AI-Search-Aggregator-Web-App/issues/new?template=feature_request.md) to suggest new functionality.

Thank you for your contribution. Let's build a best-in-class tool together.