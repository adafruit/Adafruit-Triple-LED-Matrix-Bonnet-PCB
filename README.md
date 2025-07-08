## Adafruit Triple LED Matrix Bonnet for Raspberry Pi - For HUB75 PCB

<a href="http://www.adafruit.com/products/6358"><img src="assets/6358.jpg?raw=true" width="500px"><br/>
Click here to purchase one from the Adafruit shop</a>

PCB files for the Adafruit Triple LED Matrix Bonnet for Raspberry Pi - For HUB75. 

Format is EagleCAD schematic and board layout
* https://www.adafruit.com/product/6358

### Description

You can now create large, dazzling LED matrix displays with your Raspberry Pi with the Adafruit Triple Matrix Bonnet for Raspberry Pi. This boards plugs into your Raspberry Pi with 2x20 header, and makes it super easy to control three parallel strings of HUB75 RGB matrices such as those we stock in the shop and create colorful scrolling displays or mini LED walls with ease. 

[Unlike our single-panel Matrix Bonnet](https://www.adafruit.com/product/3211), this board can drive 3 panels in parallel, also known as "active3" pinout. This means it can handle approximately 3x as many panels/pixels. However, as a trade-off, the power management is not done on-board. Instead you will have to provide the 5V 10A+ power separately! [We recommend two power distribution bus bars](https://www.adafruit.com/product/737), they're good for many amps and make wiring easier.

* "Bonnet" boards work on Raspberry Pi with a 40-pin GPIO header — Zero, Zero W/WH, Model A+, B+, Pi 2, Pi 3, Pi 4, Pi 5 They do not work with older 26-pin boards like the original Model A or B. Note with the Pi Zero, you may need to solder a header on the Pi board; it’s normally unpopulated on that model. For best performance we recommend a Pi 4 or Pi 5.
* For Pi 0, 2, 3, and 4 we recommend the [rpi-rgb-matrix driver](https://github.com/hzeller/rpi-rgb-led-matrix), with C and Python bindings. It works great, just select the standard/active3 pinout.
* For Pi 5+, [we recommend using our PIO-based matrix driver](https://learn.adafruit.com/rgb-matrix-panels-with-raspberry-pi-5) which supports up to 3 panels - check the guide for the demo code for the triple bonnet
* By default the bonnet has a slim 2x20 header on it. If you need to 'lift' the bonnet above an enclosure, [pick up a 2x20 riser header](https://www.adafruit.com/product/4079). 
* If you want to get access to GPIO while the bonnet is installed, [pick up a 2x20 stacking header](https://www.adafruit.com/product/2223) - the pins will slide through the socket and you can plug something else on top.

This bonnet will make your mega-matrix projects super easy and avoid wiring complexity and mistakes:

* Simple design - plug in IDC cables, provide separate power to each panel, run our Python code!
* Onboard level shifters to convert the RasPi's 3.3V to 5.0V logic for clean and glitch free matrix driving
* Fully assembled compact design no soldering required! Plugs onto any Raspberry Pi with a 2x20 connector, and you're ready to glow.

Works with any of our [16x32, 32x32, 32x64, or 64x64 RGB LED Matrices with HUB75 connections](https://www.adafruit.com/categories/327). When using with 64x64 you can select whether the Address E pin is on the 4'th or 8'th IDC pad with an on-board switch. Want even more lights? No problem, chain multiple matrices together for a longer display. The bigger the display the harder it is on the Pi, so keep that in mind if you're using a lower-powered Pi Zero.

Please note: this Bonnet is only for use with HUB75 type RGB matrices. Not for use with NeoPixel, DotStar, or other 'addressable' LEDs.

Each order comes with a fully assembled and ready to go bonnet with all parts assembled. [RGB Matrix is not included, please check out our fine selection](https://www.adafruit.com/categories/327).

A serious 5V power supply is also required, not included, for power the matrix itself; the Pi cannot do it, to calculate the power, multiply the width of all the chained matrices * 0.12 Amps : A 32 pixel wide matrix can end up drawing 32*0.12 = 3.85A per panel so we recommend [a 5V 10A power supply](https://www.adafruit.com/product/658). Actual power usage will vary with how many LEDs you light up at once.

Raspberry Pi not included [(but we have 'em in the shop so pick one up! Pi 5 is recommended as its the newest, but Pi 4 will also work well)](https://www.adafruit.com/categories/176)

### License

Adafruit invests time and resources providing this open source design, please support Adafruit and open-source hardware by purchasing products from [Adafruit](https://www.adafruit.com)!

Designed by Limor Fried/Ladyada for Adafruit Industries.

Creative Commons Attribution/Share-Alike, all text above must be included in any redistribution. 
See license.txt for additional details.
