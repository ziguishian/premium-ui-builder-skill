# Information Architecture Guide

Information architecture decides what the UI says first, what it asks users to do, and what stays secondary.

## Core Questions

- What is the primary user goal?
- What secondary goals support it?
- What must users understand before they act?
- What can be hidden, delayed, or moved to settings?
- What states must exist when there is no data, loading, or an error?

## Page Hierarchy

Use a clear hierarchy:

1. Context: Where am I and what is this?
2. Primary value: Why does this matter?
3. Primary action: What should I do next?
4. Supporting proof or controls: What helps me decide or act?
5. Secondary paths: What else can I explore?

## Section Sequencing

Landing pages:

1. Hero with product category, value proposition, primary CTA, and product proof.
2. Problem or use-case section.
3. Product workflow or feature proof.
4. Differentiation.
5. Social proof or trust.
6. Pricing or final CTA.

SaaS dashboards:

1. Top-level status.
2. Primary metrics.
3. Main workflow entry points.
4. Recent activity or alerts.
5. Deeper analysis.

AI generation tools:

1. Prompt / input area.
2. Model and generation controls.
3. Result preview.
4. History and variants.
5. Export / share / refine actions.

Admin dashboards:

1. Filters and scope.
2. Key operational status.
3. Main table or queue.
4. Detail panel.
5. Bulk actions and logs.

Portfolio pages:

1. Identity and role.
2. Selected work.
3. Case-study proof.
4. Skills and approach.
5. Contact.

Mobile screens:

1. Current context.
2. Primary task.
3. One clear CTA or next action.
4. Supporting content.
5. Bottom navigation if needed.

## CTA Hierarchy

- Primary CTA: the most important action; strongest contrast.
- Secondary CTA: useful but quieter; outline or ghost style.
- Tertiary action: text or icon action; low emphasis.

Never make three CTAs look equally important.

## Navigation Patterns

- Landing page: top nav with 3-5 anchors and primary CTA.
- SaaS app: sidebar for modules, topbar for search/account/context.
- AI tool: workspace navigation plus history.
- Mobile app: bottom tabs for main areas, sheet or modal for task detail.
- Documentation site: left tree, search, content body, right on-page nav.

## Form Hierarchy

- Group fields by user intent.
- Put required fields before optional settings.
- Use progressive disclosure for advanced controls.
- Show validation near the field.
- Keep the submit action visible and specific.

## Dashboard Hierarchy

- Summary first, details second.
- Filters should control visible scope without dominating the page.
- Tables need sorting, empty states, loading states, and row actions.
- Charts must answer a question, not merely decorate the screen.

## Empty / Loading / Error States

Plan these as real content:

- Empty state: explain what is missing and offer the next action.
- Loading state: reserve layout space and show progress when possible.
- Error state: explain what happened, what can be retried, and what data is preserved.
