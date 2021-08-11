## Adafruit 24LC32 I2C EEPROM Breakout PCB

<a href="http://www.adafruit.com/products/5146"><img src="assets/5146.jpg?raw=true" width="500px"><br/>
Click here to purchase one from the Adafruit shop</a>

PCB files for the Adafruit 24LC32 I2C EEPROM Breakout. 

Format is EagleCAD schematic and board layout
* https://www.adafruit.com/product/5146

### Description

If you want to store calibration values, MAC addresses, non-secure access tokens, or other unique identifiers, EEPROM storage is a great option. EEPROM is long lasting, and doesn't need to be written in pages - a single byte can be written at once (unlike with flash memory!) EEPROM storage persists even when the power goes out, and can be over-written literally one million times.

Some microcontrollers, like the ATmega328, have built in EEPROM, usually around 64 to 1024 bytes of it. But some, especially ARM Cortex's, don't! What then? that's where this petite Adafruit 24LC32 I2C EEPROM Breakout comes in to help! With 32 Kbit (4 KByte) of storage, and handy chainable Stemma QT connectors, it's just the right amount of simple I2C-controllable storage. Since its external to your microcontroller or microcomputer, uploading new flash memory won't wipe the data from this chip.

We use the CAT24C32 (or equivalent) EEPROM, internally organized as 4096 words of 8 bits each. It features a 32 byte page write buffer (if you want to write faster than one byte at a time). Use 2 to 5V power/logic and up to 1 MHz clocked I2C. The default I2C address is 0x50 and there are three external address pins / jumpers to allow addressing of up to eight EEPROM devices on the same bus.

To make things easier and a bit more flexible, we've also included SparkFun Qwiic compatible STEMMA QT connectors for the I2C bus so you don't even need to solder! Just plug in a compatible cable and attach it to your MCU of choice, and you’re ready to store and retrieve from a reliable and durable EEPROM. QT Cable is not included, but we have a variety in the shop. 

### License

Adafruit invests time and resources providing this open source design, please support Adafruit and open-source hardware by purchasing products from [Adafruit](https://www.adafruit.com)!

Designed by Limor Fried/Ladyada for Adafruit Industries.

Creative Commons Attribution/Share-Alike, all text above must be included in any redistribution. 
See license.txt for additional details.
