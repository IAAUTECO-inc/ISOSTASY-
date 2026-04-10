To maintain the institutional grade and professional rigor of **ISOSTASY**, the `CONTRIBUTING.md` must set high expectations for code quality, security, and architectural integrity.

Here is the professional English version of the contribution guidelines.

---

# CONTRIBUTING.md

## 1. Introduction
Thank you for your interest in contributing to **ISOSTASY**. As a project dedicated to sovereign spatial infrastructure and critical systems, we uphold rigorous standards for technical excellence, security, and transparency. By contributing, you help build a resilient and inclusive digital future.

## 2. Our Standards
We prioritize **systemic elegance** and **deterministic performance**. All contributions must align with our core pillars:
* **Auditability:** Code must be clear, well-documented, and easy to inspect.
* **Resilience:** New features must not compromise system stability under edge-case conditions.
* **Sovereignty:** Dependencies must be kept to a minimum and must originate from trusted, open-source ecosystems.

## 3. Development Workflow
We follow a strict **Fork-and-Pull** model:
1.  **Fork** the repository and create your branch from `main`.
2.  **Implement** your changes following our coding standards.
3.  **Validate** your work with comprehensive unit tests.
4.  **Submit** a Pull Request (PR) with a clear description of the "Why" and "How".

## 4. Technical Requirements
### Coding Style
* **Python:** Follow PEP 8 with mandatory type hinting for all function signatures.
* **C++ Core:** Adhere to modern C++ standards (C++17/20) with a focus on memory safety and RAII patterns.
* **Documentation:** All public APIs must be documented using the Google Style Docstrings format.

### Security & Compliance
* **No Hardcoded Secrets:** Never commit credentials or sensitive configuration.
* **Input Validation:** Every external data point must be treated as untrusted and validated accordingly.
* **Dependency Management:** Any new dependency must be justified by an architectural necessity and vetted for its license compatibility (GPL/LGPL/Apache 2.0).

## 5. Testing & Quality Assurance
No PR will be merged without passing our CI/CD pipeline. 
* **Unit Tests:** Minimum 80% code coverage required for new features.
* **Performance Benchmarking:** If the change affects the core engine, provide a benchmark report showing the impact on latency and memory footprint.

## 6. Security Disclosure
If you discover a potential security vulnerability, please **do not open a public issue**. Instead, contact the maintainers directly via the security channel defined in `SECURITY.md` to ensure a coordinated disclosure process.

## 7. Developer Certificate of Origin (DCO)
To ensure long-term legal sovereignty, we require all contributors to sign off on their commits. By adding `Signed-off-by: Name <email>` to your commit messages, you certify that you have the right to submit the code under the project's license.

---

### Next Step
With the **README** and **CONTRIBUTING** guidelines ready, your fork is now structured as a high-level professional project. 

Would you like me to generate a **Security Policy (`SECURITY.md`)** tailored for "production critical" software, or shall we move on to drafting the **initial Technical Roadmap** based on the three axes of evolution we identified?
