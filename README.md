# Paraglider-Life-Logger

[Example Web App on CodePen | The esp32 will serve this page with the onboard data. No internet connection required](https://codepen.io/editor/markfaulk350/pen/019f87c5-aa06-7c7d-9d85-782d8050ce29)

## Goal
The goal is to build a stupid simple device that measures the amount of time the glider has spent out of the bag. A single light sensor cannot tell us whether you are sitting on launch parawaiting, kiting, flying, packing your wing, etc. But its a simple metric. How many hours has this glider been out of the bag exposed to light.



🔥🔥🔥🔥 TODO 🔥🔥🔥🔥
* Figure out a file format that works. Maybe CSV with empty row for new flight.
* Record distance, altitude, timestamp, random light value to a CSV File. Create a web app that has a download CSV file button. Also display the battery voltage.
* Test out the new distance sensor in sunlight.
* Order an SPI Flash from adafruit to play with. Maybe I2C or SPI FRAM too while you are at it.
* Create a webapp that takes that CSV file and analyzes all the flights, and shows data
* Figure out the min ditance our TOF sensor works at, and the distance when flying normally.


