<p align="center">
    <img src="https://qclic.github.io/img/logo.svg" alt="secos-logo" width="64"><br>
    A security operating system focused on the AIoT (Artificial Intelligence of Things) field.<br/>
    <br/>
</p>

English | [中文版](README_CN.md)

# Introduction

This repository contains pre-built SecOS-related image files for Feiteng Pi and Raspberry Pi 4B, intended for quickly experiencing the performance of SecOS.

# Quick Start

1. Burn the Linux image to the SD card
   - Raspberry Pi: Use the official `Raspberry Pi imager` tool, Raspberry Pi Imager, to write the `raspberrypi4/openeuler-image-raspberrypi4-64-20241128020741.rootfs.rpi-sdimg` image to the SD card.
   - Phytium Pi: Use the `Win32DiskImager` tool to write the `phytiumpi/openeuler-image-phytiumpi-20241128014520.rootfs.genimage` image to the SD card

2. Insert the SD card into the development board and power it on. The default username is root, and you will need to set a password during the first boot.

3. Copy the `arceos/arceos.bin` file to the Linux system on the development board.

4. Start Jailhouse and boot the arceos.bin as an Inmate

# Documents

For more information about the project, check out [The SecOS Document](https://qclic.github.io/).

# License

The source code and documentation of SecOS are primarily licensed under the MIT License, while some components retain their original open-source licenses.
