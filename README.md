# platform_template
This is a template repository for describing a platform (like a boat, car, farm or house/apartment) for a sensor-y technical project

# About the platform
This is the HMT Template. A generic vessel capable of navigating the seas, fields, roads, cities and suburbs.

# Parts

This template uses ESP-32s and sensors to monitor and trigger on all aspects of boat life.


## Processing and communication
Several ESP32s that uses SMS and LoRaWAN to forward information.

## UI
4 inch TFT resistive touch screen

## Data collection
We all like data right? Well here it comes.

### I2c
* CO2/Humidity/Temperature
* Proximity

### CANbus/SeatalkNG
* NMEA2000 converter

### RS-232 

* Ultrasonic level meters (black/potable water)

### Resistor
* Lever level fuel meter
* Thermistor

## Safety/security
These sensors  are in a separate section, as they are not merely data collectors, but with little processing triggers of high priority messaging, waking up more central devices and need to operate continuously, with far lower energy consumption.


### I2c
* IR movement sensor
* Gas/fire sensor

### SPI
* EM proximity sensor

### GPIO
* Fluid level sensor



