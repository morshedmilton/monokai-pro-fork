# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [2.0.14-fork] - 2025-08-09

### Added
- Initial community fork release
- MIT License
- Professional README with badges and installation instructions
- CONTRIBUTING.md with contribution guidelines
- CODE_OF_CONDUCT.md (Contributor Covenant)
- GitHub issue templates (bug report, feature request)
- GitHub Actions workflow for automated VSIX building and releases
- .gitignore for proper version control

### Changed
- **BREAKING**: Removed all license validation logic from `js/main.js` and `js/browser.js`
- **BREAKING**: Removed purchase prompts and "Thanks for your purchase" notifications
- Updated `package.json`:
  - Name: `theme-monokai-pro-vscode` → `theme-monokai-pro-fork`
  - Display Name: `Monokai Pro` → `Monokai Pro Fork`
  - Publisher: `monokai` → `community-fork`
  - Version: `2.0.14` → `2.0.14-fork`
  - Pricing: `Trial` → `Free`
  - License: Proprietary → `MIT`
  - Repository, bugs, homepage URLs updated for GitHub
- Updated README to clearly indicate this is a community fork
- Encourages supporting original author by purchasing license

### Removed
- License key validation functions (`et`, `te`, `ee`)
- License key storage and verification
- External URL opening for license purchase (`Ct`, `_e`, `It` functions)
- Purchase thank-you message popups (`vt`, `Se` functions)
- Trial expiration logic

### Security
- No longer collects or transmits license information
- No external network requests for validation

---

## Upstream History (Monokai Pro v2.0.14)

This fork is based on Monokai Pro v2.0.14 by Monokai. Original changelog:

### [2.0.14] - 2024-08-05
- [new] agent window theme
- [fix] icons occasionally resetting when an unrelated setting changed

### [2.0.13] - 2024-04-01
- [fix] activity badges
- [fix] input background color
- [fix] inlay hint parameter / type discrimination
- [new] inline edit colors

### [2.0.12] - 2024-01-07
- [new] web assembly icon
- [new] solidity icon
- [new] gemini icon

### [2.0.11] - 2023-12-17
- [new] vite icon
- [new] odin icon
- [new] assembly icon

### [2.0.10] - 2023-11-03
- [new] skill icon
- [new] zig icon
- [new] polyglot notebook icon
- [new] update icon set when "auto detect system color mode" is active
- [new] license / email information is stored in secret storage

### [2.0.9] - 2023-10-17
- [new] jupyter icon
- [new] gradle icon
- [new] js decorator color
- [fix] disabled item color

### [2.0.8] - 2023-10-04
- [new] agents icon
- [new] claude icon
- [new] gleam icon
- [new] groq icon
- [new] nim icon
- [new] nix icon
- [fix] list drop background

### [2.0.7] - 2023-06-04
- [new] F# icon
- [new] JavaScript / TypeScript unit test icons
- [fix] gitconfig icon
- [fix] namespace coloring
- [fix] remote extension badge color
- [fix] suggestion select background

### [2.0.6] - 2023-01-15
- [new] cuda c++ icons
- [new] bun.lock icon
- [fix] UI checkbox, button color tweaks

### [2.0.5] - 2022-12-04
- [fix] rust improvements
- [fix] ansible improvements

### [2.0.2] - 2022-11-03
- [fix] light theme categorization
- [fix] UI tweaks

### [2.0.1] - 2022-10-24
- [fix] Light activity bar fix

### [2.0.0] - 2022-10-23
- [new] Monokai Pro Light
- [new] Monokai Pro Light (filter Sun)
- [new] next.config.ts icon
- [new] bun.lockb icon
- [new] kotlin icon

### [1.3.2] - 2022-04-21
- [new] gulpfile icon

### [1.3.1] - 2022-04-18
- [fix] command center debug background
- [fix] vue icon
- [fix] various file icon syntax scoping fixes

### [1.3.0] - 2022-04-17
- [new] adonisjs icon
- [new] ansible icon
- [new] archive icon
- [new] bun icon
- [new] composer icon
- [new] gruntfile icon
- [new] license icon
- [new] next icon
- [new] nextjs icon
- [new] nginx icon
- [new] nodejs icon
- [new] opengl icon
- [new] postcss icon
- [new] rollup icon
- [new] settings icon
- [new] stylelint icon
- [new] sublime icon
- [new] tailwind icon
- [new] visualstudio icon
- [new] webpack icon
- [new] yarn icon
- [fix] various color fixes

### [1.2.2] - 2021-12-22
- [new] inlay hints colors
- [new] astro icon
- [new] mdx icon
- [fix] typescript color improvements
- [fix] java import color fix
- [fix] various color fixes

### [1.2.1] - 2021-05-03
- [new] profile badge color
- [fix] trailing comma fix
- [fix] link tailwind syntax to css icon
- [fix] transparent scroll bar in diff view
- [fix] markdown punctuation in links

### [1.2.0] - 2020-11-27
- [new] web extension compatible

### [1.1.21] - 2020-08-27
- [new] added hare icon
- [new] added clojure icon
- [new] added notebook colors
- [new] added test colors
- [new] added menu colors
- [new] added inline value colors
- [fix] fixed various user interface colors

### [1.1.20] - 2020-01-19
- [new] added svelte icon
- [new] added rescript icon
- [new] added support for untrusted workspaces
- [new] added support for colored bracket pairs
- [fix] constants in python
- [fix] docstrings in python

### [1.1.19] - 2019-04-06
- [fix] editor theme additions
- [fix] ruby syntax highlight improvements

### [1.1.18] - 2018-11-18
- [new] chart colors
- [new] crystal icon
- [fix] git decoration colors
- [fix] vue custom component color

---

## Versioning Scheme

This fork uses **Semantic Versioning** with a `-fork` suffix:
- `MAJOR.MINOR.PATCH-fork`
- Example: `2.0.15-fork`

The base version matches the upstream Monokai Pro version this fork is based on.
The `-fork` suffix distinguishes community releases from official ones.

---

## Release Process

1. Update version in `package.json`
2. Update this CHANGELOG.md
4. Create git tag: `git tag v2.0.15-fork`
5. Push tag: `git push origin v2.0.15-fork`
6. GitHub Action automatically builds VSIX and creates release
7. (Optional) Publish to VS Code Marketplace

---

## Links

- [GitHub Releases](https://github.com/yourusername/monokai-pro-fork/releases)
- [Original Monokai Pro](https://monokai.pro)
- [VS Code Marketplace (Original)](https://marketplace.visualstudio.com/items?itemName=monokai.theme-monokai-pro-vscode)
