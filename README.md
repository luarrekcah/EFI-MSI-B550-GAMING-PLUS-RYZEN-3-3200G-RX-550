# Hackintosh: MSI B550 Gaming Plus / Ryzen 3 3200G / RX 550 4GB

![MacOS Screenshot](print-osx.png)

This repository provides details on my Hackintosh build. Below is a summary of the hardware and its compatibility with macOS.

Benchmarks: [here](https://browser.geekbench.com/user/539709)

---

## Hardware Overview

| Component          | Model                          | Status        |
|--------------------|--------------------------------|---------------|
| **Motherboard**    | MSI B550 Gaming Plus          | Fully Working |
| **CPU**            | AMD Ryzen 3 3200G             | Fully Working |
| **GPU**            | AMD RX 550 4GB                | Works Great |
| **RAM**            | 16gb DDR4 3,2ghz              | Fully Working |
| **Storage**        | 250gb NVMe - 250gb sata - 2tb hdd | Fully Working |
| **Audio**          | Realtek ALC Audio (onboard)   | Fully Working |
| **Networking**     | [bcm94360cd](https://pt.aliexpress.com/item/1005007474393740.html?spm=a2g0o.order_list.order_list_main.11.4826caa4omkike&gatewayAdapt=glo2bra)     | Fully Working |

---

## Compatibility Notes

- **Graphics**: The AMD RX 550 isnot native polaris, i did a fakeid and it works as well.
- **Audio**: Realtek onboard audio is fully functional.
- **Networking**: AirDrop, Wi-Fi, Bluetooth and Ethernet fully functional.
- **Emulation**: No supported for AMD, but can use XCode Simulator (tested iphone 16).

---

## Software Setup

- **Bootloader**: OpenCore 1.0.4
- **Operating System**: macOS Sequoia 15.3

---

For more details on the configuration files and troubleshooting, please refer to the documentation provided in the repository.

Credits to [Universo Hackintosh](http://universohackintosh.com) for creating helpfull content about hackintosh and how-to.


