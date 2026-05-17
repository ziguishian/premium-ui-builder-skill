# New SaaS Dashboard

## User Original Input

"I want to build a new SaaS dashboard from scratch. Make it look premium and product-ready."

## Detected Mode

Mode A: New Project UI Planning.

## Project Type

SaaS dashboard. The user needs an operational app surface with navigation, metrics, workflows, and states.

## UI Goal

Create a dashboard that feels trustworthy, clear, and ready for daily use by business users.

## Key Design Problems or Assumptions

- The product needs real app structure, not a landing-page hero.
- Users need to scan status quickly and act on important items.
- Premium feeling should come from hierarchy, density control, and component polish.

## Recommended UI Strategy

Use a polished product interface with a left sidebar, compact topbar, summary metrics, primary workflow cards, and recent activity. Target Level 4 maturity first.

## Information Architecture

- Primary: current business status and required actions.
- Secondary: trends, alerts, recent activity.
- Navigation: Overview, Customers, Reports, Automations, Settings.
- States: loading skeletons for metrics, empty state for no activity, inline error for failed data.

## Visual System

- Style: Premium Minimal + Linear-style SaaS.
- Colors: light neutral surfaces with one blue or violet accent and semantic status colors.
- Typography: clean sans, strong dashboard title, compact metadata.
- Borders: subtle 1px borders for panels.
- Radius: 8px cards, 6px controls.
- Shadows: very light, only for overlays.

## Component System

| Component | Purpose | States |
| --- | --- | --- |
| Sidebar | Module navigation | active, hover, collapsed |
| Topbar | Search, date range, account | focused, menu open |
| Metric cards | Summary status | loading, positive, warning |
| Chart card | Trend explanation | loading, empty, tooltip |
| Activity feed | Recent events | empty, filtered |
| Data table | Records and actions | sorted, selected, loading |

## Motion Strategy

Use fast hover and focus feedback. Animate panel entry subtly on first load. Use skeleton loading, not dramatic spinners.

## Frontend Implementation Recommendation

React / Next.js, TypeScript, Tailwind CSS, shadcn/ui, lucide-react, Recharts. Use CSS variables for tokens and define responsive sidebar behavior.

## Codex-ready Prompt

```text
Implement a premium SaaS dashboard UI. Use a sidebar + topbar app shell, overview metrics, chart cards, recent activity, and a data table. Visual direction: premium minimal with Linear-style operational clarity. Use restrained neutrals, one accent color, subtle borders, 8px cards, clear focus states, and realistic loading/empty/error states. Build responsive behavior: sidebar collapses on tablet and becomes a drawer on mobile; metric cards stack below 768px. Use React/Next.js, TypeScript, Tailwind CSS, shadcn/ui, lucide-react, and Recharts if available. Avoid generic marketing hero sections, excessive gradients, and decorative animation. Acceptance: primary status visible above the fold, all controls have hover/focus/disabled states, table has loading and empty states, and mobile layout remains usable.
```

## Acceptance Criteria

- App shell feels like a real SaaS product.
- Primary metrics are visible immediately.
- Tables and charts include loading, empty, and error states.
- Navigation has active and collapsed states.
- Mobile layout is planned, not accidental.
