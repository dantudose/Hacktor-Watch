# Hacktor-Watch
Open hardware &amp; software smartwatch

## Hardware Diagram &amp; features

<img src="https://github.com/dantudose/Hacktor-Watch/blob/main/Images/Hacktor Watch 2.0.jpg" height="500"/>

This is a open-hardware wearable based on the ESP32 microcontroller. It is fully Arduino-compatible and it comes with the following features:

* ESP32-S3 processor (dual-core 240MHz, WiFI, BLE, 512kB SRAM and 4MB Flash)
* GC9A01 1.28 inch color LCD, 240 x 240 pixels withc capacitive touch screen
* LSM6DSLTR 6-axis inertial sensor (accelerometer and gyroscope)
* W25Q256JVEIQ 32MB external SPI Flash
* ESP-PSRAM64H 8MB PSRAM
* DRV2605YZFR haptic driver
* LMD2718T261-OA1 microphone
* MAX98357 I2S audio amplifier and speaker
* MAX17048 fuel gauge
* Dual RT6160 DC/DC PMIC (main power and peripherals)
* BQ24040 LiPo charger
* 200mAh LiPo battery
* USB-C connector

## Repository Contents

* **/Hardware** - Schematic and hardware design files (Fusion360 & KiCAD)
* **/Images** - Images & diagrams
* **/Mechanical** - 3D files for the watch case

### Button Layout

 <div style='float:left'>
<table>
<thead>
  <tr>
    <th>Button</th>
    <th>ESP32 Pin</th>
  </tr></thead>
  <tbody>
  <tr>
    <td>BOOT</td>
    <td>IO0</td>
  </tr>
  <tr>
    <td>RESET</td>
    <td>EN</td>
  </tr>
  </tbody>
</table>
 </div>
<div style='float:right'>
  <img src="https://github.com/dantudose/hacktor-watch/blob/main/Images/hacktor_buttons.jpg" height="250"/> 
  </div>


## License Information

This product is _**open source**_! 

Please review the LICENSE file for license information. 

Distributed as-is; no warranty is given.
