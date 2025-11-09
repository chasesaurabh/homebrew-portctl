
# Homebrew Tap: portctl

This repository provides a Homebrew tap for installing [`portctl`](https://github.com/chasesaurabh/portctl), a tool to find and free processes binding a TCP port.

## Formula

The tap includes the formula for `portctl` supporting:
- **macOS** (Intel and ARM)
- **Linux** (Intel and ARM)

## Installation

Add this tap and install `portctl` using Homebrew:

```sh
brew tap chasesaurabh/portctl
brew install portctl
```

## Usage

After installation, you can use `portctl` to find and free processes binding to a TCP port. For example:

```sh
portctl 8080
```

See the [portctl documentation](https://github.com/chasesaurabh/portctl) for more details and advanced usage.

## Links
- [portctl main repository](https://github.com/chasesaurabh/portctl)
- [Releases & binaries](https://github.com/chasesaurabh/portctl/releases)
