# LoPy weather station

This repository contains a script to create a weather station using the LoPy, PySense and The Things Network. The script is sending for example light, humidity and temperature every 5 minutes to TTN. After sending the information a deep sleep is performed to minimize the power usage (running it on a solar panel and battery). My setup:
- LoPy
- PySense
- 4400mAh battery (https://www.adafruit.com/product/354)
- Solar panel (https://www.adafruit.com/product/200)

Retrieving the data using home assistant using the TTN component.
