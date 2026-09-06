# Contributing

Thanks for helping improve the ayaan.lol project.

## Before you start

Read the [README](README.md), then inspect the live project at [ayaan.lol](https://ayaan.lol). Open an issue first for changes that affect the project direction, content structure, or visual language.

## Issue reports

Use the repository issue form for broken links, rendering defects, accessibility problems, and preview mismatches. Include:

- The page or section where the problem appears.
- The browser and viewport size.
- Steps to reproduce the problem.
- Expected and observed behavior.
- A screenshot or short recording for visual problems.

## Pull requests

Keep pull requests small and focused. A good pull request explains:

- What changed.
- Why the change belongs in the project.
- How you tested the change.
- Which screenshots show the result, when the change affects visuals.

Use clear commit messages. Prefer one of these prefixes:

```text
feat: add a new visual pattern
fix: correct a broken interaction
docs: improve the project guide
chore: refresh a repository asset
```

## Visual changes

Preserve the project’s design direction:

- Use the existing palette and type system.
- Keep motion purposeful and test reduced-motion behavior.
- Avoid browser chrome, debug overlays, and temporary tooling in committed previews.
- Provide before and after screenshots when the change affects layout, interaction, or animation.

## Preview asset

The README uses `preview.png`. Replace it when the first viewport changes. Keep the image focused on the live product and verify the image renders from the repository’s default branch.

## Review checklist

Before opening a pull request:

- Confirm links resolve.
- Confirm the README renders correctly on GitHub.
- Confirm new assets use stable paths and descriptive names.
- Confirm no generated files or local debug output slipped into the change.
- Confirm the working tree contains only intended changes.
