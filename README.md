<!-- Please do not change this html logo with link -->
<a href="https://www.microchip.com" rel="nofollow"><img src="images/microchip.png" alt="MCHP" width="300"/></a>

# AVR128DB48 Using the Internal Opamp as Regulated Power Supply for MVIO
A new feature introduced in the AVR® DB family is the Analog Signal Conditioning (OPAMP) peripheral. In this example, the OPAMP is used as an adjustable power supply. This eliminates the need for an external power supply for a second voltage domain. One op amp is configured as a voltage follower and code examples for four scenarios are presented:
1.	Voltage reference using the internal resistor ladder
2.	Voltage reference using an external resistor
3.	Voltage reference using the internal DAC
4.	Monitoring voltage level with the internal ADC


## Related Documentation

* [ANxxxx - AVR128DB48 Using the Internal OPAMP as Regulated Power Supply for MVIO](https://microchip.com/DSxxxxxxxxxx) <!--fill in DS number once it has been assigned-->
* [AVR128DB48 device page](https://www.microchip.com/wwwproducts/en/AVR128DB48)
* AVR128DB48 Curiosity Nano User Guide (link will be added once available)

## Software Used

* [Atmel Studio](https://www.microchip.com/mplab/avr-support/atmel-studio-7) 7.0.2397 or later
* Atmel Studio AVR-DB_DFP version 1.3.67 or later
* For the MPLAB® X version of these projects, please go to [this repository](https://github.com/microchip-pic-avr-examples/avr128db48-using-opamp-as-a-regulated-power-supply-mplab)

## Hardware Used

* [AVR128DB48 Curiosity Nano](https://www.microchip.com/DevelopmentTools/ProductDetails/PartNO/EV35L43A) <!-- Not the correct link, fix when curiosity nano page exists-->
* Two resistors (values based on desired voltage level)


## Setup

->
* Enable MVIO powered by internal op-amps on the development board, see [application note](https://microchip.com/DSxxxxxxxxxx) for each respective scenario <!--fill in DS number once it has been assigned-->
* Enable Dual Supply mode in the System Configuration 1 (SYSCFG1) fuse

## Operation
* Connect the AVR128DB48 Curiosity Nano to a computer using a USB cable
* Download the zip file or clone the example to get the source code
* Open the .atsln with Atmel Studio
* Press *Start without debugging* or use CTRL+ALT+F5 hotkeys to run the application


## Conclusion
After going through this example you should have a better understanding of how to set up the OPAMP peripheral as a regulated power supply.
