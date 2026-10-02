<div align="center">

# ✒️ OmniQuill

**A sleek, cross-platform Markdown → PDF desktop editor**

Write, preview, and export beautifully typeset PDFs — on Windows, Linux, and macOS.

English | [简体中文](README.zh-CN.md)

![](https://img.shields.io/badge/.NET-8.0-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![](https://img.shields.io/badge/Avalonia-11.2-8B5CF6?style=for-the-badge&logo=avalonia&logoColor=white)
![](https://img.shields.io/badge/platform-Windows%20%7C%20Linux%20%7C%20macOS-4FC08D?style=for-the-badge)
[![Release](https://img.shields.io/github/v/release/xianshi3/omni-quill?style=for-the-badge&logo=github&logoColor=white)](https://github.com/xianshi3/omni-quill/releases/latest)
[![Downloads](https://img.shields.io/github/downloads/xianshi3/omni-quill/total?style=for-the-badge&label=downloads&logo=github&logoColor=white)](https://github.com/xianshi3/omni-quill/releases)
[![Build](https://img.shields.io/github/actions/workflow/status/xianshi3/omni-quill/ci.yml?branch=master&style=for-the-badge&label=build&logo=githubactions&logoColor=white)](https://github.com/xianshi3/omni-quill/actions/workflows/ci.yml)
[![License: MIT](https://img.shields.io/github/license/xianshi3/omni-quill?style=for-the-badge&label=license&color=EB5424)](LICENSE)

[**⬇️ Download**](#%EF%B8%8F-download) · [**✨ Features**](#%EF%B8%8F-features) · [**🚀 Getting Started**](#%EF%B8%8F-getting-started) · [**🤝 Contributing**](#%EF%B8%8F-contributing)

</div>

---

<div align="center">
  <table>
    <tr>
      <td align="center"><b>🌙 Dark Theme</b></td>
      <td align="center"><b>☀️ Light Theme</b></td>
    </tr>
    <tr>
      <td><img src="https://github.com/user-attachments/assets/041a015d-450c-45fc-84be-29069c59c075" width="100%" alt="Dark theme" /></td>
      <td><img src="https://github.com/user-attachments/assets/7288f666-32d2-4b14-b781-a06e0e5ba20b" width="100%" alt="Light theme" /></td>
    </tr>
  </table>
</div>

---

## ✨ Features

<table>
  <tr>
    <td width="33%">🔍 <b>Live Preview</b><br><sub>Real-time rendering powered by Markdig AST — full GFM syntax</sub></td>
    <td width="33%">🎨 <b>3 Themes</b><br><sub>Dark, Light & Gray with smooth transition animations</sub></td>
    <td width="33%">🌐 <b>EN / 中文</b><br><sub>Instant language switching across the whole UI</sub></td>
  </tr>
  <tr>
    <td>📄 <b>PDF &amp; HTML Export</b><br><sub>Page size, margins &amp; font — or styled HTML with embedded CSS</sub></td>
    <td>🔤 <b>CJK Ready</b><br><sub>Bundled SimSun font for flawless Chinese rendering in PDFs</sub></td>
    <td>📊 <b>Live Statistics</b><br><sub>Line, word &amp; character counts at a glance</sub></td>
  </tr>
  <tr>
    <td>💾 <b>Auto-Save</b><br><sub>Backup every 60 seconds — your work is never lost</sub></td>
    <td>📁 <b>Recent Files</b><br><sub>Persistent list of your last 10 documents</sub></td>
    <td>🎯 <b>Find &amp; Replace</b><br><sub>Case-sensitive search with match count &amp; navigation</sub></td>
  </tr>
  <tr>
    <td>🖱️ <b>Drag &amp; Drop</b><br><sub>Drop a <code>.md</code> file anywhere to open it instantly</sub></td>
    <td>🔎 <b>Zoom 50–200%</b><br><sub>Editor font zoom via toolbar buttons or shortcuts</sub></td>
    <td>⌨️ <b>Full Shortcuts</b><br><sub>Undo/Redo, formatting &amp; everything you'd expect</sub></td>
  </tr>
</table>

<details>
<summary><b>⌨️ Keyboard Shortcuts</b></summary>

| Shortcut | Action |
|---|---|
| `Ctrl+N` | New File |
| `Ctrl+O` | Open File |
| `Ctrl+S` | Save File |
| `Ctrl+Z` / `Ctrl+Y` | Undo / Redo |
| `Ctrl+F` | Find |
| `Ctrl+B` / `Ctrl+I` | Bold / Italic |
| `Ctrl+P` | Toggle Preview |
| `Ctrl++` / `Ctrl+-` / `Ctrl+0` | Zoom In / Out / Reset |

</details>

---

## ⬇️ Download

Grab the latest release for your platform — **no .NET runtime required**, everything is bundled:

| Platform | Architecture | Download |
|---|---|---|
| 🪟 Windows | x64 | [**OmniQuill-win-x64.zip**](https://github.com/xianshi3/omni-quill/releases/latest/download/OmniQuill-win-x64.zip) |
| 🐧 Linux | x64 | [**OmniQuill-linux-x64.zip**](https://github.com/xianshi3/omni-quill/releases/latest/download/OmniQuill-linux-x64.zip) |
| 🍎 macOS | Apple Silicon | [**OmniQuill-osx-arm64.zip**](https://github.com/xianshi3/omni-quill/releases/latest/download/OmniQuill-osx-arm64.zip) |
| 🍎 macOS | Intel | [**OmniQuill-osx-x64.zip**](https://github.com/xianshi3/omni-quill/releases/latest/download/OmniQuill-osx-x64.zip) |

<details>
<summary><b>Platform notes</b></summary>

- **Windows** — unzip and run `OmniQuill.Desktop.exe`
- **Linux** — unzip, then run `./OmniQuill.Desktop`
- **macOS** — the app is unsigned, so on first launch choose **Right-click → Open** (or run `xattr -dr com.apple.quarantine OmniQuill-osx-*`)

</details>

---

## 🚀 Getting Started

### Prerequisites

- [.NET 8.0 SDK](https://dotnet.microsoft.com/download/dotnet/8.0) or later
- An IDE: [Visual Studio 2022](https://visualstudio.microsoft.com/), [JetBrains Rider](https://www.jetbrains.com/rider/), or [VS Code](https://code.visualstudio.com/) with the C# extension

### Build & Run

```bash
# Clone the repository
git clone https://github.com/xianshi3/omni-quill.git
cd omni-quill

# Run the application
dotnet run --project OmniQuill.Desktop

# Publish a self-contained build
dotnet publish OmniQuill.Desktop -c Release -r win-x64 --self-contained
```

> Replace `win-x64` with `linux-x64`, `osx-x64`, or `osx-arm64` for other platforms.

### How to Use

1. **Open** — click the folder icon or drag a `.md` file onto the upload zone
2. **Edit** — use the formatting toolbar or keyboard shortcuts
3. **Preview** — switch to the **Preview** tab for real-time rendering
4. **Export** — click **PDF** or **HTML**, choose your settings, and save
5. **Customize** — switch themes (Dark/Light/Gray) and language (EN/中文) in the sidebar

---

## 🛠 Tech Stack

| Layer | Technology |
|---|---|
| **UI Framework** | [Avalonia UI](https://www.avaloniaui.net/) 11.2.3 — cross-platform desktop UI |
| **Architecture** | MVVM with [ReactiveUI](https://www.reactiveui.net/) |
| **Markdown Parsing** | [Markdig](https://github.com/xoofx/markdig) 0.39.1 |
| **PDF Generation** | [PdfSharpCore](https://github.com/ststeiger/PdfSharpCore) + [MigraDocCore](https://github.com/ststeiger/MigraDocCore) 1.3.65 |
| **HTML Parsing** | [HtmlAgilityPack](https://html-agility-pack.net/) 1.12.1 |
| **Runtime** | .NET 8.0 |
| **Platforms** | Windows (x64) · Linux (x64) · macOS (Intel & Apple Silicon) |

---

## 📁 Project Structure

<details>
<summary>Expand</summary>

```
OmniQuill/
├── OmniQuill/                    # Core class library
│   ├── App.axaml                 # Application entry (styles, Fluent theme)
│   ├── Converters/               # Value converters
│   ├── Models/                   # Data models (PreviewBlock, PreviewBlockType)
│   ├── Resources/
│   │   ├── Fonts/                # Bundled fonts (SimSun.ttf)
│   │   └── Strings/              # Localization JSON (en-US, zh-CN)
│   ├── Services/                 # Business logic
│   │   ├── ThemeService.cs       # Theme management (Dark/Light/Gray)
│   │   ├── LocalizationService.cs# Multi-language support
│   │   ├── MarkdownPreviewService.cs # Markdig → PreviewBlock parsing
│   │   └── MarkdownToPdfService.cs   # PDF generation
│   ├── ViewModels/               # MVVM ViewModels
│   │   └── MainViewModel.cs      # Central ViewModel
│   └── Views/                    # Avalonia UI views & components
│       ├── MainWindow.axaml      # Main window
│       ├── AboutWindow.axaml     # About dialog
│       └── Components/           # Editor / ToolBar / Sidebar / MenuBar / …
├── OmniQuill.Desktop/            # Desktop executable host
│   └── Program.cs                # Entry point (Avalonia app builder)
├── .github/workflows/            # CI & Release automation
├── OmniQuill.sln                 # Solution file
└── Directory.Build.props         # Shared MSBuild properties
```

</details>

---

## 🤝 Contributing

Contributions are what make the open-source community an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the project
2. Create your feature branch — `git checkout -b feature/AmazingFeature`
3. Commit your changes — `git commit -m 'Add some AmazingFeature'`
4. Push to the branch — `git push origin feature/AmazingFeature`
5. Open a **Pull Request**

Found a bug or have an idea? Feel free to [open an issue](https://github.com/xianshi3/omni-quill/issues).

---

## 📄 License

Distributed under the [MIT License](LICENSE). See [`LICENSE`](LICENSE) for details.

---

<div align="center">
  <br>
  <p>If OmniQuill helps you, please consider giving it a ⭐ <b>star</b> — it really helps!</p>
  <p>Made with ❤️ using <a href="https://avaloniaui.net/">Avalonia UI</a> &amp; <a href="https://dotnet.microsoft.com/">.NET</a></p>
</div>
