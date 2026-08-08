<p align="center">
  <a href="https://github.com/morshedmilton/monokai-pro-fork">
    <img src="https://raw.githubusercontent.com/monokai-pro/vscode/main/img/monokai-pro.png" alt="Monokai Pro Fork" width="600">
  </a>
</p>

<h1 align="center">Monokai Pro Fork</h1>

<p align="center">
  <strong>Beautiful functionality for professional developers</strong> — Community fork of Monokai Pro with license validation removed.
</p>

<p align="center">
  <a href="https://github.com/morshedmilton/monokai-pro-fork/releases"><img src="https://img.shields.io/github/v/release/morshedmilton/monokai-pro-fork?include_prereleases&label=version&style=for-the-badge" alt="Version"></a>
  <a href="https://opensource.org/licenses/MIT"><img src="https://img.shields.io/badge/License-MIT-green?style=for-the-badge" alt="License"></a>
  <a href="https://code.visualstudio.com/"><img src="https://img.shields.io/badge/VS%20Code-1.14%2B-blue?style=for-the-badge&logo=visual-studio-code" alt="VS Code"></a>
  <a href="https://github.com/morshedmilton/monokai-pro-fork/pulls"><img src="https://img.shields.io/badge/PRs-welcome-brightgreen?style=for-the-badge" alt="PRs Welcome"></a>
  <a href="https://github.com/morshedmilton/monokai-pro-fork/stargazers"><img src="https://img.shields.io/github/stars/morshedmilton/monokai-pro-fork?style=for-the-badge" alt="Stars"></a>
</p>

---

## ⚠️ Important Notice

> **This is an unofficial community fork.** The original [Monokai Pro](https://monokai.pro) is a commercial product by [Monokai](https://monokai.pro).
>
> **If you use this professionally, please consider [purchasing a license](https://monokai.pro) to support the original author and future development.**
>
> This fork exists to make the themes accessible while encouraging support for the original creator.

---

## ✨ Why This Fork?

| Original Monokai Pro | This Fork |
|---------------------|-----------|
| 🔒 Trial with license validation | ✅ **Free forever — no validation** |
| 💰 Paid license required | ✅ **MIT licensed — open source** |
| 🔔 Purchase prompts & popups | ✅ **Clean experience — no nagging** |
| 🏢 Single maintainer | ✅ **Community driven — PRs welcome** |

---

## 🎨 Themes (8 Beautiful Variants)

### Dark Themes

| Theme | Preview | Palette |
|-------|---------|---------|
| **Monokai Pro** | <a href="https://raw.githubusercontent.com/monokai-pro/vscode/main/img/monokai-pro.png"><img src="https://raw.githubusercontent.com/monokai-pro/vscode/main/img/monokai-pro.png" width="120"></a> | `#272822` `#F92672` `#A6E22E` `#FD971F` |
| **Filter Octagon** | *Image unavailable* | `#2D2A2E` `#FC618D` `#8CE10B` `#FD9353` |
| **Filter Ristretto** | *Image unavailable* | `#23241F` `#F9265D` `#A5DC86` `#FD971F` |
| **Filter Spectrum** | *Image unavailable* | `#1B1D1E` `#FF6188` `#A9DC76` `#FFD866` |
| **Filter Machine** | *Image unavailable* | `#191919` `#FF8080` `#A8E063` `#FFCC33` |
| **Monokai Classic** | *Image unavailable* | `#272822` `#F92672` `#A6E22E` `#E6DB74` |

### Light Themes

| Theme | Preview | Palette |
|-------|---------|---------|
| **Monokai Pro Light** | *Image unavailable* | `#FCFCFA` `#D81B60` `#3A8E00` `#F57C00` |
| **Filter Sun** | *Image unavailable* | `#FDF6E3` `#D33682` `#859900` `#B58900` |

> **Note:** Only the main Monokai Pro preview image is publicly available from the original repo. Other variant images return 404. Color codes above represent each theme's signature palette: **Background / Accent / Green / Yellow**.

---

## 📁 Icon Packs (24 Variants)

All icon themes include **Regular** and **Monochrome** versions:

- 🎨 **Monokai Pro Icons**
- 🔷 **Filter Octagon Icons**
- 🔶 **Filter Ristretto Icons**
- 🌈 **Filter Spectrum Icons**
- ⚙️ **Filter Machine Icons**
- ☀️ **Monokai Pro Light Icons**
- 🌅 **Filter Sun Icons**
- 📜 **Monokai Classic Icons**

---

## 🚀 Quick Install

### Option 1: Download VSIX (Easiest)
[![Download](https://img.shields.io/badge/Download-Latest%20VSIX-blue?style=for-the-badge&logo=visual-studio-code)](https://github.com/morshedmilton/monokai-pro-fork/releases/latest)

1. Download `theme-monokai-pro-fork-*.vsix` from [Releases](https://github.com/morshedmilton/monokai-pro-fork/releases)
2. VS Code → Extensions → `⋮` → **Install from VSIX...**
3. Select the downloaded file
4. `Ctrl+Shift+P` → **Monokai Pro: Select Theme**

### Option 2: Install from Source
```bash
# Clone & install
git clone https://github.com/morshedmilton/monokai-pro-fork.git
cd monokai-pro-fork
npm install -g @vscode/vsce
vsce package --no-dependencies
code --install-extension theme-monokai-pro-fork-*.vsix
```

### Option 3: Development Symlink
```bash
# Live development (changes reflect immediately)
git clone https://github.com/morshedmilton/monokai-pro-fork.git
ln -s "$(pwd)/monokai-pro-fork" ~/.vscode/extensions/theme-monokai-pro-fork
# Restart VS Code
```

---

## 🎯 Usage

| Action | Command |
|--------|---------|
| **Select Theme** | `Ctrl+Shift+P` → `Monokai Pro: Select Theme` |
| **Activate Icons** | `Ctrl+Shift+P` → `Monokai Pro: Activate Icons` |
| **Enter License** | `Ctrl+Shift+P` → `Monokai Pro: Enter License` *(no-op in fork)* |

### Settings
```json
{
  "monokaiPro.fileIconsMonochrome": false
}
```

---

## 🎨 Theme Palettes at a Glance

<details>
<summary><strong>Click to expand all color palettes</strong></summary>

| Theme | Background | Accent | Green | Yellow/Orange |
|-------|------------|--------|-------|---------------|
| Monokai Pro | `#272822` | `#F92672` | `#A6E22E` | `#FD971F` |
| Filter Octagon | `#2D2A2E` | `#FC618D` | `#8CE10B` | `#FD9353` |
| Filter Ristretto | `#23241F` | `#F9265D` | `#A5DC86` | `#FD971F` |
| Filter Spectrum | `#1B1D1E` | `#FF6188` | `#A9DC76` | `#FFD866` |
| Filter Machine | `#191919` | `#FF8080` | `#A8E063` | `#FFCC33` |
| Monokai Classic | `#272822` | `#F92672` | `#A6E22E` | `#E6DB74` |
| Monokai Pro Light | `#FCFCFA` | `#D81B60` | `#3A8E00` | `#F57C00` |
| Filter Sun | `#FDF6E3` | `#D33682` | `#859900` | `#B58900` |

</details>

---

## 🛠 For Developers

### Project Structure
```
monokai-pro-fork/
├── 📁 js/
│   ├── main.js          # Node entry point
│   └── browser.js       # Web entry point
├── 📁 themes/           # 8 color theme JSON files
├── 📁 icon-themes/      # 24 icon theme JSON files + font
├── 📄 package.json      # Extension manifest
├── 📄 LICENSE.txt       # MIT License
├── 📄 README.md         # This file
├── 📄 CHANGELOG.md      # Release history
├── 📄 CONTRIBUTING.md   # Contribution guide
└── 📁 .github/          # CI/CD & issue templates
```

### Build Commands
```bash
# Install packaging tool
npm install -g @vscode/vsce

# Package as VSIX
vsce package --no-dependencies

# Publish to marketplace (requires publisher)
vsce publish
```

---

## 🤝 Contributing

We ❤️ contributions! See [CONTRIBUTING.md](CONTRIBUTING.md) for details.

### Quick Start
```bash
# 1. Fork the repo
# 2. Create branch
git checkout -b feature/your-feature

# 3. Make changes (themes/ or js/)
# 4. Test locally
vsce package --no-dependencies

# 5. Commit & push
git commit -m 'feat: your amazing feature'
git push origin feature/your-feature

# 6. Open Pull Request
```

### Ways to Contribute
- 🐛 **Bug fixes** — Theme rendering, icon issues
- 🎨 **New color variants** — Design new filter themes
- 📁 **Icon improvements** — Add missing file types
- 📝 **Documentation** — Improve guides, translations
- ♿ **Accessibility** — Contrast, color-blind support
- 🌐 **Localization** — Translate UI strings

---

## 📋 Changelog

See [CHANGELOG.md](CHANGELOG.md) for full history.

### v2.0.14-fork (Latest)
- 🆓 Removed all license validation
- 🆓 Removed purchase prompts & popups
- 📜 Changed to MIT license
- 📦 Repackaged as `theme-monokai-pro-fork`
- 🏷️ Version: `2.0.14-fork`

---

## 📄 License

**MIT License** — See [LICENSE.txt](LICENSE.txt)

```
Original work: Copyright (c) 2017-2025 Monokai
Fork changes:  Copyright (c) 2025 Community Contributors
```

> **Please support the original author** by purchasing a license at [monokai.pro](https://monokai.pro) if you use this professionally.

---

## 🙏 Acknowledgments

| Contributor | Role |
|-------------|------|
| **[Monokai](https://monokai.pro)** | Original creator of Monokai Pro |
| **[Wimer Hazenberg](https://monokai.pro/about)** | Author of original Monokai (2006) |
| **Community** | Fork maintainers & contributors |

---

## 🔗 Links

| Link | Description |
|------|-------------|
| [🏠 Repository](https://github.com/morshedmilton/monokai-pro-fork) | Source code & issues |
| [📦 Releases](https://github.com/morshedmilton/monokai-pro-fork/releases) | Download VSIX files |
| [🐛 Issues](https://github.com/morshedmilton/monokai-pro-fork/issues) | Bug reports & features |
| [💬 Discussions](https://github.com/morshedmilton/monokai-pro-fork/discussions) | Community Q&A |
| [💎 Original](https://monokai.pro) | Buy official license |
| [🛒 Marketplace](https://marketplace.visualstudio.com/items?itemName=monokai.theme-monokai-pro-vscode) | Official extension |

---

<div align="center">

### ⭐ Star this repo if you find it useful!

**Made with ❤️ by the community** · [MIT Licensed](LICENSE.txt)

*Support the original author: [monokai.pro](https://monokai.pro)*

</div>

---

<details>
<summary><strong>📊 Repository Stats</strong></summary>

![GitHub repo size](https://img.shields.io/github/repo-size/morshedmilton/monokai-pro-fork)
![GitHub last commit](https://img.shields.io/github/last-commit/morshedmilton/monokai-pro-fork)
![GitHub issues](https://img.shields.io/github/issues/morshedmilton/monokai-pro-fork)
![GitHub pull requests](https://img.shields.io/github/issues-pr/morshedmilton/monokai-pro-fork)

</details>