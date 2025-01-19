# Electronic Clock with Alarm Function (Using SDK-1.1M)

## Project Objective
This project is designed to create an electronic clock with an alarm function using the SDK-1.1M platform. The system uses the STM32F407VGT6 microcontroller and the MCP79411 RTC module for precise time tracking. The clock displays the current time on a graphical OLED display and allows users to set an alarm through a user interface. The settings are retained even when power is disconnected, thanks to the built-in battery of the RTC module.

## Features
- Display the current time in real-time.
- Set the time and alarm via buttons.
- Trigger the alarm at the set time with a flashing screen.
- Power-saving mode to extend battery life.

## Requirements

### Hardware
- **SDK-1.1M Platform**
- **STM32F407VGT6 Microcontroller**
- **OLED Display**: WEO012864DL from Winstar
- **RTC Module**: MCP79411 (with battery backup for time tracking)
- **12-Button Keypad** for time and alarm configuration

### Software
- **STM32CubeMX**
- **STM32CubeIDE**

## Installation Instructions for Windows 7/8/10

1. **Install WinUSB driver** using the **Zadig** program.
   - Connect the SDK-1.1M to your computer via the USB DBG connector.
   - Open the **Zadig** program and check the option **List All Devices**.
   - Select the device **Dual RS232 (Interface 0)**.
   - Choose **WinUSB** from the available driver list.
   - Click **Replace/Install** to install the driver.

## Usage Instructions
1. **Setting Time**: Use the keypad to set the current time on the clock.
2. **Setting Alarm**: Use the keypad to set the alarm time.
3. **Triggering Alarm**: The alarm will activate at the set time, and the screen will flash to alert the user.

## Development Tools

- **STM32CubeMX** for configuring the microcontroller and peripherals.
- **STM32CubeIDE** for development and debugging the project.
