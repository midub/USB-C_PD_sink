# USB-C Power Delivery sink
A board that negotiates voltage with PD compatible power supply.

				An easy way to bring USB-C power to your own project.

![A little board](https://github.com/midub/USB-C_PD_sink/blob/main/usbc-pd-sink.PNG "USB-C Power Delivery sink")

### Features
- Utilizes Cypress semiconductor's [CYPD3177](https://www.cypress.com/file/460416/download) IC.
- Tiny 32x16 mm board.
- Up to 3A current thanks to quality components.
- Set voltage by specified resistor value or by I2C.
- Access to I2C, GPIO_1, Interupt and Flip pins that are wired out to a 2x3 1.27mm pitch pin header.
- Screw holes next to usb-c port for better attachment.

![PCB footprint](https://github.com/midub/USB-C_PD_sink/blob/main/usbc-pd-sink2.PNG "PCB footprint")

### Todos
- Replace output power pins with fastons or othes suitable common connector.
- Create a design block, which can be used by powered board.

## DISCLAIMER: Use at your own risk
