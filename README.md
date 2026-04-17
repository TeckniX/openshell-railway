# OpenShell Docker

[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](LICENSE)
[![Docker Image](https://img.shields.io/badge/ghcr.io-NVIDIA%2FOpenShell-blue)](https://github.com/NVIDIA/OpenShell)

[![Deploy on Railway](https://railway.com/button.svg)](https://railway.com/deploy/nvidia-openshell)

Docker image for [NVIDIA OpenShell](https://github.com/NVIDIA/OpenShell) — the safe, private runtime for autonomous AI agents.

## Quick Install

### Docker

```bash
docker run -it ghcr.io/nemochief/railway-openshell:latest
```

### From Source

```bash
docker build -t openshell .
```

## Installation Options

The install script supports these environment variables:

| Variable | Default | Description |
|----------|---------|-------------|
| `OPENSHELL_VERSION` | `latest` | Release tag to install |
| `OPENSHELL_INSTALL_DIR` | `~/.local/bin` | Installation directory |

### Examples

```bash
# Install latest release
curl -LsSf https://raw.githubusercontent.com/NVIDIA/OpenShell/main/install.sh | sh

# Install specific version
OPENSHELL_VERSION=v0.0.31 sh install.sh

# Install to custom directory
OPENSHELL_INSTALL_DIR=/usr/local/bin sh install.sh
```

## Supported Platforms

| Architecture | OS | Status |
|--------------|-----|--------|
| x86_64 | Linux (musl) | ✓ |
| aarch64 | Linux (musl) | ✓ |
| aarch64 | macOS | ✓ |

## License

Apache 2.0 — see [LICENSE](LICENSE) and [NVIDIA/OpenShell](https://github.com/NVIDIA/OpenShell).
