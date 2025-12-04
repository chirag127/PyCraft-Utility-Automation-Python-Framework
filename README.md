# PyCraft-Utility-Automation-Python-Framework

[![Build Status](https://img.shields.io/github/actions/workflow/user/chirag127/PyCraft-Utility-Automation-Python-Framework/ci.yml?style=flat-square&logo=githubactions)](https://github.com/chirag127/PyCraft-Utility-Automation-Python-Framework/actions)
[![Code Coverage](https://img.shields.io/codecov/c/github/chirag127/PyCraft-Utility-Automation-Python-Framework?style=flat-square&logo=codecov)](https://codecov.io/gh/chirag127/PyCraft-Utility-Automation-Python-Framework)
[![Python](https://img.shields.io/badge/python-3.10%2B-blue.svg?style=flat-square&logo=python)](https://www.python.org/)
[![Ruff](https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/charliermarsh/ruff/main/assets/badge/v0.zip&style=flat-square&logo=ruff)](https://github.com/astral-sh/ruff)
[![License: CC BY-NC 4.0](https://img.shields.io/badge/License-CC%20BY--NC%204.0-blue.svg?style=flat-square&logo=creativecommons)](https://creativecommons.org/licenses/by-nc/4.0/)
[![GitHub Stars](https://img.shields.io/github/stars/chirag127/PyCraft-Utility-Automation-Python-Framework?style=flat-square&logo=github)](https://github.com/chirag127/PyCraft-Utility-Automation-Python-Framework/stargazers)

This Python framework provides a robust and scalable solution for developing, managing, and deploying versatile automation and utility scripts. It adheres to modern architectural principles for seamless integration and modular expansion, empowering system administrators and developers with efficient workflow management.

**Star ⭐ this Repo!**

---

## Table of Contents

*   [About The Project](#about-the-project)
*   [Key Features](#key-features)
*   [Architecture](#architecture)
*   [AI Agent Directives](#ai-agent-directives)
*   [Getting Started](#getting-started)
    *   [Prerequisites](#prerequisites)
    *   [Installation](#installation)
*   [Usage](#usage)
*   [Development Standards](#development-standards)
*   [Contributing](#contributing)
*   [License](#license)

---

## About The Project

`PyCraft-Utility-Automation-Python-Framework` is engineered to streamline the creation and execution of Python-based automation and utility scripts. It emphasizes modularity, testability, and maintainability, making it an ideal foundation for complex DevOps tasks, system administration utilities, and data processing pipelines. The framework is designed to be extensible, allowing for easy incorporation of new functionalities and integrations.

## Key Features

*   **Modular Design:** Easily extendable with independent modules for different functionalities.
*   **Scalable Architecture:** Built to handle growing complexity and automation needs.
*   **Efficient Dependency Management:** Utilizes `uv` for fast and reliable package installation.
*   **High-Performance Linting:** Integrated `Ruff` for rapid code analysis and formatting.
*   **Robust Testing:** Comprehensive test suite powered by `Pytest`.
*   **Developer Friendly CLI:** Intuitive command-line interface for seamless interaction.
*   **AI Integration (Optional):** Hooks for integrating AI models for advanced processing.

---

## Architecture

mermaid
graph TD
    A[CLI Interface (Click)] --> B(Core Framework Logic)
    B --> C{Module Manager}
    C --> D[Utility Modules]
    C --> E[Automation Modules]
    E --> F(External APIs/Services)
    D --> G(Configuration)
    B --> H(Testing Suite - Pytest)
    B --> I(Linting/Formatting - Ruff)
    B --> J(Dependency Management - uv)
    B --> K(AI Integration - Gemini API - Optional)

    style A fill:#f9f,stroke:#333,stroke-width:2px
    style H fill:#ccf,stroke:#333,stroke-width:2px
    style I fill:#cfc,stroke:#333,stroke-width:2px
    style J fill:#fcf,stroke:#333,stroke-width:2px
    style K fill:#eee,stroke:#333,stroke-width:2px


---

## AI Agent Directives

<details>
<summary>View AI Agent Directives</summary>

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
**Directives:** Detect the project type (`pyproject.toml` for Python) and apply the corresponding **Apex Toolchain**. This repository, `PyCraft-Utility-Automation-Python-Framework`, is a Python-based AI automation tool.

*   **PRIMARY SCENARIO: DATA / SCRIPTS / AI (Python)**
    *   **Stack:** This project leverages **Python 3.10+**. Key tools include **uv** (for package management and dependency resolution), **Ruff** (for ultra-fast linting and formatting), and **Pytest** (for robust unit and integration testing).
    *   **Architecture:** Adheres to a **Modular Monolith** pattern, ensuring clear separation of concerns for features like GitHub API interaction, AI processing, and CLI interface, while maintaining a unified deployment.
    *   **AI Integration:** Deeply integrated with **Google Gemini API** (`gemini-3-pro` by default) for intelligent batch-processing and decision-making on GitHub resources. Prioritize modular design, clear API contracts, and robust error handling for all AI model interactions.
    *   **CLI Framework:** Uses `Click` or similar for a powerful and intuitive command-line interface.

*   **SECONDARY SCENARIO A: WEB / APP / EXTENSION (TypeScript) - *Not applicable for this project's primary function. Reference only for potential future web-based extensions.***
    *   **Stack:** TypeScript 6.x (Strict), Vite 7 (Rolldown), Tauri v2.x (Native), WXT (Extensions).
    *   **State:** Signals (Standardized).

---

## 4. CODE QUALITY & VERIFICATION MANDATES
*   **LINTING & FORMATTING:** **Ruff** is the sole arbiter. Configure it aggressively via `pyproject.toml`. No deviations.
*   **TESTING FRAMEWORK:** **Pytest** is mandatory. Aim for 95%+ code coverage. Write atomic tests that cover edge cases.
*   **TYPE CHECKING:** Enforce strict type hints using Python's typing module. `mypy` can be run via Ruff.
*   **SECURITY:**
    *   **Dependency Scanning:** Integrate `safety` or similar via CI.
    *   **Vulnerability Analysis:** Regularly scan with `semgrep` or `bandit`.
    *   **Secrets Management:** **NEVER** commit secrets. Use environment variables or a dedicated secrets manager.

---

## 5. CORE DEVELOPMENT PRINCIPLES
*   **SOLID:** Ensure all modules adhere to the SOLID principles.
*   **DRY (Don't Repeat Yourself):** Abstract common logic into reusable functions and classes.
*   **YAGNI (You Ain't Gonna Need It):** Implement features only when required.
*   **KISS (Keep It Simple, Stupid):** Favor straightforward solutions.

---

## 6. AI SERVICE INTEGRATION (GOOGLE GEMINI API)
*   **API Client:** Use the official Google AI Python SDK.
*   **Prompt Engineering:** Develop robust prompts. Document prompt strategies.
*   **Rate Limiting & Error Handling:** Implement graceful handling of API rate limits and errors.
*   **Cost Management:** Monitor API usage and implement cost-saving measures.

---

## 7. VERSION CONTROL & CI/CD PROTOCOL
*   **BRANCHING STRATEGY:** Gitflow or GitHub Flow, adapted for project velocity.
*   **CI/CD PIPELINE (`.github/workflows/ci.yml`):** Automate linting, testing, type checking, and optional deployment steps.

</details>

---

## Getting Started

### Prerequisites

*   Python 3.10 or higher
*   `pip` (usually comes with Python)
*   `git`

### Installation

1.  **Clone the repository:**
    bash
    git clone https://github.com/chirag127/PyCraft-Utility-Automation-Python-Framework.git
    cd PyCraft-Utility-Automation-Python-Framework
    

2.  **Install dependencies using `uv`:**
    bash
    uv python -- --prompt "(pycraft)" -m venv .venv # Or directly use uv install
    uv pip install --system
    
    *(Note: `uv pip install --system` installs packages globally, which is often suitable for CLI tools. For isolated environments, omit `--system` or manage virtual environments explicitly.)*

3.  **Verify installation:**
    bash
    pycraft --version
    

---

## Usage

Run commands via the `pycraft` CLI. For detailed usage and available commands, refer to the integrated help:

bash
pycraft --help


Example:

bash
pycraft process --file data.csv --output processed.csv


---

## Development Standards

This project adheres to the following principles:

*   **SOLID:** Maintainable and understandable object-oriented design.
*   **DRY:** Avoid code duplication by abstracting common logic.
*   **YAGNI:** Build only what is needed now.
*   **KISS:** Prefer simple, straightforward solutions.
*   **PEP 8:** Follow Python's official style guide (enforced by Ruff).
*   **Type Hinting:** Utilize Python's type hinting for improved code clarity and static analysis.

---

## Contributing

Contributions are welcome! Please read our [CONTRIBUTING.md](https://github.com/chirag127/PyCraft-Utility-Automation-Python-Framework/blob/main/.github/CONTRIBUTING.md) for details on the process for submitting pull requests and the code of conduct.

---

## License

This project is licensed under the Creative Commons Attribution-NonCommercial 4.0 International License (CC BY-NC 4.0). See the [LICENSE](https://github.com/chirag127/PyCraft-Utility-Automation-Python-Framework/blob/main/LICENSE) file for more details.
