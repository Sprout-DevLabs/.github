# 🌱 Sprout DevLabs

Developer tools that make software projects easier to explore, understand, and build.

### [Sprout](https://github.com/Sprout-DevLabs/sprout): map your codebase, for you and your AI agent

[![Release](https://img.shields.io/github/v/release/Sprout-DevLabs/sprout)](https://github.com/Sprout-DevLabs/sprout/releases/latest)
[![Docs](https://img.shields.io/badge/docs-sprout--web-blue)](https://sprout-devlabs.github.io/sprout-web/docs/)
[![Good first issues](https://img.shields.io/github/issues/Sprout-DevLabs/sprout/good%20first%20issue?label=good%20first%20issues&color=7057ff)](https://github.com/Sprout-DevLabs/sprout/issues?q=is%3Aissue+is%3Aopen+label%3A%22good+first+issue%22)

One small binary, no dependencies. Sprout reads a project the way a developer
does: it shows the tree without the noise, follows the imports between files,
and tells you what a change could break. It also runs as an MCP server, so
coding agents get the same map.

```sh
brew install sprout-devlabs/tap/sprout

sprout tour                        # what the project is, its layout, what to read first
sprout impact --diff main...HEAD   # what this branch could break, and the tests to run
sprout context src/auth.ts         # what to know before editing a file
sprout --ai | pbcopy               # a token-budgeted map to paste into any chat
```

**New in [v0.4.0](https://github.com/Sprout-DevLabs/sprout/releases/tag/v0.4.0):**
`sprout tour`, a guided first look at any codebase.

| Repo | |
|---|---|
| [sprout](https://github.com/Sprout-DevLabs/sprout) | The CLI and MCP server (Go, standard library only) |
| [sprout-web](https://github.com/Sprout-DevLabs/sprout-web) | Website and docs: [sprout-devlabs.github.io/sprout-web](https://sprout-devlabs.github.io/sprout-web/) |
| [homebrew-tap](https://github.com/Sprout-DevLabs/homebrew-tap) | `brew install sprout-devlabs/tap/sprout` |
| [scoop-bucket](https://github.com/Sprout-DevLabs/scoop-bucket) | `scoop install sprout` on Windows |

New to open source? Issues labelled
[`good first issue`](https://github.com/Sprout-DevLabs/sprout/issues?q=is%3Aissue+is%3Aopen+label%3A%22good+first+issue%22)
say which files to look at and how to test, and
[CONTRIBUTING.md](https://github.com/Sprout-DevLabs/sprout/blob/main/CONTRIBUTING.md)
walks through your first pull request. Questions are welcome in
[Discussions](https://github.com/Sprout-DevLabs/sprout/discussions).
