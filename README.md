<a href="https://discord.gg/R7YNRcsUsk"><img src="https://img.shields.io/discord/1230525222135005276.svg" alt="Discord"> </a>

# SmartPrintCoreH7x

![SmartPrintCoreH7x](Media//SmartPrintCoreH7x.png)

SmartPrintCoreH7X © 2024 by Boltz R&D is licensed under Creative Commons Attribution-ShareAlike 4.0 International. To view a copy of this license, visit https://creativecommons.org/licenses/by-sa/4.0/

Dive into the heart of innovation with SmartPrintCoreH7x, a groundbreaking open-source 3D printer mainboard designed with passion for the community and a clear focus on durability, reliability, and ease of use. Born from a vision to empower makers, tinkerers, and engineers around the globe, SmartPrintCoreH7x prepares to stand as a beacon of collaborative development in the 3D printing world.

## Revolutionary Self-Locking Connectors

At the core of SmartPrintCoreH7x's design philosophy lies our pioneering use of self-locking connectors. These connectors redefine what you can expect from your 3D printing hardware:

- **Unwavering Reliability**: Say goodbye to loose connections. Our self-locking connectors ensure a steadfast link under any condition, providing you peace of mind.
- **Swift Assembly**: Experience the sheer joy of building and upgrading your setup with connectors designed for hassle-free, tool-less assembly and disassembly.
- **Durability Redefined**: Engineered for endurance, these connectors withstand repeated use, helping your mainboard last longer and perform better.

![Self-Locking Connectors](Media//ConnectorsImg.png "Self-Locking Connectors in Action")
![Self-Locking Connectors](Media//SmartPrintCoreH7x_mot_ports.png "Self-Locking Connectors in Action")

## Unmatched Power Supply Reliability

SmartPrintCoreH7x introduces an unparalleled level of reliability in power supplies. With robust Texas Instrument Buck converters at its heart, and a design that accommodates 5V and 12V 5A power supplies, it ensures your projects are powered efficiently and without interruption.

- **Versatile Power Compatibility**: Whether you're using a 24V or 12V PSU, SmartPrintCoreH7x adapts seamlessly, providing stable and reliable power to all components.
- **Advanced Power Management**: Auto power switching and dedicated circuits for SBC, peripherals, and fans mean that power is precisely distributed where and when it's needed.

## High Power and Superior Thermal Design

The high power capabilities of SmartPrintCoreH7x are matched by an innovative thermal design using custom heatsinks(TBD) with strategic airflow paths, ensuring efficient heat dissipation even under the most demanding operations.

- **Efficient High-Power Mosfets**: Low RDS(on) Mosfets minimize heat production while maximizing power efficiency, allowing for cool and reliable operation.

- **Optimized Thermal Layout**: The PCB design prioritizes heat management, with strategically placed components and thermal pathways that ensure optimal cooling.


## Open-Source and Community-Driven

SmartPrintCoreH7x is more than just hardware; it's a commitment to the open-source ethos. Crafted in KiCad and compatible with both Marlin and Klipper firmware, it's a testament to the power of community collaboration. Whether you're looking to tweak, enhance, or build from scratch, SmartPrintCoreH7x is your canvas.

### Key Features

- **STM32H723 MCU**: Elevate your print quality with high-performance computing.
- **USB C & Power Management**: Seamless connectivity with auto-switching and robust power supplies.
- **Advanced Thermal Management**: Keep cool under pressure with superior design.
- **Compatibility Plus**: Fully geared for Marlin and Klipper, unleash the potential of your prints.
- **Super Minimal Jumper Settings**: Ready to go with as little as 2 Jumper Installations.

## Join the Movement

Ready to contribute, tweak, or dive deep into the SmartPrintCoreH7x project? Here's how you can get involved:

1. **Clone and Create**: Start with `git clone https://github.com/BoltzRnD/SmartPrintCoreH7x.git`.
2. **Explore and Expand**: Dive into the schematics, contribute your modifications, or simply marvel at the possibilities.
3. **Share and Support**: Got an idea, a question, or a masterpiece? Share it! Our community thrives on collaboration and support.

## Embrace Openness

Licensed under CC-BY-SA, SmartPrintCoreH7x embodies the spirit of open access and shared progress. Your contributions, enhancements, and feedback not only fuel the future of this project but also fortify the foundation of the open-source hardware movement.

## A Call to Innovators

To everyone who's ever dreamed of pushing the boundaries of what's possible with 3D printing — SmartPrintCoreH7x is for you. It's not just a project; it's a promise to keep the spirit of innovation, freedom, and collaboration alive in every piece of hardware we build together.

We are actively looking for contributors to keep this project alive, Join us in making 3D printing more accessible, reliable, and fun for everyone. Let's create, innovate, and inspire the future, one layer at a time.

Feature Requests and Bug Reports are most welcome :)

## All Features

1. **Fully Open-Source Design**: Accessible and modifiable for all.
2. **Developed in KiCad**: Ensuring ease of use and widespread accessibility.
3. **Powered by STM32H723 MCU**: High-performance computing for advanced operations.
4. **Equipped with Five Motor Drivers**: Enables precise control of multi-axis movements.
5. **Five Closed-Loop External Stepper Ports**: For enhanced motion accuracy and repeatability.
6. **USB-C with Auto Power Switching**: Seamless power management and device connectivity.
7. **Easy-to-Assemble Connector Architecture**: Ensures reliable and quick assembly.
8. **Enhanced Thermal Management**: Optimized for high-power operations to maintain performance.
9. **Locking JST-GH Connectors**: Secure and stable connections for critical components.
10. **Comprehensive Fan Support**: Includes four PWM and two always-on fan ports.
11. **Dual Voltage Compatibility**: Supports both 24V and 12V power supplies.
12. **Four Servo Channels**: Broadens the range of mechanical applications.
13. **Innovative Single Side-Entry Locking Connector**: Simplifies power input connections.
14. **Reliable TI Buck Converters**: Efficient power supply for SBC and auxiliary components.
15. **Robust 5V 10A Supply for SBC**: Delivered via a secure locking connector and Type-C port.
16. **Versatile Auxiliary Power**: 5V 5A and 12V 5A supplies for peripherals and fans.
17. **3.3V 1A Auxiliary Supply**: Dedicated power for Wi-Fi modules and small peripherals.
18. **High-Efficiency MOSFETs**: Low RDS(on) for cooler and more efficient operation.
19. **15A Max Power Heated Bed**: Features an easy-to-use locking connector.
20. **Three High-Power Heaters**: Designed with locking connectors for secure installation.
21. **Secure Connectors for Motors and Power**: Enhance the reliability and safety of connections.
22. **Onboard Slow Burning Fuse**: Adds an extra layer of safety.
    1.  Note - The Board Assembly requires external inline fuses for Power Input (Included in BOM)
23. **Low-Noise Power Design**: Ensures stable operation of the MCU and accelerometers.
24. **DIP Switch Configuration**: Allows for easy setup of sensorless homing.
25. **Preconfigured Switchable Microstepping**: SMD resistors preinstalled for flexible stepper configuration.
26. **Buffered Signals**:
    - Motor SPI
    - UART
27. **Firmware Flexibility**: Supports both Marlin and Klipper.
28. **Clearly Marked Stepper Drivers**: For straightforward identification and setup.

## Ports Overview

| Port Category          | Quantity                | Details                                  | Current Rating (Max Unless Notified)         |
|------------------------|-------------------------|------------------------------------------|----------------------------------------------|
| Power Input            | 1                       | 6-in-1;                                  | 60A Total: 20A BED, 20A Motors, 20A Heaters  |
| Steppers               | 5 (+1)                  | 2 Ports for Z Stepper                    | 20A                                          |
| Smart Steppers Port    | 5 (+1)                  |                                          | 20A                                          |
| Heaters                | 3                       |                                          | 20A                                          |
| Bed Heaters            | 1                       |                                          | 20A                                          |
| Accelerometer          | 3 (Total)               | 1 x SPI 3.3V, 1 x I2C 5V, 1 x I2C 3.3V   | 1A                                           |
| ESP-01 UART            | 1                       |                                          | 1A                                           |
| FAN                    | 6                       | 4 x PWM + 2 x Always On, Switchable      | 5A                                           |
| Servo                  | 4                       |                                          | 5A                                           |
| Aux Servo Power        | 1                       | 5V                                       | 5A                                           |
| SPI (Spare)            | 3                       | 1 x 3.3V + 2 x 5V                        | 1A 5V, 0.2A 3.3V                             |
| PT100 SPI Port         | 1                       |                                          | 0.2A                                         |
| USART                  | 2                       |                                          | 2A                                           |
| SBC Supply             | 2                       | 1 x 4-pin Connector + 1 x Type C         | 10A                                          |
| CAN                    | 1                       |                                          | 0A                                           |
| Temperature Sensors    | 4                       |                                          | N/A                                          |
| Endstops               | 6                       |                                          | N/A                                          |
| Filament Sensors       | 2                       |                                          | N/A                                          |
| LCD Connector Set      | 1                       |                                          | 2A                                           |
| SWD                    | 1                       |                                          | N/A                                          |
| PS CTRL                | 1                       |                                          | N/A                                          |
| PS PWR DET             | 1                       |                                          | N/A                                          |
| Neopixel LED Port      | 1                       |                                          | 2A                                           |
| BLTOUCH Port           | 1                       |                                          | 2A                                           |
| Probe                  | 1                       |                                          | 2A                                           |
| MicroSD                | 1                       |                                          | N/A                                          |


## Jumpers and Configurations

| Configuration               | Options                           | Description                                 |
|-----------------------------|-----------------------------------|---------------------------------------------|
| Sensorless Homing           | 1                                 | Configurable through onboard DIP switches   |
| Fan Voltage Selection       | 2                                 | Selectable voltages: 12V, 5V, or POWER_IN   |


## Design Considerations
To optimize general usage and simplify installation, the following design features have been incorporated:

1. **External Inline Fuses**: Installed beyond the power supply line for easy fuse replacement without the need to dismantle the mainboard section of your printer.
2. **Pre-Configured Stepper Jumpers**:
   - Jumpers are preset to high using 0402 resistors, eliminating the need for manual adjustments.
   - MSX bit changes are managed via firmware if you are utilizing hardware settings.
   - Note: A4988/DRV8266 and SPI-based drivers cannot be mixed and used concurrently without soldering additional 0402 configuration resistors.

## Buy From
1. Boltz R&D - Contact us at info@boltzrnd.com
2. -- More to Come --

Interested in becoming a listed manufacturer? Reach out to us at info@boltzrnd.com to discuss adding your store link here or to be our official Manufacturing Partner.

## Compatible Accesories -
1. Custom Heatsinks - [To Be Released By May 2024] 
2. Cases - [To Be Released By May 2024] 

Note - Stay tuned to our Thingiverse channel to be the first one to know - https://www.thingiverse.com/boltzrnd/designs

# Story Time

### How It Was Created
SmartPrintCoreH7x was born out of a combination of long commute hours and a renewed passion for building. With 7 hours a day of travel time, a result of embarking on an exciting single life, there was ample opportunity to reconnect with my hobby of creating innovative hardware. Fueled by endless cups of Chai Tea and free time, I found a new rhythm between the rails and circuits.

### Why It Was Created
The motivation behind SmartPrintCoreH7x is deeply rooted in both personal need and a broader vision for the 3D printing community:
- **High-Speed Performance**: Designed to handle extremely high printing speeds, up to 3000 mm/s, preparing for future advancements in 3D printing technology.
- **Unmatched Control**: Providing complete control over the hardware, allowing for extensive customization and modification at any time to meet evolving needs.
- **Reliable and Easy Connections**: To eliminate common issues with connectivity in intensive printing operations.
- **Open Source Commitment**: Ensuring the hardware remains open and accessible, allowing anyone to modify and improve upon the design without restriction.
- **Safety and Reliability**: Integrating robust power supplies to safeguard the system, particularly enhancing the performance and reliability of connected Single Board Computers (SBCs).

### Our Philosophy: Power Meets Passion
Every aspect of SmartPrintCoreH7x reflects a commitment to quality, flexibility, and open innovation. Developed during long commutes, this project is a testament to the idea that passion can turn even the most routine activities into opportunities for creativity and impact. This board isn't just about pushing the boundaries of 3D printing; it's about redefining them with every print.

# Commitment to Open Source

**Note:** In celebration of our dedication to open-source hardware and software, Boltz R&D endorses the use of BeaglePlay and BeagleBone SBCs with SmartPrintCoreH7X. We are committed to actively supporting the community by ensuring seamless interfacing and integration of these setups.

# Extra notes

1. Marlin Configuration is still under development, Please Raise a requirement on discord to prioritize it above other tasks if needed.
2. The Component Libraries are not included and redistributed because of license restrictions, contact us to join our organisation as a "contributor" to access the part libraries for development.
3. Custom 3D Printed casing is under development and evaluation, and is expected to release by end of May 2024.
4. The Klipper Configuration files are minimal, and will require some modifications to fit your use case, reach out to us whenever in doubt.
5. Feel Free to reach out to our discord server for any queries related to integration, development and production.
6. You can also send us feasture requests that you'd like to see in the next versions of the board.

# Disclaimer

The SmartPrintCoreH7x is an open-source project provided by Boltz R&D. It is offered "as is" and without any warranties or guarantees, express or implied.

Boltz R&D provides no warranty of any kind regarding the safety, reliability, durability, and performance of the SmartPrintCoreH7x. By using this project's design, software, or hardware, you expressly acknowledge and agree that you assume all risks associated with its use.

Boltz R&D shall not be liable for any claims, damages, or other liabilities whatsoever, whether in an action of contract, tort or otherwise, arising from, out of, or in connection with the SmartPrintCoreH7x or the use or other dealings in this project.

This project is provided as an open-source resource for the community to use, modify, and distribute subject to the terms of the CC-BY-SA 4.0 license. All third parties manufacturing, selling, or using the SmartPrintCoreH7x are responsible for ensuring that their products and services comply with all applicable laws and regulations.

Users are responsible for compliance with local laws, and for ensuring that appropriate safety measures are in place when manufacturing, using, or modifying the SmartPrintCoreH7x mainboard.
