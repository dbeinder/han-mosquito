# µHAN mosquito

> **_Aus Österreich?:_** Ich habe noch einige Module übrig, bei Interesse bitte Email an david(at)beinder.at
> 
>  Inkl. Versand 37€ für 1 Stk, dann +15€ für jedes weitere. Privatverkauf, Bastellösung, keine Gewährleistung, etc ;)

A tiny [M-BUS](https://m-bus.com/documentation-wired/04-physical-layer)-powered [ESP32-C3](https://www.espressif.com/sites/default/files/documentation/esp32-c3_datasheet_en.pdf) board to capture data from digital electricity meters. Compatible with [AMS reader](https://github.com/UtilitechAS/amsreader-firmware) firmware.

  - Power & flashing via USB-C
  - Power & meter signal via M-BUS (RJ11)
    - Input current limited to 40mA, this is probably only compatible with Kaifa meters
    - Firmware needs no aggressive WiFi power management, there is enough for AP mode and OTA firmware upgrade
  - ESP32-C3-MINI-1 module: 160MHz RISC-V core, 4MB Flash, 400kB RAM, 2.4GHz WiFi
  - 1mm² RGB LED
  - Two side-mounted buttons
    - Top: ESP32 reset
    - Bottom: AP mode, hold during reset to flash
  - Mounted by magnet on the IR port
  - Tested on an Austrian (Vbg) Kaifa MA309M
  - Designed in KiCad 7
  
License: free to use and modify for non-commercial use

![panel](https://user-images.githubusercontent.com/342955/234837384-dd8bcc59-4c91-4d21-b3d1-55f3d78f4bea.jpg)
![proto-mounted](https://user-images.githubusercontent.com/342955/226061390-f7ff8e88-6779-4742-96a4-bf8edfa9e282.jpg)

###  Prototype pictures
  
| ![proto-front](https://user-images.githubusercontent.com/342955/226060267-d9ec69e8-2e86-4415-bbc0-5e2663936821.jpg)  | ![proto-back](https://user-images.githubusercontent.com/342955/226060220-808c2063-8537-4f6c-839b-6f2d49a36215.jpg) |
| ------------- | ------------- |
| ![image](https://user-images.githubusercontent.com/342955/226062623-08615a8e-ff71-4c6f-b636-feafea7a7d91.png)  | |


