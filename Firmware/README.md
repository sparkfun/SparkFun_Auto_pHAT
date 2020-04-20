SparkFun Auto pHAT for Raspberry Pi (Qwiic)
========================================

The SparkFun Auto pHAT for Raspberry Pi Has two separate pieces of firmware:

(1) The Motor Controller firmware on the 4245 PSOC on the Auto pHAT is identical to the firmware found on the [SparkFun Qwiic Motor Driver](https://www.sparkfun.com/products/15451).

[Serial Controller Motor Driver Firmware](https://github.com/sparkfun/Serial_Controlled_Motor_Driver)

(2) The Encoder Reader firmware on the ATTiny84 can be found at the following Github Repository:

[Qwiic Dual Encoder Reader Firmware](https://github.com/sparkfun/Qwiic_Dual_Encoder_Reader)

For reference on programming the ATTINY84:

FUSE BITS:
(Set fuses to run at 8MHz internal)
(Disable Brown Out Detect)

* LowFuse 0xE2 
* HighFuse 0xDF
* ExtendedFuse 0xFF

License Information
-------------------

This product is _**open source**_! 

Please review the LICENSE.md file for license information. 

If you have any questions or concerns on licensing, please contact technical support on our [SparkFun forums](https://forum.sparkfun.com/viewforum.php?f=152).

Distributed as-is; no warranty is given.

- Your friends at SparkFun.
