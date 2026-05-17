# premium-ui-builder-skill

> AI Coding / Vibe Coding 워크플로를 위한 프리미엄 UI 디자인 어드바이저 Skill입니다.

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Codex Skill](https://img.shields.io/badge/Codex-Skill-black.svg)](SKILL.md)
[![Docs](https://img.shields.io/badge/docs-ready-blue.svg)](docs/usage.md)
[![Languages](https://img.shields.io/badge/i18n-zh%20%7C%20en%20%7C%20ja%20%7C%20ko-orange.svg)](#language-readmes)

**Language READMEs**: [中文](README.md) | [English](README.en-US.md) | [日本語](README.ja-JP.md) | 한국어

> Design before decoration.  
> System before style.  
> Implementation before vague aesthetics.

## 소개

`premium-ui-builder-skill`은 모호한 UI 요구사항을 실행 가능한 UI 설계 계획과 프론트엔드 구현 브리프로 바꾸는 Codex Skill입니다.

단순히 "더 예쁘게" 만드는 프롬프트 모음이 아닙니다. 제품 의도, 정보 구조, 시각적 위계, 컴포넌트 시스템, 인터랙션, 모션, 프론트엔드 제약을 함께 설계하는 방법론입니다.

## 대상 사용자

- UI 구현 전에 AI coding agent에게 명확한 디자인 방향을 주고 싶은 사용자
- Vibe Coding으로 실제 제품 같은 인터페이스를 만들고 싶은 크리에이터
- SaaS, AI 도구, 대시보드, 랜딩 페이지, 포트폴리오, 관리자 화면, 모바일 화면을 만드는 개발자
- 일반적인 템플릿 느낌을 줄이고 더 성숙한 제품 UI를 만들고 싶은 팀

## 두 가지 작업 모드

### Mode A: New Project UI Planning

처음부터 새 UI를 설계할 때 사용합니다. 제품 UI 포지셔닝, 사용자 맥락, 화면 전략, 정보 구조, 비주얼 방향, 레이아웃 시스템, 컴포넌트 시스템, 모션 전략, 프론트엔드 추천, Codex-ready prompt를 제공합니다.

### Mode B: Existing UI Upgrade / Diagnosis

이미 존재하는 페이지, 스크린샷, 코드베이스를 개선할 때 사용합니다. UI 진단, 성숙도 레벨, 주요 문제, 개선 우선순위, 정보 위계, 레이아웃, 비주얼 시스템, 컴포넌트, 모션, 구현 노트, Codex-ready redesign prompt를 제공합니다.

## 사용 방법

1. 만들 제품이나 개선할 UI 문제를 설명합니다.
2. Codex에 `premium-ui-builder-skill` 사용을 요청합니다.
3. Skill이 Mode A 또는 Mode B를 자동으로 판단합니다.
4. UI 계획 또는 진단 결과를 검토합니다.
5. 생성된 Codex-ready prompt로 프론트엔드 구현을 진행합니다.

## 예시 프롬프트

```text
Use premium-ui-builder-skill to plan the UI for this AI tool.
```

```text
This page looks too ordinary. Diagnose it and give me an upgrade plan.
```

```text
Make this interface look more like a real product, not an AI-generated template.
```

## 지원 프로젝트 유형

Landing page, SaaS dashboard, AI tool interface, Admin dashboard, Portfolio, Content generation tool, E-commerce interface, Mobile app screen, Developer tool, Data dashboard, Creator tool, Pricing page, Settings page, Documentation site.

## 파일 구조

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
- [日本語](README.ja-JP.md): Japanese README.

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=ziguishian/premium-ui-builder-skill&type=Date)](https://www.star-history.com/#ziguishian/premium-ui-builder-skill&Date)

## Contributing

새로운 예시, 비주얼 스타일, 진단 루브릭, 컴포넌트 패턴, 모션 가이드, 구현 노트, 평가 케이스를 환영합니다. 모든 내용은 구체적이고 AI coding agent가 바로 실행할 수 있어야 합니다.

## License

MIT License. Copyright (c) 2026 ziguishian.
