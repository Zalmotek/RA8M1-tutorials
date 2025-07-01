# Renesas RA8M1 Feather SoM 

Welcome to the <a href="https://zalmotek.com/products/RA8M1-Feather-SoM/">Renesas RA8M1 Feather SoM</a> GitHub repository!

Here you'll find all the resources you need to get up and running quickly.

## 🪶 What is the RA8M1 Feather SoM?

The <a href="https://www.renesas.com/en/products/microcontrollers-microprocessors/ra-cortex-m-mcus/ra8m1-480mhz-arm-cortex-m85-based-microcontroller-helium-and-trustzone">Renesas RA8M1</a> allows you to achieve the full potential of a real-time operating system (RTOS) while leveraging the performance boost provided by the 64-bit Arm® Cortex®-M85 CPU core with a maximum operating frequency of 360 MHz.

Besides the processor, the Feather SoM contains the classic Feather features: GPIOs (analog and digital), I2C and SPI communication pins, UART pins, a LiPo battery power plug, and the USB programming port. The SoM also features a USB Type-C for powering the board and for USB debug upload, making it perfect for high-performance embedded applications requiring advanced security features.

<p align="center">
  <img src="images/Feather-RA8M1-pinout.png" height="500">
  <img src="images/Feather-RA8M1-BD.png" height="500">
</p>

## Feather Pinout

The pinout for each port is as follows:


| Pin | Function | Notes | Pin | Function | Notes |
| :-- | :-- | :-- | :-- | :-- | :-- |
| 1 | RESET |  |  |  |  |
| 2 | VCC (3V3) |  |  |  |  |
| 3 | AREF |  |  |  |  |
| 4 | GND |  |  |  |  |
| 5 | A0 | BSP_IO_PORT_00_PIN_14 | 17 | VBAT |  |
| 6 | A1 | BSP_IO_PORT_00_PIN_08 | 18 | EN |  |
| 7 | A2 | BSP_IO_PORT_00_PIN_07 | 19 | BUS |  |
| 8 | A3 | BSP_IO_PORT_00_PIN_06 | 20 | D13 | BSP_IO_PORT_01_PIN_15 |
| 9 | A4 | BSP_IO_PORT_00_PIN_05 | 21 | D12 | BSP_IO_PORT_01_PIN_14 |
| 10 | A5 | BSP_IO_PORT_00_PIN_04 | 22 | D11 | BSP_IO_PORT_01_PIN_13 |
| 11 | SCK | BSP_IO_PORT_04_PIN_12  | 23 | D10 | BSP_IO_PORT_01_PIN_12 |
| 12 | MOSI | BSP_IO_PORT_04_PIN_11 | 24 | D9 | BSP_IO_PORT_04_PIN_15 |
| 13 | MISO| BSP_IO_PORT_04_PIN_10 | 25 | D6 | BSP_IO_PORT_04_PIN_14 |
| 14 | RX | BSP_IO_PORT_08_PIN_02 | 26 | D5 | BSP_IO_PORT_04_PIN_08 |
| 15 | TX | BSP_IO_PORT_08_PIN_01 | 27 | SCL | BSP_IO_PORT_02_PIN_05 |
| 16 | D14 | BSP_IO_PORT_00_PIN_00 | 28 | SDA | BSP_IO_PORT_02_PIN_06 |


## 🐣🏁 Quick Start Guide

### 🔌 Hardware Requirements
- USB-C cable
- JTAG Debugger, such as the <a href="https://www.segger.com/products/debug-probes/j-link/">SEGGER J-Link</a>

### 💻 Development Environment Setup

#### Installing Renesas e² studio IDE

The e² studio IDE from Renesas is a comprehensive, user-friendly platform designed to streamline embedded application development. It supports Renesas microcontrollers and combines powerful features with an intuitive interface for coding, debugging, and project management.

First of all, download the latest release of the Flexible Software Package with the e²studio platform installer from the following <a href="https://www.renesas.com/us/en/software-tool/e2studio-information-ra-family">link</a>, according to your OS.

The installer will guide you through the necessary steps. After the installation is finished, launch Renesas e² studio and set up your workspace. This will be the directory where all your projects will be stored.

You will also need to install the J-Link Software pack from <a href="https://www.segger.com/products/debug-probes/j-link/technology/flash-download/">here</a>.

#### Running your first project

Once you have all the tools installed, follow <a href="https://github.com/Zalmotek/renesas-RA8M1-feather/tree/main/firmware/Blink/RA8M1_Feather_Blink">this</a> guide to learn how to import, build, and run a project in the e² studio IDE. 

---
Thank you for choosing the Renesas RA8M1 Feather SoM! 

We can't wait to see what amazing projects you'll create with it! 💻✨
