# Landing Page Redesign

## User Original Input

"I have a landing page, but it looks too generic. Make it more trustworthy, premium, and conversion-oriented."

## Detected Mode

Mode B: Existing UI Upgrade / Diagnosis.

## Project Type

Landing page. The page must explain value, build trust, and convert.

## UI Goal

Move from generic template to credible product story with clear CTA hierarchy.

## Key Design Problems or Assumptions

- The page likely has vague feature cards and weak proof.
- Premium feeling should come from product specificity and restraint.
- Conversion needs proof, not just visual polish.

## Recommended UI Strategy

Use Editorial Tech + Premium Minimal. Replace generic sections with product workflow proof, use real product visuals, and make one CTA dominant.

## Information Architecture

- Hero: category, value proposition, primary CTA, product proof.
- Problem: one painful user scenario.
- Workflow: how the product solves it.
- Differentiation: 3-4 specific advantages.
- Trust: testimonials, logos, metrics, security notes.
- Final CTA: clear next step.

## Visual System

- Background: clean neutral with controlled accent gradient only in hero or proof visual.
- Typography: confident headline, readable body, compact labels.
- Cards: fewer but stronger; no identical generic icon grid.
- Assets: product screenshots, annotated UI, or realistic mock data.

## Component System

Hero, proof visual, CTA group, workflow steps, bento feature cards, testimonial cards, pricing/CTA block, FAQ accordion.

## Motion Strategy

Use scroll reveal for supporting sections only. CTA hover should be immediate. Product proof can have subtle parallax, but text stays stable.

## Frontend Implementation Recommendation

Use existing stack. If unspecified: Next.js, Tailwind CSS, Framer Motion, lucide-react. Avoid adding a component library unless form/dialog complexity requires it.

## Codex-ready Prompt

```text
Redesign this landing page to feel trustworthy, premium, and conversion-oriented. Diagnose and replace generic feature-card sections with a clear product story: hero with product category and value proposition, primary CTA, visible product proof, problem section, workflow section, differentiated features, trust proof, and final CTA. Use Premium Minimal + Editorial Tech direction: restrained neutral background, strong typography hierarchy, controlled accent color, subtle borders, and realistic product visuals. Keep one primary CTA visually dominant. Add purposeful scroll reveal only for non-critical sections and respect reduced motion. Avoid generic gradient hero, vague icons, identical cards, and excessive effects. Acceptance: the first viewport communicates what the product is, who it is for, why it matters, and what users should do next.
```

## Acceptance Criteria

- Hero communicates category, value, proof, and CTA.
- Feature sections are product-specific.
- Trust elements are visible before the final CTA.
- Visual polish does not hide conversion hierarchy.
