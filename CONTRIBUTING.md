# Contributing to Grok Export Viewer

Thank you for considering contributing to `grok-export-viewer`! This guide outlines how to contribute effectively to the project.

## Getting Started

1. **Fork the Repository**:

   - Fork the repository on GitHub: [https://github.com/beejaksharam/grok-export-viewer](https://github.com/beejaksharam/grok-export-viewer).
   - Clone your fork:
     ```bash
     git clone https://github.com/beejaksharam/grok-export-viewer.git
     cd grok-export-viewer
     ```

2. **Set Up Development Environment**:

   - Create a virtual environment and install dependencies:
     ```bash
     python -m venv .venv
     source .venv/bin/activate  # On Windows: .venv\Scripts\activate
     pip install -e ".[test]"
     ```

3. **Run Tests**:
   - Ensure tests pass before making changes:
     ```bash
     python -m pytest
     ```

## How to Contribute

### Reporting Issues

- Use the [GitHub Issues](https://github.com/beejaksharam/grok-export-viewer/issues) page to report bugs or suggest features.
- Provide a clear description, including:
  - Steps to reproduce the issue.
  - Expected and actual behavior.
  - Relevant logs or screenshots.
  - Your environment (OS, Python version, package version).

### Submitting Pull Requests

1. **Create a Branch**:

   - Branch off `main` with a descriptive name:
     ```bash
     git checkout -b feature/your-feature-name
     ```

2. **Make Changes**:

   - Follow the coding style (PEP 8).
   - Update tests in `tests/` if adding new functionality.
   - Keep changes focused and atomic.

3. **Test Your Changes**:

   - Run tests and ensure 100% pass rate:
     ```bash
     python -m pytest
     ```
   - Test the CLI manually with a sample `prod-grok-backend.json`.

4. **Commit and Push**:

   - Write clear, concise commit messages:
     ```bash
     git commit -m "Add feature: your feature description"
     git push origin feature/your-feature-name
     ```

5. **Open a Pull Request**:
   - Submit a PR against the `main` branch.
   - Include a detailed description of changes and link to related issues.
   - Ensure all CI checks (if set up) pass.

## Coding Guidelines

- Use Python 3.8+ compatible code.
- Follow [PEP 8](https://www.python.org/dev/peps/pep-0008/) for style.
- Add type hints where possible (as in `core.py`).
- Document functions with docstrings.
- Avoid introducing new dependencies unless necessary.

## Community Guidelines

- Be respectful and inclusive in all interactions.
- Follow the [Code of Conduct](CODE_OF_CONDUCT.md) (if added).

## Questions?

Reach out via [GitHub Issues](https://github.com/beejaksharam/grok-export-viewer/issues) for help or clarification.

Thank you for helping improve `grok-export-viewer`!
