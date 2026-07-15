# Setup Binaryen

## Example

```yaml
- uses: BlackAsLight/setup-binaryen@v2.1.0
  env:
    GH_TOKEN: ${{ github.token }}
  with:
    # Version can be one of:
    # - "latest" (default): Download the latest Github Release binaries.
    # - "canary": Build Binaryen from the latest source.
    # - A specific release tag (for example, "version_124"): Download that release's binaries.
    version: version_124

    # Whether to save time by using actions/cache. Defaults to true.
    cache: true
```
