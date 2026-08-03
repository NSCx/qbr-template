# Repository-specific Copilot instructions

- Prefer non-attachment verification for UI checks in this repository.
- Do **not** use `playwright-browser_take_screenshot` unless a human explicitly requests an image.
- Use `playwright-browser_evaluate`, `playwright-browser_snapshot`, and textual DOM assertions to validate visual/layout changes.
