# <div align="center">🌉 TeraBridge: Instant Terabox Direct Link Generator 🌉</div>

<div align="center">

**High-performance web app to generate direct, high-speed download links from Terabox URLs. Instantly bypasses ads and wait times for a streamlined, superior user experience.**

</div>

<div align="center">

[
![Build Status](https://img.shields.io/github/actions/workflow/status/chirag127/TeraBridge-Terabox-Direct-Link-Generator/ci.yml?branch=main&style=flat-square&logo=githubactions&logoColor=white)
](https://github.com/chirag127/TeraBridge-Terabox-Direct-Link-Generator/actions/workflows/ci.yml)
[
![Code Coverage](https://img.shields.io/codecov/c/github/chirag127/TeraBridge-Terabox-Direct-Link-Generator?style=flat-square&logo=codecov)
](https://codecov.io/gh/chirag127/TeraBridge-Terabox-Direct-Link-Generator)
[
![Maintained](https://img.shields.io/badge/Maintained%3F-yes-green.svg?style=flat-square)
](https://github.com/chirag127/TeraBridge-Terabox-Direct-Link-Generator/graphs/commit-activity)
[
![License](https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey.svg?style=flat-square)
](https://creativecommons.org/licenses/by-nc/4.0/)

---

[
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
](https://react.dev/)
[
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
](https://www.typescriptlang.org/)
[
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
](https://vitejs.dev/)
[
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
](https://tailwindcss.com/)
[
![Biome JS](https://img.shields.io/badge/Biome-60A5FA?style=flat-square&logo=biome&logoColor=white)
](https://biomejs.dev/)

</div>

<div align="center">
  <a href="https://github.com/chirag127/TeraBridge-Terabox-Direct-Link-Generator/stargazers" target="_blank">
    <img src="https://img.shields.io/github/stars/chirag127/TeraBridge-Terabox-Direct-Link-Generator?style=social" alt="GitHub Stars" />
  </a>
</div>

## ✨ Overview

TeraBridge is an elite, client-side web application engineered to generate direct, high-speed download links from Terabox URLs. It eradicates intrusive ads and mandatory wait times, providing a seamless and efficient user experience. Built on a modern, high-velocity tech stack including React, Vite, and TypeScript, TeraBridge ensures maximum performance and reliability.

## 🏛️ Architecture

TeraBridge adheres to the **Feature-Sliced Design (FSD)** methodology, a professional standard for scalable and maintainable frontend applications. This architectural pattern ensures a clear separation of concerns, simplifies dependency management, and enhances developer velocity.

sh
📂 src
├── app/         # App-wide setup, providers, styles
├── pages/       # Atomic routing components (e.g., HomePage)
├── widgets/     # Compositional blocks (e.g., Header, LinkGeneratorForm)
├── features/    # Business logic slices (e.g., generate-direct-link)
├── entities/    # Core business models (e.g., TeraboxLink)
└── shared/      # Reusable modules, UI-kit, APIs, libs


---

## 📋 Table of Contents

- [✨ Overview](#-overview)
- [🏛️ Architecture](#️-architecture)
- [🤖 AI Agent Directives](#-ai-agent-directives)
- [🚀 Getting Started](#-getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [🛠️ Development Scripts](#️-development-scripts)
- [🤝 Contributing](#-contributing)
- [📜 License](#-license)

---

## 🤖 AI Agent Directives

<details>
<summary><strong>SYSTEM: APEX TECHNICAL AUTHORITY (DECEMBER 2025 EDITION)</strong></summary>

### 1. IDENTITY & PRIME DIRECTIVE
**Role:** You are a Senior Principal Software Architect and Master Technical Copywriter with **40+ years of elite industry experience**. You operate with absolute precision, enforcing FAANG-level standards and the wisdom of "Managing the Unmanageable."
**Context:** Current Date is **December 2025**. You are building for the 2026 standard.
**Output Standard:** Deliver **EXECUTION-ONLY** results. No plans, no "reporting"—only executed code, updated docs, and applied fixes.
**Philosophy:** "Zero-Defect, High-Velocity, Future-Proof."

---

### 2. CONTEXT-AWARE APEX TECH STACKS (LATE 2025 STANDARDS)
This repository, `TeraBridge-Terabox-Direct-Link-Generator`, is a high-performance frontend web application. You are mandated to adhere to the following 2026 standards for this project type.

*   **PRIMARY SCENARIO: WEB / APP / GUI (TypeScript)**
    *   **Stack:** This project leverages **TypeScript 5.x+ (Strict Mode)** for robust type safety. The development and build environment is powered by **Vite 5+** for near-instant feedback loops. The UI is constructed with **React 18+** using modern Hooks and concurrent features.
    *   **Styling:** **TailwindCSS v4** is the designated utility-first CSS framework for rapid, consistent, and maintainable styling.
    *   **Architecture:** Strictly enforce **Feature-Sliced Design (FSD)**. All new components, logic, and modules must be correctly placed within the `app/`, `pages/`, `widgets/`, `features/`, `entities/`, or `shared/` layers. Maintain clear boundaries and explicit dependencies between slices.
    *   **State Management:** For simple to moderate state, leverage React's native state management (`useState`, `useReducer`, `useContext`). For complex global state, integrate a lightweight, signal-based library like **Jotai** or **Zustand**.

*   **TOOLING & QUALITY ASSURANCE**
    *   **Package Manager:** Use **pnpm** for efficient, deterministic, and fast dependency management.
    *   **Linting & Formatting:** **Biome** is the unified toolchain for this project. Use `pnpm biome check --apply` to format and lint the entire codebase. The configuration in `biome.json` is the single source of truth for code style.
    *   **Testing:** Employ a multi-layered testing strategy:
        *   **Unit/Integration Tests:** Use **Vitest** for component and logic-level testing. Tests should be co-located with their corresponding source files.
        *   **E2E Tests:** Use **Playwright** for end-to-end testing of critical user flows, such as submitting a Terabox URL and receiving a valid direct link.

### 3. VERIFICATION & EXECUTION COMMANDS
*   **Code Quality Check:** `pnpm biome check --apply`
*   **Run All Tests:** `pnpm test`
*   **Run E2E Tests:** `pnpm test:e2e`
*   **Build for Production:** `pnpm build`

</details>

---

## 🚀 Getting Started

Follow these instructions to set up the development environment locally.

### Prerequisites

- [Node.js](https://nodejs.org/) (v20.x or higher)
- [pnpm](https://pnpm.io/) (v9.x or higher)

### Installation

1.  **Clone the repository:**

    bash
    git clone https://github.com/chirag127/TeraBridge-Terabox-Direct-Link-Generator.git
    cd TeraBridge-Terabox-Direct-Link-Generator
    

2.  **Install dependencies:**

    bash
    pnpm install
    

3.  **Start the development server:**

    bash
    pnpm dev
    

    The application will be available at `http://localhost:5173`.

## 🛠️ Development Scripts

This project includes several scripts to streamline development and quality assurance:

| Command          | Description                                               |
| ---------------- | --------------------------------------------------------- |
| `pnpm dev`       | Starts the Vite development server with Hot Module Reload.  |
| `pnpm build`     | Compiles the application for production deployment.       |
| `pnpm preview`   | Serves the production build locally for verification.     |
| `pnpm test`      | Runs all unit and integration tests with Vitest.          |
| `pnpm test:ui`   | Starts the Vitest UI for interactive testing.             |
| `pnpm lint`      | Lints the codebase using Biome.                           |
| `pnpm format`    | Formats the entire codebase using Biome.                  |
| `pnpm check`     | Runs both linting and formatting checks.                  |

## 🤝 Contributing

Contributions are welcome and essential for keeping this project innovative and robust. Please read the [**CONTRIBUTING.md**](./.github/CONTRIBUTING.md) guide for details on our code of conduct, development process, and pull request submission standards.

To report a bug or request a feature, please use the [**Issue Templates**](./.github/ISSUE_TEMPLATE).

## 📜 License

This project is licensed under the [Creative Commons Attribution-NonCommercial 4.0 International License](https://creativecommons.org/licenses/by-nc/4.0/). See the [**LICENSE**](./LICENSE) file for full details.
