# Adafruit_MCP23008_RF
The Microchip's MCP23008 I/O Extender, sold by Adafruit.com, has a very nice application as a bidirectional
pin extender for Arduino. It communicates using the I2C protocol, thus utilizaiton of only 2 Arduino pins 
leads to as many as 8 GPIO pins. This library is a small modification of the Adafruit_MCP23008 library developed 
at Adafruit. In my project, explicit reference to Adafruit_MCP23008 conflicted with the same library implicitly
used by Adafuit's LCD display. Therefore, in this library I changed all references from "Adafruit_MCP23008" to
"Adafruit_MCP23008_RF" to avoid the conflict. In addition, I've added one member function allPinMode() for
convenience.

