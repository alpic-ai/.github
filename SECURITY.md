# Security Policy

Alpic takes the security of our open source projects and cloud platform seriously. We appreciate responsible disclosure of vulnerabilities.

## Supported projects

Security reports are welcome for public repositories under [github.com/alpic-ai](https://github.com/alpic-ai), including but not limited to:

- [skybridge](https://github.com/alpic-ai/skybridge)
- [apps-sdk-template](https://github.com/alpic-ai/apps-sdk-template)
- [webmcp](https://github.com/alpic-ai/webmcp) / [webmcp-proxy](https://github.com/alpic-ai/webmcp-proxy)
- [grizzly](https://github.com/alpic-ai/grizzly), [mcp-eval](https://github.com/alpic-ai/mcp-eval), [mcp-app-conformance](https://github.com/alpic-ai/mcp-app-conformance)
- Other tooling and templates published by the Alpic org

If a repository has its own `SECURITY.md`, follow that document instead.

## Reporting a vulnerability

**Do not open a public GitHub issue for security vulnerabilities.**

Prefer one of these channels:

1. **GitHub private vulnerability reporting** (when enabled on the target repository): use *Security → Report a vulnerability* on that repo.
2. **Email**: [contact@alpic.ai](mailto:contact@alpic.ai) with subject line `[SECURITY]` and enough detail to reproduce the issue.

Please include:

- Affected repository / package / component and version if known
- Description of the vulnerability and its impact
- Steps to reproduce, or a proof of concept
- Any mitigations you already know of

## What to expect

- We will acknowledge receipt as soon as we can
- We will investigate and keep you informed of progress when practical
- Please give us reasonable time to fix and release before any public disclosure

## Scope notes

- Do not run destructive tests against production Alpic Cloud projects you do not own
- Do not access, modify, or delete data that is not yours
- Social engineering, physical attacks, and denial-of-service are out of scope for this policy

Thank you for helping keep Alpic and our users safe.
