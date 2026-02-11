# Kali Linux on KASM

This projecet is intended to build a most-complete Kali instance for KASM, which primary is used in online pentesting. Therefore, real hardware implementation (like RFID) has been removed from the instance.

The build images are based on [Kali Rolling Desktop](https://hub.docker.com/r/kasmweb/kali-rolling-desktop/).

## Available containers

Users are recommended to use those available containers

- `theflightsims/kasm-kali-rolling:latest-amd64` (for AMD64 desktop)
- `theflightsims/kasm-kali-rolling:latest-arm64v8` (for ARM64v8 desktop)

## Usage

```bash
# For AMD64 computers
docker pull theflightsims/kasm-kali-rolling:latest-amd64

# For ARM64v8 desktop
docker pull theflightsims/kasm-kali-rolling:latest-arm64v8
```
