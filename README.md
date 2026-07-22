<p align="center">
  <a href="README.md"><img src="https://img.shields.io/badge/English-0969da?style=flat-square" alt="English"></a>
  <a href="README.zh-CN.md"><img src="https://img.shields.io/badge/%E7%AE%80%E4%BD%93%E4%B8%AD%E6%96%87-c8102e?style=flat-square" alt="简体中文"></a>
  <a href="README.ja.md"><img src="https://img.shields.io/badge/%E6%97%A5%E6%9C%AC%E8%AA%9E-8250df?style=flat-square" alt="日本語"></a>
</p>

<div align="center">

# HaoXiang Huang / NextWeb4

**Building practical desktop tools, local-first workflows, and multilingual web projects.**

[![Website](https://img.shields.io/badge/Website-nextweb4.github.io-0969da?style=flat-square&logo=githubpages&logoColor=white)](https://nextweb4.github.io/)
[![GitHub followers](https://img.shields.io/github/followers/NextWeb4?style=flat-square&logo=github&label=followers)](https://github.com/NextWeb4?tab=followers)
[![Profile stars](https://img.shields.io/github/stars/NextWeb4/NextWeb4?style=flat-square&logo=github&label=profile%20stars)](https://github.com/NextWeb4/NextWeb4)
[![Repository size](https://img.shields.io/github/repo-size/NextWeb4/NextWeb4?style=flat-square&logo=github)](https://github.com/NextWeb4/NextWeb4)
[![Profile update](https://img.shields.io/github/last-commit/NextWeb4/NextWeb4?style=flat-square&logo=github&label=profile%20updated)](https://github.com/NextWeb4/NextWeb4/commits/main)

<img src="github-metrics.svg" alt="Committed snapshot of NextWeb4 GitHub activity" width="520">

</div>

## About

I build focused software around everyday data, desktop workflows, offline operation, and personal publishing. The repositories below favor inspectable local storage, explicit network behavior, practical Windows packaging, and documentation that states both capabilities and limitations.

This profile is a guide to the public work, not a claim that every repository has the same maturity, support policy, or license. Each linked project README is the source of truth for its setup and current boundaries.

## Current focus

- Windows and cross-platform desktop utilities for configuration, metadata, records, file transfer, and personal productivity.
- Local-first and offline-first designs that document where data is stored and when a network request can occur.
- Multilingual static sites and documentation with English, Simplified Chinese, and Japanese entry points.
- Small, auditable services for administration, publishing, and controlled Git operations when a static frontend alone is insufficient.
- Honest release, security, test, compatibility, and maintenance notes instead of feature-only summaries.

## Application portfolio

| Project | Stack | Focus |
| --- | --- | --- |
| [yaml-proxy-editor](https://github.com/NextWeb4/yaml-proxy-editor) | Tauri, React, TypeScript | Local audit, editing, and export for Clash, OpenClash, and Mihomo YAML files |
| [alias-cockpit](https://github.com/NextWeb4/alias-cockpit) | C#, .NET, WinUI | Generate, mark, store, and package local email-alias workflows on Windows |
| [deepseek-translation-studio](https://github.com/NextWeb4/deepseek-translation-studio) | Python, PySide6 | Web/API translation, SRT continuation, screen capture, and Windows packaging |
| [phone-record-manager](https://github.com/NextWeb4/phone-record-manager) | Python, PySide6, SQLite | Local phone-number binding records, backup, restore, and release packaging |
| [photo-metadata-editor](https://github.com/NextWeb4/photo-metadata-editor) | Python, ExifTool | Windows EXIF, XMP, and IPTC metadata inspection and editing |
| [tips-prompt-manager](https://github.com/NextWeb4/tips-prompt-manager) | Python | Offline prompt organization and retrieval for Windows |
| [folder-locker](https://github.com/NextWeb4/folder-locker) | Python | AES-256-GCM encrypted containers and optional Windows ACL quick lock |
| [lan-file-transfer](https://github.com/NextWeb4/lan-file-transfer) | Python | Local-network file transfer with users, groups, permissions, and audit logs |
| [offline-utility-suite](https://github.com/NextWeb4/offline-utility-suite) | Python | Offline folder-protection and SRT subtitle utilities |
| [code-relay](https://github.com/NextWeb4/code-relay) | JavaScript | Local mailbox verification-code console for owned-account workflows |

## Web and publishing

| Project | Role |
| --- | --- |
| [NextWeb4.github.io](https://github.com/NextWeb4/NextWeb4.github.io) | Generated public runtime for the root personal website, with browser-delivered bilingual content and no private editor or backend |
| [Private](https://github.com/NextWeb4/Private) | Public static runtime for the separate `/Private/` article archive and self-measure journal |
| [github-achievement-collab-notes](https://github.com/NextWeb4/github-achievement-collab-notes) | Documentation-only fork for practicing reviewable cross-account collaboration without fabricated activity |

## Learning and reference archives

The public account also preserves earlier study material in [C-practice](https://github.com/NextWeb4/C-practice), [Cplus.test](https://github.com/NextWeb4/Cplus.test), [Python-Basic](https://github.com/NextWeb4/Python-Basic), [VB-practice](https://github.com/NextWeb4/VB-practice), [VB-Skills.test](https://github.com/NextWeb4/VB-Skills.test), and [2021-Skill-Synthesis-Test](https://github.com/NextWeb4/2021-Skill-Synthesis-Test). These are heterogeneous learning archives, not single applications with one build command.

[hacking.script](https://github.com/NextWeb4/hacking.script) is documented as an authorized, isolated security-lab archive for defensive learning. Its README safety boundary applies before using any example.

## Technology evidence

| Technology | Repository evidence |
| --- | --- |
| TypeScript, React, Tauri | `yaml-proxy-editor` desktop workbench and Rust-backed packaging boundary |
| C#, .NET, WinUI | `alias-cockpit` Windows desktop application |
| Python, PySide6, SQLite | Translation, record-management, metadata, offline, and LAN desktop projects |
| HTML, CSS, vanilla JavaScript | Both published websites and the local `code-relay` interface |
| ExifTool | Metadata read/write engine integrated by `photo-metadata-editor` |
| Git and GitHub Pages | Static publishing plus guarded content commit, push, history, and rollback workflows |

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Tauri](https://img.shields.io/badge/Tauri-24C8DB?style=flat-square&logo=tauri&logoColor=white)
![.NET](https://img.shields.io/badge/.NET-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)

## Working principles

- Keep user data local by default and describe exceptions explicitly.
- Separate UI, domain logic, persistence, network, and packaging responsibilities where the project warrants it.
- Prefer standard-library or mature, narrowly scoped dependencies after compatibility, license, network, and maintenance review.
- Preserve existing behavior with focused tests and document commands that were actually verified.
- Treat encryption, ACLs, browser deterrence, and local authentication according to their real security boundaries.
- Maintain equivalent facts, paths, commands, images, and limitations across the three README languages.

## Profile repository

This special repository is intentionally small: three language READMEs, this committed `github-metrics.svg` snapshot, and `AGENTS.md`. It has no application runtime, package manager, build command, automated test, lint, format, or generation workflow.

The dynamic Shields badges refresh when GitHub renders the page. The committed metrics SVG does not update automatically and may lag behind current account activity; project repositories and their live metadata take precedence.

## Status and limitations

The profile repository was active and not archived at the 2026-07-22 audit. Project scope, versions, and availability continue to change, so follow the linked README and release history before installing or reusing anything. Some repositories are learning archives, and the absence of a license in one project must not be inferred from another.

## Contact

- Website: [nextweb4.github.io](https://nextweb4.github.io/)
- GitHub: [github.com/NextWeb4](https://github.com/NextWeb4)
- Email: [Rays688888@Gmail.com](mailto:Rays688888@Gmail.com)

Please use the relevant repository's issue tracker for reproducible project-specific problems when issues are enabled.

## License

No license file is declared for this profile repository. Each linked project has its own repository status and licensing terms; public visibility alone does not grant reuse permission.
