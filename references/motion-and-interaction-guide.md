# Motion and Interaction Guide

Motion should support meaning. It should explain state, feedback, navigation, loading, focus, or progress.

## Hover Behavior

- Use small color, border, shadow, or translate changes.
- Keep hover effects consistent by component type.
- Do not move layout around on hover.

## Press Behavior

- Buttons should feel responsive with a slight scale, shade, or inset change.
- Press feedback should be immediate and short.
- Keep destructive actions visually distinct.

## Focus Behavior

- Every interactive element needs visible focus.
- Use focus rings that fit the visual system.
- Do not remove outlines without replacing them.

## Scroll Reveal

- Use only for narrative pages and non-critical supporting content.
- Avoid revealing essential controls late.
- Keep distance small and duration short.

## Page Transition

- Use route transitions to preserve orientation.
- Keep app transitions faster than marketing transitions.
- Avoid full-page animations that block task completion.

## Loading State

- Use skeletons for structured content.
- Use progress indicators for generation or long-running tasks.
- Preserve layout space to avoid jumping.

## Skeleton Loading

- Match the shape of the final UI.
- Use subtle shimmer or pulse.
- Avoid loading skeletons for instant content.

## Micro-interactions

Good uses:

- Copy success
- Save state
- Upload progress
- Generation progress
- Row selection
- Filter applied

Poor uses:

- Random icon spinning
- Constant ambient movement near body text
- Animating every card independently

## Duration Guidelines

- Micro feedback: 80-150ms
- Small panel transitions: 150-220ms
- Page or section transitions: 220-360ms
- Ambient background: slow and non-critical

## Easing Guidelines

- Use ease-out for entering elements.
- Use ease-in for leaving elements.
- Use spring motion sparingly for direct manipulation.
- Keep app UI calmer than playful interfaces.

## Reduced Motion Guidelines

- Respect `prefers-reduced-motion`.
- Replace movement with opacity or instant state change.
- Never require animation to understand the UI.

## What Not to Animate

- Long paragraphs
- Dense tables during scanning
- Primary controls while users are deciding
- Error messages that move away too quickly
- Backgrounds that compete with inputs
