# ESP OTA GitHub Showcase

Working example for the [ESP_OTA_GitHub library](https://github.com/yknivag/ESP_OTA_GitHub).

This repository contains the sketches and binaries set-up with the correct releases to fully demonstrate the [ESP_OTA_GitHub library](https://github.com/yknivag/ESP_OTA_GitHub).

## Hardware

The binaries attached are compiled for a Wemos D1 Mini

## Instructions

1. Download the binary from release 0.0.0 and flash it to your Wemos D1 Mini
2. Attach the D1 Mini to a Serial Monitor
3. Reset the module and confirm in the Serial Monitor that you are using version 0.0.0
4. Use the captive portal to connect the device to your WiFi network.
5. Keep watch in the Serial Monitor as the device updates.
6. Verify on reboot that the device now shows 0.0.1 as the current version number.

## Code

The sketch provided here is essentally the same as the basic example for the [ESP_OTA_GitHub library](https://github.com/yknivag/ESP_OTA_GitHub) with the addition of the captive portal for connection.  You may use it as a starting point for your project but please do be sure to update the GitHub user, repository name, expected binary file name and version to match your own repository.
