**UART-wand** //
It is an open-source, ultra-compact USB-to-Serial converter. It uses the CH340E IC to provide a stable asynchronous serial interface (UART) via a USB-C connector.

This design is ideal for developers working with ESP8266, ESP32, Arduino Pro Mini, or any system requiring a serial console where space is limited.

**Features**
USB-C Interface: Modern reversible connector for easy connectivity.

CH340E Chipset: No external crystal required, allowing for a tiny PCB footprint.

Compact Design: Dongle-style form factor that plugs directly into your computer.

Enhanced Reliability: Includes teardrops on all pads and vias for improved mechanical and electrical durability.

Standard Pinout: Breaks out TX, RX, VCC (5V/3.3V), and GND.

**Hardware Specifications**
PCB Layers: 2

Track Width: 0.2 mm

Minimum Clearance: 0.2 mm

Via Size: 0.6 mm (0.3 mm drill)

EDA Tool: KiCad 8.0+

**Getting Started**
Manufacturing: Use the provided KiCad files to generate Gerbers or use the provided BOM to order components.

Drivers: The CH340 chip is natively supported by most Linux distributions and macOS. For Windows, you may need to install the standard CH340 drivers.

Usage: Connect the TX/RX pins to your target device (cross-connect: TX to RX, RX to TX).
