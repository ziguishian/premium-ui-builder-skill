# AI Tool Interface

## User Original Input

"I want to build an AI generation tool interface with prompt input, model options, generation history, and result preview."

## Detected Mode

Mode A: New Project UI Planning.

## Project Type

AI tool interface / content generation tool.

## UI Goal

Create a focused workspace where users can prompt, tune, generate, compare, and export results.

## Key Design Problems or Assumptions

- The prompt/result workflow must be the center.
- Advanced options should not overwhelm beginners.
- Generation states are essential to product realism.

## Recommended UI Strategy

Use AI-native Dark Interface + Creator Tool Interface. Design a three-zone workspace: controls, preview, history.

## Information Architecture

- Primary: prompt input and generate action.
- Secondary: model options, style presets, history.
- Output: result preview, variants, metadata, export/refine actions.
- States: empty preview, streaming, queued, failed, completed.

## Visual System

- Background: deep neutral with subtle panel layering.
- Accent: one luminous color for generation and focus.
- Typography: compact labels, readable prompt/result text.
- Components: layered panels with borders, not heavy glow.

## Component System

Prompt editor, model selector, parameter controls, preset chips, generate button, result panel, variant tabs, history list, export menu, toast, loading progress.

## Motion Strategy

Animate generation progress and streaming output. Use subtle selected-state transitions for variants. Avoid constantly moving background near the editor.

## Frontend Implementation Recommendation

React / Next.js, TypeScript, Tailwind CSS, shadcn/ui, lucide-react, Framer Motion. Add resizable panels if useful.

## Codex-ready Prompt

```text
Build an AI generation tool interface with a premium AI-native dark workspace. Structure the UI into prompt controls, result preview, and generation history. Include prompt editor, model selector, advanced settings disclosure, preset chips, generate button, result preview panel, variant tabs, history list, export/refine actions, and toast feedback. Visual direction: deep neutral background, subtle borders, layered panels, one controlled luminous accent, readable typography, and clear focus states. Include empty, generating, streaming, complete, failed, and copied/exported states. Motion should explain generation progress and selected variants; avoid decorative constant movement. Responsive: desktop uses multi-panel layout, tablet stacks controls above preview, mobile uses tabs or segmented views. Acceptance: a user can understand where to type, how to generate, where results appear, and how to refine or export.
```

## Acceptance Criteria

- Prompt input is visually central.
- Advanced controls are available but not overwhelming.
- Generation states are clear.
- Preview has enough space and stable dimensions.
