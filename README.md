# Power Delivery sink
A board that negotiates voltage with PD compatible power supply.
Utilizes Cypress semiconductor's CYPD3177 IC.

### Features
- Tiny 32x16 mm board.
- Up to 3A current.
- Large output pins.
- I2C, GPIO_1, Interupt and Flip pins are wired out to a 2x3 1.27mm pitch pin header.
- Screw holes next to usb-c port for better attachment.

### Todo
- Replace output power pins with fastons.
- Create a design block, which can be used by powered board.
- Add a 5V output for situation when negotiation fails.
