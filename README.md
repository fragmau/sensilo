# sensilo project - a small sensor board
## Design Definition

- [ ] The board must be run by a uController
- [ ] The board must be powered off of a USB-C connector
- [ ] The board must be able to generate a 3.3V single rail
- [ ] The board must be debuggable via SWD and programmable via USB
- [ ] The board shall have a square size, no bigger than 10x10cm
- [ ] The board must contain a high resolution data converter
- [ ] The board must be able to monitor multiple analog signals
- [ ] The analog signals shall be provided through screw-in connectors
- [ ] The board must have status, power and a spare LED indicators
- [ ] The board shall integrate at least 1 sensor, with the remaining being external to it
- [ ] The board shall integrate a connector to debug the system
- [ ] The board shall integrate a connector to access and debug the digital interfaces enabled on it (SPI, I2C…..)
- [ ] The board shall have the capability of it being powered through a battery
- [ ] The system’s overall power consumption shall be minimised
- [ ] The board must have 4 layers

## Components list
- [x] RP2040 - C2040 - ARM Cortex-M0 1@x4ch/12bit USB Host/Device 2 264KB 2 133MHz 30 2 QFN-56(7x7)  Microcontroller Units (MCUs/MPUs/SOCs) ROHS
- [x] AD7124-8 - NA - High Resolution S-D ADC
- [x] X322512MSB4SI - C9002 - 12MHz SMD Crystal Resonator 20pF ±10ppm ±30ppm -40℃~+85℃ SMD3225-4P  Crystals ROHS
- [x] AMS1117-3.3 - C6186 - 72dB@(120Hz) 1A 1.3V@(800mA) Fixed 3.3V~3.3V Positive 1 SOT-223  Linear Voltage Regulators (LDO) ROHS
- [x] TYPE-C-31-M-12 - C165948 - 250mA 1 16 Female Type-C SMD  USB Connectors ROHS
- [x] W25Q128JVSIQ - C97521 - SOIC-8_208mil  NOR FLASH ROHS
- [x] ALS-PT19-315C/L177/TR8 - C146233 - 1.7*0.8*0.6mm  Ambient Light Sensors ROHS
- [x] TS-1187A-B-A-B - C318884 - No NO 50mA 5.1mm 100mΩ 100000 160gf 12V -30℃~+85℃ 5.1mm 1.5mm Golden Round Button Brick nogging SPST SMD  Tactile Switches ROHS
- [x] CMFB103F3950FANT - C51597 - 10kΩ -40℃~+120℃ ±1% 3950K ±1% 0805  NTC Thermistors ROHS

# TODO
- [ ] Confirm Footprints assigned to all components with JLCPCB parts
- [ ] Create footprint for Ambient Light Sensor
- [ ] Confirm footprint of push button for reset
- [ ] Confirm footprint and/or replace SPST button as it seems there is nothing that's not a push button