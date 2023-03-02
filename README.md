# XenoponicsPCB

Xenoponics was the final design project for EECS 473. Designed around the ESP32 microcontroller, the Xenoponics board can monitor solution parameters, control lights/pumps, and record data for a hydroponics growing system.  

![image](https://user-images.githubusercontent.com/64921046/222591835-91ebb92b-7283-4f32-92e0-6fdee4978930.png)

The TDS and pH sensors were based on schematics from [SeeedStudio](https://wiki.seeedstudio.com/Grove-TDS-Sensor/) and [DHRobot](https://wiki.dfrobot.com/PH_meter_SKU__SEN0161_). 
The L293D Dual H-Bridge driver from Texas Instruments was used to control peristaltic motors in order to dose solution based on the readings from  the TDS and pH sensors.
The DS18B20 thermistor from Analog Devices was used to measure the solution's temperature.

## NOTE:
This project is currently available for portfolio purposes.
The codebase for this project is not currently on a public facing repository due to some outstanding changes that would need to be
made in order to properly interface to a new cloud server.
Additionally, there are some small hardware issues that are not currently noted anywhere. 
(i.e. the TDS sensor connector is an incorrect part for the probe that was used).
