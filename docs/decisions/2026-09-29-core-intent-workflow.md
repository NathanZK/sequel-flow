# Core intent-driven workflow

## Context

The architecture calls for direct creation when requests are straightforward, with source relationships and deeper capabilities used only when they help.

## Choice

Put actionable repository guidance in `.github/copilot-instructions.md`. Keep `README.md` as the concise project overview and `docs/story-modes.md` as optional source-relationship guidance.

## Ruled out

- README-only guidance, which would mix Copilot behavior instructions with the project overview.
- A separate workflow document, which adds another instruction artifact without improving the user-facing overview or source-relationship reference.
- Required story modes, process stages, agents, sessions, or planning artifacts.
