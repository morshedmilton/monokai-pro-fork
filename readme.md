# Monokai Pro Fork

[![Version](https://img.shields.io/badge/version-2.0.14--fork-blue.svg)](https://github.com/yourusername/monokai-pro-fork/releases)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![VS Code](https://img.shields.io/badge/VS%20Code-1.14%2B-blue.svg)](https://code.visualstudio.com/)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](https://github.com/yourusername/monokai-pro-fork/pulls)

> **Beautiful functionality for professional developers** — Community fork of Monokai Pro with license validation removed.

---

## ⚠️ Important Notice

**This is an unofficial community fork.** The original [Monokai Pro](https://monokai.pro) is a commercial product by [Monokai](https://monokai.pro). If you use this professionally, please consider [purchasing a license](https://monokai.pro) to support the original author and future development.

This fork exists to make the themes accessible while encouraging support for the original creator.

---

## ✨ Features

### 🎨 Themes (8 Variants)

| Theme | Type | Preview |
|-------|------|---------|
| **Monokai Pro** | Dark | ![Monokai Pro](https://raw.githubusercontent.com/monokai-pro/vscode/main/img/monokai-pro.png) |
| **Filter Octagon** | Dark | ![Filter Octagon](https://raw.githubusercontent.com/monokai-pro/vscode/main/img/monokai-pro-filter-octagon.png) |
| **Filter Ristretto** | Dark | ![Filter Ristretto](https://raw.githubusercontent.com/monokai-pro/vscode/main/img/monokai-pro-filter-ristretto.png) |
| **Filter Spectrum** | Dark | ![Filter Spectrum](https://raw.githubusercontent.com/monokai-pro/vscode/main/img/monokai-pro-filter-spectrum.png) |
| **Filter Machine** | Dark | ![Filter Machine](https://raw.githubusercontent.com/monokai-pro/vscode/main/img/monokai-pro-filter-machine.png) |
| **Monokai Pro Light** | Light | ![Light](https://raw.githubusercontent.com/monokai-pro/vscode/main/img/monokai-pro-light.png) |
| **Filter Sun** | Light | ![Filter Sun](https://raw.githubusercontent.com/monokai-pro/vscode/main/img/monokai-pro-light-filter-sun.png) |
| **Monokai Classic** | Dark | ![Classic](https://raw.githubusercontent.com/monokai-pro/vscode/main/img/monokai-classic.png) |

### 📁 Icon Packs (24 Variants)
- **Monokai Pro Icons** — Regular & Monochrome
- **Filter Octagon Icons** — Regular & Monochrome
- **Filter Ristretto Icons** — Regular & Monochrome
- **Filter Spectrum Icons** — Regular & Monochrome
- **Filter Machine Icons** — Regular & Monochrome
- **Monokai Pro Light Icons** — Regular & Monochrome
- **Filter Sun Icons** — Regular & Monochrome
- **Monokai Classic Icons** — Regular & Monochrome

### 🚀 What's Different from Original
- ✅ **No license validation** — Works out of the box
- ✅ **No purchase prompts** — Clean experience
- ✅ **Free & open source** — MIT licensed
- ✅ **Community maintained** — PRs welcome

---

## 📦 Installation

### From VSIX (Recommended)
1. Download the latest `.vsix` from [Releases](https://github.com/yourusername/monokai-pro-fork/releases)
2. In VS Code: `Extensions` → `⋮` → `Install from VSIX...`
3. Select the downloaded file

### From Source
```bash
# Clone the repository
git clone https://github.com/yourusername/monokai-pro-fork.git
cd monokai-pro-fork

# Install dependencies (for development)
npm install

# Package as VSIX
npx vsce package --no-dependencies

# Install the generated .vsix
code --install-extension theme-monokai-pro-fork-*.vsix
```

### Manual Install (Development)
```bash
# Symlink for live development
ln -s "$(pwd)" ~/.vscode/extensions/theme-monokai-pro-fork
# Restart VS Code
```

---

## 🎯 Usage

1. Open Command Palette (`Ctrl+Shift+P` / `Cmd+Shift+P`)
2. Run **Monokai Pro: Select Theme**
3. Choose your preferred variant
4. (Optional) Run **Monokai Pro: Activate Icons** for file icons

### Settings
```json
{
  "monokaiPro.fileIconsMonochrome": false
}
```

---

## 🛠 Development

### Project Structure
```
├── js/
│   ├── main.js          # Extension entry point (Node)
│   └── browser.js       # Extension entry point (Web)
├── themes/              # Color themes (8 variants)
├── icon-themes/         # File icon themes (24 variants)
├── themes/              # Color theme JSON files
├── package.json         # Extension manifest
└── LICENSE.txt          # MIT License
```

### Building
```bash
# Install vsce globally
npm install -g @vscode/vsce

# Package extension
vsce package --no-dependencies

# Publish to marketplace (requires publisher account)
vsce publish
```

### Testing Changes
```bash
# Watch for changes (requires @vscode/vscode-test)
npm run watch

# Run tests
npm test
```

---

## 🤝 Contributing

We welcome contributions! Please see our [Contributing Guide](CONTRIBUTING.md) for details.

### Quick Start
1. Fork the repository
2. Create a feature branch: `git checkout -b feature/amazing-feature`
3. Make your changes
4. Run linting: `npm run lint`
5. Commit: `git commit -m 'feat: add amazing feature'`
6. Push: `git push origin feature/amazing-feature`
7. Open a Pull Request

### Areas for Contribution
- 🐛 Bug fixes
- 🎨 New color filter variants
- 📁 Icon improvements
- 📝 Documentation
- 🌐 Localization
- ♿ Accessibility improvements

---

## 📋 Changelog

See [CHANGELOG.md](CHANGELOG.md) for release history.

### v2.0.14-fork (Latest)
- Forked from Monokai Pro v2.0.14
- Removed license validation logic
- Updated to MIT license
- Added community contribution guidelines

---

## 📄 License

**MIT License** — See [LICENSE.txt](LICENSE.txt) for details.

```
Original work: Copyright (c) 2017-2025 Monokai
Fork changes:  Copyright (c) 2025 Community Contributors
```

> **Please support the original author** by purchasing a license at [monokai.pro](https://monokai.pro) if you use this professionally.

---

## 🙏 Acknowledgments

- **[Monokai](https://monokai.pro)** — Original creator of Monokai Pro
- **[Wimer Hazenberg](https://monokai.pro/about)** — Author of the original Monokai color scheme (2006)
- **Community contributors** — Everyone who helps improve this fork

---

## 🔗 Links

- **Original Monokai Pro**: [monokai.pro](https://monokai.pro)
- **VS Code Marketplace**: [Monokai Pro](https://marketplace.visualstudio.com/items?itemName=monokai.theme-monokai-pro-vscode)
- **Issues**: [GitHub Issues](https://github.com/yourusername/monokai-pro-fork/issues)
- **Discussions**: [GitHub Discussions](https://github.com/yourusername/monokai-pro-fork/discussions)

---

<div align="center">

**Made with ❤️ by the community**

*If you find this useful, consider starring ⭐ the repo and supporting the original author!*

</div>