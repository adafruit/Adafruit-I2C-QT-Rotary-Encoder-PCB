## Adafruit I2C QT Rotary Encoder with NeoPixel - STEMMA QT / Qwiic PCB

<a href="http://www.adafruit.com/products/4991"><img src="assets/4991.jpg?raw=true" width="500px"><br/>
Click here to purchase one from the Adafruit shop</a>

PCB files for the Adafruit I2C QT Rotary Encoder with NeoPixel - STEMMA QT / Qwiic. 

Format is EagleCAD schematic and board layout
* https://www.adafruit.com/product/4991

### Description

Rotary encoders are soooo much fun! Twist em this way, then twist them that way. Unlike potentiometers, they go all the way around, and often have little detents for tactile feedback. But, if you've ever tried to add encoders to your project you know that they're a real challenge to use: timers, interrupts, debouncing...

This Stemma QT breakout makes all that frustration go away - solder in any 'standard' PEC11-pinout rotary encoder with or without a push-switch. The onboard microcontroller is programmed with our seesaw firmware and will track all pulses and pins for you and then save the incremental value for querying at any time over I2C. Plug it in with a Stemma QT cable for instant rotary goodness, with any kind of microcontroller from an Arduino UNO up to a Raspberry Pi.

You can use our Arduino library to control and read data with any compatible microcontroller. We also have CircuitPython/Python code for use with computers or single-board Linux boards.

It's also easy to add this breakout to a breadboard - with six 0.1"-spaced breakout pads. Power with 3 to 5V DC and then use 3 or 5V logic I2C data. The INT pin can be configured to pulse low whenever rotation or push-buttoning is detected so you do not have to spam-read the I2C port to detect motion.

There's a NeoPixel onboard, that can display any color you like. It's also controlled over I2C for additional visual feedback or keep it off if you like. On the back there's a green power LED as well as a red INT LED that, if the interrupt is configured, will blink when the interrupt fires.

Using the three onboard address jumpers, you can connect up to 8 of these rotary encoders on a single I2C port. The first one will be at address 0x36, the last one at 0x3D when all three jumpers are soldered closed.

To keep the board nice and compact, only 1" x 1" we made the footprint for the rotary encoder at a 45-degree angle. Since it rotates around freely there's no need for it to be at a 90-degree angle to the PCB. Each order comes with one assembled and tested PCB breakout and a small piece of header.

To get you going fast, we spun up a custom made PCB with the seesaw chip and all supporting circuitry, in the STEMMA QT form factor, making them easy to interface with. The STEMMA QT connectors on either side are compatible with the SparkFun Qwiic I2C connectors. This allows you to make solderless connections between your development board and the rotary encoder or to chain them with a wide range of other sensors and accessories using a compatible cable. QT Cable is not included, but we have a variety in the shop.

This breakout does not come with an encoder soldered on, so you can pick whatever encoder you like. We sell a common 24-detent-with-switch encoder here and it works wonderfully. You can also use encoders without detents or with a different number of detents per rotation, of course! You'll need to solder the encoder and optional header onto the PCB to use with a solderless breadboard. but it's fairly easy and takes only a few minutes even for a beginner.

### License

Adafruit invests time and resources providing this open source design, please support Adafruit and open-source hardware by purchasing products from [Adafruit](https://www.adafruit.com)!

Designed by Limor Fried/Ladyada for Adafruit Industries.

Creative Commons Attribution/Share-Alike, all text above must be included in any redistribution. 
See license.txt for additional details.
