# Security Policy for TeraBridge-Terabox-Direct-Link-Generator

## Commitment to Security

As the Apex Technical Authority, we treat security as a first-class citizen, adhering to the principle of "Zero-Defect, High-Velocity, Future-Proof." This repository, `TeraBridge-Terabox-Direct-Link-Generator`, is designed with security boundaries in mind, particularly concerning external service interactions (Terabox API/Web Scraping).

--- 

## Supported Versions

Only the latest stable version of the primary stack (TypeScript, React, Vite) is actively supported and patched. Older versions are considered End-of-Life (EOL) immediately upon framework updates unless explicitly stated otherwise.

| Component | Version Track | Support Status |
| :--- | :--- | :--- |
| Core Runtime | Latest Stable | Supported |
| Dependencies | Patched/Audited | Active |

--- 

## Reporting a Vulnerability

We welcome responsible disclosure of security vulnerabilities. Please follow these steps to report an issue efficiently:

1.  **Do not** create a public issue containing sensitive details (e.g., exploit proof-of-concept, direct API keys).
2.  **Use the GitHub Security Advisory feature** if available, or send an encrypted email to `security@chirag127.dev` (Placeholder for professional contact).
3.  **Reference the Issue:** If you must open a temporary public issue to track the report lifecycle, mark it clearly as `[Security Report]` and refer to the private contact method.

### Information to Include in Your Report

To accelerate the triage process, please provide the following:

*   **Vulnerability Type:** (e.g., XSS, SSRF, Denial of Service, Dependency Conflict).
*   **Affected Component(s):** Specify file paths or URLs.
*   **Steps to Reproduce:** Detailed, concise steps to trigger the vulnerability.
*   **Impact Assessment:** The potential damage if exploited.
*   **Recommended Fix (Optional):** Any mitigation suggestions.

--- 

## Vulnerability Response Timeline (SLA)

Our goal is rapid response and remediation, aligned with our High-Velocity mandate. This timeline reflects our commitment to the integrity of the solution.

| Stage | Target Response Time |
| :--- | :--- |
| Initial Triage & Acknowledgment | 24 Hours |
| Fix Development Commenced | 48 Hours |
| Patch Release Deployment | 7 Days (For Critical Issues) |

*Note: This timeline assumes the vulnerability is reproducible and within the scope of this project's responsibility (i.e., not solely an issue with an upstream dependency or the target service itself).* 

## Dependency Scanning & Auditing

We employ automated tools integrated into the CI pipeline (`.github/workflows/ci.yml`) to scan dependencies regularly. For this frontend/utility project, standard checks via `npm audit` (or similar tools integrated with Biome/Vite tooling) are mandatory before merging to `main`.

*   **Critical/High Vulnerabilities:** Automatically block merges via branch protection rules.
*   **Medium/Low Vulnerabilities:** Must be documented, assigned to a sprint, and remediated within 30 days.

--- 

## Security Best Practices for Contributors

All contributions are expected to align with the following principles, as documented in `.github/CONTRIBUTING.md`:

1.  **DRY/SOLID Compliance:** Well-structured code is inherently more secure.
2.  **Input Sanitization:** Never trust input, especially when constructing network requests or rendering HTML content derived from external sources (Terabox links/metadata).
3.  **Secrets Management:** **NEVER** hardcode API keys, secrets, or authentication tokens in source code. Use GitHub Secrets or environment variables exclusively. See `.gitignore` for exclusions.
4.  **Principle of Least Privilege:** The operational environment should only have the minimum permissions necessary to perform its download link generation function.

[Back to Repository Root](https://github.com/chirag127/TeraBridge-Terabox-Direct-Link-Generator)