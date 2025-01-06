# Marlin Morpheus STM32

This repository is a fork of [Marlin](https://github.com/MarlinFirmware/Marlin), specifically adapted for building successfully on the **BLUE PILL** board with the **STM32F103C8T6** microcontroller.

## Target Board
This firmware is intended for use with the [Morpheus-STM32](https://github.com/pscrespo/Morpheus-STM32) board.

## Features
- STM32F103C8T6
- Compatible with BLUE PILL hardware
- Pre-configured for Morpheus-STM32 board

## Requirements
Make sure you have the following dependencies installed:
- **PlatformIO**
- **STM32 Development Environment**
- Compatible build tools for Marlin firmware

## Build Instructions
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/Marlin-Morpheus-STM32.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Marlin-Morpheus-STM32
   ```
3. Build the firmware using PlatformIO:
   ```bash
   pio run
   ```
4. Upload the firmware to the STM32 board:
   ```bash
   pio run --target upload
   ```

## Configuration
You can customize the firmware settings in the `Configuration.h` and `Configuration_adv.h` files located in the `Marlin` directory.

## Troubleshooting
- Verify your connections and board configuration.
- Check the PlatformIO environment settings in `platformio.ini`.
- Review error logs during the build process for specific issues.
- See: [Morpheus-STM32 issue log](https://github.com/pscrespo/Morpheus-STM32/issues/1)

## Contribution
Contributions are welcome! Feel free to submit pull requests or report issues via GitHub.

## License
This project inherits the Marlin [GPLv3 License](https://github.com/MarlinFirmware/Marlin/blob/bugfix-2.1.x/LICENSE).

## Credits
- Original firmware: [MarlinFirmware/Marlin](https://github.com/MarlinFirmware/Marlin)
- Board: [Morpheus-STM32](https://github.com/pscrespo/Morpheus-STM32)

---
GP
