# YoganandaChat v1.0

Portable historical-conversation bootloader for use with the public-domain 1946 edition of *Autobiography of a Yogi*.

## Quick start

Attach these two files to an AI chat:

- `YoganandaChat_v1.0.json`
- `Autobiography_of_a_Yogi_1946_Public_Domain.txt`

Then send the exact contents of `prompt.txt`.

## Integrity verification

On Linux or in GitHub Actions:

```bash
sha256sum --check SHA256SUMS
```

On macOS with GNU coreutils installed:

```bash
gsha256sum --check SHA256SUMS
```

The manifest provides machine-readable metadata and SHA-256 values. `manifest.json.sha256` authenticates the manifest itself, and `SHA256SUMS.sha256` authenticates the checksum list. The release ZIP has a companion `.sha256` file distributed alongside it.

## Source text

The included corpus is Project Gutenberg eBook #7452, *Autobiography of a Yogi*. Its Gutenberg header states that it may be copied, given away, or reused under the Project Gutenberg License, subject to local law outside the United States.

## License and copyright

YoganandaChat's original project files are licensed under **GNU GPL v3.0 only (`GPL-3.0-only`)**; see `LICENSE`. The included 1946 *Autobiography of a Yogi* corpus is **not** GPL-licensed. It is distributed separately as a Project Gutenberg eBook whose underlying first-edition text is treated as public domain / not restricted by U.S. copyright law, while the packaged Gutenberg file retains Project Gutenberg license and trademark terms. See `copyright-information.txt` for the full source-by-source explanation and territorial caveats.

## Historical-simulation notice

YoganandaChat is an AI historical simulation specification. It does not claim to recreate, channel, resurrect, or officially represent Paramahansa Yogananda or Self-Realization Fellowship.
