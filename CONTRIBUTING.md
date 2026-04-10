# Contributing to Awesome Design MD

Thanks for contributing.

This repository is a curated collection of mobile `DESIGN.md` files for AI-generated UI. Each file captures a complete visual language in a format any AI agent can read.

## How to Contribute

### Improve an Existing DESIGN.md

If you notice issues with an existing file:

1. **Open an issue first** to describe what you'd like to change and get feedback from maintainers
2. Open the target file under `design-md/`
3. Review the current structure and preserve the section format
4. Fix incorrect tokens, weak descriptions, missing component guidance, or unclear usage rules
5. If your changes affect colors, typography, spacing, surfaces, or components, update or add the paired `preview.html` and `preview-dark.html` examples for that design style
6. Open a PR with a short before/after rationale

## Preview Files

Preview files are used to visually validate a design style outside the Markdown spec.

- `preview.html`: light-mode preview of tokens and common UI components
- `preview-dark.html`: dark-mode preview of the same design system
- If a design style does not yet include previews and your change materially affects visual output, add them as part of the contribution
- Keep preview files aligned with the corresponding `DESIGN.md`

We cannot accept low-context `DESIGN.md` pull requests. Changes need to preserve quality, consistency, and the mobile-first intent of the collection.

## License

By contributing, you agree your contributions are provided under the repository license terms.
