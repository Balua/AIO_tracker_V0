### AIO_Tracker_V1.0 - Beware, we are still testing this board...

#### Corrections and alterations to this board can be found in the AIO_tracker_V1.0 repository.


#### Features:

#####Microprocessor
- ATMEGA 328p smd package

#####Power
- Step up Boost Converters from 2 AA Batteries to 3.3V and 5V

#####Communication
- Radiometrix HX1 - VHF Narrow Band FM High Power (300mW) Transmitter with SMA Antenna
- RFM22B ISM Transceiver Module with SMA Antenna

#####GPS
- Ublox Max 6 GPS with Sarantel antenna

#####Sensors
- One wire temperature sensor - DS18B20
- Battery Voltage
- Pressure Sensor - HSCSANN015PA2A3 

#####Storage
- MicroSD Socket

#####Programming
- AVR SPI Programming pins available

#####External pins
- I2c Pins with pull-up for expansion available
- 4 ADC Pins available

#####Other
- On Board AA battery holder
- 5V boost converter with enable controllable
- UBlox GPS Power ON Controllable
- On board LED
- 5V/3.3V smd jumpers available for Atmega 328p, i2c and SPI Programming pins.

#### Erros detected and Corrections that need to be done

- Replace tx pin of HX1 from PD4 to PD3 in atmega 328 and 5V enable from PD3 to PD4.
- SDN pin of the RFM22b is low activated, therefore needs to be connected to GND instead of 3.3V.
