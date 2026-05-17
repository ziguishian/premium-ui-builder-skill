# Before / After UI Diagnosis

## User Original Input

"This existing UI looks too ordinary. Give me a systematic diagnosis and upgrade plan."

## Detected Mode

Mode B: Existing UI Upgrade / Diagnosis.

## Project Type

Existing UI upgrade. Exact type depends on the provided screenshot or codebase.

## UI Goal

Move the UI from generic and flat to structured, product-specific, and implementation-ready.

## Key Design Problems or Assumptions

- The issue is probably not "not enough decoration."
- Common root causes: weak hierarchy, inconsistent spacing, generic cards, missing states, and no product-specific visual focus.
- Upgrade should prioritize structure first.

## Recommended UI Strategy

Diagnose maturity level, then move one level higher. If Level 2, target Level 3/4 before attempting Level 5 brand effects.

## Information Architecture

- Identify the primary user goal.
- Reorder content around the main task.
- Make the primary CTA dominant.
- Move secondary settings or explanations into quieter areas.
- Add empty/loading/error state planning.

## Visual System

- Choose one style direction based on product type.
- Define background, surface, border, type scale, accent, and state colors.
- Remove unrelated effects.
- Make realistic content and component states visible.

## Component System

Audit navbar/sidebar, hero/header, cards, forms, tables, modals, empty states, and loading states. For each, define purpose, visual rule, and states.

## Motion Strategy

Add motion only for feedback: hover, focus, loading, panel open, selected state, success/error.

## Frontend Implementation Recommendation

Adapt to the existing stack. Do not rewrite the app if tokens and components can be improved in place.

## Codex-ready Prompt

```text
Diagnose and upgrade this existing UI so it feels like a real premium product. Start by identifying the page type, current maturity level, primary user goal, and main hierarchy problems. Then implement prioritized fixes: reorder content around the primary action, align sections to a consistent grid, normalize spacing and typography, define a restrained color/surface/border/radius system, improve component states, and add loading/empty/error states. Motion should be limited to hover, focus, selected, loading, and panel transitions. Avoid solving the problem by adding random gradients, glass, shadows, or excessive animation. Acceptance: the upgraded UI has a clear first reading point, one dominant primary action, consistent components, real states, responsive behavior, and a product-specific visual direction.
```

## Acceptance Criteria

- Diagnosis names root causes, not just symptoms.
- Upgrade priorities are ordered.
- Before/after direction is clear.
- Prompt is implementable by Codex.
