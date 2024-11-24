Breakout PCB for Supermini/Promicro nRF52840 board with Heltec HT-RA62 LoRa module (and I2C and voltage measurement)

The first ver_1 is without voltage measurement and i2c bus, but you can solder the necessary elements yourself, 2 x equal resistors about 300-500 kohm and wire i2c.

The second ver_2 has PCB fields for two SMD 1206 resistors and a pinout directly under i2c like INA219.

The ver_2_WD has the HeartBeat impulse transferred to a pin 1.07 to control the external WatchDog chip.
Unfortunately, the HeartBaet on the LED is inactive.

After uploading the modified bootloader, it is possible to upgrade the firmware via Bluetooth.
You need the 'nRF Connect' program with MTU = 23 and the firmware.zip file

Good luck :)

Jacek SQ9ETV!

![IMG_20241109_134210](https://github.com/user-attachments/assets/9736826f-40d9-4fae-801a-4bcf4dfe69b7)
![IMG_20241109_134233](https://github.com/user-attachments/assets/51b732f3-c0c5-4e8d-bb65-0cf870212d62)
