Breakout PCB do płytki Supermini/Promicro nRF52840 z modułem Heltec HT-RA62 LoRa (oraz I2C i pomiar napięcia)
z polami PCB dla dwóch rezystorów SMD 1206 i układ pinów bezpośrednio pod i2c, jak INA219.

W katalogu "bootloader" sa dwa pliki jeden oryginalny, drugi zmodyfikowany do wgrywania firmware po BT.
Po wgraniu zmodyfikowanego bootloadera możliwa jest aktualizacja oprogramowania poprzez Bluetooth.
Potrzebujesz programu „nRF Connect” z MTU = 23 i pliku firmware.zip lub program 'DFU' z liczbą pakietów ustawioną na 10.

Katalog "SoftDevice" to pliki BIOS do układów nRF52. Wersja oryginalna znajdująca się w modułach ProMicro to s140 6.1.1.
Najnowsza którą można wgrać to s140 7.3.0. Firmware Meshtastic nie jest zamienny, pod odpowiedni BIOS należy wgrać odpowiednią
wersję firmwaru, albo z katalogu "ver_V2" albo "wer_V2_(SoftDevice7.3)". Polecam pozostać przy 6.1.1 aczkolwiek teoretycznie
wersja 7.3.0 powinna mieć poprawki i być bardziej stabilna.

Właściwy Firmware Meshtastic to katalogi "ver_V2" dla oryginalnych ProMicro bez modyfikacji BIOSu oraz "ver_V2_(SSoftDevice7.3.0)
dla ProMicro ze zmodyfikowanym BIOSem.

Powodzenia :)
-
Breakout PCB for Supermini/Promicro NRF52840 tile with HELTEC HT-RA62 Lora module (and I2C and voltage measurement)
with PCB fields for two SMD 1206 resistors and pins system directly under I2C, such as ina219.

In the "bootloader" directory there are two original files, the other modified to upload firmware after BT.
After uploading a modified bootloader, it is possible to update the software via Bluetooth.
You need "nrf Connect" from MTU = 23 and firmware.zip file or 'DFU' program with the number of packages set up to 10.

The "Softdevice" directory is BIOS files for NRF52 systems. The original version in the Promicro modules is S140 6.1.1.
The latest one can be uploaded is S140 7.3.0. Firmware meshtastic is not replacement, the appropriate bios should be uploaded to the appropriate bios
Version of firmwar or from the "Ver_V2" or "Wer_V2_ (Softdevice7.3) catalog". I recommend staying at 6.1.1 but theoretically
Version 7.3.0 should have corrections and be more stable.

The right firmware Meshtastic is "VER_V2" catalogs for the original Promicro without bios modification and "Ver_V2_ (SSOFTDEVICE7.3.0)
for Promicro with a modified bios.

Good luck :)
-
Jacek SQ9ETV!
-
![IMG_20241109_134210](https://github.com/user-attachments/assets/9736826f-40d9-4fae-801a-4bcf4dfe69b7)
![IMG_20241109_134233](https://github.com/user-attachments/assets/51b732f3-c0c5-4e8d-bb65-0cf870212d62)
