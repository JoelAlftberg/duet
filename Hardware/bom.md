# Materials

## MCU

An ESP32 with built in WiFi and BLE as well as 16 MB flash and 8 MB RAM, chosen for ease of
development and price.   

ESP32-S3-WROOM-1-N16R8

Pin headers  
`TO BE ADDED`

## FPGA 
The FPGA chosen for the development board is the Lattice ECP5 chosen for its amount of LUTs, speed
and price.  

LFE5U-45F-6BG256C

## Oscillator
25 MHz crystal oscillator for the FPGA  
OT322525MJBA4SL  

## HDMI controller and interface
SII9022ACNU  
version 1.4a  
supports up to 1080p 60Hz (24 bit RGB)  
I2C and I2S  

Connector  
A71-05H5-111N1

## RAM 
W956D8MBYA5I  
64 Mbit 200 MHz with 2 bytes per clock = 400 MB/s in theory  
Requires 1.8 V

## Flash
W25Q128JVSIQ  
128Mbit  
Quad SPI  
3.3 V

## Power

Powered by 5V from USB-C

TPS563201  
1.1V for the FPGA core  
3.3V for ESP32  

AMS1117-2.5  
2.5 V LDO for the FPGA auxiliary  

RT9193-18GB  
1.8 V LDO for HyperRAM and its accosiated FPGA IO bank  

RT9013-12GB  
1.2 V LDO for the HDMI Transmitters core supply and analog supply for the output circuitry

## Decoupling capacitors
Cermic X5R or X7R with good tolerance 10% or 20%.  

- CL05B104KO5NNNC - 100 nF  
- CL05B103KB5NNNC - 10 nF  
- CL21A226MAQNNNE - 22 uF  
- CL10A106MA8NRNC - 10 uF  
- CL05A475MP5NRNC - 4.7 uF  

## Ferrite beads
Used in conjunction with the decoupling capacitors to reduce high frequency noise of the power
supply to the core voltage of the ICs.  
- GZ1608D601TF - 600ohm@100MHz 200mA 450mOhm  


## Resistors

Most are chosen from the same series on JLCPCB from the manufacturer UNI-ROYAL

- 0402WGF1002TCE - 10k 0402 package resistors, 62.5 mW   
- 0402WGF4701TCE - 4.7k 0402 package reisstors, 62.5 mW  
- 0402WGF2201TCE - 2.2k 0402 package reisstors, 62.5 mW  

## LEDs

Status LEDs for the FPGA and MCU
