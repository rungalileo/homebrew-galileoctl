# Setting up the Homebrew Tap Repository

This guide explains how to set up the `homebrew-galileoctl` repository for the first time.

## Initial Setup

1. Create the repository structure:
   ```bash
   git clone git@github.com:rungalileo/homebrew-galileoctl.git
   cd homebrew-galileoctl
   mkdir -p Formula
   ```

2. Create an initial formula file (or copy from this repository):
   ```bash
   # Copy the template from the main repo
   cp /path/to/galileoctl/Formula/galileoctl.rb Formula/galileoctl.rb
   ```

3. Commit and push:
   ```bash
   git add Formula/galileoctl.rb
   git commit -m "Initial Homebrew formula"
   git push
   ```

## Automatic Updates

After the initial setup, the release workflow in the main `galileoctl` repository will automatically:
- Generate the formula with correct version and checksums
- Commit and push it to this tap repository
- No manual intervention needed!

## Repository Structure

The tap repository should have this structure:
```
homebrew-galileoctl/
└── Formula/
    └── galileoctl.rb
```

## Testing

Users can then install via:
```bash
brew tap rungalileo/galileoctl
brew install galileoctl
```

