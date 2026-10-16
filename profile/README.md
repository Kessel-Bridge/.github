# Welcome to Kessel-Bridge

Kadena AI ecosystem tools and releases.

## What We Build

AI-focused development (community-based effort) for the Kadena Chainweb blockchain.

## Repositories of Interest

_No public repositories yet._

## In Development

Sneak preview — what we're working on next:

- `kessel-Kore` — Its A EVM SVM Bridge !!
- `kessel-ui-tui` — The is the window into Kessel !!
- `Parsec` — Its A Fast Route instand Finality !!
- `parsec-ui-tui-` — This Is the window into Parsec !!

## Download Builds

Binaries for all projects: **https://github.com/Kessel-Bridge/releases**

### Homebrew

```bash
brew trust kessel-bridge/tap
brew tap kessel-bridge/tap
brew install <formula>
```

## Getting Help

Open an issue in the relevant repository.

## For Developers: Bootstrap Your Own Org

Running your own org and want the same structure? The tool we use to set this up lives in our shared tooling org:

**[homebrew-tap-app](https://github.com/kore-kda-community/homebrew-tap-app)** — a single script that scaffolds:

- **`.github`** — org profile README + shared community health files
- **`releases`** — central hub where every tagged build lands
- **`homebrew-tap`** — package manager formulae, auto-bumped by CI
- **Source repos** — one per project, with branch layout for project work
- **Release workflow** — GoReleaser config + GitHub Actions; tag → build → publish → formula bump, fully automated
- **Release schedule** — driven by tags, so `git tag vX.Y.Z && git push --tags` is the whole workflow

Clone it, point it at your org, run `./run.sh`. Safe to re-run.