# Lattice ECP5

LFE5U-45

## Power requirements
1.1 V core operating voltage
1.8 V RAM voltage for one of the banks

## Banks

### Bank 0 and 1
3.3 Vcc-io  
HDMI, I2C, Pmod headers

### Bank 2
1.8 Vcc-io
HyperRAM

## Bank 6 and 7
Mezzanine 60p connector    

### Bank 8
3.3 Vcc-io  
SPI flash, JTAG, ESP32


## Pinout 

The nomeclature for the pins are the following:

P means Pin I/O  
L/R simply indicates what side of the physical IC the pin is located  
T/B indicates top or bottom of the IC  

The left side has banks 2 and 3
The right side has banks 6 and 7
The top side has banks 0 and 1
The bottom has bank 8


sysI/O is the name of the buffers used to interface with the ECP5  
