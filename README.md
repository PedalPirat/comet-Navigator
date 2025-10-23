# comet-Navigator
Extension for the [Mecha Comet](https://mecha.so/comet) based on the nRF54H20 with GPS, IMU and CAN


Part of the [PedalPirat](https://github.com/PedalPirat/PedalPirat) ecosystem, intended to be used with the [pizero_bikecomputer](https://github.com/hishizuka/pizero_bikecomputer)

## Motivation
I want to use the pizero_bikecomputer on a Mecha Comet. For it to work it needs some sensors as described [here](https://github.com/hishizuka/pizero_bikecomputer/blob/master/doc/hardware_installation.md), so the goal is to create a PCB with
- Nordic [nRF54H20](https://www.nordicsemi.com/Products/nRF54H20)
  - Supports ANT+ (soon)
  - CAN
  - USB Host to connect to the Comet
- u-blox [MAX-M10S](https://www.u-blox.com/en/product/max-m10-series) (GPS)
- Bosch [BHI385](https://www.bosch-sensortec.com/products/smart-sensor-systems/bhi385/) (IMU/Environmental)
- CAN-Transceiver (to connect to the PedalPirat or E-Bikes)
- 5 Buttons (to control the Software)


## Existing Products / Designs
- 