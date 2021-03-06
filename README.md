# LoPy weather station

This repository contains a script to create a weather station using the LoPy, PySense and The Things Network. The script is sending for example light, humidity and temperature every 5 minutes to TTN. After sending the information a deep sleep is performed to minimize the power usage (running it on a solar panel and battery). My setup:
- LoPy (https://pycom.io/product/lopy4/)
- PySense (https://pycom.io/product/pysense/)
- 4400mAh battery (https://www.adafruit.com/product/354)
- PowerBoost 500 Basic (https://www.adafruit.com/product/1903)
- USB / DC / Solar Lithium Ion/Polymer charger (https://www.adafruit.com/product/390)
- Solar panel (https://www.adafruit.com/product/200)

Retrieving the data using home assistant using the TTN component.

Modify the following lines in the script before using (values obtained from TTN):
```
app_eui = binascii.unhexlify('')
app_key = binascii.unhexlify('')
```
![alt tag](https://i.imgur.com/sg1jCOI.jpg)
