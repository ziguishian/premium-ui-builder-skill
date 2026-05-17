# Design Principles

## 1. Structure Before Decoration

A premium UI starts with information architecture, layout rhythm, and clear user intent. Do not add gradients, shadows, glass effects, or animations before the structure is understandable.

Checklist:

- The primary action is visible without explanation.
- The page has a clear first, second, and third reading order.
- Sections are grouped by user intent, not by visual convenience.
- Decorative effects never compete with the main content.

## 2. Product Realism Over Dribbble Aesthetics

The UI should feel like a real product that people can operate, not a static concept shot.

Prioritize:

- Real content density
- Empty states
- Error states
- Loading states
- Disabled states
- Responsive behavior
- Keyboard and focus behavior

Avoid:

- Perfect but unrealistic fake data
- Oversized hero areas that hide the product
- Components without states
- Visual effects that make common workflows slower

## 3. Visual Hierarchy Creates Premium Feeling

Premium feeling comes from knowing what matters most. A page without hierarchy feels generic even if the colors are fashionable.

Ask:

- What should users see first?
- What should they do next?
- Which information is primary?
- Which information should stay secondary?
- Which elements need contrast, and which need quietness?

## 4. Consistency Beats Complexity

A simple but consistent visual system is stronger than many unrelated effects.

Define:

- Color rules
- Typography scale
- Spacing scale
- Radius scale
- Shadow rules
- Border rules
- Component states

## 5. Motion Must Explain State

Motion should clarify state change, feedback, navigation, loading, focus, or progress. Motion that exists only to look cool usually makes the UI feel less mature.

Use motion for:

- Button press feedback
- Panel open / close transitions
- Loading progress
- Tab or route transitions
- Error or success acknowledgement

Do not animate:

- Long body text
- Critical controls while users are reading
- Data tables without purpose
- Everything on scroll

## 6. 3D Must Support the Product

3D, particles, shaders, and spatial effects should support brand feeling or user understanding. They should not reduce readability, performance, or accessibility.

3D helps when:

- The product sells a technical or spatial idea.
- The effect creates a memorable brand surface.
- It stays behind the content or appears in a controlled feature area.

3D distracts when:

- It competes with form fields, tables, or CTAs.
- It makes mobile performance unstable.
- It becomes the only sign of "premium."

## 7. Accessibility Is Part of Premium Design

Premium UI must be usable. Contrast, focus, readable type, predictable controls, and reduced motion support are not optional extras.

Minimum expectations:

- Visible focus states
- Proper semantic elements
- Color contrast suitable for body text and controls
- Labels for inputs and icon buttons
- Motion alternatives for users who prefer reduced motion

## 8. Responsive Behavior Is Not Optional

A design is not complete until it works across desktop, tablet, and mobile.

Plan:

- Which content collapses
- Which navigation changes form
- Which panels stack
- Which data tables need horizontal scroll or card conversion
- Which hero or visual assets should shrink or disappear

## 9. Implementation Constraints Matter

Design advice must map to implementation. Codex needs component names, layout rules, token values, state requirements, breakpoints, and acceptance criteria.

Good instruction:

> Use a 12-column desktop grid, 24px section gutters, max-width 1200px, and convert the analytics cards to a 1-column stack below 768px.

Weak instruction:

> Make the layout more modern.

## 10. Avoiding AI-generated Template Feeling

AI-generated UI often feels generic because it stacks predictable patterns: big gradient hero, vague feature cards, identical rounded cards, generic icons, and no real states.

Fix it by:

- Using product-specific information hierarchy
- Writing realistic labels and sample data
- Varying component structure based on content
- Defining clear states
- Reducing decorative effects
- Making the main workflow visible
