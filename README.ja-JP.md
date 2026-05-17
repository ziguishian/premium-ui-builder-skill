# premium-ui-builder-skill

> AI Coding / Vibe Coding ワークフロー向けの、プレミアム UI デザインアドバイザー Skill です。

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Codex Skill](https://img.shields.io/badge/Codex-Skill-black.svg)](SKILL.md)
[![Docs](https://img.shields.io/badge/docs-ready-blue.svg)](docs/usage.md)
[![Languages](https://img.shields.io/badge/i18n-zh%20%7C%20en%20%7C%20ja%20%7C%20ko-orange.svg)](#language-readmes)

**Language READMEs**: [中文](README.md) | [English](README.en-US.md) | 日本語 | [한국어](README.ko-KR.md)

> Design before decoration.  
> System before style.  
> Implementation before vague aesthetics.

## 概要

`premium-ui-builder-skill` は、曖昧な UI 要望を、実装可能な UI 設計計画とフロントエンド実装ブリーフに変換する Codex Skill です。

単なる「きれいにする」プロンプト集ではありません。プロダクトの意図、情報設計、視覚階層、コンポーネント、モーション、実装制約をつなげて考えるための再利用可能な方法論です。

## 対象ユーザー

- AI coding agent に UI 実装前の設計指針を与えたい人
- Vibe Coding でプロダクト UI を作りたい初心者やクリエイター
- SaaS、AI ツール、ダッシュボード、LP、ポートフォリオ、管理画面、モバイル画面を作る開発者
- UI を「実在するプロダクトらしく」改善したい個人開発者やデザイナー

## 2つのモード

### Mode A: New Project UI Planning

ゼロから新しい UI を計画する場合に使います。プロダクト UI の位置づけ、ページ構成、情報設計、視覚方向、レイアウト、コンポーネント、モーション、フロントエンド技術選定、Codex-ready prompt を出力します。

### Mode B: Existing UI Upgrade / Diagnosis

既存のページ、スクリーンショット、コードベースを改善する場合に使います。UI の成熟度、主要課題、改善優先度、情報階層、レイアウト、ビジュアルシステム、コンポーネント、モーション、実装メモ、Codex-ready redesign prompt を出力します。

## 使い方

1. 作りたいプロダクト、または改善したい UI の問題を説明します。
2. Codex に `premium-ui-builder-skill` を使うよう依頼します。
3. Skill が Mode A または Mode B を判定します。
4. UI 設計計画または診断結果を確認します。
5. 生成された Codex-ready prompt を使って実装します。

## 例

```text
Use premium-ui-builder-skill to plan the UI for this AI tool.
```

```text
This page looks too ordinary. Diagnose it and give me an upgrade plan.
```

```text
Make this interface look more like a real product, not an AI-generated template.
```

## 対応プロジェクト

Landing page、SaaS dashboard、AI tool interface、Admin dashboard、Portfolio、Content generation tool、E-commerce interface、Mobile app screen、Developer tool、Data dashboard、Creator tool、Pricing page、Settings page、Documentation site。

## ファイル構成

```text
.
├── SKILL.md
├── README.md
├── README.en-US.md
├── README.zh-CN.md
├── README.ja-JP.md
├── README.ko-KR.md
├── docs/
├── references/
├── examples/
└── evals/
```

## Language READMEs

- [中文](README.md): Chinese default README.
- [English](README.en-US.md): English README.
- [简体中文](README.zh-CN.md): Simplified Chinese mirror README.
- [한국어](README.ko-KR.md): Korean README.

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=ziguishian/premium-ui-builder-skill&type=Date)](https://www.star-history.com/#ziguishian/premium-ui-builder-skill&Date)

## Contributing

新しい事例、視覚スタイル、診断ルーブリック、コンポーネントパターン、モーション指針、実装ノート、評価ケースの追加を歓迎します。すべての提案は具体的で、AI coding agent が実装できる形にしてください。

## License

MIT License. Copyright (c) 2026 ziguishian.
