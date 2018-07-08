# Color-Wifi

> Open Source air quality monitor with ODIN-W262



## Specs
- Supports `PM2.5 + Co2 + TVoc + TH/R`
- Used `ARM mbed OS`
- Software : [Github @Colorful-Fish](https://github.com/colorful-fish)
- Debugger : [Daplink Debugger](https://github.com/ARMmbed/mbed-HDK)

## Used Design Tools
- EDA
    - Altium Designer V18
- Mech
    - SolidWorks 2017
    - Autocad 2017

## Sensors
- Particulate Matter ( PM1.0 / PM2.5 )
    - WUHAN CUBIC : PM2006
- Carbon Dioxde
    - WUHAN CUBIC : CM1106
- Temp & Humid with Tvoc
    - Bosch BME680

## Warning
- Recommanded Voltage: `5V 1A`
- Each sensor will calibrate itself for GRIMM reference
- Co2 Sensor has internal ABC( Automatic baseline correction ) Logic, 
    it will work least one week power on
