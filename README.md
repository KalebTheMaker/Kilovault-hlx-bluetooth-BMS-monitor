# BMS Monitor for Kilovault HLX+ Batteries using ESPHome

This repository is for monitoring the Kilovault HLX+ Battery Management System via Bluetooth. These batteries have only the Android and IOS app to monitor them, and now that Kilovault has gone out of business the apps are disabled on the Google Play store and the IOS app store. There are quite a few people who have purchased these batteries, and we need a way to monitor the BMS. This method allows us to use [ESPHome](https://esphome.io/) and [Home Assistant](https://www.home-assistant.io/) to view data from the batteries in near real time.

If you are not technical and do not understand what all of this is, but would like to utilize this project, I will do my best to provide information and instruction on how to get it up and running. 

## Description of Project
This project runs on an ESP32 microcontroller by [ExpressIF](https://www.espressif.com/). The code running on the microcontroller is generated and managed by ESPHome. The microcontroller gathers data from the Kilovault Batteries and sends it to Home Assistant for collection and visualization. 

## Attributions
This work is not solely mine. While I have contributed some of the work, much of the code was written by [Sebastian Muszynski](https://github.com/syssi) who created an ESPHome module to work with JK BMS's, and [fancygaphtrn](https://github.com/fancygaphtrn) who modified Sebastian's code to work with the Kilovault BMS. 

My contribution to this effort is mainly in providing a complete solution in a single place with instructions (here) on how to make it work for you.

## Code and Contributions
Please see the [WIKI](../../wiki/Code-and-Contributing) for more information on Code and Contributions
