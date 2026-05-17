# Component System Guide

Specify components by purpose, anatomy, visual rules, states, behavior, and implementation notes.

## Navigation

- Purpose: Help users move across major product areas.
- Anatomy: logo, primary links, secondary links, CTA/account.
- Visual rules: keep active state obvious; avoid too many top-level items.
- States: default, active, hover, focus, collapsed mobile.
- Behavior: sticky only when useful; mobile becomes drawer or sheet.
- Implementation notes: Use semantic nav and keyboard-accessible menus.

## Sidebar

- Purpose: Persistent app module navigation.
- Anatomy: workspace switcher, nav groups, active item, utility links.
- Visual rules: compact labels, clear selected state.
- States: collapsed, expanded, active, hover, disabled.
- Behavior: collapsible on desktop, drawer on mobile.
- Implementation notes: Keep icon and label alignment consistent.

## Topbar

- Purpose: Scope, search, user actions, page-level controls.
- Anatomy: page title, breadcrumbs/search, actions, user menu.
- Visual rules: avoid competing with page content.
- States: sticky, scrolled, focused search.
- Behavior: primary actions stay visible.
- Implementation notes: Use height tokens and avoid layout shift.

## Hero

- Purpose: Establish product category, value, proof, and primary action.
- Anatomy: headline, subcopy, CTA, proof visual.
- Visual rules: first viewport signal must show product or offer.
- States: responsive stacking.
- Behavior: motion supports reveal, not confusion.
- Implementation notes: Avoid generic gradient-only hero sections.

## Feature Card

- Purpose: Explain one capability or benefit.
- Anatomy: icon/visual, title, description, optional proof.
- Visual rules: each card should have a distinct reason to exist.
- States: hover, focus if clickable.
- Behavior: clickable cards need clear affordance.
- Implementation notes: Do not use identical cards with vague copy.

## Bento Card

- Purpose: Show varied product moments in a structured grid.
- Anatomy: title, short copy, visual artifact, optional metric.
- Visual rules: mix sizes intentionally; align to one grid.
- States: hover, active if interactive.
- Behavior: avoid complex nested interactions.
- Implementation notes: Each bento cell needs stable dimensions.

## Data Table

- Purpose: Scan, compare, sort, filter, and act on records.
- Anatomy: toolbar, columns, rows, row actions, pagination.
- Visual rules: dense but readable; align numbers right.
- States: loading, empty, selected, sorted, error.
- Behavior: sorting, filtering, bulk actions, keyboard focus.
- Implementation notes: Plan mobile behavior early.

## Form

- Purpose: Collect structured input.
- Anatomy: labels, fields, help text, validation, submit action.
- Visual rules: clear grouping and required/optional distinction.
- States: focus, error, success, disabled, loading.
- Behavior: validate near the field; preserve input on errors.
- Implementation notes: Use accessible labels and error descriptions.

## Prompt Input

- Purpose: Capture natural-language instructions for AI tools.
- Anatomy: textarea, model controls, attachments, submit.
- Visual rules: make it feel like the core workspace, not a tiny field.
- States: focused, generating, disabled, error.
- Behavior: support shortcuts, token/character feedback, clear loading.
- Implementation notes: Separate primary prompt from advanced parameters.

## Result Panel

- Purpose: Display generated output, preview, or analysis.
- Anatomy: toolbar, preview area, metadata, actions.
- Visual rules: give output enough space; avoid cramped previews.
- States: empty, streaming, complete, error, selected variant.
- Behavior: copy, export, regenerate, compare.
- Implementation notes: Reserve dimensions to avoid layout shift.

## Modal

- Purpose: Focus a short task or confirmation.
- Anatomy: title, content, actions, close.
- Visual rules: strong hierarchy; avoid long workflows.
- States: open, closing, loading, error.
- Behavior: trap focus, close on escape when safe.
- Implementation notes: Use accessible dialog primitives.

## Drawer

- Purpose: Show secondary details without leaving context.
- Anatomy: header, body, actions.
- Visual rules: width appropriate to content; not a full page hidden in a drawer.
- States: open, loading, error.
- Behavior: preserves page context.
- Implementation notes: Good for row details and settings.

## Toast

- Purpose: Short feedback after an action.
- Anatomy: status icon, message, optional action.
- Visual rules: concise and semantic.
- States: success, error, warning, info.
- Behavior: auto-dismiss only for non-critical messages.
- Implementation notes: Do not hide important errors in transient toast only.

## Badge

- Purpose: Show status, category, or metadata.
- Anatomy: text, optional dot/icon.
- Visual rules: semantic colors, compact size.
- States: active, neutral, warning, error, success.
- Behavior: usually non-interactive.
- Implementation notes: Keep contrast readable.

## Tabs

- Purpose: Switch related views at the same hierarchy level.
- Anatomy: tab list, selected tab, panels.
- Visual rules: selected state must be clear.
- States: selected, hover, focus, disabled.
- Behavior: keyboard navigation.
- Implementation notes: Avoid tabs for unrelated navigation.

## Stepper

- Purpose: Show progress through a multi-step flow.
- Anatomy: steps, current state, completion states.
- Visual rules: current step strongest; completed steps clear.
- States: pending, current, complete, error.
- Behavior: allow navigation only when safe.
- Implementation notes: Include validation per step.

## Pricing Card

- Purpose: Compare plans and convert.
- Anatomy: plan name, price, features, CTA, badge.
- Visual rules: highlight recommended plan without making others unreadable.
- States: hover, selected, disabled.
- Behavior: monthly/yearly toggle if needed.
- Implementation notes: Keep feature comparison honest and scannable.

## Empty State

- Purpose: Explain absence and guide next action.
- Anatomy: title, explanation, visual, CTA.
- Visual rules: quiet but helpful.
- States: first use, filtered empty, permission empty.
- Behavior: link directly to creation or fix.
- Implementation notes: Empty states are product content, not filler.

## Loading Skeleton

- Purpose: Preserve layout while data loads.
- Anatomy: blocks matching final content.
- Visual rules: subtle contrast, no dramatic shimmer.
- States: loading, slow loading.
- Behavior: do not shift layout when content arrives.
- Implementation notes: Match expected card/table structure.

## Error State

- Purpose: Explain failure and recovery.
- Anatomy: message, cause when useful, retry/action.
- Visual rules: clear but not alarming unless destructive.
- States: inline error, page error, partial error.
- Behavior: preserve user input.
- Implementation notes: Include retry and fallback paths.

## Chart Card

- Purpose: Answer a data question.
- Anatomy: title, metric, chart, legend, timeframe.
- Visual rules: legible labels, limited colors.
- States: loading, empty, error.
- Behavior: tooltip and filter interactions.
- Implementation notes: Use Recharts or equivalent; define semantic color use.
