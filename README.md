# Autono Homebrew Tap

Homebrew tap for CLI tools published by [Autono](https://autono.co).

## Install

```bash
brew install autonoco/tap/<name>
```

Or tap first, then install by short name:

```bash
brew tap autonoco/tap
brew install <name>
```

## Tools

| Name | Description | Source |
|------|-------------|--------|
| [buttons](https://github.com/autonoco/buttons) | Deterministic workflow engine for AI agents | [autonoco/buttons](https://github.com/autonoco/buttons) |

## Updating

```bash
brew upgrade <name>
```

## How this tap is maintained

Formula files under `Casks/` are auto-generated and pushed by [goreleaser](https://goreleaser.com/) on every release of the source project. Do not hand-edit `Casks/*.rb` — changes will be overwritten by the next release.

## License

Each tool has its own license (see the source repo linked above). This tap's packaging metadata is provided as-is.
