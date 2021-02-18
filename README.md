# DynaLoRa USB Radio Dongle
DynaLoRa USB Radio is a low cost, CircuitPython and Arduino compatible USB radio dongle.

This plaform is equipped with an ATSAMD21 micrcontroller, plus a HopeRF radio module. By default we chose the RFM96W, a LoRa 868 - 915 MHz module based on Semtech's SX1276. You can use an RFM95W for 433 MHz, or an RFM69HCW for generic non-LoRa Sub-GHz radios since they are pin compatible.

Hardware in this repository is licenced under **CERN OHL v1.2**.

## Technical details

- ATSAMD21E18 48 MHz Cortex-M0+ processor with 256 KB flash + 32 KB RAM, compatible with CircuitPython and Arduino
- 32 Mbit SPI flash for storing CircuitPython code and libraries
- High performance HopeRF radio module. You can choose between LoRa (RFM96W, RFM95W) or regular Sub-GHz (RFM69HCW).
- User-controllable WS2812B addressable RGB LED
- Regular user LED
- 3V3 @ 1A power through a DC/DC buck regulator from USB
- MicroSD Card slot
- GPIO header exposing SWD interface, a full SERCOM (enabling external SPI/I2C/UART peripherals) and a DAC for prototyping
- This version comes with an USB-A plug. It should be easy enough to modify the design to offer other options (such as USB-C).

## Documentation

Available in our [Wiki](https://github.com/BHDynamics/rfm_radio_dongle/wiki).
