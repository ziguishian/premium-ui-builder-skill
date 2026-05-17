# Admin Dashboard Upgrade

## User Original Input

"I have an admin dashboard that looks plain and table-heavy. Make it more professional without hurting usability."

## Detected Mode

Mode B: Existing UI Upgrade / Diagnosis.

## Project Type

Admin dashboard.

## UI Goal

Improve professional polish while preserving density, scanning speed, and operational clarity.

## Key Design Problems or Assumptions

- The dashboard likely relies on raw tables with little hierarchy.
- The solution should not become a marketing-style page.
- Professional polish should come from filters, status, table states, and layout discipline.

## Recommended UI Strategy

Use High-contrast Technical UI + Premium Minimal. Keep tables central but add summary, filters, status badges, and detail drawers.

## Information Architecture

- Scope/filter bar first.
- Operational summary cards second.
- Main table third.
- Detail drawer for row inspection.
- Bulk actions and export in toolbar.
- Empty/loading/error states for table and filters.

## Visual System

- Color: neutral app background, white or dark surfaces, semantic status colors.
- Typography: compact but readable.
- Borders: dividers instead of heavy card shadows.
- Density: medium-high, with spacing scale.

## Component System

Filter bar, status summary cards, data table, status badges, row action menu, detail drawer, bulk action toolbar, pagination, toast.

## Motion Strategy

Use minimal transitions for drawer and row selection. Avoid animated charts or scroll reveals.

## Frontend Implementation Recommendation

Use existing stack. Add accessible table primitives, shadcn/ui components if React, and clear CSS tokens.

## Codex-ready Prompt

```text
Upgrade this admin dashboard so it feels professional while preserving usability and data density. Do not turn it into a marketing-style dashboard. Add a clear filter/scope bar, compact summary cards, improved data table hierarchy, semantic status badges, row actions, bulk action toolbar, pagination, and a detail drawer. Visual direction: High-contrast Technical UI + Premium Minimal with neutral surfaces, subtle borders, readable compact typography, and semantic status colors. Define loading, empty, error, selected row, sorted column, disabled action, and drawer states. Motion should be limited to drawer transition, row feedback, and toast feedback. Acceptance: users can scan the table faster, understand status at a glance, and perform row/bulk actions without losing context.
```

## Acceptance Criteria

- Table remains central and scannable.
- Filters and summaries improve context.
- Row details do not require page navigation.
- No unnecessary decorative effects.
