# OpenShell Docker

[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](LICENSE)
[![Docker Image](https://img.shields.io/badge/ghcr.io%2Ftecknix%2Frailway-openshell%3Alatest-blue)](https://github.com/TeckniX/openshell-railway)


[![Deploy on Railway](https://railway.com/button.svg)](https://railway.com/deploy/stX6Av?referralCode=HhsRaZ&utm_medium=integration&utm_source=template&utm_campaign=generic)

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
