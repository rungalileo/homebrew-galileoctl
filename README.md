# Homebrew Formula for galileoctl

This repository contains the Homebrew formula for `galileoctl`, the Galileo CLI tool for quick troubleshooting and log bundle collection.

## About galileoctl

`galileoctl` is a command-line interface tool that provides quick troubleshooting capabilities and log bundle collection for Galileo systems.

## Installation

Install `galileoctl` via Homebrew tap:

```bash
brew tap rungalileo/galileoctl
brew install galileoctl
```

After installation, verify it's working:

```bash
galileoctl version
```

## Formula Repository

This is the official Homebrew tap repository for `galileoctl`. The formula is automatically updated in this repository during each release of the main `galileoctl` project.

**Repository**: [rungalileo/homebrew-galileoctl](https://github.com/rungalileo/homebrew-galileoctl)  
**Main Project**: [rungalileo/galileoctl](https://github.com/rungalileo/galileoctl)

## Automatic Updates

The formula is automatically generated and committed to this repository during the release process with:
- Correct version number
- SHA256 checksums for macOS (arm64) and Linux (amd64)
- Proper download URLs from GitHub releases

The generated formula is:
- Committed to this repository in the `Formula/` directory
- Attached to each GitHub release as `Formula/galileoctl.rb`

**Note:** Do not manually edit the formula file - it will be overwritten on the next release.

## Testing the Formula Locally

You can test the formula locally before installation:

```bash
# Test the formula locally
brew install --build-from-source Formula/galileoctl.rb

# Or test with a local file path
brew install --build-from-source /path/to/galileoctl.rb
```

## Formula Details

- **Name**: `galileoctl`
- **Description**: Galileo CLI for quick troubleshooting and log bundle collection
- **Homepage**: https://github.com/rungalileo/galileoctl
- **Platforms**: macOS (arm64), Linux (amd64)
- **License**: Apache-2.0

## Troubleshooting

If you encounter issues with installation:

1. **Update Homebrew**: `brew update`
2. **Clean cache**: `brew cleanup`
3. **Reinstall**: `brew uninstall galileoctl && brew install galileoctl`

For more help, see the [main project repository](https://github.com/rungalileo/galileoctl) or open an issue.

## Contributing

This formula is automatically maintained. If you need to report issues with the Homebrew formula, please open an issue in the [main galileoctl repository](https://github.com/rungalileo/galileoctl).

