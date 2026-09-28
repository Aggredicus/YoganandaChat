# Verifying YoganandaChat v1.0

## Verify all packaged files

Run from the release directory:

```bash
sha256sum --check SHA256SUMS
```

Expected result: every listed file reports `OK`.

## Verify the manifest

```bash
sha256sum --check manifest.json.sha256
```

## Verify the checksum list

```bash
sha256sum --check SHA256SUMS.sha256
```

## GitHub Actions

The included `.github/workflows/verify.yml` performs these checks automatically on pushes, pull requests, and manual workflow dispatches.

## Release ZIP

When downloaded from a GitHub Release, verify the ZIP from its parent directory with the companion file:

```bash
sha256sum --check YoganandaChat-v1.0.zip.sha256
```
