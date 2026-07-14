# Setup Binaryen

## Example
```yaml
- uses: BlackAsLight/setup-binaryen@v2.0.0
  env:
    GH_TOKEN: ${{ github.token }}
  with:
    # Version can be one of:
    # - "canary": Clones the Binaryen repo and builds from source.
    # - "latest": (Default) Downloads the latest release binaries from GitHub Releases.
    # - A specific release tag (e.g., "version_124"): downloads that exact version's binaries.
    version: version_124
```
