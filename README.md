# Paraglider-Life-Logger

[Example Web App on CodePen | The esp32 will serve this page with the onboard data. No internet connection required](https://codepen.io/editor/markfaulk350/pen/019f87c5-aa06-7c7d-9d85-782d8050ce29)

## Goal
The goal is to build a stupid simple device that measures the amount of time the glider has spent out of the bag. A single light sensor cannot tell us whether you are sitting on launch parawaiting, kiting, flying, packing your wing, etc. But its a simple metric. How many hours has this glider been out of the bag exposed to light.



🔥🔥🔥🔥 TODO 🔥🔥🔥🔥
* Order different photodiodes. Try to make them very sensitive.
* Figure out what to do when the photodiodes push too much voltage into the board and crash it.
* Figure out if we should use analog voltage to wake up our device or something else.
* Figure out if there is a TOF sensor that can wake up our device if a distance exceeds 4 inches.
* Figure out the min ditance our TOF sensor works at, and the distance when flying normally.
* Wait for the barometric sensor, adafruit feather + 3.7v battery to get here wednesday.
* Host a webapp on the esp32 that tells us the light voltage and ditance, as well as a log of barometric pressure every 30 seconds. Put it in the glider and watch the data change.
