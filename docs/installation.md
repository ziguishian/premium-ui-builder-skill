# Installation

`premium-ui-builder-skill` is a documentation-oriented Codex Skill. It is not an npm package, framework, Figma plugin, or code generator.

## Use as a Reference Repository

Clone or copy this repository into any project where you want UI planning support. Read `SKILL.md` first, then load relevant files from `references/`, `examples/`, and `evals/` as needed.

## Copy Into a Codex Skill Directory

To use it as a Codex Skill, copy the repository folder into your Codex skills directory and keep the folder name aligned with the Skill name:

```text
premium-ui-builder-skill/
```

The required Skill entry file is:

```text
SKILL.md
```

## Use Before UI Implementation

Use this Skill before asking an AI coding agent to implement a UI. The recommended flow is:

1. Describe the product or UI problem.
2. Ask for a premium UI plan or upgrade diagnosis.
3. Review the information architecture and visual system.
4. Use the generated Codex-ready prompt for implementation.

## Use for UI Redesign Review

For existing pages, provide a screenshot, codebase, URL, or description. The Skill should enter Mode B and produce a diagnosis before suggesting visual changes.

## No Build Step

There is no package install, build step, or runtime. This repository intentionally avoids unnecessary scripts and frontend scaffolding.
