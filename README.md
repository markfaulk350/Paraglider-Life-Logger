# Paraglider-Life-Logger

# 🔥🔥🔥🔥 TODO 🔥🔥🔥🔥
* Decide on CSV file format variable types and names, then work on the web app that takes that CSV upload, analyzes it, then displays it.
* Order a GPS module, see if we can update the timestamp with it, and how fast it finds location after sleeping.
* Record distance, altitude, timestamp, random light value to a CSV File. Create a web app that has a download CSV file button. Also display the battery voltage.
* Test out the new distance sensor in sunlight.
* Order an SPI Flash from adafruit to play with. Maybe I2C or SPI FRAM too while you are at it. And GPS
* Create a webapp that takes that CSV file and analyzes all the flights, and shows data
* When it comes to analyzing the CSV sensor data, can we use AI to look at each flight and see if anything is weird?
  * Maybe glider is left in car that still has a little bit of light
  * Glider is in stuff sack, still exposed to light, going up gondola for more laps
  * etc... Anytime the glider isnt in complete darkness while packed away  


# Current Hardware
* [Adafruit ESP32 Feather V2 - 8MB Flash + 2 MB PSRAM - STEMMA QT](https://www.adafruit.com/product/5400)
* [Lithium Ion Polymer Battery - 3.7V 350mAh](https://www.adafruit.com/product/2750)
* [Adafruit MAX44009 Wide-range Lux Light Sensor - 188,000 Lux Max STEMMAQT / Qwiic](https://www.adafruit.com/product/6498)
* [MPL3115A2 - I2C Barometric Pressure/Altitude/Temperature Sensor](https://www.adafruit.com/product/1893)
* [TOF400C VL53L1X 4M Laser Ranging Sensor](https://a.co/d/06YS9mfA)
* [SHILLEHTEK MPU6050 GY-521 Module | 6-Axis Accelerometer Sensor & IMU Sensor](https://a.co/d/0cQsTEwh)
* [Adafruit SPI FLASH Breakout W25Q128 - 128 MBit / 16 MByte](https://www.adafruit.com/product/5643)
* (OPTIONAL) | [Adafruit Mini GPS PA1010D](https://www.adafruit.com/product/4415) - GPS can be used to get the time, which solves the RTC drift issue


# "Other" Hardware used during Testing
* [ESP32-S3-DevKitC-1-N8R8 Development Board](https://a.co/d/014kO2zb)
* [Adafruit LTR-303 Light Sensor - STEMMA QT / Qwiic](https://www.adafruit.com/product/5610)


## Electrical Engineer's Reccomended Hardware
* [STM32U073KCU6](https://www.digikey.com/en/products/detail/stmicroelectronics/STM32U073KCU6/22332782)
* CR2032 battery (220-240 mAh) or CR2450 battery (500-620 mAh)
* 16Mbit external SPI flash (Use internal RAM as buffer, then save to External flash when buffer is full. Issue #31 for more info)
