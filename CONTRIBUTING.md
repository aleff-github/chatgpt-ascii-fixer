# Contributing

Thanks for taking the time to contribute.

## What to contribute

- New replacement rules for characters that commonly break ASCII-only tooling
- UX improvements (accessibility, keyboard shortcuts, clearer diagnostics)
- Documentation improvements
- Bug fixes

## Development setup

There is no build step.

1. Clone the repo
2. Open `index.html` in a browser

## Guidelines

- Keep the project dependency-free (plain HTML/CSS/JS).
- Prefer conservative replacements. The purpose is ASCII safety.
- Avoid "smart" behavior that changes meaning (e.g., converting mathematical symbols into ambiguous text).
- Ensure the app works offline.
- Keep docs and templates in simple ASCII when possible.

## Adding a replacement rule

1. Paste your problematic text into the app.
2. Find the character in Diagnostics (note the codepoint `U+....`).
3. Add it to the `REPLACEMENTS` map (or to `LIGATURES` / invisibles if appropriate).
4. Include an example in your PR description.

## Pull requests

- Keep PRs focused
- Update `CHANGELOG.md` for user-visible changes
- Make sure GitHub Pages still deploys (workflow should stay green)
