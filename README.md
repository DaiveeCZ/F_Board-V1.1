# F_Board-V1.1

![fboard](https://github.com/DaiveeCZ/F_Board-V1.1/assets/83717170/ed4c998c-00fe-417b-99ba-c810fd10f93e)

Programmer based on CH340 chip for ESP8266. It is designed for programming the module directly soldered on the board. Connection to PC is using industrial version of USB-C from Amphenol.
**This board has been manufactured and tested in practice.**


![usbc](https://github.com/DaiveeCZ/F_Board-V1.1/assets/83717170/fc345e8a-e55b-454d-9f8f-355ae2995fac)


## Pin map:
Pinheader 2.54mm
- 1 - 3.3V
- 2 - GND
- 3 - RX
- 4 - TX
- 5 - FLASH
- 6 - RESET
  
## Functionality in practice:
For proper functionality, you need to connect several 10K resistors to the ESP8266 and connect it correctly to the circuit. This must be done on the side of the board where the programmer is to be connected:
![esp](https://github.com/DaiveeCZ/F_Board-V1.1/assets/83717170/262494f8-4c14-4c93-b338-a40623eab01c)
