## Agent skills

### Issue tracker

Track specs, decisions, and implementation issues in GitHub Issues. See `docs/agents/issue-tracker.md`.

### Triage labels

Use the five default triage labels. See `docs/agents/triage-labels.md`.

### Domain docs

Use a single root glossary and root ADR directory. See `docs/agents/domain.md`.

## Current library documentation

Use the `ctx7` CLI whenever the user asks about a library, framework, SDK, API, CLI tool, or cloud service. This includes syntax, configuration, migrations, setup, and library-specific debugging. Skip it for general programming concepts, business logic debugging, code review, refactoring, and scripts written from scratch.

1. Resolve the official library name with `npx ctx7@latest library <name> "<full user question>"` unless the user supplied a `/org/project` ID. Select the best result by name, relevance, snippet count, source reputation, and benchmark score.
2. Fetch `npx ctx7@latest docs <libraryId> "<full user question>"`. Use a versioned ID for version-specific questions.
3. If the result is insufficient, retry the docs command with `--research`.

Use at most three Context7 commands per question. Keep credentials out of queries. Run these requests outside Codex's default sandbox; after a DNS or network failure, retry outside the sandbox. On quota errors, tell the user and suggest `npx ctx7@latest login` or `CONTEXT7_API_KEY` rather than silently relying on memory.
