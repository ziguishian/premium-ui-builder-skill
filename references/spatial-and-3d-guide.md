# Spatial and 3D Guide

Use spatial and 3D effects only when they support product meaning, brand memory, or comprehension.

## When to Use 3D

- The product has a technical, AI, hardware, spatial, or creative identity.
- A 3D element can explain the product better than a flat graphic.
- The 3D layer can remain secondary to the main task.
- Performance budgets allow it.

## When Not to Use 3D

- The UI is primarily forms, tables, or admin workflows.
- The effect competes with text or controls.
- Mobile performance would suffer.
- The only reason is "make it look premium."

## Patterns

### Subtle Depth Layers

Use layered surfaces with clear z-order: background, panel, active control, overlay. Keep contrast high.

### Glass Panels

Use translucent panels with blur and borders only when background contrast is controlled. Always test text readability.

### Floating Cards

Use small translate or shadow differences to show active state. Avoid random floating blocks.

### 3D Orb

Useful for AI-native or data products as a brand object. Keep it decorative and secondary unless the product itself is spatial.

### Particle Field

Use sparingly as an ambient background. Avoid dense particles behind text or input fields.

### Shader Gradient

Good for premium hero backgrounds or AI product atmosphere. Keep it slow, soft, and behind content.

### Parallax

Use for depth in landing pages. Avoid parallax in core productivity workflows.

### Perspective Cards

Use for feature previews or case-study visuals. Do not tilt important forms or data tables.

## Performance Considerations

- Prefer static 3D assets when interaction is not needed.
- Pause offscreen canvas work.
- Limit particle count.
- Avoid heavy post-processing on mobile.
- Provide CSS fallback or static fallback.

## Accessibility and Readability

- Foreground text must remain clear.
- Respect reduced motion.
- Do not place controls inside moving 3D objects unless the interaction is core.
- Avoid depth illusions that make click targets ambiguous.

## Practical Recommendations

- Three.js: Use for custom canvas scenes, shaders, particles, and standalone 3D hero visuals.
- React Three Fiber: Use in React apps when 3D must integrate with component state.
- CSS 3D transform: Use for lightweight card perspective and hover depth.
- Shader gradient backgrounds: Use for brand atmosphere behind static UI.
- Static 3D assets: Use when visual polish is needed without runtime cost.
