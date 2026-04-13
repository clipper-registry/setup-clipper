# setup-clipper

GitHub Action to install the [Clipper](https://clipper.dev) CLI.

## Usage

```yaml
- uses: clipper-registry/setup-clipper@v1
- run: clipper pull clipper.dev/myorg/myimage:latest
```

### Pin a version

```yaml
- uses: clipper-registry/setup-clipper@v1
  with:
    version: v0.3.0
```

## Inputs

| Input | Description | Default |
|-------|-------------|---------|
| `version` | Clipper version to install (e.g. `v0.3.0`) | `latest` |
