# Homebrew Formula for galileoctl

This directory contains a reference copy of the Homebrew formula for `galileoctl`. 

**Note:** The actual Homebrew formula is maintained in the [homebrew-galileoctl](https://github.com/rungalileo/homebrew-galileoctl) repository and is automatically updated with each release.

## Installation

Install via Homebrew tap:

```bash
brew tap rungalileo/galileoctl
brew install galileoctl
```

## Formula Repository

The formula is automatically updated in the [rungalileo/homebrew-galileoctl](https://github.com/rungalileo/homebrew-galileoctl) repository during each release.

## Updating the Formula

The formula is automatically generated and committed to this repository during the release process with:
- Correct version number
- SHA256 checksums for macOS (arm64) and Linux (amd64)
- Proper download URLs

The generated formula is:
- Committed to this repository in the `Formula/` directory
- Attached to each GitHub release as `Formula/galileoctl.rb`

## Testing the Formula Locally

```bash
# Test the formula locally
brew install --build-from-source Formula/galileoctl.rb

# Or test with a local file
brew install --build-from-source /path/to/galileoctl.rb
```

## Formula Details

- **Name**: `galileoctl`
- **Description**: Galileo CLI for quick troubleshooting and log bundle collection
- **Homepage**: https://github.com/rungalileo/galileoctl
- **Platforms**: macOS (arm64), Linux (amd64)
- **License**: Apache-2.0

