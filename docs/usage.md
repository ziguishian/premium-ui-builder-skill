# Usage

## Typical Flow

1. User describes the product or UI problem.
2. Skill detects whether the request is Mode A or Mode B.
3. Skill identifies project type and UI goal.
4. Skill creates page strategy or diagnosis.
5. Skill defines visual system and components.
6. Skill generates frontend implementation notes.
7. Skill outputs a Codex-ready prompt.
8. Codex implements the UI based on the prompt.

## Mode A: New Project UI Planning

Use when the user is starting from zero or wants to design before coding.

Expected output:

- Product UI positioning
- Target users and usage context
- Page / screen strategy
- Information architecture
- Visual direction
- Layout system
- Component system
- Motion and interaction strategy
- Frontend implementation recommendation
- Codex-ready implementation prompt

## Mode B: Existing UI Upgrade / Diagnosis

Use when the user already has a UI and wants to improve it.

Expected output:

- UI diagnosis summary
- Current maturity level
- Main problems
- Upgrade priorities
- Information hierarchy fixes
- Layout and spacing fixes
- Visual system fixes
- Component-level fixes
- Motion and interaction fixes
- Frontend implementation notes
- Codex-ready redesign prompt

## Example Trigger Prompts

```text
Use premium-ui-builder-skill to plan the UI for this AI tool.
```

```text
This page looks too ordinary. Diagnose it and give me an upgrade plan.
```

```text
Before coding, help me define the UI system for this SaaS.
```

```text
Make this interface look more like a real product, not an AI-generated template.
```

```text
Generate a Codex-ready UI implementation prompt for this page.
```

## Good Inputs

The Skill works best when the user provides:

- Product type
- Target users
- Primary user action
- Existing screenshot or code if available
- Desired style references
- Frontend stack if already chosen
- Constraints such as mobile-first, dark mode, accessibility, or performance

## Good Outputs

A good Skill output should:

- Explain design choices in plain language.
- Prioritize structure before decoration.
- Translate aesthetic direction into frontend instructions.
- Include components and states.
- Include responsive behavior.
- Include acceptance criteria.
