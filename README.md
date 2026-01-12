# DevSecOps Showcase Monorepo

A monorepo showcasing DevSecOps practices and implementations.

## Structure
```
├── .github/workflows/    # CI/CD pipelines
├── infrastructure/       # IaC configurations
├── applications/        # Sample applications
├── security/           # Security tooling and policies
├── docs/              # Documentation
├── scripts/           # Automation scripts
└── tests/            # Testing suites
```

## Commit Message Standards

This repository follows the [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/) specification.

Commit messages must be structured as follows:

```
<type>[optional scope]: <description>

[optional body]

[optional footer(s)]
```

**Types:**
- `feat:` A new feature
- `fix:` A bug fix
- `docs:` Documentation changes
- `style:` Code style changes (formatting, missing semi-colons, etc.)
- `refactor:` Code refactoring
- `perf:` Performance improvements
- `test:` Adding or updating tests
- `chore:` Maintenance tasks, dependency updates
- `cicd:` CI/CD changes

**Example:**
```
feat(auth): add JWT-based authentication

Implement JWT-based authentication with refresh token support.
Includes login, logout, and token validation endpoints.

Fixes #123
```