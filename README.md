
# ArchDroid-KDE

One-script Arch Linux ARM + KDE Plasma desktop installer for Android using Termux, PRoot and Termux:X11, with experimental Adreno GPU acceleration.

> **Status:** Experimental. Installation reliability and GPU acceleration must be verified on each device.

## Features

- Arch Linux ARM (AArch64)
- KDE Plasma desktop with X11
- Runs without root using Termux and PRoot
- Uses Termux:X11 for the graphical desktop
- Experimental GPU acceleration investigation for compatible Adreno devices

## Requirements

- Android device with ARM64 support
- Termux
- Termux:X11
- `proot-distro`
- Sufficient free storage for Arch Linux and KDE packages

## Installation

Installation instructions will be added after the installer script has been tested and published.

## GPU Acceleration

GPU acceleration is experimental and is **not guaranteed**. Software rendering may be used if a compatible hardware-acceleration path is unavailable.

Verify the OpenGL renderer and Vulkan device inside the Linux environment before claiming hardware acceleration works.

## Troubleshooting

When reporting an issue, include your device model, Android version, installation logs, and GPU diagnostic output.

## Disclaimer

This project is provided as-is. Back up important data before installing packages or modifying your Termux environment.

## License

A license will be added when the project's licensing terms are decided.
