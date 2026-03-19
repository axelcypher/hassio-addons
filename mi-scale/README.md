[![version](https://img.shields.io/github/v/release/hassio-addons/hassio-addons)](../../releases)
[![ha_badge](https://img.shields.io/badge/Home%20Assistant-Add%20On-blue.svg)](https://www.home-assistant.io/)

# Home Assistant Add-on: Xiaomi Mi Scale

[aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[armv6-shield]: https://img.shields.io/badge/armv6-yes-green.svg
[armv7-shield]: https://img.shields.io/badge/armv7-yes-green.svg
[i386-shield]: https://img.shields.io/badge/i386-yes-green.svg
![aarch64-shield]
![amd64-shield]
![armv6-shield]
![armv7-shield]
![i386-shield]

Reads weight measurements from Xiaomi Body Scales via Bluetooth. See [Documentation](./DOCS.md) for full setup and configuration.

## Installation
Add your own fork URL in Home Assistant (for example `https://github.com/axelcypher/hassio-addons`) and install the **Xiaomi Mi Scale** add-on from there.

## Image build & publish
This repository includes a GitHub Actions workflow that builds and publishes a multi-arch image to:

`ghcr.io/axelcypher/xiaomi-mi-scale-ha-add-on`

The add-on config is set to use that GHCR image format.

## Credit
Original add-on author: [@lolouk44](https://github.com/lolouk44).
