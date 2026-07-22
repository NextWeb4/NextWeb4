


<p align="center">
  <a href="README.md"><img src="https://img.shields.io/badge/English-0969da?style=flat-square" alt="English"></a>
  <a href="README.zh-CN.md"><img src="https://img.shields.io/badge/%E7%AE%80%E4%BD%93%E4%B8%AD%E6%96%87-c8102e?style=flat-square" alt="简体中文"></a>
  <a href="README.ja.md"><img src="https://img.shields.io/badge/%E6%97%A5%E6%9C%AC%E8%AA%9E-8250df?style=flat-square" alt="日本語"></a>
</p>

<div align="center">

# 黄浩翔 / NextWeb4

**构建实用桌面工具、本地优先工作流与多语言 Web 项目。**

[![个人网站](https://img.shields.io/badge/%E4%B8%AA%E4%BA%BA%E7%BD%91%E7%AB%99-nextweb4.github.io-0969da?style=flat-square&logo=githubpages&logoColor=white)](https://nextweb4.github.io/)
[![GitHub 关注者](https://img.shields.io/github/followers/NextWeb4?style=flat-square&logo=github&label=%E5%85%B3%E6%B3%A8%E8%80%85)](https://github.com/NextWeb4?tab=followers)
[![Profile Stars](https://img.shields.io/github/stars/NextWeb4/NextWeb4?style=flat-square&logo=github&label=profile%20stars)](https://github.com/NextWeb4/NextWeb4)
[![仓库大小](https://img.shields.io/github/repo-size/NextWeb4/NextWeb4?style=flat-square&logo=github&label=%E4%BB%93%E5%BA%93%E5%A4%A7%E5%B0%8F)](https://github.com/NextWeb4/NextWeb4)
[![Profile 更新](https://img.shields.io/github/last-commit/NextWeb4/NextWeb4?style=flat-square&logo=github&label=profile%20%E6%9B%B4%E6%96%B0)](https://github.com/NextWeb4/NextWeb4/commits/main)

<img src="github-metrics.svg" alt="NextWeb4 GitHub 活动的仓库内快照" width="520">

</div>

## 关于我

我围绕日常数据、桌面工作流、离线运行和个人发布构建边界清晰的软件。下面的仓库注重可检查的本地存储、明确的联网行为、实用的 Windows 打包，以及同时说明能力与限制的文档。

这个 Profile 是公开项目的导航，不代表所有仓库拥有相同的成熟度、支持政策或许可证。每个项目的安装方式与当前边界都以对应 README 为准。

## 当前方向

- 面向配置、元数据、记录、文件传输和个人效率的 Windows 与跨平台桌面工具。
- 明确说明数据存放位置与网络请求时机的本地优先、离线优先设计。
- 同时提供英文、简体中文和日文入口的多语言静态网站与文档。
- 当纯静态前端无法满足需求时，使用小型、可审计的服务完成管理、发布和受控 Git 操作。
- 如实记录发布、安全、测试、兼容性和维护状态，而不是只列功能。

## 应用项目

| 项目 | 技术栈 | 重点 |
| --- | --- | --- |
| [yaml-proxy-editor](https://github.com/NextWeb4/yaml-proxy-editor) | Tauri、React、TypeScript | 在本地审计、编辑和导出 Clash、OpenClash 与 Mihomo YAML 文件 |
| [alias-cockpit](https://github.com/NextWeb4/alias-cockpit) | C#、.NET、WinUI | 在 Windows 上生成、标记、存储并打包本地邮箱别名工作流 |
| [deepseek-translation-studio](https://github.com/NextWeb4/deepseek-translation-studio) | Python、PySide6 | Web/API 翻译、SRT 续译、屏幕捕获与 Windows 打包 |
| [phone-record-manager](https://github.com/NextWeb4/phone-record-manager) | Python、PySide6、SQLite | 本地手机号绑定记录、备份、恢复与发布打包 |
| [photo-metadata-editor](https://github.com/NextWeb4/photo-metadata-editor) | Python、ExifTool | 在 Windows 上查看和编辑 EXIF、XMP 与 IPTC 元数据 |
| [tips-prompt-manager](https://github.com/NextWeb4/tips-prompt-manager) | Python | Windows 离线提示词整理与检索 |
| [folder-locker](https://github.com/NextWeb4/folder-locker) | Python | AES-256-GCM 加密容器与可选的 Windows ACL 快速锁定 |
| [lan-file-transfer](https://github.com/NextWeb4/lan-file-transfer) | Python | 带用户、组、权限和审计日志的局域网文件传输 |
| [offline-utility-suite](https://github.com/NextWeb4/offline-utility-suite) | Python | 离线文件夹保护与 SRT 字幕工具 |
| [code-relay](https://github.com/NextWeb4/code-relay) | JavaScript | 面向自有账号工作流的本地邮箱验证码控制台 |

## Web 与发布

| 项目 | 职责 |
| --- | --- |
| [NextWeb4.github.io](https://github.com/NextWeb4/NextWeb4.github.io) | 静态个人博客、可搜索文章归档、自我度量日志与公开项目入口 |
| [website](https://github.com/NextWeb4/website) | 静态双语主页，以及仅绑定本机回环地址的 FastAPI 内容管理和保留历史的发布工具 |
| [github-achievement-collab-notes](https://github.com/NextWeb4/github-achievement-collab-notes) | 仅含文档的 Fork，用于练习可审查的跨账号协作，不制造虚假活动 |

## 学习与资料归档

公开账号还在 [C-practice](https://github.com/NextWeb4/C-practice)、[Cplus.test](https://github.com/NextWeb4/Cplus.test)、[Python-Basic](https://github.com/NextWeb4/Python-Basic)、[VB-practice](https://github.com/NextWeb4/VB-practice)、[VB-Skills.test](https://github.com/NextWeb4/VB-Skills.test) 和 [2021-Skill-Synthesis-Test](https://github.com/NextWeb4/2021-Skill-Synthesis-Test) 中保留了早期学习资料。这些仓库是由不同材料组成的学习归档，并不是能够用一条构建命令运行的单一应用。

[hacking.script](https://github.com/NextWeb4/hacking.script) 被明确记录为用于防御性学习的授权、隔离安全实验归档；使用任何示例前都必须遵守其 README 中的安全边界。

## 技术依据

| 技术 | 仓库依据 |
| --- | --- |
| TypeScript、React、Tauri | `yaml-proxy-editor` 桌面工作台与 Rust 打包边界 |
| C#、.NET、WinUI | `alias-cockpit` Windows 桌面应用 |
| Python、PySide6、SQLite | 翻译、记录管理、元数据、离线和局域网桌面项目 |
| HTML、CSS、原生 JavaScript | 两个已发布网站与本地 `code-relay` 界面 |
| FastAPI、Pydantic、pytest | `website` 中的本机回环管理服务与回归测试套件 |
| ExifTool | `photo-metadata-editor` 集成的元数据读写引擎 |
| Git 与 GitHub Pages | 静态发布，以及受保护的内容提交、推送、历史和回滚工作流 |

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Tauri](https://img.shields.io/badge/Tauri-24C8DB?style=flat-square&logo=tauri&logoColor=white)
![.NET](https://img.shields.io/badge/.NET-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)

## 工作原则

- 默认把用户数据保留在本地，并明确记录例外。
- 在项目确有需要时分离 UI、领域逻辑、持久化、网络和打包职责。
- 完成兼容性、许可证、联网行为和维护状态审计后，优先选择标准库或成熟的小型依赖。
- 通过聚焦的测试保留现有行为，只记录经过验证的命令。
- 根据加密、ACL、浏览器阻止措施和本地认证的真实边界描述安全能力。
- 三语 README 必须保留相同的事实、路径、命令、图片和限制。

## Profile 仓库

这个特殊仓库有意保持精简：三份语言 README、一个已提交的 `github-metrics.svg` 快照和 `AGENTS.md`。它没有应用运行时、包管理器、构建命令、自动化测试、lint、format 或生成工作流。

动态 Shields 徽章会在 GitHub 渲染页面时刷新；已提交的 Metrics SVG 不会自动更新，可能落后于当前账号活动，应以项目仓库及其实时元数据为准。

## 状态与限制

截至 2026-07-18 审计时，Profile 仓库处于活跃且未归档状态。项目范围、版本和可用性会继续变化，安装或复用前请查看对应 README 与发布历史。部分仓库是学习归档，不能把某个项目缺少许可证的情况推断到其他项目。

## 联系方式

- 个人网站：[nextweb4.github.io](https://nextweb4.github.io/)
- GitHub：[github.com/NextWeb4](https://github.com/NextWeb4)
- 邮箱：[Rays688888@Gmail.com](mailto:Rays688888@Gmail.com)

如对应仓库启用了 Issue，具有可复现步骤的项目问题请提交到该仓库的 Issue 区。

## 许可证

本 Profile 仓库没有声明许可证。每个链接项目都有自己的仓库状态和许可条款；公开可见本身不等于获得复用许可。
