## Adafruit NFC/RFID controller breakout board - v1.6 PCB

<a href="http://www.adafruit.com/products/364"><img src="assets/364.jpg?raw=true" width="500px"><br/>
Click here to purchase one from the Adafruit shop</a>

PCB files for the Adafruit NFC/RFID controller breakout board - v1.6. Format is EagleCAD schematic and board layout
* https://www.adafruit.com/product/364

### Description

The PN532 is the most popular NFC chip, and is what is embedded in pretty much every phone or device that does NFC. It can pretty much do it all, such as read and write to tags and cards, communicate with phones (say for payment processing), and 'act' like a NFC tag. If you want to do any sort of embedded NFC work, this is the chip you'll want to use!

NFC (Near Field Communications) is a way for two devices very close to each other to communicate. Sort of like a very short range bluetooth that doesn't require authentication. It is an extension of RFID, so anything you can do with RFID you can do with NFC. You can do more stuff with NFC as well, such as communicate bi-directionally with cell phones

Because it can read and write tags, you can always just use this for RFID-tag projects. We carry a few different tags that work great with this chip. It can also work with any other NFC/RFID Type 1 thru 4 tag.

The PN532 is also very flexible, you can use 3.3V TTL UART at any baud rate, I2C or SPI to communicate with it. This chip is also strongly supported by [libnfc](http://www.libnfc.org/), simply plug in an FTDI cable and use the FTDI serial port device to communicate - this lets you do NFC dev using any Linux/Mac/Windows computer! We also include onboard power LED, 3.3V regulator and an FTDI header so you can plug in an [FTDI friend](http://www.adafruit.com/products/284) or [FTDI cable](http://www.adafruit.com/products/70) and use with libnfc.

Comes with: the PN532 breakout board including a tuned 13.56MHz stripline antenna, 0.1" header, 2 jumpers/shunts and a 4050 level shifter chip. We also toss in a  13.56MHz 1K card! ([You can get more tags from us here](http://www.adafruit.com/category/55))

### License

Adafruit invests time and resources providing this open source design, please support Adafruit and open-source hardware by purchasing products from [Adafruit](https://www.adafruit.com)!

Designed by Limor Fried/Ladyada for Adafruit Industries.

Creative Commons Attribution/Share-Alike, all text above must be included in any redistribution. See license.txt for additional details.
