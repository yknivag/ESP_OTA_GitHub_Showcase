# ESP OTA GitHub Showcase

Working example for the [ESP_OTA_GitHub library](https://github.com/yknivag/ESP_OTA_GitHub).

This repository contains the sketches and binaries set-up with the correct releases to fully demonstrate the [ESP_OTA_GitHub library](https://github.com/yknivag/ESP_OTA_GitHub).

## Hardware

The binaries attached are compiled for a Wemos D1 Mini with the memory map set to *"4MB (FS:1MB, OTA:~1019KB)"*.

## Instructions

1. Download or clone the master branch.
2. Add your WiFi credentials to the sketch.
3. Ensure the memory map os set to *"4MB (FS:1MB, OTA:~1019KB)"* ("Tools" -> "Flash Size" in the Arduino IDE.
4. Use "Tools" -> "ESP8266 Sketch Data Upload" to add the certificate file in the data directory of the sketch to your board.
5. Attach the D1 Mini to a Serial Monitor at 115200 baud.
6. Compile and upload the code.
7. When the board resets you will see it print to the Serial monitor that it is version 0.0.0.
8. Keep watch in the Serial Monitor as the device updates.
9. Verify on reboot that the device now shows 0.1.0 as the current version number.

## Code

The sketch provided here is essentally the same as the basic example for the [ESP_OTA_GitHub library](https://github.com/yknivag/ESP_OTA_GitHub).  You may use it as a starting point for your project but please do be sure to update the GitHub user, repository name, expected binary file name and version to match your own repository.
