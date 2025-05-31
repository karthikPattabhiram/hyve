# 🚀 Branch Naming Conventions & Collaboration Guide

To ensure smooth collaboration, minimize merge conflicts, and maintain a professional workflow, we follow these **branch naming conventions** and guidelines:

## Branch Prefixes

| Prefix        | Purpose                           | Example                         |
|---------------|-----------------------------------|----------------------------------|
| `feature/`    | New features or enhancements      | `feature/user-authentication`    |
| `bugfix/`     | Bug fixes                         | `bugfix/navbar-link-error`       |
| `hotfix/`     | Critical fixes for production     | `hotfix/login-crash`             |
| `release/`    | Release preparation               | `release/v1.2.0`                 |
| `experiment/` | Experimental ideas or spike work  | `experiment/dark-mode-test`      |
| `chore/`      | Maintenance & refactoring         | `chore/remove-unused-code`       |
| `docs/`       | Documentation updates             | `docs/update-readme`             |
| `test/`       | Testing-related changes           | `test/improve-coverage`          |

## Workflow

1. **Never push directly to `main` (or `master`) branch**.
2. Create a new branch for each task, using the prefixes above.
3. Commit with clear, descriptive messages.
4. Frequently pull the latest `main` to keep your branch up-to-date.
5. Submit a Pull Request (PR) for review when your work is ready.
6. Tag reviewers (e.g., `@username`) in your PR.
7. Address any PR comments and resolve merge conflicts as they appear.
8. Only merge after receiving at least one approval from a teammate.

## Example

```shell
git checkout -b feature/user-authentication
# ... work on your changes ...
git add .
git commit -m "feature: add user authentication flow"
git pull origin main  # resolve conflicts if necessary
git push origin feature/user-authentication
# Then open a Pull Request on GitHub
```


