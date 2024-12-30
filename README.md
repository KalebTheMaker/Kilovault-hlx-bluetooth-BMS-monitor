# BMS Monitor for Kilovault HLX+ Batteries using ESPHome

This repository is for monitoring the Kilovault HLX+ Battery Management System via Bluetooth. These batteries have only the Android and IOS app to monitor them, and now that Kilovault has gone out of business the apps are disabled on the Google Play store and the IOS app store. There are quite a few people who have purchased these batteries, and we need a way to monitor the BMS. This method allows us to use [ESPHome](https://esphome.io/) and [Home Assistant](https://www.home-assistant.io/) to view data from the batteries in near real time.

If you are not technical and do not understand what all of this is, but would like to utilize this project, I will do my best to provide information and instruction on how to get it up and running. 

## Description of Project
This project runs on an ESP32 microcontroller by [ExpressIF](https://www.espressif.com/). The code running on the microcontroller is generated and managed by ESPHome. The microcontroller gathers data from the Kilovault Batteries and sends it to Home Assistant for collection and visualization. 

### Microcontroller
A microcontroller is a small integrated circuit, which allows a user to write custom software and run it directly on the microcontroller hardware. Some microcontrollers have WiFi and Bluetooth radios onboard which we can write software for.

**Microcontroller used for this project:** ESP-32.

**Microcontroller that has been tested:**
|Name             | Manufacturer | Devkit            |
| --------------- | -------------| ------------------|
| esp32-wroom-32u | ExpressIF    | [ESP32-DEVKITC-32U](https://www.amazon.com/dp/B0B64TWJQX) |
Links to vendors are NOT affiliate links.

### ESPHome
ESPHome is a system to control microcontrollers such as the ESP32 by simple yet powerful configuration files and control them remotely through Home Automation Systems. ESPHome will also generate the code required to run on the microcontroller and upload it to the microcontroller.

### Home Assistant
Home Assistant is a very powerful and configurable open source home automation system that can be run at home without the need of cloud services.

## Attributions
This work is not solely mine. While I have contributed some of the work, much of the code was written by [Sebastian Muszynski](https://github.com/syssi) who created an ESPHome module to work with JK BMS's, and [fancygaphtrn](https://github.com/fancygaphtrn) who modified Sebastian's code to work with the Kilovault BMS. 

My contribution to this effort is mainly in providing a complete solution in a single place with instructions (here) on how to make it work for you.

## Code base for this project
While the code resides in the above mentioned repositories, it has been modified from Sebastian's original, and is not conveniently placed in fancygaphtrn's repository. I would like this, and associated repositories to become the main project for this effort, with a single place for the solution to live and grow.

#### Contributions
Please feel free to submit pull requests for any changes that you make. This is the only method we have to monitor these batteries, and if it gets better and more stable, then we are all happy!

#### Description of code


#### Structure and subrepositories
