# Cosmos SDK Frozen Versions

This repository contains multiple frozen versions of cosmos-sdk as separate Go modules.

## Available Versions

| Directory | Based on Version | Module Path |
|-----------|------------------|-------------|
| v018frozen | v0.18.0 | `github.com/jonathansumner/cosmos-sdk/v018frozen` |
| v0181frozen | v0.18.1 | `github.com/jonathansumner/cosmos-sdk/v0181frozen` |
| v0182frozen | v0.18.2 | `github.com/jonathansumner/cosmos-sdk/v0182frozen` |
| v0184frozen | v0.18.4 | `github.com/jonathansumner/cosmos-sdk/v0184frozen` |
| v0193frozen | v0.19.3 | `github.com/jonathansumner/cosmos-sdk/v0193frozen` |
| v0194frozen | v0.19.4 | `github.com/jonathansumner/cosmos-sdk/v0194frozen` |
| v0200frozen | v0.20.0 | `github.com/jonathansumner/cosmos-sdk/v0200frozen` |

## Usage

In your `go.mod`:
```go
require (
    github.com/jonathansumner/cosmos-sdk/v018frozen v0.0.0-<commit-hash>
    // or use a specific branch/tag
)
```

Then:
```bash
go get github.com/jonathansumner/cosmos-sdk/v018frozen@multi-version-frozen
```

Each subdirectory is a complete, independent module with its own dependencies.
