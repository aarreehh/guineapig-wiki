# Contributing to Guinea Pig Wiki 🐹

First off — thank you for taking the time to contribute! Whether you're fixing a typo, adding a breed profile, or building a new feature, every contribution helps make this wiki better for guinea pig owners everywhere.

Please take a moment to read this guide before submitting anything.

---

## Table of Contents

- [Code of Conduct](#code-of-conduct)
- [How Can I Contribute?](#how-can-i-contribute)
  - [Reporting Bugs](#reporting-bugs)
  - [Suggesting Features](#suggesting-features)
  - [Contributing Code](#contributing-code)
- [Development Setup](#development-setup)
- [Style Guidelines](#style-guidelines)
- [Commit Messages](#commit-messages)

---

## Code of Conduct

This project is governed by our [Code of Conduct](./CODE_OF_CONDUCT.md). By participating, you agree to uphold its standards. Please report unacceptable behaviour to the maintainers.

---

## How Can I Contribute?

### Reporting Bugs

Found something broken? Please [open a bug report](../../issues/new?template=bug_report.md) and include:

- A clear, descriptive title
- Steps to reproduce the issue
- What you expected to happen vs what actually happened
- Screenshots if relevant
- Your OS, browser, and Node.js version

### Suggesting Features

Have an idea for a new feature or improvement? [Open a feature request](../../issues/new?template=feature_request.md). Describe the problem you're trying to solve and your proposed solution.

### Contributing Code

1. **Check existing issues and PRs** to avoid duplicating effort.
2. **Open an issue first** for significant changes so we can discuss the approach before you invest time coding it.
3. For small fixes (typos, minor UI tweaks), feel free to open a PR directly.

---

## Development Setup

```bash
# 1. Fork the repository and clone your fork
git clone https://github.com/your-username/guineapig-wiki.git
cd guineapig-wiki

# 2. Install dependencies
pnpm install

# 3. Create a feature branch
git checkout -b feat/your-feature-name

# 4. Start the dev server
pnpm dev

# 5. Make your changes, then lint before committing
pnpm lint
```

---

## Style Guidelines

- **TypeScript** — all new code must be typed. Avoid `any`.
- **React** — use functional components and hooks. No class components.
- **Formatting** — the project uses ESLint. Run `pnpm lint` and fix any errors before pushing.
- **File naming** — use `PascalCase` for components and `camelCase` for utilities/hooks.
- **Accessibility** — new UI elements should include appropriate ARIA labels and keyboard navigation.

---

## Commit Messages

We follow [Conventional Commits](https://www.conventionalcommits.org/):

```
<type>: <short summary>
```

Common types:

| Type | When to use |
|---|---|
| `feat` | A new feature |
| `fix` | A bug fix |
| `docs` | Documentation changes only |
| `style` | Formatting, no logic change |
| `refactor` | Code restructuring, no feature change |
| `chore` | Tooling, dependencies, config |

**Examples:**
```
feat: add safe food list page
fix: broken link in health guide
docs: update contributing guide
```

---

Thank you again for contributing. The piggies appreciate it 🥦
