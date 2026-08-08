# Contributing to Monokai Pro Fork

Thank you for your interest in contributing! This document provides guidelines for contributing to this community fork.

## 📋 Table of Contents
- [Code of Conduct](#code-of-conduct)
- [How Can I Contribute?](#how-can-i-contribute)
- [Development Setup](#development-setup)
- [Pull Request Process](#pull-request-process)
- [Coding Standards](#coding-standards)
- [Commit Messages](#commit-messages)
- [Reporting Bugs](#reporting-bugs)
- [Suggesting Features](#suggesting-features)

---

## Code of Conduct

This project follows the [Contributor Covenant Code of Conduct](CODE_OF_CONDUCT.md). By participating, you agree to uphold this code.

---

## How Can I Contribute?

### 🐛 Report Bugs
- Use the [bug report template](.github/ISSUE_TEMPLATE/bug_report.md)
- Check existing issues first
- Provide clear reproduction steps

### 💡 Suggest Features
- Use the [feature request template](.github/ISSUE_TEMPLATE/feature_request.md)
- Explain the use case and benefits
- Consider if it aligns with project scope

### 🎨 Improve Themes/Icons
- Submit color adjustments with before/after screenshots
- Ensure accessibility (contrast ratios)
- Test across light/dark variants

### 📝 Improve Documentation
- Fix typos, clarify instructions
- Add translations
- Update README for new features

### 🔧 Code Contributions
- Fix bugs in theme loading/logic
- Add new configuration options
- Improve build/packaging process

---

## Development Setup

### Prerequisites
- Node.js 16+
- VS Code 1.70+
- Git

### Local Development
```bash
# 1. Fork and clone
git clone https://github.com/YOUR_USERNAME/monokai-pro-fork.git
cd monokai-pro-fork

# 2. Install packaging tool
npm install -g @vscode/vsce

# 3. Make changes to themes/ or js/

# 4. Test locally
vsce package --no-dependencies
code --install-extension theme-monokai-pro-fork-*.vsix

# 5. Restart VS Code and test your changes
```

### Theme Development Tips
- Edit JSON files in `themes/` for color themes
- Edit JSON files in `icon-themes/` for icon themes
- Use VS Code's **Developer: Inspect Editor Tokens and Scopes** to find scope names
- Test both light and dark variants

---

## Pull Request Process

1. **Fork** the repository
2. **Create a branch** from `main`:
   ```bash
   git checkout -b feature/your-feature-name
   # or
   git checkout -b fix/your-bug-fix
   ```
3. **Make your changes** with clear, focused commits
4. **Test thoroughly** — verify all theme variants work
5. **Update documentation** if needed (README, CHANGELOG)
6. **Push** to your fork
7. **Open a Pull Request** against `main`

### PR Requirements
- ✅ Clear title and description
- ✅ References related issue(s)
- ✅ Screenshots for visual changes
- ✅ Passes any CI checks
- ✅ No VSIX files in PR (generated on release)

### Review Process
- Maintainers review within 7 days
- Address feedback promptly
- Squash commits before merge (maintainers will handle)

---

## Coding Standards

### Theme Files (JSON)
- Use 2-space indentation
- Sort keys alphabetically where practical
- Use hex colors (`#RRGGBB`) or named CSS colors
- Include comments for non-obvious values (VS Code supports comments in theme JSON)

### JavaScript (js/main.js, js/browser.js)
- ES6+ syntax
- 2-space indentation
- Semicolons required
- Descriptive variable names
- JSDoc for exported functions

### Commit Messages
Follow [Conventional Commits](https://www.conventionalcommits.org/):

```
<type>[optional scope]: <description>

[optional body]

[optional footer(s)]
```

**Types:**
- `feat` — New feature
- `fix` — Bug fix
- `docs` — Documentation only
- `style` — Formatting, missing semicolons, etc.
- `refactor` — Code restructuring
- `test` — Adding tests
- `chore` — Maintenance, build changes

**Examples:**
```
feat: add new Filter Ocean color variant
fix: resolve icon loading issue on Windows
docs: update installation instructions
refactor: simplify theme registration logic
```

---

## Reporting Bugs

**Before submitting:**
1. Check [existing issues](https://github.com/yourusername/monokai-pro-fork/issues)
2. Try latest version
3. Test with minimal setup

**Include in report:**
- VS Code version (`Help > About`)
- OS and version
- Theme variant affected
- Steps to reproduce
- Expected vs actual behavior
- Screenshots if visual

---

## Suggesting Features

**Before submitting:**
1. Check [existing issues](https://github.com/yourusername/monokai-pro-fork/issues) and [discussions](https://github.com/yourusername/monokai-pro-fork/discussions)
2. Consider if it fits project scope (theme/icon focused)

**Include in request:**
- Clear description of the feature
- Use case / problem it solves
- Mockups or examples if visual
- Willingness to implement

---

## Release Process

Maintainers handle releases:
1. Update version in `package.json`
2. Update `CHANGELOG.md`
3. Create git tag: `git tag v2.0.15-fork`
4. Push tag: `git push origin v2.0.15-fork`
5. GitHub Action builds and attaches VSIX to release
6. Publish to marketplace (optional)

---

## Questions?

- Open a [Discussion](https://github.com/yourusername/monokai-pro-fork/discussions)
- Check existing [Issues](https://github.com/yourusername/monokai-pro-fork/issues)

---

**Thank you for contributing!** 🎉