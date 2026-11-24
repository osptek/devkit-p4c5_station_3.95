# NestStation (灵栖小站)

OSPTEK Desk AI Companion · ESP32-P4C5 · 3.95-inch display · camera · 6 keys + joystick

<p align="center">
  <img src="docs/images/banner_en.png" alt="OSPTEK NestStation desk AI companion" width="100%">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/MCU-ESP32--P4C5-2F6F55?style=flat-square&labelColor=14201B" alt="MCU">
  <img src="https://img.shields.io/badge/Display-3.95%22-2F6F55?style=flat-square&labelColor=14201B" alt="Display">
  <img src="https://img.shields.io/badge/Camera-onboard-2F6F55?style=flat-square&labelColor=14201B" alt="Camera">
  <img src="https://img.shields.io/badge/Input-6%20keys%20%2B%20joystick-2F6F55?style=flat-square&labelColor=14201B" alt="Input">
</p>

<p align="center">
  <a href="README.md">简体中文</a> &nbsp;|&nbsp; <b>English</b>
</p>

<img src="docs/images/divider.svg" alt="" width="100%" height="4">

## Overview

NestStation (灵栖小站) is an OSPTEK desktop development kit; this repository is `devkit-p4c5_station_3.95`.

It is built on the [ESP32-P4C5-Module dev board](https://github.com/osptek/devboard-esp32p4c5_module), with a 3.95-inch display, a camera on top, and six mechanical keys plus a joystick on the front. The screen is tilted slightly backward so it is easy to see on a desk. The body is white, with sound holes on the back.

<p align="center">
  <img src="images/product.jpg" alt="NestStation front view" width="45%">
</p>

<p align="center">
  <img src="images/angles.jpg" alt="NestStation front, front-side and rear-side views" width="70%">
</p>

> [!NOTE]
> This document covers the hardware only for now. Firmware and software details will be added later.

## Hardware at a glance

| Item | Description |
| :--- | :--- |
| MCU | ESP32-P4C5 ([ESP32-P4C5-Module dev board](https://github.com/osptek/devboard-esp32p4c5_module)) |
| Display | 3.95-inch, mounted with a slight backward tilt |
| Camera | On top of the body |
| Input | 6 mechanical keys + 1 joystick |
| Enclosure | White body |

For the carrier schematic, dimensions, interfaces and GPIO, see the [ESP32-P4C5-Module dev board](https://github.com/osptek/devboard-esp32p4c5_module) repository.

Keypad board project (6 keys + joystick, EasyEDA Pro, 2026-11-23): [hardware/NestStation_Keypad_EasyEDA_20261123.epro2](./hardware/NestStation_Keypad_EasyEDA_20261123.epro2).

## Related resources

- [ESP32-P4C5-Module dev board (carrier docs, schematic, firmware)](https://github.com/osptek/devboard-esp32p4c5_module)

## License

Repository materials (docs, images, etc.): [CC BY-NC-SA 4.0](LICENSE). Credit OSPTEK when sharing or adapting; non-commercial use only. Contact us for commercial licensing.

<p align="center">
  <b>O S P T E K</b> &nbsp;·&nbsp; <code>NESTSTATION</code>
</p>
