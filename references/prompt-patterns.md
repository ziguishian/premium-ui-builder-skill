# Prompt Patterns

Each pattern turns design direction into implementable AI coding instructions.

## 1. New Project UI Planning Prompt

- When to use: Starting a product from zero.
- Required inputs: product idea, target user, core workflow, desired impression, existing stack if any.
- Prompt template:

```text
Use premium-ui-builder-skill in Mode A. Plan the UI for [product]. Target users are [users]. The core workflow is [workflow]. Desired impression: [visual feeling]. Output product type, IA, visual system, component system, motion strategy, frontend recommendation, and a Codex-ready implementation prompt.
```

- Acceptance criteria: Clear mode, project type, page list, component list, implementation prompt.

## 2. Existing Page Redesign Prompt

- When to use: Improving an existing page or screenshot.
- Required inputs: page purpose, current issues, screenshot/code/context.
- Prompt template:

```text
Use premium-ui-builder-skill in Mode B. Diagnose this existing [page/app] UI. It currently feels [problem]. Identify maturity level, main problems, priority fixes, visual system changes, component changes, motion changes, and write a Codex-ready redesign prompt.
```

- Acceptance criteria: Specific diagnosis, prioritized fixes, before/after direction.

## 3. Landing Page Prompt

- When to use: Marketing or conversion page.
- Required inputs: offer, audience, CTA, proof.
- Prompt template:

```text
Design a premium landing page for [offer]. Audience: [audience]. Primary CTA: [CTA]. Use [style direction]. Plan hero, proof, features, workflow, trust, pricing/final CTA, responsive behavior, and implementation notes.
```

- Acceptance criteria: Conversion hierarchy, product proof, non-generic sections.

## 4. Dashboard Prompt

- When to use: SaaS, analytics, admin, or data dashboards.
- Required inputs: data types, user decisions, actions.
- Prompt template:

```text
Plan a premium dashboard UI for [product]. Users need to monitor [data] and take [actions]. Define navigation, summary metrics, tables/charts, filters, empty/loading/error states, responsive behavior, and frontend component specs.
```

- Acceptance criteria: Operational clarity, real states, table/chart guidance.

## 5. AI Tool Interface Prompt

- When to use: Prompt-based or generation tools.
- Required inputs: input, model options, output, history/export needs.
- Prompt template:

```text
Plan an AI tool interface for [task]. It needs prompt input, model controls, generation history, result preview, and export/refine actions. Define layout, states, visual system, motion for generation, and implementation notes.
```

- Acceptance criteria: Prompt/result workflow is central and usable.

## 6. Mobile Screen Prompt

- When to use: Single mobile screen or mobile-first product.
- Required inputs: screen purpose, primary action, content.
- Prompt template:

```text
Design a premium mobile screen for [app]. Primary task: [task]. Define hierarchy, navigation, touch targets, component states, motion, responsive constraints, and implementation-ready details.
```

- Acceptance criteria: Clear one-hand workflow, touch-safe controls.

## 7. Component Upgrade Prompt

- When to use: Improving a specific component.
- Required inputs: component name, current problem, product context.
- Prompt template:

```text
Upgrade the [component] for [product]. Current issue: [issue]. Specify purpose, anatomy, visual rules, states, interaction behavior, responsive behavior, and implementation acceptance criteria.
```

- Acceptance criteria: Complete states and visual consistency.

## 8. Motion Refinement Prompt

- When to use: UI exists but interactions feel flat or excessive.
- Required inputs: components, states, desired feel.
- Prompt template:

```text
Refine motion for [UI]. Define hover, press, focus, panel transitions, loading, micro-interactions, reduced motion behavior, durations, easing, and what must remain static.
```

- Acceptance criteria: Motion explains state and avoids over-animation.

## 9. 3D / Spatial UI Prompt

- When to use: 3D may support brand or comprehension.
- Required inputs: product type, 3D purpose, performance constraints.
- Prompt template:

```text
Evaluate whether spatial/3D UI helps [product]. If useful, define the depth concept, placement, interaction, performance constraints, accessibility fallback, and frontend implementation approach.
```

- Acceptance criteria: 3D has purpose and fallback.

## 10. Design System Prompt

- When to use: Need consistent UI rules before implementation.
- Required inputs: product type, style, components.
- Prompt template:

```text
Define a lightweight UI system for [product]. Include tokens for color, typography, spacing, radius, shadow, border, components, states, responsive rules, and implementation notes for [stack].
```

- Acceptance criteria: Tokens and states are concrete.

## 11. "Make It Less AI-looking" Prompt

- When to use: Generic template feeling.
- Required inputs: current UI, product purpose.
- Prompt template:

```text
Diagnose why this UI feels AI-generated. Replace generic sections with product-specific hierarchy, realistic content, real component states, restrained visual rules, and a Codex-ready redesign prompt.
```

- Acceptance criteria: Less generic, more product-specific.

## 12. "Make It More Like a Real Product" Prompt

- When to use: Early prototype feels fake.
- Required inputs: workflow, missing states, target user.
- Prompt template:

```text
Upgrade this prototype so it feels like a real product. Add workflow-specific navigation, realistic data, empty/loading/error states, component states, responsive behavior, and implementation acceptance criteria.
```

- Acceptance criteria: Real workflow and state coverage.
