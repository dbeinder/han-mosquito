# µHAN mosquito
A tiny [M-BUS](https://m-bus.com/documentation-wired/04-physical-layer)-powered [ESP32-C3](https://www.espressif.com/sites/default/files/documentation/esp32-c3_datasheet_en.pdf) board to capture data from digital electricity meters. Compatible with [AmsReader](https://github.com/UtilitechAS/amsreader-firmware) firmware.

  - Power & flashing via USB-C
  - Power & meter signal via M-BUS (RJ11)
    - Input current limited to 40mA, this is probably only compatible with Kaifa meters
    - Firmware needs no energy saving, there is enough power for AP mode and OTA firmware upgrade
  - ESP32-C3-MINI-1 module: 160MHz, 4MB Flash, 320kB RAM
  - 1mm² RGB LED
  - Two side-mounted buttons
   - Top: Reset
   - Bottom: AP mode, hold during reset for bootloader
  - Mounted by magnet on the IR port ;)
  - Tested on an Austrian (Vbg) Kaifa MA309M
  
  ![proto-front](https://user-images.githubusercontent.com/342955/226060267-d9ec69e8-2e86-4415-bbc0-5e2663936821.jpg)
  ![proto-back](https://user-images.githubusercontent.com/342955/226060220-808c2063-8537-4f6c-839b-6f2d49a36215.jpg)
