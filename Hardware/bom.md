# Materials


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
At least 80% higher voltage rating than the power rail used, size is important for the decoupling
capacitor that need to be 0201 or 0402.  
Cermic X5R or X7R with good tolerance 10% or 20%.  

- CL05B104KO5NNNC - 100 nF  
- CL10A106MA8NRNC - 10 uF
