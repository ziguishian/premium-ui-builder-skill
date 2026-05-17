# UI Diagnosis Rubric

Score each dimension from 1 to 5.

## 1. Information Hierarchy

- Level 1: Everything has similar visual weight; users do not know where to look.
- Level 3: Main content is visible, but secondary content competes.
- Level 5: Primary goal, supporting details, and secondary actions are clearly ordered.
- Common fixes: Increase heading contrast, reduce secondary emphasis, group related content, make the primary CTA more obvious.

## 2. Layout Alignment

- Level 1: Elements float randomly with inconsistent edges.
- Level 3: Most blocks align, but cards and sections do not share a grid.
- Level 5: A clear grid controls sections, cards, controls, and content widths.
- Common fixes: Use a shared container, consistent columns, aligned card edges, and predictable gutters.

## 3. Spacing Rhythm

- Level 1: Spacing is arbitrary; dense and empty areas feel accidental.
- Level 3: Spacing is mostly usable but lacks vertical rhythm.
- Level 5: Spacing scale creates calm grouping and strong scan flow.
- Common fixes: Define 4/8px spacing scale, separate sections more than items, reduce card padding variance.

## 4. Typography Quality

- Level 1: Too many sizes, weak contrast, poor line height.
- Level 3: Type is readable but hierarchy is generic.
- Level 5: Type scale, weight, line height, and metadata styles are controlled.
- Common fixes: Limit sizes, increase title/body contrast, tune line height, create metadata and label styles.

## 5. Color System

- Level 1: Random colors, too many accents, poor contrast.
- Level 3: Usable palette but not tied to function.
- Level 5: Neutrals, accents, semantic colors, and surfaces have clear roles.
- Common fixes: Use one primary accent, define success/warning/error, reduce saturated backgrounds, check contrast.

## 6. Component Consistency

- Level 1: Buttons, cards, inputs, and badges all use different rules.
- Level 3: Common components exist but states are incomplete.
- Level 5: Components share tokens, anatomy, states, and interaction rules.
- Common fixes: Normalize radii, padding, borders, icons, hover/focus/disabled states.

## 7. Interaction States

- Level 1: Controls have no hover, focus, disabled, loading, or error states.
- Level 3: Main controls have some states but secondary components do not.
- Level 5: All interactive components communicate state clearly.
- Common fixes: Add focus rings, loading indicators, disabled styling, validation messages, selected states.

## 8. Motion Quality

- Level 1: No motion or excessive random motion.
- Level 3: Some transitions exist but they do not explain state.
- Level 5: Motion is subtle, purposeful, consistent, and respects reduced motion.
- Common fixes: Use short durations, consistent easing, animate state transitions only, avoid scroll animation overload.

## 9. Responsiveness

- Level 1: Desktop layout breaks on mobile.
- Level 3: Content stacks but hierarchy or spacing becomes weak.
- Level 5: Each breakpoint has planned navigation, density, and component behavior.
- Common fixes: Define breakpoints, stack cards, simplify tables, adapt nav, test long text.

## 10. Product Realism

- Level 1: Looks like a placeholder or concept shot.
- Level 3: Some realistic content exists but workflows feel incomplete.
- Level 5: Realistic data, empty/loading/error states, settings, filters, and feedback exist.
- Common fixes: Add real sample data, action states, form validation, empty states, and workflow-specific controls.

## 11. Brand Feeling

- Level 1: Generic template with no recognizable personality.
- Level 3: Some style direction exists but it is inconsistent.
- Level 5: Visual choices consistently support the product's desired impression.
- Common fixes: Define 3-5 visual keywords, remove unrelated effects, choose a distinct but restrained accent system.

## 12. Implementation Feasibility

- Level 1: Design advice is too vague or too complex to build.
- Level 3: Implementable but lacks exact component/state guidance.
- Level 5: Clear component plan, tokens, breakpoints, motion specs, and acceptance criteria.
- Common fixes: Translate feelings into CSS rules, component specs, library choices, and testable outcomes.
