# 📦 Cellaris POS — Official Releases

Welcome to the official binary distribution hub for **Cellaris POS** — an open-source, high-speed, offline-first retail Point-of-Sale (POS) and ERP desktop appliance.

---

## 🚀 Download Latest Release

| Platform | Format | Package | Download Link |
| :--- | :--- | :--- | :--- |
| 🪟 **Windows** (64-bit) | `.exe` | Windows 1-Click Installer | [**📥 Download CellarisPOS-Setup.exe**](https://github.com/hammadmunir959/cellaris-pos-releases/releases/latest/download/CellarisPOS-Setup.exe) |
| 🐧 **Linux** (x86_64) | `.snap` | Canonical Snap Package | [**📥 Download CellarisPOS.snap**](https://github.com/hammadmunir959/cellaris-pos-releases/releases/latest/download/CellarisPOS.snap) |
| 📋 **Release Notes** | Web | Changelog & Asset Hashes | [**🔗 View Latest Release on GitHub**](https://github.com/hammadmunir959/cellaris-pos-releases/releases/latest) |

---

## 💻 Installation Instructions

### 🪟 Windows Installation
1. Click the download link above to download **`CellarisPOS-Setup.exe`**.
2. Run the installer (takes ~30 seconds).
3. The installer creates a desktop shortcut and starts the application automatically.
4. On first launch, follow the onboarding wizard to configure your store profile and initial SuperAdmin account.

### 🐧 Linux Installation (Snap)
1. Download **`CellarisPOS.snap`** or install via terminal:
   ```bash
   sudo snap install --dangerous --classic CellarisPOS.snap
   ```
2. Launch Cellaris POS from your applications menu or run:
   ```bash
   cellaris-pos
   ```

---

## 🛡️ Security & Integrity

- **Source Code**: Audited and compiled from [hammadmunir959/cellaris-pos](https://github.com/hammadmunir959/cellaris-pos).
- **Process Isolation**: Context isolation enabled, zero renderer node integration, typed IPC preload security boundaries.
- **Encrypted Local Storage**: Database cloaked via AES-256 SQLite database engine.
- **Automated CI/CD**: All binaries in this repository are compiled automatically on clean GitHub Actions runners (`windows-latest` & `ubuntu-latest`) upon every release commit.

---

## 🔗 Related Links

- 🧑‍💻 **Source Code Repository**: [https://github.com/hammadmunir959/cellaris-pos](https://github.com/hammadmunir959/cellaris-pos)
- 🐛 **Issue Tracker**: [Report an Issue or Bug](https://github.com/hammadmunir959/cellaris-pos/issues)
- 👤 **Maintainer**: [@hammadmunir959](https://github.com/hammadmunir959)
