# ESP32-C6 Expansion Board

## Overview

This project features a modular expansion board based on the **ESP32-C6** microcontroller, designed to showcase advanced wireless connectivity and interface flexibility for proof-of-concept embedded systems. The board includes **Wi-Fi 6**, **Bluetooth 5**, and **802.15.4 (Thread/Zigbee)** support, making it suitable for modern IoT applications. In addition to its wireless capabilities, the board exposes key communication interfaces like **QSPI**, **SPI**, **I2C**, and **UART**, enabling it to serve as a powerful, plug-and-play module in larger prototype systems.

## Features

- **ESP32-C6 MCU** – RISC-V single-core processor with Wi-Fi 6, BLE 5, Thread, and Zigbee support
- **QSPI Interface** – For high-speed flash memory or display integration
- **SPI, I2C, UART** – Standard communication protocols for versatile interfacing
- **Low Power Operation** – Ideal for battery-powered and energy-conscious applications
- **Modular Design** – Created for reuse across multiple proof-of-concept hardware projects

## Applications

- **IoT Prototyping** – Wireless communication for smart sensors and devices
- **Home Automation** – Thread/Zigbee-enabled devices with cloud connectivity
- **Industrial Monitoring** – Robust wireless links in noisy environments
- **Education & Research** – Hands-on embedded systems development

## Getting Started

### Hardware Requirements

- ESP32-C6 Expansion Board
- Host MCU or baseboard (if applicable)
- USB-C or serial programmer (if needed)
- 3.3V power supply

### Software Requirements

- [ESP-IDF](https://docs.espressif.com/projects/esp-idf/en/latest/esp32c6/index.html) – Espressif's official development framework
- [esptool.py](https://github.com/espressif/esptool) – Flashing utility
- Serial terminal (e.g., `minicom`, `screen`, or [CoolTerm](https://freeware.the-meiers.org/))

## Setup & Usage

1. **Power the Board** – Supply 3.3V through header or onboard regulator.
2. **Connect to PC** – Use a USB-to-serial adapter if required.
3. **Flash Firmware** – Use `esptool.py` or ESP-IDF to upload your application.
4. **Interface with Peripherals** – Connect SPI/I2C/UART/QSPI devices as needed.
5. **Run Application** – Test wireless or peripheral functionality in your project.

## Schematic

You can view the schematic [here](Hardware/Schematic/ESP32-C6_Expansion_Schematic.pdf) *(update with actual path)*.

## Future Enhancements

- 🔹 **Thread/Zigbee Demos** – Example apps using 802.15.4 stack
- 🔹 **External Flash/Display Support** – Over QSPI
- 🔹 **Power Optimization Modes** – Advanced sleep and wake-up configurations
- 🔹 **Plug-in Board Compatibility** – For stacking with other expansions

## License

This project is open-source under the **MIT License**.

