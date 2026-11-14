# Contributing Guidelines

## 1. Branching Strategy

We use Trunk-Based Development with Feature Branches.

- main: Production-ready code.
- develop: Integration branch.
- feat/: New feature development.
- fix/: Bug fixes.
- refactor/: Code refactoring.

## 2. Branch Naming Convention

- feat/cr-[id]-[short-name]
- fix/[bug-id]
- refactor/[module-name]

Examples:
- feat/cr-01-user-registration
- fix/bug-01-login-error
- refactor/auth-module

## 3. Conventional Commits

All commits must follow Conventional Commits.

- feat: New feature (MINOR)
- fix: Bug fix (PATCH)
- refactor: Internal refactoring (PATCH)
- test: Adding or updating tests
- docs: Documentation updates

## 4. Pull Request Rules

- All changes must be submitted through Pull Requests.
- Feature branches must target develop.
- Milestone releases must target main.
- At least one approval is required.
- Resolve review comments before merging.

## 5. Testing Requirements

Before submitting a Pull Request, run:

- npm test
- npm run lint

All automated tests must pass before merging.
