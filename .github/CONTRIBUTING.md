# Contributing Guidelines for TeraBridge-Terabox-Direct-Link-Generator

Thank you for considering contributing to **TeraBridge-Terabox-Direct-Link-Generator**! We welcome your input to make this project even better.

This project adheres to the Apex Technical Authority standards, emphasizing high-velocity, zero-defect, and future-proof development. All contributions are expected to align with these principles.

## 1. Code of Conduct

This project is governed by the Contributor Covenant, version 2.1. We expect all contributors to uphold this code of conduct. Please report any violations to `chirag.dev@example.com`.

## 2. Contribution Workflow

We follow a standard GitHub pull request workflow:

1.  **Fork the Repository:** Create your own fork of the `chirag127/TeraBridge-Terabox-Direct-Link-Generator` repository.
2.  **Clone Your Fork:** Clone your forked repository to your local machine.
    bash
    git clone https://github.com/chirag127/TeraBridge-Terabox-Direct-Link-Generator.git
    cd TeraBridge-Terabox-Direct-Link-Generator
    
3.  **Set Up Development Environment:**
    *   Follow the setup instructions in the `README.md` to install dependencies and configure the environment. This project uses **Vite**, **TypeScript**, and **TailwindCSS** for the frontend.
    *   Ensure you have Node.js and npm/yarn installed.
    bash
    # Example using npm
    npm install
    
4.  **Create a New Branch:** Create a feature branch for your contribution.
    bash
    git checkout -b feature/your-feature-name
    
5.  **Make Your Changes:** Implement your feature, fix bugs, or improve documentation.
6.  **Test Your Changes:** Ensure all tests pass. Run linters and formatters.
    bash
    # Example commands (refer to README for specifics)
    npm run lint
    npm run test
    npm run format
    
7.  **Commit Your Changes:** Write clear and concise commit messages.
    bash
    git commit -m "feat: Add new direct link generation logic"
    
8.  **Push to Your Fork:** Push your branch to your forked repository.
    bash
    git push origin feature/your-feature-name
    
9.  **Open a Pull Request:** Navigate to the original repository (`chirag127/TeraBridge-Terabox-Direct-Link-Generator`) and open a pull request from your feature branch.

## 3. Branching Strategy

*   All development should occur on feature branches branched off the `main` (or `master`) branch.
*   The `main` branch is considered stable and production-ready.

## 4. Coding Standards & Best Practices

*   **Language:** This project is primarily written in **HTML**, but relies heavily on **TypeScript** and **JavaScript** for dynamic functionality.
*   **Frameworks:** **React** and **Vite** are used for the frontend.
*   **Styling:** **TailwindCSS** is used for utility-first styling.
*   **Linting & Formatting:** Adhere to the linting and formatting rules enforced by **Biome** (or similar configured tools). Ensure your code is clean and well-formatted before committing.
*   **Code Quality:**
    *   Follow **SOLID** principles where applicable.
    *   Ensure code is **DRY** (Don't Repeat Yourself).
    *   Write clear, readable, and maintainable code.
    *   Add comments where logic is complex or non-obvious.
*   **Testing:** All new features and significant bug fixes must be accompanied by unit and/or integration tests. Refer to the testing section in `README.md` for details.

## 5. Submitting Patches

When submitting a bug fix, please:

1.  Verify the bug in the `main` branch.
2.  Write a test that describes and reveals the bug.
3.  Fix the bug and ensure the test passes.

## 6. Project Structure

Familiarize yourself with the project's structure as defined in the `README.md` or an architectural diagram (if provided).

## 7. Licensing

This project is licensed under the **CC BY-NC 4.0** license. By contributing, you agree that your contributions will be licensed under this same license.

## 8. Questions?

If you have any questions about the contribution process or the project itself, please open an issue or contact the maintainer.
