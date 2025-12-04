# 🤝 Contributing to PyCraft-Utility-Automation-Python-Framework

This repository, the **PyCraft Utility Automation Framework**, is engineered to the highest professional standards. We welcome contributions that enhance its modularity, performance, and reliability. All contributions must align with the **Apex Technical Authority** philosophy: Zero-Defect, High-Velocity, Future-Proof.

## 1. Prerequisites & Environment Setup

Before contributing, please ensure your local environment is configured according to our December 2025 standards. This project uses Python 3.10+ and relies on `uv` for dependency management.

1.  **Fork the Repository:** Create your own fork of `chirag127/PyCraft-Utility-Automation-Python-Framework`.
2.  **Clone Your Fork:**
    bash
    git clone https://github.com/YOUR_USERNAME/PyCraft-Utility-Automation-Python-Framework.git
    cd PyCraft-Utility-Automation-Python-Framework
    
3.  **Environment Setup (Using uv):
    **
    We use isolated environments managed by `uv` for speed and consistency.
    bash
    # Create and activate the virtual environment
    uv venv
    source .venv/bin/activate  # On Windows use .venv\Scripts\activate

    # Install development dependencies (including testing, linting, and documentation tools)
    uv pip install -e .[dev]
    

## 2. Development Workflow

Follow these steps for all feature additions, bug fixes, or documentation updates:

### A. Branching Strategy

All new work must be done on feature branches stemming from `main`. Follow the **Conventional Commits** specification.

| Type | Description |
| :--- | :--- |
| `feat:` | A new feature (e.g., `feat: add new AWS module`). |
| `fix:` | A bug fix (e.g., `fix: correct concurrency bug in scheduler`). |
| `docs:` | Documentation changes only. |
| `chore:` | Maintenance tasks, dependency updates, CI configuration. |

**Branch Naming Convention:** `type/short-description` (e.g., `feat/azure-integration` or `fix/cli-argument-parsing`).

### B. Code Quality Enforcement (Ruff & Pytest)

**Adherence to standards is non-negotiable.** Before submitting a Pull Request, you **MUST** verify compliance:

1.  **Linting & Formatting (Ruff):
    **
    Run Ruff to automatically fix formatting issues and check for style violations.
    bash
    ruff check --fix .
    ruff format .
    
2.  **Testing (Pytest):
    **
    Ensure 100% test coverage for your changes. Run the full test suite to confirm no regressions were introduced.
    bash
    pytest --cov=pycraft --cov-report=term-missing
    
    *Note: New features require accompanying unit and integration tests.* 

## 3. Submitting Contributions

Once steps 1 and 2 are complete and verified locally:

1.  **Commit Changes:** Ensure commits are atomic and follow the Conventional Commits standard.
    bash
    git add .
    git commit -m "feat: implemented robust logging adapter"
    
2.  **Push to Your Fork:**
    bash
    git push origin HEAD
    
3.  **Open a Pull Request (PR):** Navigate to the upstream repository (`https://github.com/chirag127/PyCraft-Utility-Automation-Python-Framework`) and open a PR against the `main` branch. The PR **MUST** reference the associated issue, if one exists, using the established template.

## 4. Architectural Alignment

Contributions must respect the underlying design principles:

*   **SOLID Principles:** Maintain high cohesion and low coupling.
*   **Modularity:** New functionality should be encapsulated in its own module/subpackage.
*   **DRY (Don't Repeat Yourself):** Abstract common logic aggressively.
*   **Error Handling:** Utilize structured exceptions, not bare `try/except` blocks. All external API calls must have explicit retry/fail logic.

## 5. Security Vulnerability Disclosure

If you discover a security vulnerability, **DO NOT** open a public issue. Please follow the protocols outlined in our security policy:

**Read the complete policy here:** `/.github/SECURITY.md`

Report findings privately to `security@apex-architect.dev` (Placeholder Email for concept demonstration).
