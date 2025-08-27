# Blinky Template

This template is a minimal STM32 project that toggles an LED at a fixed interval using the HAL library. It targets the STM32F4 series but can be adapted to other STM32 families by updating the clock configuration and pin assignment.

## Files
- `main.c` – Implements `main()` and basic initialization. Uses HAL to toggle PA5 every 500 ms.
- `README.md` – Provides an overview and instructions.

## Usage
1. Create a new CubeMX project for your target MCU and generate code.
2. Replace the generated `main.c` with this template, or merge the LED blink logic.
3. Ensure the GPIO pin and clock settings match your hardware.
4. Build and flash the project using your preferred IDE (Keil, STM32CubeIDE, etc.).

This template aims to demonstrate the recommended folder structure and coding style. Extend it by adding peripherals, FreeRTOS, or other modules.
