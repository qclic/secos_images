<p align="center">
    <img src="https://qclic.github.io/img/logo.svg" alt="secos-logo" width="64"><br>
    A security operating system focused on the AIoT (Artificial Intelligence of Things) field.<br/>
    <br/>
</p>

[English](README.md) | 中文版

# 简介

本仓库中包含预构建的适用于飞腾派和树莓派 4B 的 SecOS 相关镜像文件，用于快速体验 SecOS 的运行效果。

# 快速上手

1. 将 Linux 镜像烧录 SD 中
   - 树莓派：使用树莓派官方的烧录工具 `Raspberry Pi Imager` 将 `raspberrypi4/openeuler-image-raspberrypi4-64-20241128020741.rootfs.rpi-sdimg` 烧写到 SD 卡中
   - 飞腾派：使用 `Win32DiskImager` 烧录工具将 `phytiumpi/openeuler-image-phytiumpi-20241128014520.rootfs.genimage` 烧写到 SD 卡中

2. 将 SD 卡插入到开发板并上电启动。默认用户名为 root，初次启动需要先设置一个密码！

3. 将 `arceos/arceos.bin` 复制到开发板中的 Linux 系统中

4. 启动 Jailhouse，并将 arceos.bin 作为一个 Inmate 启动即可

# 技术文档

查看 [The SecOS Document](https://qclic.github.io/) 以了解更多关于本项目的信息。

# 开源许可

SecOS 的源代码和文档主要使用 MIT 协议， 部分组件保持原有开源协议！
