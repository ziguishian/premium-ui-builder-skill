# Personal Portfolio

## User Original Input

"I want to build a personal portfolio website with a high-end designer/developer feel."

## Detected Mode

Mode A: New Project UI Planning.

## Project Type

Personal portfolio.

## UI Goal

Create a portfolio that feels selective, credible, and memorable without looking like a template.

## Key Design Problems or Assumptions

- The portfolio needs proof of taste and execution, not just a biography.
- Selected work should dominate over decorative effects.
- The design must support scanning by hiring managers or collaborators.

## Recommended UI Strategy

Use Editorial Tech + Premium Minimal. Focus on case-study cards, process notes, and strong typography.

## Information Architecture

- Hero: name, role, positioning, contact CTA.
- Selected work: 3-5 projects with outcomes.
- Case-study detail: problem, role, process, result.
- Skills: concise capability map.
- About: short personal context.
- Contact: email/social links.

## Visual System

- Color: warm or cool neutral base with one accent.
- Typography: editorial headline, readable body, monospace metadata for project tags.
- Layout: wide case-study grid with strong rhythm.
- Assets: real screenshots, process images, or product previews.

## Component System

Navbar, hero, project card, case-study block, skill list, timeline, contact block, footer.

## Motion Strategy

Use subtle page load and project card hover. Avoid elaborate portfolio animations that slow reading.

## Frontend Implementation Recommendation

Static Next.js or Astro, Tailwind CSS, Framer Motion if needed, optimized images.

## Codex-ready Prompt

```text
Design and implement a high-end designer/developer portfolio. Prioritize selected work and proof of execution over decoration. Structure: hero with name/role/positioning/contact CTA, selected projects, case-study summaries, skill map, about, and contact. Visual direction: Editorial Tech + Premium Minimal with strong typography, neutral palette, one accent, generous whitespace, aligned project grid, and real project visuals. Use project cards with role, year, stack, outcome, and clear hover states. Motion should be subtle and support navigation only. Responsive: project grid collapses cleanly and images keep stable aspect ratios. Avoid generic animated blobs, vague "creative" copy, and too many effects. Acceptance: within the first viewport, visitors understand who this person is, what they make, and how to view the work.
```

## Acceptance Criteria

- Work is the main visual proof.
- Typography feels intentional.
- Project cards include real metadata and outcomes.
- Mobile layout keeps case studies readable.
