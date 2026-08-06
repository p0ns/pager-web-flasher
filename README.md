[![Cloudflare Pages](https://img.shields.io/badge/Cloudflare-Pages-F38020?logo=cloudflare&logoColor=white)](https://pager.0bn.cc)
[![GPLv3](https://img.shields.io/badge/license-GPLv3-blue.svg)](LICENSE)

# Pager Web Flasher

This public fork deploys the Meshtastic Web Flasher for the custom DEF CON 34
T-LoRa Pager firmware at <https://pager.0bn.cc>. It limits the device picker to
the LILYGO T-LoRa Pager and serves the matching firmware files from the same
site. The standard update and full erase/install flows remain available.

Firmware reproduction information is in `firmware-source/README.md`.

## Upstream Project

This project is based on [meshtastic/web-flasher](https://github.com/meshtastic/web-flasher).

## Introduction
Welcome to the Meshtastic Web Flasher - a user-friendly, robust tool designed for flashing Meshtastic devices. Leveraging the power of Nuxt/Vue and Tailwind CSS, this web application offers an easy-to-use interface for device flashing.

## Key Features
- **Espressif's esptool.js Integration**: Incorporates the official JavaScript port of Espressif's esptool for enhanced robustness and compatibility with newer Espressif silicon.
- **All-in-One Platform Support**: Designed to be a comprehensive solution, supporting a wide range of devices including nRF52 and Pico UF2.
- **Developer-Friendly Design**: Built with Nuxt/Vue, simplifying the development and maintenance process.
- **Built-in Serial Monitor**: The built-in Serial Monitor allows debugging and troubleshooting of issues encountered on Meshtastic devices via the native serial logging interface.

## Getting Started
To use the Meshtastic Web Flasher, simply visit [https://flasher.meshtastic.org](https://flasher.meshtastic.org). The website is designed to be intuitive and easy to navigate, allowing you to start flashing your devices right away.

## Contributing
Interested in contributing? Here's how you can get involved:

1. Clone this repository.
2. Make sure to install the dependencies:
```bash
pnpm install
```
3. Start the development server on `http://localhost:3000`:
```bash
pnpm run dev
```

Check out the full Nuxt [deployment documentation](https://nuxt.com/docs/getting-started/deployment#presets) for more information.

## Feedback and Support
For bug reports, feature requests, or general queries, please open an issue in this repository. Your feedback helps us improve and evolve the Meshtastic Web Flasher.

Thank you for using and supporting the Meshtastic Web Flasher.

## Stats

![Alt](https://repobeats.axiom.co/api/embed/b5590d57a9c3443c86121c36ded22aeb28f709d2.svg "Repobeats analytics image")
