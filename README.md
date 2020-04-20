SparkFun Auto pHAT for Raspberry Pi (Qwiic)
========================================

[![SparkFun Auto pHAT for Raspberry Pi (Qwiic))](https://cdn.sparkfun.com//assets/parts/1/5/0/3/5/16328-SparkFun_Auto_pHAT_for_Raspberry_Pi-01b.jpg)](https://www.sparkfun.com/products/16328)

[*SparkFun Auto pHAT for Raspberry Pi (Qwiic) (ROB-16328)*](https://www.sparkfun.com/products/16328)

The SparkFun Auto pHAT for Raspberry Pi is an all in one robotics package that focuses on quickly adding robot functionality and support to your Raspberry Pi or other single-board computer. The Auto pHAT can drive two small DC motors with or without encoders and up to four servo motors in a straightforward manner via an I<sup>2</sup>C connection. The servo control is based on the [SparkFun servo pHAT](https://www.sparkfun.com/products/15316) and thanks to its I<sup>2</sup>C capabilities, this PWM add-on saves the Raspberry Pi's GPIO pins, allowing you to use them for other purposes. We have also provided a Qwiic connector for easy interfacing with the I<sup>2</sup>C bus using the [Qwiic system](https://www.sparkfun.com/qwiic). Whether you use the Auto pHAT with a Raspberry Pi, NVIDIA, Jetson Nano, Google Coral, or other SBC, it makes for a unique robotics addition for and board with a 2x20 GPIO.

The DC motor control comes from the same 4245 PSOC and 2-channel motor ports system used on the [SparkFun Qwiic Motor Driver](https://www.sparkfun.com/products/15451). This provides 1.2A steady state drive per channel (1.5A peak) and 127 levels of DC drive strength. The SparkFun Auto pHAT also supports up to two motor encoders thanks to the onboard ATTINY84A to provide more precise movement to your creation! 

Additionally, the Auto pHAT has an on-board ICM-20948 9DOF IMU for all your motion sensing needs. This enables your robot to access the 3-Axis Gyroscope with four selectable ranges, 3-Axis Accelerometer, again with four selectable ranges, and 3-axis magnetometer with an FSR of ±4900µT.

Power to the SparkFun Auto pHAT can be supplied through USB-C connector or external power. This will power either the motors only, or power the motors as well as the Raspberry Pi that is connected to the HAT. This USB-C connector can also be used to hook up the Pi via serial port connection to avoid having to use a monitor and keyboard for setting up the Pi. We've even added power protection circuits to the design, to avoid damage to power sources.


For reference on programming the ATTINY84:

FUSE BITS:
(Set fuses to run at 8MHz internal)
(Disable Brown Out Detect)

* LowFuse 0xE2 
* HighFuse 0xDF
* ExtendedFuse 0xFF


Repository Contents
-------------------

* **/Documentation** - Data sheets, additional product information
* **/Hardware** - Eagle design files (.brd, .sch)
* **/Hardware/Production** - Production panel files and gerbers (.brd)
* **/Firmware** - Firmware for the Dual Encoder Reader IC (ATTiny84) and the Motor Driver IC (4245 PSOC)

Documentation
--------------

* **[Hookup Guide](https://learn.sparkfun.com/tutorials/sparkfun-auto-phat-hookup-guide)** - Basic hookup guide for the SparkFun Auto pHAT for Raspberry Pi (Qwiic).

License Information
-------------------

This product is _**open source**_! 

Please review the LICENSE.md file for license information. 

If you have any questions or concerns on licensing, please contact technical support on our [SparkFun forums](https://forum.sparkfun.com/viewforum.php?f=152).

Distributed as-is; no warranty is given.

- Your friends at SparkFun.
