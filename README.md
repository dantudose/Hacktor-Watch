# Hacktor-Watch
A stylish open hardware &amp; software smartwatch, designed by makers for makers.

<div style='float:center'>
  <img src="https://github.com/dantudose/hacktor-watch/blob/main/Images/20250808_133324.jpg" height="350"/> 
  </div>

## Hardware Diagram &amp; features

<img src="https://github.com/dantudose/Hacktor-Watch/blob/main/Images/Hacktor Watch 2.0.jpg" height="500"/>

This is a open-hardware wearable based on the ESP32 microcontroller. It is fully Arduino-compatible and it comes with the following features:
* <a href="https://www.espressif.com/sites/default/files/documentation/esp32-s3_datasheet_en.pdf">ESP32-S3</a> processor (dual-core 240MHz, WiFI, BLE, 512kB SRAM and 4MB Flash)
* <a href="https://www.aliexpress.com/item/1005007293053050.html">GC9A01</a> 1.28 inch color LCD, 240 x 240 pixels with CST816T capacitive touch screen
* <a href="https://www.st.com/en/mems-and-sensors/lsm6dsl.html">LSM6DSLTR</a> 6-axis inertial sensor (accelerometer and gyroscope)
* <a href="https://www.winbond.com/hq/product/code-storage-flash-memory/serial-nor-flash/?__locale=en&partNo=W25Q256JV">W25Q256JVEIQ</a> 32MB external SPI Flash
* <a href="https://cdn-shop.adafruit.com/product-files/4677/4677_esp-psram64_esp-psram64h_datasheet_en.pdf">ESP-PSRAM64H</a> 8MB PSRAM
* <a href="https://www.ti.com/product/DRV2605/part-details/DRV2605YZFR">DRV2605YZFR</a> haptic driver
* <a href="https://jlcpcb.com/api/file/downloadByFileSystemAccessId/8586212537977618432">LMD2718T261-OA1</a> microphone
* <a href="https://www.analog.com/media/en/technical-documentation/data-sheets/max98357a-max98357b.pdf">MAX98357</a> I2S audio amplifier and speaker
* <a href="https://www.analog.com/media/en/technical-documentation/data-sheets/max17048-max17049.pdf">MAX17048</a> fuel gauge
* Dual <a href="https://www.richtek.com/m/Products/Switching%20Regulators/Buck-Boost%20Converter/RT6160A?sc_lang=en">RT6160</a> DC/DC PMIC (main power and peripherals)
* <a href="https://www.ti.com/lit/ds/symlink/bq24040.pdf?ts=1754753213993">BQ24040</a> LiPo charger
* 200mAh LiPo battery
* USB-C connector for charging and data

<div id="cover">
  <img src="https://github.com/dantudose/Hacktor-Watch/blob/main/Images/perspective2.png" height="300"/> 
  <img src="https://github.com/dantudose/Hacktor-Watch/blob/main/Images/exploded_view.png" height="300"/>
  <img src="https://github.com/dantudose/Hacktor-Watch/blob/main/Images/side_assy.png" height="300"/> 
</div>

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
  <img src="https://github.com/dantudose/hacktor-watch/blob/main/Images/hacktor_buttons.jpg" height="350"/> 
  </div>

## Software Support
The watch supports Arduino and ESP-IDF programming. For a working NuttX port, check out <a href="https://github.com/radupascale">Radu Pascale's</a> github page. 

## License Information

This product is _**open source**_! 

Please review the LICENSE file for license information. 

Distributed as-is; no warranty is given.
