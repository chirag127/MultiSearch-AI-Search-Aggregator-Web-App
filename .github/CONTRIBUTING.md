# Contributing to MetaMind-Unified-AI-Search-Engine-Web-App

Thank you for your interest in contributing to **MetaMind-Unified-AI-Search-Engine-Web-App**! We aim to foster a collaborative environment built on the principles of Zero-Defect, High-Velocity, and Future-Proof development.

## 1. Code of Conduct

This project adheres to the Contributor Covenant Code of Conduct. Please read the full [CODE_OF_CONDUCT.md](https://github.com/chirag127/MetaMind-Unified-AI-Search-Engine-Web-App/blob/main/CODE_OF_CONDUCT.md) to understand what actions are considered unacceptable.

## 2. How to Contribute

We welcome contributions in the form of bug reports, feature requests, documentation improvements, and code contributions.

### 2.1. Reporting Bugs

1.  **Search Existing Issues:** Before reporting, please check if the issue has already been reported. 
2.  **Create a Detailed Report:** If it's a new bug, please open a new issue using the `Bug Report` template. Include:
    *   A clear and concise title.
    *   Steps to reproduce the bug.
    *   The expected behavior vs. the actual behavior.
    *   Environment details (OS, browser, versions).
    *   Screenshots or recordings if applicable.
    *   Relevant logs.

### 2.2. Suggesting Features

1.  **Search Existing Features:** Check if your feature request already exists.
2.  **Open a Feature Request:** If it's a new idea, please open a new issue using the `Feature Request` template. Explain:
    *   The problem you are trying to solve.
    *   Your proposed solution.
    *   Why this feature would be valuable to users.

### 2.3. Contributing Code

Follow these steps to contribute code:

1.  **Fork the Repository:** Create your own fork of the `chirag127/MetaMind-Unified-AI-Search-Engine-Web-App` repository.
2.  **Clone Your Fork:** Clone your forked repository to your local machine:
    bash
    git clone https://github.com/chirag127/MetaMind-Unified-AI-Search-Engine-Web-App.git
    cd MetaMind-Unified-AI-Search-Engine-Web-App
    
3.  **Set Up Development Environment:** Follow the setup instructions in the `README.md` file to install dependencies and set up the project.
    *   **Technology Stack:** TypeScript 6.x (Strict), Vite 7 (Rolldown), TailwindCSS v4, React 19, Biome (Linter/Formatter), Vitest (Unit Testing), Playwright (E2E Testing).
    *   **Architecture:** Feature-Sliced Design (FSD).
4.  **Create a New Branch:** Branch out from the `main` branch for your new feature or bug fix:
    bash
    git checkout -b feature/your-feature-name
    # or
    git checkout -b bugfix/your-bug-fix-name
    
5.  **Make Your Changes:** Implement your changes, ensuring they adhere to the project's coding standards and architectural guidelines.
6.  **Run Tests:** Ensure all tests pass:
    bash
    # Install dependencies
    npm install
    # Run linters and formatters
    npm run lint
    # Run unit tests
    npm run test:unit
    # Run E2E tests
    npm run test:e2e
    
7.  **Commit Your Changes:** Commit your changes with clear and descriptive commit messages.
    bash
    git add .
    git commit -m "feat: Add user authentication for search results"
    
8.  **Push to Your Fork:** Push your branch to your fork on GitHub:
    bash
    git push origin feature/your-feature-name
    
9.  **Open a Pull Request:** Submit a pull request to the `main` branch of the `chirag127/MetaMind-Unified-AI-Search-Engine-Web-App` repository.
    *   Clearly describe your changes.
    *   Reference any related issues.
    *   Ensure your pull request adheres to the [Pull Request Template](https://github.com/chirag127/MetaMind-Unified-AI-Search-Engine-Web-App/blob/main/.github/PULL_REQUEST_TEMPLATE.md).

## 3. Development Standards & Principles

*   **Apex Philosophy:** Zero-Defect, High-Velocity, Future-Proof.
*   **Naming Convention:** Follow the `Title-Case-With-Hyphens` convention (e.g., `MetaMind-Unified-AI-Search-Engine-Web-App`).
*   **Architecture:** Feature-Sliced Design (FSD) for maintainability and scalability.
*   **Coding Standards:** Strict TypeScript, modern React patterns, and Tailwind CSS for styling.
*   **Linting & Formatting:** Utilize Biome for consistent code style and quality. Run `npm run lint` before committing.
*   **Testing:** Comprehensive unit tests with Vitest and end-to-end tests with Playwright. Aim for high test coverage.
*   **SOLID Principles:** Adhere to SOLID principles for robust and maintainable object-oriented design.
*   **DRY (Don't Repeat Yourself):** Avoid redundant code.
*   **YAGNI (You Aren't Gonna Need It):** Implement only what is necessary currently.

## 4. Project Structure (Feature-Sliced Design - FSD)

mermaid
graph TD
    A[App: Root application layer]
    B[Pages: Routing and page-level components]
    C[Widgets: Composite UI components]
    D[Features: Independent features (e.g., Search, History)]
    E[Entities: Core business entities]
    F[Shared: Reusable UI, utilities, constants]

    A --> B
    B --> C
    B --> D
    C --> D
    D --> E
    D --> F
    E --> F


## 5. AI Agent Directives

Refer to the [AGENTS.md](https://github.com/chirag127/MetaMind-Unified-AI-Search-Engine-Web-App/blob/main/AGENTS.md) file for specific AI agent configurations and directives pertinent to this project.

## 6. Getting Help

If you have questions or need assistance, please:

*   Check the [README.md](https://github.com/chirag127/MetaMind-Unified-AI-Search-Engine-Web-App/blob/main/README.md) for common setup and usage information.
*   Search existing [Issues](https://github.com/chirag127/MetaMind-Unified-AI-Search-Engine-Web-App/issues).
*   Open a new issue if you cannot find an answer.

We look forward to your contributions!
