# Visual Style Library

Use styles as strategic directions, not decorative presets. Combine at most two compatible styles.

## 1. Premium Minimal

- Suitable for: SaaS, productivity, finance, personal tools.
- Not suitable for: youth campaigns, highly expressive games.
- Visual keywords: restrained, spacious, precise, calm.
- Color direction: warm or cool neutrals with one accent.
- Typography direction: clean sans, strong title/body contrast.
- Layout direction: generous whitespace, strict grid, few sections.
- Component style: subtle borders, low shadows, crisp states.
- Motion style: short fades and gentle transforms.
- Avoid: empty luxury styling without workflow depth.
- Implementation notes: Use tokens for neutral surfaces, border opacity, spacing scale.

## 2. Editorial Tech

- Suitable for: AI products, research tools, developer storytelling, portfolios.
- Not suitable for: dense admin operations.
- Visual keywords: narrative, technical, high-contrast, structured.
- Color direction: neutral background, strong text contrast, controlled accent.
- Typography direction: expressive headings with readable body.
- Layout direction: magazine-like sections, asymmetry with grid discipline.
- Component style: content-led cards, code snippets, annotations.
- Motion style: restrained reveal for storytelling.
- Avoid: making operational controls look like magazine decoration.
- Implementation notes: Pair editorial headings with product screenshots or real UI modules.

## 3. Linear-style SaaS

- Suitable for: issue trackers, workflow tools, B2B SaaS.
- Not suitable for: playful consumer apps.
- Visual keywords: focused, fast, keyboard-native, elegant.
- Color direction: dark or light neutral system with purple/blue accent used sparingly.
- Typography direction: compact, clear labels, strong metadata.
- Layout direction: sidebar + content, command palette, dense lists.
- Component style: thin borders, selected states, keyboard focus.
- Motion style: instant, subtle, utility-first.
- Avoid: copying brand assets; capture the operational clarity instead.
- Implementation notes: Build command input, list states, keyboard focus, and density controls.

## 4. Vercel-style Developer UI

- Suitable for: developer tools, deployment dashboards, API platforms.
- Not suitable for: non-technical consumer apps.
- Visual keywords: monochrome, precise, code-native, infrastructure.
- Color direction: black/white/neutrals with restrained semantic colors.
- Typography direction: sans plus monospace for technical metadata.
- Layout direction: docs-like clarity, cards, logs, status panels.
- Component style: thin borders, code blocks, status badges.
- Motion style: minimal feedback.
- Avoid: overusing black backgrounds without readability.
- Implementation notes: Use monospace for IDs, commands, logs, and metrics.

## 5. Apple-like Product Clarity

- Suitable for: consumer tools, device-related products, premium apps.
- Not suitable for: dense enterprise dashboards.
- Visual keywords: clear, confident, spacious, cinematic.
- Color direction: soft neutrals, large visual assets, limited accents.
- Typography direction: large confident headings, high readability.
- Layout direction: strong hero, focused sections, clear product moments.
- Component style: smooth controls, large touch targets.
- Motion style: polished transitions, scroll-driven only when meaningful.
- Avoid: copying Apple layouts without product-specific content.
- Implementation notes: Prioritize visual asset quality and typography scale.

## 6. Notion-like Calm Productivity

- Suitable for: notes, documents, knowledge bases, planning tools.
- Not suitable for: high-impact marketing pages.
- Visual keywords: calm, readable, modular, approachable.
- Color direction: light neutrals, soft semantic colors.
- Typography direction: readable body, modest headings.
- Layout direction: document-first, blocks, side navigation.
- Component style: simple blocks, inline actions, light borders.
- Motion style: almost invisible.
- Avoid: making everything too plain; add hierarchy through content structure.
- Implementation notes: Great for settings, docs, and editor interfaces.

## 7. AI-native Dark Interface

- Suitable for: AI agents, generation tools, model dashboards.
- Not suitable for: accessibility-sensitive long-form reading without contrast care.
- Visual keywords: intelligent, focused, ambient, technical.
- Color direction: deep neutral background, one luminous accent, semantic status colors.
- Typography direction: crisp labels, readable input/output areas.
- Layout direction: prompt area, result panel, history, parameters.
- Component style: layered panels, subtle borders, clear focus states.
- Motion style: generation progress, streaming output, state transitions.
- Avoid: illegible low-contrast gray text and excessive glow.
- Implementation notes: Build loading, streaming, empty, and error states first.

## 8. Glassmorphism Dashboard

- Suitable for: brand-heavy dashboards, finance demos, spatial UI.
- Not suitable for: text-heavy admin tools.
- Visual keywords: translucent, layered, ambient, polished.
- Color direction: deep or blurred background with translucent surfaces.
- Typography direction: high contrast on glass surfaces.
- Layout direction: layered cards with strong alignment.
- Component style: backdrop blur, thin borders, limited shadows.
- Motion style: subtle depth shifts.
- Avoid: poor contrast and too many transparent layers.
- Implementation notes: Always test readability over background changes.

## 9. Aurora Gradient System

- Suitable for: AI, creativity, developer launches, premium landing pages.
- Not suitable for: dense operational screens.
- Visual keywords: luminous, atmospheric, futuristic.
- Color direction: dark neutral plus controlled gradient accent.
- Typography direction: strong clean headings.
- Layout direction: hero or background accent, not every card.
- Component style: neutral components with accent highlights.
- Motion style: slow ambient movement only in non-critical areas.
- Avoid: rainbow gradients across all UI elements.
- Implementation notes: Keep gradients in background layers or hero visuals.

## 10. Bento Grid Product UI

- Suitable for: feature explanation, product overview, landing pages.
- Not suitable for: workflows requiring linear task completion.
- Visual keywords: modular, scannable, structured, modern.
- Color direction: neutral cards, varied but controlled accents.
- Typography direction: compact headings and concise copy.
- Layout direction: asymmetric grid with consistent gutters.
- Component style: feature modules with visual proof.
- Motion style: hover detail, subtle reveal.
- Avoid: identical cards with generic icons.
- Implementation notes: Each bento cell needs a specific story or product artifact.

## 11. Soft Brutalism

- Suitable for: creative tools, portfolios, cultural projects.
- Not suitable for: conservative B2B trust pages.
- Visual keywords: bold, direct, tactile, playful.
- Color direction: high contrast with limited strong accents.
- Typography direction: bold headings, simple body.
- Layout direction: strong blocks, visible structure.
- Component style: sharp or modest radii, visible borders.
- Motion style: snappy, physical.
- Avoid: messy alignment disguised as personality.
- Implementation notes: Use strict grid so bold choices still feel intentional.

## 12. High-contrast Technical UI

- Suitable for: data tools, monitoring, security, infrastructure.
- Not suitable for: soft lifestyle brands.
- Visual keywords: precise, dense, readable, operational.
- Color direction: dark or light neutrals with semantic status colors.
- Typography direction: compact sans plus monospace metadata.
- Layout direction: tables, filters, panels, charts.
- Component style: thin dividers, badges, dense controls.
- Motion style: minimal state feedback.
- Avoid: decorative dashboards that reduce scanning speed.
- Implementation notes: Prioritize table states, filters, sorting, and chart legends.

## 13. Spatial / 3D Product Interface

- Suitable for: AI, hardware, creative tools, immersive demos.
- Not suitable for: core admin workflows.
- Visual keywords: depth, presence, ambient, dimensional.
- Color direction: dark or neutral base with controlled light.
- Typography direction: foreground UI must remain crisp.
- Layout direction: 3D background or feature scene behind usable UI.
- Component style: layered panels, readable controls.
- Motion style: slow parallax or direct manipulation.
- Avoid: 3D blocking text or hurting performance.
- Implementation notes: Use Three.js or React Three Fiber only where it earns its cost.

## 14. Creator Tool Interface

- Suitable for: design tools, content generators, social media tools.
- Not suitable for: pure reporting dashboards.
- Visual keywords: productive, expressive, preview-first.
- Color direction: neutral workspace with vivid content accents.
- Typography direction: practical labels, clear control hierarchy.
- Layout direction: left controls, center canvas/preview, right properties or history.
- Component style: toolbars, swatches, segmented controls, previews.
- Motion style: direct manipulation feedback, generation progress.
- Avoid: marketing-page layout for an actual tool.
- Implementation notes: Prioritize canvas sizing, controls, presets, undo/redo, and export states.
