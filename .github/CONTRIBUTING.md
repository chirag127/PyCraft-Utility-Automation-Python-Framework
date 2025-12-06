# Contributing to PyCraft-Utility-Automation-Python-Framework

Welcome! We appreciate your interest in contributing to the **PyCraft-Utility-Automation-Python-Framework**. Your contributions help us build a more robust, efficient, and versatile automation solution. This document outlines the guidelines for contributing to ensure a smooth and collaborative development process.

## Code of Conduct

By participating in this project, you are expected to uphold our [Code of Conduct](https://github.com/chirag127/PyCraft-Utility-Automation-Python-Framework/blob/main/CODE_OF_CONDUCT.md). Please read it carefully.

## How Can I Contribute?

### 🐞 Reporting Bugs

*   Before submitting a bug report, please check the [existing issues](https://github.com/chirag127/PyCraft-Utility-Automation-Python-Framework/issues) to see if the issue has already been reported.
*   If not, open a new issue using our [bug report template](https://github.com/chirag127/PyCraft-Utility-Automation-Python-Framework/blob/main/.github/ISSUE_TEMPLATE/bug_report.md). Provide a clear and concise description of the bug, steps to reproduce it, expected behavior, and your environment details.

### 💡 Suggesting Enhancements

*   We welcome suggestions for new features or improvements. Before creating a new enhancement request, check if a similar idea has already been discussed in [issues](https://github.com/chirag127/PyCraft-Utility-Automation-Python-Framework/issues).
*   Submit your ideas using the appropriate issue template, explaining the proposed feature, its benefits, and potential use cases.

### 🚀 Submitting Pull Requests

*   **Small, focused changes** are preferred. Larger changes should be broken down into smaller, logical pull requests.
*   Ensure your changes adhere to our [Pull Request Template](https://github.com/chirag127/PyCraft-Utility-Automation-Python-Framework/blob/main/.github/PULL_REQUEST_TEMPLATE.md) and guidelines below.

## Local Development Setup

To set up your local development environment, follow these steps:

1.  **Fork and Clone the Repository:**
    bash
    git clone https://github.com/chirag127/PyCraft-Utility-Automation-Python-Framework.git
    cd PyCraft-Utility-Automation-Python-Framework
    

2.  **Install `uv` (if not already installed):**
    We use `uv` for ultra-fast dependency management.
    bash
    pip install uv
    

3.  **Create and Activate a Virtual Environment with `uv`:**
    bash
    uv venv
    source .venv/bin/activate  # On macOS/Linux
    # .venv\Scripts\activate   # On Windows
    

4.  **Install Dependencies:**
    bash
    uv pip install -e '.[dev,test]'
    

5.  **Run Tests:**
    Ensure all existing tests pass before making changes.
    bash
    pytest
    

6.  **Lint and Format Code:**
    We use `Ruff` for linting and formatting. Run it regularly to maintain code quality.
    bash
    ruff check .
    ruff format .
    
    You can also run auto-fix:
    bash
    ruff check . --fix
    

## Coding Guidelines

*   **Python Standards:** Adhere to [PEP 8](https://www.python.org/dev/peps/pep-0008/) for code style. Use type hints extensively.
*   **Architectural Principles:** Follow the project's **Modular Monolith** architecture. Ensure clear separation of concerns and adherence to **SOLID**, **DRY**, and **YAGNI** principles.
*   **Documentation:** All new features or significant changes must include appropriate documentation, including docstrings for functions/classes, and updates to the `README.md` if necessary.
*   **Testing:** Write comprehensive unit and integration tests for new features and bug fixes. Aim for high code coverage.
*   **Commit Messages:** Follow the [Conventional Commits specification](https://www.conventionalcommits.org/en/v1.0.0/) (e.g., `feat: add new CLI command`, `fix: resolve data parsing error`).

## Pull Request Guidelines

Before submitting your pull request, please ensure the following:

1.  **Branch Naming:** Create a new branch for your feature or bug fix (e.g., `feature/my-new-feature` or `bugfix/issue-123`).
2.  **Clear Description:** Provide a detailed description in your pull request, explaining the changes, their purpose, and any relevant issue numbers.
3.  **Tests:** Include new or updated tests that validate your changes.
4.  **Pass All Checks:** Ensure your code passes all linting, formatting, and test checks locally before pushing.
5.  **Code Review:** Be prepared for constructive feedback during the code review process.

## Security Vulnerabilities

If you discover a security vulnerability, please report it responsibly by following our [Security Policy](https://github.com/chirag127/PyCraft-Utility-Automation-Python-Framework/blob/main/.github/SECURITY.md).

## License

By contributing to PyCraft-Utility-Automation-Python-Framework, you agree that your contributions will be licensed under the [CC BY-NC 4.0 License](https://github.com/chirag127/PyCraft-Utility-Automation-Python-Framework/blob/main/LICENSE).