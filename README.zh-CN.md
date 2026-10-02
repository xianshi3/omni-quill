<div align="center">

# ✒️ OmniQuill

**优雅的跨平台 Markdown → PDF 桌面编辑器**

撰写、预览并导出排版精美的 PDF —— 通吃 Windows、Linux 和 macOS。

[English](README.md) | 简体中文

![](https://img.shields.io/badge/.NET-8.0-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![](https://img.shields.io/badge/Avalonia-11.2-8B5CF6?style=for-the-badge&logo=avalonia&logoColor=white)
![](https://img.shields.io/badge/platform-Windows%20%7C%20Linux%20%7C%20macOS-4FC08D?style=for-the-badge)
[![Release](https://img.shields.io/github/v/release/xianshi3/omni-quill?style=for-the-badge&logo=github&logoColor=white)](https://github.com/xianshi3/omni-quill/releases/latest)
[![Downloads](https://img.shields.io/github/downloads/xianshi3/omni-quill/total?style=for-the-badge&label=downloads&logo=github&logoColor=white)](https://github.com/xianshi3/omni-quill/releases)
[![Build](https://img.shields.io/github/actions/workflow/status/xianshi3/omni-quill/ci.yml?branch=master&style=for-the-badge&label=build&logo=githubactions&logoColor=white)](https://github.com/xianshi3/omni-quill/actions/workflows/ci.yml)
[![License: MIT](https://img.shields.io/github/license/xianshi3/omni-quill?style=for-the-badge&label=license&color=EB5424)](LICENSE)

[**⬇️ 下载**](#%EF%B8%8F-下载) · [**✨ 功能**](#-功能) · [**🚀 快速开始**](#-快速开始) · [**🤝 参与贡献**](#-参与贡献)

</div>

---

<div align="center">
  <table>
    <tr>
      <td align="center"><b>🌙 深色主题</b></td>
      <td align="center"><b>☀️ 浅色主题</b></td>
    </tr>
    <tr>
      <td><img src="https://github.com/user-attachments/assets/041a015d-450c-45fc-84be-29069c59c075" width="100%" alt="深色主题" /></td>
      <td><img src="https://github.com/user-attachments/assets/7288f666-32d2-4b14-b781-a06e0e5ba20b" width="100%" alt="浅色主题" /></td>
    </tr>
  </table>
</div>

---

## ✨ 功能

<table>
  <tr>
    <td width="33%">🔍 <b>实时预览</b><br><sub>基于 Markdig AST 的即时渲染 — 完整 GFM 语法支持</sub></td>
    <td width="33%">🎨 <b>三套主题</b><br><sub>深色、浅色、灰色，切换带平滑过渡动画</sub></td>
    <td width="33%">🌐 <b>中英双语</b><br><sub>界面语言即时切换，无需重启</sub></td>
  </tr>
  <tr>
    <td>📄 <b>PDF / HTML 导出</b><br><sub>页面尺寸、边距、字体可调；或导出内嵌样式的 HTML</sub></td>
    <td>🔤 <b>中文开箱即用</b><br><sub>内置宋体，PDF 中文渲染零乱码</sub></td>
    <td>📊 <b>实时统计</b><br><sub>行数、字数、字符数一目了然</sub></td>
  </tr>
  <tr>
    <td>💾 <b>自动备份</b><br><sub>每 60 秒自动保存，心血永不丢失</sub></td>
    <td>📁 <b>最近文件</b><br><sub>自动记录最近打开的 10 个文档</sub></td>
    <td>🎯 <b>查找替换</b><br><sub>区分大小写，显示匹配数并可逐个跳转</sub></td>
  </tr>
  <tr>
    <td>🖱️ <b>拖拽打开</b><br><sub>把 <code>.md</code> 文件拖进窗口即可打开</sub></td>
    <td>🔎 <b>缩放 50–200%</b><br><sub>工具栏按钮或快捷键调节编辑器字号</sub></td>
    <td>⌨️ <b>完整快捷键</b><br><sub>撤销/重做、格式化一应俱全</sub></td>
  </tr>
</table>

<details>
<summary><b>⌨️ 快捷键一览</b></summary>

| 快捷键 | 功能 |
|---|---|
| `Ctrl+N` | 新建文件 |
| `Ctrl+O` | 打开文件 |
| `Ctrl+S` | 保存文件 |
| `Ctrl+Z` / `Ctrl+Y` | 撤销 / 重做 |
| `Ctrl+F` | 查找 |
| `Ctrl+B` / `Ctrl+I` | 加粗 / 斜体 |
| `Ctrl+P` | 切换预览 |
| `Ctrl++` / `Ctrl+-` / `Ctrl+0` | 放大 / 缩小 / 复位 |

</details>

---

## ⬇️ 下载

选择对应平台的最新版本 —— **无需安装 .NET 运行时**，解压即用：

| 平台 | 架构 | 下载 |
|---|---|---|
| 🪟 Windows | x64 | [**OmniQuill-win-x64.zip**](https://github.com/xianshi3/omni-quill/releases/latest/download/OmniQuill-win-x64.zip) |
| 🐧 Linux | x64 | [**OmniQuill-linux-x64.zip**](https://github.com/xianshi3/omni-quill/releases/latest/download/OmniQuill-linux-x64.zip) |
| 🍎 macOS | Apple Silicon | [**OmniQuill-osx-arm64.zip**](https://github.com/xianshi3/omni-quill/releases/latest/download/OmniQuill-osx-arm64.zip) |
| 🍎 macOS | Intel | [**OmniQuill-osx-x64.zip**](https://github.com/xianshi3/omni-quill/releases/latest/download/OmniQuill-osx-x64.zip) |

<details>
<summary><b>平台说明</b></summary>

- **Windows** — 解压后运行 `OmniQuill.Desktop.exe`
- **Linux** — 解压后运行 `./OmniQuill.Desktop`
- **macOS** — 应用未签名，首次启动请 **右键 → 打开**（或执行 `xattr -dr com.apple.quarantine OmniQuill-osx-*`）

</details>

---

## 🚀 快速开始

### 环境要求

- [.NET 8.0 SDK](https://dotnet.microsoft.com/download/dotnet/8.0) 或更高版本
- IDE：[Visual Studio 2022](https://visualstudio.microsoft.com/)、[JetBrains Rider](https://www.jetbrains.com/rider/) 或安装 C# 插件的 [VS Code](https://code.visualstudio.com/)

### 构建与运行

```bash
# 克隆仓库
git clone https://github.com/xianshi3/omni-quill.git
cd omni-quill

# 运行应用
dotnet run --project OmniQuill.Desktop

# 发布自包含版本
dotnet publish OmniQuill.Desktop -c Release -r win-x64 --self-contained
```

> 将 `win-x64` 替换为 `linux-x64`、`osx-x64` 或 `osx-arm64` 即可发布其他平台。

### 使用方法

1. **打开** — 点击文件夹图标，或把 `.md` 文件拖入上传区
2. **编辑** — 使用格式工具栏或快捷键撰写
3. **预览** — 切换到 **预览** 标签页实时查看渲染效果
4. **导出** — 点击工具栏的 **PDF** 或 **HTML**，设置参数后保存
5. **个性化** — 在侧边栏切换主题（深色/浅色/灰色）与语言（EN/中文）

---

## 🛠 技术栈

| 层级 | 技术 |
|---|---|
| **UI 框架** | [Avalonia UI](https://www.avaloniaui.net/) 11.2.3 — 跨平台桌面 UI |
| **架构模式** | MVVM + [ReactiveUI](https://www.reactiveui.net/) |
| **Markdown 解析** | [Markdig](https://github.com/xoofx/markdig) 0.39.1 |
| **PDF 生成** | [PdfSharpCore](https://github.com/ststeiger/PdfSharpCore) + [MigraDocCore](https://github.com/ststeiger/MigraDocCore) 1.3.65 |
| **HTML 解析** | [HtmlAgilityPack](https://html-agility-pack.net/) 1.12.1 |
| **运行时** | .NET 8.0 |
| **支持平台** | Windows (x64) · Linux (x64) · macOS (Intel 与 Apple Silicon) |

---

## 📁 项目结构

<details>
<summary>展开</summary>

```
OmniQuill/
├── OmniQuill/                    # 核心类库
│   ├── App.axaml                 # 应用入口（样式、Fluent 主题）
│   ├── Converters/               # 值转换器
│   ├── Models/                   # 数据模型（PreviewBlock、PreviewBlockType）
│   ├── Resources/
│   │   ├── Fonts/                # 内置字体（SimSun.ttf）
│   │   └── Strings/              # 多语言 JSON（en-US、zh-CN）
│   ├── Services/                 # 业务逻辑
│   │   ├── ThemeService.cs       # 主题管理（深色/浅色/灰色）
│   │   ├── LocalizationService.cs# 多语言支持
│   │   ├── MarkdownPreviewService.cs # Markdig → PreviewBlock 解析
│   │   └── MarkdownToPdfService.cs   # PDF 生成
│   ├── ViewModels/               # MVVM ViewModel
│   │   └── MainViewModel.cs      # 主 ViewModel
│   └── Views/                    # Avalonia 视图与组件
│       ├── MainWindow.axaml      # 主窗口
│       ├── AboutWindow.axaml     # 关于对话框
│       └── Components/           # 编辑器/工具栏/侧边栏/菜单栏等
├── OmniQuill.Desktop/            # 桌面可执行宿主
│   └── Program.cs                # 入口（Avalonia 应用构建器）
├── .github/workflows/            # CI 与 Release 自动化
├── OmniQuill.sln                 # 解决方案文件
└── Directory.Build.props         # 共享 MSBuild 属性
```

</details>

---

## 🤝 参与贡献

开源社区因你的贡献而精彩，任何形式的贡献都**深受感激**：

1. Fork 本仓库
2. 创建特性分支 — `git checkout -b feature/AmazingFeature`
3. 提交更改 — `git commit -m 'Add some AmazingFeature'`
4. 推送分支 — `git push origin feature/AmazingFeature`
5. 发起 **Pull Request**

发现 Bug 或有新想法？欢迎 [提交 Issue](https://github.com/xianshi3/omni-quill/issues)。

---

## 📄 许可证

本项目基于 [MIT License](LICENSE) 开源，详见 [`LICENSE`](LICENSE) 文件。

---

<div align="center">
  <br>
  <p>如果 OmniQuill 对你有帮助，欢迎点个 ⭐ <b>Star</b> 支持一下！</p>
  <p>用 ❤️ 基于 <a href="https://avaloniaui.net/">Avalonia UI</a> 与 <a href="https://dotnet.microsoft.com/">.NET</a> 打造</p>
</div>
