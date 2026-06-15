# Contributing to axon‑prot

## Overview

This document defines the **standard contribution process for all repositories** under the **axon‑prot** GitHub organization. It applies to this repository and any other repositories. Repository‑specific instructions can be found in a local ``CONTRIBUTING.md`` file, but they should only contain **minor, repository‑specific details** and refer back to this file for the full workflow.

---

## Getting Started

1. **Fork** the repository you want to contribute to.
2. **Clone** your fork locally:
   ```bash
   git clone <your-fork-url>
   cd <repo-name>
   ```
3. Follow any **repository‑specific prerequisites** listed in the local ``CONTRIBUTING.md`` (e.g., required runtimes, SDKs, tooling).

---

## Branching \& Workflow

- Create a **feature branch** for each logical change. Use a naming convention such as:
  - `feat/<short-description>` for new features
  - `fix/<short-description>` for bug fixes
  - `doc/<short-description>` for documentation updates
- Write **conventional commits** (see [Conventional Commits](https://www.conventionalcommits.org)). Example:
  ```
  feat: add handshake support to the C# client
  ```
- Push your branch and open a **Merge Request / Pull Request** against the default branch of the upstream repository.

---

## Code Review \& Pull Requests

- Provide a clear description of the change and reference any related issue.
- Keep PRs **small and focused** – a single logical change per PR.
- Respond promptly to review comments.
- Ensure the CI test suite passes before merging.

---

## Testing

All repositories must have a **passing test suite** before merging.
- Add new tests for any new functionality or bug‑fix.
- Verify that existing tests continue to pass.

---

## Documentation

- Keep documentation up‑to‑date when you change the code.
- For the protocol spec, update any affected markdown files under `spec/`.
- For libraries, update README, API docs, and inline code comments as needed.

---

## Issue Reporting

- Use the repository's issue template.
- Provide a clear title, description, and steps to reproduce (if applicable).
- Link related pull requests or discussion threads.

---

## License

All `axon‑prot` repositories are released under the **MIT License** unless otherwise specified. See the ``LICENSE`` file in each repository.

---

## When to Add Repository‑Specific Information

If a repository requires extra setup or has language‑specific tooling, include a minimal ``CONTRIBUTING.md`` in the repository root that **only**:
- Lists the required runtimes, SDKs, or CLI commands.
- Provides short examples for building and testing.
- References this top‑level file for the full contribution workflow.

---

## Code of Conduct

Please follow the project's [Code of Conduct](https://github.com/axon-prot/.github/blob/main/profile/CODE_OF_CONDUCT.md) when interacting with the community.

---

*Thank you for contributing to axon‑prot!*