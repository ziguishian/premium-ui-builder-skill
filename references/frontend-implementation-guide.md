# Frontend Implementation Guide

Translate design advice into buildable frontend instructions.

## React / Next.js

- Break pages into semantic sections and reusable components.
- Keep data, layout, and visual tokens separate.
- Use server/client boundaries intentionally in Next.js.
- Build real states: loading, empty, error, disabled, selected.

## TypeScript Component Planning

Define props around product meaning:

- `status`, `variant`, `density`, `isLoading`, `isSelected`, `onAction`
- Avoid passing raw class strings everywhere.
- Use discriminated unions for components with distinct states.

## Tailwind CSS Design Tokens

- Define color, radius, spacing, shadow, and typography tokens.
- Prefer consistent utility patterns over one-off arbitrary values.
- Use CSS variables when themes or dark mode are needed.
- Keep component spacing predictable.

## shadcn/ui

- Use for accessible primitives and common app components.
- Customize tokens and variants instead of rewriting every component.
- Good for dialogs, dropdowns, tabs, forms, tables, toasts, and command menus.

## Framer Motion

- Use for purposeful transitions, layout changes, route transitions, and micro-feedback.
- Keep durations short for app UIs.
- Respect reduced motion.
- Avoid animating large lists without virtualization or restraint.

## lucide-react

- Use for consistent line icons.
- Keep icon sizes consistent.
- Pair icon-only buttons with accessible labels and tooltips when needed.

## Recharts

- Use for dashboards and analytics.
- Define semantic chart colors.
- Include empty/loading/error states.
- Keep legends and tooltips readable.

## Three.js / React Three Fiber

- Use only when 3D supports brand or comprehension.
- Provide mobile fallbacks.
- Avoid blocking core UI.
- Keep canvas behind or beside readable content.

## Responsive Breakpoints

Recommended baseline:

- Mobile: below 640px
- Tablet: 640px-1024px
- Desktop: 1024px and above
- Wide: 1280px and above

Plan how navigation, grids, tables, hero visuals, and tool panels adapt.

## Accessibility Basics

- Use semantic HTML.
- Keep visible focus states.
- Ensure contrast for body text and controls.
- Label inputs and icon buttons.
- Preserve keyboard navigation.
- Respect `prefers-reduced-motion`.

## Dark Mode and Light Mode

- Define semantic variables such as background, surface, border, text, muted, primary, success, warning, error.
- Do not simply invert colors.
- Test charts, badges, and focus rings in both modes.

## CSS Variables and Design Tokens

Useful token groups:

- `--color-bg`
- `--color-surface`
- `--color-border`
- `--color-text`
- `--color-muted`
- `--color-primary`
- `--radius-sm/md/lg`
- `--shadow-card/popover`
- `--space-section`

## Avoid Messy One-off Styles

- Do not use unique spacing for every card.
- Do not create many unrelated shadows.
- Do not mix multiple icon styles.
- Do not hardcode colors in every component.
- Do not use animation as a substitute for hierarchy.
