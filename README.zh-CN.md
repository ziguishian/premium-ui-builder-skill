# premium-ui-builder-skill

> 一个面向 AI Coding / Vibe Coding 场景的高级 UI 设计顾问 Skill：把模糊审美需求翻译成可执行的 UI 与前端实现方案。

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Codex Skill](https://img.shields.io/badge/Codex-Skill-black.svg)](SKILL.md)
[![Docs](https://img.shields.io/badge/docs-ready-blue.svg)](docs/usage.md)
[![Languages](https://img.shields.io/badge/i18n-zh%20%7C%20en%20%7C%20ja%20%7C%20ko-orange.svg)](#多语言-readme)

**多语言 README**：中文 | [English](README.en-US.md) | [日本語](README.ja-JP.md) | [한국어](README.ko-KR.md)

> 先设计系统，再做页面美化。  
> 先定义审美逻辑，再进入前端实现。

## 这个 Skill 是什么

`premium-ui-builder-skill` 是一个文档型 Codex Skill，用来帮助用户和 AI coding agent 在写代码之前先把 UI 设计逻辑讲清楚。

它不是一组“美化提示词”，也不是让页面随便加渐变、阴影、玻璃拟态和动画。它关注的是：产品目标、信息层级、视觉系统、组件规范、交互状态和前端实现之间如何一起工作。

## 适合谁

- 正在做 AI Coding / Vibe Coding 的创作者
- 不太懂 UI 术语，但想把页面做得更像真实产品的用户
- 独立开发者、产品 builder、SaaS 创业者
- 想在 Codex 实现前先规划界面的设计师和前端开发者
- 正在做 AI 工具、Dashboard、Landing Page、Portfolio、Admin Panel、移动端页面或内容工具的人

## 解决什么问题

- “Make this page more premium”
- “这个页面太普通了”
- “看起来不像真实产品”
- “想要更有科技感”
- “不要那么 AI 生成感”
- “想要 Apple / Linear / Notion / Vercel 风格”
- “页面没有层级和视觉冲击力”
- “先帮我设计 UI，再让 Codex 写代码”

## 为什么高级 UI 不是美化提示词

高级感来自克制、对齐、留白、层级和一致性，不是更多特效。

一个看起来专业的界面通常先解决这些问题：

- 用户第一眼应该看哪里
- 页面最重要的操作是什么
- 哪些信息应该突出，哪些应该安静
- 字体、颜色、间距、圆角、阴影是否有规则
- 组件是否有 hover、focus、loading、empty、error 等真实状态
- 移动端是否还能保持清晰

## 两种工作模式

### Mode A：新项目 UI 规划

适用于从 0 到 1 规划产品界面的情况。Skill 会输出产品 UI 定位、目标用户、页面列表、信息架构、关键流程、视觉方向、布局系统、组件系统、动效策略、响应式策略、前端技术建议和 Codex-ready 实现提示词。

### Mode B：现有页面升级 / 诊断

适用于已经有页面、截图、代码或原型，但看起来普通、模板感强、不够像真实产品的情况。Skill 会输出 UI 诊断、成熟度判断、主要问题、升级优先级、信息层级修复、布局修复、视觉系统修复、组件修复、动效修复和 Codex-ready 改版提示词。

## 文件结构

```text
.
├── SKILL.md
├── README.md
├── README.en-US.md
├── README.zh-CN.md
├── README.ja-JP.md
├── README.ko-KR.md
├── LICENSE
├── .gitignore
├── docs/
├── references/
├── examples/
└── evals/
```

## 如何使用

1. 描述你的产品或页面问题。
2. 让 Codex 使用 `premium-ui-builder-skill`。
3. Skill 自动判断是新项目规划还是现有页面升级。
4. 先获得 UI 方案或诊断报告。
5. 再使用生成的 Codex-ready prompt 让 AI coding agent 实现。

## 示例触发语

```text
Use premium-ui-builder-skill to plan the UI for this AI tool.
```

```text
这个页面太普通了，帮我诊断并给出高级感升级方案。
```

```text
Before coding, help me define the UI system for this SaaS.
```

```text
Make this interface look more like a real product, not an AI-generated template.
```

## 支持的项目类型

Landing page、SaaS dashboard、AI tool interface、Admin dashboard、个人作品集、内容生成工具、电商界面、移动端页面、桌面应用、开发者工具、数据看板、创作者工具、Onboarding、Pricing page、Settings page、文档站点。

## 不适合的场景

这个 Skill 不适合纯后端架构、数据库设计、API contract、与 UI 无关的 bug 修复、纯文案写作、只要图片生成 prompt、或要求直接实现完整设计系统包的场景。

## 输出示例

```markdown
# Premium UI Upgrade Plan

## 1. UI Diagnosis Summary
当前页面的问题不是不够花，而是信息层级不够清楚。用户不知道第一眼该看哪里，也不知道下一步应该做什么。

## 4. Upgrade Priorities
1. 先重建主操作和内容层级。
2. 再统一间距、字体、颜色和组件状态。
3. 最后添加克制的动效，只用于反馈、切换和加载。
```

## 多语言 README

- [中文默认 README](README.md)：GitHub 默认展示的中文首页。
- [English](README.en-US.md)：English README for global open-source users.
- [日本語](README.ja-JP.md)：Japanese README.
- [한국어](README.ko-KR.md)：Korean README.

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=ziguishian/premium-ui-builder-skill&type=Date)](https://www.star-history.com/#ziguishian/premium-ui-builder-skill&Date)

## 如何贡献

欢迎补充新的案例、视觉风格、诊断维度、组件模式、动效规则、前端实现建议和评测用例。贡献时请保持建议具体、可执行、适合 Codex 落地。

## License

MIT License. Copyright (c) 2026 ziguishian.
