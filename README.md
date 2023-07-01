# setup-sqlc

This [action](https://docs.github.com/actions) downloads and installs [sqlc](https://sqlc.dev).

## Usage

```yaml
steps:
# Ensure sqlc is installed
- uses: sqlc-dev/setup-sqlc@v2
  with:
    sqlc-version: '1.18.0'
# Print out the current version
- run: sqlc version
```
