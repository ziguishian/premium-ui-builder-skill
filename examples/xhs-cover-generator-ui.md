# Xiaohongshu Cover Generator UI

## User Original Input

"I want to build a Xiaohongshu cover / carousel generation tool with a modern creator-tool interface."

## Detected Mode

Mode A: New Project UI Planning.

## Project Type

Creator tool interface / content generation tool.

## UI Goal

Help creators generate, preview, edit, and export Xiaohongshu covers and carousel pages efficiently.

## Key Design Problems or Assumptions

- The product needs a real workspace, not a landing page.
- Preview canvas must be central.
- Controls should support presets, brand styles, copy, templates, and export.

## Recommended UI Strategy

Use Creator Tool Interface + Premium Minimal. Layout should resemble a practical editor: controls, canvas, property panel/history.

## Information Architecture

- Left: template presets, content input, brand tone.
- Center: cover/carousel preview canvas.
- Right: style controls, page list, export options.
- Bottom/top: generation actions, undo/redo, save.
- States: empty canvas, generating, variant comparison, export success.

## Visual System

- Background: neutral workspace gray.
- Canvas: high-contrast framed preview with exact aspect ratio.
- Accent: one energetic creator-focused color.
- Typography: practical labels and readable controls.
- Components: toolbars, swatches, segmented controls, sliders.

## Component System

Template gallery, prompt/content form, style preset chips, color swatches, canvas preview, carousel page strip, property panel, generation history, export menu, toast.

## Motion Strategy

Use direct manipulation feedback, generation progress, page selection transition, and export confirmation. Avoid background animation near the canvas.

## Frontend Implementation Recommendation

React / Next.js, TypeScript, Tailwind CSS, shadcn/ui, lucide-react. Use canvas/SVG/HTML preview depending on export approach.

## Codex-ready Prompt

```text
Build a modern Xiaohongshu cover/carousel generator UI as a creator-tool workspace. Layout: left panel for templates and content input, center canvas preview with Xiaohongshu cover/carousel aspect ratio, right panel for style controls and page list, top toolbar for undo/redo/save/export. Include template gallery, prompt/content form, tone selector, style preset chips, color swatches, typography selector, canvas preview, carousel thumbnails, generation history, export menu, loading and empty states. Visual direction: Creator Tool Interface + Premium Minimal with neutral workspace, strong canvas focus, one energetic accent, crisp controls, and clear selected states. Motion should show generation progress, selected page changes, and export success only. Responsive: desktop multi-panel, tablet collapsible side panels, mobile tabbed editor/preview/export views. Avoid landing-page layout, decorative cards, and effects that distract from the canvas. Acceptance: users can input content, choose a style, preview covers, compare variants, and export without confusion.
```

## Acceptance Criteria

- Preview canvas is the visual center.
- Creator controls are discoverable.
- Export and variant states are clear.
- Mobile has a workable tabbed flow.
