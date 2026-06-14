# Rohit Javvadi

AI engineer building Codex workflows, developer tools, browser automation reliability, macOS utilities, and practical AI systems.

Creator of [`Claude Review for Codex`](https://github.com/rohitjavvadi/claude-review-for-codex), a local Codex plugin that gives Codex a read-only Claude Code reviewer and an opt-in disposable-worktree implementation flow while Codex stays the writer, tester, reviewer, and merge gate.

I work close to agentic coding tools: browser MCP runtime behavior, PR review automation, OpenAI API demos, route mapping, provider diagnostics, validation safety, and developer workflows that turn rough ideas into working software.

## Current Signal

- **30 merged PRs** across OpenClaw, openclaw/clawpatch, and steipete/CodexBar.
- **26 merged OpenClaw ecosystem PRs** across `openclaw/openclaw` and `openclaw/clawpatch`.
- Recent contributions landed in public developer-tooling repos including `openclaw/openclaw` with 378k+ stars, `steipete/CodexBar` with 14k+ stars, and `openclaw/clawpatch`.
- **8 merged PRs in `openclaw/openclaw`**, including CLI numeric-option validation, SecretRef profile auth handling, Chrome MCP browser-session lifecycle fixes, plugin install compatibility, model-auth status, Memory Palace report-card navigation, and telemetry watchdog behavior.
- **18 merged PRs in `openclaw/clawpatch`**, including validation command quoting, route mapping, Python runtime prompt metadata, provider diagnostics, review locking, validation, and evidence stability.
- **4 merged PRs in `steipete/CodexBar`**, covering OpenAI Admin usage pagination, LLM Proxy reset-time handling, missing CLI guidance, and stale UI cleanup.
- [`Claude Review for Codex`](https://github.com/rohitjavvadi/claude-review-for-codex): creator/maintainer of a Codex plugin for read-only Claude Code reviews and supervised disposable-worktree implementation.

## Recent Open Source Work

### `openclaw/openclaw`

- [#92490](https://github.com/openclaw/openclaw/pull/92490): validated CLI numeric options so invalid canvas inputs fail clearly before runtime work begins.
- [#92483](https://github.com/openclaw/openclaw/pull/92483): validated CLI numeric option ranges for matrix commands.
- [#90686](https://github.com/openclaw/openclaw/pull/90686): honored profile auth for SecretRef model entries.
- [#88305](https://github.com/openclaw/openclaw/pull/88305): isolated Chrome MCP pending attach aborts so one cancelled caller does not fail unrelated callers sharing the same browser session attach.
- [#87477](https://github.com/openclaw/openclaw/pull/87477): rejected incompatible package plugin API installs early.
- [#86378](https://github.com/openclaw/openclaw/pull/86378): showed OAuth delegation markers correctly in `models status`.
- [#85886](https://github.com/openclaw/openclaw/pull/85886): disabled Chrome DevTools MCP telemetry watchdog processes by default.
- [#85144](https://github.com/openclaw/openclaw/pull/85144): opened Memory Palace report cards through the existing wiki preview flow.

### `openclaw/clawpatch`

- [#111](https://github.com/openclaw/clawpatch/pull/111): quoted mapper-generated validation command arguments.
- [#109](https://github.com/openclaw/clawpatch/pull/109): respected Python runtime syntax metadata in prompts.
- Route mapping work across Node, Express, Fastify, Hono, Django, Flask, Rails, and Laravel.
- Provider diagnostics, atomic review locks, feature validation, and evidence-stability fixes.

### `steipete/CodexBar`

- [#1465](https://github.com/steipete/CodexBar/pull/1465): fixed OpenAI Admin usage pagination.
- [#1030](https://github.com/steipete/CodexBar/pull/1030): clarified missing CLI guidance.
- [#1025](https://github.com/steipete/CodexBar/pull/1025): removed obsolete peak-hours UI.
- [#1022](https://github.com/steipete/CodexBar/pull/1022): fixed LLM Proxy fractional reset times.

## Projects

- [`Claude Review for Codex`](https://github.com/rohitjavvadi/claude-review-for-codex): Codex plugin where Claude Code performs read-only reviews while Codex remains the writer/fixer, with supervised implementation in disposable worktrees.
- [`WorkTape`](https://worktape.javvadi.in/): OpenAI x Outskill MVP that turns workflow screen recordings into structured software specs and internal tools using Codex and the OpenAI Responses API.
- [`ClipLy`](https://github.com/rohitjavvadi/ClipLy): lightweight macOS clipboard history app with local SQLite storage and Homebrew install support.
- [`QuickTranscript`](https://github.com/rohitjavvadi/quicktranscript): macOS menu bar app for local meeting transcription with MLX Whisper.

## What I Like Building

- Codex and agentic coding workflows
- Developer experience tools and demos
- Browser automation and MCP reliability
- Code review automation
- CLI and macOS utilities
- TypeScript, Swift, JavaScript, Python

## Links

- Portfolio: [rohitjavvadi.ai](https://rohitjavvadi.ai)
- Email: [rohit@javvadi.in](mailto:rohit@javvadi.in)
- X: [@rohitj997](https://x.com/rohitj997)
