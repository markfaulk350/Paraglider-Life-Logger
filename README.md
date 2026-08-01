# Paraglider-Life-Logger

[Example Web App on CodePen | The esp32 will serve this page with the onboard data. No internet connection required](https://codepen.io/editor/markfaulk350/pen/019f87c5-aa06-7c7d-9d85-782d8050ce29)

## Goal
The goal is to build a stupid simple device that measures the amount of time the glider has spent out of the bag. A single light sensor cannot tell us whether you are sitting on launch parawaiting, kiting, flying, packing your wing, etc. But its a simple metric. How many hours has this glider been out of the bag exposed to light.



# 🔥🔥🔥🔥 TODO 🔥🔥🔥🔥
* Figure out a file format that works
* Order a GPS module, see if we can update the timestamp with it, and how fast it finds location after sleeping.
* Record distance, altitude, timestamp, random light value to a CSV File. Create a web app that has a download CSV file button. Also display the battery voltage.
* Test out the new distance sensor in sunlight.
* Order an SPI Flash from adafruit to play with. Maybe I2C or SPI FRAM too while you are at it. And GPS
* Create a webapp that takes that CSV file and analyzes all the flights, and shows data


# Current Hardware
* [Adafruit ESP32 Feather V2 - 8MB Flash + 2 MB PSRAM - STEMMA QT](https://www.adafruit.com/product/5400)
* [Lithium Ion Polymer Battery - 3.7V 350mAh](https://www.adafruit.com/product/2750)
* [Adafruit MAX44009 Wide-range Lux Light Sensor - 188,000 Lux Max STEMMAQT / Qwiic](https://www.adafruit.com/product/6498)
* [MPL3115A2 - I2C Barometric Pressure/Altitude/Temperature Sensor](https://www.adafruit.com/product/1893)
* [TOF400C VL53L1X 4M Laser Ranging Sensor](https://a.co/d/06YS9mfA)
* [SHILLEHTEK MPU6050 GY-521 Module | 6-Axis Accelerometer Sensor & IMU Sensor](https://a.co/d/0cQsTEwh)


# "Other" Hardware used during Testing
* [ESP32-S3-DevKitC-1-N8R8 Development Board](https://a.co/d/014kO2zb)
* [Adafruit LTR-303 Light Sensor - STEMMA QT / Qwiic](https://www.adafruit.com/product/5610)
* 
