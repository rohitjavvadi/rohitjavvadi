## Hi, I'm Rohit

I build, test, and ship software with AI agents as part of my daily engineering
workflow. Lately I have been focused on open source contributions, security
review, provider workflows, and practical tooling around Codex.

I like finding the kind of bugs that actually matter: broken runtime behavior,
unsafe edge cases, cross-platform failures, missing validation, and state issues
that can quietly block users.

### What I am working on

- Open source bug hunting and focused PRs
- Codex-based development workflows
- Claude Review for Codex for second-pass review and edge-case validation
- Security and robustness reviews before shipping fixes
- TypeScript, Swift, CLI tooling, provider integrations, and automation

### Recent open source work

- [`openclaw/clawpatch`](https://github.com/openclaw/clawpatch): contributed a
  merged fix so `clawpatch fix` runs feature-aware validation instead of
  skipping important feature-specific checks.
- [`steipete/CodexBar`](https://github.com/steipete/CodexBar): reported and
  patched Host header hardening for the local `codexbar serve` command; the
  maintainer landed the fix directly on `main`.

### How I work

I use Codex to inspect codebases, reproduce issues, write focused fixes, and run
tests. I use Claude Review for Codex as an adversarial reviewer when a change
needs another pass for security, data loss, race conditions, or weird edge
cases.

The goal is simple: small PRs, real impact, clear evidence, and fixes that
maintainers can trust.

### Links

- Portfolio: [rohit.javvadi.in](https://rohit.javvadi.in)
- GitHub: [@rohitjavvadi](https://github.com/rohitjavvadi)
