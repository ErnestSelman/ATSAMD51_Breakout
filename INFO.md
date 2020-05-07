# ATSAMD51_Breakout
Similar to SparkFun Thing Plus but without battery charging and leaving USB and FLASH Memory in the same pins. All other pins are accessible. I also added a connector for the PICKit4 programmer/debugger. 
You could follow SparkFun Thing Plus tutorial and program their bootloader. It should work the same as theirs and you could use Arduino to program the board through the USB. Although the reason for making this board is to learn to work with low level CORTEX M4 and stop using Arduino.
Voltage regulator are more powerfull so you can power whatever else you want with the same board. There is no over-current protection so be very carefull. 
The Flash Memory IC has the same pin-out as the one in SparkFun Thin Plus so I connected it exactly the same. If you use the IC from the BoM, it might not be the same as the one used by SparkFun so their code could not work. 
