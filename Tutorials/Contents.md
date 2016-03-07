# Tutorials Wiki

The Tutorials Wiki contains guides on a variety of Omega topics, from the basics of Linux, to how to use the Omega Expansions, to using specific software or accomplishing a certain task.

[[_TOC_]]



[//]: # (Connecting to the Omega)

# Connecting to the Omega

Taking the first step, connecting to the Omega's command line:
* [Connecting to Omega via Serial Terminal](./Connecting-to-Omega-via-Serial-Terminal)
* [Connecting to Omega via SSH](./Connecting-to-Omega-via-SSH)
  * [Adding your Public key to the Omega](./Adding-Public-Key-to-Omega)



[//]: # (Introduction to Linux)

# Introduction to Linux

This series of tutorials is meant to get you comfortable with using a Linux environment:

* [Introduction to Linux](./LinuxBasics/Linux_Intro_Part1)
* [The Command Line](./LinuxBasics/CLI_Part2)
* [The File System](./LinuxBasics/FileSystem_Part3)
* [Redirection](./LinuxBasics/Redirection_Part4)
* [Shell Scripting](./LinuxBasics/ShellScript_Part5)
* [Ownership and Permissions](./LinuxBasics/Permissions_Part6)




[//]: # (Updating the Omega)

# Updating the Omega

Follow this guide to update the Omega's firmware:
* [Omega Firmware Updates](./Updating-the-Omega)

In case your Omega's firmware gets corrupted during installation, it is possible to reflash a fresh firmware:
* [Reflash Firmware using an Ethernet Expansion](./Reflash-The-Firmware-With-Ethernet-Expansion)




[//]: # (Using the Expansions and Docks)

# Using the Docks and Expansions

The Omega's functionality can be greatly extended with the different available Docks and Expansions.

The Omega itself has an LED onboard, it can be controlled to blink in a variety of patterns:
* [Blinking Morse Code on the Omega's LED](./Blinking-Morse-Code-on-LED)

## The Expansion Dock

The Expansion Dock provides a breakout for the Omega's GPIOs, allowing you to use the Expansions or simply drive the GPIOs. It also has an RGB LED that can be programmed to show different colours:

* [How to use the GPIOs](./Using-the-GPIOs)
* [Creating PWM signals on the GPIOs](./Using-PWM-on-Exp-Dock)
* [Controlling the RGB LED](./Controlling-RGB-LED)



## The Expansions

The Expansions provide additional functionality and features to the Omega:

* [How to use the Ethernet Expansion](./Expansions/Using-the-Ethernet-Expansion)
* [How to use the Relay Expansion](./Expansions/Using-the-Relay-Expansion)
* [How to use the Servo Expansion](./Expansions/Using-the-Servo-Expansion)
* [How to use the OLED Expansion](./Expansions/Using-the-OLED-Expansion)



## The Arduino Dock

The Arduino Dock has an ATmega microcontroller and can be used just like an Arduino:

* [Initial Setup](./Arduino-Dock/Initial-Setup)
* [Using the Arduino Dock](./Arduino-Dock/Using-the-Arduino-Dock)
  * [Controlling Neopixels](./Arduino-Dock/Controlling-Neopixels)



[//]: # (The Omega and Connectivity)

# The Omega and Connectivity

The Omega is very versatile when it comes to WiFi networks, the following guides illustrate some of that flexibility:

* [Connecting to a WiFi Hotspot that requires a login](./Connecting-Omega-to-Wifi-Hotspot-that-Requres-Login)
* [Using the Omega as a Router](./Using-Omega-As-A-Router)
* [Using the Omega as a WiFi Range Extender](./Using-Omega-As-Wifi-Range-Extender)



[//]: # (Storage Space)

# Storage Space

The Omega has 16MB of flash memory, this might be a little limiting in some cases. Plugging in a USB drive to the Omega's USB Host can help alleviate this issue:
* [Using USB Storage](./Using-USB-Storage)


It is also possible to run the Omega's OS from USB storage:
* [Using USB Storage as ROOTFS](./Using-USB-Storage-as-Rootfs)



[//]: # (Using Software)

# Using Software on the Omega

Since the Omega runs a full Linux distribution, it is very flexible in the software that it can run. The following guides illustrate how to install and use different software:

* [Using Git](./Using-Git)
* [Installing Pyton](./Installing-Python)
* [Sending Emails with Python](./Sending-Emails-With-Python)

LAMP Stack:
* [Instaling the LAMP Stack on the Omega](./How-To-Install-LAMP-Stack-on-the-Omega)

PHP:
* [Using PHP on the Omega](./PHP-GPIO-Example)
* [Using PHP with PushBullet](./PHP-PushBullet-Example)



[//]: # (Reading Sensor Data)

# Reading Sensor Data

The Omega can be used with a variety of different communication protocols. I2C is supported out of the box, for others, additional work is required:

* [Using 1Wire to read sensor data](./Reading-1Wire-Sensor-Data)



[//]: # (Cross Compilation)

# Cross Compilation

The Omega can run C and C++ programs, however, it does not host a C compiler, so these programs will have to be cross-compiled on another machine and then installed on your Omega:
* [Cross Compilation](./Cross-Compile)











