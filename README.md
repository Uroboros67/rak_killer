Breakout PCB do płytki Supermini/Promicro nRF52840 z modułem Heltec HT-RA62 LoRa (oraz I2C i pomiar napięcia)

Pierwsza wersja_1 jest bez pomiaru napięcia i magistrali i2c, ale można samemu wlutować potrzebne elementy, 2 x równe rezystory około 300-500 kΩ i przewód i2c.

Druga wersja_2 ma pola PCB dla dwóch rezystorów SMD 1206 i układ pinów bezpośrednio pod i2c, jak INA219.

Ver_2_WD ma impuls HeartBeat przeniesiony na pin 1.07 w celu sterowania zewnętrznym chipem WatchDog.
Niestety HeartBaet na diodzie LED jest nieaktywny.

Po wgraniu zmodyfikowanego bootloadera możliwa jest aktualizacja oprogramowania poprzez Bluetooth.
Potrzebujesz programu „nRF Connect” z MTU = 23 i pliku firmware.zip

Powodzenia :)
-
Breakout PCB for Supermini/Promicro nRF52840 board with Heltec HT-RA62 LoRa module (and I2C and voltage measurement)

The first ver_1 is without voltage measurement and i2c bus, but you can solder the necessary elements yourself, 2 x equal resistors about 300-500 kohm and wire i2c.

The second ver_2 has PCB fields for two SMD 1206 resistors and a pinout directly under i2c like INA219.

The ver_2_WD has the HeartBeat impulse transferred to a pin 1.07 to control the external WatchDog chip.
Unfortunately, the HeartBaet on the LED is inactive.

After uploading the modified bootloader, it is possible to upgrade the firmware via Bluetooth.
You need the 'nRF Connect' program with MTU = 23 and the firmware.zip file

Good luck :)
-
Jacek SQ9ETV!
-
![IMG_20241109_134210](https://github.com/user-attachments/assets/9736826f-40d9-4fae-801a-4bcf4dfe69b7)
![IMG_20241109_134233](https://github.com/user-attachments/assets/51b732f3-c0c5-4e8d-bb65-0cf870212d62)
