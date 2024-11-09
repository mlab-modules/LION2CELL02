### MLAB LION2CELL02 - Dual-Cell Li-Ion Battery Management Module

### What is it?

The **MLAB LION2CELL02** is a high-efficiency dual-cell battery management system (BMS) designed to charge and protect a two-cell Li-Ion battery stack. Featuring an I2C interface and a USB-C charging port, the LION2CELL02 integrates easily into systems requiring robust power management. The module is compatible with standard USB BC 1.2 sources.

The LION2CELL02 is pre-configured for **INR18650MJ1** cells, ensuring optimal performance and battery health.

### Why did you make it?

This module was created to simplify the power management and protection requirements where single-cell Li-Ion battery setups are not enougth. It’s tailored to applications requiring reliable charging, safety, and monitoring features, which are essential in embedded systems like IoT devices, portable instruments, and backup power solutions. 

### What makes it special?

- **Dual-cell support and protection**: Charger and Gas-gauge both independently manages charging for two Li-Ion cells, with integrated protection for voltage, current, and temperature.
- **I2C communication**: Allows seamless integration with microcontroller systems for real-time battery status.
- **High-efficiency charging**: Includes the BQ25792 high-efficiency buck-boost charger, ensuring fast and reliable charging from USB-C sources.
- **Advanced cell balancing**: The BQ40Z50-R2 fuel gauge features Impedance Track™ technology for precise capacity measurement and cell balancing, extending battery lifespan.
- **Flexible Power Delivery (PD)**: Compatible with USB BC 1.2 and offers optional USB PD support via an external controller.

### Key Features

- **USB-C Charging**: Supports USB BC 1.2 with an optional external PD controller.
- **Integrated Protections**: Includes overvoltage, undervoltage, overcurrent, and thermal protections.
- **High Precision Fuel Gauge**: Impedance Track™ technology provides real-time capacity and state-of-charge data.
- **I2C Interface**: Connects easily to MCUs for monitoring battery voltage, current, and temperature.
- **LED Indicators**: Visual indicators display charge level and fault conditions.

### Technical Specifications

- **Battery Type**: Li-Ion (configured for INR18650MJ1 cells)
- **Cells Supported**: 2 cells (2S configuration)
- **Charger IC**: Texas Instruments BQ25792
- **Fuel Gauge IC**: Texas Instruments BQ40Z50-R2
- **Input Voltage**: 3.6V to 20V (USB-C)
- **Output Current**: Up to 5A (charging), 3A (USB OTG mode)
- **Communication**: I2C (compatible with SMBus v1.1)
- **Protections**: Overvoltage, undervoltage, overcurrent, overtemperature, cell balancing
- **Dimensions**: Fits standard 6x8 MLAB module footprint

For additional details and configuration options, refer to the datasheets for [BQ40Z50-R2](https://www.ti.com/product/BQ40Z50-R2) and [BQ25792](https://www.ti.com/product/BQ25792).

### Included

- LION2CELL02 module pre-configured
- Two INR18650MJ1 Li-ion cells

### Use Cases

- [Stratospheric baloons](https://github.com/ODZ-UJF-AV-CR/FIK-6)
 


