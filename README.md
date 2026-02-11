# Kali Linux on KASM

This projecet is intended to build a most-complete Kali instance for KASM, which primary is used in online pentesting. Therefore, real hardware implementation (like RFID) has been removed from the instance.

The build images are based on [Kali Rolling Desktop](https://hub.docker.com/r/kasmweb/kali-rolling-desktop/).

## Available containers

Users are recommended to use those available containers

- `theflightsims/kasm-kali:latest-amd64` (for AMD64 desktop)
- `theflightsims/kasm-kali:latest-arm64v8` (for ARM64v8 desktop)

## Usage

1. Try to pull the Kali desktop image from Docker Hub

    ```bash
    # For AMD64
    docker pull theflightsims/kasm-kali:latest-amd64
    
    # For ARM64v8
    docker pull theflightsims/kasm-kali:latest-arm64v8
    ```

2. Customize the image registry, [using this document from KASM](https://www.kasmweb.com/docs/develop/how_to/building_images.html#basic-build)

![KASM Desktop Customization](https://www.kasmweb.com/docs/develop/_images/image_registration.webp)
