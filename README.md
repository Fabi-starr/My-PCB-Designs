# My-PCB-Designs
Multipurpose Flight controller PCB Design 

## Flight Controller PCB Design
 # Overview
This repository contains the design files and documentation for a **multipurpose flight controller PCB**. The flight controller is designed for UAV applications, providing robust sensor integration, motor control, and communication interfaces. It supports a wide range of sensors and actuators to offer precise control and stabilization for drones or other flying platforms.
Features
- Microcontroller: STM32F100RCT6(LQFP144)
- Sensors Supported: MPU9250 (9-axis IMU), BMP280 (barometric pressure sensor), etc.
- Motor Control: Supports up to 6 servo motors for flight stabilization.
- Communication: Zigbee, I2C, SPI, and UART interfaces for sensor and module integration.
- Power Management: USB-powered with onboard voltage regulation.
- PCB Design: Optimized for compactness and efficient signal routing.

## Hardware Specifications
- Dimensions: 7cm*7cm
- Number of Layers: Two Layers
- Connectors: 8 terminal blocks for input/output, switches, and MOSFET-controlled outputs.
- Antenna Interface: SMA connector with PCB trace antenna support for Zigbee communication.
- Sensors Interface: MPU9250 (I2C), BMP280 (I2C).
- Power: Powered through USB with onboard voltage regulation.
## Requirements
- PCB Design Software: The PCB files were created using : EasyEDA pro_version .
- Components: 
  - Microcontroller: STM32F100RCT6(LQFP144)
  - Sensors: MPU9250, BMP280
  - Zigbee Module: CC2530
  - SMA Connector

## Block Diagram







 







## Contributing
Feel free to open issues or submit pull requests if you'd like to contribute or improve the design.
## Contact
If you have any questions or suggestions, feel free to reach out at fabiolaingabire02gmail.com.


