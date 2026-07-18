<p align="center">
  <a href="README.md"><img src="https://img.shields.io/badge/English-0969da?style=flat-square" alt="English"></a>
  <a href="README.zh-CN.md"><img src="https://img.shields.io/badge/%E7%AE%80%E4%BD%93%E4%B8%AD%E6%96%87-c8102e?style=flat-square" alt="简体中文"></a>
  <a href="README.ja.md"><img src="https://img.shields.io/badge/%E6%97%A5%E6%9C%AC%E8%AA%9E-8250df?style=flat-square" alt="日本語"></a>
</p>

<div align="center">

# HaoXiang Huang / NextWeb4

**実用的なデスクトップツール、ローカルファーストのワークフロー、多言語 Web プロジェクトを開発しています。**

[![Web サイト](https://img.shields.io/badge/Web%20%E3%82%B5%E3%82%A4%E3%83%88-nextweb4.github.io-0969da?style=flat-square&logo=githubpages&logoColor=white)](https://nextweb4.github.io/)
[![GitHub フォロワー](https://img.shields.io/github/followers/NextWeb4?style=flat-square&logo=github&label=%E3%83%95%E3%82%A9%E3%83%AD%E3%83%AF%E3%83%BC)](https://github.com/NextWeb4?tab=followers)
[![Profile Stars](https://img.shields.io/github/stars/NextWeb4/NextWeb4?style=flat-square&logo=github&label=profile%20stars)](https://github.com/NextWeb4/NextWeb4)
[![リポジトリサイズ](https://img.shields.io/github/repo-size/NextWeb4/NextWeb4?style=flat-square&logo=github&label=%E3%82%B5%E3%82%A4%E3%82%BA)](https://github.com/NextWeb4/NextWeb4)
[![Profile 更新](https://img.shields.io/github/last-commit/NextWeb4/NextWeb4?style=flat-square&logo=github&label=profile%20%E6%9B%B4%E6%96%B0)](https://github.com/NextWeb4/NextWeb4/commits/main)

<img src="github-metrics.svg" alt="NextWeb4 の GitHub 活動を記録したリポジトリ内スナップショット" width="520">

</div>

## プロフィール

日々のデータ、デスクトップ作業、オフライン動作、個人出版を中心に、目的を絞ったソフトウェアを開発しています。以下のリポジトリでは、確認可能なローカル保存、明示的なネットワーク動作、実用的な Windows パッケージング、機能と制限の両方を記す文書を重視しています。

この Profile は公開プロジェクトへの案内であり、すべてのリポジトリが同じ成熟度、サポート方針、ライセンスを持つという主張ではありません。セットアップと現在の境界は、各プロジェクトの README を正としてください。

## 現在の重点領域

- 設定、メタデータ、記録、ファイル転送、個人の生産性を扱う Windows およびクロスプラットフォームのデスクトップツール。
- データの保存場所とネットワーク要求の発生条件を明記する、ローカルファーストおよびオフラインファースト設計。
- 英語、簡体字中国語、日本語の入口を備えた多言語の静的サイトとドキュメント。
- 静的フロントエンドだけでは足りない場合に、管理、公開、制御された Git 操作を担う小規模で監査可能なサービス。
- 機能だけでなく、リリース、セキュリティ、テスト、互換性、保守状況を正直に記録する文書。

## アプリケーション一覧

| プロジェクト | 技術スタック | 主な用途 |
| --- | --- | --- |
| [yaml-proxy-editor](https://github.com/NextWeb4/yaml-proxy-editor) | Tauri、React、TypeScript | Clash、OpenClash、Mihomo の YAML をローカルで監査、編集、エクスポート |
| [alias-cockpit](https://github.com/NextWeb4/alias-cockpit) | C#、.NET、WinUI | Windows 上でメールエイリアスを生成、マーキング、保存、パッケージ化 |
| [deepseek-translation-studio](https://github.com/NextWeb4/deepseek-translation-studio) | Python、PySide6 | Web/API 翻訳、SRT 継続翻訳、画面キャプチャ、Windows パッケージング |
| [phone-record-manager](https://github.com/NextWeb4/phone-record-manager) | Python、PySide6、SQLite | ローカルの電話番号紐付け記録、バックアップ、復元、配布パッケージ作成 |
| [photo-metadata-editor](https://github.com/NextWeb4/photo-metadata-editor) | Python、ExifTool | Windows で EXIF、XMP、IPTC メタデータを確認、編集 |
| [tips-prompt-manager](https://github.com/NextWeb4/tips-prompt-manager) | Python | Windows 向けのオフラインプロンプト整理と検索 |
| [folder-locker](https://github.com/NextWeb4/folder-locker) | Python | AES-256-GCM 暗号化コンテナと任意の Windows ACL クイックロック |
| [lan-file-transfer](https://github.com/NextWeb4/lan-file-transfer) | Python | ユーザー、グループ、権限、監査ログを備えた LAN ファイル転送 |
| [offline-utility-suite](https://github.com/NextWeb4/offline-utility-suite) | Python | オフラインのフォルダー保護と SRT 字幕ユーティリティ |
| [code-relay](https://github.com/NextWeb4/code-relay) | JavaScript | 自分が所有するアカウントの作業向けローカルメール認証コードコンソール |

## Web と公開

| プロジェクト | 役割 |
| --- | --- |
| [NextWeb4.github.io](https://github.com/NextWeb4/NextWeb4.github.io) | 静的な個人ブログ、検索可能な記事アーカイブ、自己測定ジャーナル、公開プロジェクトの入口 |
| [website](https://github.com/NextWeb4/website) | 静的な二言語ホームページと、ループバック専用 FastAPI コンテンツ管理・履歴保持型公開ツール |
| [github-achievement-collab-notes](https://github.com/NextWeb4/github-achievement-collab-notes) | 偽の活動を作らず、レビュー可能なアカウント間連携を練習するドキュメント専用フォーク |

## 学習・資料アーカイブ

公開アカウントでは、以前の学習資料を [C-practice](https://github.com/NextWeb4/C-practice)、[Cplus.test](https://github.com/NextWeb4/Cplus.test)、[Python-Basic](https://github.com/NextWeb4/Python-Basic)、[VB-practice](https://github.com/NextWeb4/VB-practice)、[VB-Skills.test](https://github.com/NextWeb4/VB-Skills.test)、[2021-Skill-Synthesis-Test](https://github.com/NextWeb4/2021-Skill-Synthesis-Test) に保存しています。これらは異種資料からなる学習アーカイブであり、1 つのビルドコマンドで動かす単一アプリケーションではありません。

[hacking.script](https://github.com/NextWeb4/hacking.script) は、防御学習のために許可された隔離環境で扱うセキュリティラボのアーカイブです。例を使う前に、その README に記載された安全境界を必ず確認してください。

## 技術的な裏付け

| 技術 | リポジトリ上の根拠 |
| --- | --- |
| TypeScript、React、Tauri | `yaml-proxy-editor` のデスクトップワークベンチと Rust 側パッケージング境界 |
| C#、.NET、WinUI | `alias-cockpit` Windows デスクトップアプリケーション |
| Python、PySide6、SQLite | 翻訳、記録管理、メタデータ、オフライン、LAN の各デスクトッププロジェクト |
| HTML、CSS、バニラ JavaScript | 2 つの公開 Web サイトとローカル `code-relay` インターフェース |
| FastAPI、Pydantic、pytest | `website` のループバック管理サービスと回帰テスト |
| ExifTool | `photo-metadata-editor` に統合したメタデータ読み書きエンジン |
| Git と GitHub Pages | 静的公開と、保護されたコンテンツのコミット、プッシュ、履歴、ロールバック処理 |

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Tauri](https://img.shields.io/badge/Tauri-24C8DB?style=flat-square&logo=tauri&logoColor=white)
![.NET](https://img.shields.io/badge/.NET-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)

## 開発原則

- ユーザーデータは既定でローカルに保ち、例外を明示します。
- プロジェクトに必要な範囲で、UI、ドメインロジック、永続化、ネットワーク、パッケージングの責務を分離します。
- 互換性、ライセンス、ネットワーク、保守状況を確認したうえで、標準ライブラリまたは成熟した小規模依存関係を優先します。
- 対象を絞ったテストで既存動作を維持し、実際に確認したコマンドだけを記載します。
- 暗号化、ACL、ブラウザー上の抑止、ローカル認証は、それぞれの実際のセキュリティ境界に沿って説明します。
- 3 言語の README で、事実、パス、コマンド、画像、制限を揃えます。

## Profile リポジトリ

この特別なリポジトリは意図的に小さく、3 言語の README、コミット済みの `github-metrics.svg` スナップショット、`AGENTS.md` だけで構成されています。アプリケーションランタイム、パッケージマネージャー、ビルドコマンド、自動テスト、lint、format、生成ワークフローはありません。

動的な Shields バッジは GitHub の表示時に更新されます。コミット済みの Metrics SVG は自動更新されないため、現在のアカウント活動より古くなる可能性があります。各プロジェクトのリポジトリとライブメタデータを優先してください。

## 状況と制限

2026-07-18 の監査時点で、Profile リポジトリはアクティブかつ未アーカイブでした。プロジェクトの範囲、バージョン、利用可能性は今後も変わるため、インストールや再利用の前にリンク先の README とリリース履歴を確認してください。一部は学習アーカイブであり、あるプロジェクトにライセンスがないことを別のプロジェクトへ当てはめることはできません。

## 連絡先

- Web サイト：[nextweb4.github.io](https://nextweb4.github.io/)
- GitHub：[github.com/NextWeb4](https://github.com/NextWeb4)
- メール：[didadida1688@gmail.com](mailto:didadida1688@gmail.com)

再現手順のあるプロジェクト固有の問題は、該当リポジトリで Issue が有効な場合、その Issue トラッカーへ報告してください。

## ライセンス

この Profile リポジトリにはライセンスファイルがありません。リンク先の各プロジェクトには個別の状態とライセンス条件があり、公開されているだけでは再利用許可を意味しません。
