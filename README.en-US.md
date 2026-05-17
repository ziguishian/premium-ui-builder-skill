# premium-ui-builder-skill

> A premium UI design advisor skill for AI Coding and Vibe Coding workflows.

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Codex Skill](https://img.shields.io/badge/Codex-Skill-black.svg)](SKILL.md)
[![Docs](https://img.shields.io/badge/docs-ready-blue.svg)](docs/usage.md)
[![Languages](https://img.shields.io/badge/i18n-zh%20%7C%20en%20%7C%20ja%20%7C%20ko-orange.svg)](#language-readmes)

**Language READMEs**: [中文](README.md) | English | [日本語](README.ja-JP.md) | [한국어](README.ko-KR.md)

> Design before decoration.  
> System before style.  
> Implementation before vague aesthetics.

## What This Is

`premium-ui-builder-skill` is a documentation-first Codex Skill that turns vague UI requests into executable design plans and frontend implementation briefs.

It is not a prompt collection for "making things beautiful." It is a reusable methodology for connecting product intent, information architecture, visual hierarchy, component systems, motion, and frontend constraints.

## Who It Is For

- AI coding agents that need clearer UI direction before implementation
- Vibe Coding learners who know what feeling they want but not how to specify it
- Indie hackers and product builders improving early product interfaces
- Designers and frontend developers who want a shared UI planning language
- Creators building SaaS, AI tools, dashboards, landing pages, portfolios, admin panels, mobile screens, or content tools

## Why Premium UI Needs a System

Premium UI does not come from adding more gradients, shadows, glass, or animations. It comes from structure:

- Clear information hierarchy
- Consistent spacing and alignment
- A restrained visual system
- Component states that feel real
- Motion that explains state changes
- Responsive behavior that does not collapse under real content

## Problems It Solves

- "Make this page more premium."
- "This looks too ordinary."
- "Make it look like a real product."
- "Add more tech feeling."
- "Make it less AI-generated."
- "I want Apple / Linear / Notion / Vercel style."
- "This page lacks hierarchy and visual impact."
- "Help me design the UI before coding."

## Two Working Modes

### Mode A: New Project UI Planning

For products that are being planned from zero. The Skill creates product positioning, page strategy, information architecture, visual direction, layout rules, component system, motion strategy, frontend recommendations, and a Codex-ready implementation prompt.

### Mode B: Existing UI Upgrade / Diagnosis

For pages, screenshots, or codebases that already exist. The Skill diagnoses UI maturity, identifies problems, prioritizes upgrades, defines visual and component fixes, and produces a Codex-ready redesign prompt.

## File Structure

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

## How to Use

1. Describe the product or existing UI problem.
2. Ask Codex to use `premium-ui-builder-skill`.
3. Let the Skill detect Mode A or Mode B.
4. Review the generated UI plan or upgrade diagnosis.
5. Use the Codex-ready prompt to implement the interface.

## Example Prompts

```text
Use premium-ui-builder-skill to plan the UI for this AI tool.
```

```text
This page looks too ordinary. Diagnose it and give me a premium upgrade plan.
```

```text
Before coding, help me define the UI system for this SaaS dashboard.
```

```text
Make this interface look more like a real product, not an AI-generated template.
```

## Supported Project Types

Landing pages, SaaS dashboards, AI tool interfaces, admin dashboards, personal portfolios, content generation tools, e-commerce interfaces, mobile app screens, desktop app interfaces, developer tools, data dashboards, creator tools, onboarding flows, pricing pages, settings pages, and documentation sites.

## When Not to Use

Do not use this Skill for backend architecture, database design, API contract design, non-UI bug fixes, pure copywriting, image-generation-only prompts, or building a full design system package.

## Output Example

```markdown
# Premium UI Upgrade Plan

## 1. UI Diagnosis Summary
The current page is usable but visually generic. The main issue is not missing decoration; it is weak hierarchy, inconsistent spacing, and components that lack real product states.

## 4. Upgrade Priorities
1. Rebuild the page hierarchy around the primary user action.
2. Define a restrained color and typography system.
3. Upgrade cards, tables, empty states, loading states, and focus states.
4. Add purposeful motion only for feedback and transitions.
```

## Language READMEs

- [中文](README.md): Chinese default README.
- [简体中文](README.zh-CN.md): Simplified Chinese mirror README.
- [日本語](README.ja-JP.md): Japanese README.
- [한국어](README.ko-KR.md): Korean README.

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=ziguishian/premium-ui-builder-skill&type=Date)](https://www.star-history.com/#ziguishian/premium-ui-builder-skill&Date)

## Contributing

Contributions are welcome. Add new examples, visual styles, diagnosis cases, component patterns, motion rules, implementation notes, or eval cases. Keep advice practical and implementation-ready.

## License

MIT License. Copyright (c) 2026 ziguishian.
