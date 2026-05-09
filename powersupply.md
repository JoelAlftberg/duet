# Power supply

Voltage leves  
- 1.1 V FPGA core voltage (buck converter)
- 1.8 V RAM and FPGA io bank as well as HDMI transmitter(LDO)
- 3.3 V for ESP32, FPGA aux, HDMI possibly and Pmods
- 5 V passthrough to expansion header


Vcc core needs 3x 10 uF capacitors spread out around the chip and each vcc pin (1.1V core) needs a
100 nF decoupling capacitor as close to the ball as possible. X7R ceramic capacitors are preferred
and size 201 or 402.
