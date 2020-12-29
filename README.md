# Power Delivery sink
A board that negotiates voltage with PD compatible power supply.
Utilizes Cypress semiconductor's CYPD3177 IC.

![A little board](https://github.com/midub/USB-C_PD_sink/blob/main/usbc-pd-sink.PNG "Render of USB-C PD sink")

### Features
- Tiny 32x16 mm board.
- Up to 3A current.
- High quality USB-C connector for power applications.
- Large output pins.
- I2C, GPIO_1, Interupt and Flip pins are wired out to a 2x3 1.27mm pitch pin header.
- Screw holes next to usb-c port for better attachment.

![PCB footprint](https://github.com/midub/USB-C_PD_sink/blob/main/usbc-pd-sink2.PNG "PCB footprint")

### Todo
- Replace output power pins with fastons.
- Create a design block, which can be used by powered board.
- Add a 5V output for situation when negotiation fails.

## DISCLAIMER: Use at your own risk
