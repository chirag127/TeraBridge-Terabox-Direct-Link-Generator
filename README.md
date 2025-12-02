# TeraBridge-Terabox-Direct-Link-Generator

A high-performance web app for generating direct, high-speed download links from Terabox URLs. Bypasses ads and wait times for a streamlined user experience.

[![Build Status](https://img.shields.io/github/actions/workflow/user/chirag127/TeraBridge-Terabox-Direct-Link-Generator/ci.yml?style=flat-square&logo=github)](https://github.com/chirag127/TeraBridge-Terabox-Direct-Link-Generator/actions/workflows/ci.yml)
[![Code Coverage](https://img.shields.io/codecov/c/github/chirag127/TeraBridge-Terabox-Direct-Link-Generator?style=flat-square&logo=codecov)](https://codecov.io/gh/chirag127/TeraBridge-Terabox-Direct-Link-Generator)
[![Tech Stack](https://img.shields.io/badge/TechStack-Vite%2C%20React%2C%20TypeScript%2C%20TailwindCSS-blue?style=flat-square&logo=vite)]()
[![Lint/Format](https://img.shields.io/badge/Lint%2FFmt-Biome-informational?style=flat-square&logo=biome)](https://biomejs.dev/)
[![License](https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey?style=flat-square&logo=creativecommons)](https://creativecommons.org/licenses/by-nc/4.0/)
[![GitHub Stars](https://img.shields.io/github/stars/chirag127/TeraBridge-Terabox-Direct-Link-Generator?style=flat-square&logo=github)](https://github.com/chirag127/TeraBridge-Terabox-Direct-Link-Generator/stargazers)

**Star ⭐ this Repo to support its development!**

---

## 🚀 BLUF (Bottom Line Up Front)

TeraBridge accelerates your Terabox downloads by instantly generating direct, ad-free links. This web application bypasses traditional wait times and aggressive advertising, offering a seamless user experience powered by modern web technologies.

---

## 🌳 Project Architecture

This project adheres to a Feature-Sliced Design (FSD) architecture, promoting modularity, scalability, and maintainability. The frontend is structured into distinct features, layers, and segments for clear organization.

mermaid
graph TD
    A[App Layer] --> B(Pages Layer)
    B --> C(Features Layer)
    C --> D(Entities Layer)
    C --> E(Shared Layer)
    D --> E
    E --> F(Vendor Layer)


---

## 📜 Table of Contents

*   [🚀 BLUF (Bottom Line Up Front)](#-bluf-bottom-line-up-front)
*   [🌳 Project Architecture](#-project-architecture)
*   [📜 Table of Contents](#-table-of-contents)
*   [⚡ Key Technologies](#-key-technologies)
*   [🛠️ Development Setup](#-development-setup)
*   [✅ Verification & Testing](#-verification--testing)
*   [🤖 AI AGENT DIRECTIVES](#-ai-agent-directives)
*   [⚖️ License](#️-license)

---

## ⚡ Key Technologies

*   **Frontend Framework:** Vite 7 (Rolldown), React 19
*   **Language:** TypeScript 6.x (Strict Mode)
*   **Styling:** TailwindCSS v4
*   **Native Integration (Optional/Future):** Tauri v2.x
*   **Linting & Formatting:** Biome (Ultra-fast, comprehensive code quality)
*   **Testing:** Vitest (Unit & Integration), Playwright (E2E)

---

## 🛠️ Development Setup

Follow these steps to get a local copy of the project up and running.

1.  **Clone the repository:**
    bash
    git clone https://github.com/chirag127/TeraBridge-Terabox-Direct-Link-Generator.git
    cd TeraBridge-Terabox-Direct-Link-Generator
    

2.  **Install dependencies:**
    bash
    npm install
    

3.  **Run the development server:**
    bash
    npm run dev
    

---

## ✅ Verification & Testing

Automated tests ensure the stability and correctness of TeraBridge.

### Running Tests

*   **Unit & Integration Tests (Vitest):**
    bash
    npm run test
    

*   **End-to-End (E2E) Tests (Playwright):**
    bash
    npm run test:e2e
    

*   **Linting and Formatting Check (Biome):**
    bash
    npm run lint
    

*   **Code Formatting (Biome):**
    bash
    npm run format
    

---

## 🤖 AI AGENT DIRECTIVES

<details>
<summary>View AI Agent Directives</summary>

## SYSTEM: APEX TECHNICAL AUTHORITY & ELITE ARCHITECT (DECEMBER 2025 EDITION)

### 1. IDENTITY & PRIME DIRECTIVE
**Role:** You are a Senior Principal Software Architect and Master Technical Copywriter with **40+ years of elite industry experience**. You operate with absolute precision, enforcing FAANG-level standards and the wisdom of "Managing the Unmanageable."
**Context:** Current Date is **December 2025**. You are building for the 2026 standard.
**Output Standard:** Deliver **EXECUTION-ONLY** results. No plans, no "reporting"—only executed code, updated docs, and applied fixes.
**Philosophy:** "Zero-Defect, High-Velocity, Future-Proof."

---

### 2. INPUT PROCESSING & COGNITION
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

### 3. CONTEXT-AWARE APEX TECH STACKS (LATE 2025 STANDARDS)
**Directives:** Detect the project type and apply the corresponding **Apex Toolchain**.

*   **PRIMARY SCENARIO: WEB / APP / EXTENSION (TypeScript)**
    *   **Stack:** This project leverages **TypeScript 6.x (Strict Mode)**. Key tools include **Vite 7 (Rolldown)** for blazing-fast builds, **React 19** for UI, and **TailwindCSS v4** for utility-first styling. For potential native integration, **Tauri v2.x** is the standard. For browser extensions, **WXT** is preferred.
    *   **Linting & Formatting:** **Biome** is mandated for its speed and comprehensive rule set, replacing ESLint and Prettier.
    *   **Testing:** **Vitest** is the standard for unit and integration tests, with **Playwright** for robust end-to-end testing.
    *   **Architecture:** **Feature-Sliced Design (FSD)** is the standard for organizing frontend code.
    *   **State Management:** **Signals** (following web standards) are preferred for efficient and declarative state updates.

</details>

---

## ⚖️ License

This project is licensed under the **Creative Commons Attribution-NonCommercial 4.0 International License (CC BY-NC 4.0)**. You are free to share and adapt the material for non-commercial purposes, provided you give appropriate credit, provide a link to the license, and indicate if changes were made.

[![CC BY-NC 4.0][cc-by-nc-badge]][cc-by-nc]

[cc-by-nc]: http://creativecommons.org/licenses/by-nc/4.0/
[cc-by-nc-badge]: https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey.svg
