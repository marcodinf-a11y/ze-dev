# Issue tracker: GitHub

Use GitHub Issues in `marcodinf-a11y/ze-dev` through `gh` for specs and tickets. Pass `--repo marcodinf-a11y/ze-dev` until this workspace has a usable Git remote.

## Operations

- Create, read, list, comment on, label, and close issues with `gh issue`.
- Use GitHub sub-issues for parent and child work; if unavailable, link the parent in the child body.
- Keep “PRs as a request surface” set to no.

## Wayfinding

- The map is one issue labelled `wayfinder:map`.
- Each decision is a child issue labelled `wayfinder:research`, `wayfinder:prototype`, `wayfinder:grilling`, or `wayfinder:task`.
- Use native issue dependencies for blocking when available; otherwise record `Blocked by: #...` in the child.
- The frontier is the map’s open, unassigned children with no open blockers.
- Claim by assigning the issue to yourself. Resolve with a comment, close it, and add a short linked pointer to the map.

The [studio simulation map](https://github.com/marcodinf-a11y/ze-dev/issues/1) is canonical. Files under `.scratch/studio-simulation/` are the local planning archive and research assets.
