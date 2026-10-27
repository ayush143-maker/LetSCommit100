# Small-commit checklist

Use this before marking an experiment complete.

- [ ] The change solves one clearly stated problem.
- [ ] The file opens in a modern browser without a build step, where practical.
- [ ] Inputs have labels or accessible names.
- [ ] Buttons have visible focus states.
- [ ] Empty and invalid input cases are considered.
- [ ] User-provided text is inserted as text, not interpreted as HTML.
- [ ] Any browser storage behavior is documented.
- [ ] External network requests and dependencies are avoided unless needed.
- [ ] The commit message describes the actual change.
- [ ] The README reflects any new tool or limitation.

## Suggested message patterns

- `feat: add ...` for a new capability.
- `fix: handle ...` for a bug fix.
- `docs: explain ...` for documentation.
- `test: cover ...` for test improvements.
- `refactor: simplify ...` for behavior-preserving cleanup.

A small commit should still be a real, reviewable improvement. Do not create empty commits just to increase a number.