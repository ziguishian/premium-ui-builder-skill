# Contribution Guide

Contributions should make the Skill more useful for real AI Coding and Vibe Coding workflows.

## Ways to Contribute

- Add new examples for common product types.
- Add new visual styles to `references/visual-style-library.md`.
- Improve the diagnosis rubric.
- Add component patterns to `references/component-system-guide.md`.
- Improve motion guidelines.
- Add frontend implementation notes for additional stacks.
- Submit eval cases for vague, realistic, or difficult UI requests.
- Improve multilingual README consistency.

## Content Standards

Good contributions should:

- Be concrete and implementation-ready.
- Explain why a design choice exists.
- Avoid vague aesthetic language.
- Avoid trend stacking.
- Include real states such as loading, empty, error, hover, focus, disabled, and selected.
- Consider responsive behavior.
- Consider accessibility.

## Adding Examples

Each example should include:

- User original input
- Detected mode
- Project type
- UI goal
- Key design problems or assumptions
- Recommended UI strategy
- Information architecture
- Visual system
- Component system
- Motion strategy
- Frontend implementation recommendation
- Codex-ready prompt
- Acceptance criteria

## Adding Visual Styles

Each style should include:

- Suitable for
- Not suitable for
- Visual keywords
- Color direction
- Typography direction
- Layout direction
- Component style
- Motion style
- What to avoid
- Implementation notes

## Adding Eval Cases

Each eval case should include:

- Input
- Expected detected mode
- Expected output focus
- Common mistakes
- Recommended scoring focus

## Consistency Check Before PR

Before opening a PR:

- Confirm `SKILL.md` still describes the Skill accurately.
- Confirm README files remain semantically aligned.
- Confirm new advice is not just decoration.
- Confirm examples include implementation-ready prompts.
- Confirm no unnecessary scripts, package files, or frontend app files were added.
