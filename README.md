![The Project so far](https://github.com/bneedhamia/MAX31820WeatherStation/blob/master/Project.jpg)
# MAX31820WeatherStation
An Arduino Sketch for a Sparkfun ESP8266 Thing Dev board, using a MAX31820 temperature sensor to sense and report the current ambient temperature to the Weather Underground via WiFi.

The state of the project: My weather station is installed on my house wall (not the best site), and is sending the temperature to Weather Underground every 10 minutes. See Diary.odt for details.

The Arduino Sketch requires a Sparkfun ESP8266 Thing Dev board, a MAX31820 temperature sensor, a 4.7K Ohm pull-up resistor and a few wires. Details are in BillOfMaterials.ods. Total cost: about $28 USD.

## Files
* BillOfMaterials.ods = the parts list.
* box.stl = the 3D printing file for the box that holds the parts. Print in PLA, upside down, with no support, raft, or brim.
* boxLid.stl = the 3D printing file for the box's lid. Print in PLA, upside down, with no support, raft, or brim.
* Diary.odt = my journal/diary of the project, with design and assembly details.
* LICENSE = the project GPL2 license file.
* MAX31820WeatherStation.ino = the ESP8266 Arduino Sketch.
* MAX31820WeatherStation.fzz = the Fritzing (circuit wiring) diagram. See [Fritzing.org](http://fritzing.org)
* Project.jpg = a photo of the project so far.
* ProjectBox.FCStd = the FreeCAD design file for the box that holds the parts.
* README.md = this file.