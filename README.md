# OpenShell Docker

[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](LICENSE)
[![Docker Image](https://img.shields.io/badge/ghcr.io-TeckniX%2FRailway-OpenShell-blue)](https://github.com/TeckniX/openshell-railway)

[![Deploy on Railway](https://railway.com/button.svg)](https://railway.com/deploy/nvidia-openshell)

Based on the binary for [NVIDIA OpenShell](https://github.com/NVIDIA/OpenShell) — the safe, private runtime for autonomous AI agents.

## Quick Install

### Docker

```bash
docker run -it ghcr.io/tecknix/railway-openshell:latest
```

### From Source

```bash
docker build -t railway-openshell .
```

## Supported Platforms

| Architecture | OS | Status |
|--------------|-----|--------|
| x86_64 | Linux (musl) | ✓ |
| aarch64 | Linux (musl) | ✓ |
| aarch64 | macOS | ✓ |

## License

Apache 2.0 — see [LICENSE](LICENSE) and [NVIDIA/OpenShell](https://github.com/NVIDIA/OpenShell).
