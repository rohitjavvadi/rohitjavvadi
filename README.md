# Rohit Javvadi

I build developer tools, macOS utilities, and agentic coding workflows.

Recently I have been contributing to the OpenClaw/Codex ecosystem, especially code review automation, route mapping, validation, provider diagnostics, and small reliability fixes that maintainers can merge quickly.

## Open Source Signal

- [`openclaw/clawpatch`](https://github.com/openclaw/clawpatch): 16 merged PRs.
  Contributions include atomic review locking, feature-aware validation, Node/Express/Fastify/Hono route mapping, Django, Flask, Rails, and Laravel route mapping, provider diagnostics, and evidence-stability fixes.
- [`steipete/CodexBar`](https://github.com/steipete/CodexBar): 3 merged PRs.
  Fixed LLM Proxy reset-time handling, removed obsolete peak-hour UI, and improved missing CLI guidance.
- [`Claude Review for Codex`](https://github.com/rohitjavvadi/claude-review-for-codex): creator/maintainer.
  A local Codex plugin where Claude Code performs read-only reviews while Codex remains the only writer and fixer.
- [`ClipLy`](https://github.com/rohitjavvadi/ClipLy): creator.
  A lightweight macOS clipboard history app for text, images, and files with local SQLite storage, configurable retention, and a Homebrew cask.

## Selected Contributions

### `openclaw/clawpatch`

- [#13](https://github.com/openclaw/clawpatch/pull/13): made review feature locks atomic.
- [#24](https://github.com/openclaw/clawpatch/pull/24): added feature validation during fixes.
- [#47](https://github.com/openclaw/clawpatch/pull/47): added Node server route mapping for Express, Fastify, and Hono.
- [#52](https://github.com/openclaw/clawpatch/pull/52): recognized aliased Express routers.
- [#54](https://github.com/openclaw/clawpatch/pull/54): added Django route mapping.
- [#70](https://github.com/openclaw/clawpatch/pull/70): handled Express Router imports after block comment banners.
- [#72](https://github.com/openclaw/clawpatch/pull/72): improved malformed JSON diagnostics for the opencode provider.
- [#77](https://github.com/openclaw/clawpatch/pull/77): mapped Fastify plugin callback routes.
- [#78](https://github.com/openclaw/clawpatch/pull/78): supported Fastify method arrays.
- [#79](https://github.com/openclaw/clawpatch/pull/79): mapped Laravel group prefixes.
- [#97](https://github.com/openclaw/clawpatch/pull/97): stabilized fallback finding evidence signatures.
- [#98](https://github.com/openclaw/clawpatch/pull/98): preserved Node mounted route prefixes.
- [#99](https://github.com/openclaw/clawpatch/pull/99): classified stdout-only provider failures.
- [#100](https://github.com/openclaw/clawpatch/pull/100): mapped Flask blueprint prefixes.
- [#102](https://github.com/openclaw/clawpatch/pull/102): mapped literal Rails routes.
- [#103](https://github.com/openclaw/clawpatch/pull/103): preserved Django include route prefixes.

### `steipete/CodexBar`

- [#1022](https://github.com/steipete/CodexBar/pull/1022): fixed LLM Proxy fractional reset times.
- [#1025](https://github.com/steipete/CodexBar/pull/1025): removed obsolete peak-hours indicator.
- [#1030](https://github.com/steipete/CodexBar/pull/1030): clarified missing CLI guidance.

## Focus

- Agentic coding tools
- Code review automation
- macOS menu bar apps
- CLI workflows
- Security, robustness, and edge-case testing
- TypeScript, Swift, JavaScript, and Python

## Links

- Portfolio: [rohit.javvadi.in](https://rohit.javvadi.in)
- GitHub: [@rohitjavvadi](https://github.com/rohitjavvadi)
- X: [@rohitj997](https://x.com/rohitj997)
