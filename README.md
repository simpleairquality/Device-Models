# Device Models

## SimpleAQ Pro

A primary goal while crafting the chassis for the AQ Pro was to have the fewest separate parts needed and a minimal hardware count. To accomplish this all the hardware, _with the exception of the RaspberryPi and custom TopHat_, simply friction fit into the Base Holder with only a light push of a finger. The end result is a chassis that only requires two (2) sperate parts, the Base Holder and Chassis Shell. Additionally, it incorporates two screw mounts on the back side that fit standard drywall or wood screws to allow the AQ Pro to be mounted to whatever surface is needed.

The total hardware needed to assemble the AQ Pro is as such:

- Four (4) M3x8mm Screws
- Four (4) M2.5x10mm Standoffs Make to Female
- Four (4) M.2.5x6mm Screws
- _Optional_ Two (2) Drywall Screws

The next goal was to make everything 3D Printable with minimal supports, if any, that used the least amount of material while maintaining structural rigidity and weather resistance. The final chassis can be printed in about four hours and uses less than 150g of material while needing supports on only one area of the model. 

It should be noted that a material choice of PETG, ASA, ABS, or similar is required for outdoor use. PLA will not hold up to environmental stresses.

![TopHat Install](/assets/08.jpg)

## Hardware Install Guide

Below are the recommended steps to assemble your own SimpleAQ Pro Device

### Step One - The Base

Take the Base Holder and place onto your work surface, inspect it for any defects, damage, or print errors.

![Base Holder with nothing installed in it](/assets/01.jpg)

### Step Two - The GPS

Slide the BE-180 GPS into its housing area ensuring the connector is on the bottom side. It is recommended to the connect the cable to the GPS before installing the GPS.

![GPS Install](/assets/02.jpg)

### Step Three - The BMP

Press the BMP into the slot next to the GPS with the _BMP Text_ on the module facing up to avoid damaging any components on the board. It's a tight fit, but won't damage anything while installing. Again, it is recommended to the connect the cable to the BMP before installing it.

![BMP Install](/assets/03.jpg)

### Step Four - The SENS

Next insert the SENS module into its dedicated location making sure it's fully seated. Cable installation can be done now or later.

![SENS Install](/assets/04.jpg)

### Step Five - The RaspberryPi Zero

Gather the RaspberryPi Zero and four standoffs. Place the Pi with the Micro SD card slot closest to the grille vents. Secure it to the Base Holder with the four stand offs.

![rPi Install](/assets/05.jpg)

### Step Six - TopHat

Now attach the TopHat onto the RaspberyPi with the power connector over the Pi's SD Card Slot. Secure it with four M2.5 screws.

![TopHat Install](/assets/06.jpg)

### Step Seven - Specialty Sensors

If you are using any specialty sensors press fit them into the included tube slots. Use which ever locations you prefer. 
_If you have less than three sensors use the AQ Pro Plugs to seal off the unused tubes._

![TopHat Install](/assets/07.jpg)

### Step Eight - Connect Everything and Close it up

Connect everything to the TopHat following the labeles on the TopHat. Plug in the power cable to the TopHat and route the cable through the included notch of the Base Holder. Flip the Base Holder over and insert it into the Chassis Shell ensuring the SENS is closest to the wall mounting screws of the Chassis Shell. Secure the Base Holder to the Chassis Shell with four M3x8mm Screws.

And your done!

## 3D Printable Files

Below are the files needed to print your own SimpleAQ Pro

[Base Holder](https://github.com/simpleairquality/Device-Models/blob/main/assets/Base%20Holder.step)<br/>
[Chassis Shell](https://github.com/simpleairquality/Device-Models/blob/main/assets/Chassis%20Shell.step)<br/>
[Chassis Plug](https://github.com/simpleairquality/Device-Models/blob/main/assets/Plug.step)<br/>


## 3D Printing Notes - Read if you plan to print your own Chassis

- As stated above you must use PETG, ASA, ABS or similar materials if you plan to use the Simple AQ Pro outdoors.
- When printing use 3 or 4 wall loops for strength and weather resistance.
- For infill you can use 15% with any method you prefer.
- Print the Chassis Shell with the top portion on the print bed. It should look like a bowl in the slicing software. No supports are needed for the Shell.
- When printing the Base Holder supports are needed for the GPS Holder. You can use default support settings without issue. See below for the exact area supports are needed.

![Support Location](/assets/10.jpg)
