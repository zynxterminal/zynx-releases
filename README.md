<div align="center">

# ⚡ ZynxTerminal

**The terminal workspace built for how you actually ship.**

[![Latest Release](https://img.shields.io/github/v/release/zynxterminal/zynx-releases?color=6366f1&label=Release&logo=github&style=flat-square)](https://github.com/zynxterminal/zynx-releases/releases/latest)
[![Microsoft Store](https://img.shields.io/badge/Microsoft_Store-Get_it_free-0078D7?style=flat-square&logo=microsoft)](https://apps.microsoft.com/detail/9PKFLR5JVDRB?hl=en-us&gl=IN&ocid=pdpshare)
[![Platform](https://img.shields.io/badge/Platform-Windows%2010%20%7C%2011%20(x64)-blue?style=flat-square&logo=windows)](https://github.com/zynxterminal/zynx-releases/releases/latest)
[![License](https://img.shields.io/badge/License-Apache%202.0-green?style=flat-square)](./LICENSE)
[![Website](https://img.shields.io/badge/Website-usezynx.com-orange?style=flat-square)](https://usezynx.com)
[![Issues](https://img.shields.io/badge/Issue%20Tracker-GitHub%20Issues-purple?style=flat-square&logo=github)](https://github.com/zynxterminal/zynx-releases/issues)

<br />

[**Official Website**](https://usezynx.com) • [**Microsoft Store**](https://apps.microsoft.com/detail/9PKFLR5JVDRB?hl=en-us&gl=IN&ocid=pdpshare) • [**Downloads**](#-downloads-v105) • [**Release Notes**](https://github.com/zynxterminal/zynx-releases/releases) • [**Report an Issue**](https://github.com/zynxterminal/zynx-releases/issues/new/choose)

</div>

---

## 📦 Downloads (v1.0.5)

| Asset | Package Type | Architecture | Size | Checksum (SHA-256) | Download |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **Microsoft Store** | Official Windows Store App | `Windows x64` | Store Cloud | Verified by Microsoft | [🛍️ **Get from Store**](https://apps.microsoft.com/detail/9PKFLR5JVDRB?hl=en-us&gl=IN&ocid=pdpshare) |
| **`ZynxTerminal_1.0.5_x64-setup.exe`** | NSIS Setup (Recommended) | `Windows x64` | `10.19 MB` | `bad429732e1786520b6e45b4b4b3edad17f30ee7342d746d06f3c1a14ec9fa7d` | [⬇️ **Download .exe**](https://github.com/zynxterminal/zynx-releases/releases/download/v1.0.5/ZynxTerminal_1.0.5_x64-setup.exe) |
| **`ZynxTerminal_1.0.5_x64_en-US.msi`** | MSI Enterprise Installer | `Windows x64` | `12.65 MB` | `cbbf474c48000c4a7b0ec26edd049ccbad9b96164c3847e5435643e8ac5e1ea9` | [⬇️ **Download .msi**](https://github.com/zynxterminal/zynx-releases/releases/download/v1.0.5/ZynxTerminal_1.0.5_x64_en-US.msi) |

---

## 🚀 Quick Install

### Method 1: Microsoft Store (Zero Configuration)
Install directly from the [**Microsoft Store**](https://apps.microsoft.com/detail/9PKFLR5JVDRB?hl=en-us&gl=IN&ocid=pdpshare) for automated OS background updates.

### Method 2: Graphical Setup (.exe)
1. Download [**`ZynxTerminal_1.0.5_x64-setup.exe`**](https://github.com/zynxterminal/zynx-releases/releases/download/v1.0.5/ZynxTerminal_1.0.5_x64-setup.exe).
2. Run the installer and follow the quick setup wizard.
3. Launch **ZynxTerminal** from your Start Menu or Desktop.

### Method 3: PowerShell One-Liner
Open PowerShell and run:
```powershell
Invoke-WebRequest -Uri "https://github.com/zynxterminal/zynx-releases/releases/download/v1.0.5/ZynxTerminal_1.0.5_x64-setup.exe" -OutFile "$env:TEMP\ZynxTerminal-setup.exe"; Start-Process "$env:TEMP\ZynxTerminal-setup.exe"
```

---

## ✨ Key Capabilities

- **🤖 Native AI CLI Context**: Deep detection and acceleration for Claude Code, OpenAI Codex, Gemini CLI, and Aider. Commands are inserted (never auto-run) with safety guard protection against destructive commands (`rm -rf`, `git push --force`).
- **📑 OSC 133 Structured Command Blocks**: Transforms unstructured terminal stream into copyable, collapsible, structured command cards with execution duration, working directory, and exit codes.
- **🔄 Crash-Recoverable Workspaces**: Automatic debounced snapshots restore split-panes, profiles, tabs, and commands across crashes or reboots.
- **🎨 17 Curated Terminal Schemes**: Built-in Tokyo Night, Catppuccin Mocha, Dracula, Nord, One Dark Pro, Monokai Pro, Rosé Pine, Night Owl, and more.
- **⚡ High-Throughput Engine**: WebGL-accelerated 60 FPS rendering with zero dropped frames under heavy PTY output bursts.
- **🔒 First-Class SSH & SFTP**: OS credential manager isolation (DPAPI), ED25519 fingerprint review, and remote port forwarding.

---

## 💻 System Requirements

| Specification | Requirement |
| :--- | :--- |
| **Operating System** | Windows 10 (version 1809+) or Windows 11 |
| **Architecture** | 64-bit (`x64` / `AMD64`) |
| **Runtime** | Microsoft Edge WebView2 (pre-installed on Windows 10/11) |
| **Supported Shells** | PowerShell 7 / 5.1, Command Prompt (`cmd.exe`), Git Bash, WSL2 (Ubuntu, Debian, Arch) |

---

## 🔐 Verify Binary Integrity

You can verify the authenticity and integrity of downloaded binaries using PowerShell:

```powershell
Get-FileHash -Algorithm SHA256 "path\to\ZynxTerminal_1.0.0_x64-setup.exe"
# Hash: BAD429732E1786520B6E45B4B4B3EDAD17F30EE7342D746D06F3C1A14EC9FA7D

Get-FileHash -Algorithm SHA256 "path\to\ZynxTerminal_1.0.0_x64_en-US.msi"
# Hash: CBBF474C48000C4A7B0EC26EDD049CCBAD9B96164C3847E5435643E8AC5E1EA9
```

---

## 🤝 Community & Support

- **Bug Reports & Feature Requests**: [ZynxTerminal Issue Tracker](https://github.com/zynxterminal/zynx-releases/issues)
- **Security Vulnerabilities**: See [SECURITY.md](./SECURITY.md) or email `security@usezynx.com`
- **Documentation & Website**: [https://usezynx.com](https://usezynx.com)

---

<div align="center">
  <sub>Built with Tauri, Rust, React & xterm.js · Copyright © 2026 ZynxTerminal. All rights reserved.</sub>
</div>
