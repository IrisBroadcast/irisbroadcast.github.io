![IRIS Broadcast](../logo-iris.png)

[Home](../README.md) - [IRIS Platform](../README_IRIS.md) - [About ACIP](../README_ABOUT.md) - Ophrys Signage - [Larkspur EmBER+ Provider](../larkspur/README_LARKSPUR.md) - [Contributers](../README_CONTRIBUTERS.md)


# Ophrys Signage

* Web Site: https://www.irisbroadcast.org/ophrys
* Github: [Github.com/irisbroadcast/OphrysSignage](https://github.com/IrisBroadcast/OphrysSignage)

A simple way to display a webpage on a screen without all the fuzz.
Basic signage solution with configuration page for url selection,
screen rotation and option to fetch configuration settings from
external server. We are using it with Linux Debian Buster on
Raspberry Pi 3 and 4. This should work fine on other hardwares
as well. Let us know if you run into any problems or have any questions.

We use it to display system monitoring and door-signage for our broadcast studios.

![Ophrys Signage Screenshot](signage-screenshot.png)

#### Components
- Whiptail install script (guides the installation of dependencies)
- Debian + OpenBox + LightDM + Xserver
- Chromium Browser + OMXPlayer
- NodeJs server for configuration
- Bash scripts for setting URLs and screen rotation

#### Features
- Fullscreen browser without window decorations
- Boot image on system start (Ophrys graphics)
- Rotate screen on both Raspberry Pi 3 and 4 without reboot
- Load a configuration JSON from an external site with settings
- REST API for page refresh and */health* endpoint for status information
- Built in multi webpage iframe view, with transitioning abilities
- Built in webpage with a studio-clock

## Download Ophrys installer
Get the installer here [Download Ophrys installer ](http://irisbroadcast.com/ophrys/install.tar.gz)

Find the install instructions here [Oprhys - How to get started ](https://github.com/IrisBroadcast/OphrysSignage/blob/master/README.md#how-to-get-started-using-a-raspberry-pi)
