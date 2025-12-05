# PyCraft-Utility-Automation-Python-Framework

[![GitHub Build Status](https://img.shields.io/github/actions/workflow/user/chirag127/PyCraft-Utility-Automation-Python-Framework/ci.yml?style=flat-square&logo=githubactions)](https://github.com/chirag127/PyCraft-Utility-Automation-Python-Framework/actions/workflows/ci.yml)
[![Code Coverage](https://img.shields.io/codecov/c/github/chirag127/PyCraft-Utility-Automation-Python-Framework.svg?style=flat-square&logo=codecov)](https://codecov.io/github/chirag127/PyCraft-Utility-Automation-Python-Framework)
[![Python Version](https://img.shields.io/badge/python-3.10+-blue.svg?style=flat-square&logo=python)](https://www.python.org/)
[![License: CC BY-NC 4.0](https://img.shields.io/badge/License-CC%20BY--NC%204.0-red.svg?style=flat-square&logo=creativecommons)](https://creativecommons.org/licenses/by-nc/4.0/)
[![GitHub Stars](https://img.shields.io/github/stars/chirag127/PyCraft-Utility-Automation-Python-Framework?style=flat-square&logo=github)](https://github.com/chirag127/PyCraft-Utility-Automation-Python-Framework/stargazers)

A robust Python framework for developing, managing, and deploying versatile automation and utility scripts. Designed for efficiency and scalability, it adheres to modern architectural principles for seamless integration and modular expansion. Ideal for system administrators and developers.

## Architecture Diagram

mermaid
graph TD
    A[CLI Interface (Click)] --> B(Core Automation Engine)
    B --> C{Module Manager}
    C --> D[Utility Scripts]
    C --> E[DevOps Workflows]
    B --> F(GitHub API Client)
    F --> G[AI Integration (Gemini)]
    B --> H(Configuration Manager)
    D --> I(Logging)
    E --> I
    F --> I
    G --> I
    H --> I


## Table of Contents

*   [Overview](#overview)
*   [Key Features](#key-features)
*   [Architecture](#architecture)
*   [Tech Stack](#tech-stack)
*   [AI Agent Directives](#ai-agent-directives)
*   [Getting Started](#getting-started)
*   [Development Setup](#development-setup)
*   [Testing](#testing)
*   [Contributing](#contributing)
*   [License](#license)

## Overview

PyCraft provides a structured and scalable environment for Python-based automation and utility tasks. It simplifies script development, management, and deployment by enforcing modularity, promoting best practices, and integrating advanced capabilities like AI-driven insights.

## Key Features

*   **Modular Design:** Easily extendable with custom modules for various automation needs.
*   **Scalable Framework:** Built to handle complex workflows and large-scale deployments.
*   **AI Integration:** Leverages Google Gemini for intelligent task automation and data analysis.
*   **Developer-Friendly CLI:** Intuitive command-line interface for seamless interaction.
*   **DevOps Centric:** Tailored for efficient integration into CI/CD pipelines.
*   **Robust Error Handling:** Comprehensive logging and error management.

## Architecture

This project follows a **Modular Monolith** architectural pattern. The core components are: 

*   **CLI Interface:** Built with `Click` for user interaction.
*   **Core Automation Engine:** Orchestrates script execution and workflow management.
*   **Module Manager:** Handles loading and managing extensible modules.
*   **GitHub API Client:** Interacts with GitHub services.
*   **AI Integration:** Utilizes Google Gemini API for advanced features.
*   **Configuration Manager:** Manages application settings.
*   **Logging:** Centralized logging for all operations.

## Tech Stack

*   **Language:** Python 3.10+
*   **Package Management:** uv
*   **Linting & Formatting:** Ruff
*   **Testing:** Pytest
*   **CLI Framework:** Click
*   **AI Model:** Google Gemini API (`gemini-3-pro` by default)
*   **Architecture:** Modular Monolith

## 🤖 AI Agent Directives

<details>
<summary>Click to expand AI Agent Directives</summary>

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

## 4. PROJECT MANAGEMENT & COMPLIANCE
*   **Source Control:** Git
*   **CI/CD:** GitHub Actions (Defined in `.github/workflows/ci.yml`)
*   **Code Quality:** Ruff (Linting & Formatting), Pytest (Testing).
*   **Dependency Management:** uv
*   **License:** CC BY-NC 4.0
*   **Documentation:** README.md, AGENTS.md, CONTRIBUTING.md, ISSUE_TEMPLATE, PR_TEMPLATE, SECURITY.md

---

## 5. APEX CODING PRINCIPLES
*   **SOLID:** Adhere to all five SOLID principles for maintainable and scalable code.
*   **DRY:** Don't Repeat Yourself. Abstract common logic into reusable functions or classes.
*   **YAGNI:** You Ain't Gonna Need It. Focus on current requirements, avoid over-engineering.
*   **KISS:** Keep It Simple, Stupid. Prefer straightforward solutions.
*   **Defensive Programming:** Validate inputs, handle edge cases, and implement robust error handling.

---

## 6. VERIFICATION COMMANDS (Python)
*   **Install Dependencies:** `uv pip sync`
*   **Lint & Format:** `ruff check . --fix`
*   **Run Tests:** `pytest`
*   **Full CI Pipeline:** `python -m pytest --cov=./ --cov-report=xml` (or equivalent commands executed by GitHub Actions).
*   **AI Model Interaction:** Ensure API keys are securely managed (e.g., via environment variables or a secrets manager) and API calls are retried with exponential backoff for transient network issues.

</details>

## Getting Started

This project is designed to be run using Python 3.10 or higher.

1.  **Clone the Repository:**
    bash
    git clone https://github.com/chirag127/PyCraft-Utility-Automation-Python-Framework.git
    cd PyCraft-Utility-Automation-Python-Framework
    

2.  **Set up Environment:**
    bash
    # Ensure uv is installed: https://github.com/astral-sh/uv
    uv venv # Creates a virtual environment
    uv pip sync # Installs all project dependencies
    

3.  **Configure API Keys:**
    Set your Google Gemini API key as an environment variable:
    bash
    export GOOGLE_API_KEY='YOUR_GEMINI_API_KEY'
    
    *(Note: For production, use a more secure secret management solution.)*

## Development Setup

To contribute to PyCraft, ensure you have the following installed:

*   Python 3.10+
*   uv
*   Git

Follow the steps in "Getting Started" to set up your local development environment.

## Scripts

| Script Name         | Description                                                    |
| :------------------ | :------------------------------------------------------------- |
| `pycraft run <module>` | Executes a specific automation module.                         |
| `pycraft config set <key> <value>` | Sets a configuration value.                                    |
| `pycraft test`      | Runs all project tests using Pytest.                           |
| `pycraft lint`      | Lints and formats code using Ruff.                             |
| `pycraft ai summarize <text>` | Uses AI to summarize provided text.                            |
| `pycraft github-sync <repo>` | Synchronizes repository settings via GitHub API.               |

*(Refer to the CLI documentation for a comprehensive list of commands.)*

## Testing

Pytest is used for all unit and integration tests. Ensure all tests pass before submitting changes.

bash
pytest


To run tests with coverage:

bash
python -m pytest --cov=./ --cov-report=xml


## Contributing

We welcome contributions! Please refer to the [CONTRIBUTING.md](https://github.com/chirag127/PyCraft-Utility-Automation-Python-Framework/blob/main/.github/CONTRIBUTING.md) file for detailed guidelines on how to contribute.

## License

This project is licensed under the Creative Commons Attribution-NonCommercial 4.0 International License (CC BY-NC 4.0). See the [LICENSE](https://github.com/chirag127/PyCraft-Utility-Automation-Python-Framework/blob/main/LICENSE) file for more details.

---
